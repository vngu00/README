# CONTENTS
* Introduction
* Requirements
* Pseudo Code
* Configuration
* Maintainers

# INTRODUCTION
The Lab 1 Activity is to show how we want our class grade to be determined. In this assignment, we take the different categories that will make up our grade and determine the percentage that it should take. The different categories which will be mentioned are: homework assignments, midterm, project, and final. 

# REQUIREMENTS
There are no requirements for this assignment.

# PSEUDO CODE
float Final_grade = 1.00  
float Homework = 0.45  
float Midterm = 0.2  
float Project = 0.15  
float Final = 0.2  

if [  
    print("Please enter name of student: ")  
    //pass input as string and store in array  
    print("Please enter student ID: ")  
    //pass input as int and store in array  
    print("Would you like to add another student? Y for Yes. N for No")  
    //pass input as string. If y was chosen, loop again. If no, end loop.  
    ]  
    print("How many homework assignments were assigned?")  
    //pass input as int. Use this for length of homework assignments array and to divide.  
    print("How many projects were assigned?")
    //pass input as int. Use this for length of projects array and to divide.  
    for(int homework_assignments:int i)[ //this will loop for the number they entered for homework assignments.  
        print("Enter" name "homework assignment grade.")  
        pass input into homework_array as float  
    ]  
    print(homework_array) //prints list of students  
    float final_homework = (homework_score = sum of homework_array / int homework_assignments)*weekly  
    //repeat this process for projects  
    print("Enter the Midterm Score: ") //pass as midterm_score  
    float final_midterm = midterm_score*midterm  
    //repeat this process for final  
    final_grade = final_homework + final_project + final_midterm + final_final  
    if final_grade >= .90:return"A"  
        if 90 > score >= .80:return"B"  
        if 80 > score >= .70:return"C"  
        if 70 > score >= .60:return"D"  
        if 60 > score:return"F"  
    

# CONFIGURATION

# MAINTAINERS
* Vivi Nguyen - https://github.com/vngu00
