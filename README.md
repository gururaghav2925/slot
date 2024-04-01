# Ex03 Time Table
## Date:01/04/2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<head>
<title> My Time Table </title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
<style>
    .text{
        background-color: yellow;
        font-weight: bold;
    }
    #text{
        background-color: brown;
    }
    
</style>
<table border="3" cellspacing="6" cellpading="6">
<caption>SLOT TIMETABLE-GURU RAGHAV PONJEEVITH V(212223220027)</caption>
<tr>
<th bgcolor="Green">Day/Time</th>
<th id="text">Monday</th>
<th id="text" >Tuesday</th>
<th id="text">Wednesday</th>
<th id="text">Thursday</th>
<th id="text">Friday</th>
</tr>
<tr>0
<td class="text">8-10</td>
<td bgcolor="pink">BEEE</td>
<td bgcolor="pink">FREE</td>
<td bgcolor="pink">FREE</td>
<td bgcolor="pink">FREE</td>
<td bgcolor="pink">web</td>
</tr>
<tr>
<td class="text">10-12</td>
<td bgcolor="lightblue">FREE</td>
<td bgcolor="lightblue">Python</td>
<td bgcolor="lightblue">CN</td>
<td bgcolor="lightblue">C</td>
<td bgcolor="lightblue">FREE</td>
</tr>
<tr>
<td style="background-color: aquamarine;">12-1</td>
<td colspan="5" bgcolor="aquamarine">------------BREAK TIME------------</td>
</tr>
<tr>
<td class="text">1-3</td>
<td bgcolor="lightblue">MATHS</td>
<td bgcolor="lightblue">Python</td>
<td bgcolor="lightblue">FREE</td>
<td bgcolor="lightblue">FREE</td>
<td  bgcolor="lightblue">WEB</td>
</tr>
<tr>
<td class="text">3-5</td>
<td bgcolor="lightblue">MATH</td>
<td bgcolor="lightblue">WEB</td>
<td bgcolor="lightblue">FREE</td>
<td bgcolor="lightblue">SS</td>
<td bgcolor="lightblue">Python</td>
</tr>
</table>
<table border="2" cellspacing="5" cellpading="5">
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td>1.</td>
<td>19MA206</td>
<td>Logic And Combnatrics(LAC)</td>
</tr>
<tr>
<td>2.</td>
<td>19AI304</td>
<td>Fundamentals of C programming(C)</td>
</tr>
<tr>
<td>3.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Development(WEB)</td>
</tr>
<tr>
<td>4.</td>
<td>19EE305</td>
<td>Basic Electrical Electronics and Measurement Engineering(BEEE)</td>
<tr>
<td>5.</td>
<td>19CS406</td>
<td>computer Network(CN)</td>
</tr>
<tr>
<td>6.</td>
<td>19EY701</td>
<td>soft skill(SS)</td>
</tr>
<tr>
<td>7.</td>
<td>19CS301</td>
<td>Python programming(Python)</td>
</tr>
</table>
</center>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-04-01 150152.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
