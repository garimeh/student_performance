
## Project Overview
This project aims to analyze a dataset concerning students' performance across various subjects. The dataset is from [Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/student-study-performance). includes multiple variables like gender, race/ethnicity, parental level of education, lunch type, test preparation course completion, and scores in math, reading, and writing. Through this analysis, we explore how different factors, including test preparation courses and parental education levels, influence students' academic outcomes.

## Dataset Description
The dataset comprises the following fields:
    gender: The student's gender (Male/Female).
    race/ethnicity: The student's race/ethnicity (Groups A to E).
    parental level of education: The highest education level attained by the student's parents.
    lunch: Type of lunch had by the student (standard or free/reduced).
    test preparation course: Indicates if the student completed a test preparation course (none/completed).
    math score: Student's score in mathematics.
    reading score: Student's score in reading.
    writing score: Student's score in writing.
## Objective
The project aims to answer the following key questions:
        1. How does the gender of students affect their performance in math, reading, and writing?
        2. Does the level of parental education influence student performance across subjects?
        3. How does participation in a test preparation course impact student scores?

## Analysis Steps
### Data Cleaning
The initial step involves cleaning the dataset to ensure it is free from inconsistencies, missing values, or duplicates, which could skew the analysis.

### Descriptive Statistics
Calculate basic statistics (mean, median, mode, etc.) to get an overview of the data distribution.

### Data Analysis
- Gender Impact Analysis : Analyze the data to understand how gender influences student performance in different subjects.
- Parental Education Level Analysis : Examine the relationship between the parents' education level and student scores.
- Test Preparation Course Analysis : Determine the impact of completing a test preparation course on student performance.

### Visualization
Create visual representations, such as bar charts and box plots, to illustrate the findings and make the data more accessible.

### Findings and Conclusion
- It was found that on average, female students were more likely to score higher on language tests whereas male students were more likely to score higher on math tests.
- It was found that on average, students whose parents pursued higher education were more likely to score higher on tests whereas  students were less likely to score higher on tests.
- It was found that on average, students were more likely to score higher on tests if they took preparatory courses.

## Libraries used:
``` Python : seaborn, matplotlib, pandas, numpy ```

## Future Directions
We can further do a study on how the gender and the ethnicity affects the scores coupled with the preparation and parental education. And see how the option of having lunch affects performance.
