# Ex.07 Software Product Company Website
## Date:
26/10/23

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Learning Platform</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }

        nav {
            background-color: #555;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
            margin: 0 10px;
        }

        section {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>E-Learning Platform</h1>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="courses.html">Courses</a>
        <a href="contact.html">Contact</a>
    </nav>

    <section>
        <h2>Welcome to Our E-Learning Platform</h2>
        <p>Explore our courses and start learning today!</p>
    </section>

    <footer>
        <p>&copy; 2023 E-Learning Platform</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Courses - E-Learning Platform</title>
    <style>
        /* Styles are kept inline for simplicity, but in a real-world scenario, external stylesheets would be preferred */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }

        nav {
            background-color: #555;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
            margin: 0 10px;
        }

        section {
            padding: 20px;
        }

        .course-card {
            border: 1px solid #ddd;
            border-radius: 5px;
            overflow: hidden;
            margin-bottom: 20px;
            background-color: white;
            padding: 10px;
        }

        .course-card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        .course-card h3 {
            margin: 10px 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>E-Learning Platform</h1>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="courses.html">Courses</a>
        <a href="contact.html">Contact</a>
    </nav>

    <section>
        <h2>Available Courses</h2>

        <div class="course-card">
            <img src="course.jpg" alt="Course 1" style="width: 400px; height: 700px;">
        </div>
        
            <h3>Introduction to HTML</h3>
            <p>Learn the basics of HTML.</p>
        </div>

        <div class="course-card">
            <img src="course1.png" alt="Course 2" style="width: 500px; height: 500px;">
        </div>
            <h3>CSS Fundamentals</h3>
            <p>Explore the fundamentals of CSS.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 E-Learning Platform</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - E-Learning Platform</title>
    <style>
        /* Styles are kept inline for simplicity, but in a real-world scenario, external stylesheets would be preferred */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }

        nav {
            background-color: #555;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
            margin: 0 10px;
        }

        section {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>E-Learning Platform</h1>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="courses.html">Courses</a>
        <a href="contact.html">Contact</a>
    </nav>

    <section>
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to reach out to us:</p>
        <p>Email: info@example.com</p>
        <p>Phone: +1 234 567 890</p>
    </section>

    <footer>
        <p>&copy; 2023 E-Learning Platform</p>
    </footer>

</body>
</html>




## OUTPUT:
![Screenshot (9)](https://github.com/kavisree86/softweb/assets/145759687/2321107c-e6c4-4115-b236-1fe004174377)
![Screenshot (10)](https://github.com/kavisree86/softweb/assets/145759687/ad39261c-a243-4d8b-b08e-069f61d5011a)
![Screenshot (11)](https://github.com/kavisree86/softweb/assets/145759687/580696fe-9a0a-4263-b6a8-d87f8cc6c3a2)
![Screenshot (12)](https://github.com/kavisree86/softweb/assets/145759687/df9aa595-65a9-4d76-8c92-4603e8f0d94a)





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
