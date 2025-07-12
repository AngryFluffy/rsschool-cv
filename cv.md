<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sergei Boichenko CV</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #eadedd;
      color: #0d3e56;
      display: flex;
      justify-content: center;
      padding: 40px 0;
    }

    .container {
      width: 90%;
      max-width: 1000px;
      background-color: white;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
      display: grid;
      grid-template-columns: 280px 1fr;
      border-radius: 12px;
      overflow: hidden;
    }

    .sidebar {
      background-color: #941a14;
      color: white;
      padding: 30px 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .photo {
      width: 200px;
      height: 200px;
      background-color: #eadedd;
      border-radius: 10px;
      margin-bottom: 20px;
      background-size: cover;
      background-position: center;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    }

    .sidebar h2 {
      margin-top: 0;
      color: #e35d24;
      font-size: 1.8em;
      margin-bottom: 10px;
    }

    .sidebar p, .sidebar a {
      font-size: 1em;
      color: #f0eaea;
      margin: 5px 0;
      text-align: center;
    }

    .sidebar a {
      color: #3ba1ae;
      text-decoration: none;
    }

    .content {
      padding: 40px 30px;
      background-color: #f7f4f3;
    }

    h1 {
      color: #941a14;
      font-size: 2.2em;
      margin-bottom: 10px;
    }

    h2 {
      color: #0d3e56;
      border-left: 6px solid #941a14;
      padding-left: 10px;
      margin-top: 30px;
      font-size: 1.4em;
    }

    code {
      background-color: #eee;
      display: block;
      padding: 15px;
      border-radius: 6px;
      font-family: Consolas, monospace;
      margin-bottom: 10px;
      white-space: pre;
    }

    .section {
      margin-bottom: 25px;
      line-height: 1.6;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="sidebar">
      <div class="photo">
        <!-- Место под фото -->
      </div>
      <h2>Sergei Boichenko</h2>
      <p>Discord: @angry_fluffydfy</p>
      <p><a href="https://github.com/AngryFluffy" target="_blank">My GitHub profile</a></p>
      <p>boichenkosergei@gmail.com</p>
    </div>
    <div class="content">
      <h1>Welcome to My CV</h1>

      <div class="section">
        <h2>About Me</h2>
        <p>I want to learn a new profession. There is a desire to learn and learn something new.</p>
      </div>

      <div class="section">
        <h2>Skills</h2>
        <p>I don't know any programming languages.</p>
      </div>

      <div class="section">
        <h2>Code Example</h2>
        <code>
function multiply(a, b) {
  return a * b;
}
        </code>
      </div>

      <div class="section">
        <h2>CV Link</h2>
        <p><a href="https://github.com/AngryFluffy/rsschool-cv/blob/gh-pages/cv.md" target="_blank">My CV</a></p>
      </div>

      <div class="section">
        <h2>Education</h2>
        <p>Higher technical education in automotive engineering.</p>
      </div>

      <div class="section">
        <h2>English Level</h2>
        <p>A2 Pre-intermediate</p>
      </div>
    </div>
  </div>
</body>
</html>