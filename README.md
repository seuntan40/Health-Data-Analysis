# Health-Data-Analysis

The healthcare industry plays a crucial role in ensuring the well-being of individuals. However, rising medical costs and varying levels of insurance coverage often create financial challenges for patients. This analysis focuses on understanding the key cost drivers in patient billing, specifically medication costs, treatment costs, and, while considering the impact of insurance coverage on out-of-pocket expenses.
The primary aim of this study is to identify patterns in patient billing and insurance coverage, highlight key observations, and propose actionable recommendations to optimize costs, improve patient affordability, and enhance overall healthcare delivery. The findings are based on a dataset comprising inpatient, outpatient, and emergency cases, with detailed breakdowns of service utilization and associated financial burdens.

# UNIMED Teaching Hospital Dashboard

## 📌 Project Overview
The **UNIMED Teaching Hospital Dashboard** provides an interactive analysis of hospital billing, patient satisfaction, treatment costs, and insurance coverage. This project leverages **Power BI** to visualize key metrics, enabling better decision-making in healthcare management.

## 📊 Features
- **Total Billing Analysis:** Breakdown by department and procedure.
- **Treatment Cost Distribution:** Comparison of inpatient, outpatient, and emergency costs.
- **Patient Satisfaction Scores:** Visualization by department.
- **Insurance Coverage Analysis:** Coverage distribution across different age groups.
- **Demographic Filters:** Gender and seasonal insights.

## 🗂 Data Preparation
1. **Data Collection:** Gather hospital billing, treatment, and insurance datasets.
2. **Cleaning & Processing:** Remove inconsistencies, standardize formats.
3. **Categorization:** Group data by department, procedures, and demographics.

## 📈 Dashboard Development
- **Key Metrics Display:**
  - Total Billing Amount
  - Medication Cost
  - Treatment Cost
  - Total Insurance Coverage
- **Visuals Implemented:**
  - Bar charts for billing by department and procedure.
  - Pie charts for patient satisfaction and insurance coverage by age.
  - Horizontal bars for treatment cost by service type.
- **Filters:** Gender & Season selection.

## 🔍 Analysis & Insights
- Identify departments with the highest billing amounts.
- Evaluate patient satisfaction across departments.
- Understand insurance coverage distribution.
- Compare inpatient, outpatient, and emergency treatment costs.

## 🚀 Deployment & Usage
1. Open **Power BI Desktop**.
2. Load the provided dataset.
3. Import the `.pbix` file for the dashboard.
4. Interact with the visuals to derive insights.

## 📜 Documentation & Contribution
- **`README.md`** (this file) explains the project structure.
- Contributions are welcome! Fork the repository and submit a pull request.

## 📷 Screenshot
![Dashboard Preview](path/to/Health-Dashboard.jpg)

## 🏥 About
This dashboard was created to improve **healthcare data analysis** and provide meaningful insights into hospital operations. If you find this project useful, consider starring ⭐ the repository!

---

📧 For any inquiries, contact akinmurele40@gmail.com, Phone number: 08100403138


Python was used to calculate important financial information for UNIMED Teaching Hospital. First, the Total Billing Amount was found by adding the Treatment Cost, Medication Cost, and Room Charges (daily rate). This shows the total cost of care for each patient. Then, the Out of Pocket Cost was calculated by subtracting the Insurance Coverage Amount from the Total Billing Amount. This shows how much patients need to pay themselves. The results were checked by displaying key parts of the data.

**OBSERVATION AND RECOMMENDATION

1.	INSURANCE COVERAGE DISPARITY:
Observation: 
•	Patients with limited or no insurance coverage may face higher out-of-pocket costs, potentially leading to inequitable access to 	treatment, and financial strain.
Recommendation: 
•	Implement a scale payment system based on income levels 
•	Offering of financial aids programs to uninsured patients 

2.	LOW INSURANCE COVERAGE FOR EMERGENCY PATIENTS 
	Observation: 
•	Emergency patient often have minimal or no insurance coverage, resulting in higher unpaid bills 
	Recommendation: 
•	Collaborate with insurance companies to create low-cost emergency – specific coverage plans.

3.	HIGHT COST FOR INPATIENTS DUE TO LONG HOSPITAL STAYS 
	Observation:
•	Prolong hospital stays contributes significantly to inpatient costs 
	Recommendation:
•	Implement faster discharge protocols with home care follow-ups
	Provide financial incentives for patients.
•	Reduce unnecessary room service add-ons by offerings “basic care package”



5.	OVERUSE OF EMERGENCY SERVICE 
	Observation:
•	Many patients use emergency service for non-urgent cases, increasing the burden on healthcare resources 
	Recommendation:
•	Launch community education campaigns about appropriate emergency room usage 
•	Introduce a system to direct non-urgent cases to outpatient clinics

6.	SIGNIFICANT PORTION OF PATIENTS ARE UNINSURED 
	Observation: 
•	Some patient lacks insurance entirely, for example, the children
	Recommendation: 
•	Partner with government agencies or NGOs to Provide free or subsidized insurance plans 
•	Offer discounts or instalment payment plan for uninsured patients to reduce financial barriers 



7.	SEASONAL TREADS AFFECT PATIENT VOLUME AND COST 

	Observation: 
•	Fall and winter are the peak season for getting sicks or ill, particularly with respiratory illness like colds and flu with will 	lead to surge in outpatient and emergency visits

	Recommendation: 
•	increase staffing and resource during peak seasons 
•	Run vaccination or preventive health campaigns before high-demand periods 
•	Preventive measures such as flu vaccinations, frequent handwashing and proper ventilation can help reduce illness during these 		times 

8.	PATIENTS WITH ZERO INSURANCE COVERAGE SPEND MORE OUT-OF-POCKET 
	Observation:
•	Patients without insurance coverage spend significantly more on healthcare.
	Recommendation: 
•	Introduce flexible payment plans or discount for patients with no insurance.
•	Advocate for mandatory basic insurance coverage at the policy level
9.	CHRONIC CONDITIONS

	Observation:
•	Patients with chronic conditions especially orthopedics department faces higher medication and treatment costs.

	Recommendation: 
•	Partner with Pharmaceutical companies to provide discounts or free essential medications for chronic conditions 
•	Implement preventive care programs to reduce the long-term medication burden.


10.	PATIENTS WITH NO INSURANCE TEND TO DELAY TREATMENT 

Observation:
•	Uninsured patients delay seeking medical care leading to more severe (and expensive) conditions.

Recommendation: 
•	Establish community outreach programs to provide early intervention for uninsured individuals.
•	Offer free health screenings to encourage timely diagnosis and treatment




10.	UNINSURED EMERGENCY PATIENTS INCREASES HOSPITAL DEBT 
 
Observation: 
•	Hospital accrues bad debt when uninsured emergency patients are unable to pay.

Recommendation: 
•	Advocate for government grants to cover emergency care for uninsured patients 
	partner with charities to fundraise for critical emergency cases.
•	Partner with insurance providers to expand coverage options for underinsured patients.
•	Provide financial counseling to patients to minimize out-of-pocket burdens.
