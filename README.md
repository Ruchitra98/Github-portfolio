<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me - Ruchitra Kumaresan</title>
    <link rel="icon" href="Portfolio/11.jpg">
    <style>
        body {
            background-image: url("8.jpg");
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 10px;
            text-align: center;
            color: white;
        }

        .container {
            max-width: 90%;
            margin: auto;
            padding: 20px;
        }

        .intro {
            text-align: center;
            margin: 20px 0;
        }

        .intro h1 {
            background-color: black;
            font-size: 2rem;
            margin-bottom: 10px;
        }

       .intro {
    text-align: center;
    margin: 20px 0;
    padding: 20px;
    border-radius: 10px;
    color: black; /* Text color */
}
        .profile-image {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin: 10px auto;
            display: block;
        }

        .nav {
            list-style-type: none;
            padding: 0;
            margin: 20px 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
        }

        .nav-item {
            margin: 0;
        }

        .nav-link {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            background-color: rgba(0, 0, 0, 0.7);
            transition: background-color 0.3s, color 0.3s;
        }

        .nav-link:hover {
            background-color: #04AA6D;
            color: white;
        }

        .big-box {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 15px;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .big-box p {
            font-size: 1rem;
            color: #333;
        }

        .contact-details p {
            font-size: 1rem;
            margin: 5px 0;
        }

        .social-icons {
            display: flex;
            gap: 15px;
            justify-content: center;
            margin: 20px 0;
        }

        .social-icons img {
            width: 40px;
            height: 40px;
        }

        /* Media Queries for Responsiveness */
        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .nav-link {
                padding: 8px 15px;
                font-size: 0.9rem;
            }

            .big-box {
                padding: 15px;
            }

            .profile-image {
                width: 100px;
                height: 100px;
            }
        }

        @media (max-width: 480px) {
            .intro p {
                font-size: 0.10rem;
            }

            .nav {
                flex-direction: column;
                gap: 5px;
            }

            .big-box {
                padding: 10px;
            }

            .social-icons img {
                width: 50px;
                height: 50px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>WELCOME 👋</h1>
    </header>

    <div class="container">
        <section class="intro">
            <img src="1.jpg" alt="Ruchitra Kumaresan" class="profile-image">
                <p class="intro-text">Ruchitra Kumaresan <br> Front-end Developer | Software Developer | UX/UI Designer</p>
                <nav class="intro-nav">
                <ul class="nav">
                    <li class="nav-item"><a href="Project.html" class="nav-link">Projects</a></li>
                    <li class="nav-item"><a href="Achievements.html" class="nav-link">Achievements</a></li>
                    <li class="nav-item"><a href="Certifications.html" class="nav-link">Certifications</a></li>
                    <li class="nav-item"><a href="Resume.html" class="nav-link">Resume</a></li>
                    <li class="nav-item"><a href="Contact.html" class="nav-link">Contact Me</a></li>
                </ul>
            </nav>
        </section>

        <section class="big-box">
            <h2 class="text-center"> <b> ABOUT ME</b> </h2>
            <p>I'm Ruchitra Kumaresan, a dedicated front-end developer with a Master's in Computer Science from New York Institute of Technology (NYIT) and a Bachelor's in Computer Science from REVA University, India. I specialize in front-end development, with technical expertise in JavaScript, React.js, HTML5, CSS, and software testing. Throughout my academic and professional career, I have successfully delivered robust applications and systems, demonstrating my ability to tackle complex challenges and provide high-quality solutions.

            In addition to my technical skills, I am well-versed in software development methodologies and have experience working in agile environments. My internships at Lernov and Sain Solutions in Bangalore, India, provided me with hands-on experience in front-end web development. I contributed to projects that improved user interaction and functionality. Furthermore, my coursework and projects, such as product recommendation systems and utilizing Recurrent Neural Networks (RNNs) for trading, have honed my analytical and problem-solving abilities.

   I am eager to explore new opportunities to apply my skills and creativity to drive impactful software development and tech industry projects. Let's connect and discuss how we can collaborate to make a significant difference in this ever-evolving field..</p>
        </section>

        <div class="container">
            <h2>Connect 📨</h2>
            <div class="contact-details">
                <p><strong>Email:</strong> ruchitrak98@gmail.com</p>
            </div>
            <div class="social-icons">
                <a href="https://www.linkedin.com/in/ruchitrakumaresan"><img src="Linkedin.jpg" alt="LinkedIn"></a>
                <a href="https://github.com/Ruchitra98"><img src="Github.jpg" alt="GitHub"></a>
            </div>
        </div>
    </div>
</body>
</html>
