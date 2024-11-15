# Ex03 Time Table
## Date:12.11.2024

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
    <body>
        <img src="logo.png">
        <table border="1" cellspacing="15" cellpadding="2">
        <caption>Timetable -JANSI RANI A A (24900239)</caption>
        <tr bgcolor="yellow">
         <th>Day/Time</th>
         <th>Monday</th>
         <th>Tuesday</th>
         <th>Wednesday</th>
         <th>Thursday</th>
         <th>Frida</th>
         <th>Saturday</th>
         </tr>
         <tr>
            <td>8 to 10</td>
            <td>FREE SLOT</td>
            <td>PCE</td>
            <td>CMA</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>CE</td>
         </tr>
         <TR>
            <td>10 to 12</td>
            <td>FCP</td>
            <td>DE</td>
            <td>CE</td>
            <td>CMA</td>
            <td>FCP</td>
            <td>CDS</td>
         </tr>
         <TR>
            <td>12 to 1</td>
            <td colspan="6" align="center">LUNCH</td>
         </tr>
         <TR>
            <td>1 to 3</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>MENTOR MEET</td>
            <td>PCE</td>
            <td>DE</td>
            <td>FREE SLOT</td>
         </tr>
         <TR>
            <td>3 to 5</td>
            <td colspan="6" align="center">FREE SLOT</td>
         </tR>
         </table>
         
        <Table border="2" cellspacing="15" cellpadding="2">
         <caption>Timetable</caption>
         <tr bgcolor="Green">
         <th>S.No</th>
         <th>Subject  Code</th>
         <th>Subject Name</th>
    </tr>
    <TR>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamental Of Web Application Development(FWAD)</td>
    </tr>
    <TR>
        <td>2</td>
        <td>19EN612</td>
        <td>German Basic(GSR)</td>
    </tr>
    <TR>
        <td>3</td>
        <td>19PH206</td>
        <td>Physics For Information Technology(PHY)</td>
    </tr>
    <TR>
        <td>4</td>
        <td>19CY205</td>
        <td>Principles Of Chemistry In Engineering(CHE)</td>
    </tr>
    <TR>
        <td>5</td>
        <td>19MA201</td>
        <td>Calculus And Matrix Algebra(MAT)</td>
    </tr>
    <TR>
        <td>6</td>
        <td>19EY701</td>
        <td>Soft Skills(SS)</td>
    </TR>
    </Table>
    </body>
    </html>
```

## OUTPUT
![alt text](<Screenshot (10).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
