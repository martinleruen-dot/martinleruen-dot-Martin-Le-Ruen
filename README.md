<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Martin Le Ruen - Profile</title>
  <meta name="description" content="Page de profil de Martin Le Ruen. Étudiant à l'IÉSEG et professionnel du marketing digital.">
  
  <!-- Importation de Font Awesome pour des icônes au rendu impeccable -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  
  <!-- Lien vers la feuille de style externe -->
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Le container centralise et cadre l'ensemble de la page -->
  <div class="container">
    
    <!-- Carte 1 : Identité & Présentation -->
    <div class="card-white">
      <h1>Hello, I'm Martin 😎</h1>
      <!-- Remplace "ma-photo.jpg" par le nom de ton fichier image réel dans ton dépôt -->
      <img src="ma-photo.jpg" alt="Martin Le Ruen" class="img-circle">
      <p>
        Actuellement étudiant en Master à l'IÉSEG School of Management, j'évolue dans le secteur du marketing digital et du business development. Passionné par la tech, j'apprends le développement web pour maîtriser les leviers techniques de l'animation e-commerce et optimiser l'expérience utilisateur !
      </p>
      <a href="https://www.lewagon.com" target="_blank" class="btn-purple">Discover Le Wagon</a>
    </div>

    <!-- Carte 2 : Expérience Professionnelle -->
    <div class="card-white">
      <h2>E-commerce & Digital Marketing 🚀</h2>
      <p>
        Au sein des équipes e-commerce chez Lacoste, je participe activement à la gestion du catalogue en ligne, à l'optimisation des pages de listes de produits (PLP) et au déploiement des campagnes d'animation commerciale sur les différents marchés.
      </p>
    </div>

    <!-- Carte 3 : Projet Majeur / Recherche -->
    <div class="card-white">
      <h2>Master's Thesis & Research 📚</h2>
      <p>
        J'ai récemment mené un travail de recherche approfondi appliqué au cas de Lacoste, analysant comment adapter l'animation e-commerce aux spécificités des marchés européens tout en garantissant une image de marque cohérente. Cette étude s'appuie sur une méthodologie qualitative rigoureuse comprenant 20 entretiens approfondis.
      </p>
    </div>

    <!-- Carte 4 : Passions & Sports -->
    <div class="card-white">
      <h2>Sports & Hobbies 🏃‍♂️🎾</h2>
      <p>
        Grand passionné de tennis, je suis de très près l'actualité des grands tournois du Grand Chelem comme Roland-Garros et Wimbledon. Côté terrain, j'aime le dépassement de soi et je m'entraîne régulièrement pour des courses à pied de 10km.
      </p>
    </div>

    <!-- Carte 5 : Liens et Réseaux Sociaux -->
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
      </ul>
    </div>

  </div>

</body>
</html>
/* --- 1. PARAMÈTRES GÉNÉRAUX DU SITE --- */
body {
  background-color: #F4F6F9; /* Un gris-bleu très doux et moderne pour le fond */
  color: rgb(45, 45, 45);    /* Un texte sombre mais moins agressif que le noir pur */
  font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  font-size: 16px;
  line-height: 1.7;          /* Espacement de ligne confortable pour la lecture */
  margin: 0;
  padding: 0;
}

/* --- 2. TYPOGRAPHIE & TITRES --- */
h1 {
  font-size: 34px;
  font-weight: 700;
  color: #111111;
  margin-top: 10px;
  margin-bottom: 20px;
}

h2 {
  font-size: 22px;
  font-weight: 600;
  color: #1A1A1A;
  margin-bottom: 12px;
}

p {
  color: rgb(90, 90, 90);
  font-size: 15.5px;
  font-weight: 400;
  margin-bottom: 25px;
}

/* --- 3. ALIGNEMENT ET BLOCS (CONTAINER & CARDS) --- */
.container {
  width: 600px;        /* Largeur idéale pour une lecture fluide sur ordinateur */
  margin: 50px auto;   /* Centre parfaitement le bloc verticalement et horizontalement */
  padding: 0 15px;     /* Sécurité pour les petits écrans */
}

.card-white {
  background: #FFFFFF;
  padding: 40px;
  border-radius: 8px;  /* Angles légèrement plus arrondis pour un look moderne */
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05); /* Ombre très douce et diffuse */
  margin-bottom: 25px;
  text-align: center;  /* Centre l'intégralité des éléments à l'intérieur de la carte */
}

/* --- 4. STYLE DES COMPOSANTS (AVATAR & BOUTON VIOLET) --- */
.img-circle {
  width: 130px;
  height: 130px;
  border-radius: 50%;   /* Forme un cercle parfait */
  object-fit: cover;    /* Empêche la déformation de la photo */
  margin-bottom: 15px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.btn-purple {
  display: inline-block;
  background-color: #5D5FEF; /* Le violet emblématique de l'exercice */
  color: #FFFFFF;
  padding: 14px 28px;
  border-radius: 6px;
  font-weight: 600;
  text-decoration: none;
  letter-spacing: 0.5px;
  transition: all 0.3s ease; /* Transition animée pour le survol */
}

.btn-purple:hover {
  background-color: #4B4DDC; /* Teinte plus intense au survol */
  color: #FFFFFF;
  text-decoration: none;
  transform: translateY(-1px); /* Léger effet de surélévation dynamique */
}

/* --- 5. STYLE DE LA LISTE VERTICALE DES RÉSEAUX --- */
.list-vertical {
  list-style: none; /* Nettoie les puces par défaut */
  padding-left: 0;
  margin: 20px 0 0 0;
}

.list-vertical li {
  margin: 14px 0; /* Espacement vertical aéré entre les réseaux */
}

.list-vertical a {
  color: #5D5FEF;
  text-decoration: none;
  font-size: 17px;
  font-weight: 500;
  transition: color 0.2s ease;
}

.list-vertical a:hover {
  color: #4B4DDC;
  text-decoration: underline; /* Souligné élégant au survol */
}

.list-vertical i {
  margin-right: 10px; /* Espace précis entre le logo du réseau et son texte */
  font-size: 19px;
}
