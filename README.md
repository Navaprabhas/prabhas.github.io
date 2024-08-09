<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .section {
            padding: 2rem 0;
        }
        .section h2 {
            text-align: center;
            margin-bottom: 1rem;
        }
        .projects, .contact {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .project, .contact-item {
            background: #fff;
            padding: 1rem;
            margin: 1rem;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 45%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Student Portfolio</h1>
    </header>
    <div class="container">
        <section class="section about">
            <h2>About Me</h2>
            <p>Hello! I am a student passionate about web development. I enjoy creating websites and learning new technologies.</p>
        </section>
        <section class="section projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1</h3>
                <p>Description of project 1.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>Description of project 2.</p>
            </div>
        </section>
        <section class="section contact">
            <h2>Contact</h2>
            <div class="contact-item">
                <h3>Email</h3>
                <p>student@example.com</p>
            </div>
            <div class="contact-item">
                <h3>Phone</h3>
                <p>+123 456 7890</p>
            </div>
        </section>
    </div>
</body>
</html>
