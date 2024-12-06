# Ex03 Time Table
# Date:21/10/2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using 'table' tag in html.

## STEP 4
Add header row using 'th' tag.

## STEP 5
Add your timetable using 'td' tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM

```python

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIME TABLE</title>
    <center>
    <img src="/static/logo.png" height="100" width="1000"> </img>
    
    <h3 style="font-size: x-large;"> SLOT TIME TABLE - KISHORE.S(24900594)</h3>    
    </center>
    </head>    
    <style>
        table{
            border-collapse: collapse;
            margin: 20px  auto;
            background-color: rgb(255, 255, 255);
            box-shadow: 0;
        }
        .vertical-align{
            font-size: larger;
            writing-mode:vertical-lr
        }
    </style>
    <center>
<table border="1" width="50%" height="25%">
    <tr  style="background-color: rgb(0, 255, 149);">
        <th>Day/Time</th>
        <th> 8-10 </th>
        <th> 10-12 </th>
        <th> 12-1 </th>
        <th> 1-3 </th>
        <th> 3-5 </th>
    </tr>
    <tr> 
        <th style="background-color: yellow;"></thstyle>MONDAY</th>
        <td>FREE</td> 
        <td> WEB </td>
        <td class="no-border vertical-align" rowspan="6">LUNCH  TIME</td>
        <td>FREE</td>
        <td>FREE</td>
    </tr>
    <tr>
        <th style="background-color: yellow;"></thstyle>TUESDAY</th>
        <td> ENGLISH </td>
        <td>FREE</td>
    
        <td> PYTHON </td>
        <td>FREE</td>
    </tr>
    <tr>
        <th style="background-color: yellow;"></thstyle>WEDNESDAY</th>
        <td> PYTHON </td>
        <td>FREE</td> 

        <td> SCOFT</td>
        <td>FREE</td>
    </tr>  
    <tr>
        <th style="background-color: yellow;"></thstyle>THURSDAY</th>
        <td> PYSICS </td>
        <td> PYTHON </td>

        <td> WEB </td>
        <td>FREE</td>
    </tr>
    <tr>
        <th style="background-color: yellow;"></thstyle>FRIDAY</th>
        <td> ENGLISH </td>
        <td> CD SKILLS </td>

        <td> PHYSICS </td>
        <td>FREE</td>
    </tr>
    <tr>
        <th style="background-color: yellow;"></thstyle>SATURDAY</th>
        <td>FREE</td>
        <td> PYTHON </td>

        <td>FREE</td>
        <td> WEB </td>


    </tr>    
</table>
</center>
</head>
<body>
<table border="4px" width="300" height="400" >
        <tr style="background-color: rgb(251, 159, 107);">
            <th> S.NO </th>
            <th> SUBJECT NAME </th>
            <th> SUBJECT CODE </th>
        </tr>
        <tr style="background-color: rgb(219, 225, 225);">
            <th> 1. </th>
            <td> Fundamentals of web applications </td>
            <td> 19AI401 </td>
        </tr>
        <tr style="background-color: rgb(219,225,225);">
            <th> 2. </th>
            <td> Python and linear algebra </td>
            <td> 19AI301C </td>
        </tr>
        <tr style="background-color: rgb(219,225,225);">
            <th> 3. </th>
            <td> Physics for Quantum computing </td>
            <td> SH3214 </td>
        </tr>
        <tr style="background-color: rgb(219,225,225);">
            <th> 4. </th>
            <td> Communicative English</td>
            <td> 19EN101 </td>
        </tr>
        <tr style="background-color: rgb(219,225,225);">
            <th> 5. </th>
            <td> Career Development Skills</td>
            <td> 19EY708 </td>
         </tr>
</table>
</body>
</html>

```
# OUTPUT
![Screenshot 2024-12-06 221046](https://github.com/user-attachments/assets/67578ca8-6b57-473a-8583-714d6e995344)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
