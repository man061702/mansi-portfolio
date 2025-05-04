 
        <!DOCTYPE html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mansi Avhad | SEO Content Writer</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Playfair+Display:wght@400;700&family=Inter:wght@400;600;700&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
        integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        /* Basic Reset and Box Sizing */
        *,
        *::before,
        *::after {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #000;
            color: #fff;
            line-height: 1.6;
        }

        /* Header Section */
        header {
            background-image: url('https://images.unsplash.com/photo-1519389950473-47ba0277781c');
            background-size: cover;
            background-position: center;
            min-height: 80vh;
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
            background-color: rgba(0, 0, 0, 0.5);
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
            font-size: 3rem;
            margin-bottom: 0.5rem;
            font-weight: 700;
            letter-spacing: 0.1rem;
            animation: textShadow 2s ease-in-out infinite alternate, fadeIn 1s ease;
        }

        .hero-content p {
            font-family: 'Inter', sans-serif;
            font-style: italic;
            font-size: 1.2rem;
            margin-top: 0;
            color: #eee;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
            animation: pulse 2s ease-in-out infinite alternate;
        }

        .button {
            font-family: 'Poppins', sans-serif;
            background: #fff;
            color: #000;
            padding: 0.8rem 1.6rem;
            border-radius: 8px;
            display: inline-block;
            margin-top: 2rem;
            text-decoration: none;
            font-weight: 600;
            transition: background-color 0.3s ease, box-shadow 0.2s ease-in-out,
                transform 0.2s ease-in-out;
            font-size: 1.1rem;
            box-shadow: 0 4px 6px rgba(255, 255, 255, 0.3);
            animation: buttonShadow 2s ease-in-out infinite alternate;
        }

        .button:hover {
            background: #eee;
            box-shadow: 0 6px 10px rgba(255, 255, 255, 0.5);
            transform: translateY(-3px) scale(1.05);
        }

        .button:active {
            opacity: 0.8;
            transform: scale(0.95);
        }

        .button:focus {
            outline: 2px solid #fff;
            outline-offset: 2px;
        }

        /* Navigation Bar */
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
            color: #fff;
            text-decoration: underline;
            transform: scale(1.1);
        }

        nav a:active {
            opacity: 0.8;
        }

        nav a:focus {
            outline: 2px solid #fff;
            outline-offset: 2px;
        }

        /* Main Content Section */
        main {
            padding-top: 2rem;
        }

        section {
            padding: 4rem 2rem;
            max-width: 1000px;
            margin: 0 auto;
            text-align: center;
        }

        section h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            color: #fff;
            font-weight: 700;
            margin-bottom: 1rem;
            letter-spacing: 0.1rem;
            text-align: left;
            transition: color 0.3s ease, transform 0.3s ease;
        }

        section h2:hover {
            transform: scale(1.05);
            color: #fff;
        }

        section p {
            font-family: 'Inter', sans-serif;
            font-size: 1.1rem;
            line-height: 1.7;
            color: #fff;
        }

        /* About Section */
        #about {
            background-color: rgba(0, 0, 0, 0.8);
            color: #fff;
            animation: fadeIn 2s ease-in;
            text-align: left;
            border-radius: 10px;
            padding: 2rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            margin-bottom: 2rem;
        }

        #about ul {
            list-style-type: disc;
            padding-left: 1.5rem;
            color: #fff;
            text-align: left;
            max-width: 700px;
            margin-left: 0;
            margin-right: auto;
        }

        #about li {
            margin-bottom: 0.5rem;
            transition: color 0.3s ease, transform 0.3s ease;
        }

        #about li b {
            font-weight: 700;
            color: #ddd;
        }

        #about li:hover {
            color: #fff;
            transform: translateX(5px);
        }

        /* Work Section */
        #work {
            background-image: url('https://images.unsplash.com/photo-1554415707-6e8cfc93fe23?auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
            padding: 4rem 2rem;
            color: #fff;
            animation: fadeIn 2s ease-in;
            background-repeat: no-repeat;
            position: relative;
            overflow: hidden;
        }

        #work::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.6);
            z-index: 1;
        }

        .work-section {
            position: relative;
            z-index: 2;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
            text-align: left;
        }

        .work-section h3 {
            font-family: 'Playfair Display', serif;
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
            color: #fff;
        }

        .work-section ul {
            list-style: none;
            padding-left: 0;
            margin-left: 0;
        }

        .work-section ul li {
            margin-bottom: 0.3rem;
            opacity: 0;
            animation: fadeInUp 0.6s ease-out forwards;
        }

        /* Style for the blog title links */
        .blog-title-link {
            color: #fff;
            text-decoration: none;
            font-weight: 700; /* Make the text bold */
            transition: color 0.3s ease, text-shadow 0.3s ease, border-bottom 0.3s ease;
            /* Add transition for border-bottom */
            display: inline-block; /* Needed for the border animation to work correctly */
            padding-bottom: 0.25rem; /* Add some padding below the text */
            border-bottom: 2px solid transparent; /* Start with transparent border */
            position: relative; /* For absolute positioning of the pseudo-element */
        }

        .blog-title-link:hover {
            color: #eee;
            text-shadow: 0 0 5px rgba(255, 255, 255, 0.5);
        }

        .blog-title-link.active {
            color: #ffdb58;
            text-shadow: 0 0 8px #ffdb58;
            transform: scale(1.2);
            transition: transform 0.2s ease-in-out;
        }

        /* Add animation to the underline */
        .blog-title-link::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 100%;
            height: 2px;
            background-color: #fff;
            transform: scaleX(0); /* Start with 0 width */
            transform-origin: left;
            transition: transform 0.3s ease-in-out; /* Add smooth transition */
        }

        .blog-title-link:hover::after {
            transform: scaleX(1); /* Expand to full width on hover */
        }


        /* Contact Section */
        #contact {
            background-color: #000;
            color: #fff;
            padding: 4rem 2rem;
            text-align: center;
        }

        #contact h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 1rem;
            letter-spacing: 0.1rem;
            color: #fff;
            animation: fadeIn 1s ease;
        }

        #contact p {
            font-family: 'Poppins', sans-serif;
            font-size: 1.1rem;
            line-height: 1.8;
            color: #fff;
            font-weight: bold;
            animation: pulse 2s ease-in-out infinite alternate;
        }

        #contact a {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s ease, transform 0.3s ease-in-out;
        }

        #contact a:hover {
            color: #eee;
            text-decoration: underline;
            transform: scale(1.05);
        }

        #contact .fa-envelope,
        #contact .fa-phone,
        #contact .fab,
        #contact .fas {
            margin-right: 0.5rem;
            color: #fff;
            animation: rotate 2s linear infinite;
        }

        /* Footer */
        footer {
            text-align: center;
            background: #333;
            color: white;
            padding: 2rem 1rem;
            font-size: 0.9rem;
            font-family: 'Poppins', sans-serif;
        }

        /* Keyframe Animations */
        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(-10px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(10px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes textShadow {
            from {
                text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
            }
            to {
                text-shadow: 2px 2px 4px rgba(255, 255, 255, 0.5);
            }
        }

        @keyframes buttonShadow {
            from {
                box-shadow: 0 4px 6px rgba(255, 255, 255, 0.1);
            }
            to {
                box-shadow: 0 6px 12px rgba(255, 255, 255, 0.3);
            }
        }

        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.06);
            }
            100% {
                transform: scale(1);
            }
        }

        @keyframes rotate {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }
        /* Media Queries for Responsive Design */
        @media (max-width: 768px) {
            header {
                min-height: 60vh;
            }

            header h1 {
                font-size: 2.5rem;
            }

            .hero-content p {
                font-size: 1rem;
            }

            nav ul {
                flex-direction: column;
                text-align: center;
            }

            nav li {
                margin: 0.5rem 0;
            }

            section {
                padding: 3rem 1.5rem;
            }

            section h2 {
                font-size: 2rem;
            }

            section p {
                font-size: 1rem;
                line-height: 1.7;
            }

            .work-section {
                padding: 1rem;
            }

            .work-section h3 {
                font-size: 1.2rem;
            }

            .work-section ul li {
                font-size: 0.95rem;
            }

            #contact p {
                font-size: 1rem;
            }
        }

        @media (max-width: 480px) {
            header {
                min-height: 80vh;
            }

            header h1 {
                font-size: 2rem;
            }

            .hero-content p {
                font-size: 0.9rem;
            }

            .button {
                font-size: 1rem;
                padding: 0.7rem 1.4rem;
            }

            nav a {
                font-size: 1rem;
            }

            section {
                padding: 2rem 1rem;
            }

            section h2 {
                font-size: 1.75rem;
            }

            section p {
                font-size: 0.9rem;
                line-height: 1.6;
            }

            #about ul {
                padding-left: 1rem;
            }

            .work-section {
                padding: 0.8rem;
            }

            .work-section h3 {
                font-size: 1.1rem;
            }

            .work-section ul li {
                font-size: 0.9rem;
            }

            #contact p {
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <header role="banner">
        <div class="hero-content">
            <h1  style="animation: textShadow 2s ease-in-out infinite alternate, fadeIn 1s ease;">Mansi Avhad</h1>
            <p  style="animation: pulse 2s ease-in-out infinite alternate;">Helping You Show Up, Stand Out, and Shine Online</p>
            <a href="#contact" class="button">Let's Talk</a>
        </div>
    </header>
    <nav role="navigation">
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#work">Work</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
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
            <h2 style="color: #fff; animation: textShadow 2s ease-in-out infinite alternate;">My Work</h2>
            <p style="color: #fff; animation: pulse 2s ease-in-out infinite alternate;">
                Here's a glimpse into the topics I write about:
            </p>
            <div class="work-section">
                <h3 style="color: #fff;">B2B Blogs</h3>
                <div>
                    <ul>
                        <li><a href="https://medium.com/@mansiavhad4/the-real-reason-your-linkedin-posts-arent-bringing-in-leads-7a1a17e289b6"
                                rel="noopener noreferrer" target="_blank" class="blog-title-link">The Real Reason Your LinkedIn Posts Aren’t Bringing in
                                Leads</a></li>
                        <li><a href="https://medium.com/@mansiavhad4/why-case-studies-are-your-secret-weapon-in-b2b-marketing-a1ac35da21b0"
                                rel="noopener noreferrer" target="_blank" class="blog-title-link">Why Case Studies Are Your Secret Weapon in B2B
                                Marketing</a></li>
                        <li><a href="https://medium.com/@mansiavhad4/why-canva-is-the-branding-backbone-for-mid-sized-businesses-c6afc932c9b7"
                                rel="noopener noreferrer" target="_blank" class="blog-title-link">Why Canva Is the Branding Backbone for Mid-Sized
                                Businesses</a></li>
                        <li><a href="#" class="blog-title-link">Is Your Business Ready for an Economic Downturn?</a></li>
                        <li><a href="#" class="blog-title-link">The Growing Importance of ESG Investments</a></li>
                    </ul>
                </div>
            </div>
            <div class="work-section">
                <h3 style="color: #fff;">B2C Blogs</h3>
                <div>
                    <ul>
                        <li><a href="#" class="blog-title-link">Skincare Myths You Still Believe—and What Actually Works</a></li>
                        <li><a href="#" class="blog-title-link">Why We Buy – The Psychology Behind Your Shopping Habits</a></li>
                        <li><a href="#" class="blog-title-link">Scroll, Stop, Shop: Cracking the Code of Mobile Buyers</a></li>
                    </ul>
                </div>
            </div>
            <div class="work-section">
                <h3 style="color: #fff;">News Articles</h3>
                <div>
                    <ul>
                        <li><a href="#" class="blog-title-link">Start Fresh: How One Simple Morning Habit Boosts Your Energy All Day</a></li>
                        <li><a href="#" class="blog-title-link">The “Treat Yourself” Economy: Inside the Rise of Micro-Splurges</a></li>
                    </ul>
                </div>
            </div>
        </section>
        <section id="contact">
            <h2>Ready to Elevate Your Content?</h2>
            <p>
                Scroll, stop, and say hi — let’s create content that sticks
            </p>
            <p>
                <i class="fas fa-envelope"></i>
                <a href="mailto:mansiavhad4@gmail.com">mansiavhad4@gmail.com</a><br />
                <i class="fas fa-phone"></i>
                <a href="tel:9819455710">9819455710</a><br />
                <i class="fab fa-linkedin"></i>
                <a href="https://www.linkedin.com/in/mansi-a-b950372bb?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"
                    target="_blank" rel="noopener noreferrer">LinkedIn</a><br />
                <i class="fas fa-file-alt"></i>
                <a href="https://aquamarine-evie-30.tiiny.site" target="_blank" rel="noopener noreferrer">View My
                    Resume</a>
            </p>
        </section>
    </main>
    <footer>
        &copy; 2025 Mansi Avhad. All rights reserved.
    </footer>
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const blogTitleLinks = document.querySelectorAll('.blog-title-link');

            blogTitleLinks.forEach(link => {
                link.addEventListener('click', function (event) {
                    event.preventDefault();

                    blogTitleLinks.forEach(otherLink => {
                        if (otherLink !== this) {
                            otherLink.classList.remove('active');
                        }
                    });

                    this.classList.add('active');

                    // Open the link in a new tab after adding the active class
                    window.open(this.href, '_blank');

                    setTimeout(() => {
                        this.classList.remove('active');
                    }, 500);
                });
            });
        });
    </script>
