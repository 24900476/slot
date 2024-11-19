# Ex03 Time Table
## Date:18-11-2024

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

## PROGRAM!
```
<img src="logo.png" height="200" width="1000"
<html>
    <body>
     <table border="5" bgcolor="cyan" cellpadding="10"> 
    <caption align="center"> Time table </caption>
    <th colspan="7" align="center" bgcolor="red">SAVEETHA ENGINEERING COLLEGE </th>
     <tr>
        <th>S.NO</th>
        <th>MONDAY</th>
        <th>TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
     </tr>
     <tr> 
        <td> 1</td>
        <td> -</td>
        <td> -</td>
        <td> -</td>
        <td>  physics</td>
        <td> -</td>
        <td>  -</td>
     </tr>
     <tr>
        <td> 2</td> 
        <td> web application</td>
        <td>  maths</td>
        <td> web appplication</td>
        <td> computer archieture</td>
        <td>   python</td>
        <td>  maths</td>
     </tr>
     <tr>
        <td> 3 </td>
        <td> basic electronics</td>
        <td>  basic electronic</td>
        <td> mentor meeting</td>
        <td> python</td>
        <td> physics</td>
        <td> web application</td>
     </tr>
     </table>
    </body>
</html>
<table border="2">
    <tr bgcolor="red">
        <th>S.no</th>
        <th>Couse code</th>
        <th>Course name</th>
    </tr>
    <tr bgcolor="violet">
        <td>1</td>
        <td>19AI414</td>
        <td>FUNDAMENTALS OF WEB APPLICATION</td>
    </tr>
    <tr bgcolor="violet">
        <td>2</td>
        <td>19MA201</td>
        <td>CALCULUS AND MATRIX ALGEBRA </td>
    </tr>
    <tr bgcolor="violet">
        <td>3</td>
        <td>19EE305</td>
        <td>BASIC ELECTRICAL,ELECTRONIC AND MEASUREMENT ENGINEERING</td>
    </tr>
    <tr bgcolor="violet">
        <td>4</td>
        <td>19AI301</td>
        <td>PYTHON PROGRAMMING</td>
    </tr>
    <tr bgcolor="violet">
        <td>5</td>
        <td>19CS305</td>
        <td>COMPUTER ARCHITECTURE</td>
    </tr>
    <tr bgcolor="violet">
        <td>6</td>
        <td>19PH214</td>
        <td>PHYSICS FOR QUANTUM COMPUTING </td>
    </tr>
    
</table>

```
## OUTPUT:

![alt text](<Screenshot 2024-11-19 124041.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.