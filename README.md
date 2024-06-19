# Student Mental Health

![Project image](mentalhealth.jpg)

### Project Overview

This project aims to analyze the mental health of international students at a Japanese university. Using PostgreSQL, we explore whether international students face higher risks of mental health difficulties compared to domestic students. Specifically, we examine the impact of social connectedness, acculturative stress, and the length of stay on depression levels among international students.

### Data Description

The dataset contains information on students' demographics, language proficiency, academic level, length of stay, and various mental health scores. Below are the descriptions of the fields used in this analysis:

- inter_dom: Types of students (international or domestic)
- japanese_cate: Japanese language proficiency
- english_cate: English language proficiency
- academic: Current academic level (undergraduate or graduate)
- age: Current age of the student
- stay: Current length of stay in years
- todep: Total score of depression (PHQ-9 test)
- tosc: Total score of social connectedness (SCS test)
- toas: Total score of acculturative stress (ASISS test)

### Tools

- PostgreSQL
- Visual Studio Code

### Analysis

During this investigation, the query provided the following information:

- The number of international students for each length of stay.
- The average PHQ-9 depression score.
- The average SCS social connectedness score.
- The average ASISS acculturative stress score.

### Observations

Depression Scores (PHQ-9): Generally, depression scores tend to decrease slightly with longer stays, with the highest average score of 13.00 observed at a 10-year stay and the lowest average score of 0.00 at a 5-year stay. This suggests that longer stays might provide some adjustment and adaptation benefits that could reduce depression levels.

Social Connectedness Scores (SCS): Social connectedness scores vary, but there is no clear trend with length of stay. Scores range from 32.00 to 48.00, indicating variability in how well international students integrate socially.

Acculturative Stress Scores (ASISS): Acculturative stress shows a fluctuating pattern across different lengths of stay, with scores ranging from 45.00 to 91.00. Higher scores generally indicate greater stress associated with adapting to a new culture, which tends to be more pronounced in the initial years.

### Conclusion:
The data suggests that while longer stays may correlate with slightly lower depression scores, the variability in social connectedness and acculturative stress highlights ongoing challenges for international students. Universities can use these insights to tailor support services that address both social integration and stress management, particularly in the early stages of students' international experiences.

These findings underscore the importance of ongoing research and support mechanisms to enhance the well-being of international students in academic environments.

### References

- Datacamp
