# Reading Assessment - Exploratory Data Analysis

## Overview
This project is a self-initiated exploratory data analysis of a 
children's reading assessment dataset. The dataset contains survey 
responses from 50 children collected at two timepoints - baseline 
and endline - across 20 questions measuring reading habits, skills, 
and attitudes.

## Key Findings

- **Ceiling Effect:** Most children scored near the maximum (59-60 
  out of 100) at baseline, leaving little room to measure improvement
  
- **Skills vs Enjoyment Split:** Skills-based questions consistently 
  improved while enjoyment and confidence questions consistently 
  declined - a pattern that held across every analysis approach

- **Survey Structure:** Correlation analysis revealed the 20 questions 
  measure exactly 5 underlying themes, each repeated 4 times, with 
  near-perfect within-theme correlations (r = 0.98)

- **Age Group:** 5-year-olds showed the most consistent improvement. 
  The 7+ group showed the highest variability

- **Gender:** Male participants showed a small net gain (+0.50 points) 
  while female participants showed no net change (0.00)

## Analysis Breakdown

| Plot | What It Shows |
|------|--------------|
| Plot 1 | Overall score distribution at baseline and endline |
| Plot 2 | Individual level score changes per participant |
| Plot 3 | Per question mean scores and change |
| Plot 4 | Score breakdown by gender |
| Plot 5 | Score breakdown by age group |
| Plot 6 | Full heatmap of every participant and question |
| Plot 7 | Improvement rate per question ranked |
| Plot 8 | Correlation matrix of all 20 questions |
| Plot 9 | Age in months vs total score |
| Plot 10 | Executive summary dashboard |

## Tools and Libraries
- Python 3
- Pandas
- Seaborn
- Matplotlib
- openpyxl
- Google Colab

## Files
- `reading_analysis.ipynb` - Full analysis notebook
- `reading_assessment_report.pdf` - Written report with all charts
- `charts/` - Individual chart PNG files

## Note
This project was completed as a personal exercise to explore the 
dataset more deeply beyond the original task requirements. It was 
built out of genuine interest in research on early childhood 
development.
```

