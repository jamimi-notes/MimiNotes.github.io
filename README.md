<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home | My Website</title>
  <link rel="stylesheet" href="css/mystyles.css">
</head>
<body>
  <header>
    <h1 class="site-title">Welcome to My Website</h1>
    <nav class="navbar">
      <ul>
        <li><a href="contact.html">Contact Us</a></li>
        <li><a href="developer.html">Developer</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="reviewer.html">Reviewer</a></li>
      </ul>
    </nav>
  </header>
<styles>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Title Styling */
.site-title {
  font-family: 'Times New Roman', Times, serif;
  font-size: 2.5rem;
  text-align: center;
  margin: 20px 0;
  color: #333;
}

/* Navigation Bar */
.navbar {
  background-color: #333;
  padding: 10px 0;
}

.navbar ul {
  list-style: none;
  display: flex;
  justify-content: center;
}

.navbar li {
  margin: 0 15px;
}

.navbar a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.navbar a:hover {
  text-decoration: underline;
}

/* Boxes Layout */
.box-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding: 20px;
  gap: 20px;
}

.box {
  background-color: #f0f0f0;
  width: 150px;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none;
  color: #333;
  border: 2px solid #ccc;
  border-radius: 8px;
  transition: background-color 0.3s, transform 0.2s;
}

.box:hover {
  background-color: #e0e0e0;
  transform: scale(1.05);
}
  
</styles>
  <main class="box-container">
    <a class="box" href="https://example1.com" target="_blank">Box 1</a>
    <a class="box" href="https://example2.com" target="_blank">Box 2</a>
    <a class="box" href="https://example3.com" target="_blank">Box 3</a>
    <a class="box" href="https://example4.com" target="_blank">Box 4</a>
    <a class="box" href="https://example5.com" target="_blank">Box 5</a>
    <a class="box" href="https://example6.com" target="_blank">Box 6</a>
  </main>
</body>
</html>
