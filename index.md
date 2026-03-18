<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Kaustav Mondal | Research</title>

<style>

/* RESET */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* BODY */
body {
    font-family: "Segoe UI", Tahoma, sans-serif;
    background: #f5f7fa;
    color: #333;
}

/* NAVBAR (ONLY ONE) */
.navbar {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 40px;   /* reduced side padding */
    background: white;
    box-shadow: 0 2px 6px rgba(0,0,0,0.05);
}

.navbar .name {
    font-size: 20px;
    font-weight: 500;
}

.navbar .links a {
    margin-left: 20px;
    text-decoration: none;
    color: #333;
    font-size: 15px;   /* smaller */
    font-weight: 500;
}

.navbar .links a:hover {
    color: #0077cc;
}

/* HEADER */
header {
    text-align: center;
    padding: 30px 10px;
    font-size: 32px;
    font-weight: 600;
}

/* CONTAINER (FULL WIDTH FIX) */
.container {
    width: 100%;           /* 👈 FULL WIDTH */
    max-width: 1200px;     /* 👈 controlled width */
    margin: auto;
    padding: 0 20px;       /* 👈 small side padding */
}

/* PROFILE */
.profile {
    display: flex;
    gap: 50px;
    align-items: center;
    margin: 40px 0;
}

.profile img {
    width: 260px;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.profile-text {
    flex: 1;
    background: white;
    padding: 25px;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}

.profile-text h2 {
    margin-bottom: 10px;
}

/* GRID */
.research-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
    margin-top: 30px;
}

.card {
    background: white;
    padding: 15px;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

.card img {
    width: 100%;
    border-radius: 10px;
}

/* FOOTER */
footer {
    margin-top: 50px;
    background: white;
    text-align: center;
    padding: 20px;
}

</style>
</head>

<body>

<!-- ONLY NAVBAR -->
<div class="navbar">
    <div class="name">Kaustav Mondal</div>
    <div class="links">
        <a href="#">Research</a>
        <a href="#">Publications</a>
        <a href="#">Teaching</a>
    </div>
</div>

<header>
    My Research Page
</header>

<div class="container">

    <div class="profile">
        <img src="assets/profile.jpg" alt="My Photo">

        <div class="profile-text">
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
            in active and passive systems.
            </p>
        </div>
    </div>

    <div class="research-grid">

        <div class="card">
            <img src="assets/work1.jpg">
            <p>Active-passive particle simulations and clustering behavior.</p>
        </div>

        <div class="card">
            <img src="assets/work2.jpg">
            <p>Rod-like particle dynamics and anisotropic interactions.</p>
        </div>

        <div class="card">
            <img src="assets/work3.jpg">
            <p>Stochastic modeling and nonequilibrium systems.</p>
        </div>

        <div class="card">
            <img src="assets/work4.jpg">
            <p>Biofilm and bacterial colony simulations.</p>
        </div>

    </div>

</div>

<footer>
    Contact: your.email@example.com | Twitter | LinkedIn
</footer>

</body>
</html>
