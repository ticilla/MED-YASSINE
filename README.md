<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HEEC Marrakech</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Barre de navigation -->
  <nav class="navbar"> 
    <div class="container">
      <a class="navbar-brand" href="#"><img src="https://ecoleheec.ma/wp-content/uploads/2019/04/logo-HEEC_Plan-de-travail-1.png" alt="Logo HEEC" class="logo"></a>
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="index.html"><i class="fas fa-home"></i> Accueil</a></li>
        <li class="nav-item"><a class="nav-link" href="#filieres"><i class="fas fa-graduation-cap"></i> Filières</a></li>
        <li class="nav-item"><a class="nav-link" href="inscription.html"><i class="fas fa-user-plus"></i> Inscriptions</a></li>
      </ul>
    </div>
  </nav>

  <!-- Section principale -->
  <section class="hero-section text-center py-5">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-6">
          <h1>Bienvenue à HEEC Marrakech</h1>
          <p class="my-4">Formation de qualité en informatique, intelligence artificielle et plus encore.</p>
          <a href="inscription.html" class="btn btn-primary btn-lg" id="inscrireButton" target="_blank"><i class="fas fa-user-plus"></i> S'inscrire maintenant</a>
        </div>
        <div class="col-6 d-flex justify-content-center">
          <img src="https://ecoleheec.ma/wp-content/uploads/2019/04/logo-HEEC_Plan-de-travail-1.png" alt="Logo HEEC" class="hero-image">
        </div>
      </div>
    </div>
  </section>
é
  <!-- Section des filières -->
  <section id="filieres" class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Nos Filières</h2>
      <div class="row">
        <div class="col-6">
          <div class="card p-3">
            <h3><i class="fas fa-laptop-code me-2"></i>INFORMATIQUE</h3>
          </div>
        </div>
        <div class="col-6">
          <div class="card p-3">
            <h3><i class="fas fa-brain me-2"></i>IAM</h3>
          </div>
        </div>
        <div class="col-6">
          <div class="card p-3">
            <h3><i class="fas fa-chart-bar me-2"></i>MANAGEMENT</h3>
          </div>
        </div>
        <div class="col-6">
          <div class="card p-3">
            <h3><i class="fas fa-code me-2"></i>MARKETING</h3>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Pied de page -->
  <footer class="footer py-3 text-center">
    <p>&copy; 2025 HEEC Marrakech | <i class="fas fa-map-marker-alt"></i> Avenue Hassan II, Guéliz, Marrakech | <i class="fas fa-phone"></i> 0524006852</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
