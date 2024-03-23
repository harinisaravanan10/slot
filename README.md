# Ex03 Time Table
## Date:23.03.2024

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
<html>
    <head>

    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100"width="540">
        </center>
        <br>
        <table align="center" width="540">
            <caption><b>SLOT TIMETABLE HARINI S(212223040058)</b></caption>
            <tr align="center">
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">Monday</th>
                <th bgcolor="yellow">Tuesday</th>
                <th bgcolor="yellow">Wednesday</th>
                <th bgcolor="yellow">Thursday</th>
                <th bgcolor="yellow">Friday</th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">8-10</th>
                <td bgcolor="blue">DIGITAL ELECTRONICS</td>
                <td bgcolor="blue">ALGEBRA AND NUMBER ALGEBRA</td>
                <td bgcolor="blue">GERMAN BASIC AND ADVANCEDR</td>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="blue">FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT </td>
            </tr>
            <tr align="centre">
                <th bgcolor="yellow">10-12</th>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="blue">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="blue">PYTHON PROGRAMMING</td>
            </tr>
            <tr align="centre">
                <th bgcolor="yellow">12-1</th>
                <td bgcolor="blue">LUNCH</td>
                <td bgcolor="blue">MENTOR MEET</td>
                <td bgcolor="blue">LUNCH</td>
                <td bgcolor="blue">LUNCH</td>
                <td bgcolor="blue">LUNCH</td>
            </tr>
            <tr align="centre">
                <th bgcolor="yellow">1-3</th>
                <td bgcolor="blue">GERMAN BASIC AND ADVANCED</td>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="blue">CREATIVE SKILLS FOR COMMUNICATION</td>
                <td bgcolor="blue">ALGEBRA AND NUMBER THEORY</td>
                <td bgcolor="blue">PYTHON PROGRAMMING</td>
            </tr>
            <tr align="centre">
                <th bgcolor="yellow">3-5</th>
                <td bgcolor="blue">OPERATING SYSTEM</td>
                <td bgcolor="blue">GERMAN BASIC AND ADVANCED</td>
                <td bgcolor="blue">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="blue">PYTHON PROGRAMMING</td>
                <td bgcolor="blue">FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="6" border="6">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT(FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19CS405</td>
                <td>OPERATING SYSTEM(OS)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19EN613C</td>
                <td>GERMAN BASIC AND ADVANCED(GBA)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19MA212</td>
                <td>ALGEBRA AND NUMBER THEORY(ANT)</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19EE404</td>
                <td>DIGITAL ELECTRONICS(DE)</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19AI301</td>
                <td>PYTHON PROGRAMMING(PP)</td>
            </tr>
            <tr>
                <td align="center">7.</td>
                <td align="center">19EY702</td>
                <td>CREATIVE SKILLS (cs)</td>
            </tr>
        </table>
    </body>
</html>

## OUTPUT


![Screenshot 2024-03-23 232220](https://github.com/harinisaravanan10/slot/assets/149035598/973bd1ab-8b45-4a99-831a-9908d10de985)


![Screenshot 2024-03-23 232231](https://github.com/harinisaravanan10/slot/assets/149035598/2e659f72-d867-4087-9488-e8344e5fc207)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
