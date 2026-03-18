<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kaustav Mondal | Research</title>

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

/* CONTAINER */
.container {
  width: 95%;
  margin: auto;
}


/* MAIN SECTION */
.main {
  display: flex;
  gap: 30px;
  margin-bottom: 30px;
  align-items: center;
}

/* PHOTO (NO BOX, BIGGER) */
.photo {
  flex: 1.2;
  display: flex;
  align-items: center;
  justify-content: center;
}

.photo img {
  width: 100%;
  max-width: 320px;
  border-radius: 10px;
}

/* DESCRIPTION */
.description {
  flex: 3;
  border: 2px solid black;
  padding: 20px;
  background: white;
}

.description h2 {
  margin-bottom: 10px;
}

.description ul {
  margin: 10px 0 10px 20px;
}

/* PAPERS */
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
  transition: 0.3s;
}

.paper:hover {
  transform: translateY(-5px);
}

.paper img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  margin-bottom: 10px;
}

/* FOOTER */
.footer {
  border: 2px solid black;
  text-align: center;
  padding: 20px;
  font-size: 16px;
  background: white;
}

/* RESPONSIVE */
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



  <!-- MAIN SECTION -->
  <div class="main">

    <!-- PHOTO -->
    <div class="photo">
      <img src="assets/profile.jpg" alt="My Photo">
    </div>

    <!-- DESCRIPTION -->
    <div class="description">
      <h2>PhD Student in Statistical Physics and Complex Systems</h2>

      <p>
        My research focuses on active matter, nonequilibrium statistical mechanics,
        and particle-based simulations.
      </p>

      <ul>
        <li>Active matter</li>
        <li>Particle simulations</li>
        <li>Bacterial colony modelling</li>
      </ul>

      <p>
        I develop computational models to study emergent collective behavior
        in active and passive particle systems.
      </p>
    </div>

  </div>

  <!-- PAPERS -->
  <div class="papers">

    <div class="paper">
      <a href="https://github.com/your-username/project1" target="_blank">
        <img src="assets/work1.jpg" alt="">
        <p>Active-passive particle simulations and clustering behavior</p>
      </a>
    </div>

    <div class="paper">
      <a href="https://github.com/your-username/project2" target="_blank">
        <img src="assets/work2.jpg" alt="">
        <p>Rod-like particle dynamics and anisotropic interactions</p>
      </a>
    </div>

    <div class="paper">
      <a href="https://github.com/your-username/project3" target="_blank">
        <img src="assets/work3.jpg" alt="">
        <p>Stochastic modeling and nonequilibrium systems</p>
      </a>
    </div>

    <div class="paper">
      <a href="https://github.com/your-username/project4" target="_blank">
        <img src="assets/work4.jpg" alt="">
        <p>Biofilm and bacterial colony simulations</p>
      </a>
    </div>

  </div>

  <!-- FOOTER -->
  <div class="footer">
    Contact: your.email@example.com |
    <a href="#">Twitter</a> |
    <a href="#">LinkedIn</a>
  </div>

</div>

</body>
</html>
