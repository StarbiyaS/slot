# Ex03 Time Table
## Date:15-11-2023

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
<title>TIME TABLE - ODD JUNIOR</TITLE>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<table border="6" align="center" cellspacing="4">
<caption><b>TIME TABLE</b></caption>
<tr>
<th bgcolor="PaleVioletRed">DAYS/TIME</th>
<th bgcolor="PaleVioletRed">8.00am-10.00am</th>
<th bgcolor="PaleVioletRed">10.00am-12.00pm</th>
<th bgcolor="PaleVioletRed">12.00pm-1.00pm</th>
<th bgcolor="PaleVioletRed">1.00pm-3.00pm</th>
<th bgcolor="PaleVioletRed">3.00pm-5.00pm</th>
</tr>
<tr>
<th bgcolor="PaleVioletRed">MONDAY</th>
<td bgcolor="Thistle" align="center">C-PROGRAMMING</td>"
<td bgcolor="Thistle" align="center">SOFT SKILLS</td>
<td bgcolor="Thistle" align="center">LUNCH</td>
<td bgcolor="Thistle">PRINCIPLES OF CHEMISTRY</td>
<td bgcolor="Thistle" align="center">FREE</td>
</tr>
<tr>
<th bgcolor="PaleVioletRed">TUESDAY</th>
<td bgcolor="Thistle">COMMUNICATIVE ENGLISH</td>
<td bgcolor="Thistle" align="center">C-PROGRAMMING</td>
<td bgcolor="Thistle" align="center">LUNCH</td>
<td bgcolor="Thistle" align="center">EDM</td>
<td bgcolor="Thistle" align="center">FREE</td>
</tr>
<tr>
<th bgcolor="PaleVioletRed">WEDNESDAY</th>
<td bgcolor="Thistle" align="center">FUNDAMENTALS OF WEB</td>
<td bgcolor="Thistle" align="center">FREE</td>
<td bgcolor="Thistle" align="center">LUNCH</td>
<td bgcolor="Thistle">PRINCIPLES OF CHEMISTRY</td>
<td bgcolor="Thistle">CALCULAS AND MATRIX ALGEBRA</td>
</tr>
<tr>
<th bgcolor="PaleVioletRed">THURSDAY</th>
<td bgcolor="Thistle" align="center">EDM</td>
<td bgcolor="Thistle" align="center">FUNDAMENTALS OF WEB</td>
<td bgcolor="Thistle" align="center">LUNCH</td>
<td bgcolor="Thistle">COMMUNICATIVE ENGLISH</td>
<td bgcolor="Thistle" align="center">FREE</td>
</tr>
<tr>
<th bgcolor="PaleVioletRed">FRIDAY</th>
<td bgcolor="Thistle" align="center">FREE</td>
<td bgcolor="Thistle" align="center">FREE</td>
<td bgcolor="Thistle">MENTOR MEET</td>
<td bgcolor="Thistle" align="center">FUNDAMENTALS OF WEB</td>
<td bgcolor="Thistle">CALCULAS AND MATRIX ALGEBRA</td>
</tr>
</table>
<table align="center" cellspacing="3" cellpadding="15" border="2 bgcolor="black">
<tr align="center">
<th bgcolor="grey">S.NO</th>
<th bgcolor="grey">SUBJECT CODE</th>
<th bgcolor="grey">SUBJECT NAME</th>
</tr>
<tr>
<th align="center" bgcolor="pink"> 1. </th>
<td align="center" bgcolor="pink"> 19AI414 </td>
<td bgcolor="pink"> Fundamentals of Web Application Development </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 2. </th>
<td align="center" bgcolor="pink"> 19MA201 </td>
<td bgcolor="pink"> Calculas  Matrix </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 3. </th>
<td align="center" bgcolor="pink"> 19CY205 </td>
<td bgcolor="pink"> Principles of Chemistry in Engineering </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 4. </th>
<td align="center" bgcolor="pink"> 19AI302 </td>
<td bgcolor="pink"> Engineering Design and Modeling </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 5. </th>
<td align="center" bgcolor="pink"> 19EN101 </td>
<td bgcolor="pink"> Communicative English </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 6. </th>
<td align="center" bgcolor="pink"> 19EY701 </td>
<td bgcolor="pink"> Soft Skill </td>
</tr>
<tr>
<th align="center" bgcolor="pink"> 7. </th>
<td align="center" bgcolor="pink">19AI304 </td>
<td bgcolor="pink"> Fundamentals Of C Programming</td>
</tr>
</body>
</html>
```
## OUTPUT

![Alt text](<Screenshots/Screenshot 2023-11-15 165155.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
