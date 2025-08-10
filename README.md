<!--
Project: Site vitrine industriel/tech — 5 pages
Structure (all files included below):
- index.html
- about.html
- services.html
- projects.html
- contact.html
- assets/style.css
- assets/script.js
- README.md (déploiement GitHub Pages)

Instructions: copiez ces fichiers dans un repo GitHub et activez GitHub Pages (branche main / dossier root) pour publier gratuitement.
-->

<!-- FILE: index.html -->
<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Nom Entreprise — Accueil</title>
  <meta name="description" content="Entreprise industrielle / tech — solutions & projets" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="assets/style.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="brand" href="index.html">ENTREPRISE</a>
      <nav class="nav">
        <a href="about.html">À propos</a>
        <a href="services.html">Services</a>
        <a href="projects.html">Projets</a>
        <a href="contact.html" class="cta">Contact</a>
      </nav>
      <button class="nav-toggle" aria-label="menu">☰</button>
    </div>
  </header>

  <main>
    <section class="hero">
      <img class="hero-bg" src="https://source.unsplash.com/1600x900/?industrial,machinery,tech" alt="Industrie">
      <div class="container hero-content">
        <h1>Solutions industrielles & technologiques</h1>
        <p>Conception, intégration et optimisation — des systèmes robustes, pensés pour l’avenir.</p>
        <p class="hero-actions"><a href="services.html" class="btn">Nos services</a> <a href="#contact" class="btn ghost">Devis gratuit</a></p>
      </div>
    </section>

    <section class="features container">
      <article>
        <h3>Ingénierie sur mesure</h3>
        <p>Conception complète — du cahier des charges à la mise en service.</p>
      </article>
      <article>
        <h3>Automatisation & IoT</h3>
        <p>Capteurs, supervision, données temps réel pour piloter vos opérations.</p>
      </article>
      <article>
        <h3>Maintenance prédictive</h3>
        <p>Réduction des pannes et optimisation du ROI grâce à l’analyse des données.</p>
      </article>
    </section>

    <section class="projects-teaser">
      <div class="container">
        <h2>Projets récents</h2>
        <div class="project-grid">
          <figure>
            <img src="https://source.unsplash.com/600x400/?factory,robot" alt="projet1">
            <figcaption>Ligne automatisée — client A</figcaption>
          </figure>
          <figure>
            <img src="https://source.unsplash.com/600x400/?warehouse,automation" alt="projet2">
            <figcaption>Système de supervision — client B</figcaption>
          </figure>
          <figure>
            <img src="https://source.unsplash.com/600x400/?control,room" alt="projet3">
            <figcaption>Contrôle qualité connecté — client C</figcaption>
          </figure>
        </div>
        <p class="center"><a href="projects.html" class="btn ghost">Voir tous les projets</a></p>
      </div>
    </section>

    <section id="contact" class="contact-cta">
      <div class="container">
        <h2>Prêt à démarrer ?</h2>
        <p>Contactez-nous pour une étude gratuite et un devis personnalisé.</p>
        <p><a href="contact.html" class="btn">Contact</a></p>
      </div>
    </section>

  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> Nom Entreprise — Tous droits réservés</p>
      <nav class="footer-nav">
        <a href="privacy.html">Politique de confidentialité</a>
      </nav>
    </div>
  </footer>

  <script src="assets/script.js"></script>
</body>
</html>


<!-- FILE: about.html -->
<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>À propos — Nom Entreprise</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="assets/style.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="brand" href="index.html">ENTREPRISE</a>
      <nav class="nav">
        <a href="about.html">À propos</a>
        <a href="services.html">Services</a>
        <a href="projects.html">Projets</a>
        <a href="contact.html" class="cta">Contact</a>
      </nav>
      <button class="nav-toggle" aria-label="menu">☰</button>
    </div>
  </header>

  <main class="container">
    <section class="content-block">
      <h1>Notre histoire</h1>
      <p>Fondée par des ingénieurs passionnés, notre entreprise fournit des solutions industrielles de pointe. Nous combinons savoir-faire mécanique, électrique et logiciel pour créer des systèmes fiables et évolutifs.</p>
    </section>

    <section class="team">
      <h2>Équipe</h2>
      <div class="team-grid">
        <div class="card"><img src="https://source.unsplash.com/300x300/?engineer,portrait" alt="membre"><h4>Jean Dupont</h4><p>Directeur technique</p></div>
        <div class="card"><img src="https://source.unsplash.com/300x300/?technician,portrait" alt="membre"><h4>Lucie Martin</h4><p>Responsable projet</p></div>
        <div class="card"><img src="https://source.unsplash.com/300x300/?developer,portrait" alt="membre"><h4>Samir K.</h4><p>Ingénieur logiciel</p></div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year2"></span> Nom Entreprise — Tous droits réservés</p>
    </div>
  </footer>
  <script src="assets/script.js"></script>
</body>
</html>


