[portfolio-khelifi (3).html](https://github.com/user-attachments/files/33487701/portfolio-khelifi.3.html)
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Abderrahmène Khelifi — Portfolio BTS SIO SISR</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=Source+Sans+3:wght@400;600&display=swap">
<style>
:root{
  --bg:#eef2f6; --surface:#ffffff; --ink:#14202b; --muted:#4a5a6a; --line:#cfd8e1;
  --accent:#1f4fd8; --accent-ink:#ffffff; --tag:#dde7fb; --ph:#fff4d6; --ph-ink:#6b4e00;
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){
    --bg:#0f1720; --surface:#17222e; --ink:#e8eef4; --muted:#9db0c2; --line:#2a3a4a;
    --accent:#7aa2ff; --accent-ink:#0f1720; --tag:#22385f; --ph:#3a3112; --ph-ink:#f2d98a;
  }
}
:root[data-theme="dark"]{
  --bg:#0f1720; --surface:#17222e; --ink:#e8eef4; --muted:#9db0c2; --line:#2a3a4a;
  --accent:#7aa2ff; --accent-ink:#0f1720; --tag:#22385f; --ph:#3a3112; --ph-ink:#f2d98a;
}
*,*::before,*::after{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:calc(64px + env(safe-area-inset-top,0px))}
body{margin:0;background:var(--bg);color:var(--ink);font:400 17px/1.6 "Source Sans 3",system-ui,-apple-system,"Segoe UI",sans-serif}
h1,h2,h3{font-family:"Bricolage Grotesque","Trebuchet MS",system-ui,sans-serif;line-height:1.15;margin:0}
a{color:var(--accent)}
:focus-visible{outline:3px solid var(--accent);outline-offset:3px}
.wrap{max-width:1000px;margin:0 auto;padding:0 20px}
header.nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:20;background:var(--surface);border-bottom:1px solid var(--line)}
.nav .wrap{display:flex;align-items:center;justify-content:space-between;gap:16px;min-height:64px}
.brand{font-family:"Bricolage Grotesque",sans-serif;font-weight:800;text-decoration:none;color:var(--ink)}
.nav ul{display:flex;gap:4px;list-style:none;margin:0;padding:0;overflow-x:auto}
.nav li a{display:block;padding:8px 12px;border-radius:8px;text-decoration:none;color:var(--muted);font-weight:600;white-space:nowrap}
.nav li a:hover{background:var(--tag);color:var(--ink)}
.hero{padding:72px 0 56px}
.hero h1{font-size:clamp(2.6rem,9vw,5.5rem);font-weight:800;letter-spacing:-.02em}
.hero .role{font-size:1.4rem;color:var(--accent);font-weight:600;margin:12px 0 20px;font-family:"Bricolage Grotesque",sans-serif}
.hero p{max-width:60ch;color:var(--muted)}
.btns{display:flex;flex-wrap:wrap;gap:12px;margin-top:28px}
.btn{display:inline-block;padding:12px 20px;border-radius:10px;font-weight:600;text-decoration:none;border:2px solid var(--accent)}
.btn.primary{background:var(--accent);color:var(--accent-ink)}
.btn.ghost{color:var(--accent)}
.facts{display:flex;flex-wrap:wrap;gap:28px;margin-top:40px;padding-top:24px;border-top:1px solid var(--line)}
.facts div{min-width:110px}
.facts strong{display:block;font:800 1.6rem "Bricolage Grotesque",sans-serif}
.facts span{color:var(--muted);font-size:.95rem}
section{padding:56px 0;border-top:1px solid var(--line)}
section>.wrap>h2{font-size:clamp(1.8rem,5vw,2.4rem);margin-bottom:8px}
.lead{color:var(--muted);max-width:62ch;margin:0 0 28px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:16px}
.card{background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:20px}
.card h3{font-size:1.15rem;margin-bottom:8px}
.card p{margin:0;color:var(--muted)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
.chip{background:var(--tag);color:var(--ink);padding:3px 11px;border-radius:99px;font-size:.92rem}
.filters{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:20px}
.filters button{font:600 .95rem "Source Sans 3",sans-serif;padding:8px 14px;border-radius:99px;border:1px solid var(--line);background:var(--surface);color:var(--ink);cursor:pointer}
.filters button[aria-pressed="true"]{background:var(--accent);color:var(--accent-ink);border-color:var(--accent)}
.card .kind{font-size:.9rem;color:var(--accent);font-weight:600;margin-bottom:6px}
.ph{background:var(--ph);color:var(--ph-ink);padding:1px 6px;border-radius:4px}
.scroll{overflow-x:auto;border:1px solid var(--line);border-radius:12px;background:var(--surface)}
table{border-collapse:collapse;width:100%;min-width:760px;font-size:.95rem}
th,td{padding:10px 12px;border-bottom:1px solid var(--line);text-align:center}
th:first-child,td:first-child{text-align:left}
th{background:var(--tag);font-weight:600}
.cv-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:16px}
.cv-grid h3{font-size:1.05rem;margin-bottom:10px}
.cv-grid ul{margin:0;padding-left:18px;color:var(--muted)}
.note{margin:0 0 28px;padding:14px 16px;border-radius:10px;background:var(--ph);color:var(--ph-ink)}
footer{padding:32px 0;border-top:1px solid var(--line);color:var(--muted);font-size:.95rem}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
</style>
</head>
<body>
<header class="nav">
  <div class="wrap">
    <a class="brand" href="#accueil">A. Khelifi</a>
    <nav aria-label="Navigation principale">
      <ul>
        <li><a href="#competences">Compétences</a></li>
        <li><a href="#realisations">Réalisations</a></li>
        <li><a href="#stage">Stage</a></li>
        <li><a href="#veille">Veille</a></li>
        <li><a href="#fiche">Fiche</a></li>
        <li><a href="#cv">CV</a></li>
      </ul>
    </nav>
  </div>
