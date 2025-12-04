## Ex03 Time Table
## Date:28/11/2025
## Register Number:25015366

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
<title>Slot Timetable</title>
</head>

<body style="font-family: Arial; background-color: #f2f6ff;">

<center>
    <img src="/static/logo1.png" height="100" width="540">
</center>

<br>

<!-- MAIN TIMETABLE -->
<table align="center" width="700" cellspacing="2" cellpadding="6" 
       border="3" style="background-color:#f2f6ff; border-color:#004c99; border-radius:10px;">

<caption style="font-size:22px; font-weight:bold; color:#003366; padding:10px;">
    SLOT TIME TABLE - Ritesh DP (25015366)
</caption>

<tr align="center" style="background-color:#0066cc; color:white;">
<th>Day / Time</th>
<th>Monday</th>
<th>Tuesday</th>
<th>Wednesday</th>
<th>Thursday</th>
<th>Friday</th>
</tr>

<tr align="center">
<th style="background:#ffcc00;">8–10</th>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>STATISTICS & NUMERICAL METHODS</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
</tr>

<tr align="center" style="background-color:#f9ffff;">
<th style="background:#ffcc00;">10–12</th>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>FREE SLOT</td>
<td>STATISTICS & NUMERICAL METHODS</td>
</tr>

<tr style="background:#ffe680; font-weight:bold;">
<th style="background:#ffcc00;">12–1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>

<tr align="center">
<th style="background:#ffcc00;">1–3</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>SOFT SKILLS</td>
</tr>

<tr align="center" style="background-color:#f9ffff;">
<th style="background:#ffcc00;">3–5</th>
<td>STATISTICS & NUMERICAL METHODS</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
</tr>

</table>

<br>

<!-- SUBJECT TABLE -->
<table align="center" cellspacing="2" cellpadding="6" border="3"
       style="width:600px; background:#fff; border-color:#0066cc; border-radius:10px;">

<tr align="center" style="background:#0066cc; color:white;">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>

<tr style="background:#f2f9ff;">
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>Fundamentals of C Programming (C PROGRAM)</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>

<tr style="background:#f2f9ff;">
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>

</table>

</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-12-04 230632.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.



