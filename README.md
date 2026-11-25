# Ex04 Time Table
## Date:18/11/2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
   <head>
    <title>Time Table</title>
   </head>
   <body bgcolor="lightblue">
    <img src="/static/logo.png" width="1000" height="77" hspace="295">

    <caption><h2 align="center">TIME TABLE - SURYAPRAKSH P N(26010234)</h2></caption>

    <table border="6" align="center" cellpadding="1" cellspacing="4" height="75" width="45%">

        <tr bgcolor="gold">
            <th>DAY/TIME</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
        </tr>

        <tr bgcolor="gray">
            <th bgcolor="lime">8.00 TO 9.30</th>
            <td align="center" bgcolor="maroon">FCC</td>
            <td align="center" bgcolor="teal">PY</td>
            <td align="center" bgcolor="violet">FWAD</td>
            <td align="center" bgcolor="coral">MAT</td>
            <td align="center" bgcolor="teal">PY</td>
            <td align="center" bgcolor="orange">FREE</td>
        </tr>

        <tr bgcolor="gray">
            <th bgcolor="lime">9.45 TO 11.15</th>
            <td align="center" bgcolor="violet">FWAD</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center" bgcolor="maroon">FCC</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center" bgcolor="magenta">CDS</td>
        </tr>

        <tr bgcolor="gray">
            <th bgcolor="lime">11.30 TO 1.00</th>
            <td colspan="6" align="center" bgcolor="warm brown">L U N C H / ECA-SCOFT-M</td>
        </tr>

        <tr bgcolor="gray">
            <th bgcolor="lime">1.15 TO 2.45</th>
            <td align="center" bgcolor="teal">PY</td>
            <td align="center" bgcolor="violet">FWAD</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center" bgcolor="navy blue">EDM</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center" bgcolor="coral">MAT</td>
        </tr>

        <tr bgcolor="gray">
            <th bgcolor="lime">3.00 TO 4.30</th>
            <td align="center" bgcolor="cyan">DE</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center" bgcolor="navy blue">EDM</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center" bgcolor="cyan">DE</td>
            <td align="center" bgcolor="orange">FREE</td>
        </tr>
    </table>

    <br><br>

    <table border="3"  cellspacing="5" align="center" cellpadding="5" height="75" width="45%">

        <tr bgcolor="lavender">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">1.</td>
            <td align="center" bgcolor="gray">19AI414</td>
            <td bgcolor="gold">Fundamentals of Web Application Development (FWAD)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">2.</td>
            <td align="center" bgcolor="gray">19AI302</td>
            <td bgcolor="gold">Engineering Design and Modelling (EDM)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">3.</td>
            <td align="center" bgcolor="gray">19MA201</td>
            <td bgcolor="gold">Calculus and Matrix Algebra (MAT)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">4.</td>
            <td align="center" bgcolor="gray">19CS547</td>
            <td bgcolor="gold">Fundamentals of Cryptocurrency (FCC)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">5.</td>
            <td align="center" bgcolor="gray">19AI301</td>
            <td bgcolor="gold">Python Programming (PY)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">6.</td>
            <td align="center" bgcolor="gray">19EY708</td>
            <td bgcolor="gold">Career Development Skills (CDS)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">7.</td>
            <td align="center" bgcolor="gray">19EE404</td>
            <td bgcolor="gold">Digital Electronics (DE)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">8.</td>
            <td align="center" bgcolor="gray">ECA-SCOFT-M</td>
            <td bgcolor="gold">SCOFT Mentor Meeting</td>
        </tr>
    </table>

</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (24).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
