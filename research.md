<!doctype html>
<html lang="it">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Research | Giulia Giannini</title>
  <link rel="stylesheet" href="assets/css/style.css" />
</head>
<body>
  <header class="topbar">
    <a class="brand" href="index.html" aria-label="Home">
      <img class="avatar" src="assets/img/avatar.jpg" alt="Foto profilo" />
      <span class="brand-name">Giulia Giannini</span>
    </a>

    <nav class="nav">
      <a class="nav-link" href="index.html">Home</a>
      <a class="nav-link" href="cv.html">CV</a>
      <a class="nav-link active" href="research.html">Research</a>
      <a class="nav-link" href="publications.html">Publications</a>
    </nav>
  </header>

  <main class="page">
    <article class="content">
      <h1>Research</h1>
      <p>
        Testo introduttivo su cosa fai: weak lensing, photo-z calibration, SBI, ecc.
      </p>

      <section class="cards">
        <article class="card">
          <img class="card-img" src="assets/img/home-photo.jpg" alt="Immagine progetto" />
          <div class="card-body">
            <h2>Simulation-Based Inference for Multi-Probe Cosmology</h2>
            <p>
              Due righe su obiettivo, dataset, e cosa hai ottenuto.
            </p>
            <p class="links">
              <a href="#" target="_blank" rel="noopener">Paper</a>
              <a href="#" target="_blank" rel="noopener">Code</a>
            </p>
          </div>
        </article>

        <article class="card">
          <img class="card-img" src="assets/img/home-photo.jpg" alt="Immagine progetto" />
          <div class="card-body">
            <h2>Photometric redshift calibration (SOMPZ)</h2>
            <p>
              Descrizione breve, con link ai paper.
            </p>
            <p class="links">
              <a href="#" target="_blank" rel="noopener">Paper</a>
            </p>
          </div>
        </article>
      </section>
    </article>
  </main>

  <footer class="footer">
    <span>© <span id="year"></span> Giulia Giannini</span>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
