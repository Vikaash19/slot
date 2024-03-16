# Ex03 Time Table
## Date: 15/03/2024

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
        <title>My Time Table</title>
    </head>
    <body align="center">
        <img src="logo.png" height="100" width="800">
        <table bgcolor="Orange" border="4" cellspacing="3" cellpadding="5" width="200" height="100" align="center">
            <caption>SLOT TIME TABLE-VIKAASH K S(212223240179)</caption>
            <tr bgcolor="lime"><th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th> 
            <th>Saturday</th>   
            </tr>
            <tr>
            <td bgcolor="lime"><b>8-10</b></td>
            <td>PHY</td> 
            <td>ACP</td>
            <td>CHEM</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>    
            </tr>
            <tr>
            <td bgcolor="lime"><b>10-12</b></td>
            <td>FAI</td> 
            <td>FREE SLOT</td>
            <td>PQM</td>
            <td>FAI</td>
            <td>FREE SLOT</td>
            <td>IML</td>   
            </tr>
            <tr>
            <td bgcolor="lime"><b>12-1</b></td>
            <td colspan="6" align="center">LUNCH</td>  
            </tr>
            <tr>
                <td bgcolor="lime"><b>1-3</b></td>
                <td>IML</td> 
                <td>FWAD</td>
                <td>CS</td>
                <td>FWAD</td>
                <td>CHEM</td>
                <td>PQM</td>    
            </tr>
            <tr>
            <td bgcolor="lime"><b>3-5</b></td>
            <td colspan="2">FREE SLOT</td> 
            <td>FAI</td>
            <td colspan="3">FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table border="1" cellspacing="2" cellpadding="2" align="center">
            <tr>
                <th>S.no</th>
                <th>Subject Code</th>
                <th>Subject name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19PH214</td>
                <td>Physics for Quantum Computing(PHY)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19MA222</td>
                <td>Probability and Queueing Models(PQM)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EY702</td>
                <td>Creative Skills for Communication(CS)</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19CY205</td>
                <td>Principles of Chemistry in Engineering(CHEM)</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19AI410</td>
                <td>Introduction to Machine Learning(IML)</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19AI405</td>
                <td>Fundamentals of Artificial Intelligence(FAI)</td>
            </tr>
            <tr>
                <td>8</td>
                <td>19AI305</td>
                <td>Advanced C Programming(ACP)</td>
            </tr>
        </table>
    </body>
</html>
```
## OUTPUT
![alt text](<Exp 3 Web.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.