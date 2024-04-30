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
![Screenshot (14)](https://github.com/sheroneysa/Ex06_Web-Design/assets/167157047/c2c28f4a-bcd6-488e-9589-4cece0ca3a2f)
![Screenshot (15)](https://github.com/sheroneysa/Ex06_Web-Design/assets/167157047/af0705d0-3da8-408f-9598-9b88f79c8088)
![Screenshot (16)](https://github.com/sheroneysa/Ex06_Web-Design/assets/167157047/50c01082-638c-4ab7-89d9-3c74bcc78d66)
![Screenshot (17)](https://github.com/sheroneysa/Ex06_Web-Design/assets/167157047/4ad66c70-a476-4e89-a9e2-2ceaa2428d1e)
![Screenshot (18)](https://github.com/sheroneysa/Ex06_Web-Design/assets/167157047/c599f5a0-44ad-45dd-96c8-bf72b3d9f803)
![Screenshot (19)](https://github.com/sheroneysa/Ex06_Web-Design/assets/167157047/a67f03aa-0ee8-4fe5-81d4-1bc671886f71)








## RESULT
  Student result using JavaScript is created successfully.
