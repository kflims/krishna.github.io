<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Krishna Bhumbar - Video Editor Portfolio</title>
  
  <!-- Linking Google Fonts for Stylish Text -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500&family=Raleway:wght@300;400;600&display=swap" rel="stylesheet">
  
  <!-- Inline CSS -->
  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f7f7f7;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #ff6f61; /* Vibrant header color */
      color: #fff;
      padding: 1.5rem;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    header .logo {
      background: linear-gradient(135deg, #ff6f61, #ff4f3a); /* Gradient background for logo */
      padding: 20px;
      border-radius: 10px;
      display: inline-block;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    header .logo img {
      width: 400px;  /* Logo size increased 4 times */
      height: auto;
      display: block;
      margin: 0 auto;
      border-radius: 10px;
    }

    nav ul {
      list-style: none;
      padding: 0;
      margin-top: 20px;
    }

    nav ul li {
      display: inline;
      margin: 0 25px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 500;
      font-size: 1.1rem;
      letter-spacing: 1px;
    }

    nav ul li a:hover {
      color: #333;
    }

    section {
      padding: 3rem;
      max-width: 1200px;
      margin: 0 auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #333;
      font-family: 'Raleway', sans-serif;
      font-weight: 600;
    }

    p {
      font-size: 1.2rem;
      line-height: 1.7;
      color: #555;
      text-align: center;
      font-weight: 400;
      margin-bottom: 2rem;
    }

    #portfolio .portfolio-items {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 25px;
      margin-top: 30px;
    }

    .portfolio-item {
      text-align: center;
      background-color: #fff;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      padding: 15px;
      border-radius: 15px;
      transition: all 0.3s ease;
      max-width: 350px;
      width: 100%;
    }

    .portfolio-item:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
    }

    .portfolio-item video {
      width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .portfolio-item h3 {
      margin-top: 15px;
      color: #333;
      font-weight: 500;
    }

    .button {
      display: inline-block;
      padding: 15px 25px;
      background-color: #ff6f61;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: 500;
      font-size: 1.1rem;
      margin-top: 20px;
      transition: background-color 0.3s ease;
    }

    .button:hover {
      background-color: #ff4f3a;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #333;
      color: #fff;
      position: fixed;
      width: 100%;
      bottom: 0;
    }

    /* Upload Section Styling */
    .upload-section {
      background-color: #ffebeb; /* Soft background for upload section */
      border-radius: 10px;
      padding: 20px;
      margin-top: 30px;
      text-align: center;
    }

    .upload-section input[type="file"] {
      padding: 10px;
      border: 2px solid #ff6f61;
      border-radius: 5px;
      font-size: 1rem;
      color: #333;
    }

    .upload-section button {
      padding: 12px 25px;
      background-color: #ff6f61;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1.1rem;
      margin-top: 20px;
    }

    .upload-section button:hover {
      background-color: #ff4f3a;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <div class="logo">
      <!-- Replace with your own logo image -->
      <img src="kfilms logo w.png" alt="Krishna Bhumbar Logo">
    </div>
    <nav>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#upload">Upload</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- About Me Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Welcome to my portfolio! I’m Krishna Bhumbar, a passionate video editor with 4 years of experience bringing stories to life through dynamic editing, seamless transitions, and creative storytelling. Explore my work and let's collaborate on your next project!</p>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio-items">
      <!-- Video 1 -->
      <div class="portfolio-item">
        <video width="320" height="240" controls>
          <source src="sample_video1.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <h3>Project 1</h3>
      </div>

      <!-- Video 2 -->
      <div class="portfolio-item">
        <video width="320" height="240" controls>
          <source src="sample_video2.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <h3>Project 2</h3>
      </div>
    </div>
    <div style="text-align:center;">
      <a href="#upload" class="button">Upload Your Video</a>
    </div>
  </section>

  <!-- File Upload Section -->
  <section id="upload" class="upload-section">
    <h2>Upload Sample Video</h2>
    <p>Click the button below to select a video from your device and upload it to my portfolio.</p>
    <form action="upload.php" method="post" enctype="multipart/form-data">
      <label for="fileUpload">Choose a file to upload:</label>
      <input type="file" name="file" id="fileUpload" accept=".mp4, .mov, .avi" required>
      <button type="submit" name="submit">Upload</button>
    </form>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <p>If you'd like to work together or have any questions, feel free to reach out!</p>
    <ul>
      <li>Email: <a href="mailto:kfilms510@gmail.com">kfilms510@gmail.com</a></li>
      <li>Phone: <a href="tel:+917620769641">7620769641</a></li>
    </ul>
  </section>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2025 Krishna Bhumbar. All Rights Reserved.</p>
  </footer>

</body>
</html>
