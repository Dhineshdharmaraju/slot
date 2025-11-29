# Ex02 Time Table
## Date:29.11.2025

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
    <title>My Time Table</title>
       
</head>

    <body>
        <img src="logo.png" width="1200">

    <h3 align="center"> SLOT TIME TABLE - DINESH D (25018449)</h3>

    <table border="2" bgcolor="pink">
        <tr bgcolor="violet">
            <th>Time/Day</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td bgcolor="violet">08:00 - 10:00</td>
            <td align="center" colspan="2">ENG</td>
            <td align="center">FWAD</td>
            <td align="center">PYTHON</td>
            <td align="center">FREE SLOT</td>
            <td align="center">FWAD</td>
        </tr>
        <tr>
            <td bgcolor="violet">10:00 - 12:00</td>
            <td align="center" colspan="3">FWAD</td>
            <td align="center" colspan="2">FREE SLOT</td>
            <td align="center">ENG</td>
        </tr>
        <tr>
            <td bgcolor="violet">12:00 - 1:00</td>
            <td align="center" colspan="6" >LUNCH BREAK</td>
        </tr>
        <tr>
            <td bgcolor="violet">01:00 - 03:00</td>
            <td align="center">PYTHON</td>
            <td align="center">FREE SLOT</td>
            <td align="center">MENTOR MEET</td>
            <td align="center">ENG</td>
            <td align="center" colspan="2">FREE SLOT</td>
        </tr>
        <tr>
            <td bgcolor="violet">03:00 - 05:00</td>
            <td align="center">PYTHON</td>
            <td align="center" colspan="3">FREE SLOT</td>
            <td align="center">PYTHON</td>
            <td align="center">FREE SLOT</td>
    </table>
<br>
<br>

    <table border="2" bgcolor="red">
        <tr bgcolor="radium">
            <td align="center">S.NO.</td>
            <td align="center">Subject Code</td>
            <td align="center">Subject Name</td>
        </tr>
        <tr bgcolor="biege">
            <td align="center">1.</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamentals of Web Application Development</td>
        </tr>
        <tr bgcolor="biege">
            <td align="center">2.</td>
            <td align="center">19AI301</td>
            <td align="center">Python Programming</td>
        </tr>
        <tr bgcolor="biege">
            <td align="center">3.</td>
            <td align="center">19EN101</td>
            <td align="center">Communicative English</td>
        </tr>
    </table>

</body>

</html>
```
## OUTPUT
![alt text](<Screenshot 2025-11-29 082331.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
