# Ex03 Time Table
# Date:27-09-2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using ``<th>`` tag.

## STEP 5
Add your timetable using ``<td>`` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet"href="style.css">
    <title>TIME TABLE</title>
    
</head>
<body>
<div class="Logo">
    <center>
    <img src="saveetha.jpg" alt="Logo">
     <h1>TIMETABLE</h1>
    </center>
    <table>
        <thead>
            <tr>
                <th>day/time</th>
                <th>8.00-10.00</th>
                <th>10.00-12.00</th>
                <th>12.00-1.00</th>
                <th>1.00-3.00</th>
                <th>3.00-5.00</th>
          </tr>
        </thead>
        <tbody>
            <tr>
                <th>MONDAY</th>
                <td>-</td>
                <td>-</td>
                <td>Lunch</td>
                <td>web</td>
                <td>-</td>
            </tr>
            <tr>
                <th>TUESDAY</th>
                <td>CE</td>
                <td>-</td>
                <td>Lunch</td>
                <td>python</td>
                <td>-</td>
            </tr>
            <tr>
                <th>WEDNESDAY</th>
                <td>-</td>
                <td>-</td>
                <td>Lunch</td>
                <td>Mentor class</td>
                <td>chemistry</td>
            </tr>
            <tr>
                <th>THURSDAY</th>
                <td>-</td>
                <td>python</td>
                <td>Lunch</td>
                <td>CDS</td>
                <td>Chemistry</td>
            </tr>
            <tr>
                <th>FRIDAY</th>
                <td>CE</td>
                <td>web</td>
                <td>Lunch</td>
                <td>python</td>
                <td>-</td>
            </tr>
            <tr>
                <th>SATURDAY</th>
                <td>-</td>
                <td>web</td>
                <td>Lunch</td>
                <td>python</td>
                <td>-</td>
            </tr>
        </tbody>
        </table>
        <Subject Table>
        <center>
        <h2>Subject Details</h2>
        </center>
        <table>
            <thead>
            <tr>
                <th> S.NO</th>
                <th> Subject Code</th>
                <th> Subject Name</th>
            </tr>
            </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>19Al301C</td>
                <td>Python and linear algebra</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19Al414</td>
                <td>Fundamental of web application</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19CY205</td>
                <td>Principle of chemistry</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EY708</td>
                <td>Career Development skills</td>
            </tr>
        </tbody>
    </table>
</div>
</center>   
</body>
</html>
---
#style.css          
body{
    height:100%;
    margin:20px;
    display:flex;
    text-align:center;
    justify-content: center;
    align-items: center;
}
.Logo{
    width:50%;
    height:100%;
    align-items: center;
    justify-content: center;
    padding: 20px;
}
table{
    width:100%;
    height:100%;
    border-collapse:collapse;
    padding:20px;   
}
th,td{
    border:1px solid #1b1a1afa;
    padding:10px;
    text-align:center;   
}

th{
    background-color: rgb(200, 135, 49);
}

td{
    background-color:antiquewhite;
}

.Subject Table th {
    background-color:rgb(49, 185, 200);
}
.Subject Table td {
    background-color: aquamarine;
}
---
```         
# OUTPUT
![Screenshot (46)](https://github.com/user-attachments/assets/d2b6a3dd-3088-498e-a8c2-6d6993b8a377)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
