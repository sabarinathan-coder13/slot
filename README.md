# Ex02 Time Table
## Date:30.11.2025

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
        <title>Timetable</title>
    </head>
    <body>
        <img src="logo.png" width="594px;">
        <br>
        <br>
        <table border="4" cellspacing="3" cellpadding="6" style="background-color: rgb(107, 208, 112);">
            <caption><b>SLOT TIME TABLE - SABARINATHAN A (25005972)</b></caption>
            <tr bgcolor="Gray" align="center">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="Red" align="center">
                <td bgcolor="Pink">8-10</td>
                <td>FREE SLOT</td>
                <td>FCP</td>
                <td colspan="2">FREE SLOT</td>
                
                <td>FWAD</td>
                <td>FREE SLOT</td>
            </tr>
            <tr bgcolor="Red" align="center">
                <td bgcolor="Pink">10-12</td>
                <td>FCP</td>
                <td>CE</td>
                <td>FREE SLOT</td>
                <td>CE</td>
                <td>FWAD</td>
                <td>FWAD</td>
            </tr>
            <tr bgcolor="Red" align="center">
                <td bgcolor="Pink">12-1</td>
                <td colspan="6">LUNCH BREAK</td>
            </tr>
            <tr bgcolor="Red" align="center">
                <td bgcolor="Pink">1-3</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>ECA-M</td>
                <td>CE</td>
                <td colspan="2">FREE SLOT</td>
                
            </tr>
            <tr bgcolor="Red" align="center">
                <td bgcolor="Pink">3-5</td>
                <td>FREE SLOT</td>
                <td>FCP</td>
                <td>FCP</td>
                <td>FCP</td>
                <td>FREE SLOT</td>
                <td>CE</td>
            </tr>
        </table>
        <br>
        <table border="3" cellspacing="4" cellpadding="4">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th style="width: 408px;">Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI304</td>
                <td>Fundamentals of C Programming (FCP)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19EN101</td>
                <td>Communicative English (CE)</td>
            </tr>
        </table>
    </body>
</html>
```

##cd OUTPUT

![alt text](<Screenshot (43).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
