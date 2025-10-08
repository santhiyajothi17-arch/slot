# Ex03 Time Table
## Date:08/10/2025

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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Timetable</title>
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>

    <!-- Timeplan -->
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
        <caption><b>SLOT TIME TABLE - Bhavitra B (25012160)</b></caption>
        <tr align="center">
            <th bgcolor="yellow">Day/Time</th>
            <th bgcolor="yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
        </tr>

        <!-- 8-10 -->
        <tr align="center">
            <th bgcolor="yellow">8-10</th>
            <td>FREE SLOT</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>FREE SLOT</td>
            <td>DATA SCIENCE</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        </tr>

        <!-- 10-12 -->
        <tr align="center">
            <th bgcolor="yellow">10-12</th>
            <td>PYTHON PROGRAMMING</td>
            <td>DATA SCIENCE</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>PYTHON PROGRAMMING</td>
            <td>DATA SCIENCE</td>
        </tr>

        <!-- 12-1 -->
        <tr align="center">
            <th bgcolor="yellow">12-1</th>
            <td colspan="5">LUNCH BREAK</td>
        </tr>

        <!-- 1-3 -->
        <tr align="center">
            <th bgcolor="yellow">1-3</th>
            <td>FREE SLOT</td>
            <td>DATA SCIENCE</td>
            <td>MENTOR MENTEE SESSION</td>
            <td>FREE SLOT</td>
            <td>DATA SCIENCE</td>
        </tr>

        <!-- 3-5 -->
        <tr align="center">
            <th bgcolor="yellow">3-5</th>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>PYTHON PROGRAMMING</td>
            <td>PYTHON PROGRAMMING</td>
            <td>PYTHON PROGRAMMING</td>
        </tr>
    </table>

    <br><br>

    <!-- Fagkoder og fagnavn -->
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="lightgrey">
        <caption><b>SUBJECT DETAILS</b></caption>
        <tr align="center">
            <th>Sl.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr align="center">
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr align="center">
            <td>2.</td>
            <td>19AI301</td>
            <td>Python Programming(PP)</td>
        </tr>
        <tr align="center">
            <td>3.</td>
            <td>19AI403</td>
            <td>DATA SCIEDNCE(DS)</td>
        </tr>
       
    </table>
</body>
</html>


## OUTPUT
<!DOCTYPE html>
<html>
<head>
    <title>Slot Timetable</title>
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>

    <!-- Timeplan -->
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
        <caption><b>SLOT TIME TABLE - Bhavitra B (25012160)</b></caption>
        <tr align="center">
            <th bgcolor="yellow">Day/Time</th>
            <th bgcolor="yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
        </tr>

        <!-- 8-10 -->
        <tr align="center">
            <th bgcolor="yellow">8-10</th>
            <td>FREE SLOT</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>FREE SLOT</td>
            <td>DATA SCIENCE</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        </tr>

        <!-- 10-12 -->
        <tr align="center">
            <th bgcolor="yellow">10-12</th>
            <td>PYTHON PROGRAMMING</td>
            <td>DATA SCIENCE</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>PYTHON PROGRAMMING</td>
            <td>DATA SCIENCE</td>
        </tr>

        <!-- 12-1 -->
        <tr align="center">
            <th bgcolor="yellow">12-1</th>
            <td colspan="5">LUNCH BREAK</td>
        </tr>

        <!-- 1-3 -->
        <tr align="center">
            <th bgcolor="yellow">1-3</th>
            <td>FREE SLOT</td>
            <td>DATA SCIENCE</td>
            <td>MENTOR MENTEE SESSION</td>
            <td>FREE SLOT</td>
            <td>DATA SCIENCE</td>
        </tr>

        <!-- 3-5 -->
        <tr align="center">
            <th bgcolor="yellow">3-5</th>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>PYTHON PROGRAMMING</td>
            <td>PYTHON PROGRAMMING</td>
            <td>PYTHON PROGRAMMING</td>
        </tr>
    </table>

    <br><br>

    <!-- Fagkoder og fagnavn -->
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="lightgrey">
        <caption><b>SUBJECT DETAILS</b></caption>
        <tr align="center">
            <th>Sl.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr align="center">
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr align="center">
            <td>2.</td>
            <td>19AI301</td>
            <td>Python Programming(PP)</td>
        </tr>
        <tr align="center">
            <td>3.</td>
            <td>19AI403</td>
            <td>DATA SCIEDNCE(DS)</td>
        </tr>
       
    </table>
</body>
</html>


## RESULT
<img width="1920" height="978" alt="image" src="https://github.com/user-attachments/assets/61044efc-6e65-4547-b3c9-2f9c629d652f" />

The program for creating slot timetable using basic HTML tags is executed successfully.
