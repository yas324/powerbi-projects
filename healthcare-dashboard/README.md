# 🏥 Healthcare Analytics Dashboard - Power BI

## 📌 Overview
This project presents a **Healthcare Analytics Dashboard** built in **Power BI**, providing end-to-end insights into patient demographics, medical history, doctor workload, clinical operations, revenue generation, and individual patient reports. The dashboard is divided into three reports:

1. **Healthcare Overview**
2. **Doctor Report**
3. **Patient Report**

---

## 🏥 1. Healthcare Overview Report

This Healthcare Overview Report provides an end-to-end view of the healthcare dataset, focusing on patient statistics, test results, diagnosis, treatment, and revenue performance. It is designed to help healthcare professionals and administrators analyze patient demographics, treatment outcomes, and cost efficiency.

---

## 🖼️ Snapshot

![healthcare-dashboard](./1_Overview%20Report.JPG)

*Snapshot of Healthcare Overview Dashboard created in Power BI.*

---

## ⚡ Key Features

* **KPI Cards** showing Total Patients, Total Revenue, Follow-Up Rate, Treatment Cost per Visit, and Average Age.
* **Gauge Charts** to track Abnormal Test Rate % and Emergency Rate % with YoY comparisons.
* **Trend Analysis** using Line Chart for Total Patients by Month.
* **Dynamic Filters (Slicers):** Year, Test Result, and Diagnosis.
* **Parameter-based Analysis:**

  * **Donut Chart** → Gender, Blood Type, and Diagnosis by Total Patients.
  * **Treemap Chart** → Test Type, Treatment Type, and Visit Type by Total Patients.
* **Age Group Analysis** using Column Chart for Total Patients across different age ranges.

---

## 📊 KPIs & Metrics Used

* **Total Patients:** 10K (YoY +93.27%)
* **Total Revenue:** 25.41M (YoY +92.66%)
* **Follow-Up Rate:** 49.84%
* **Treatment Cost per Visit:** 2,541
* **Average Age:** 49
* **Abnormal Test Rate %:** 33.54%
* **Emergency Rate %:** 20.16%

---

## 📈 Visuals & What They Show

* **Line Chart:** Monthly patient trends across different time periods.
* **Gauge Charts:** Performance of abnormal test rate % and emergency rate % compared to targets.
* **Donut Chart:** Distribution of patients by Gender, Blood Type, and Diagnosis.
* **Treemap:** Visit types (Emergency, Follow-up, Routine Check, Chronic Pain, etc.) and treatment types.
* **Column Chart:** Patient distribution by age group (0–18, 19–30, 31–45, 46–60, 61–75, 76+).

---

## 🔑 Key Insights

* Majority of patients fall in the **31–60 age group**.
* **Abnormal test rate (33.54%)** indicates a significant number of critical cases.
* **Follow-up rate is below 50%**, suggesting patient retention opportunities.
* **Revenue growth is strong (92.66% YoY)**, aligning with increased patient visits.
* Emergency visits are still notable at **20.16%**, highlighting the need for preventive care measures.

---

## 🩺 2. Doctor Report
The Doctor Report provides insights into clinical operations, doctor workload, patient visits, and prescribed medications. It helps administrators track doctor specializations, clinic distribution, and the impact of medication prescriptions on revenue and patient outcomes.

---

## 🖼️ Snapshot

![healthcare-dashboard](./2_Doctor%20Report.JPG)
*Snapshot of Doctor Report created in Power BI.*

---

## ⚡ Key Features

* **KPI Cards**: Total Doctors, Total Visits, Doctor Workload, Total Lab Tests.
* **Filters (Slicers):** Visit Type, City, State, Specialization, Medication Prescribed.
* **Map Visualization:** Clinics by State and City with patient distribution.
* **Tables for Detailed View:**

  * **Table 1:** Prescribed Medicines, Dosage, Revenue, and Patient Count.
  * **Table 2:** Clinics, Visit Type, and Total Patients.
  * **Table 3:** Doctor Name, Specialization, and Experience.
* **Navigation Buttons:** Seamless navigation to **Overview Report** and **Patient Report**.

---

## 📊 KPIs & Metrics Used

* **Total Doctors:** 1,000
* **Total Visits:** 10,000
* **Doctor Workload:** 10
* **Total Lab Tests:** 10,000

---

## 📈 Visuals & What They Show

* **Map Chart:** Clinics and patient distribution across US states and cities.
* **Medicine Table:** Most prescribed medicines and their contribution to revenue.
* **Clinic Table:** Visit types and patient counts by clinic.
* **Doctor Table:** Doctors categorized by specialization and years of experience.

---

## 🔑 Key Insights

* High dependency on medicines like **Omeprazole and Metformin**, generating significant revenue.
* Clinics see varied patient volumes, with **follow-up and emergency visits** being the most frequent.
* Specialist distribution shows a balance between **Cardiology, Neurology, and Orthopedics**.
* Doctor workload remains consistent at an average of **10 patients per doctor**.

---

