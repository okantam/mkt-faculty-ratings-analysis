# MKT Faculty Ratings Analysis
Mixed-effects modeling of student evaluations in marketing courses, exploring the impact of instructor preparedness, student behaviors, and course type on overall faculty ratings.


This project investigates the relationship between professor performance, student behaviors, and overall student evaluations in marketing courses at Miami University (2013–2017). Using a mixed-effects model, we analyzed how both instructor traits and student engagement metrics influence overall course ratings. 

### 📊 Key Research Questions
1. What instructor performance measures drive student evaluations?
2. How do student behaviors affect ratings?
3. Do these relationships vary by course type?

### 🧠 Methodology
- Cleaned and processed 587 observations of faculty evaluations.
- Explored multicollinearity using Variance Inflation Factors (VIF).
- Applied a full and forward-selected mixed-effects model with random intercepts for instructor and course type.
- Evaluated the significance of predictors via ANOVA and diagnostic plots.

### 🔍 Key Findings
- The strongest predictors of high student ratings were:
  - `iDemo`: Instructor showed concern for student learning.
  - `iTopic`: Students appreciated the course topic.
  - `iChallenged`: Instructor challenged students intellectually.
  - `iPrepared`: Instructor came well-prepared for class.
- Student engagement (`sEngaged`) played a smaller but positive role.
- Course type had little effect on the relationships, suggesting consistency in what students value.

### 💡 Recommendations
Instructors seeking higher evaluations should:
- Demonstrate concern for student learning.
- Challenge students intellectually.
- Show strong preparation.
- Foster student appreciation for course content.

### 📎 Files Included
- **Report (1).Rmd**: RMarkdown script with all code for data processing, exploratory analysis, and modeling.
- **Report--1-.pdf**: Final report summarizing methodology, findings, and recommendations.
- **CombinedData.csv**: Dataset containing student evaluations across multiple marketing courses.
- **Presentation.pdf**: *Provided by the client* to give background on project goals and variables of interest.

### 📄 Citation
Chapman, Ethan, and Okanta, Michael. *MKT Faculty Ratings Analysis*. Miami University, 2024.

---

Feel free to clone, adapt, or cite this work. For questions or collaborations, reach out via [LinkedIn](https://www.linkedin.com/in/michael-okanta-4486281b5/).
