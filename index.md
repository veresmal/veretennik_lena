<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Index Page</title>
  <style>
    /* Menu Ribbon Styling */
    .menu {
      background-color: #333; /* Dark background */
      display: flex;
      justify-content: center;
      padding: 15px 0;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2); /* Subtle shadow for depth */
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    .menu a {
      color: white; /* White text for contrast */
      text-decoration: none;
      margin: 0 20px;
      font-size: 18px;
      font-family: Arial, sans-serif;
      font-weight: 600;
      padding: 5px 10px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    .menu a:hover {
      background-color: #555; /* Slightly lighter background on hover */
    }
    /* Page content */
    .content {
      margin: 20px;
      font-family: Arial, sans-serif;
    }
  </style>
</head>
<body>
  <!-- Menu Ribbon -->
  <div class="menu">
    <a href="index.md">Home</a>
    <a href="cv">CV</a>
    <a href="research.md">Research</a>
  </div>

  <!-- Page Content -->
  <div class="content">
    <h1>Welcome to My Homepage</h1>
    <div style="display: flex; align-items: flex-start; margin-top: 20px;">
      <img src="./photo_cv.jpg" alt="Lena Veretennik" style="width: 150px; height: auto; margin-right: 20px;">
      <div>
        <p>
          I am a Doctoral Student at KU Leuven’s Faculty of Economics and Business (the Department of Management, Strategy and Innovation), specializing in innovation networks, knowledge transfer, and the economics of science.
        </p>
        <p>
          With a decade of experience spanning consulting, research, and teaching, my work bridges academia and industry by leveraging advanced big data analytics and social network analysis. Currently, I am investigating how interpersonal ties between inventors and authors shape innovation, knowledge exchange, and collaboration in different industries.
        </p>
        <ul>
          <li><a href="./cv_veretennik_2024.pdf">CV</a></li>
          <li><a href="./research.md">Research</a></li>
        </ul>
      </div>
    </div>
  </div>
</body>
</html>