<!-- FILE: services.html -->
<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Services — Nom Entreprise</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="assets/style.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="brand" href="index.html">ENTREPRISE</a>
      <nav class="nav">
        <a href="about.html">À propos</a>
        <a href="services.html">Services</a>
        <a href="projects.html">Projets</a>
        <a href="contact.html" class="cta">Contact</a>
      </nav>
      <button class="nav-toggle" aria-label="menu">☰</button>
    </div>
  </header>

  <main class="container">
    <h1>Nos services</h1>
    <div class="services-grid">
      <article class="service-card">
        <h3>Conception & ingénierie</h3>
        <p>Études, prototypes et industrialisation.</p>
      </article>
      <article class="service-card">
        <h3>Automatisation</h3>
        <p>Automates, SCADA, robotique et intégration.</p>
      </article>
      <article class="service-card">
        <h3>Intégration IoT</h3>
        <p>Capteurs, passerelles et tableaux de bord.</p>
      </article>
      <article class="service-card">
        <h3>Support & maintenance</h3>
        <p>Contrats, télémaintenance et formation.</p>
      </article>
    </div>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year3"></span> Nom Entreprise — Tous droits réservés</p>
    </div>
  </footer>
  <script src="assets/script.js"></script>
</body>
</html>


<!-- FILE: projects.html -->
<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Projets — Nom Entreprise</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="assets/style.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="brand" href="index.html">ENTREPRISE</a>
      <nav class="nav">
        <a href="about.html">À propos</a>
        <a href="services.html">Services</a>
        <a href="projects.html">Projets</a>
        <a href="contact.html" class="cta">Contact</a>
      </nav>
      <button class="nav-toggle" aria-label="menu">☰</button>
    </div>
  </header>

  <main class="container">
    <h1>Réalisations</h1>
    <div class="project-list">
      <section class="project">
        <img src="https://source.unsplash.com/800x500/?assembly,line" alt="proj1">
        <div>
          <h3>Ligne d'assemblage automatisée</h3>
          <p>Déploiement complet pour une usine agroalimentaire — gains de productivité de 37%.</p>
        </div>
      </section>

      <section class="project">
        <img src="https://source.unsplash.com/800x500/?control,system" alt="proj2">
        <div>
          <h3>Système de supervision multi-site</h3>
          <p>Plateforme centralisée de monitoring et reporting en temps réel.</p>
        </div>
      </section>

      <section class="project">
        <img src="https://source.unsplash.com/800x500/?robotics,factory" alt="proj3">
        <div>
          <h3>Cellule robotisée pour assemblage</h3>
          <p>Intégration robotique sur chaîne existante, sécurité et conformité ISO.</p>
        </div>
      </section>
    </div>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year4"></span> Nom Entreprise — Tous droits réservés</p>
    </div>
  </footer>
  <script src="assets/script.js"></script>
</body>
</html>


<!-- FILE: contact.html -->
<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Contact — Nom Entreprise</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="assets/style.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="brand" href="index.html">ENTREPRISE</a>
      <nav class="nav">
        <a href="about.html">À propos</a>
        <a href="services.html">Services</a>
        <a href="projects.html">Projets</a>
        <a href="contact.html" class="cta">Contact</a>
      </nav>
      <button class="nav-toggle" aria-label="menu">☰</button>
    </div>
  </header>

  <main class="container">
    <h1>Contact</h1>
    <div class="contact-grid">
      <form class="contact-form" method="POST" action="https://formspree.io/f/your-form-id">
        <label>Nom<input type="text" name="name" required></label>
        <label>Email<input type="email" name="email" required></label>
        <label>Société<input type="text" name="company"></label>
        <label>Message<textarea name="message" rows="6" required></textarea></label>
        <button class="btn" type="submit">Envoyer</button>
      </form>

      <aside class="contact-info">
        <h3>Infos</h3>
        <p>Téléphone: +33 1 23 45 67 89</p>
        <p>Email: contact@entreprise.example</p>
        <p>Adresse: 12 Rue Industrielle, 75000 Paris</p>
        <h4>Horaires</h4>
        <p>Lun - Ven: 9h - 18h</p>
      </aside>
    </div>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year5"></span> Nom Entreprise — Tous droits réservés</p>
    </div>
  </footer>
  <script src="assets/script.js"></script>
</body>
</html>


