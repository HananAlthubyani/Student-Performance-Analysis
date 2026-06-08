# Student-Performance-Analysis
this study aims to analyze student performance using 13 selected features from the Student Performance Dataset. The analysis focuses on identifying the factors that influence academic achievement and understanding how student performance changes across different demographic, family, and educational characteristics.
Dataset
The dataset contains student information collected from secondary schools. Although the original dataset includes 33 features, this project focuses on the following 13 features:
•	school
•	sex
•	age
•	address
•	famsize
•	Medu
•	Fedu
•	guardian
•	G1
•	G2
•	G3
Objectives
The analysis aims to answer the following questions:
1.	Does the school play a role in grade improvement?
2.	Do male or female students achieve higher grades?
3.	Does age affect student performance?
4.	Does the type of residence influence academic performance?
5.	What is the relationship between family size and student performance?
6.	Does parents' educational level affect school performance?
7.	Does the role of a guardian affect student performance?

Data Analysis
The following techniques were used:
•	Data Cleaning
•	Descriptive Statistics
•	Correlation Analysis
•	Data Visualization
•	ANOVA Test
•	Grade Comparison Analysis
Key Findings
Statistical analysis found that students’ final academic performance ($G3$) is most strongly influenced by parental education, especially mothers’ education (Medu, $p < 0.001$, $r = 0.22$), followed by fathers’ education (Fedu, $p = 0.022$, $r = 0.15$). In short, students with more educated parents tend to do better. Age also matters—older students in this group tend to score lower ($p = 0.024$, $r = -0.16$), possibly due to repeating grades. Living in an urban area (address, $p = 0.035$, $r = 0.11$) and gender (sex, $p = 0.039$, $r = 0.10$) had small but statistically significant effects, with urban students and some gender groups performing slightly better. However, the specific school attended, family size, and type of legal guardian had no meaningful impact, as their $p$-values were not significant. In short, parental education is the strongest factor, while school, family structure, and guardian status do not appear to matter much.
Technologies Used
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	SciPy
