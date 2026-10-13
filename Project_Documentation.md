# IT Help Desk Analysis Dashboard – Project Documentation

## 1. Introduction

The IT Help Desk Analysis Dashboard is a Power BI project developed to analyze IT support ticket data. The purpose of the project is to transform operational ticket information into meaningful insights that can help IT teams monitor support demand, identify important issues, and improve service performance.

## 2. Problem Statement

Organizations receive numerous IT support requests from employees and users. When ticket information is stored only as raw data, it becomes difficult to quickly identify:

- Which departments generate the highest number of tickets.
- Which ticket priorities require immediate attention.
- Which issues have high severity.
- How long tickets remain open.
- How satisfied users are with IT support.
- How support workload is distributed.

A centralized dashboard can help convert this raw information into actionable insights.

## 3. Project Objective

The main objective of this project is to build an interactive Power BI dashboard that provides a clear overview of IT help desk performance and ticket characteristics.

The project aims to:

1. Analyze the total number of support tickets.
2. Compare ticket volume across departments and business units.
3. Analyze ticket priority and severity.
4. Identify different categories of IT issues.
5. Monitor the number of days tickets remain open.
6. Analyze user and employee-related information.
7. Evaluate customer satisfaction.
8. Provide insights that can support operational decision-making.

## 4. Dataset Description

The analysis uses IT ticket-related data containing attributes such as:

| Field | Description |
|---|---|
| Ticket ID | Unique identifier for each support ticket |
| Employee Name | Employee associated with the ticket |
| Department | Department from which the ticket originated |
| Business Unit | Organizational business unit |
| Gender | Gender-related employee information |
| Job Classification | Employee job category or classification |
| Ticket Type | Category of IT support request |
| Severity | Technical or business severity of the issue |
| Priority | Urgency level assigned to the ticket |
| Days Open | Number of days the ticket remained open |
| Satisfaction | User satisfaction information |
| IT Owner | Person or team responsible for the ticket |

## 5. Tools Used

### Power BI
Used for building interactive reports and dashboards.

### Power Query
Used for data cleaning, transformation, and preparation before visualization.

### DAX
Used for creating calculated measures and supporting analytical calculations.

## 6. Dashboard Analysis

The dashboard is titled **IT Ticket Analysis** and is designed to provide an overview of IT support operations.

### Ticket Volume Analysis
Helps monitor the overall number of IT support requests and identify changes in support demand.

### Department and Business Unit Analysis
Helps identify organizational areas generating higher volumes of IT support tickets.

### Priority and Severity Analysis
Helps identify critical and urgent issues that may require faster resolution.

### Ticket Type Analysis
Helps understand the categories of issues commonly reported to the IT support team.

### Days Open Analysis
Helps monitor how long tickets remain unresolved and can highlight potential bottlenecks.

### Satisfaction Analysis
Provides insight into user experience and perceived quality of IT support services.

### IT Owner Analysis
Can be used to understand ticket distribution and support workload.

## 7. Expected Insights

This dashboard can help answer questions such as:

- Which department generates the highest number of tickets?
- Which ticket types occur most frequently?
- How many tickets are high priority or high severity?
- How long do tickets typically remain open?
- Which business units require greater IT support?
- What are the trends in user satisfaction?
- How is the workload distributed among IT owners?

## 8. Conclusion

The IT Help Desk Analysis Dashboard demonstrates how Power BI can be used to convert operational IT ticket data into meaningful visual insights. The project helps stakeholders monitor ticket trends, understand service demand, and identify areas where IT support processes may be improved.

## 9. Future Enhancements

Possible future improvements include:

- Adding real-time ticket data.
- Creating automated refresh schedules.
- Adding ticket resolution SLA analysis.
- Introducing monthly and yearly trend analysis.
- Adding drill-through pages for detailed ticket investigation.
- Including predictive analysis for future ticket volume.
- Creating role-based views for IT managers and support teams.

## 10. Repository Contents

- `IT Analysis.pbit` – Power BI template file.
- `README.md` – Project overview and setup instructions.
- `documentation/Project_Documentation.md` – Detailed project documentation.
- `screenshots/` – Folder reserved for dashboard screenshots.
