# The Impact of Having Parents in Tech on Student Performance & Habits

## Overview
This project explores how having parents in tech influences students' academic performance, programming habits, and lifestyle choices. The analysis is based on data collected from students, examining variables like **GPA, age of starting programming, study habits, sleep patterns, and screentime.** The study applies **ANOVA tests, correlation analysis, and data visualization** to derive insights.

## Key Findings
- **Programming Age:** Students with tech-savvy parents tend to start programming earlier.
- **GPA:** No significant correlation between having parents in tech and GPA.
- **Study Habits:** No major influence on group study preferences or note-taking methods.
- **Lifestyle Factors:** Sleep schedules, screentime, and TikTok usage appear independent of parental tech background.

## Dataset Description
The dataset consists of various student attributes:
| Column Name      | Description |
|-----------------|-------------|
| `Tech_Parents`  | Number of parents in tech (0, 1, or 2) |
| `Prog_Age`      | Age at which the student started programming |
| `GPA_Last` & `GPA_Lasttolast` | GPA for the last two semesters |
| `Notes`         | Preferred note-taking method (Tablet, Paper, Computer, None) |
| `Screentime`    | Average daily screentime (hours) |
| `Sleep`         | Hours of sleep per day |
| `Group_Study`   | Frequency of group study participation |
| `Scholarship`   | Scholarship status (None, Partial, Full) |

## Methodology
### 1️⃣ Data Cleaning:
- Handled missing values (removed 9.6% of rows with nulls).
- Converted categorical values into numerical form.
- Removed extreme outliers (e.g., programming at age 2).

### 2️⃣ Statistical Analysis:
- **ANOVA Testing:** Used to check the statistical significance of Tech_Parents on various factors.
- **Correlation Analysis:** Evaluated relationships between Tech_Parents and GPA, programming age, etc.

### 3️⃣ Visualization:
- Bar plots, boxplots, and scatter plots were used to visualize trends.

## Notable Results
📌 **Tech parents influence programming start age:** Students with tech-savvy parents tend to start programming earlier.  
📌 **GPA remains unaffected:** No significant difference in academic performance across groups.  
📌 **Study habits stay constant:** Parental tech background does not influence group study participation or note-taking.  
📌 **Lifestyle choices are independent:** Sleep schedules and screentime habits are shaped more by personal factors.

## How to Use the Notebook
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Tech_Parents_Impact_Study.git
   cd Tech_Parents_Impact_Study
