# Talend_Projects

This repository contains a collection of ETL (Extract, Transform, Load) projects developed using **Talend Open Studio for Data Integration (TOS_DI) 8.0.1**.

Each project in this repository demonstrates key ETL operations such as:

- 🔌 Connecting to various data sources (CSV, Excel, MySQL, SQL Server, Oracle, etc.)
- 🔄 Transforming data (filtering, joining, mapping, aggregating, validating, etc.)
- 📤 Loading cleaned and transformed data into target destinations

---

## 📁 Folder Location

All Talend project folders are stored here on your local machine:
C:/Users/your_username/OneDrive/Documents/Talend_Projects


You can import them directly into Talend using the built-in import tools.

---

## 🚀 How to Open Projects in Talend

1. Open **Talend Open Studio for Data Integration** (version 8.0.1)
2. Select or create your workspace.
3. Go to `File > Import Items`.
4. Browse to:  
   `C:/Users/palak/OneDrive/Documents/Talend_Projects`
5. Select all available projects and click **Finish**.

---

## 🧪 Example Project Types (Replace with real project names)

- `CustomerData_Cleanup` – Cleans and standardizes customer records
- `Sales_ETL_Job` – Loads and transforms monthly sales data into SQL Server
- `Employee_DB_Sync` – Synchronizes employee data between CSV and MySQL
- `CSV_to_Oracle` – Validates and transfers CSV rows to Oracle DB

---

## 🛠️ Requirements

To run or modify these projects, make sure you have:

- ✅ [Talend Open Studio for Data Integration 8.0.1](https://www.talend.com/products/data-integration/)
- ✅ Java JDK 8 or 11
- ✅ Required database drivers (JDBC connectors for MySQL, Oracle, etc.)

---

## 📦 Exporting a Job from Talend

To export a job as a ZIP:

1. Right-click the job in the Talend `Repository` panel.
2. Select **Export Job**.
3. Choose `.zip` as the export format and save.

> Avoid uploading exported ZIPs larger than 100MB to GitHub. Instead, keep them locally or use Git LFS.

---

## 📝 Notes

- Do **NOT** place Talend project folders inside `C:\Program Files (x86)\...` due to permission issues.
- Always commit `.item`, `.properties`, and `.xml` files to preserve job metadata.
- Avoid uploading the `/lib` folder unless necessary—it contains heavy dependency files.

---

## 📄 License

These projects are created for learning and demonstration purposes.  
Feel free to use them for academic or non-commercial use.

---
