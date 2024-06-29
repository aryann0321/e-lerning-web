# e-lerning-web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Learning Platform</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        
        header {
            background-color: #f0f0f0;
            padding: 20px;
            text-align: center;
        }
        
        main {
            display: flex;
            flex-direction: row;
            align-items: flex-start;
            justify-content: space-between;
        }
        
        section {
            background-color: #ffffff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 48%;
            margin-right: 2%;
        }
        
        #courses-section {
            width: 48%;
            margin-left: 2%;
        }
        
        #courses-ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        
        #courses-ul li {
            padding: 10px;
            border-bottom: 1px solid #ccc;
        }
        
        #courses-ul li:last-child {
            border-bottom: none;
        }
        
        #course-details {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
        }
        
        #course-details h2 {
            margin-top: 0;
        }
        
        #course-details p {
            margin-bottom: 0;
        }
        
        #enroll-btn {
            background-color: #4CAF50;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
        
        #enroll-btn:hover {
            background-color: #3e8e41;
        }
    </style>
</head>
<body>
    <header>
        <h1>E-Learning Platform</h1>
    </header>
    <main>
        <section id="courses-section">
            <h2>Courses</h2>
            <ul id="courses-ul">
                <li>
                    <div id="course-details">
                        <h2>Introduction to HTML/CSS</h2>
                        <p>Learn the basics of HTML and CSS to create beautiful websites.</p>
                    </div>
                    <button id="enroll-btn">Enroll</button>
                </li>
                <li>
                    <div id="course-details">
                        <h2>JavaScript Fundamentals</h2>
                        <p>Master the fundamentals of JavaScript programming language.</p>
                    </div>
                    <button id="enroll-btn">Enroll</button>
                </li>
                <li>
                    <div id="course-details">
                        <h2>Python for Data Science</h2>
                        <p>Learn Python programming language for data science and machine learning.</p>
                    </div>
                    <button id="enroll-btn">Enroll</button>
                </li>
            </ul>
        </section>
        <section id="enrolled-courses-section">
            <h2>Enrolled Courses</h2>
            <ul id="enrolled-courses-ul">
                <!-- enrolled courses will be displayed here -->
            </ul>
        </section>
    </main>
    <script>
        const enrollBtns = document.querySelector
