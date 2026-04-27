#  Impact of 75% Attendance Rule on Students

##  Overview
This project analyzes the impact of the 75% attendance rule on students using survey data, data visualization, and mathematical modeling.

The project explores whether maintaining 75% attendance is realistic, its effect on academic performance, and why recovering attendance becomes difficult.


##  Objectives
- To analyze whether maintaining 75% attendance is realistic  
- To study the relationship between attendance and marks  
- To understand student stress due to attendance rule  
- To examine the difficulty of attendance recovery using mathematical analysis  


##  Features
- Data analysis using Python (Pandas, Seaborn, Matplotlib)  
- Visualization of attendance distribution and trends  
- Correlation analysis between attendance and marks  
- Mathematical proof of recovery difficulty  
- Attendance recovery calculator  


##  Key Insights
- Weak correlation between attendance and marks  
- High attendance ensures consistency but not guaranteed performance  
- Majority of students feel stressed due to the 75% rule  
- Recovery from low attendance is mathematically difficult  


##  Mathematical Insight
Recovering attendance requires attending a large number of additional classes continuously.  
This makes recovery difficult once attendance drops below 75%.


##  How to Run

### Run Notebook
Open:
```
notebooks/analysis.ipynb
```

### Run Calculator
```bash
python src/calculator.py
```


##  Project Structure
```
project1/
│
├── data/
│   └── survey.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── src/
│   └── calculator.py
│
├── README.md
└── requirements.txt
```

---

##  Future Improvements
- Build a web app using Streamlit  
- Use a larger dataset  
- Add prediction models
