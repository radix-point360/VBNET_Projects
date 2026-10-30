# Legacy-to-Web Data Migration Utility

A robust VB.NET Windows Forms desktop utility designed to streamline the migration of customer data from legacy desktop applications to modern web-based platforms. 

Due to architectural evolution and database schema normalizations between the legacy desktop system and the new web application, direct database restoration or simple SQL scripts are often insufficient. This tool automates the extraction, transformation, and formatting of legacy data tables to perfectly align with the target web application's database schema.

---

## 🚀 Key Features

* **Schema Mapping & Transformation:** Automatically maps legacy tables and columns to the updated web application database structure.
* **Data Validation & Sanitization:** Validates data types, handles null constraints, and cleans up legacy formatting inconsistencies prior to export.
* **User-Friendly WinForms Interface:** Provides a clean, step-by-step wizard UI allowing operators to select data modules, monitor real-time extraction logs, and view error reports.
* **Configurable Connections:** Securely connects to both local/remote legacy databases and target staging/production web databases using configurable connection strings.
* **Detailed Error Logging:** Generates comprehensive execution logs and exception reports for troubleshooting failed records during migration.

---

## 🛠️ Tech Stack

* **Language:** VB.NET (.NET Framework 4.8)
* **UI Framework:** Windows Forms (WinForms)
* **Data Access:** ADO.NET
* **Database Support:** Microsoft SQL Server.
