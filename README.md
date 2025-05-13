# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

Good luck and happy coding! 🚀💻


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Colorful Blog</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Inter', sans-serif;
            color: #333;
            background-color: #f0f4f8; /* Light background */
        }

        /* Header Styles */
        header {
            background-color: #6200ea; /* Vibrant purple */
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            color: #ffffff;
            font-size: 2.5em;
            margin-bottom: 0;
        }

        header p {
            color: #ede7f6;
            font-size: 1.1em;
            font-weight: 500;
        }

        /* Navigation Styles */
        nav {
            background-color: #f3e5f5; /* Light purple */
            padding: 15px;
            text-align: center;
            border-bottom: 1px solid #d1c4e9;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        nav ul li a {
            color: #6200ea; /* Purple */
            text-decoration: none;
            font-weight: 600;
            font-size: 1.2em;
            padding: 10px 15px;
            border-radius: 8px;
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover {
            background-color: #d1c4e9; /* Light purple hover */
        }

        /* Main Content Styles */
        main {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        main h2 {
            color: #6200ea; /* Purple */
            font-size: 2em;
            margin-bottom: 20px;
            text-align: center;
        }

        main p {
            color: #424242;
            font-size: 1.1em;
            line-height: 1.7;
            margin-bottom: 20px;
        }

        .blog-post {
            background-color: #ffffff;
            padding: 25px;
            border-radius: 12px;
            margin-bottom: 30px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease;
        }

        .blog-post:hover {
            transform: translateY(-5px);
        }

        .blog-post h3 {
            color: #6200ea; /* Purple */
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .blog-post p {
            color: #555;
            font-size: 1.1em;
            line-height: 1.7;
            margin-bottom: 15px;
        }

        .blog-post .read-more {
            display: inline-block;
            background-color: #6200ea; /* Purple */
            color: #ffffff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 8px;
            font-weight: 600;
            transition: background-color 0.3s ease;
            margin-top: 10px;
        }

        .blog-post .read-more:hover {
            background-color: #4a148c; /* Darker purple */
        }

        /* Footer Styles */
        footer {
            background-color: #311b92; /* Very dark purple */
            color: #ffffff;
            padding: 20px;
            text-align: center;
            margin-top: 40px;
        }

        footer p {
            font-size: 0.9em;
            font-weight: 400;
        }

        /* Responsive Styles */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                gap: 10px;
            }

            header h1 {
                font-size: 2.5em;
            }

            main h2 {
                font-size: 1.8em;
            }

            .blog-post {
                padding: 20px;
            }
        }

        @media (max-width: 480px) {
            header h1 {
                font-size: 2em;
            }

            header p {
                font-size: 1em;
            }

            main {
                padding: 10px;
            }

            .blog-post h3 {
                font-size: 1.2em;
            }

            .blog-post p {
                font-size: 1em;
            }
        }

        /* Utility Classes */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .text-center {
            text-align: center;
        }

        .mt-5 {
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>My Colorful Blog</h1>
            <p>A journey through technology, design, and life.</p>
        </div>
    </header>
    <nav>
        <div class="container">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>
    <main>
        <div class="container">
            <section id="home" class="text-center">
                <h2>Welcome to My Blog</h2>
                <p>
                    This is a space where I share my thoughts, ideas, and experiences.
                    Join me as I explore the exciting world of web development,
                    design, and everything in between.
                </p>
                <p>
                    I hope you find something that inspires you!
                </p>
            </section>

            <section id="blog">
                <h2>Latest Posts</h2>
                <div class="blog-post">
                    <h3>The Beauty of CSS Grid</h3>
                    <p>
                        CSS Grid Layout is a powerful tool for creating complex and
                        responsive layouts.  Learn how to use it to build amazing websites.
                    </p>
                    <a href="#" class="read-more">Read More</a>
                </div>
                <div class="blog-post">
                    <h3>Mastering JavaScript Functions</h3>
                    <p>
                        Functions are the building blocks of JavaScript.  Understand how
                        to define, call, and use them effectively.
                    </p>
                    <a href="#" class="read-more">Read More</a>
                </div>
                <div class="blog-post">
                    <h3>Responsive Design with Media Queries</h3>
                    <p>
                       Media Queries are essential for making your website look good on all devices.
                    </p>
                    <a href="#" class="read-more">Read More</a>
                </div>
            </section>

            <section id="about" class="text-center">
                <h2>About Me</h2>
                <p>
                    I'm a web developer passionate about creating beautiful and
                    functional websites. I love exploring new technologies and sharing
                    my knowledge with the world.
                </p>
                <p>
                    When I'm not coding, you can find me reading, hiking, or
                    experimenting with new recipes.
                </p>
            </section>

            <section id="contact" class="text-center">
                <h2>Contact Me</h2>
                <p>
                    Have a question or just want to say hello?  Feel free to reach out
                    to me through the following channels:
                </p>
                <p>
                    Email: example@email.com<br>
                    Twitter: @myusername<br>
                    LinkedIn: /in/myprofile
                </p>
            </section>
        </div>
    </main>
    <footer>
        <div class="container">
            <p>&copy; 2025 My Colorful Blog. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

       // Interactive "Read More" links (simulated)
        document.querySelectorAll('.read-more').forEach(link => {
            link.addEventListener('click', function (e) {
                e.preventDefault();
                const post = this.closest('.blog-post');
                const content = post.querySelector('p'); // Select the paragraph

                if (content.style.maxHeight) {
                    content.style.maxHeight = null;
                    this.textContent = 'Read More';
                } else {
                    content.style.maxHeight = content.scrollHeight + 'px';
                    this.textContent = 'Read Less';
                }
            });
        });
    </script>
</body>
</html>

