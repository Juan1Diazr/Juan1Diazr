## Juan1Diazr 👋

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 
    <title>Juan Díaz - Portafolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #6e6d6d; /* Gris de fondo */
            color: #EAEAEA; /* Texto claro */
        }
        header {
            background-color: #000; /* Negro */
            color: white;
            text-align: center;
            padding: 2em;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 0.5em 0;
            font-size: 1.2em;
            opacity: 0.9;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 2em;
        }
        section {
            margin-bottom: 2em;
        }
        h2 {
            color: white;
            border-bottom: 2px solid white;
            padding-bottom: 0.3em;
        }
        .about {
            display: flex;
            align-items: center;
            flex-wrap: wrap;
            gap: 2em;
        }
        .about img {
            max-width: 300px;
            border-radius: 12px;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
        }
        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 1em;
        }
        .project {
            background-color: #1E1E1E; /* Negro suave */
            padding: 1em;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.5);
            flex: 1 1 300px;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }
        .project:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(255, 255, 255, 0.2);
        }
        .project h3 {
            margin-top: 0;
            color: white;
        }
        .skills-icons img {
            height: 40px;
            margin: 0.3em;
            transition: transform 0.2s ease, filter 0.2s ease;
        }
        .skills-icons img:hover {
            transform: scale(1.1);
            filter: drop-shadow(0 0 5px white);
        }
        .contact img {
            margin: 0.5em;
            height: 35px;
            transition: transform 0.2s ease, filter 0.2s ease;
        }
        .contact img:hover {
            transform: scale(1.15);
            filter: drop-shadow(0 0 6px white);
        }
        footer {
            text-align: center;
            padding: 1em;
            background-color: #1E1E1E;
            color: #B0B0B0;
            font-size: 0.9em;
        }
        @media (max-width: 600px) {
            .about {
                flex-direction: column;
                text-align: center;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Juan Díaz</h1>
    <p>Backend Developer | Azure & Cloud Enthusiast | Student at Uniminuto</p>
</header>

<div class="container">
    <section id="about" class="about">
        <div>
             <ul>
                <li>📚 Studying to become a Backend Developer specialized in Azure Cloud.</li>
                <li>🏫 Software Development student at Uniminuto University in Colombia.</li>
                <li>💻 Strong focus on backend development and cloud-based solutions.</li>
                <li>📂 Experience building an internal File Management Intranet for a company.</li>
                <li>🚀 Preparing for Microsoft Azure Fundamentals (AZ-900) certification.</li>
                <li>🖥 Languages: JavaScript, Python, SQL.</li>
                <li>⚙ Databases: MySQL, PostgreSQL and MongoDB</li>
                <li>📘 Currently learning API design, authentication, and cloud deployment on Azure.</li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="project">
                <h3>Quotation System</h3>
                <p>Internal application with PDF generation, developed in Node.js to speed up business processes.</p>
                <p><strong>Technologies:</strong> Node.js, JavaScript, SQL</p>
            </div>
            <div class="project">
                <h3>File Management Intranet</h3>
                <p>Local intranet system for organizing, storing, and managing internal company files efficiently.</p>
                <p><strong>Technologies:</strong> Node.js, Express, SQL</p>
            </div>
        </div>
    </section>

    <section id="skills">
        <h2>Technologies</h2>
        <div class="skills-icons">
            <p align="center">
               <a href="https://skillicons.dev">
                   <img src="https://skillicons.dev/icons?i=git,aws,docker,postman,azure,css,mongodb,postgres,nodejs,py,vscode" />
                 </a>
          </p>
        </div>
    </section>

    <section  align="center" id="contact" class="contact">
        <h2>Connect With Me</h2>
        <a href="https://www.instagram.com/jua.ndiaz102"><img src="https://cdn.simpleicons.org/instagram" alt="Instagram"></a>
        <a href="#"><img src="https://cdn.simpleicons.org/gmail" alt="Gmail"></a>
        <a href="https://github.com/Juan1Diazr"><img src="https://cdn.simpleicons.org/github" alt="GitHub"></a>
        <a href="www.linkedin.com/in/juan-diaz-aaa762172"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"></a>
    </section>
</div>

<footer>
    © 2025 Juan Díaz | All rights reserved
</footer>

</body>
</html>
