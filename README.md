# Payroll Dashboard

## Project Overview
This payroll analytics dashboard was developed to provide HR and finance teams with clear visibility into salary distribution, payment methods, employee roles, and compensation trends across departments. It helps monitor payroll efficiency, identify high-cost areas, and ensure equity in pay and workforce composition.

---

## Dataset

The dataset contains employee-level payroll records with the following key fields:

| Column         | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| PayrollID      | Unique identifier for each payroll record.                                  |
| EmployeeID     | Unique identifier assigned to each employee.                                |
| FullName       | Name of the employee.                                                        |
| Department     | Department where the employee is assigned (e.g., Marketing, HR, Finance).   |
| JobTitle       | Specific role held by the employee (e.g., HR Officer, Software Engineer).   |
| PayDate        | Date when the salary was issued.                                             |
| EmploymentType | Type of employment contract: Full-Time, Internship, or Part-Time.           |
| BasicSalary    | Base salary paid before any additions or deductions.                        |
| Allowances     | Additional compensation such as benefits or bonuses.                        |
| Deductions     | Statutory or internal payroll deductions (e.g., tax, benefits).             |
| GrossPay       | Total salary before deductions (Basic Salary + Allowances).                 |
| NetPay         | Final salary received after deductions (Gross Pay – Deductions).            |
| PaymentMethod  | Mode of payment (e.g., Bank Transfer, Mobile Money, Cash).                  |
| BankName       | Associated bank for payment processing (where applicable).                  |

Power BI was used for data modeling, KPI computation, and dashboard development to provide a comprehensive and interactive analysis of payroll operations across departments, roles, and payment structures.

---

## Executive Summary

- The payroll analysis dashboard, built using data from one fiscal year, offers a comprehensive view of compensation structures across departments, roles, and employment types.
- Total payroll spending reached **$13.9 million**, with Marketing, HR, and Finance accounting for over **70% of total compensation**.
- Marketing leads in salary allocation (**$3.81M**), driven by the largest headcount and significant investment in full-time and internship roles. HR and Finance follow closely.
- Internship and part-time roles are widely adopted in IT and Sales, supporting operational flexibility and cost management.
- Bank transfers dominate payroll disbursement methods, while mobile money sees notable use in Sales and Marketing.
- Top earners, including Marketing and HR officers, reflect the company’s emphasis on frontline and administrative talent.
- Salary deductions remain consistently between **5–6%** of gross pay, suggesting standardized compensation policies.

---

## Visualization

_Visuals included in the dashboard to explore:_
- Salary distribution by department and role
- Employment contract type composition
- Net pay by payment method
- Top earners by title and department

---

## Insight Deep Dive

### Departmental Payroll Distribution
- Marketing leads departmental salary spending, totaling **~$3.81M**, including the highest basic salary outlay (**$3.58M**).
- HR and Finance follow with **$3.34M** and **$2.77M**, respectively.
- Sales records **$2.06M**, with leaner compensation but competitive net pay due to efficient deductions.
- IT shows the lowest payroll expense (**$1.72M**), reflecting lean teams or cost-optimized staffing.

### Workforce Composition by Job Title
- **Marketing Officers** dominate with **672 employees**—the largest job group in the company.
- HR and Finance follow with **HR Officers + Managers (564)** and **Accountants + Finance Analysts (492)**.
- IT and Sales are the smallest teams: **360 Sales Executives/Reps**, **312 IT staff**.

### Employment Type Breakdown
- Marketing employs **240 full-time** and **240 interns**, showcasing a strong mix of experienced and early-career staff.
- Finance and HR have the next highest intern headcount: **228** and **204**, respectively.
- Part-time contracts are most common in Marketing and HR (**192 each**), followed by IT (**120**).

### Payment Method Analysis
- **Bank Transfer** dominates in every department—especially Marketing (**$1.84M**) and HR (**$1.69M**).
- **Mobile Money** is heavily used in Marketing (**$1.24M**) and Sales (**$753K**).
- **Cash** is used minimally, mostly in HR (**$732K**) and IT (**$600K**).

### Net Pay by Employment Type
- Marketing leads net pay across all types: **$1.4M full-time**, **$1.31M interns**, **$1.1M part-time**.
- HR follows with balanced net pay distribution across employment types.
- Finance and Sales show reliance on interns (**$1.23M** and **$983K**, respectively).
- IT has the lowest total net pay (**$1.73M**) but an even distribution across roles.

### Top Net Salary Insights
- **Angela Phillips (Marketing Officer)** holds the highest net pay at **$88,052**.
- HR staff—**Latoya Kirk** and **Amber Taylor**—rank second and third with **$85,536** and **$82,563**.
- Marketing and HR dominate the top salary brackets.

---

## Recommendations

- **Expand Digital Payment Methods**  
  While bank transfers dominate, Sales and Marketing departments utilize mobile money significantly. Standardize infrastructure and policies to support all digital channels with robust fraud prevention and cost controls.

- **Minimize Cash Dependency**  
  Cash remains in limited use (e.g., HR and IT), but poses higher risk and audit challenges. Migrate remaining teams to secure, traceable digital payroll methods to enhance efficiency and compliance.

- **Balance Contract Types Across Departments**  
  Marketing and HR effectively use a mix of full-time, interns, and part-time roles. Departments like IT and Sales should adopt similar flexibility to optimize headcount, manage costs, and ensure operational agility.

- **Reallocate Internship Investment Strategically**  
  Finance and Sales heavily rely on interns for payroll output. Consider converting high-performing interns to full-time roles or diversifying roles across departments to reduce overdependence on temporary contracts.

- **Conduct Cross-Departmental Salary Benchmarking**  
  With top earners concentrated in Marketing and HR, initiate regular salary band reviews across all departments to ensure role-based pay equity, avoid pay compression, and align compensation with responsibilities.

- **Review Workforce Distribution in Technical Roles**  
  IT shows the lowest payroll share and headcount despite digital needs. Evaluate if current staffing aligns with the company’s growth strategy and invest in high-impact tech roles accordingly.

---
