# School_District_Analysis

 Summary:
        This "Student Data Challenge in pyton pandas is used for Education Department to analyze Schools and Students data for different purposes. By using this kind of data schools can make decisions about their students success and as they can analyze their budget as well so they can check which department need more budget and how their budget can give them maximum output. On the other hand it can be helpful for school boards and for government officials to decide about schools performance and for their budget. 
Resources:
    In this challenge there were two csv files to work on student data and school data that was combined in one file and information was provided in different columns.


While working on this project first Data is loaded using os.path.join. Then it is checked if there are any null values using “isnull” function. “Dropna” function is used to drop rows with null values.

![image](https://user-images.githubusercontent.com/112978144/207429143-d54c10d3-7a8c-4254-8f80-19698514ad08.png)



for duplicated rows, duplicate.sum function is used and got 2168 duplicated rows, “dtype” function is used to check data type and to change datatype ‘astype’ function is used. 
Summary statistics:


In deliverable 3 summary statistics of reading and maths are as follow.  the mean math score using the mean function were 64.67573326141189. Other statistics are as follow:
![image](https://user-images.githubusercontent.com/112978144/207429388-abea28bc-a5e8-47fb-9c54-34aa283d7d7a.png)



In deliverable 4 loc function work perfectly to display grade column and `iloc` function display the first 3 rows and columns 3, 4, and 5.

As shown in this img: ![image](https://user-images.githubusercontent.com/112978144/206323734-3aa7fb91-1e31-433c-86c3-032a58ced180.png)





Loc with condition function is used to get reading scores of 10th graders at Dixon High School

Groupby function is used to run following code:

![image](https://user-images.githubusercontent.com/112978144/207428745-dc3e593f-894e-4b10-8aa7-860c668630e8.png)






* The findings show that reading and math scores of Charter schools have a greater score than District schools. 

* The other irregular finding of this analysis is that when the budget per student increases student's average score decreases.

* The data shows that when the number of students sizes higher in schools the average scores, decrease. So, we can say that, when student size, increases it negatively influences student achievement. 

* Therefore, Government officials, School districts, and charters should work on student size and budget in schools in a way that they can get maximum outcome in education because, it directly affects overall growth of individual’s performance and on broader picture it affects highly on national growth.

	

