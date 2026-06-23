# martinleruen-dot-Martin-Le-Ruen
Rattrapage du cours Développement Front-End 1293 - Page de profil et Landing Page.
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Mon Profil - Martin Le Ruen</title>
  <meta name="description" content="Page de profil de Martin Le Ruen pour le cours Développement Front-End.">
  
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="container">
    
    <div class="card-white">
      <h1>Hello, I'm Martin 😎</h1>
      <img src="ma-photo.jpg" alt="Photo de Martin Le Ruen" class="img-circle">
      <p>
        Étudiant en Master à l'IÉSEG et alternant en e-commerce chez Lacoste, 
        j'adore découvrir le développement web et apprendre à coder avec Le Wagon !
      </p>
      <a href="https://www.lewagon.com" target="_blank" class="btn-purple">Discover Le Wagon</a>
    </div>

    <div class="card-white">
      <h2>UX/UI & E-commerce 📐</h2>
      <p>I am passionate about UX/UI Design and digital merchandising.</p>
    </div>

    <div class="card-white">
      <h2>Frontend Development 💻</h2>
      <p>I am passionate about Frontend Development and building clean web pages.</p>
    </div>

    <div class="card-white">
      <h2>Sports & Running 🏃‍♂️</h2>
      <p>I am passionate about tennis and training for 10km running races.</p>
    </div>

    <div class="card-white">
      <h2>Follow me</h2>
      <ul class="list-vertical">
        <li>
          <a href="https://github.com/Martin-Le-Ruen" target="_blank">
            <i class="fab fa-github"></i> GitHub
          </a>
        </li>
        <li>
          <a href="https://linkedin.com/" target="_blank">
            <i class="fab fa-linkedin-in"></i> LinkedIn
          </a>
        </li>
        <li>
          <a href="https://twitter.com/" target="_blank">
            <i class="fab fa-twitter"></i> Twitter
          </a>
        </li>
      </ul>
    </div>

  </div>

</body>
</html>
/* --- 1. DESIGN GLOBAL & DESIGN DU BODY --- */
body {
  background-color: #F3F4F6; /* Fond gris clair comme sur le modèle */
  color: rgb(30, 30, 30);
  font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  font-size: 16px;
  margin: 0;
  padding: 0;
}

/* --- 2. TYPOGRAPHIE DES TITRES & TEXTES --- */
h1 {
  font-size: 32px;
  font-weight: bold;
  color: #111;
  margin-bottom: 20px;
}

h2 {
  font-size: 20px;
  font-weight: bold;
  color: #222;
  margin-bottom: 10px;
}

p {
  color: rgb(100, 100, 100);
  margin-bottom: 20px;
  font-weight: 300;
}

/* --- 3. STRUCTURE DES DIVS (CONTAINER & CARDS) --- */
.container {
  width: 550px;       /* Largeur idéale pour le rendu de profil centré */
  margin: 40px auto;  /* Centre automatiquement le bloc sur la page */
}

.card-white {
  background: white;
  padding: 40px;
  border-radius: 4px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.08); /* Ombre légère et élégante */
  margin-bottom: 20px;
  text-align: center; /* Aligne TOUT le contenu au centre de la carte */
}

/* --- 4. DESIGN DES ÉLÉMENTS (AVATAR & BOUTON) --- */
.img-circle {
  width: 120px;
  height: 120px;
  border-radius: 50%;   /* Arrondit parfaitement l'image en cercle */
  object-fit: cover;
  margin-bottom: 15px;
}

.btn-purple {
  display: inline-block;
  background-color: #5D5FEF; /* Couleur violette identique au bouton du Wagon */
  color: white;
  padding: 12px 24px;
  border-radius: 4px;
  font-weight: bold;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.btn-purple:hover {
  background-color: #4B4DDC;
  color: white;
  text-decoration: none;
}

/* --- 5. DESIGN DE LA LISTE DE RÉSEAUX (VERTICALE) --- */
.list-vertical {
  list-style: none; /* Enlève les puces d'origine */
  padding-left: 0px; 
  margin: 20px 0 0 0;
}

.list-vertical li {
  margin: 12px 0; /* Espace vertical entre chaque réseau */
}

.list-vertical a {
  color: #5D5FEF;
  text-decoration: none;
  font-size: 18px;
  font-weight: 500;
  transition: color 0.3s ease;
}

.list-vertical a:hover {
  color: #4B4DDC;
  text-decoration: underline;
}

/* Espacement pour les icônes à l'intérieur des liens */
.list-vertical i {
  margin-right: 8px;
  font-size: 18px;
}
