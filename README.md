# Ex03 Time Table
## Date:19/11/2024

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
        <title align="center">SLOT TIMETABLE</title>
    </head>
    <body>
        <center>
            <img src="C:\Users\admin\slot\logo.png" height="100" width="870">
        </center>
        <br>        
        <center>
            <b><font color="black" size="5">SLOT TIMETABLE M.Avanthika(24901279)</font></b>
        </center>
            <table align="center" border="2" cellpadding="4" bordercolor=" black" bgcolor="#e9e1fd">
                <tr>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">Day/Time</font></th>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">8:00 to 10:00</font></th>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">10:00 to 12:00</font></th>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">12:00 to 1:00</font></th>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">1:00 to 3:00</font></th>
                    <th bgcolor="#FFFFE0"><font color="black"  size="5">3:00 to 5:00</font></th>
                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black"  size="5">Monday</font></td>
                    <td align="center" rowspan="3"><font color="black" size="5">Free Hour </font></td>
                    <td align="center "><font color="black"  size="5">EMPD</font></td>
                    <td align="center" rowspan="6"><font color="black"  size="5"> LUNCH HOUR</font></td>
                    <td align="center"><font color="black"  size="5">BEEE</font></td>
                    <td align="center" rowspan="2"><font color="black" size="5">Free Hour</font></td>
                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black"  size="5">Tuesday</font></td>
                    <td align="center "><font color="black"  size="5">PQC</font></td>
                    <td align="center"><font color="black"  size="5">FWAD</font></td>
                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black"  size="5">Wednesday</font></td>
                    <td align="center "><font color="black"  size="5">CMA</font></td>
                    <td align="center"><font color="black"  size="5">Mentor Meet</font></td>
                    <td align="center"><font color="black"  size="5">BEEE</font></td>
                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black"  size="5">Thursday</font></td>
                    <td align="center"><font color="black"  size="5">FOC</font></td>
                    <td align="center "><font color="black"  size="5">Free Hour</font></td>
                    <td align="center"><font color="black"  size="5">FWAD</font></td>
                    <td align="center" rowspan="3"><font color="black" size="5">Free Hour</font></td>
                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black"  size="5">Friday</font></td>
                    <td align="center"><font color="black"  size="5">PQC</font></td>
                    <td align="center "><font color="black"  size="5">CDS</font></td>
                    <td align="center"><font color="black"  size="5">CMA</font></td>
                </tr>
                <tr>
                    <td align="center" bgcolor="#FFFFE0"><font color="black" size="5">Saturday</font></td>
                    <td align="center"><font color="black"  size="5">EMPD</font></td>
                    <td align="center "><font color="black" size="5">FWAD</font></td>
                    <td align="center"><font color="black"  size="5">FOC</font></td>
                </tr>
            </table>
            <br>
            <table align="center" border="1" cellspacing="0" cellpadding="4" width="850">
                <thead>
                  <tr>
                    <th><font color="black"  size="5">S. No.</font></th>
                    <th><font color="black"  size="5">Subject Code</font></th>
                    <th><font color="black"  size="5">Subject Name</font></th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td align="center"><font size="5">1</font></td>
                    <td align="center">19AI414<font size="5"></font></td>
                    <td align="center">Fundamentals of Web Application Development (FWAD)<font size="5"></font></td>
                  </tr>
                  <tr>
                   <td align="center">2<font size="5"></font></td>
                   <td align="center">19AI304<font size="5"></font></td>
                   <td align="center">Fundamentals of C Programming<font size="5"></font></td>                    
                  </tr>
                  <tr>
                    <td align="center">3<font size="5"></font></td>
                    <td align="center">19AI303<font size="5"></font></td>
                    <td align="center">Engineering Mechanics And Product Development <font size="5"></font></td>
                  </tr>
                  <tr>
                    <td align="center">4<font size="5"></font></td>
                    <td align="center">19EE305<font size="5"></font></td>
                    <td align="center">Basic Electrical,Electronics and measurement Engineering<font size="5"></font></td>
                  </tr>
                  <tr>
                    <td align="center">5<font size="5"></font></td>
                    <td align="center">SH3214<font size="5"></font></td>
                    <td align="center">Physics foe Quantum Computing<font size="5"></font></td>
                  </tr>
                  <tr>
                    <td align="center">6<font size="5"></font></td>>
                    <td align="center">19AI201<font size="5"></font></td>
                    <td align="center">Calculus and Matrix Algebra<font size="5"></font></td>
                  </tr>
                  <tr>
                    <td align="center">7<font size="5"></font></td>
                    <td align="center">19EY708<font size="5"></font></td>
                    <td align="center">Career Development Skills<font size="5"></font></td>
                  </tr>
                </tbody>
              </table>
    </body>
</html>
```

## OUTPUT

![Screenshot 2024-12-14 113209](https://github.com/user-attachments/assets/a02d5e99-affa-49e9-88ec-7cd4dcf995b0)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
