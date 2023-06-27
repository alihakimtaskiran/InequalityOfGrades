# Bilkent University Grade Analysis

This repository contains a Jupyter Notebook that demonstrates the calculation of the Gini index and the plotting of the Lorenz curve for student grades at Bilkent University.

## Introduction
Understanding the distribution of grades among students is essential for analyzing academic performance and identifying potential areas of improvement. The Gini index is a measure of inequality often used to assess income distribution, and it can also be applied to grade distributions. The Lorenz curve provides a visual representation of the grade distribution.

In this notebook, we utilize the powerful NumPy library to calculate the Gini index and plot the Lorenz curve based on student grades at Bilkent University.

## Key Findings

The table provides the Gini index values for different courses at Bilkent University. The Gini index is a measure of inequality in grade distribution, where lower values indicate less inequality and higher values indicate more inequality.

Based on the Gini index values, the courses can be categorized as follows:

-  Low Inequality (Deep Sky Blue): Courses with Gini index values ranging from 0.07 to 0.19 (inclusive). These courses exhibit relatively low grade inequality among students.

-   Moderate Inequality (Green): Courses with Gini index values ranging from 0.21 to 0.25 (inclusive). These courses demonstrate a moderate level of grade inequality among students.

-   High Inequality (Orange): Courses with Gini index values ranging from 0.28 to 0.39 (inclusive). These courses exhibit a high degree of grade inequality among students.

-   Severe Inequality (Red): Courses with Gini index values ranging from 0.41 to 0.63 (inclusive). These courses demonstrate a severe level of grade inequality among students.

The key findings suggest that there is variation in grade inequality among different courses at Bilkent University. Courses with lower Gini index values (Deep Sky Blue) indicate a more equal distribution of grades, while courses with higher Gini index values (Maroon) depict a greater degree of grade inequality.

Understanding these differences in grade distribution can help identify areas where there might be challenges in academic performance and grading practices, prompting further investigation and potential improvements to ensure fairness and equal opportunities for all students.

Grade Inequality

Note: The image above provides a visual representation of the grade inequality for all courses at Bilkent University.


|Course|Gini Index|
|---|---|
|<font color="deepskyblue">HIST200</font>|0.07|
|<font color="deepskyblue">ENG401</font>|0.11|
|<font color="deepskyblue">ENG102</font>|0.16|
|<font color="deepskyblue">TURK102</font>|0.17|
|<font color="deepskyblue">PHYS252</font>|0.19|
|<font color="deepskyblue">HUM112</font>|0.19|
|<font color="green">IE102</font>|0.21|
|<font color="green">ENG101</font>|0.21|
|<font color="green">HUM111</font>|0.21|
|<font color="green">TURK101</font>|0.25|
|<font color="green">EE211</font>|0.28|
|<font color="orange">EE202</font>|0.32|
|<font color="orange">EE212</font>|0.34|
|<font color="orange">CS105</font>|0.36|
|<font color="orange">EE102</font>|0.38|
|<font color="orange">MATH242</font>|0.39|
|<font color="orange">PHYS101</font>|0.39|
|<font color="red">MATH241</font>|0.41|
|<font color="red">MATH255</font>|0.42|
|<font color="red">PHYS102</font>|0.47|
|<font color="maroon">MATH101</font>|0.58|
|<font color="maroon">MATH102</font>|0.63|
**Lower is better**: <font color="maroon">Severe</font>, <font color="red">High</font>, <font color="orange">Reasonable</font>, <font color="green">Moderate</font>,<font color="deepskyblue">Low</font>.
 This data analysis depict the inequality of Bilkent University students in terms of their grades

 

## Calculating Gini Index
The notebook demonstrates how to calculate the Gini index using NumPy. It utilizes the Lorenz curve concept to measure the inequality in the grade distribution. The Gini index value ranges from 0 to 1, where 0 represents perfect equality (all students have the same grade) and 1 represents maximum inequality (one student has all the grades).

## Plotting Lorenz Curve
The notebook also showcases how to plot the Lorenz curve using Matplotlib. The Lorenz curve visually represents the cumulative distribution of grades among students. It provides insights into the concentration or dispersion of grades.

## Contributing
Contributions to the research project are highly dependent on the availability of data. If you have letter grade statistics data of any course that can aid the research, you are encouraged to contribute.
To contribute to the research, please email me at alihakimxyz@gmail.com.

## Acknowledgements
I specially thank Semih Akkoç for me to provide data of some courses
## License
This repository is licensed under the [GNU GPL3 License](LICENSE). You are free to use the code and modify it according to your needs.
