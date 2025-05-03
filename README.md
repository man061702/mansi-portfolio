!DOCTYPE html> 
<html lang="en"><!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mansi Avhad | SEO Content Writer</title>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Playfair+Display:wght@400;700&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
        integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #f8f8f8;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-image: url('https://images.unsplash.com/photo-1519389950473-47ba0277781c');
            background-size: cover;
            background-position: center;
            height: 90vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
            animation: fadeIn 2s ease-in;
        }

        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.6);
        }

        .hero-content {
            position: relative;
            z-index: 1;
            color: #fff;
            padding: 2rem;
            animation: fadeInUp 1s ease-out;
        }

        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3.5rem;
            margin-bottom: 0.3rem;
            font-weight: 700;
            letter-spacing: 0.1rem;
        }

        .hero-content p {
            font-family: 'Poppins', sans-serif;
            font-style: italic;
            font-size: 1.4rem;
            margin-top: 0;
            color: #eee;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
        }

        nav {
            background: #333;
            padding: 0.7rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            margin: 0;
            padding: 0;
        }

        nav li {
            margin: 0 1.5rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease, transform 0.2s ease-in-out;
            font-size: 1.1rem;
        }

        nav a:hover {
            color: #007acc;
            text-decoration: underline;
            transform: scale(1.1);
        }

        nav a:active {
            opacity: 0.8;
        }

        nav a:focus {
            outline: 2px solid #007acc;
            outline-offset: 2px;
        }

        section {
            padding: 5rem 2rem;
            max-width: 1000px;
            margin: 0 auto;
            text-align: center;
        }

        section h2 {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            color: #222;
            font-weight: 700;
            margin-bottom: 1rem;
            letter-spacing: 0.1rem;
            text-align: left; /* Added text-align: left; here */
        }

        section p {
            font-family: 'Poppins', sans-serif;
            font-size: 1.15rem;
            line-height: 1.8;
            color: #444;
        }

        a.button {
            font-family: 'Poppins', sans-serif;
            background: #007acc;
            color: white;
            padding: 0.8rem 1.6rem;
            border-radius: 8px;
            display: inline-block;
            margin-top: 2rem;
            text-decoration: none;
            font-weight: 600;
            transition: background-color 0.3s ease, box-shadow 0.2s ease-in-out,
            transform 0.2s ease-in-out;
            font-size: 1.1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        a.button:hover {
            background: #005fa3;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.2);
            transform: translateY(-3px) scale(1.05);
        }

        a.button:active {
            opacity: 0.8;
            transform: scale(0.95);
        }

        a.button:focus {
            outline: 2px solid #007acc;
            outline-offset: 2px;
        }

        footer {
            text-align: center;
            background: #333;
            color: white;
            padding: 2.5rem 1rem;
            font-size: 1rem;
            font-family: 'Poppins', sans-serif;
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(-20px);
            }

            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }

            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes typing {
            from {
                width: 0;
            }

            to {
                width: 100%;
            }
        }

        @keyframes blink-caret {
            from,
            to {
                border-color: transparent
            }

            50% {
                border-color: #fff;
            }
        }

        /* Section-specific styles */
        #about {
            background-color: #000;
            color: white;
            animation: fadeIn 2s ease-in;
            text-align: left;
        }

        #about h2 {
            color: #fff;
            text-align: left;
            transition: color 0.3s ease;
        }

        #about h2:hover {
            color: #00aaff;
        }

        #about p {
            color: #ddd;
            text-align: left;
            max-width: 700px;
            margin-left: 0;
            margin-right: auto;
            transition: color 0.3s ease;
        }

        #about p:hover {
            color: #eee;
        }

        #about ul {
            list-style-type: disc;
            padding-left: 2rem;
            color: #ddd;
            text-align: left;
            max-width: 700px;
            margin-left: 0;
            margin-right: auto;
        }

        #about li {
            margin-bottom: 0.5rem;
            transition: color 0.3s ease;
        }

        #about li:hover {
            color: #fff;
            transform: translateX(5px);
        }

        #work {
            background-image: url('https://images.unsplash.com/photo-1554415707-6e8cfc93fe23?auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
            padding: 6rem 2rem;
            color: white;
            animation: fadeIn 2s ease-in;
            background-repeat: no-repeat;
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            justify-content: center;
            min-height: 300px;
            text-align: left;
        }

        #work::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.4);
            z-index: 1;
        }

        #work h2 {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            font-weight: 700;
            position: relative;
            z-index: 2;
            text-align: left; /* Added text-align: left; here */
            margin-bottom: 1rem;
            width: 100%;
            letter-spacing: 0.1rem;
            transition: transform 0.3s ease;
        }

        #work h2:hover {
            transform: scale(1.05);
        }

        #work p {
            font-family: 'Poppins', sans-serif;
            font-size: 1.15rem;
            line-height: 1.8;
            position: relative;
            z-index: 2;
            text-align: left;
            margin-bottom: 1.5rem;
            max-width: 600px;
            align-self: flex-start;
            transition: color 0.3s ease;
        }

        #work p:hover {
            color: #eee;
        }

        #work a.button {
            font-family: 'Poppins', sans-serif;
            background-color: rgba(0, 122, 204, 0.8);
            color: white;
            padding: 0.8rem 1.6rem;
            border-radius: 8px;
            display: inline-block;
            margin-top: 2rem;
            text-decoration: none;
            font-weight: 600;
            transition: background-color 0.3s ease;
            position: relative;
            z-index: 2;
            align-self: flex-start;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        #work a.button:hover {
            background-color: rgba(0, 95, 163, 0.9);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.2);
            transform: translateY(-3px) scale(1.05);
        }

        #work a.button:active {
            opacity: 0.8;
            transform: scale(0.95);
        }

        #work a.button:focus {
            outline: 2px solid #007acc;
            outline-offset: 2px;
        }

        #contact {
            background-color: #000;
            color: white;
            animation: fadeIn 2s ease-in;
            padding: 6rem 2rem;
            border-radius: 10px;
            text-align: center;
            font-family: 'Poppins', sans-serif;
        }

        #contact h2 {
            font-family: 'Playfair Display', serif;
            font-size: 3.2rem;
            font-weight: 700;
            color: white;
            overflow: hidden;
            white-space: nowrap;
            margin: 0 auto 1rem;
            letter-spacing: .1em;
            animation: typing 3.5s steps(30, end) forwards,
                blink-caret .75s step-end infinite;
        }

        #contact p {
            font-family: 'Poppins', sans-serif;
            font-size: 1.15rem;
            line-height: 1.8;
            color: #fff;
            transition: transform 0.2s ease-in-out;
        }

        #contact p:hover {
            transform: scale(1.05);
            color: #eee;
        }

        #contact a {
            font-family: 'Poppins', sans-serif;
            font-weight: bold;
            color: #fff;
            text-decoration: none;
            transition: color 0.3s ease, transform 0.2s ease-in-out;
        }

        #contact a:hover {
            color: #00aaff;
            text-decoration: underline;
            transform: translateX(5px) scale(1.05);
        }

        #contact a:active {
            opacity: 0.8;
        }

        #contact a:focus {
            outline: 2px solid #00aaff;
            outline-offset: 2px;
        }

        /* Media Queries for Responsiveness */
        @media (max-width: 768px) {
            header {
                height: 70vh;
            }

            header h1 {
                font-size: 2.8rem;
            }

            .hero-content p {
                font-size: 1.2rem;
            }

            nav ul {
                flex-direction: column;
                align-items: flex-start;
            }

            nav li {
                margin: 0.7rem 0;
            }

            section {
                padding: 4rem 1.5rem;
            }

            section h2 {
                font-size: 2.5rem;
            }

            section p {
                font-size: 1.1rem;
            }

            #work {
                align-items: center;
                text-align: center;
            }

            #work h2 {
                text-align: left; /* Added text-align: left; here */
            }

            #work p {
                text-align: center;
                align-self: center;
            }

            #work a.button {
                align-self: center;
            }

            #about,
            #contact {
                text-align: center;
            }

            #about h2,
            #about p,
            #about ul {
                text-align: center;
                margin-left: auto;
                margin-right: auto;
            }
        }
    </style>
    
