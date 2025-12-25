# Ex09 Event Registration Web Application
## Date: 24-12-2025
## Ref No: 25018897

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
~~~

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Online Python Course Registration</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }

        /* Navbar */
        header {
            background-color: #0d6efd;
            padding: 15px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: white;
        }

        header h1 {
            margin: 0;
            font-size: 22px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 16px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 70px 20px;
            background-color: #e7f1ff;
        }

        .hero h2 {
            font-size: 36px;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 25px;
        }

        .hero button {
            padding: 12px 25px;
            font-size: 16px;
            border: none;
            background-color: #ffc107;
            cursor: pointer;
            border-radius: 5px;
        }

        .hero button:hover {
            background-color: #e0a800;
        }

        /* Highlights */
        .highlights {
            display: flex;
            justify-content: space-around;
            padding: 50px 20px;
            flex-wrap: wrap;
        }

        .card {
            background-color: white;
            width: 220px;
            margin: 10px;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .card h3 {
            margin-bottom: 10px;
            color: #0d6efd;
        }

        /* Course Section */
        .course {
            padding: 50px 20px;
            background-color: white;
            text-align: center;
        }

        .course h2 {
            margin-bottom: 20px;
        }

        .course ul {
            list-style: none;
            padding: 0;
            font-size: 16px;
        }

        .course li {
            margin: 10px 0;
        }

        /* Registration Form */
        .register {
            padding: 50px 20px;
            background-color: #e7f1ff;
            text-align: center;
        }

        form {
            max-width: 400px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        input, select {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        form button {
            width: 100%;
            padding: 12px;
            background-color: #0d6efd;
            color: white;
            border: none;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }

        form button:hover {
            background-color: #084298;
        }

        /* Footer */
        footer {
            background-color: #0d6efd;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .highlights {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Python Course</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Courses</a>
        <a href="#">Syllabus</a>
        <a href="#register">Register</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Learn Python from Scratch</h2>
    <p>Beginner Friendly • Certificate • Online Classes</p>
    <button>Register Now</button>
</section>

<section class="highlights">
    <div class="card">
        <h3>Duration</h3>
        <p>8 Weeks</p>
    </div>
    <div class="card">
        <h3>Level</h3>
        <p>Beginner</p>
    </div>
    <div class="card">
        <h3>Mode</h3>
        <p>Online</p>
    </div>
    <div class="card">
        <h3>Certificate</h3>
        <p>Yes</p>
    </div>
</section>

<section class="course">
    <h2>Course Syllabus</h2>
    <ul>
        <li>Introduction to Python</li>
        <li>Variables and Data Types</li>
        <li>Conditions and Loops</li>
        <li>Functions and Modules</li>
        <li>File Handling</li>
        <li>Mini Project</li>
    </ul>
</section>

<section class="register" id="register">
    <h2>Course Registration</h2>
    <form>
        <input type="text" placeholder="Full Name" required>
        <input type="email" placeholder="Email Address" required>
        <input type="tel" placeholder="Phone Number" required>
        <input type="text" placeholder="College / School Name">
        <select required>
            <option value="">Select Level</option>
            <option>Beginner</option>
            <option>Intermediate</option>
        </select>
        <button type="submit">Enroll Now</button>
    </form>
</section>

<footer>
    <p>© 2025 Online Python Course | All Rights Reserved</p>
</footer>

</body>
</html>


~~~


## OUTPUT:
![alt text](<Screenshot 2025-12-25 131828.png>)


![alt text](<Screenshot 2025-12-25 131852.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
