# Ex08 CAMU Schedule using Bootstrap
## Date:28/5/26

## AIM:
To design a responsive and visually appealing CAMU Schedule using Bootstrap.

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Add the Bootstrap CDN link inside the ```<head>``` section.

### Step 5:
Insert a table element with Bootstrap table classes.

### Step 6:
Construct the complete table.

### Step 7:
Add a header/footer displaying copyright information.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
    <title>CAMU Schedule</title>

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">

    <!-- jQuery -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>

    <!-- Bootstrap JS -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

    <style>
        body{
            background-color:#f5f5f5;
        }
        h1{
            text-align:center;
            color:#003366;
            margin-bottom:20px;
        }
        .table{
            background-color:white;
        }
    </style>
</head>

<body>

<div class="container">

    <h1>CAMU Schedule</h1>

    <div class="table-responsive">

        <table class="table table-bordered table-striped table-hover text-center">

            <thead class="bg-primary">
                <tr>
                    <th>Day/Time</th>
                    <th>Period 1<br>8:00-9:00</th>
                    <th>Period 2<br>9:00-10:00</th>
                    <th>Period 3<br>10:00-11:00</th>
                    <th>Period 4<br>11:00-12:00</th>
                    <th>Period 5<br>1:00-2:00</th>
                    <th>Period 6<br>2:00-3:00</th>
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>Monday</td>
                    <td>Adv C</td>
                    <td>Adv C</td>
                    <td>Computer Networks</td>
                    <td>Computer Networks</td>
                    <td>Free Sloth</td>
                    <td>Free Sloth</td>
                </tr>

                <tr>
                    <td>Tuesday</td>
                    <td>Web</td>
                    <td>Web</td>
                    <td>Python</td>
                    <td>Python</td>
                    <td>Adv C</td>
                    <td>Adv C</td>
                </tr>

                <tr>
                    <td>Wednesday</td>
                    <td>Web</td>
                    <td>Web</td>
                    <td>Free Sloth</td>
                    <td>Free Sloth</td>
                    <td>Mentor meet</td>
                    <td>Mentor meet</td>
                </tr>

                <tr>
                    <td>Thursday</td>
                    <td>Adv c</td>
                    <td>Adv C</td>
                    <td>Python</td>
                    <td>Python</td>
                    <td>Computer networks</td>
                    <td>Computer networks</td>
                </tr>

                <tr>
                    <td>Friday</td>
                    <td>Web</td>
                    <td>Web</td>
                    <td>Python</td>
                    <td>Python</td>
                    <td>Adv C</td>
                    <td>Adv C</td>
                </tr>

                <tr>
                    <td>Saturday</td>
                    <td>Web</td>
                    <td>Web</td>
                    <td>Adv C</td>
                    <td>Adv C</td>
                    <td>Python</td>
                    <td>Python</td>
                </tr>
            </tbody>

        </table>

    </div>

</div>

</body>
</html>
```

## OUTPUT:
<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/9e80bf27-21ec-405d-81f0-ab3c32f0ad1d" />


## RESULT:
A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.
