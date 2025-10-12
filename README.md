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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="header">
        <img src="slot time.png" alt="College Logo" class="logo" />
        <h1>SAVEETHA ENGINEERING COLLEGE</h1>
    </div>
    
    <h2>TIMETABLE</h2>
    
    
    <table>
        <thead>
            <tr>
                <th>Day/Time</th>
                <th>8.00-10.00</th>
                <th>10.00-12.00</th>
                <th>12.00-1.00</th>
                <th>1.00-3.00</th>
                <th>3.00-5.00</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>MONDAY</td>
                <td>-</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>L</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>-</td>
            </tr>
            <tr>
                <td>TUESDAY</td>
                <td>-</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
                <td>U</td>
                <td>DIGITAL ELECTRONICS</td>
                <td>PYTHON PROGRAMING</td>
            </tr>
            <tr>
                <td>WEDNESDAY</td>
                <td>DIGITAL ELECTRONICS</td>
                <td>-</td>
                <td>N</td>
                <td>MENTOR MEET</td>
                <td>-</td>
            </tr>
            <tr>
                <td>THURSDAY</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>CAREER DEVELOPMENTAL SKILLS</td>
                <td>C</td>
                <td>PYTHON PROGRAMING</td>
                <td>-</td>
            </tr>
            <tr>
                <td>FRIDAY</td>
                <td>-</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>H</td>
                <td>HUMAN VALUES AND ETHICS</td>
                <td>-</td>
            </tr>
            <tr>
                <td>SATURDAY</td>
                <td>-</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td></td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
                <td>-</td>
            </tr>
        </tbody>
    </table>
    
    <!-- Subject Table -->
    <h2>SUBJECTS</h2>
    <table class="subject-table">
        <thead>
            <tr>
                <th>S.NO.</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>19A1410</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
            </tr>
            <tr>
                <td>2</td>
                <td>SH3214</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EY708</td>
                <td>CAREER DEVELOPMENTAL SKILLS</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EE404</td>
                <td>DIGITAL ELECTRONICS</td>
            </tr>
            <tr>
                <td>6</td>
                <td>SH7801</td>
                <td>HUMAN VALUES AND ETHICS</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19AI301</td>
                <td>PYTHON PROGRAMING</td>
            </tr>
        </tbody>
    </table>
    </div>
    
</body>
</html>
.container {
    width: 80%;
    margin: 0 auto;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); /* Subtle shadow */
    padding: 20px;
    border-radius: 8px; /* Rounded corners */
    background-color: #ffffff; /* White */
}
.img {
    display: block;
    margin: 0 auto; /* Centers the image */
    width: 100px; /* Adjust as needed */
    height: auto;
}
h1 {
    text-align: center;
    color: hsl(210, 82%, 26%); /* Dark Blue Gray */
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 20px;
}

th, td {
    border: 1px solid #dcdcdc; /* Light Gray */
    padding: 10px;
    text-align: center;
}

th {
    background-color: #b2e0e6; /* Lighter Cyan */
    color: #004d4d; /* Darker Teal */
}

td {
    background-color: #e0f7fa; /* Light Blue */
}

.subject-table th {
    background-color: #ffe4e1; /* Misty Rose */
    color: #8b0000; 
}



OUTPUT:

<img width="1365" height="679" alt="image" src="https://github.com/user-attachments/assets/641b0bf4-fa28-446a-9801-127ff36430bd" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
