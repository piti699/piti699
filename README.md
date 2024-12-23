<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Trendy Website</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Montserrat:wght@700&display=swap" rel="stylesheet">
  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #121212;
      color: #ffffff;
      line-height: 1.6;
      margin: 0;
    }

    h1, h2 {
      font-family: 'Montserrat', sans-serif;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Header Styles */
    header {
      background: linear-gradient(45deg, #1d1f21, #2c2f38);
      padding: 20px;
      text-align: center;
    }

    header h1 {
      color: #ffffff;
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      color: #ccc;
      font-size: 1rem;
    }

    /* Navigation Styles */
    nav {
      display: flex;
      justify-content: center;
      background-color: #1d1f21;
      padding: 15px;
    }

    nav a {
      color: #f1f1f1;
      margin: 0 15px;
      font-weight: 500;
      text-transform: uppercase;
      letter-spacing: 1px;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ff7e5f;
    }

    /* Main Content Styles */
    section {
      padding: 40px 20px;
      text-align: center;
    }

    .feature {
      display: flex;
      justify-content: center;
      margin-top: 30px;
      gap: 30px;
      flex-wrap: wrap;
    }

    .feature-item {
      background: #2c2f38;
      border-radius: 8px;
      padding: 20px;
      width: 30%;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .feature-item:hover {
      transform: translateY(-10px);
      box-shadow: 0 6px 10px rgba(0, 0, 0, 0.2);
    }

    .feature-item h2 {
      margin-bottom: 1rem;
      color: #ff7e5f;
      font-size: 1.5rem;
    }

    .feature-item p {
      color: #ccc;
      font-size: 1rem;
    }

    /* Footer Styles */
    footer {
      background: #1d1f21;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    footer p {
      color: #999;
      font-size: 0.9rem;
    }

    /* Dark Mode Styles */
    body.dark-mode {
      background-color: #1e1e1e;
    }

    body.dark-mode header {
      background: linear-gradient(45deg, #2c2f38, #1d1f21);
    }

    body.dark-mode footer {
      background: #2c2f38;
    }

    /* Button */
    .btn {
      background-color: #ff7e5f;
      padding: 10px 20px;
      color: white;
      border-radius: 50px;
      font-weight: 500;
      text-transform: uppercase;
      letter-spacing: 1px;
      cursor: pointer;
      border: none;
      transition: background-color 0.3s ease;
    }

    .btn:hover {
      background-color: #f6a5b1;
    }

  </style>
</head>
<body>
  <header>
    <h1>Welcome to Trendy Web</h1>
    <p>Stay ahead with modern web design and features.</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Features</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <section>
    <h2>Our Features</h2>
    <div class="feature">
      <div class="feature-item">
        <h2>Modern Design</h2>
        <p>Experience sleek and minimalistic layouts with a modern touch.</p>
      </div>
      <div class="feature-item">
        <h2>Interactive UI</h2>
        <p>Engage users with smooth animations and interactive elements.</p>
      </div>
      <div class="feature-item">
        <h2>Mobile Friendly</h2>
        <p>Your content looks great on every device, from mobile to desktop.</p>
      </div>
    </div>

    <button class="btn" onclick="toggleDarkMode()">Toggle Dark Mode</button>
  </section>

  <footer>
    <p>&copy; 2024 Trendy Web | All Rights Reserved</p>
  </footer>

  <script>
    // Dark Mode Toggle Functionality
    function toggleDarkMode() {
      document.body.classList.toggle('dark-mode');
    }
  </script>
</body>
</html>

<!---
piti699/piti699 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
