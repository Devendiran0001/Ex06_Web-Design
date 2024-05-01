# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("No Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click here to Find Grade Result of a Student
</h1>
</body>
</html>
```

## OUTPUT
![Screenshot (8)](https://github.com/Devendiran0001/Ex06_Web-Design/assets/167397898/4b11fcd2-cea1-442d-bcd2-4410f6d17f7a)
![Screenshot (9)](https://github.com/Devendiran0001/Ex06_Web-Design/assets/167397898/fb9661b2-61f0-413d-bd7d-686f4b766f93)
![Screenshot (10)](https://github.com/Devendiran0001/Ex06_Web-Design/assets/167397898/c1125074-41ef-4f24-9c55-1040e8fae834)
![Screenshot (11)](https://github.com/Devendiran0001/Ex06_Web-Design/assets/167397898/136bbd35-2ffa-432f-b614-cceaa3a3044d)
![Screenshot (12)](https://github.com/Devendiran0001/Ex06_Web-Design/assets/167397898/d5291a7e-1453-443a-b274-d8819a5a8a9c)
![Screenshot (13)](https://github.com/Devendiran0001/Ex06_Web-Design/assets/167397898/44f790f3-e9cf-400a-aca5-e72bc1273251)







## RESULT
  Student result using JavaScript is created successfully.