## 👩‍⚕️ 3. Patient Report
The Patient Report is designed to provide a detailed **patient-level view**, showcasing demographics, health conditions, insurance details, and medical history. This helps in understanding individual patient records for quick reference and care management.

---

## 🖼️ Snapshot

![healthcare-dashboard](./3_Patient%20Report.JPG)
*Snapshot of Patient Report created in Power BI.*

---

## ⚡ Key Features

* **Patient Demographics:** Age, Gender, Marital Status, Blood Type, Date of Birth, City, State.
* **Medical Information:** Medical History, Chronic Conditions, Allergies, Test Type, Visit Type, Test Result.
* **Insurance Details:** Insurance Provider, Policy Number.
* **Button Slicer:** Patient ID selector for easy filtering of individual patient records.
* **Navigation Buttons:** Links to **Overview Report** and **Doctor Report**.

---

## 📊 Example Patient Data of Patient ID:100105 (Shown in Snapshot)

* **Name:** Kristin Gonzales
* **Age:** 23
* **Gender:** Female
* **Marital Status:** Divorced
* **Blood Type:** B+
* **Medical History:** Diabetes
* **Chronic Condition:** Asthma
* **Allergies:** Peanuts
* **Visit Type:** Emergency
* **Test Type:** CT Scan
* **Test Result:** Pending
* **Insurance Provider:** Brown Ltd
* **Policy Number:** POL468623

---

## 📈 Visuals & What They Show

* **Patient Card Layout:** Displays each patient’s demographic and medical information in a structured format.
* **ID Slicer:** Allows quick navigation between patients by selecting their Patient ID.

---

## 🔑 Key Insights

* Provides **individual patient-level data** rather than aggregated summaries.
* Helps doctors/administrators **quickly filter and review** patient-specific details.
* Enhances decision-making with **full visibility of health history and insurance details**.

---

## 🛠️ Tools & Technology Used

* **Power BI** → Data Modeling, DAX, Interactive Visualizations
* **Bing Maps Integration** → For Clinic Distribution
* **DAX Measures:** Patients, Revenue, Abnormal Rate %, Emergency Rate %, YoY Growth %
* **Navigation Buttons** → Seamless movement across reports
* **Data filters** → Interactive exploration

---

## 🗂️ Data Fields Used

Across the three dashboards (Healthcare Overview, Doctor Report, Patient Report), the following data fields were utilized:

* **Patient Information:** Patient ID, Name, Age, Gender, Marital Status, Blood Type, Date of Birth, City, State.
* **Medical Details:** Diagnosis, Test Result, Test Type, Treatment Type, Visit Type, Chronic Conditions, Allergies, Medical History.
* **Doctor Information:** Doctor Name, Specialization, Years of Experience, Workload.
* **Clinic Information:** Clinic Name, City, State, Visit Type.
* **Financial Data:** Total Revenue, Treatment Cost, Medication Prescribed, Dosage, Policy Number, Insurance Provider.
* **Time Fields:** Year, Month (for trend analysis).

---

## 🎛️ Interactivity & Design

* **Filters (Slicers):**

  * *Healthcare Overview:* Year, Test Result, Diagnosis.
  * *Doctor Report:* Visit Type, City, State, Specialization, Medication Prescribed.
  * *Patient Report:* Patient ID button slicer for quick selection.
* **Parameters:**

  * Donut chart → Gender, Blood Type, Diagnosis.
  * Treemap → Test Type, Treatment Type, Visit Type.
* **Navigation Buttons:** Enabled seamless page navigation between **Healthcare Overview ↔ Doctor Report ↔ Patient Report**.
* **Dynamic Visuals:**

  * Gauge charts for Abnormal Test Rate % and Emergency Rate %.
  * Line chart for monthly trends.
  * Map visual for clinic distribution.
  * Patient card layout for detailed medical records.
* **Design Choices:**

  * Consistent **color theme** across all reports for readability.
  * **Card visuals** for key KPIs.
  * **Interactive slicers & buttons** for user-friendly exploration.
  * Structured layout (KPIs on top, detailed visuals below).

---

## 🏷️ Tags

`#PowerBI` `#Healthcare Analytics` `#Patient Dashboard` `#Dashboard` `#Data Visualization` `#KPIs`  `#DAX`

---
## 🎯 Click Below to Explore the Dashboard  

<p align="left">
  <img src="https://img.icons8.com/color/48/000000/power-bi.png" alt="Power BI" width="35"/>
  <a href="https://app.powerbi.com/groups/me/reports/0459dd22-cd56-4f44-80cd-04b158ff8442/e42cb886ca555b04acbc?experience=power-bi" target="_blank">
    🚀 Launch Live Dashboard
  </a>
</p>

---
## <img src="https://img.icons8.com/ios-glyphs/30/000000/guest-male.png" alt="Author Icon"/> Author


**Syed Yaseen**  
*Aspiring Data Analyst | Power BI | Excel | SQL | Tableau*

<a href="https://syedyaseen324.carrd.co/">
  <img src="https://github.com/yas324/AboutMe_SyedYaseen/blob/main/Badge%201.png" alt="Badge" width="150">
</a>

⭐ **Don't forget to star the repo if you found it helpful!**


