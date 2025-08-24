# Arianypnoz-
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Hypnothérapeute Ariane — Bien-être & Accompagnement</title>
  <meta name="description" content="Ariane, hypnothérapeute : accompagnement pour l'arrêt du tabac, gestion des migraines, perte de poids, addiction au sucre, phobies. Séances à distance et en cabinet." />
  <meta property="og:title" content="Hypnothérapeute Ariane" />
  <meta property="og:description" content="Arrêt du tabac, migraine, perte de poids, addiction au sucre, phobies." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1600&auto=format&fit=crop" />
  <meta name="theme-color" content="#6da3a1" />
  <style>
    :root{
      --bg:#f8fbfb; --fg:#1f2d2d; --muted:#647c7b; --brand:#6da3a1; --brand-dark:#48807e; --card:#ffffff; --accent:#f4f9f9;
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{margin:0; font-family: system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,'Helvetica Neue',Arial,'Noto Sans','Apple Color Emoji','Segoe UI Emoji'; color:var(--fg); background:var(--bg); line-height:1.6}
    a{color:var(--brand); text-decoration:none}
    a:hover{text-decoration:underline}
    .container{max-width:1100px; margin:0 auto; padding:0 20px}

    /* Header */
    header{position:sticky; top:0; z-index:20; background:rgba(255,255,255,.8); backdrop-filter:saturate(180%) blur(10px); border-bottom:1px solid #e6efef}
    .nav{display:flex; align-items:center; justify-content:space-between; padding:10px 0}
    .brand{display:flex; gap:10px; align-items:center; font-weight:700}
    .brand .logo{width:36px;height:36px;border-radius:10px;background:linear-gradient(135deg,var(--brand),#9ad1cf)}
    .nav a{font-weight:600; color:var(--fg)}
    .menu{display:flex; gap:18px}
    .cta{background:var(--brand); color:white; padding:10px 14px; border-radius:12px; border:0; font-weight:700}
    .cta:hover{background:var(--brand-dark)}

    /* Hero */
    .hero{position:relative; display:grid; grid-template-columns:1.1fr 0.9fr; gap:24px; padding:60px 0}
    .hero .text{padding:10px}
    .hero h1{font-size:clamp(28px,5vw,44px); line-height:1.15; margin:0 0 10px}
    .hero p{color:var(--muted); margin:0 0 18px}
    .hero .badges{display:flex; flex-wrap:wrap; gap:10px; margin:16px 0}
    .badge{background:var(--accent); border:1px solid #e6efef; border-radius:999px; padding:6px 12px; font-size:14px; color:var(--muted)}
    .hero .media{border-radius:20px; overflow:hidden; box-shadow:0 12px 40px rgba(0,0,0,.08)}
    .hero img{display:block; width:100%; height:100%; object-fit:cover}

    /* Sections */
    section{padding:60px 0}
    h2{font-size:clamp(22px,3.2vw,32px); margin:0 0 10px}
    .sub{color:var(--muted); margin:0 0 28px}

    /* Services */
    .grid{display:grid; grid-template-columns:repeat(3,1fr); gap:20px}
    @media (max-width:900px){.hero{grid-template-columns:1fr}.grid{grid-template-columns:repeat(2,1fr)}}
    @media (max-width:600px){.grid{grid-template-columns:1fr}}
    .card{background:var(--card); border:1px solid #e6efef; border-radius:18px; padding:18px; box-shadow:0 8px 24px rgba(0,0,0,.04)}
    .card h3{margin:6px 0 6px; font-size:20px}
    .card p{color:var(--muted); margin:0}
    .pill{display:inline-block; font-size:13px; color:#2c423f; background:#eaf6f5; border:1px solid #cee7e6; padding:4px 10px; border-radius:999px; margin-top:10px}
    .card img{width:100%; height:160px; object-fit:cover; border-radius:12px}

    /* List */
    .list{display:grid; gap:10px; color:var(--muted)}
    .list li{display:flex; gap:10px; align-items:flex-start}
    .check{width:18px; height:18px; flex:0 0 18px; margin-top:2px; color:var(--brand)}

    /* Pricing */
    .price{font-weight:800; font-size:24px}

    /* Testimonials */
    .quote{font-style:italic; color:#234; background:#eef7f6; border:1px solid #dff1f0; padding:18px; border-radius:14px}

    /* FAQ */
    details{background:var(--card); border:1px solid #e6efef; border-radius:14px; padding:14px 16px}
    details+details{margin-top:12px}
    summary{cursor:pointer; font-weight:700}

    /* Footer */
    footer{background:#0f1d1c; color:#cfe7e6; padding:26px 0; margin-top:20px}
    footer a{color:#cfe7e6}
    .footgrid{display:grid; grid-template-columns:1fr auto; gap:12px; align-items:center}
    .small{font-size:13px; color:#a8c7c5}

    /* Buttons */
    .btns{display:flex; flex-wrap:wrap; gap:12px}
    .btn{display:inline-flex; align-items:center; gap:8px; border:1px solid #d3e7e6; background:white; color:#144; padding:10px 14px; border-radius:12px; font-weight:700}
    .btn:hover{border-color:#b9d9d8}
    .btn.primary{background:var(--brand); color:white; border-color:transparent}

    /* Forms */
    form{display:grid; gap:12px}
    input, textarea{padding:12px 14px; border:1px solid #d4e7e6; border-radius:12px; font:inherit; background:white}
    label{font-weight:700}
  </style>

  <!-- JSON-LD for SEO -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "MedicalBusiness",
    "name": "Hypnothérapeute Ariane",
    "description": "Hypnothérapie : arrêt du tabac, migraine, perte de poids, addiction au sucre, phobies.",
    "url": "",
    "areaServed": "France",
    "availableService": ["Arrêt du tabac", "Gestion des migraines", "Perte de poids", "Addiction au sucre", "Phobies"],
    "logo": "",
    "image": "https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1600&auto=format&fit=crop"
  }
  </script>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand" aria-label="Hypnothérapeute Ariane">
        <div class="logo" role="img" aria-label="Logo"></div>
        <span>Ariane — Hypnothérapie</span>
      </div>
      <nav class="menu" aria-label="Navigation principale">
        <a href="#accueil">Accueil</a>
        <a href="#services">Prestations</a>
        <a href="#methode">Méthode</a>
        <a href="#tarifs">Tarifs</a>
        <a href="#faq">FAQ</a>
        <a href="#contact" class="cta" style="color:#fff">Prendre rendez‑vous</a>
      </nav>
    </div>
  </header>

  <main id="accueil" class="container hero">
    <div class="text">
      <h1>Retrouvez sérénité & clarté <br/>avec l'hypnose</h1>
      <p>Accompagnement personnalisé pour <strong>l'arrêt du tabac</strong>, la <strong>gestion des migraines</strong>, la <strong>perte de poids</strong>*, l'<strong>addiction au sucre</strong> et les <strong>phobies</strong>.</p>
      <div class="badges">
        <span class="badge">Séances en cabinet & à distance</span>
        <span class="badge">Approche bienveillante et brève</span>
        <span class="badge">Sur rendez‑vous</span>
      </div>
      <div class="btns">
        <a class="btn primary" href="#contact" aria-label="Prendre rendez-vous">Prendre rendez‑vous</a>
        <a class="btn" href="#services" aria-label="Voir les prestations">Voir les prestations</a>
      </div>
      <p class="small" style="margin-top:14px">* Si vous avez écrit « perte de tabac », cela correspond généralement à « perte de poids ». Modifiez le texte selon votre besoin précis.</p>
    </div>
    <div class="media" aria-hidden="true">
      <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1600&auto=format&fit=crop" alt="Ambiance apaisante, pierres et eau" />
    </div>
  </main>

  <section id="services">
    <div class="container">
      <h2>Prestations d'hypnothérapie</h2>
      <p class="sub">Des accompagnements ciblés, centrés sur un objectif clair et atteignable.</p>
      <div class="grid">
        <article class="card">
          <img src="https://images.unsplash.com/photo-1526045612212-70caf35c14df?q=80&w=1200&auto=format&fit=crop" alt="Arrêt du tabac" />
          <h3>Arrêt du tabac</h3>
          <p>Se libérer des automatismes, gérer les envies et retrouver une respiration libre.</p>
          <span class="pill">Programme court</span>
        </article>
        <article class="card">
          <img src="https://images.unsplash.com/photo-1517836357463-d25dfeac3438?q=80&w=1200&auto=format&fit=crop" alt="Gestion des migraines" />
          <h3>Migraine</h3>
          <p>Apprendre à moduler la perception et déployer des ressources de confort.</p>
          <span class="pill">Techniques de détente</span>
        </article>
        <article class="card">
          <img src="https://images.unsplash.com/photo-1506806732259-39c2d0268443?q=80&w=1200&auto=format&fit=crop" alt="Perte de poids" />
          <h3>Perte de poids</h3>
          <p>Rééquilibrer la relation à l'alimentation et installer de nouveaux repères.</p>
          <span class="pill">Comportements durables</span>
        </article>
        <article class="card">
          <img src="https://images.unsplash.com/photo-1483794344563-d27a8d18014e?q=80&w=1200&auto=format&fit=crop" alt="Addiction au sucre" />
          <h3>Addiction au sucre</h3>
          <p>Réduire les pulsions sucrées et retrouver une sensation de satiété naturelle.</p>
          <span class="pill">Gestion des envies</span>
        </article>
        <article class="card">
          <img src="https://images.unsplash.com/photo-1470167290877-7d5d3446de4c?q=80&w=1200&auto=format&fit=crop" alt="Phobies" />
          <h3>Phobies</h3>
          <p>Désensibilisation progressive pour reprendre confiance et liberté.</p>
          <span class="pill">Approche graduelle</span>
        </article>
        <article class="card">
          <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?q=80&w=1200&auto=format&fit=crop" alt="Séances à distance" />
          <h3>En présentiel ou à distance</h3>
          <p>Des séances flexibles, où que vous soyez.</p>
          <span class="pill">Visio sécurisée</span>
        </article>
      </div>
    </div>
  </section>

  <section id="methode">
    <div class="container">
      <h2>La méthode d'Ariane</h2>
      <p class="sub">Un cadre rassurant, une écoute active et des outils concrets pour favoriser l'autonomie.</p>
      <ul class="list" role="list">
        <li>
          <svg class="check" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M20 6L9 17l-5-5" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
          <div>
            <strong>Première séance</strong> : clarification de l'objectif, anamnèse courte, premières ressources.
          </div>
        </li>
        <li>
          <svg class="check" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M20 6L9 17l-5-5" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
          <div>
            <strong>Accompagnement</strong> : hypnose conversationnelle et techniques adaptées à votre rythme.
          </div>
        </li>
        <li>
          <svg class="check" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M20 6L9 17l-5-5" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
          <div>
            <strong>Autonomisation</strong> : stratégies concrètes et audios de pratique (optionnel).
          </div>
        </li>
      </ul>
    </div>
  </section>

  <section id="tarifs">
    <div class="container">
      <h2>Tarifs</h2>
      <p class="sub">Transparence et simplicité.</p>
      <div class="grid">
        <div class="card">
          <h3>Séance individuelle</h3>
          <p class="price">70 €</p>
          <p>Durée moyenne 1h à 1h15 — Présentiel ou visio.</p>
          <div class="btns" style="margin-top:10px">
            <a class="btn primary" href="#contact">Réserver une séance</a>
          </div>
        </div>
        <div class="card">
          <h3>Programme arrêt du tabac</h3>
          <p class="price">Forfait sur 2 à 3 séances</p>
          <p>Accompagnement ciblé avec supports entre séances.</p>
          <div class="btns" style="margin-top:10px">
            <a class="btn" href="#contact">Demander un devis</a>
          </div>
        </div>
        <div class="card">
          <h3>Entreprise & ateliers</h3>
          <p class="price">Sur mesure</p>
          <p>Qualité de vie au travail, gestion du stress, conférences.</p>
          <div class="btns" style="margin-top:10px">
            <a class="btn" href="#contact">Nous contacter</a>
          </div>
        </div>
      </div>
      <p class="small" style="margin-top:12px">L'hypnose ne remplace pas un avis médical. En cas de symptômes, consultez un professionnel de santé.</p>
    </div>
  </section>

  <section id="faq">
    <div class="container">
      <h2>FAQ</h2>
      <p class="sub">Vos questions les plus fréquentes.</p>
      <details>
        <summary>Combien de séances sont nécessaires ?</summary>
        <p>Selon l'objectif, entre 1 et 5 séances. L'accompagnement est bref et orienté résultat.</p>
      </details>
      <details>
        <summary>L'hypnose m'endort-elle ?</summary>
        <p>Non. Vous restez conscient·e et acteur·rice de tout le processus.</p>
      </details>
      <details>
        <summary>Faites-vous des séances à distance ?</summary>
        <p>Oui, en visio (lien envoyé lors de la prise de rendez-vous). Le cadre est expliqué en amont.</p>
      </details>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact & rendez‑vous</h2>
      <p class="sub">Réponse sous 24h ouvrées.</p>
      <div class="grid">
        <div class="card">
          <h3>Prenez contact</h3>
          <form action="mailto:contact@exemple.com" method="post" enctype="text/plain">
            <!-- Remplacez contact@exemple.com par votre e‑mail professionnel
                 Alternative : utilisez Formspree/Netlify Forms si vous préférez éviter mailto:. -->
            <label for="nom">Nom *</label>
            <input id="nom" name="Nom" required />
            <label for="email">Email *</label>
            <input id="email" name="Email" type="email" required />
            <label for="objet">Objet</label>
            <input id="objet" name="Objet" placeholder="Arrêt du tabac, migraine…" />
            <label for="message">Message *</label>
            <textarea id="message" name="Message" rows="5" required></textarea>
            <button class="cta" type="submit">Envoyer</button>
          </form>
        </div>
        <div class="card">
          <h3>Coordonnées</h3>
          <p><strong>Ariane — Hypnothérapeute</strong><br/>Adresse du cabinet (à compléter)<br/>75000 Paris</p>
          <p>Tél. <a href="tel:+33123456789">01 23 45 67 89</a><br/>Email <a href="mailto:contact@exemple.com">contact@exemple.com</a></p>
          <div class="btns">
            <a class="btn primary" href="tel:+33123456789">Appeler maintenant</a>
            <a class="btn" href="mailto:contact@exemple.com?subject=Prise%20de%20rendez-vous">Écrire un e‑mail</a>
          </div>
          <p class="small" style="margin-top:14px">Indiquez vos jours d'ouverture, moyens d'accès, et modalités de règlement ici.</p>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container footgrid">
      <div>
        <strong>Ariane — Hypnothérapeute</strong>
        <div class="small">© <span id="y"></span> • Tous droits réservés • Mentions légales à compléter</div>
      </div>
      <div class="small"><a href="#accueil">Haut de page ↑</a></div>
    </div>
  </footer>

  <script>
    // Mise à jour de l'année automatiquement
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
