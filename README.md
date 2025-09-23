# Ex03 Time Table
# Date:21-09-2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Timetable - Shankar </title>
</head>
<body>
<center>
<img src="/static/Screenshot 2025-09-21 164826.png" height="100" width="540">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f5f8fa;
            color: #333;
            padding: 20px;
        }

        h1 {
            text-align: center;
            color: #005b96;
        }

        table {
            width: 90%;
            margin: 20px auto;
            border-collapse: collapse;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        th, td {
            padding: 12px;
            border: 1px solid #ccc;
            text-align: center;
        }

        th {
            background-color: #ffcc00;
            color: #000;
        }

        tr:nth-child(even) {
            background-color: #e6f7ff;
        }

        .lunch-row td {
            background-color: #b3ecff;
            font-weight: bold;
            letter-spacing: 2px;
        }

        .subject-table {
            margin-top: 40px;
        }

        .subject-table th {
            background-color: #0073e6;
            color: white;
        }

        .subject-table tr:nth-child(even) {
            background-color: #f0f8ff;
        }

        td:hover {
            background-color: #d1e0e0;
            transition: 0.3s;
        }
    </style>
</head>
<body>

    <h1>Slot Time Table - Shankar SB (25017085)</h1>

    <table>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>WEB APPLICATIONS</td>
            <td>ENGLISH</td>
            <td>WEB APPLICATIONS</td>
            <td>ENGLISH</td>
            <td>C PROGRAMMING</td>
            <td>ENGLISH</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>FREE SLOT</td>
            <td>ENGLISH</td>
            <td>WEB APPLICATIONS</td>
            <td>C PROGRAMMING</td>
            <td>WEB APPLICATIONS</td>
            <td>WEB APPLICATIONS</td>
        </tr>
        <tr class="lunch-row">
            <td>12-1</td>
            <td colspan="5">LUNCH</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td>C PROGRAMMING</td>
            <td>FREE SLOT</td>
            <td>MENTOR MEET</td>
            <td>ENGLISH</td>
            <td>FREE SLOT</td>
            <td>ENGLISH</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>C PROGRAMMING</td>
            <td>C PROGRAMMING</td>
            <td>FREE SLOT></td>
            <td>FREE SLOT></td>
        </tr>
    </table>

    <table class="subject-table">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EN101</td>
            <td>Commutative Englisj</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19AI304</td>
            <td>Fundamentals of C Programming</td>
        </tr>
    </table>

</body>
</html>

```
# OUTPUT

<img width="1918" height="971" alt="Screenshot 2025-09-21 194145" src="https://github.com/user-attachments/assets/7dcb8b61-d8cf-4dee-9838-b7609dbdfc6a" />



# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
