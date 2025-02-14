# username.github
git clone https://github.com/username/username.github.io

username.github.io/
├── index.html          # Homepage
├── about.html          # About Me page
├── projects.html       # Projects page
├── resume.html         # Resume page
├── contact.html        # Contact page
├── styles/             # Folder for CSS files
│   └── style.css
├── scripts/            # Folder for JavaScript files
│   └── main.js
├── assets/             # Folder for images, PDFs, etc.
│   ├── profile.jpg
│   └── resume.pdf
└── README.md

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Data Analyst</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Data Analyst | Transforming Data into Actionable Insights</p>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="projects.html">Projects</a></li>
            <li><a href="resume.html">Resume</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    <section id="home">
        <h2>Welcome to My Portfolio</h2>
        <p>I am a data analyst passionate about uncovering insights from data.</p>
    </section>
    <footer>
        <p>&copy; 2023 Your Name</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}
header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}
nav {
    background: #444;
    color: #fff;
    padding: 1rem;
    text-align: center;
}
nav ul {
    list-style: none;
    padding: 0;
}
nav ul li {
    display: inline;
    margin: 0 10px;
}
nav ul li a {
    color: #fff;
    text-decoration: none;
}
section {
    padding: 2rem;
}
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

git add .

git commit -m "Initial commit"

git push origin main
