# HR Analytics Dashboard 

## Problem Statement
Managing employee attendance is crucial for productivity and workforce planning. HR teams need insights into employee presence, work-from-home trends, and sick leave patterns to make data-driven decisions.

![Screenshot (20)](https://github.com/user-attachments/assets/b5afe040-199f-40c1-a5ac-093a8f1d3da5)

## Data Source
- The dataset was obtained from **Atliq Company's website**.

## Data Transformation
- **Transformed using Power Query** (Pivoting employee names and dates into structured columns).
- **Measures created using DAX** to calculate key metrics.

## Key Metrics and Insights
1. **KPIs**
   - **Presence %**: Employee attendance percentage.
   - **WFH %**: Work-from-home trends.
   - **SL %**: Sick leave patterns.

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

## Final Outcomes
- **Optimized HR decision-making** by analyzing attendance patterns.
- **Identified trends** in work-from-home and sick leave usage.
- **Provided insights** for workforce planning and productivity improvements.

## Future Enhancements
1. **Real-time Data Integration** for live attendance tracking.
2. **Automated Alerts** for abnormal attendance patterns.
3. **Access Privileges** for role-based data access.

## Conclusion
This dashboard provides a clear view of employee attendance trends, helping HR make data-driven decisions. The insights assist in workforce planning, policy improvements, and understanding employee behavior.
