# Ex02 Time Table
## Date:27/11/2025

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
        <title>My Timetable</title>
    </head>
    <body bgcolor="rainbow">
        <img src="logo.png" width="1500">
        <table border="5" cellspacing="4" cellpadding="7" >
            <caption><b>SLOT  TIME  TABLE - ROHITH (25018770)</b></caption>
            <tr align="center" bgcolor="red">
                <td>Day/Time</td>
                <td>Monday</td>
                <td >Tuesday</td>
                <td>Wednessday</td>
                <td>Thursday</td>
                <td>Friday</td>
                <td>Saturday</td>
            </tr>
            <tr align="center">
                <td bgcolor="xanadu">8-10</td>
                <td bgcolor="blue">English</td>
                <td bgcolor="blue">English</td>
                <td bgcolor="cyan">FWAD</td>
                <td bgcolor="green">Python</td>
                <td>Free Slot</td>
                <td bgcolor="cyan">FWAD</td>
            </tr>
            <tr align="center">
                <td bgcolor="australien">10-12</td>
                <td bgcolor="cyan">FWAD</td>
                <td bgcolor="cyan">FWAD</td>
                <td bgcolor="cyan">FAWD</td>
                <td colspan="2">Free Slot</td>
                <td bgcolor="blue">English</td>
            </tr>
            <tr align="center">
                <td bgcolor="amaranth">12-1</td>
                <td colspan="6" bgcolor="purple" >LUNCH</td>
            </tr>
            <tr align="center">
                <td bgcolor="gingerline" >1-3</td>
                <td bgcolor="green">Python</td>
                <td>Free Slot</td>
                <td>Mentor Meet</td>
                <td bgcolor="blue">English</td>
                <td>Free Slot</td>
                <td bgcolor="green">Python</td>
            </tr>
            <tr align="center">
                <td bgcolor="falu">3-5</td>
                <td bgcolor="green">Python</td>
                <td colspan="3">Free slot</td>
                <td bgcolor="green">Python</td>
                <td>Free Slot</td>
            </tr>
        </table>
        <br>
        <br>
        <table border="2" cellspacing="4" cellpadding="8">
            <tr align="center" bgcolor="coquelicot">
                <th>S. No</th>
                <th>Subgect Code</th>
                <th>Subject Name</th>
            </tr>
            <tr align="center">
                <td bgcolor="maroon" >1.</td>
                <td>19AI414</td>
                <td>Fundamental of Web Application Development (FWAD)</td>
            </tr>
            <tr align="center">
                <td bgcolor="maroon">2.</td>
                <td>19EN101</td>
                <td>Comunicative English</td>
            </tr>
            <tr align="center">
                <td bgcolor="maroon">3.</td>
                <td>19AI301</td>
                <td>Python</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (19).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
