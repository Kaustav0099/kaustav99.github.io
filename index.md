<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>My Research Page</title>

<style>
body {
    margin: 0;
    font-family: "Segoe UI", Tahoma, sans-serif;
    background: #f5f7fa;
    color: #333;
}

/* HEADER */
header {
    text-align: center;
    padding: 40px 20px;
    background: white;
    font-size: 32px;
    font-weight: 600;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}

/* MAIN SECTION */
.container {
    width: 85%;
    margin: 40px auto;
}

/* PROFILE SECTION */
.profile {
    display: flex;
    gap: 40px;
    align-items: center;
    margin-bottom: 60px;
}

.profile img {
    width: 220px;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.profile-text {
    background: white;
    padding: 25px;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}

/* RESEARCH CARDS */
.research-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
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

.card p {
    font-size: 14px;
    margin-top: 10px;
}

/* FOOTER */
footer {
    margin-top: 60px;
    background: white;
    text-align: center;
    padding: 25px;
    box-shadow: 0 -2px 8px rgba(0,0,0,0.05);
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
