<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio GEII - Alternance Christeyns</title>

<style>
:root{
    --bg:#0b1220;
    --card:#111a2e;
    --accent:#38bdf8;
    --text:#e5e7eb;
    --muted:#94a3b8;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:var(--bg);
    color:var(--text);
}

/* HEADER */
header{
    padding:70px 20px;
    text-align:center;
    background:linear-gradient(135deg,#111a2e,#0b1220);
}

header h1{
    font-size:40px;
    margin-bottom:10px;
}

header p{
    color:var(--muted);
    font-size:18px;
}

/* NAV */
nav{
    position:sticky;
    top:0;
    background:#0f1b33;
    display:flex;
    justify-content:center;
    gap:25px;
    padding:12px;
    z-index:1000;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
    opacity:0.8;
}

nav a:hover{
    opacity:1;
    color:var(--accent);
}

/* SECTIONS */
section{
    max-width:1100px;
    margin:auto;
    padding:60px 20px;
}

h2{
    font-size:28px;
    margin-bottom:20px;
    border-left:4px solid var(--accent);
    padding-left:10px;
}

/* CARDS */
.card{
    background:var(--card);
    padding:25px;
    border-radius:12px;
    margin-bottom:20px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

/* SKILLS */
.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:15px;
}

.skill{
    background:#0b1220;
    padding:12px;
    border-radius:8px;
    border-left:3px solid var(--accent);
}

/* FOOTER */
footer{
    text-align:center;
    padding:25px;
    background:#111a2e;
    color:var(--muted);
}

/* SMALL */
.small{
    color:var(--muted);
}
</style>

</head>

<body>

<header>
    <h1>Portfolio BUT GEII</h1>
    <p>Alternance – Installation et mise en service de systèmes industriels</p>
</header>

<nav>
    <a href="#profil">Profil</a>
    <a href="#competences">Compétences</a>
    <a href="#experience">Expérience</a>
    <a href="#projets">Projets</a>
</nav>

<!-- PROFIL -->
<section id="profil">
    <h2>Profil</h2>
    <div class="card">
        Étudiant en BUT Génie Électrique et Informatique Industrielle (GEII),
        j’ai réalisé une alternance chez Christeyns en tant que technicien itinérant.
        Cette expérience m’a permis de travailler sur l’installation, le câblage,
        la programmation et la mise en service de systèmes industriels automatisés.
    </div>
</section>

<!-- COMPETENCES -->
<section id="competences">
    <h2>Compétences GEII</h2>

    <div class="skills">

        <div class="card">
            <h3>Installation industrielle</h3>
            <div class="skill">Câblage 400V / 24VDC</div>
            <div class="skill">Raccordement pneumatique</div>
            <div class="skill">Mise en service d’équipements</div>
        </div>

        <div class="card">
            <h3>Automatisme</h3>
            <div class="skill">Automate Omron CP1L</div>
            <div class="skill">Tests entrées / sorties</div>
            <div class="skill">Programmation et validation</div>
        </div>

        <div class="card">
            <h3>Analyse système</h3>
            <div class="skill">Diagnostic de pannes</div>
            <div class="skill">Lecture de schémas électriques</div>
            <div class="skill">Vérification capteurs / actionneurs</div>
        </div>

    </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
    <h2>Expérience</h2>

    <div class="card">
        <h3>Alternance – Technicien itinérant</h3>
        <p class="small">Christeyns France</p>

        <br>

        <p><b>Missions principales :</b></p>
        <ul>
            <li>Installation de systèmes industriels (Zero-Steam / Flux-Star)</li>
            <li>Raccordement électrique et pneumatique</li>
            <li>Programmation automate et mise en service</li>
            <li>Tests fonctionnels et validation client</li>
        </ul>
    </div>
</section>

<!-- PROJETS -->
<section id="projets">
    <h2>Projets industriels</h2>

    <div class="card">
        <h3>Zero-Steam 4.3</h3>
        <p>Système de chauffage industriel sans chaudière vapeur avec pilotage automate.</p>
    </div>

    <div class="card">
        <h3>Flux-Star</h3>
        <p>Système de dosage automatisé de produits chimiques pour blanchisserie industrielle.</p>
    </div>
</section>

<footer>
    Portfolio GEII – Christeyns Alternance
</footer>

</body>
</html>
