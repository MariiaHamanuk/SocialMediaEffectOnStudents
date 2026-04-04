# Social Media and Student Well-Being

Research project investigating how social media usage affects students aged 16-25 — their academic performance, sleep, mental health, and relationships.

**Authors:** Mykhailo Rykhalskyi, Ostap Mnykh, Mariia Hamaniuk (2025)

## Research Questions

- Does spending more time on social media correlate with lower grades?
- Does more social media use mean less sleep?
- Does relationship status relate to time spent online?
- Are some platforms more harmful/addictive than others?
- How do age and gender affect the amount of time spent on social media?

## Dataset

Anonymised cross-sectional dataset sourced from Kaggle — **705 student records, 13 variables** covering social media habits alongside academic and personal outcomes.

| Variable | Type | Description |
|---|---|---|
| Student_ID | Identifier | Unique respondent ID |
| Age | Continuous | Age in years |
| Gender | Categorical | Male / Female |
| Academic_Level | Categorical | High School, Undergraduate, Graduate |
| Country | Categorical | Country of residence |
| Avg_Daily_Usage_Hours | Continuous | Average hours per day on social media |
| Most_Used_Platform | Categorical | Platform where most time is spent |
| Affects_Academic_Performance | Binary | Student's own view: Yes / No |
| Sleep_Hours_Per_Night | Continuous | Average nightly sleep duration |
| Mental_Health_Score | Ordinal (1-10) | Self-rated mental well-being |
| Relationship_Status | Categorical | Single, In Relationship, Complicated |
| Conflicts_Over_Social_Media | Discrete | Number of reported conflicts |
| Addicted_Score | Ordinal (1-10) | Addiction level (Bergen Scale) |

## Methods

- Descriptive statistics & correlation analysis
- OLS Regression
- Logit / Probit models
- t-test, F-test, J-test
- Confusion matrix & ROC curve

Analysis is done in Python.

## Project Structure

```
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for exploration
├── reports/               # Research reports (PDF)
├── src/                   # Python scripts for analysis
├── .gitignore
└── README.md
```
