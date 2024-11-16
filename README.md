# Ex03 Time Table
## Date:16-11-24

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
'''
<html>
    <head>
        <title>my timetable</title>
    </head>
    <body>
        <center>
        <img src="\static\logo.png" width="700"><br>
        <b>SLOT TIME TABLE-YUVARAM S (24900232)</b>
        <TABLE BORDER="1" CELLPADDING="5" BGCOLOR="aqua" width="700">
        <tr BGCOLOR="yellow">
            <TH>TIME</TH><th>MON</th><TH>THU</TH><TH>WEN</TH><TH>THR</TH><TH>FRI</TH><TH>SAT</TH>
        </tr>
        <TR>
            <TD BGCOLOR="yellow">08-10</TD>
            <TD colspan="2">-----------------------------------</TD>
            <TD>Python</TD><TD colspan="3">-------------------------------------------------------</TD>
        </TR>
        <TR>
            <TD BGCOLOR="yellow">10-12</TD>
            <TD>Fundamentals of Web Application Development</TD>
            <TD>Introduction to Data Science</TD>
            <TD>Fundamentals of Web Application Development</TD>
            <TD>Python</TD>
            <TD>Physics For Quantum Computing</TD><TD>PYTHON</TD>
        </TR>
        <TR>
            <TD COLSPAN="7" ALIGN="CENTER" BGCOLOR="yellow">&LT;12:00-1:00&GT;LUNCH</TD>
        </TR>
        <TR>
            <TD BGCOLOR="yellow">01-03</TD><TD>Career Development Skill</TD><TD>Python</TD><TD>MENTOR MEETING</TD><TD>Physics For Quantum Computing</TD><TD>Introduction to Data Science</TD><TD>Fundamentals of Web Application Development</TD>
        </TR>

        </TABLE>
        </center><BR>
        <center>
            <table border="2" cellpadding="5" width="700">
                <tr><th>s.no</th><th>Subject Code</th><th>Subject Name</th></tr>
                <tr><td>01</td><td>19AI301</td><td>Python</td></tr>
                <tr><td>02</td><td>19AI403</td><td>Introduction to Data Science</td></tr>
                <tr><td>03</td><td>19AI414</td><td>Fundamentals of Web Application Development</td></tr>
                <tr><td>04</td><td>SH3214</td><td>Physics For Quantum Computing</td></tr>
                <tr><td>05</td><td>19EY708</td><td>Career Development Skills</td></tr>
            </table>
        </center>
    </body>
</html>
'''

## OUTPUT
![alt text](<Screenshot 2024-11-16 151033-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
