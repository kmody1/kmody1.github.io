<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>My Basic Website</title>
  <style>
    /* Basic optional styling - you can remove or modify as needed */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header, nav, main, footer {
      padding: 20px;
      margin: 0 auto;
      max-width: 900px;
    }
    header {
      background-color: #f4f4f4;
    }
    nav ul {
      list-style: none;
      padding: 0;
    }
    nav li {
      display: inline-block;
      margin-right: 10px;
    }
    nav a {
      text-decoration: none;
      color: #333;
    }
    footer {
      background-color: #f4f4f4;
      text-align: center;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1>Welcome to My Basic Website</h1>
  </header>

  <!-- Navigation Menu -->
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Main Content -->
  <main>
    <section id="about">
      <h2>About</h2>
      <p>
        This is a simple website demonstrating basic HTML structure. You can customize the content, style, and structure to fit your needs.
      </p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>
        Email: <a href="mailto:example@example.com">example@example.com</a><br />
        Phone: <a href="tel:123-456-7890">123-456-7890</a>
      </p>
    </section>
  </main>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2025 My Basic Website</p>
  </footer>
</body>
</html>
