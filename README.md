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
<body bgcolor="lavender">
    <img src="/static/logo.png" width="800" height="80" hspace="360">
    <caption><h2 align="center">TIME TABLE - SURYAPRAKSH P N(26010234)</h2></caption>

    <table border="5" bordercolor="gray"
           align="center" cellpadding="5" cellspacing="5" height="100" width="55%">

        <tr bgcolor="cyan">
            <th>DAY/TIME</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
        </tr>

        <tr bgcolor="white">
            <th bgcolor="cyan">8.00 TO 9.30</th>
            <td align="center">FCC</td>
            <td align="center">PY</td>
            <td align="center">FWAD</td>
            <td align="center">MAT</td>
            <td align="center">PY</td>
            <td align="center" bgcolor="orange">FREE</td>
        </tr>

        <tr bgcolor="white">
            <th bgcolor="cyan">9.45 TO 11.15</th>
            <td align="center">FWAD</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center">FCC</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center">CDS</td>
        </tr>

        <tr bgcolor="white">
            <th bgcolor="cyan">11.30 TO 1.00</th>
            <td colspan="6" align="center">L U N C H / ECA-SCOFT-M</td>
        </tr>

        <tr bgcolor="white">
            <th bgcolor="cyan">1.15 TO 2.45</th>
            <td align="center">PY</td>
            <td align="center">FWAD</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center">EDM</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center">MAT</td>
        </tr>

        <tr bgcolor="white">
            <th bgcolor="cyan">3.00 TO 4.30</th>
            <td align="center">DE</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center">EDM</td>
            <td align="center" bgcolor="orange">FREE</td>
            <td align="center">DE</td>
            <td align="center" bgcolor="orange">FREE</td>
        </tr>
    </table>

    <br>

    <table border="2" bordercolor="green" cellspacing="5"
           align="center" cellpadding="5" bgcolor="pink" height="200" width="55%">

        <tr bgcolor="lavender">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">1.</td>
            <td align="center" bgcolor="white">19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">2.</td>
            <td align="center" bgcolor="white">19AI302</td>
            <td>Engineering Design and Modelling (EDM)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">3.</td>
            <td align="center" bgcolor="white">19MA201</td>
            <td>Calculus and Matrix Algebra (MAT)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">4.</td>
            <td align="center" bgcolor="white">19CS547</td>
            <td>Fundamentals of Cryptocurrency (FCC)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">5.</td>
            <td align="center" bgcolor="white">19AI301</td>
            <td>Python Programming (PY)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">6.</td>
            <td align="center" bgcolor="white">19EY708</td>
            <td>Career Development Skills (CDS)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">7.</td>
            <td align="center" bgcolor="white">19EE404</td>
            <td>Digital Electronics (DE)</td>
        </tr>

        <tr>
            <td align="center" bgcolor="yellow">8.</td>
            <td align="center" bgcolor="white">ECA-SCOFT-M</td>
            <td>SCOFT Mentor Meeting</td>
        </tr>
    </table>

</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (17).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
