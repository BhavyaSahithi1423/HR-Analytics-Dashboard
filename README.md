# HR-Analytics-Dashboard

## Overview
This project analyzes HR data for Atliq Company, focusing on employee presence, work-from-home trends, and sick leave patterns. The analysis was performed using Power BI, leveraging data from multiple months to generate meaningful insights.

![Screenshot (20)](https://github.com/user-attachments/assets/3ce85266-e0ec-432d-9ba2-58beeae84c0e)

## Data Sources
- **Employee Attendance Data** (April, May, June)
- Transformed using Power Query (Pivoting employee names and dates into structured columns)
- Measures created using DAX to calculate key metrics

## Key Metrics and Insights
1. **KPIs**
   - **Presence %**: Percentage of employees present on a given day.
   - **WFH %**: Percentage of employees working from home.
   - **SL %**: Percentage of employees on sick leave.

2. **Few DAX Formulas Used**
   - **Presence % Calculation:**
     ```DAX
     Presence % = DIVIDE([Present days],'Measure Table'[Total Working Days],0)
     ```
   - **WFH % Calculation:**
     ```DAX
     WFH % = DIVIDE([WFH Count],[Present days],0)
     ```
   - **SL % Calculation:**
     ```DAX
     SL % = DIVIDE([SL Count],[Total Working Days],0)
     ```

3. **Visualizations**
   - **Trend Graphs** for Presence, WFH, and SL percentages over time.
   - **Tables** displaying daily and aggregated attendance data.
   
4. **Insights**
   - Identified trends in work-from-home preferences.
   - Patterns in employee presence and sick leave.
   - Monthly variations and potential factors influencing attendance.

## Tools Used
- **Power BI** for Data Visualization
- **Power Query** for Data Transformation
- **DAX** for Custom Measures

## Future Enhancements
- **Real-time Data Integration** for live attendance tracking.
- **Automated Alerts** for abnormal attendance patterns.
- **Access Privileges** for role-based data access.

## Conclusion
This dashboard provides a clear view of employee attendance trends, helping HR make data-driven decisions. The insights assist in workforce planning, policy improvements, and understanding employee behavior.



