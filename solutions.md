HTML
<!-- index.html — Home -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coders Club - Home</title>
    <meta name="description" content="Welcome to the Coders Club at Invertis University. Learn programming, web development, and participate in exciting tech events.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Coders Club</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html" class="active">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="registration.html">Register</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main class="container">
        <section id="hero" class="card">
            <h2>Welcome to Coders Club</h2>
            <p>Empowering students through code, collaborative projects, and hands-on workshops in software development.</p>
            <img src="images/club-banner.jpg" alt="Coders club members collaborating on programming projects in the computer lab" width="600" height="300" class="hero-img">
        </section>

        <section id="activities" class="card">
            <h2>Our Core Activities</h2>
            <ul class="styled-list">
                <li>Weekly coding workshops covering Java, JavaScript, and web development.</li>
                <li>Hackathons and competitive programming practice sessions.</li>
                <li>Peer mentoring and collaborative open-source projects.</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Coders Club, Invertis University. All rights reserved.</p>
    </footer>
</body>
</html>
HTML
<!-- about.html — Club Introduction -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coders Club - About</title>
    <meta name="description" content="Learn about the Coders Club mission, core members, and upcoming event schedules at Invertis University.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Coders Club</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html" class="active">About</a></li>
                <li><a href="registration.html">Register</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main class="container">
        <section id="about-intro" class="card">
            <h2>About the Club</h2>
            <p>Founded by passionate Computer Science Engineering students at Invertis University, Coders Club bridges the gap between theoretical classroom knowledge and practical software engineering.</p>
        </section>

        <section id="members" class="card">
            <h2>Core Committee Members</h2>
            <ul class="styled-list">
                <li><strong>Atim Akhtar</strong> — President & Lead Web Developer</li>
                <li><strong>Falak Siddiqui</strong> — Vice President & Event Coordinator</li>
                <li><strong>Utkarsh Tiwari</strong> — Technical Lead</li>
            </ul>
        </section>

        <section id="events" class="card">
            <h2>Upcoming Events Schedule</h2>
            <div class="table-container">
                <table>
                    <caption>Coders Club Fall Semester Schedule</caption>
                    <thead>
                        <tr>
                            <th>Event Name</th>
                            <th>Date</th>
                            <th>Time</th>
                            <th>Location</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>HTML & CSS Workshop</td>
                            <td>November 12, 2026</td>
                            <td>3:00 PM - 5:00 PM</td>
                            <td>Computer Lab 1</td>
                        </tr>
                        <tr>
                            <td>JavaScript Hackathon</td>
                            <td>November 25, 2026</td>
                            <td>10:00 AM - 4:00 PM</td>
                            <td>Main Auditorium</td>
                        </tr>
                        <tr>
                            <td>Git & GitHub Session</td>
                            <td>December 5, 2026</td>
                            <td>2:00 PM - 4:00 PM</td>
                            <td>Computer Lab 2</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Coders Club, Invertis University. All rights reserved.</p>
    </footer>
</body>
</html>
HTML
<!-- registration.html — Club Registration Form -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coders Club - Registration</title>
    <meta name="description" content="Register to join the Coders Club at Invertis University and participate in tech events.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Coders Club</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="registration.html" class="active">Register</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main class="container">
        <section class="card">
            <h2>Club Membership Registration</h2>
            <form action="#" method="POST" class="club-form">
                <div class="form-group">
                    <label for="fullname">Full Name:</label>
                    <input type="text" id="fullname" name="fullname" required>
                </div>

                <div class="form-group">
                    <label for="email">University Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>

                <div class="form-group">
                    <label for="rollno">Roll Number:</label>
                    <input type="text" id="rollno" name="rollno" required>
                </div>

                <div class="form-group">
                    <label for="department">Department:</label>
                    <select id="department" name="department" required>
                        <option value="">-- Select Department --</option>
                        <option value="cse">Computer Science Engineering</option>
                        <option value="it">Information Technology</option>
                        <option value="ece">Electronics & Communication</option>
                    </select>
                </div>

                <fieldset class="form-fieldset">
                    <legend>Programming Experience:</legend>
                    <div class="checkbox-group">
                        <label><input type="checkbox" id="exp-html" name="experience" value="html"> HTML/CSS</label>
                        <label><input type="checkbox" id="exp-js" name="experience" value="javascript"> JavaScript</label>
                        <label><input type="checkbox" id="exp-java" name="experience" value="java"> Java</label>
                    </div>
                </fieldset>

                <div class="form-group">
                    <button type="submit" class="btn btn-primary">Submit Registration</button>
                </div>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Coders Club, Invertis University. All rights reserved.</p>
    </footer>