</header>

<main>
<div class="wrap" id="accueil">
  <div class="hero">
    
    <h1>Abderrahmène Khelifi</h1>
    <div class="role">Étudiant en BTS SIO, option SISR</div>
    <p>Étudiant en 2ᵉ année de BTS SIO option Solutions d'infrastructure, systèmes et réseaux au lycée Parc de Vilgénis. Passionné par l'informatique, les systèmes et les réseaux, je suis sérieux, motivé et désireux de développer mes compétences techniques et professionnelles. Je recherche une alternance.</p>
    <div class="btns">
      <a class="btn primary" href="#cv">Voir mon CV</a>
      <a class="btn ghost" href="CV_Khelifi.pdf">Télécharger mon CV</a>
    </div>
    <div class="facts">
      <div><strong>2027</strong><span>Diplôme prévu</span></div>
      <div><strong>SISR</strong><span>Option</span></div>
      <div><strong>Scolaire</strong><span>Anglais</span></div>
      <div><strong>3</strong><span>Stages réalisés</span></div>
    </div>
  </div>
</div>

<section id="competences">
  <div class="wrap">
    <h2>Compétences</h2>
    <p class="lead">Ce que je sais faire aujourd'hui.</p>
    <div class="grid">
      <div class="card"><h3>Postes et systèmes</h3><div class="chips"><span class="chip">Installation de postes Windows</span><span class="chip">Installation de logiciels</span><span class="chip">Mises à jour</span><span class="chip">Active Directory</span><span class="chip">Debian 12</span></div></div>
      <div class="card"><h3>Réseaux</h3><div class="chips"><span class="chip">Notions de réseaux informatiques</span><span class="chip">Filtrage</span><span class="chip">DMZ</span><span class="chip">DHCP</span></div></div>
      <div class="card"><h3>Maintenance et support</h3><div class="chips"><span class="chip">Dépannage matériel et logiciel</span><span class="chip">Diagnostic de pannes</span><span class="chip">Support utilisateurs</span></div></div>
      <div class="card"><h3>Outils</h3><div class="chips"><span class="chip">Microsoft Office</span><span class="chip">GLPI</span></div></div>
      <div class="card"><h3>Langues et divers</h3><div class="chips"><span class="chip">Français courant</span><span class="chip">Arabe bilingue</span><span class="chip">Anglais niveau scolaire</span></div></div>
    </div>
  </div>
</section>

