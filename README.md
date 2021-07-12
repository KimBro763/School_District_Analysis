# School_District_Analysis
Pandas &amp; Jupyter Notebook

## Project Overview: Purpose and Background
The purpose of this project is to help the city school district prepare standardized test data for analysis, reporting, and presentation.  More specifically, student funding and standardized math and reading test scores were analyzed. An additional analysis required the removal of ninth grade scores from Thomas High School, which affected some of the metrics. Based on this information, trends regarding school performance are presented below. 




## School Analysis Results: 
The following addresses how each of seven school district metrics performed with and without ninth grade data from Thomas High School. 


### *1. Total School Budget*
The school district operated on a total budget of $24,649,428.  

### *2. Per Student Budget* 
The per student budget was segmented into bins. The first bin contained four schools that spent up to $584 per student. These schools had an average math score of 83.5, and an average reading score of 83.9. In addition, their passing math percentage was 93% and the passing reading percentage was 97%. Even though these schools spent the least amount per student, the overall passing percentage was 90%, which is the highest of all schools. The next spending range, $585 to $629, also represented four schools, and their corresponding scores were slightly lower than the $584 range. This trend continues for the third spending range, which was $630 to $644 per student.  Furthermore, the schools that spent the most per student ($645 to $675), had the lowest scores in each category. Ultimately, these three schools were the lowest performing of all. For further details, please refer to Table 1 below. 

*Table 1: Per Student Spending Summary*

<img width="594" alt="spending_summary" src="https://user-images.githubusercontent.com/84739988/125215095-f9868a00-e27f-11eb-88c7-3b10bab1f62f.png">


### *3. Average Math Score*
The district's average math score was 78.9%. Further, the average math scores for all grades in all schools falls between 75% and 85%. At 83.9%, Pena High School had the highest math score, and Huang High School reported the lowest average math score at 76.6%. In addition, Griffin High School's tenth grade had the highest average math score of all schools with a score of 84.2%. Alternatively, a dataframe was created to discover the difference in scores based on school size. Schools below 1,000 students scored highest in math, while the largest schools scored the lowest.  Finally, Charter Schools presented with a higher math score (83.5%) than District Schools (77%). Please see Table 2 below for more trends based on school size.

*Table 2: Math Scores by Grade*

<img width="213" alt="math_scores_by_grade" src="https://user-images.githubusercontent.com/84739988/125214931-44ec6880-e27f-11eb-933a-67fe0f6ec8cf.png">

*Table 3: Scores by School Size*

<img width="465" alt="scores_by_school_size" src="https://user-images.githubusercontent.com/84739988/125214917-330ac580-e27f-11eb-9809-5a5250229bac.png">




### *4. Average Reading Score*
The district's average reading score was 81.9%. While all reading scores fell between 80-90%, Pena High School reported the highest average math score at 84.0%, with their twelfth grade recording the highest average score at 84.6%. Alternatively, Rodriguez High School reported the lowest average math score at 80.74%. Based on school size, schools with less than 1,000 students and schools with 1,000 to 2,000 students had the highest average reading scores at 83.9%. Unfortunately, larger schools with 2,000 to 5,000 students scored the lowest at 81.3%. Finally, Charter Schools also scored higher on the average reading score with an 83.9%. For more details on average reading scores, refer to Table 4 below. 

*Table 4: Reading Scores by Grade*

<img width="229" alt="reading_scores_by_grade" src="https://user-images.githubusercontent.com/84739988/125214951-57ff3880-e27f-11eb-8388-2d55b3adb446.png">

*Table 5: Scores by School Type*

<img width="486" alt="scores_by_type" src="https://user-images.githubusercontent.com/84739988/125215424-12dc0600-e281-11eb-9181-352eef804352.png">




### *5. % Passing Math* 
Before removing the ninth grade data from Thomas High School, the district's passing math rate was 74.8%. However, once data was removed, the district's rate increased to 75.0%. Pena High School also had the highest percentage (94.6%) of students passing math than any other school. Alternatively, and in line with the average math scores above, Huang High School reported the lowest percentage of students passing math with 65.7% passing. Based on school size, larger schools with 2,000 to 5,000 students had the lowest passing math percentage with a 70% passing rate. Further, schools with less than 2,000 students scored a 94% passing rate. Following the same trends as before, Charter Schools also had a higher passing math percentage than District Schools at a 94% passing rate. 

*Table 6: District Summary Before 

<img width="608" alt="dist_summ_before" src="https://user-images.githubusercontent.com/84739988/125215049-c80dbe80-e27f-11eb-8e1a-6dce5af1d0f2.png">

*Table 7: District Summary After*

dist_summ_after<img width="581" alt="dist_summ_after" src="https://user-images.githubusercontent.com/84739988/125215060-d065f980-e27f-11eb-8270-93586b82388e.png">


### *6. % Passing Reading* 
The district's passing reading rate was 85.7% before the ninth grade data was removed. After recalculating, the passing reading rate for the district increased to 85.8%. Furthermore, before removing the ninth grade data, Thomas High School reported the highest passing reading rate at 97.3%. However, after the ninth grade data was dropped from the analysis, Thomas High School's passing percentage slightly decreased to 97.0%, but this also allowed for Griffin High School to rank first on passing reading percentage at 97.1%. In considering how school size affects the passing reading percentage, schools with 1,000 to 2,000 students had the highest passing reading rate at 97%, and again, the largest schools had the lowest passing percentage rate at 83%. Finally, Charter Schools scored higher than District Schools with a 97% passing reading rate. 

*Table 8: Passing Reading Before*

<img width="213" alt="reading_scores_by_grade_before" src="https://user-images.githubusercontent.com/84739988/125215653-add4e000-e281-11eb-90b2-c1cf864d7213.png">



*Table 9: Passing Reading After*

<img width="229" alt="reading_scores_by_grade_after" src="https://user-images.githubusercontent.com/84739988/125215673-b75e4800-e281-11eb-9c33-79b9a838cb62.png">


### *7. Overall Passing %* 
Combined reading and math scores gave the district an overall passing percentage of 65.17% before removing the ninth grade Thomas High School data. Once removed, the district's overall passing percentage decreased to 64.9%. With 91.3% of students passing math and reading, Cabrera High School has the highest overall passing percentage. Alternatively, Rodriguez High School reported the lowest scores with a 52.9% passing rate. Again, schools with 1,000 to 2,000 students had the highest overall passing percentage at 91%, while the largest schools reported the lowest overall passing percentage at 58%. Finally, Charter Schools out-scored District Schools with a 90% overall passing rate. For more information on the highest and lowest performing schools please see Tables 10 and 11 below. 

*Table 10: Highest Performing Schools*

<img width="610" alt="top_schools" src="https://user-images.githubusercontent.com/84739988/125215778-f7bdc600-e281-11eb-9c24-3fac891904e4.png">


*Table 11: Lowest Performing Schools*

<img width="619" alt="botom_schools" src="https://user-images.githubusercontent.com/84739988/125215797-01dfc480-e282-11eb-9aba-8a71527c5c85.png">


## *Summary:*
In summary, several trends were discovered throughout this analysis. Charter Schools seem to perform better than District Schools. Larger schools do not perform as well as smaller schools, and schools report higher reading scores than math scores. In addition, Cabrera High School was the highest performing school, while Johnson High School was the lowest performing school. Further analysis showed the affect of removing the ninth grade data. The passing reading rate, percentage passing math, percentage passing reading, and the overall passing percentage was affected by the removal of the data. 