</body>
</html>
HTML
<!-- contact.html — Contact Details -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coders Club - Contact</title>
    <meta name="description" content="Get in touch with the Coders Club team at Invertis University, Bareilly.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Coders Club</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="registration.html">Register</a></li>
                <li><a href="contact.html" class="active">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main class="container">
        <section id="contact-info" class="card">
            <h2>Contact Details</h2>
            <p>Have questions about events, workshops, or club memberships? Reach out to us using the details below:</p>
            <ul class="styled-list contact-list">
                <li><strong>Email:</strong> codersclub@invertisuniversity.ac.in</li>
                <li><strong>Phone:</strong> +91 98765 43210</li>
                <li><strong>Location:</strong> Department of Computer Science Engineering, Invertis University, Bareilly, Uttar Pradesh, India</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Coders Club, Invertis University. All rights reserved.</p>
    </footer>
</body>
</html>
CSS
/* style.css */
:root {
    --primary-color: #0284c7;
    --primary-hover: #0369a1;
    --secondary-color: #0f172a;
    --bg-color: #f8fafc;
    --surface-color: #ffffff;
    --text-color: #334155;
    --border-color: #e2e8f0;

    --space-sm: 8px;
    --space-md: 16px;
    --space-lg: 24px;
    --space-xl: 32px;

    --radius-md: 8px;
    --shadow-sm: 0 1px 3px rgba(0, 0, 0, 0.1);
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: var(--bg-color);
    color: var(--text-color);
    line-height: 1.6;
}

header {
    background-color: var(--secondary-color);
    color: var(--surface-color);
    padding: var(--space-md) var(--space-xl);
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 1.5rem;
    color: var(--surface-color);
}

nav ul {
    list-style: none;
    display: flex;
    gap: var(--space-md);
}

nav a {
    color: var(--surface-color);
    text-decoration: none;
    font-weight: bold;
    padding: var(--space-sm) var(--space-md);
    border-radius: var(--radius-md);
    transition: background-color 0.2s ease;
}

nav a:hover, nav a.active {
    background-color: var(--primary-color);
}

.container {
    max-width: 900px;
    margin: var(--space-xl) auto;
    padding: 0 var(--space-md);
    display: flex;
    flex-direction: column;
    gap: var(--space-lg);
}

.card {
    background-color: var(--surface-color);
    border: 1px solid var(--border-color);
    border-radius: var(--radius-md);
    padding: var(--space-lg);
    box-shadow: var(--shadow-sm);
}

h2 {
    color: var(--secondary-color);
    margin-bottom: var(--space-md);
    border-bottom: 2px solid var(--border-color);
    padding-bottom: var(--space-sm);
}

.hero-img {
    width: 100%;
    height: auto;
    border-radius: var(--radius-md);
    margin-top: var(--space-md);
}

.styled-list {
    padding-left: var(--space-lg);
}

.styled-list li {
    margin-bottom: var(--space-sm);
}

.table-container {
    overflow-x: auto;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: var(--space-md);
}

caption {
    font-weight: bold;
    margin-bottom: var(--space-sm);
}

th, td {
    border: 1px solid var(--border-color);
    padding: var(--space-sm) var(--space-md);
    text-align: left;
}

th {
    background-color: var(--bg-color);
    color: var(--secondary-color);
}

.club-form {
    display: flex;
    flex-direction: column;
    gap: var(--space-md);
}

.form-group {
    display: flex;
    flex-direction: column;
    gap: var(--space-sm);
}

.form-group label {
    font-weight: bold;
}

.form-group input, .form-group select {
    padding: var(--space-sm) var(--space-md);
    border: 1px solid var(--border-color);
    border-radius: var(--radius-md);
    font-size: 1rem;
}

.form-fieldset {
    border: 1px solid var(--border-color);
    border-radius: var(--radius-md);
    padding: var(--space-md);
}

.checkbox-group {
    display: flex;
    gap: var(--space-md);
    margin-top: var(--space-sm);
}

.btn {
    padding: var(--space-sm) var(--space-lg);
    border: none;
    border-radius: var(--radius-md);
    font-size: 1rem;
    font-weight: bold;
    cursor: pointer;
    align-self: flex-start;
}

.btn-primary {
    background-color: var(--primary-color);
    color: var(--surface-color);
}

.btn-primary:hover {
    background-color: var(--primary-hover);
}

footer {
    background-color: var(--secondary-color);
    color: var(--surface-color);
    text-align: center;
    padding: var(--space-md);
    margin-top: var(--space-xl);
}
Markdown
# Design Choices & Explanation

The website uses a clean and cohesive modern color palette based on deep slate blue (`#0f172a`) for structural elements like headers/footers and ocean blue (`#0284c7`) for interactive highlights and primary action buttons. 
All reusable styling metrics (colors, spacing, and border-radius) are defined using CSS variables in `:root` to ensure global design consistency and maintainability. 
Typography is styled with Arial sans-serif, configured with consistent line-heights and padding to make long paragraphs, multi-column tables, and form inputs clean and readable. 
Card-based structural containers (`.card`) paired with subtle box shadows organize content neatly across all four pages, maintaining a balanced hierarchy between navigation, text content, tables, and forms.