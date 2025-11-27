<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Attendance System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Navigation bar styling */
        .navbar {
            background-color: #333;
            overflow: hidden;
        }

        .navbar a {
            float: left;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 17px;
        }

        .navbar a:hover {
            background-color: #575757;
        }

        .navbar a.active {
            background-color: #04AA6D;
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <div class="navbar">
        <a class="active" href="home.html">Home</a>
        <a href="attendance_list.html">Attendance List</a>
        <a href="add_student.html">Add Student</a>
        <a href="reports.html">Reports</a>
        <a href="logout.html">Logout</a>
    </div>

    <h1>Welcome to the Student Attendance System</h1>

</body>
</html>