<section id="realisations">
  <div class="wrap">
    <h2>Réalisations</h2>
    <p class="lead">Mes travaux de stage et de formation. Pour chaque projet : le besoin, ce que j'ai fait, les outils utilisés.</p>
    <div class="filters" role="group" aria-label="Filtrer les réalisations">
      <button type="button" data-f="all" aria-pressed="true">Toutes</button>
      <button type="button" data-f="stage" aria-pressed="false">En stage</button>
      <button type="button" data-f="systemes" aria-pressed="false">Systèmes</button>
      <button type="button" data-f="reseaux" aria-pressed="false">Réseaux</button>
      <button type="button" data-f="ap" aria-pressed="false">AP de classe</button>
    </div>
    <div class="grid" id="projets">
      <article class="card" data-t="reseaux ap"><div class="kind">AP de classe, réseaux (25/02 au 11/03)</div><h3>AP Louvre : filtrage, DMZ et serveur web</h3><p>Séparer le réseau en zones : des règles de filtrage contrôlent ce qui peut passer, et le serveur web est placé dans une DMZ pour rester accessible sans exposer le réseau interne. Étapes : choisir l'adressage, écrire les règles, tester les accès autorisés et refusés.</p><div class="chips"><span class="chip">Filtrage</span><span class="chip">DMZ</span><span class="chip">Serveur web</span></div></article>
      <article class="card" data-t="systemes ap"><div class="kind">AP de classe, systèmes (18/03 au 01/04)</div><h3>AP Louvre : services internes AD et DHCP</h3><p>Mettre en place les services internes du réseau : Mettre en place les services internes : un annuaire Active Directory pour gérer comptes et groupes, et un serveur DHCP qui distribue les adresses aux postes. Étapes : installer les rôles, créer les utilisateurs, définir la plage d'adresses, vérifier qu'un poste obtient une adresse et rejoint le domaine.</p><div class="chips"><span class="chip">Active Directory</span><span class="chip">DHCP</span></div></article>
      <article class="card" data-t="stage"><div class="kind">Stage, 1ʳᵉ année</div><h3>Masterisation et préparation de postes Windows</h3><p>Préparer et configurer des postes utilisateurs sous Windows avant livraison, puis vérifier leur fonctionnement.</p><div class="chips"><span class="chip">Windows</span><span class="chip">Configuration</span><span class="chip">Tests</span></div></article>
      <article class="card" data-t="systemes"><div class="kind">TP de formation (12/02/2026)</div><h3>Déployer un serveur Debian</h3><p>Installer une machine virtuelle Debian 12 et préparer le serveur : installation du système, configuration réseau, mises à jour et vérification du bon fonctionnement.</p><div class="chips"><span class="chip">Debian 12</span><span class="chip">Serveur</span></div></article><article class="card" data-t="reseaux ap"><div class="kind">Projet de classe, réseaux (16/04 au 07/05)</div><h3>Extension d'une architecture réseau</h3><p>Faire évoluer l'architecture réseau existante pour répondre à de nouveaux besoins : analyser l'existant, planifier les changements, déployer puis tester le résultat.</p><div class="chips"><span class="chip">Architecture</span><span class="chip">Mode projet</span></div></article><article class="card" data-t="stage"><div class="kind">Stage, 1ʳᵉ année</div><h3>Diagnostic et réparation de postes (SAV)</h3><p>Diagnostiquer des pannes matérielles, réparer les postes et tester leur fonctionnement après réparation.</p><div class="chips"><span class="chip">Diagnostic</span><span class="chip">Réparation</span><span class="chip">SAV</span></div></article>
    </div>
  </div>
</section>

<section id="stage">
  <div class="wrap">
    <h2>Stage</h2>
    <p class="lead">Trois stages en informatique : maintenance, réparation et support aux utilisateurs.</p>
    <div class="grid">
      <div class="card"><h3>DML Informatique, Perreux-sur-Marne</h3><p>Maintenance et réparation de matériel informatique, installation de logiciels, assistance aux utilisateurs.</p></div>
      <div class="card"><h3>ASAWIN, Juvisy</h3><p>Diagnostic et réparation de smartphones et d'ordinateurs, support technique.</p></div>
      <div class="card"><h3>Securinfor, Wissous (juin à juillet 2026)</h3><p>Support et assistance informatique, intervention sur les équipements, découverte des environnements professionnels en systèmes et réseaux.</p></div>
    </div>
  </div>
</section>

