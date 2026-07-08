# 🏥 HealthPulse Analytics

An interactive healthcare analytics dashboard built with **Power BI**, analysing patient demographics, insurance coverage, and registration trends across 10 Nigerian states between **2019 and 2024**.

---

## 📊 Live Dashboard

👉 **[View the Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMWFhZTM3MmItODhhNC00NjlkLWI3MDEtYmY3MjljMTg2MDVmIiwidCI6IjA3M2U1ODhkLTI4NmMtNDAwNS04ZmYwLWYyYWMzYzhlYTRkMyJ9)**

---

## 📁 Project Structure

```
HealthPulse-Analytics/
│
├── 01_Patient Demographics.xlsx                  # Source dataset (2,000 patient records)
├── HealthPulse Patient Demographics.pbit         # Power BI template file
├── HealthPulse Patient Demographics.jpg          # Dashboard preview image
└── README.md
```

---

## 🗂️ Dataset Overview

**Source file:** `01_Patient Demographics.xlsx` — 2,000 patient records collected across 10 Nigerian states (2019–2024)

| Column | Type | Description |
|---|---|---|
| Patient ID | Integer | Unique patient identifier |
| Age | Integer | Patient age |
| Gender | String | Male / Female |
| State | String | Nigerian state |
| Insurance Status | String | Insured / Uninsured |
| Blood Group | String | Patient blood group |
| Marital Status | String | Marital status |
| Occupation | String | Employment category |
| Registration Date | Date | Patient registration date |

---

## 📈 Dashboard Features

### KPI Cards

- **Total Patients** — 2,000
- **Insurance Coverage** — 62.6%
- **Uninsured Patients** — 749
- **Average Age** — 46.7 years
- **Female Patients** — 50.8%

### Visuals

| Visual | Insight |
|---|---|
| Coverage Gauge | 62.6% of patients are insured |
| Registration Trend | Tracks annual patient registrations from 2019–2024 |
| Age & Gender Distribution | Compares male and female populations across age groups |
| Blood Group Distribution | Shows the proportion of each blood type |
| Marital Status | Distribution of married, single, divorced, and widowed patients |
| Occupation Coverage | Compares insured and uninsured patients across occupations |

### Filters / Slicers

- **Gender** — Female / Male
- **Insurance Status** — Insured / Uninsured
- **State** — Abuja, Delta, Enugu, Kaduna, Kano, Lagos, Ogun, Osun, Oyo, Rivers

---

## 🔑 Key Insights

1. **Nearly two-thirds of patients have health insurance**, leaving over one-third still uninsured.
2. **The 65+ age group represents the largest patient population**, highlighting increased healthcare utilization among older adults.
3. **Patient registrations peaked in 2022** before showing a gradual decline over the following years.
4. **Insurance coverage differs across occupations**, providing insight into potential gaps in healthcare accessibility.
5. **The patient population is almost evenly split by gender**, creating a balanced demographic dataset for analysis.

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development and visualization |
| DAX | KPI calculations and measures |
| Power Query (M) | Data cleaning and transformation |
| Microsoft Excel | Source dataset |

---

## 🚀 How to Use

1. **Clone this repository**

```bash
git clone https://github.com/Lawal-Jnr-Analyst/HealthPulse-Patient-Demographics.git
cd HealthPulse-Patient-Demographics
```

2. **Open the template in Power BI Desktop**

- Open `HealthPulse Patient Demographics.pbit`
- When prompted, connect the template to `01_Patient_Demographics.xlsx`

3. **Or explore the published dashboard online**

👉 **[Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMWFhZTM3MmItODhhNC00NjlkLWI3MDEtYmY3MjljMTg2MDVmIiwidCI6IjA3M2U1ODhkLTI4NmMtNDAwNS04ZmYwLWYyYWMzYzhlYTRkMyJ9)**

---

## 📷 Preview

![HealthPulse Patient Demographics Dashboard](https://github.com/Lawal-Jnr-Analyst/HealthPulse-Patient-Demographics/blob/main/HealthPulse%20Patient%20Demographics.jpg)

---

## 📄 Licence

This project was developed for **portfolio and educational purposes**. The dataset is a simulated healthcare dataset created for analytical and visualization practice.

---

## 👤 Author

**Lawal Jamiu**

**Data Analyst | Power BI · SQL · Python**

- 🔗 [LinkedIn](https://linkedin.com/in/lawal-jnr-analyst)
- 🐙 [Lawal-Jnr-Analyst](https://github.com/Lawal-Jnr-Analyst)
