<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio</title>
    <style>
        /* Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Navigation */
        header {
            background-color: #ffffff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #2c3e50;
        }
        .nav-links {
            list-style: none;
            display: flex;
        }
        .nav-links li {
            margin-left: 20px;
        }
        .nav-links a {
            text-decoration: none;
            color: #555;
            font-weight: 600;
            transition: color 0.3s;
        }
        .nav-links a:hover {
            color: #3498db;
        }

        /* Hero Section */
        #hero {
            background: linear-gradient(135deg, #2c3e50, #3498db);
            color: white;
            padding: 100px 0;
            text-align: center;
        }
        #hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }
        #hero p {
            font-size: 20px;
            margin-bottom: 20px;
            opacity: 0.9;
        }
        .btn {
            display: inline-block;
            background-color: #e74c3c;
            color: white;
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #c0392b;
        }

        /* Section Layout */
        section {
            padding: 80px 0;
        }
        section h2 {
            text-align: center;
            font-size: 32px;
            margin-bottom: 40px;
            color: #2c3e50;
            position: relative;
        }
        section h2::after {
            content: '';
            display: block;
            width: 50px;
            height: 3px;
            background-color: #3498db;
            margin: 10px auto 0 auto;
        }

        /* About Section */
        #about p {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
            font-size: 18px;
        }

        /* Grid Layout for Projects & Skills */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card h3 {
            margin-bottom: 15px;
            color: #2c3e50;
        }

        /* Contact Section */
        #contact {
            background-color: #2c3e50;
            color: white;
            text-align: center;
        }
        #contact h2 {
            color: white;
        }
        #contact p {
            margin-bottom: 20px;
        }
        #contact a {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
        }
        #contact a:hover {
            text-decoration: underline;
        }

        footer {
            background-color: #1a252f;
            color: #7f8c8d;
            text-align: center;
            padding: 20px 0;
            font-size: 14px;
        }

        /* Mobile Responsive Navigation */
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
            }
            .nav-links {
                margin-top: 20px;
            }
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <header>
        <div class="container">
            <nav>
                <div class="logo">My Portfolio</div>
                <ul class="nav-links">
                    <li><a href="#hero">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <div class="container">
            <h1>Hi, I'm [Your Name]</h1>
            <p>A passionate Developer / Designer / Creator based in the Philippines</p>
            <a href="#contact" class="btn">Get In Touch</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>
                Write a brief introduction about yourself here. Talk about your background, what you love doing, 
                and your current professional goals. Keep it short, engaging, and professional!
            </p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2>My Projects</h2>
            <div class="grid">
                <div class="card">
                    <h3>Project One</h3>
                    <p>A brief description of your first project. Explain what technologies you used and the problem it solved.</p>
                </div>
                <div class="card">
                    <h3>Project Two</h3>
                    <p>A brief description of your second project. Highlight your specific role and the outcome of the project.</p>
                </div>
                <div class="card">
                    <h3>Project Three</h3>
                    <p>A brief description of your third project. Mention any unique challenges you overcame while building it.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>I am always open to new opportunities and collaborations!</p>
            <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
            <p>LinkedIn: <a href="#" target="_blank">://linkedin.com</a></p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 [Your Name]. All rights reserved.</p>
    </footer>

</body>
</html>
# hylamaynard.github.io
Hyla PH