</head>

<body>

    <header>
        <div class="hero-content">
            <h1>Mansi Avhad</h1>
            <p>Helping You Show Up, Stand Out, and Shine Online</p>
            <a href="#contact" class="button">Let's Talk</a>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#work">Work</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>Hi, I'm Mansi!</h2>
        <p>
            I'm a passionate SEO Content Writer dedicated to helping businesses like yours
            thrive online. I don't just write words; I craft strategic content that
            drives traffic, boosts engagement, and converts visitors into loyal
            customers.
        </p>
        <p>Here's what I bring to the table:</p>
        <ul>
            <li>
                <b>SEO Expertise:</b> I understand the intricacies of search engine
                optimization and write content that ranks.
            </li>
            <li>
                <b>Compelling Storytelling:</b> I captivate your audience with engaging
                narratives that resonate.
            </li>
            <li>
                <b>Versatile Writing:</b> From blog posts and articles to website copy
                and marketing materials, I've got you covered.
            </li>
        </ul>
    </section>

    <section id="work">
        <h2>My Latest Work</h2>
        <p>
            Explore my portfolio on Medium to see how I've helped clients achieve
            their content goals.
        </p>
        <a href="https://medium.com/@mansiavhad4" target="_blank" class="button">View My Medium Articles</a>
    </section>

    <section id="contact">
        <h2>Ready to Elevate Your Content?</h2>
        <p>
            I'm excited to discuss how I can help your business achieve its content
            marketing objectives. Let's connect!
        </p>
        <p>
            <i class="fas fa-envelope"></i>
            <a href="mailto:mansiavhad4@gmail.com">mansiavhad4@gmail.com</a><br />
            <i class="fas fa-phone"></i>
            <a href="tel:9819455710">9819455710</a><br />
            <i class="fab fa-linkedin"></i>
            <a href="https://linkedin.com/in/mansiavhad" target="_blank">LinkedIn</a><br />
            <i class="fas fa-file-alt"></i>
            <a href="https://aquamarine-evie-30.tiiny.site" target="_blank">View My Resume</a>
        </p>
    </section>

    <footer>
        &copy; 2025 Mansi
    </footer>

</body>

</html>