<!-- FILE: assets/style.css -->
:root{
  --bg:#0d0f12; /* near black */
  --panel:#121519;
  --muted:#9aa3ad;
  --accent:#2dd4ff; /* cyan */
  --accent-2:#6ee7b7; /* mint */
  --glass: rgba(255,255,255,0.04);
  --container:1200px;
  font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
}
*{box-sizing:border-box}
html,body{height:100%}
body{margin:0;background:linear-gradient(180deg,var(--bg),#070809);color:#e6eef3;line-height:1.5}
.container{max-width:var(--container);margin:0 auto;padding:2rem}
.header-inner{display:flex;align-items:center;justify-content:space-between}
.brand{font-weight:800;letter-spacing:1px;color:var(--accent);text-decoration:none}
.nav{display:flex;gap:1rem}
.nav a{color:var(--muted);text-decoration:none;padding:.25rem .5rem}
.nav a.cta{border:1px solid rgba(255,255,255,0.06);padding:.5rem .75rem;border-radius:8px;color:#fff}
.nav-toggle{display:none;background:transparent;border:0;color:#fff;font-size:1.25rem}
.site-header{backdrop-filter: blur(6px);position:sticky;top:0;background:linear-gradient(180deg,rgba(0,0,0,0.35),transparent);z-index:50}
.hero{position:relative;min-height:62vh;display:flex;align-items:center}
.hero-bg{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;filter:grayscale(.15) contrast(1.05) saturate(.9);opacity:.85}
.hero-content{position:relative;padding:4rem 2rem;max-width:900px}
.hero h1{font-size:clamp(2rem,4vw,3rem);margin:0 0 .5rem}
.hero p{color:var(--muted)}
.btn{display:inline-block;background:linear-gradient(90deg,var(--accent),var(--accent-2));color:#051019;padding:.6rem 1rem;border-radius:8px;text-decoration:none;font-weight:600}
.btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:#fff}
.features{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1.25rem;padding:3rem 0}
.features article{background:var(--panel);padding:1.25rem;border-radius:12px}
.projects-teaser{padding:3rem 0}
.project-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1rem}
.project-grid figure{background:var(--glass);border-radius:10px;overflow:hidden}
.project-grid img{width:100%;height:160px;object-fit:cover;display:block}
.center{text-align:center}
.contact-cta{background:linear-gradient(180deg,transparent,rgba(255,255,255,0.02));padding:3rem 0}
.site-footer{padding:2rem 0;background:transparent;color:var(--muted);border-top:1px solid rgba(255,255,255,0.03)}
.team-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:1rem}
.card{background:var(--panel);padding:1rem;border-radius:10px;text-align:center}
.card img{width:100%;height:160px;object-fit:cover;border-radius:8px}
.services-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1rem}
.service-card{background:rgba(255,255,255,0.02);padding:1.25rem;border-radius:10px}
.project-list{display:grid;gap:1.5rem}
.project{display:grid;grid-template-columns:1fr 1fr;gap:1rem;align-items:center}
.project img{width:100%;height:220px;object-fit:cover;border-radius:8px}
.contact-grid{display:grid;grid-template-columns:1fr 320px;gap:2rem}
.contact-form{background:var(--panel);padding:1rem;border-radius:10px}
.contact-form label{display:block;margin-bottom:.75rem;color:var(--muted)}
.contact-form input,.contact-form textarea{width:100%;padding:.6rem;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:#fff}
.contact-info{background:rgba(255,255,255,0.02);padding:1rem;border-radius:10px}
@media (max-width:900px){
  .nav{display:none}
  .nav-toggle{display:block}
  .project{grid-template-columns:1fr}
  .contact-grid{grid-template-columns:1fr}
}

/* small utilities */
.center{text-align:center}


/* EOF */


<!-- FILE: assets/script.js -->
(function(){
  // small UX: year, nav toggle
  document.getElementById('year')?.appendChild(document.createTextNode(new Date().getFullYear()));
  document.getElementById('year2')?.appendChild(document.createTextNode(new Date().getFullYear()));
  document.getElementById('year3')?.appendChild(document.createTextNode(new Date().getFullYear()));
  document.getElementById('year4')?.appendChild(document.createTextNode(new Date().getFullYear()));
  document.getElementById('year5')?.appendChild(document.createTextNode(new Date().getFullYear()));

  document.querySelectorAll('.nav-toggle').forEach(btn=>{
    btn.addEventListener('click',()=>{
      const nav = document.querySelector('.nav');
      if(!nav) return;
      nav.style.display = nav.style.display === 'flex' ? 'none' : 'flex';
    })
  })
})();


<!-- FILE: README.md -->
# Déploiement - GitHub Pages

1. Crée un nouveau dépôt GitHub (par ex. `nomentreprise-site`).
2. Place tous les fichiers fournis à la racine du repo en respectant l'arborescence (`assets/` ...).
3. Commit et push sur la branche `main`.
4. Dans les settings du repo -> Pages -> Source : `main` branch / root -> Save.
5. Après quelques minutes, ton site sera disponible sur `https://<ton-nom-utilisateur>.github.io/<nomrepo>/`.

Pour une URL racine sans `<nomrepo>`, crée un repo nommé exactement `tonnomutilisateur.github.io` et pousse les fichiers dessus.

### Notes utiles
- Remplace `https://formspree.io/f/your-form-id` dans `contact.html` par ton endpoint Formspree (gratuit) ou un autre service de formulaire.
- Pour lier un domaine personnalisé, vas dans Settings -> Pages -> Custom domain et suis les instructions (ajout d'un enregistrement A / CNAME chez ton registrar).
- Si tu veux que je te fournisse directement un .zip prêt à uploader, dis-le-moi.


<!-- EOF -->
