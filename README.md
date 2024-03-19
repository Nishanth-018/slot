# Ex03 Time Table
## Date:14/03/2024

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
        <title>
            My Time Table
        </title>
    </head>

        <body>
            <center><img src="logo.png" height="200" width="1200"></center>
            <center><h1>SLOT TIME TABLE-NISHANTH.J(23007929)</h1></center>
            <center> <table bgcolour="violet" border="10" cellspacing="10" cellpadding="10"  width="75" height="100">
             <tr>
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">Monday</th>
                <th bgcolor="yellow">Tuesday</th>
                <th bgcolor="yellow">Wednesday</th>
                <th bgcolor="yellow">Thursday</th>
                <th bgcolor="yellow">Friday</th>
                <th bgcolor="yellow">Saturday</th>
             </tr> 
             
             <tr align="center">
                <th bgcolor="red">8-10</th>
                <td bgcolor="cyan">Free slot</td>
                <td bgcolor="cyan">Free slot</td>
                <td bgcolor="cyan">DS</td>
                <td bgcolor="cyan">DE</td>
                <td bgcolor="cyan">Web</td>
                <td bgcolor="cyan">Free Slot</td>
            </tr>
            <tr align="center">
                <th bgcolor="red">10-12</th>
                <td bgcolor="cyan">DE</td>
                <td bgcolor="cyan">OS</td>
                <td bgcolor="cyan">Physics</td>
                <td bgcolor="cyan">OS</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">Free Slot</td>
            </tr>
            <tr align="center">
                <th bgcolor="red">1-3</th>
                <td bgcolor="cyan">Skills</td>
                <td bgcolor="cyan">Web</td>
                <td bgcolor="cyan">Maths</td>
                <td bgcolor="cyan">Web</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">Maths</td>
            </tr>
            <tr align="center">
                <th bgcolor="red">3-5</th>
                <td bgcolor="cyan">DE</td>
                <td bgcolor="cyan">Physics</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">Free Slot</td>
                <td bgcolor="cyan">Free Slot</td>
            </tr>

     </table>
     <hr>
     <table border="10" cellspacing="10" cellpadding="10" height="100" width="500">
         <tr>
             <th>S:No</th>
             <th>Sub Code</th>
             <th>Sun Name</th>
         </tr>
         <tr>
             <td>1.</td>
             <td>19AI403</td>
             <td>Introduction too Data Science(DS)</td>
         </tr>
         <tr>
             <td>2.</td>
             <td>19AI414</td>
             <td>Fundamental of Web Development(Web)</td>
         </tr>
         <tr>
             <td>3.</td>
             <td>19CS405</td>
             <td>Operating System(OS)</td>
         </tr>
         <tr>
             <td>4.</td>
             <td>19PH214</td>
             <td>Physics for Quantum Computing(Physics)</td>
         </tr>
         <tr>
             <td>5.</td>
             <td>19EY702</td>
             <td>Creative Skills for Communication(Skills)</td>
         </tr>
         <tr>
            <td>6.</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19MA211</td>
            <td>Statistics and Numerical Methods(Maths) </td>
        </tr>
    </table>
    <hr>

</body>
</html>
 
    </center>

        </body>
</html>
```


## OUTPUT
![Screenshot 2024-03-19 142733](https://github.com/Nishanth-018/slot/assets/149347651/024ab982-4065-4d98-98f0-d48d6d6eb27b)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
