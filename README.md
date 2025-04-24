# Ex03 Time Table
## Date:24/04/2025

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
        
    </head>
    <body>
        
        <center>
            
            
            <img src="/static/logo.png" height="100" width="550">
            
            <h1>SLOT TIMETABLE </h1>

            <br><h2> Thanushree M       (reg no:212224240169)</h2>
            <hr color="black">
        </center>
        
        
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="pink">
            <tr align="center">
                <th bgcolor="lightblue">DAY/TIME</th>
                <th bgcolor="lightblue">8:00-10:00</th>
                <th bgcolor="lightblue">10:00-12:00</th>
                <th bgcolor="lightblue">12:00-1:00</th>
                <th bgcolor="lightblue">1:00-3:00</th>
                <th bgcolor="lightblue">3:00-5:00</th>
            </tr>
            <tr align="center">
                <th bgcolor="lightblue">MONDAY</th>
                <td>FREE SLOT</td>
                <td>OS</td>
                <td>LUNCH</td>
                <td>C PROGRAMMING</td>
                <td>FREE SLOT</td>
                
            </tr>
            <tr align="center">
                <th bgcolor="lightblue">TUESDAY</th>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>LUNCH </td>
                <td>PHYSICS</td>
                <td>FREE SLOT</td>
                
                
            </tr>
            <tr align="center">
                <th bgcolor="lightblue">WEDNESDAY</th>
                <td>FREE SLOT</td>
                <td>OS</td>
                <td>LUNCH</td>
                <td>MENTOR MEET</td>
                <td>WEB</td>
            </tr>
            <tr align="center">
                <TH bgcolor="lightblue">THURSDAY</TH>
                <TD>PHYSICS</TD>
                <TD>C PROGRAMMING</TD>
                <TD>LUNCH</TD>
                <TD>STATICS</TD>
                <TD>ML</TD>
            </tr>
            <TR align="center">
                <TH bgcolor="lightblue">FRIDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>WEB</TD>
                <TD>LUNCH</TD>
                <TD>ML</TD>
                <td>FREE SLOT</td>

            </TR>
            <TR align="center">
                <TH bgcolor="lightblue">SATURDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>FREE SLOT</TD>
                <TD>LUNCH</TD>
                <TD>STATICS</TD>
                <TD>FREE SLOT</TD>

            </TR>
        </table>
        <BR>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.NO : </th>
                <TH>SUBJECT CODE :</TH>
                <TH>SUBJECT NAME :</TH>
            </tr>
            <TR align="center">
                <td>1.</td>
                <td>19AI414</td>
                <TD>FUNDAMENTALS OF WEB APPLICATION</TD>
            </TR>
            <TR align="center">
                <TD>2.</TD>
                <TD>19AI304</TD>
                <TD>FUNDAMENTALS OF C PROGRAMMING</TD>
            </TR>
            <TR align="center">
                <TD>3.</TD>
                <TD>19AI410</TD>
                <TD>INTRODUCTION TO MACHINE LEARNING</TD>
            </TR>
            <TR align="center">
                <TD>4.</TD>
                <TD>19MA211</TD>
                <TD>STATICS AND NUMERICAL METHODS</TD>
            </TR>
            <TR align="center">
                <TD>5.</TD>
                <TD>19CS405</TD>
                <TD>OPERATING SYSTEM</TD>
            </TR>
            <TR align="center">
                <TD>6.</TD>
                <TD>19PH214</TD>
                <TD>PHYSICS FOR QUANTUM COMPUTING</TD>
            </TR>
        </table>
        
    </body>
</html>
```

## OUTPUT
![Screenshot 2025-04-24 203440](https://github.com/user-attachments/assets/7766f0d2-03a2-492f-aa56-175e62607021)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
