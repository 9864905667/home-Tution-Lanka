# home-Tution-Lanka
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Home Tuition - Lanka, Hojai</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f9f9f9;
        }
        header {
            background: linear-gradient(135deg, #1e88e5, #42a5f5);
            color: white;
            text-align: center;
            padding: 3rem 1rem;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        nav {
            background: #ffffff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            padding: 1rem;
            text-align: center;
        }
        nav a {
            margin: 0 1.5rem;
            text-decoration: none;
            color: #1e88e5;
            font-weight: 600;
            font-size: 1.1rem;
        }
        nav a:hover {
            color: #1565c0;
        }
        .hero {
            background: url('https://via.placeholder.com/1200x400/1e88e5/ffffff?text=Learn+Economics') no-repeat center/cover;
            padding: 4rem 2rem;
            text-align: center;
            color: white;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7);
        }
        .hero h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 2rem 1rem;
        }
        .section {
            background: white;
            padding: 2rem;
            margin-bottom: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }
        .section h2 {
            color: #1e88e5;
            margin-bottom: 1rem;
            font-size: 1.8rem;
        }
        .section p, .section ul {
            font-size: 1.1rem;
            color: #444;
        }
        .section ul {
            list-style: disc;
            margin-left: 1.5rem;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            max-width: 600px;
            margin: auto;
        }
        .contact input, .contact textarea {
            padding: 0.75rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
            width: 100%;
        }
        .contact button {
            background: #1e88e5;
            color: white;
            border: none;
            padding: 0.75rem;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: background 0.3s;
        }
        .contact button:hover {
            background: #1565c0;
        }
        footer {
            background: #1e88e5;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
        footer p {
            font-size: 0.9rem;
        }
        @media (max-width: 600px) {
            header h1 {
                font-size: 1.8rem;
            }
            header p {
                font-size: 1rem;
            }
            .hero h2 {
                font-size: 1.5rem;
            }
            nav a {
                margin: 0 0.5rem;
                font-size: 0.9rem;
            }
            .section h2 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Economics Home Tuition</h1>
        <p>Expert Tutoring by a Master’s in Economics & B.Ed. Holder in Lanka, Hojai, Assam</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#fees">Fees</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <h2>Unlock Your Potential in Economics</h2>
        <p>Personalized home tuition to help you excel in economics, taught by an experienced tutor.</p>
    </section>
    <div class="container">
        <section class="section about" id="about">
            <h2>About Your Tutor</h2>
            <p>I hold a Master’s degree in Economics and a B.Ed., bringing expertise and a passion for teaching to help students succeed. Based in Lanka, Hojai, Assam (PIN: 782446), I offer personalized home tuition tailored to your learning needs.</p>
        </section>
        <section class="section services" id="services">
            <h2>Our Services</h2>
            <ul>
                <li>One-on-one home tuition in Economics for high school and college students.</li>
                <li>Concept clarity, exam preparation, and practical applications.</li>
                <li>Customized lesson plans to suit individual learning paces.</li>
                <li>Guidance on assignments, projects, and competitive exams.</li>
            </ul>
        </section>
        <section class="section fees" id="fees">
            <h2>Fees</h2>
            <p>₹2,000 for 14 days of personalized home tuition.</p>
            <p>Sessions are designed to maximize learning within a flexible schedule. Contact me to discuss timing and availability.</p>
        </section>
        <section class="section contact" id="contact">
            <h2>Contact Me</h2>
            <p>Ready to start? Fill out the form below to get in touch!</p>
            <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <input type="tel" name="phone" placeholder="Your Phone Number" required>
                <textarea name="message" placeholder="Your Message (e.g., subject, class, or schedule)" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
            <p>Location: Lanka, Hojai, Assam, PIN: 782446</p>
        </section>
    </div>
    <footer>
        <p>© 2025 Economics Home Tuition, Lanka, Hojai, Assam. All rights reserved.</p>
    </footer>
</body>
</html>
