# 🚀 MergeX - Smart Mail Merge for Microsoft Word

MergeX is a professional, cloud-powered Microsoft Word Add-in designed to automate document generation. It allows you to merge Excel data into Word templates seamlessly with one click, featuring smart file naming and ZIP packaging.

---

### ✨ Key Features
- **One-Click Bulk Merge:** Generate dozens of documents instantly from a single Excel sheet.
- **Smart File Naming:** Automatically names each generated file based on specific columns in your Excel data.
- **Instant ZIP Download:** All merged documents are packaged into a single ZIP file for easy organization.
- **Cloud Powered:** No heavy installation. Works directly within Word Online and Desktop via a secure manifest.
- **Data Privacy:** Processing happens in your browser. We do not store your document or Excel data.

---

### 📦 How to Install
Microsoft Office interfaces vary between **Personal** and **Work/School** accounts. Follow these steps to install MergeX:

1. **Download** the `manifest.xml` file from this repository.
2. **Open Microsoft Word** (Online or Desktop).
3. **Locate the Add-ins Menu:**
   - Look for the **Add-ins** icon on the **Home** tab.
   - If not visible, go to the **Insert** tab and select **Add-ins**.
4. **Upload the Manifest:**
   - Click on **Add-ins** -> **More Add-ins** (if applicable).
   - Go to the **My Add-ins** tab.
   - Click **Manage My Add-ins** (top right) and select **Upload My Add-in**.
5. **Select** the `manifest.xml` file you downloaded.
6. The **MergeX** icon will now appear in your **Home** tab ribbon.

---

### 📖 User Guide
1. **Prepare your Template:** Use curly braces `{}` in your Word document to define fields (e.g., `{Name}`, `{Employee_ID}`, `{Department}`).
2. **Prepare your Data:** Ensure your Excel column headers match the names inside the braces exactly.
3. **Run MergeX:** Open the Add-in, upload your Excel file, and hit **Generate Documents**.
4. **Download:** Once processing is complete, download the ZIP file containing all your personalized documents.

---

### 🌐 How it Works
MergeX is a cloud-hosted Office Add-in. The `manifest.xml` file points to a secure hosted environment on Vercel. This allows the add-in to function without requiring you to host the code yourself.

---

### 📄 License & Credits
Developed by **Nisala Deshan**.

This project is licensed under **Creative Commons Attribution-NoDerivs 4.0 International (CC BY-ND 4.0)**.
- **Attribution:** You must give appropriate credit.
- **NoDerivatives:** If you remix, transform, or build upon the material, you may not distribute the modified material.

For support or feedback, please visit the repository's issues page.
