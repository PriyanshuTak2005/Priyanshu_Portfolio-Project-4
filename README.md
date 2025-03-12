# Priyanshu_Portfolio-Project-4
<br>
📌 Overview
<br>
This project is a University Data Analysis Dashboard that provides key insights into university employee and student data using analytical measures like Average, Count, and Sum. The dashboard presents data-driven visualizations to help with better decision-making and resource allocation within the university system.
<br>
<br>
📊 Features<br>

-> Count of College IDs by State – Displays the distribution of colleges across different states to understand regional trends.<br>

-> Average Age by Job Role – Calculates the average age of employees grouped by job role to analyze workforce demographics.<br>

-> Count of Employee IDs by Job Role – Shows the number of employees in each job role, helping identify staffing patterns.<br>

->Total Monthly Cost by Job Role – Computes the total salary expenditure for each job role, aiding in financial planning.<br>
<br>
<br>
📌 Usage<br>

->Load and clean university data – Import datasets from CSV or SQL databases.<br>

->Generate required measures – Use Python or SQL to calculate count, average, and sum-based metrics.<br>

->Visualize insights – Create dashboards and reports using Power BI or Tableau.<br>

->Export and share reports – Save reports as PDFs or dashboards for further analysis.<br>
<br>
<br>
🗂️ Data Structure

The project utilizes three datasets that are connected through primary and foreign keys:

-> Colleges_Dataset (Primary Key: College Id)

Contains information about colleges, including name, city, state, rank, and NIRF ranking.<br>
<br>
->Courses_Dataset (Foreign Key: College Id)

Stores details of courses offered by colleges, including course name and abbreviation.<br>
<br>
->HR_Analytics (Foreign Key: College Id)

Includes employee-related data such as age, department, education, daily rate, distance from home, and attrition.<br>
<br>

These relationships allow for in-depth analysis of college distribution, courses, and HR metrics.<br>
<br>
<br>
🤝 Contributing<br>

We welcome contributions to enhance the dashboard. Here's how you can help:<br>

->Report bugs or suggest features via issues.<br>

->Fork the repository and create a pull request.<br>

->Improve data visualizations or add new analytical metrics<br>
<br>
<br>
📜 License<br>

This project is licensed under the MIT License.
