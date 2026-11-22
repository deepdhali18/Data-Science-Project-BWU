# IPL Cricket Match Performance Analysis (2008–2024)

## Requirements
1. streamlit
2. pandas
3. numpy
4. plotly
5. openpyxl
6. python-docx

## How to Run the interactive dashboard
1. Install Python 3.10 or later.
2. Extract this project folder.
3. Open a terminal in the folder.
4. Install packages: `pip install -r requirements.txt`
5. Start the dashboard: `streamlit run app.py`

The dashboard expects the two original CSV files and the PPS/MIS result workbooks to remain in the same folder as `app.py`.

## Project deliverables
- `app.py`: interactive Streamlit dashboard
- `IPL_Cricket_Project_Report.docx`: final project report
- `deliveries_2008-2024.csv`, `matches_2008-2024.csv`: supplied datasets
- `Statistical_Analysis_Q1_Q8.xlsx`: Questions 1–8 results
- `PPS_Results.xlsx`: Question 9
- `MIS_Results.xlsx`: Question 10
- `EDA_Summary.xlsx`: EDA output

## Important methodological note
PPS and MIS are project-defined composite indices. They are not official IPL statistics. Their scores depend on the stated weights, normalization approach and eligibility thresholds.
