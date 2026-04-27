# Ex01 Portfolio
## Date:27.04.2026

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portfolio - Tarunika D</title>

  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>

<body>

<!-- NAVBAR -->
<nav>
  <h2 class="logo">TD</h2>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<header>
  <div class="hero">
    <h1>Hi, I'm <span>Tarunika D</span></h1>
    <p>Engineering Student | Aspiring Software Developer</p>
    <a href="#projects" class="btn">View My Work</a>
  </div>
</header>

<!-- ABOUT -->
<section id="about">
  <h2>About Me</h2>
  <p>
    I am an Engineering student with a strong interest in programming, data science, 
    and web development. I enjoy solving problems, building projects, and continuously 
    improving my technical skills.
  </p>
    <img src="c:\Users\admin\Downloads\TARUNIKA D.jpeg" alt="Profile Image" width="150">
</section>

<!-- SKILLS -->
<section id="skills">
  <h2>Skills</h2>
  <div class="grid">
    <div class="card">
      <h3>Java</h3>
      <p>OOP concepts, strings, recursion</p>
    </div>
    <div class="card">
      <h3>Web Development</h3>
      <p>HTML, CSS, basic frontend design</p>
    </div>
    <div class="card">
      <h3>Data Science</h3>
      <p>Basic analytics and machine learning</p>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <h2>Projects</h2>
  <div class="grid">
    <div class="card">
      <h3>Portfolio Website</h3>
      <p>Personal portfolio built using HTML and CSS</p>
    </div>
    <div class="card">
      <h3>kalasaarthi</h3>
      <p>Machine learning project using classification techniques and implemented as a online shopping app</p>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2>Contact: +91 8610730085</h2>
  <p>Email: tarunikadamod@gmail.com</p>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 Tarunika D | Portfolio</p>
</footer>

</body>
</html>
```

style.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
}

header {
    background-color: black;
    color: white;
    padding: 15px;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

a {
    color: white;
    text-decoration: none;
}

a:hover {
    color: yellow;
}

section {
    padding: 40px;
}

#home {
    background-color: #f4f4f4;
    text-align: center;
}

#about {
    background-color: #e2e2e2;
}

#projects {
    background-color: #d0d0d0;
}

#contact {
    background-color: #c0c0c0;
}

.project {
    background: white;
    padding: 15px;
    margin-top: 10px;
}
```
## OUTPUT
<img width="1898" height="790" alt="output-1 exp-1" src="https://github.com/user-attachments/assets/8d25b0b7-57ad-4f9c-8b2a-2a44810f1a84" />

<img width="1912" height="906" alt="o-2 exp-1" src="https://github.com/user-attachments/assets/f3ef1a09-7b80-4335-b7ab-4749099448ee" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
