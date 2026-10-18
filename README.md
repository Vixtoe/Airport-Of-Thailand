# Enterprise Architecture Repository (EA Repository) — Low-Code Platform

![Platform](https://img.shields.io/badge/Platform-Microsoft%20Power%20Apps-0078D4?style=flat-square&logo=microsoftpowerapps&logoColor=white)
![Backend](https://img.shields.io/badge/Backend-SharePoint%20Lists-037A76?style=flat-square&logo=microsoftsharepoint&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-Power%20Automate-0078D4?style=flat-square&logo=powerautomate&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)

An enterprise-grade tracking, management, and business intelligence reporting application developed for **Airports of Thailand Public Company Limited (AOT)**[cite: 1, 9] during a summer internship within the **Technology and Communications Strategy Department (ฝ่ายกลยุทธ์เทคโนโลยีและการสื่อสาร)**[cite: 3, 7, 15].

The system streamlines IT inventory management, operational workflows, alignment mapping, and executive dashboard analytics across AOT's enterprise architecture[cite: 9, 13, 17].

---

## Project Overview

- **Organization:** Airports of Thailand Public Company Limited (AOT)[cite: 1, 19]
- **Department:** Technology and Communications Strategy Department[cite: 3, 7, 15]
- **Developer:** Chanoudom Tann[cite: 1]
- **Duration:** June 1, 2026 – July 31, 2026 (37 working days / 333 hours)[cite: 3, 15]
- **Academic Context:** Electrical and Data Engineering (TEPE), Thammasat University[cite: 1]

---

## Documentation & Assets

### Executive Poster
![AOT Summer Internship Poster](./summer_Internship_Poster.jpg)

### Full Technical Report
<details>
  <summary><b>Click to expand full 18-page Internship Report</b></summary>
  <br>
  <img src="./Summer%20Internship%20Report_page-0001.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0002.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0003.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0004.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0005.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0006.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0007.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0008.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0009.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0010.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0011.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0012.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0013.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0014.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0015.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0016.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0017.jpg" width="100%">
  <img src="./Summer%20Internship%20Report_page-0018.jpg" width="100%">
</details>

---

## Key Features

### 1. Centralized Data Entry & Form Management
- **Authentication & Access:** Secure login module with session management[cite: 11].
- **Application Registry:** Comprehensive data collection for enterprise applications, organizational units (โครงสร้างฝ่าย), and operational dependencies[cite: 11].
- **State Management:** Custom check-box logic, dynamic drop-downs, and real-time record editing with validation rules[cite: 11, 15].

### 2. Workflow Automation
- **Event Alerts:** Automated login notifications and event triggers built via Power Automate[cite: 10, 12].
- **Daily Status Reporting:** Scheduled automated daily activity reports sent via Microsoft Outlook at 17:30[cite: 10, 12, 17].

### 3. Executive Dashboards & Analytics
- **IT Inventory Overview:** Real-time visibility into active, under-development, high-priority, and PDPA-related systems[cite: 13].
- **Application Portfolio Report:** Filtered views detailing application categories and system types[cite: 13, 14].
- **Business Alignment Report:** Strategy mapping showing how digital applications support overarching corporate objectives[cite: 13, 17].
- **Security & GRC Report:** Monitoring metrics for Governance, Risk, and Compliance[cite: 13, 17].
- **Data & PDPA Compliance Report:** Tracking systems containing personally identifiable information (PII) to align with data privacy regulations[cite: 13, 17].
- **Infrastructure & Digital Tech Reports:** Visualizations tracking underlying platform infrastructure and technology stack distributions[cite: 13, 17].

---

## Tech Stack & Tools

- **Frontend / App Framework:** Microsoft Power Apps (Canvas Apps, Power Fx formulas, custom UI/UX design)[cite: 9, 12, 14, 19]
- **Backend / Database:** SharePoint Lists (Relational cloud database structure, schema mapping)[cite: 9, 11, 14, 16]
- **Automation Engine:** Microsoft Power Automate & Microsoft Outlook Integration[cite: 9, 12, 14]
- **UI Prototyping & Flow Design:** Figma[cite: 9, 10, 14]

---

## Technical Challenges & Solutions

| Issue / Challenge | Root Cause | Solution Implemented |
| :--- | :--- | :--- |
| **Data Submission Errors** | Connection mismatches and unvalidated required fields in Power Apps form cards[cite: 15]. | Reconfigured data mapping, overhauled patch formulas, and added strict field validation[cite: 15]. |
| **Checkbox State Issues** | Conflicts between `Default` items and reset properties across form components[cite: 15, 19]. | Re-bound control formulas, updated `Default` bindings, and tested state behaviors thoroughly[cite: 15, 19]. |
| **Workflow Delays** | Time-zone offset discrepancies and trigger condition mismatches in Power Automate[cite: 15, 19]. | Corrected recurrence schedules, adjusted time zones to UTC+7, and set proper trigger conditions[cite: 15, 19]. |

---

## Future Enhancements

1. **Role-Based Access Control (RBAC):** Implement granular access tiers to restrict administrative editing based on user department level[cite: 18].
2. **Power BI Analytics:** Connect the SharePoint backend directly to Power BI for advanced predictive modeling and dynamic corporate visualizations[cite: 18].
3. **Automated Error Logging:** Create a dedicated log list in SharePoint to automatically track runtime exceptions[cite: 18].
