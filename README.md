# Ex03 Time Table
## Date:

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
    <title>SLOT TIMETABLE</title>
</head>
<center>
<img src="/static/logo.png" width='600'align="center">
</center>
<body>
    <table BORDER='3' width='600'bgcolor='white' cellspacing='3' align="center">
        <CAPTION align="above">SLOT TIMETABLE- HARINI S(212223040058)</CAPTION>
        <tr>
            <th align="center" bgcolor="yellow">Day/Time</th>
            <th align="center" bgcolor="yellow">Monday</th>
            <th align="center" bgcolor="yellow">Tuesday</th>
            <th align="center" bgcolor="yellow">Wednesday</th>
            <th align="center" bgcolor="yellow">Thursday</th>
            <th align="center" bgcolor="yellow">Friday</th>
            <th align="center" bgcolor="yellow">Saturday</th>
    
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">8-10</th>
            <td align="center" bgcolor="lightblue">Digital Electronics</td>
            <td align="center" bgcolor="lightblue">Algebra and number theory</td>
            <td align="center" bgcolor="lightblue">German basic and advanced</td>
            <td align="center" bgcolor="lightblue">Free slot</td>
            <td align="center" bgcolor="lightblue">Fundamentals of application and Web Development</td>
            <td align="center" bgcolor="lightblue">Free slot</td>
           
            
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">10-12</th>
            <td align="center" bgcolor="lightblue">Free slot</td>
            <td align="center" bgcolor="lightblue">Fundamentals of application and Web Development</td>
            <td align="center" bgcolor="lightblue">Free slot</td>
            <td align="center" bgcolor="lightblue">Free slot</td>
            <td align="center" bgcolor="lightblue">python programming</td>
            <td align="center" bgcolor="lightblue">Operating system</td>
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">12-1</th>
            <td align="center" bgcolor="lightblue" colspan="6">LUNCH</td>
        </tr>

        <tr>
            <th align="center" bgcolor="yellow">1-3</th>
            <td align="center" bgcolor="lightblue">German basic and advanced</td>
            <td align="center" bgcolor="lightblue">Free slot</td>
            <td align="center" bgcolor="lightblue">Creative skills</td>
            <td align="center" bgcolor="lightblue">Algebra and number theory</td>
            <td align="center" bgcolor="lightblue">Digital electronics</td>
            <td align="center" bgcolor="lightblue">Free slot</td>
        </tr>


        <tr>
            <th align="center" bgcolor="yellow">3-5</th>
            <td align="center" bgcolor="lightblue">Operating System</td>
            <td align="center" bgcolor="lightblue">German basic and advanced</td>
            <td align="center" bgcolor="lightblue">Fundamentals of application and Web Development</td>
            <td align="center" bgcolor="lightblue">Python programming</td>
            <td align="center" bgcolor="lightblue">Free slot</td>
            <td align="center" bgcolor="lightblue">Free slot</td>
        </tr>
    </table>

    <table border="3" width="600" cellspacing="6" cellpaddling="6" align="center">

        <tr>
            <th align="center">S.NO</th>
            <th align="center">SUBJECT CODE</th>
            <th align="center">subject name</th>
        </tr>

        <tr>
            <td align="center">1</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamental of Web Application Development(FWAD)</td>
        </tr>

        <tr>
            <td align="center">2</td>
            <td align="center">19AI301</td>
            <td align="center">Python Programming</td>
        </tr>

        <tr>
            <td align="center">3</td>
            <td align="center">19EY702</td>
            <td align="center">Creative Skills</td>
        </tr>

        </tr>

        <tr>
            <td align="center">4</td>
            <td align="center">19MA212</td>
            <td align="center">Algebra and number theory</td>
        </tr>
        <tr>
            <td align="center">5</td>
            <td align="center">19EE404</td>
            <td align="center">Digital Electronics</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19CS405</td>
            <td align="center">Operating System</td>
        </tr>
    </body>
    </html>
```


## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
