<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Vocabulario of Life</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #4a90e2;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    .dictionary {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 30px 20px;
    }
    .entry {
      display: flex;
      align-items: center;
      background: white;
      border-radius: 10px;
      margin: 15px 0;
      padding: 15px;
      width: 90%;
      max-width: 600px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    .entry img {
      width: 100px;
      height: 100px;
      border-radius: 10px;
      object-fit: cover;
      margin-right: 20px;
    }
    .entry-text {
      flex: 1;
    }
    .entry-text h3 {
      margin: 0 0 5px;
    }
    footer {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>The Vocabulario of Life</h1>
    <p>Discover and understand English words through images and simple explanations.</p>
  </header>

  <section class="dictionary">
    <!-- Palabra 1 -->
    <div class="entry">
      <img src="https://via.placeholder.com/100" alt="Sun" />
      <div class="entry-text">
        <h3>Sun</h3>
        <p>The star at the center of our solar system that gives us light and heat.</p>
      </div>
    </div>

    <!-- Palabra 2 -->
    <div class="entry">
      <img src="https://via.placeholder.com/100" alt="Tree" />
      <div class="entry-text">
        <h3>Tree</h3>
        <p>A large plant with a trunk, branches, and leaves, often found in forests.</p>
      </div>
    </div>

    <!-- Palabra 3 -->
    <div class="entry">
      <img src="https://via.placeholder.com/100" alt="Book" />
      <div class="entry-text">
        <h3>Book</h3>
        <p>A collection of pages with written or printed text used to read or learn.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>Website created as an educational tool to help understand English vocabulary with visual support. All rights reserved © 2025.</p>
  </footer>
</body>
</html>
