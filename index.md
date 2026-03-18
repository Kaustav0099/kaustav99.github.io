<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>My Research Page</title>

<style>

/* GENERAL */
body {
    margin: 0;
    font-family: "Segoe UI", Tahoma, sans-serif;
    background: #f5f7fa;
    color: #333;
}

/* NAVBAR */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 60px;
    background: white;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}

.navbar .name {
    font-size: 22px;
    font-weight: 500;
}

/* 👇 reduced font size here */
.navbar .links a {
    margin-left: 25px;
    text-decoration: none;
    color: #333;
    font-size: 16px;   /* smaller */
    font-weight: 500;
}

.navbar .links a:hover {
    color: #0077cc;
}

/* HEADER */
header {
    text-align: center;
    padding: 30px;
    font-size: 32px;
    font-weight: 600;
}

/* CONTAINER (FULL WIDTH FIX) */
.container {
    width: 95%;          /* 👈 increased from 85% */
    max-width: 1400px;   /* 👈 prevents too wide on big screens */
    margin: 0 auto;
}

/* PROFILE SECTION */
.profile {
    display: flex;
    gap: 60px;
    align-items: center;
    margin: 40px 0;
}

.profile img {
    width: 260px;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.profile-text {
    flex: 1;  /* 👈 makes it expand */
    background: white;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}

/* RESEARCH GRID */
.research-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    margin-top: 40px;
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
    margin-top: 60px;
    background: white;
    text-align: center;
    padding: 20px;
}

</style>

</head>

<body>

<header>
    My Research Page
</header>

<div class="container">

    <!-- PROFILE SECTION -->
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

    <!-- RESEARCH CARDS -->
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