</body>
</html>

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
            animation: textShadow 2s ease-in-out infinite alternate;
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
            text-align: left;
            transition: color 0.3s ease, transform 0.3s ease;
        }

        section h2:hover {
            transform: scale(1.05);
            color: #007acc;
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
            animation: buttonShadow 2s ease-in-out infinite alternate;
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

        @keyframes textShadow {
            from {
                text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
            }

            to {
                text-shadow: 2px 2px 4px rgba(0, 122, 255, 0.5);
            }
        }

        @keyframes buttonShadow {
            from {
                box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            }

            to {
                box-shadow: 0 6px 12px rgba(0, 122, 255, 0.3);
            }
        }

        /* Section-specific styles */
        #about {
            background-color: #000;
            color: white;
            animation: fadeIn 2s ease-in;
            text-align: left;
            border-radius: 10px;
            padding: 2rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            margin-bottom: 2rem;
        }

        #about h2 {
            color: #fff;
            text-align: left;
            transition: color 0.3s ease, transform 0.3s ease;
        }

        #about h2:hover {
            color: #00aaff;
            transform: scale(1.05);
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
            transition: color 0.3s ease, transform 0.3s ease;
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
            text-align: left;
            margin-bottom: 1rem;
            letter-spacing: 0.1rem;
            transition: transform 0.3s ease;
            color: #fff;
        }

        #work h2:hover {
            transform: scale(1.05);
            color: #00aaff;
        }

        .work-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 2rem;
            position: relative;
            z-index: 2;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 2rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }

        .work-section h3 {
            flex-basis: 30%;
            text-align: left;
            margin-bottom: 0.5rem;
            font-family: 'Playfair Display', serif;
            font-size: 1.5rem;
            color: #fff;
            font-weight: 700;
            padding-right: 1rem;
            transition: transform 0.3s ease;
        }

        .work-section h3:hover {
            transform: translateX(10px);
            color: #00aaff;
        }

        .work-section>div {
            flex-basis: 65%;
        }

        .work-section ul {
            list-style: none;
            padding-left: 0;
            margin-left: 0;
            margin-bottom: 0.5rem;
        }

        .work-section ul li {
            color: #fff;
            transition: transform 0.3s ease;
        }

        .work-section ul li:hover {
            transform: translateX(5px);
            color: #00aaff;
        }

        .work-section p {
            margin-bottom: 0;
            text-align: left;
            color: #fff;
            font-size: 1.15rem;
            line-height: 1.8;
        }

        .work-section a {
            color: #00aaff;
            text-decoration: none;
            transition: color 0.3s ease;
            font-weight: 600;
        }

        .work-section a:hover {
            color: #fff;
            text-decoration: underline;
            transform: scale(1.05);
        }

        /* Adjust for smaller screens */
        @media (max-width: 768px) {
            .work-section {
                flex-direction: column;
                align-items: flex-start;
            }

            .work-section h3 {
                width: 100%;
                margin-bottom: 0.5rem;
            }

            .work-section>div {
                width: 100%;
            }
        }


        #contact {
            background-color: #000;
            color: white;
            animation: fadeIn 2s ease-in;
            padding: 6rem 2rem;
            border-radius: 10px;
            text-align: center;
            font-family: 'Poppins', sans-serif;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            margin-top: 2rem;
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
                text-align: left;
                color: #fff;
            }

            #work p {
                text-align: center;
                align-self: center;
                color: #fff;
            }

            #work ul {
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

        /* Mobile Styles */
        @media (max-width: 480px) {
            header h1 {
                font-size: 2.5rem;
            }

            .hero-content p {
                font-size: 1rem;
            }

            nav li {
                margin: 0.5rem 0;
            }

            section {
                padding: 3rem 1rem;
            }

            section h2 {
                font-size: 2rem;
            }

            section p {
                font-size: 1rem;
            }

            #work ul {
                padding-left: 2rem;
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
        <h2>My Work</h2>
        <p>
            Here's a glimpse into my work. I write about a variety of topics related to
            SEO, content marketing, and digital strategy.
        </p>
        <div class="work-section">
            <h3>B2B Blogs</h3>
            <div>
                <ul>
                    <li><a
                            href="https://medium.com/@mansiavhad4/the-real-reason-your-linkedin-posts-arent-bringing-in-leads-7a1a17e289b6"
                            rel="noopener noreferrer" target="_blank">The Real Reason Your LinkedIn Posts Aren’t Bringing in
                            Leads</a></li>
                    <li><a
                            href="https://medium.com/@mansiavhad4/why-case-studies-are-your-secret-weapon-in-b2b-marketing-a1ac35da21b0"
                            rel="noopener noreferrer" target="_blank">Why Case Studies Are Your Secret Weapon in B2B
                            Marketing</a></li>
                    <li><a
                            href="https://medium.com/@mansiavhad4/why-canva-is-the-branding-backbone-for-mid-sized-businesses-c6afc932c9b7"
                            rel="noopener noreferrer" target="_blank">Why Canva Is the Branding Backbone for Mid-Sized
                            Businesses</a></li>
                    <li><a href="#">Is Your Business Ready for an Economic Downturn?</a></li>
                    <li><a href="#">The Growing Importance of ESG Investments</a></li>
                </ul>
                <p>I specialize in creating in-depth, informative content for B2B audiences. My
                    focus is on providing valuable insights and actionable strategies.</p>
            </div>
        </div>
        <div class="work-section">
            <h3>B2C Blogs</h3>
            <div>
                <ul>
                    <li><a href="#">Skincare Myths You Still Believe—and What Actually Works</a></li>
                    <li><a href="#">Why We Buy – The Psychology Behind Your Shopping Habits</a></li>
                    <li><a href="#">Scroll, Stop, Shop: Cracking the Code of Mobile Buyers</a></li>
                </ul>
                <p>For B2C clients, I craft compelling narratives and engaging content that
                    resonates with consumers and builds brand loyalty.</p>
            </div>
        </div>
        <div class="work-section">
            <h3>News Articles</h3>
            <div>
                <ul>
                    <li><a href="#">Start Fresh: How One Simple Morning Habit Boosts Your Energy All Day</a></li>
                    <li><a href="#">The “Treat Yourself” Economy: Inside the Rise of Micro-Splurges</a></li>
                </ul>
                <p>I stay up-to-date with the latest industry trends and deliver timely,
                    well-researched news articles.</p>
            </div>
        </div>
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
            <a href="https://linkedin.com/in/mansiavhad" target="_blank" rel="noopener noreferrer">LinkedIn</a><br />
            <i class="fas fa-file-alt"></i>
            <a href="https://aquamarine-evie-30.tiiny.site" target="_blank" rel="noopener noreferrer">View My
                Resume</a>
        </p>
    </section>
    <footer>
        &copy; 2025 Mansi Avhad. All rights reserved.
    </footer>
</body>

</html>
