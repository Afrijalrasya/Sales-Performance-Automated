# 🧾 Power BI Report Automation (Local Desktop)

This project demonstrates a **local automation workflow** to generate and deliver business reports using:
- **SQL Server** for structured data storage
- **Power BI Desktop** for dashboard creation
- **Power Automate Desktop (PAD)** for automating PDF export and email delivery

> ✅ This solution works **offline**, without the need for Power BI Service or cloud resources.

---

## 🧭 Workflow Overview

![Workflow Diagram](docs/Arsitektur-Project.png)

---

## 📁 Project Structure

    ```plaintext
    automated-reporting-desktop-stack/
    │
    ├── data/                    # Sample data
    ├── docs/                     # Architecture diagram, process docs
    ├── automation/              # PAD flows, step-by-step
    ├── output/                  # Sample exported reports (PDF)
    ├── pbix/                 # Power BI Dashboard file (.pbix)
    ├── scripts/                 # SQL ETL or cleanup scripts
    ├── LICENSE
    ├── README.md


##🧠 Author

Afrijal Rasya

[![LinkedIn](https://img.icons8.com/?size=100&id=60ZV_wYC0BM2&format=png&color=000000)](https://www.linkedin.com/in/afrijalrasyaputra)

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

### 📌 Note

> 💡 **Cloud Upgrade Available**  
This project is designed for local execution using Power BI Desktop and Power Automate Desktop.  
However, the entire workflow can be migrated to the **Power BI Service** and **Power Automate (Cloud)** environment with a **Power BI Pro account**, enabling:

- ✅ Scheduled report refresh via **Power BI Gateway**
- ✅ Automatic PDF export using **Power Automate (Cloud)**
- ✅ Cloud-based email delivery without local dependencies


![Power BI](https://img.shields.io/badge/tool-PowerBI-yellow)
![SQL Server](https://img.shields.io/badge/database-SQL--Server-blue)
![Power Automate Desktop](https://img.shields.io/badge/automation-PAD-lightgrey)
