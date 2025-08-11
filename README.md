# MDAP-EX_01-Portfolio
## Date:11.08.2025
## Name: HARIPRASHAD RA
## REG NO: 212223040060
## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
#### HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Computer Science Engineer</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="container">
            <h1>Hari Prashaad</h1>
            <p>Computer Science Engineering Student</p>
            <nav>
                <a href="#about">About</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <section id="about" class="container">
        <img src="images/profile.jpg" alt="Profile Picture" class="profile-pic">
        <div class="about-text">
            <h2>About Me</h2>
            <p>
                I am a passionate Computer Science Engineering student with a keen interest in 
                software development, problem-solving, and emerging technologies. I enjoy 
                creating efficient and scalable solutions.
            </p>
        </div>
    </section>

    <section id="skills" class="container">
        <h2>Skills</h2>
        <ul class="skills-list">
            <li>Python</li>
            <li>Java</li>
            <li>HTML & CSS</li>
            <li>JavaScript</li>
            <li>Data Structures & Algorithms</li>
            <li>SQL</li>
        </ul>
    </section>

    <section id="projects" class="container">
        <h2>Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <h3>Smart Waste Management System</h3>
                <p>IoT-based project to monitor and manage waste bins using sensors.</p>
            </div>
            <div class="project-card">
                <h3>Portfolio Website</h3>
                <p>Responsive personal portfolio built with HTML, CSS, and JavaScript.</p>
            </div>
            <div class="project-card">
                <h3>Library Management System</h3>
                <p>Java and MySQL-based application for efficient library operations.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="container">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:hari@example.com">hari@example.com</a></p>
        <p>LinkedIn: <a href="#">linkedin.com/in/harip</a></p>
        <p>GitHub: <a href="#">github.com/harip</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Hari Prashaad | Computer Science Engineer</p>
    </footer>

</body>
</html>

```
#### CSS
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f8f9fa;
    color: #333;
    line-height: 1.6;
}

.container {
    width: 80%;
    max-width: 1000px;
    margin: auto;
    padding: 20px;
}

header {
    background: #0077b6;
    color: white;
    text-align: center;
    padding: 20px 0;
}

header h1 {
    font-size: 2rem;
}

header nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

header nav a:hover {
    text-decoration: underline;
}

#about {
    display: flex;
    align-items: center;
    margin-top: 40px;
}

.profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-right: 30px;
}

.about-text {
    flex: 1;
}

.skills-list {
    display: flex;
    flex-wrap: wrap;
    list-style: none;
    margin-top: 20px;
}

.skills-list li {
    background: #0077b6;
    color: white;
    padding: 10px 15px;
    margin: 5px;
    border-radius: 5px;
}

.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.project-card {
    background: white;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.project-card h3 {
    margin-bottom: 10px;
    color: #0077b6;
}

#contact a {
    color: #0077b6;
    text-decoration: none;
}

#contact a:hover {
    text-decoration: underline;
}

footer {
    background: #0077b6;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 40px;
}

```

## OUTPUT


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
