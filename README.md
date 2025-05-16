<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Kaouter Rhazlani - Data Engineer Portfolio</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

  body {
    background: linear-gradient(135deg, #f0f4ff, #e1ecf9);
    font-family: 'Montserrat', sans-serif;
    margin: 0;
    padding: 2rem;
    color: #2c3e50;
    display: flex;
    justify-content: center;
  }

  .container {
    max-width: 800px;
    background: #ffffffcc;
    border-radius: 12px;
    padding: 2.5rem 3rem;
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  }

  h1 {
    font-weight: 700;
    font-size: 2.5rem;
    color: #34495e;
    margin-bottom: 0.2rem;
  }

  .intro {
    font-size: 1.15rem;
    color: #666f85;
    margin-bottom: 2rem;
    line-height: 1.6;
  }

  hr {
    border: none;
    height: 2px;
    background: linear-gradient(to right, #2980b9, #8e44ad);
    margin: 2.5rem 0;
    border-radius: 1px;
  }

  h2 {
    color: #34495e;
    border-bottom: 2px solid #8e44ad;
    padding-bottom: 0.3rem;
    margin-bottom: 1rem;
  }

  a {
    color: #2980b9;
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s ease;
  }

  a:hover {
    color: #8e44ad;
    text-decoration: underline;
  }

  .project {
    background: #f9faff;
    border-radius: 10px;
    padding: 1rem 1.5rem;
    margin-bottom: 1.8rem;
    box-shadow: 0 2px 8px rgb(142 68 173 / 0.15);
    transition: transform 0.25s ease;
  }

  .project:hover {
    transform: translateY(-6px);
  }

  .project a {
    font-weight: 700;
    font-size: 1.05rem;
  }

  .project-description {
    margin-top: 0.4rem;
    font-size: 0.95rem;
    color: #515d75;
  }

  ul.skills {
    list-style: none;
    padding-left: 0;
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
    gap: 0.8rem;
    margin-bottom: 2rem;
  }

  ul.skills li {
    background: #8e44ad;
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 8px;
    font-weight: 600;
    font-size: 0.9rem;
    text-align: center;
    box-shadow: 0 4px 10px rgb(142 68 173 / 0.3);
  }

  .contact {
    display: flex;
    gap: 1rem;
    justify-content: center;
    margin-top: 2rem;
  }

  .contact a {
    display: inline-flex;
    align-items: center;
    gap: 0.6rem;
    background: #0a66c2;
    padding: 0.6rem 1.2rem;
    border-radius: 30px;
    color: white;
    font-weight: 700;
    font-size: 1rem;
    box-shadow: 0 4px 14px rgb(10 102 194 / 0.6);
    transition: background 0.3s ease;
    text-decoration: none;
  }

  .contact a.portfolio {
    background: #2b7aee;
    box-shadow: 0 4px 14px rgb(43 122 238 / 0.6);
  }

  .contact a:hover {
    filter: brightness(1.1);
  }

  .contact a svg {
    width: 20px;
    height: 20px;
    fill: white;
  }

  footer {
    margin-top: 3rem;
    text-align: center;
    font-style: italic;
    color: #888ea8;
  }

  /* Responsive */
  @media (max-width: 520px) {
    .contact {
      flex-direction: column;
    }
  }
</style>
</head>
<body>
  <main class="container">
    <h1>👋 Bonjour, je suis Kaouter Rhazlani</h1>
    <p class="intro">
      🎓 Admise à la formation <strong>Data Engineer</strong> chez Simplon<br/>
      🔍 À la recherche d'une alternance à partir du <strong>1er septembre 2025</strong><br/>
      💡 Passionnée par l’ingénierie de données : ingestion, modélisation, automatisation et visualisation
    </p>

    <hr />

    <section>
      <h2>📄 Mon CV</h2>
      <p>Vous pouvez consulter mon CV ici : 
        <a href="https://github.com/kaouterrhazlani/cv/blob/d51e6793b1eb5ac67f7b61e44bf8763a0fc2d978/CV_Kaouter_RHAZLANI.pdf" target="_blank" rel="noopener noreferrer">Télécharger le CV</a>
      </p>
    </section>

    <section>
      <h2>📌 Projets GitHub</h2>

      <article class="project">
        <a href="https://github.com/kaouterrhazlani/Big-Query-Looker-studio-project---Prix-carburant-autour-de-mon-adresse." target="_blank" rel="noopener noreferrer">
          🔷 BigQuery & Looker Studio – Analyse des prix du carburant
        </a>
        <p class="project-description">
          📊 Projet d’analyse des prix du carburant autour de mon adresse, avec nettoyage de fichiers CSV, requêtes BigQuery et dashboard Looker Studio.
        </p>
      </article>

      <article class="project">
        <a href="https://github.com/kaouterrhazlani/DataWarehouseProject" target="_blank" rel="noopener noreferrer">
          🏗️ Data Warehouse – Projet complet
        </a>
        <p class="project-description">
          📦 Modèle Medallion (Bronze, Silver, Gold) avec fichiers CSV (ERP/CRM), script ETL, modélisation en étoile, et documentation complète.
        </p>
      </article>

      <article class="project">
        <a href="https://github.com/kaouterrhazlani/SQLProjects" target="_blank" rel="noopener noreferrer">
          📐 Projets SQL
        </a>
        <p class="project-description">
          🧮 Projets d'analyse SQL avec création de tables, vues, requêtes analytiques et cas concrets.
        </p>
      </article>

      <article class="project">
        <a href="https://github.com/kaouterrhazlani/ExcelProjects" target="_blank" rel="noopener noreferrer">
          📊 Projets Excel
        </a>
        <p class="project-description">
          📈 Nettoyage, analyse et visualisation de données avec Excel : formules avancées, tableaux croisés dynamiques, et graphiques.
        </p>
      </article>
    </section>

    <hr />

    <section>
      <h2>🛠️ Compétences techniques</h2>
      <ul class="skills">
        <li>Python</li>
        <li>SQL</li>
        <li>PySpark</li>
        <li>Power BI</li>
        <li>Looker Studio</li>
        <li>Excel</li>
        <li>Databricks</li>
        <li>PostgreSQL</li>
        <li>BigQuery</li>
        <li>SQLite</li>
        <li>SQL Server</li>
        <li>SSIS</li>
        <li>Pandas</li>
        <li>Azure Data Factory</li>
        <li>Docker</li>
        <li>Google BigQuery</li>
        <li>GitHub</li>
        <li>Notion</li>
        <li>Draw.io</li>
      </ul>
    </section>

    <section class="contact">
      <a href="https://www.linkedin.com/in/kaouter-rhazlani/" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn">
        <!-- LinkedIn SVG icon -->
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 34 34" aria-hidden="true" focusable="false"><path fill="white" d="M34,34h-7.1V23.7c0-2.4-0.8-4-2.9-4c-1.6,0-2.5,1.1-2.9,2.2c-0.1,0.3-0.1,0.7-0.1,1.1V34h-7.1c0,0,0.1-21.9,0-24.2h7.1v3.4c0.9-1.4,2.5-3.4,6.2-3.4c4.5,0,7.9,2.9,7.9,9.2V34z M4,9.2C1.8,9.2,0,7.4,0,5.2S1.8,1.2,4,1.2c2.2,0,4,1.8,4,4S6.2,9.2,4,9.2z M0,34h7.9V9.8H0V34z"/></svg>
        LinkedIn
      </a>
      <a href="https://www.datascienceportfol.io/Kaouter1rhazlani" target="_blank" rel="noopener noreferrer" class="portfolio" aria-label="Portfolio">
        <!-- Internet Explorer icon SVG -->
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48" aria-hidden="true" focusable="false" style="width:20px;height:20px;fill:white;"><path d="M12 24a12 12 0 1 0 24 0 12 12 0 1 0-24 0zm12-16c8.8 0 16 7.2 16 16s-7.2 16-16 16-16-7.2-16-16 7.2-16 16-16z"/></svg>
        Portfolio
      </a>
    </section>

    <footer>
      Merci pour votre visite ! 🌟
    </footer>
  </main>
</body>
</html>
