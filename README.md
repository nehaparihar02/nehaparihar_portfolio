<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Neha Parihar - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      color: #333;
      background-color: #f5f5f5;
    }

    header {
      background: #06eaf8;
      color: rgb(9, 1, 1);
      padding: 40px 20px;
      text-align: center;
    }

    nav {
      background: #34495e;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #000408;
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
    }

    .projects, .skills, .certification, .interest, .language, .hobbies
    {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .project, .skill, .certification, .interest, .language, .hobbies
    {
      flex: 1 1 300px;
      background: #d2fbfd;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 8px;
    }

    footer 
    {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
    }

    a
    {
      color: #2980b9;
    }

    @media (max-width: 600px)
    {
    .projects, .skills, .certification, .interest, .language, .hobbies
      {
        flex-direction: column;
      }
    }
    
      form {
        width: 300px;
        margin: auto;
      }
      input[type="text"], input[type="email"], input[type="password"] {
        width: 100%;
        padding: 10px;
        margin: 8px 0;
        box-sizing: border-box;
      }
      input[type="submit"] {
        background-color: #4CAF50;
        color: white;
        border: none;
        padding: 10px;
        width: 100%;
        cursor: pointer;
      }
      input[type="submit"]:hover {
        background-color: #45a049;
      }
      .error {
        color: red;
        font-size: 0.9em;
      }
  </style>
</head>
<body>
  
  

  <header>
    <h1>NEHA PARIHAR</h1>
    <p>IT ENGINEER |  #travelwithnushi | @aqua_oyster </p>
  </header>

  <nav>

    <a href="#about">About</a>

    <a href="#projects">Projects</a>

    <a href="#skills">Skills</a>

    <a href="#certification">Certification</a>

    <a href="#interest">Interest</a>

    <a href="#language">Language</a>

    <a href="#hobbies">Hobbies</a>

    <a href="#contact">Contact</a>

    <a href="#registration">Registration</a>

  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
An IT engineer with certification in cloud computing & virtualisation seeking for a position of cloud/software/research engineer.
Also, I'm running a travelblog on Instagram.    
</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
      <div class="project">
        <h3>Project One</h3>
        <p>Portfolio Website - Web Development</p>
        <a href="#">View Project</a>
      </div>
      <div class="project">
        <h3>Project Two</h3>
        <p>Raspberry pi - Python Programming</p>
      </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
      <div class="skill">Team Work</div>
      <div class="skill">Sales & Marketing</div>
      <div class="skill">Presentation</div>
      <div class="skill">Project Lead</div>
      <div class="skill">Research Analyst</div>
      <div class="skill">Volunteering</div>
  </section>

  <section id="certification">
    <h2>Certification</h2>
      <div class="certification">Web Development</div>
      <div class="certification">Programming in C & Data Structure</div>
      <div class="certification">GPOS, Shell Scripting & System Programming</div>
      <div class="certification">Raspberry Pi with Python Programming</div>
      <div class="certification">Introduction to R code</div>
      <div class="certification">Cloud Computing & DevOps</div>
  </section>

  <section id="interest">
    <h2>Interest</h2>
      <div class="interest">Research</div>
      <div class="interest">Data Science</div>
      <div class="interest">Artificial intelligence</div>
      <div class="interest">Case studies</div>
  </section>


  <section id="language">
    <h2>Language</h2>
      <div class="language">English</div>
      <div class="language">Hindi</div>
    </div>
  </section>

  <section id="hobbies">
    <h2>Hobbies</h2>
      <div class="hobbies">Writing</div>
      <div class="hobbies">Reading</div>
      <div class="hobbies">Painting</div>
      <div class="hobbies">Photography</div>
      <div class="hobbies">Crafting</div>
      <div class="hobbies">Badminton</div>
      <div class="hobbies">Table tennis</div>
      <div class="hobbies">Travelling</div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="https://aquaoyster2@gmail.com" target="_blank">aquaoyster2@gmail.com</a></p>
    <p>GitHub: <a href="https://github.com/nehaparihar02" target="_blank">github.com/nehaparihar02</a></p>
    <p>LinkedIn: <a href="http://linkedin.com/in/nehapa02" target="_blank">linkedin.com/in/nehapa02</a></p>
    <p>Instagram: <a href="https://www.instagram.com/aqua_oyster/" target="_blank">www.instagram.com/aqua_oyster/</a></p>
    <p>Address: Udaipur, Rajasthan, INDIA (313001)</p>
  </section>

  <section id="registration">
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 50px;
      }
      form {
        width: 300px;
        margin: auto;
      }
      input[type="text"], input[type="email"], input[type="password"] {
        width: 100%;
        padding: 10px;
        margin: 8px 0;
        box-sizing: border-box;
      }
      input[type="submit"] {
        background-color: #4CAF50;
        color: white;
        border: none;
        padding: 10px;
        width: 100%;
        cursor: pointer;
      }
      input[type="submit"]:hover {
        background-color: #45a049;
      }
      .error {
        color: red;
        font-size: 0.9em;
      }
    </style>

<h2>Registration Form</h2>

<form id="registrationForm" onsubmit="return validateForm()">
  <label for="name">Full Name:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <label for="password">Password:</label>
  <input type="password" id="password" name="password" required>

  <label for="confirmPassword">Confirm Password:</label>
  <input type="password" id="confirmPassword" name="confirmPassword" required>

  <div id="error" class="error"></div>

  <input type="submit" value="Register">
</form>

<script>
  function validateForm() {
    const name = document.getElementById("name").value.trim();
    const email = document.getElementById("email").value.trim();
    const password = document.getElementById("password").value;
    const confirmPassword = document.getElementById("confirmPassword").value;
    const errorDiv = document.getElementById("error");
    errorDiv.innerHTML = ""; // Clear previous errors



    if (name.length < 3) {
      errorDiv.innerHTML = "Name must be at least 3 characters long.";
      return false;
    }

    const emailPattern = /^[^ ]+@[^ ]+\.[a-z]{2,3}$/;
    if (!email.match(emailPattern)) {
      errorDiv.innerHTML = "Please enter a valid email address.";
      return false;
    }

    if (password.length < 6) {
      errorDiv.innerHTML = "Password must be at least 6 characters long.";
      return false;
    }

    if (password !== confirmPassword) {
      errorDiv.innerHTML = "Passwords do not match.";
      return false;
    }

    alert("Registration successful!");
    return true;
  }
</script>

  </section>


  <footer>
    <p>&copy; 2025 Neha Parihar. All rights reserved.</p>
  </footer>

</body>
</html>

