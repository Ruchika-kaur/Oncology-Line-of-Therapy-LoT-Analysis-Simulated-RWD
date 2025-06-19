# Oncology-Line-of-Therapy-LoT-Analysis-Simulated-RWD

This project demonstrates a real-world data (RWD) analysis pipeline focused on **oncology treatment patterns**, using a **synthetic dataset** that simulates patient-level lines of therapy, regimens, and clinical responses.

The goal is to showcase my experience with real-world healthcare data — including data cleaning, logic validation, and basic clinical insights — in a reproducible, privacy-safe format.

---

## Dataset Overview

- **100 patients**, each with up to 4 lines of therapy
- Fields include:
  - `Patient_ID`, `Cancer_Type`, `Line_of_Therapy`, `Regimen`
  - `Start_Date`, `End_Date`, `Duration_Days`, `Response`
- Data includes **realistic issues** such as:
  - Missing values
  - Inconsistent formatting
  - Date logic errors
  - True duplicate rows

---

## ⚙Tech Stack

- **Python**, **pandas**, **matplotlib**, **seaborn**
- Cleaned using `pandas`
- Visualized using `seaborn` and `matplotlib`

---

## Cleaning Steps

- Removed duplicate treatment records
- Fixed inconsistent formatting in `Cancer_Type` and `Regimen`
- Removed rows with `End_Date` earlier than `Start_Date`
- Handled missing values in `Response`, `Regimen`, and `Duration_Days`

---

## Key Analyses & Visuals

- Distribution of cancer types across patients
- Line of therapy frequency by patient
- Treatment duration by cancer type
- Response trends across lines of therapy
- Most commonly used regimens

---

## Sample Insights

- Most patients receive up to 3 lines of therapy
- Response rates drop after 2nd line, with progression increasing in later lines
- Certain regimens dominate across multiple cancer types
- Ovarian and prostate treatments showed longer durations on average

---

## Why This Project Matters

This project mirrors tasks I've performed in client-facing RWD oncology projects — such as mapping therapy lines, validating treatment windows, and preparing structured outputs for clinical stakeholders.

> **Note**: All data used here is synthetic and generated for educational purposes only.

---

## Next Steps

I plan to extend this into:
- A **predictive model** to forecast response (e.g., progression)
- An **interactive dashboard** for LoT and treatment insights (Power BI or Streamlit)

---

## Author

**Ruchika Kaur**  
Senior Clinical Data Analyst | Oncology RWD & EHR Data  
📫 [rucpar12@gmail.com](mailto:rucpar12@gmail.com)  
🔗 [GitHub](https://github.com/Ruchika-kaur)

---