<section id="veille">
  <div class="wrap">
    <h2>Veille technologique</h2>
    <p class="lead">Problématique : comment une entreprise doit-elle gérer la fin du support de Windows 10, et quel est le rôle du technicien informatique ?</p>
    <div class="grid">
      <div class="card"><h3>Contexte</h3><p>Le 14 octobre 2025, Microsoft a arrêté le support de Windows 10 : plus de mises à jour de sécurité, de corrections ni d'assistance technique. Les PC continuent de démarrer, mais ils deviennent plus vulnérables aux attaques au fil du temps.</p></div>
      <div class="card"><h3>Les solutions</h3><p>Passer à Windows 11 si le PC est compatible. Sinon, remplacer le PC, ou souscrire au programme payant ESU, qui apporte les correctifs de sécurité critiques pendant une durée limitée (jusqu'à 3 ans pour les entreprises). Des options existent aussi pour les particuliers : voir le site de Microsoft.</p></div>
      <div class="card"><h3>Le rôle du technicien</h3><p>Faire l'inventaire des postes encore sous Windows 10, vérifier leur compatibilité avec Windows 11, sauvegarder les données, puis migrer les postes ou planifier leur remplacement. C'est un travail que j'ai déjà rencontré en stage (installation et mise à jour de postes).</p></div>
    </div>
    <h3 style="margin:28px 0 8px">Sources</h3>
    <ul><li><a href="https://www.it-connect.fr/le-support-standard-de-windows-10-prend-fin-aujourdhui-quelles-sont-les-consequences/">IT-Connect : le support standard de Windows 10 prend fin (14 octobre 2025)</a></li><li><a href="https://www.lemondeinformatique.fr/actualites/lire-migration-vers-windows-11-la-grande-hesitation-des-entreprises-94001.html">LeMondeInformatique : migration vers Windows 11, la grande hésitation des entreprises</a></li><li><a href="https://www.ninjaone.com/fr/blog/fin-du-support-de-windows-10-eos-que-doivent-faire-les-equipes-informatiques/">NinjaOne : fin du support de Windows 10, que doivent faire les équipes informatiques ?</a></li></ul>
  </div>
</section>

<section id="fiche">
  <div class="wrap">
    <h2>Fiche de compétences</h2>
    <p class="lead">Synthèse de mes réalisations professionnelles, BTS SIO SISR, session 2027. Coche les compétences travaillées dans chaque réalisation.</p>
    <div class="scroll" tabindex="0" role="region" aria-label="Tableau des compétences">
      <table>
        <thead><tr><th>Réalisation</th><th>Gérer le patrimoine informatique</th><th>Répondre aux incidents</th><th>Développer la présence en ligne</th><th>Travailler en mode projet</th><th>Mettre à disposition un service</th><th>Organiser son développement</th></tr></thead>
        <tbody>
          <tr><td>AP Louvre : filtrage, DMZ, serveur web</td><td></td><td></td><td></td><td>✓</td><td>✓</td><td></td></tr>
          <tr><td>AP Louvre : services internes (AD, DHCP)</td><td>✓</td><td></td><td></td><td>✓</td><td>✓</td><td></td></tr>
          <tr><td>TP : déployer un serveur Debian</td><td></td><td></td><td></td><td></td><td>✓</td><td></td></tr><tr><td>Projet : extension d'une architecture</td><td></td><td></td><td></td><td>✓</td><td>✓</td><td></td></tr><tr><td>Masterisation de postes Windows (stage)</td><td>✓</td><td></td><td></td><td></td><td>✓</td><td></td></tr><tr><td>Diagnostic et réparation de postes, SAV (stage)</td><td>✓</td><td>✓</td><td></td><td></td><td></td><td></td></tr><tr><td>Veille : fin du support de Windows 10</td><td></td><td></td><td></td><td></td><td></td><td>✓</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</section>

<section id="cv">
  <div class="wrap">
    <h2>Curriculum vitae</h2>
    <p class="lead"><a href="CV_Khelifi.pdf">Télécharger mon CV</a></p>
    <div class="cv-grid">
      <div class="card"><h3>Contact</h3><ul><li>abderrahmenekh94@gmail.com</li><li>07 84 88 89 93</li><li>94310 Orly</li></ul></div>
      <div class="card"><h3>Formation</h3><ul><li>BTS SIO option SISR, 2ᵉ année en cours, lycée Parc de Vilgénis, Massy</li><li>Baccalauréat professionnel Systèmes numériques, mention assez bien, Lycée Parc de Vilgénis, Massy</li></ul></div>
      <div class="card"><h3>Expériences</h3><ul><li>Stagiaire informatique, DML Informatique, Perreux-sur-Marne</li><li>Stage réparation, ASAWIN, Juvisy</li><li>Stagiaire informatique, Securinfor, Wissous, 06/2026 à 07/2026</li></ul></div>
      <div class="card"><h3>Qualités et intérêts</h3><ul><li>Sérieux, motivé</li><li>Centres d'intérêt : football</li></ul></div>
      <div class="card"><h3>Certifications</h3><ul><li>SecNumacadémie (ANSSI), MOOC validé le 28/11/2025 : panorama de la SSI, sécurité de l'authentification, sécurité sur Internet, sécurité du poste de travail. <a href="https://abde943ols.github.io/ALL-TP/certif/hFycICdDJqSKxOf69DPDTAy29NyOl6WFq2YvkviGl3tEbLkUjc0XygpctwjL_131957_28112025.pdf">Voir l'attestation</a></li></ul></div>
    </div>
  </div>
</section>
</main>

<footer>
  <div class="wrap">© 2026 Abderrahmène Khelifi, BTS SIO SISR · abderrahmenekh94@gmail.com</div>
</footer>

<script>
(function(){
  var btns=document.querySelectorAll('.filters button');
  var cards=document.querySelectorAll('#projets .card');
  btns.forEach(function(b){
    b.addEventListener('click',function(){
      var f=b.getAttribute('data-f');
      btns.forEach(function(x){x.setAttribute('aria-pressed',x===b?'true':'false')});
      cards.forEach(function(c){
        var t=(c.getAttribute('data-t')||'').split(' ');
        c.style.display=(f==='all'||t.indexOf(f)>-1)?'':'none';
      });
    });
  });
})();
</script>
</body>
</html>
