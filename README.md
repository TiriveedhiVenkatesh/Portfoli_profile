<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tiriveedhi Sai Venkatesh - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .hero {
            height: 100vh;
            background: url('background.jpg') no-repeat center center/cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
        }
        .hero h1 {
            font-size: 3em;
            margin: 0;
        }
        .hero p {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .profile-photo {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid #fff;
            margin-top: 20px;
        }
        nav ul {
            padding: 0;
            list-style: none;
            text-align: center;
            background: #444;
            margin: 0;
        }
        nav ul li {
            display: inline;
            padding: 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px 0;
        }
        section {
            background: #fff;
            padding: 20px;
            margin-top: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
        }
        ul {
            list-style-type: square;
            padding-left: 20px;
        }
        a {
            color: #0077cc;
        }
    </style>
</head>
<body>

<header class="hero">
    <img src="profile_photo.jpg" alt="Profile Photo" class="profile-photo">
    <h1>Tiriveedhi Sai Venkatesh</h1>
    <p>Boomi Integration Developer</p>
</header>

<nav>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<div class="container">
    <section id="about">
        <h2>About Me</h2>
        <p>Having professional experience as an Boomi Technical Developer. experience of Working with different types of connectors like NetSuite, Salesforce ,WSS, Http client, Onetrust, Webhost, Snowflake, Anaplan, Database, Google sheet and drive, Local Disk etc and solving complex problems. I have experience in Oracle NetSuite, Html, SQL, PL/SQL, XML, JSON.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>SQL</li>
            <li>PL/SQL</li>
            <li>XML</li>
            <li>JSON</li>
            <li>Teamwork</li>
            <li>Communication</li>
        </ul>
    </section>

    <section id="experience">
        <h2>Work Experience</h2>
        <table border="1" cellpadding="10" cellspacing="0" style="width:100%; border-collapse: collapse; background-color: #fff;">
            <thead style="background-color: #ddd;">
                <tr>
                    <th>Role</th>
                    <th>Company</th>
                    <th>Duration</th>
                    <th>Responsibilities</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Boomi Integration Developer</td>
                    <td>Capgemini</td>
                    <td>2.6 years</td>
                    <td>
                        <ul>
                            <li>Developed and maintained integration solutions using Boomi</li>
                            <li>Worked with connectors like NetSuite, Salesforce, WSS, Http client, Onetrust, Webhost, Snowflake, Anaplan, Database, Google Sheets and Drive, Local Disk</li>
                            <li>Solved complex problems and optimized integration processes</li>
                        </ul>
                    </td>
                </tr>
            </tbody>
        </table>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p><strong>B.Tech in Computer Science</strong><br>Ramachandra College of Engineering, 2018–2022</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <h3>IoT Based Agriculture</h3>
        <p>An IoT-based project aimed at improving agricultural practices through technology.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: venkatesh@gmaul.com</p>
        <p>Phone: 123456322434</p>
        <p>LinkedIn: <a href="#">linkedin.com/in/venkatesh</a></p>
        <p>GitHub: <a href="#">github.com/venkatesh</a></p>
    </section>
</div>

</body>
</html>
