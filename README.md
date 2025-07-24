/virtual-cv
│
├── index.html
├── style.css
└── script.js

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Virtual CV</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Jane Doe</h1>
    <p>Frontend Developer | UI/UX Designer</p>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>I’m a passionate developer with experience in HTML, CSS, and JavaScript. I build intuitive and beautiful interfaces.</p>
  </section>

  <section class="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML5 & CSS3</li>
      <li>JavaScript & React</li>
      <li>Git & GitHub</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Email: jane.doe@example.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Jane Doe</p>
  </footer>
  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f7f7f7;
  color: #333;
}

header, section, footer {
  padding: 20px;
  margin: 10px auto;
  max-width: 800px;
  background: white;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

h1, h2 {
  color: #007acc;
}
// Example: Display greeting based on time
const greeting = document.createElement("p");
const hour = new Date().getHours();

if (hour < 12) greeting.textContent = "Good morning!";
else if (hour < 18) greeting.textContent = "Good afternoon!";
else greeting.textContent = "Good evening!";

document.body.prepend(greeting);
