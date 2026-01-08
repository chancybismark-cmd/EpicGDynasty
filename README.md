<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>EpicDynasty – Jeux PC & Epic Games</title>
<meta name="description" content="EpicDynasty propose des jeux PC et Epic Games avec accès VIP aux jeux rares">
<meta name="author" content="YANCLO Bismark">
<meta name="robots" content="index, follow">
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <h1>🎮 EpicDynasty</h1>
  <p>Jeux PC & Epic Games</p>
</header>

<nav>
  <a href="index.html">Accueil</a>
  <a href="jeux.html">Jeux gratuits</a>
  <a href="jeux-vip.html">Jeux VIP</a>
</nav>

<section class="hero">
  <h2>Bienvenue sur EpicDynasty</h2>
  <p>Télécharge des jeux PC et Epic Games, découvre les VIP rares !</p>
</section>

<footer>
  <p>Créé par YANCLO Bismark</p>
</footer>

<!-- StatCounter pour savoir qui visite -->
<script type="text/javascript">
var sc_project=12345678;
var sc_invisible=1;
var sc_security="abcd1234";
</script>
<script src="https://www.statcounter.com/counter/counter.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Jeux gratuits – EpicDynasty</title>
<meta name="robots" content="index, follow">
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <h1>Jeux Epic Games gratuits</h1>
</header>

<section class="games">
  <div class="game-card">
    <img src="fortnite.jpg" alt="Fortnite">
    <h3>Fortnite</h3>
    <p>Battle Royale intense</p>
    <span class="badge">Gratuit</span>
    <a href="https://store.epicgames.com/fr/p/fortnite" target="_blank">Télécharger</a>
  </div>

  <div class="game-card">
    <img src="rocketleague.jpg" alt="Rocket League">
    <h3>Rocket League</h3>
    <p>Voitures & football</p>
    <span class="badge">Gratuit</span>
    <a href="https://store.epicgames.com/fr/p/rocket-league" target="_blank">Télécharger</a>
  </div>
</section>

<footer>
  <p>Créé par YANCLO Bismark</p>
</footer>
<script src="https://www.statcounter.com/counter/counter.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Jeux VIP – EpicDynasty</title>
<meta name="robots" content="index, follow">
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <h1>Zone VIP 🔒</h1>
</header>

<section class="games">
  <div class="game-card">
    <img src="alanwake.jpg" alt="Alan Wake">
    <h3>Alan Wake Remastered</h3>
    <p>Jeu rare</p>
    <span class="badge">1000 FCFA</span>
    <a href="vip.html">Accès VIP requis</a>
  </div>

  <div class="game-card">
    <img src="metroexodus.jpg" alt="Metro Exodus">
    <h3>Metro Exodus</h3>
    <p>FPS survie</p>
    <span class="badge">1000 FCFA</span>
    <a href="vip.html">Accès VIP requis</a>
  </div>

  <div class="game-card">
    <img src="jeu500.jpg" alt="Jeu moins rare">
    <h3>Jeu Moins Rare</h3>
    <p>Accessible à tous</p>
    <span class="badge">500 FCFA</span>
    <a href="vip.html">Accès VIP requis</a>
  </div>
</section>

<footer>
  <p>Créé par YANCLO Bismark</p>
</footer>
<script src="https://www.statcounter.com/counter/counter.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Pass VIP – EpicDynasty</title>
<meta name="robots" content="index, follow">
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <h1>👑 Pass VIP</h1>
</header>

<section class="hero">
  <h2>Accès aux jeux rares</h2>
  <p>Prix : 500 FCFA (moins rares) / 1000 FCFA (rares)</p>
  <p>MTN Mobile Money : <strong>0153311061</strong></p>
</section>

<footer>
  <p>Créé par YANCLO Bismark</p>
</footer>
<script src="https://www.statcounter.com/counter/counter.js"></script>
</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Orbitron&display=swap');

body {
  margin: 0;
  font-family: 'Orbitron', sans-serif;
  background: linear-gradient(135deg, #0a0f1e, #020617, #0a0f1e);
  color: white;
}

header {
  background: #020617;
  padding: 25px;
  text-align: center;
  box-shadow: 0 0 20px #22c55e;
}

nav {
  position: fixed;
  top: 0;
  width: 100%;
  background: #020617;
  padding: 15px;
  text-align: center;
  z-index: 1000;
  box-shadow: 0 2px 10px #22c55e;
}

nav a {
  color: #facc15;
  margin: 10px;
  text-decoration: none;
}

.hero {
  padding: 30px;
  text-align: center;
  margin-top: 60px;
}

.games {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  padding: 20px;
}

.game-card {
  background: #020617;
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 0 15px #22c55e;
  transition: 0.3s;
}

.game-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 0 25px #22c55e;
}

.game-card a {
  display: inline-block;
  margin-top: 10px;
  background: #22c55e;
  color: black;
  padding: 8px 15px;
  border-radius: 8px;
  text-decoration: none;
  transition: 0.3s;
}

.game-card a:hover {
  background: #facc15;
  transform: scale(1.05);
}

.badge {
  display: inline-block;
  background: #facc15;
  color: black;
  padding: 3px 8px;
  border-radius: 5px;
  font-size: 0.8em;
  margin-bottom: 5px;
}

footer {
  background: #020617;
  padding: 15px;
  text-align: center;
  color: #9ca3af;
}

/* Responsive */
@media (max-width: 600px) {
  .games {
    grid-template-columns: 1fr;
  }
  nav a {
    display: block;
    margin: 5px 0;
  }
}
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url><loc>https://chancybismark-cmd.github.io/EpicDynasty/</loc></url>
  <url><loc>https://chancybismark-cmd.github.io/EpicDynasty/jeux.html</loc></url>
  <url><loc>https://chancybismark-cmd.github.io/EpicDynasty/jeux-vip.html</loc></url>
  <url><loc>https://chancybismark-cmd.github.io/EpicDynasty/vip.html</loc></url>
</urlset>
User-agent: *
Allow: /
Sitemap: https://chancybismark-cmd.github.io/EpicDynasty/sitemap.xml
