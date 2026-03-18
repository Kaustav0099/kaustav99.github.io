<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Research Profile</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5f5f5;
    }

    .container {
      width: 95%;
      margin: auto;
    }

    /* Header */
    .header {
      border: 2px solid black;
      text-align: center;
      padding: 20px;
      margin: 20px 0;
      font-size: 28px;
      background: white;
    }

    /* Main Section */
    .main {
      display: flex;
      gap: 20px;
      margin-bottom: 30px;
    }

    .photo {
      flex: 1;
      border: 2px solid black;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 300px;
      background: white;
    }

    .description {
      flex: 3;
      border: 2px solid black;
      padding: 20px;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      background: white;
    }

    /* Papers Section */
    .papers {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 20px;
      margin-bottom: 30px;
    }

    .paper {
      border: 2px solid black;
      background: white;
      padding: 10px;
      text-align: center;
    }

    .paper img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      margin-bottom: 10px;
    }

    /* Footer */
    .footer {
      border: 2px solid black;
      text-align: center;
      padding: 20px;
      font-size: 20px;
      background: white;
    }

    /* Responsive */
    @media (max-width: 900px) {
      .main {
        flex-direction: column;
      }

      .papers {
        grid-template-columns: repeat(2, 1fr);
      }
    }

    @media (max-width: 500px) {
      .papers {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

  <div class="container">

    <!-- Header -->
    <div class="header">
      Heading of the page || Navigation bar
    </div>

    <!-- Main Section -->
    <div class="main">
      <div class="photo">
        <p>Photo of mine</p>
      </div>

      <div class="description">
        <p>Description of me and my research</p>
      </div>
    </div>

    <!-- Research Papers -->
    <div class="papers">
      <div class="paper">
        <img src="https://via.placeholder.com/300" alt="paper1">
        <p>Photo from my research paper-1 with description below</p>
      </div>

      <div class="paper">
        <img src="https://via.placeholder.com/300" alt="paper2">
        <p>Photo from my research paper-2 with description below</p>
      </div>

      <div class="paper">
        <img src="https://via.placeholder.com/300" alt="paper3">
        <p>Photo from my research paper-3 with description below</p>
      </div>

      <div class="paper">
        <img src="https://via.placeholder.com/300" alt="paper4">
        <p>Photo from my research paper-4 with description below</p>
      </div>
    </div>

    <!-- Footer -->
    <div class="footer">
      Contact: email | Twitter | LinkedIn
    </div>

  </div>

</body>
</html>
