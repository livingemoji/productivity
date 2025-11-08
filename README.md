# AI-Driven Workforce Productivity & Operations Insight System

This project provides a comprehensive analysis system for workforce productivity using machine learning and data visualization techniques. The system processes workforce data to generate meaningful insights about employee productivity, identify patterns, and detect anomalies.

## Features

- **Data Processing**: Handles workforce data including metrics like:
  - Logged Hours
  - Tasks Completed
  - Idle Time
  - Attendance Percentage

- **Advanced Analytics**:
  - Productivity Score Calculation
  - Employee Performance Classification
  - Anomaly Detection using Isolation Forest
  - Interactive Visualizations

- **Visualization**:
  - Interactive bar charts showing productivity scores by department
  - Department-wise performance analysis
  - Anomaly visualization

## Requirements

The following Python packages are required:
```
pandas
numpy
scikit-learn
matplotlib
plotly
openpyxl
nbformat
ipywidgets
```

## Usage

1. Ensure you have all required packages installed
2. Place your workforce data CSV file in the project directory
3. Open `workforce_productivity_system.ipynb` in Jupyter Notebook or VS Code
4. Update the CSV file path if needed
5. Run all cells sequentially

## Data Format

Your input CSV file should contain the following columns:
- Employee_ID
- Department
- Logged_Hours
- Tasks_Completed
- Idle_Time
- Attendance_Percentage

## Output

The system generates:
- Productivity scores for each employee
- Classification of employee performance
- Anomaly detection results
- Interactive visualizations
- Excel report with all insights (`insights_report.xlsx`)


## Contributing

Feel free to open issues or submit pull requests to improve the system.

## Author
WANYONYI ALEX WAFULA