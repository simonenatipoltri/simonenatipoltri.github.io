<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Simone Natipoltri — Postdoc Researcher</title>
  <meta name="description" content="Simone Natipoltri — Postdoctoral researcher. Research interests, teaching, publications and contact." />
  <link rel="stylesheet" href="assets/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <div class="brand">
        <h1>Simone Natipoltri</h1>
        <p class="subtitle">Postdoctoral Researcher — [Your Institution]</p>
      </div>
      <nav class="main-nav">
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#teaching">Teaching</a>
        <a href="#publications">Publications</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section id="about" class="card">
      <h2>About</h2>
      <p>
        I am a postdoctoral researcher working on [insert research area: e.g., computational neuroscience, machine learning for health, environmental modelling].
        My recent work focuses on [short summary of recent research topics or projects].
      </p>
      <p>
        Current affiliation: <strong>[Your Institution]</strong><br>
        Email: <a href="mailto:snatipoltri@users.noreply.github.com">snatipoltri@your-institution.edu</a>
      </p>
      <p><a class="button" href="assets/CV-Simone-Natipoltri.pdf" download>Download CV (PDF)</a></p>
    </section>

    <section id="experience" class="card">
      <h2>Professional Experience</h2>
      <ul class="timeline">
        <li>
          <div class="role">Postdoctoral Researcher — [Your Institution]</div>
          <div class="meta">2023 — Present</div>
          <div class="desc">Working on [brief description of projects, collaborators, techniques].</div>
        </li>
        <li>
          <div class="role">PhD Candidate — [University]</div>
          <div class="meta">2018 — 2023</div>
          <div class="desc">Thesis: [title]. Advisors: [names].</div>
        </li>
        <!-- Add more items or keep this section sourced from experiences.md -->
      </ul>
    </section>

    <section id="teaching" class="card">
      <h2>Teaching</h2>
      <ul>
        <li><strong>Course name</strong> — [Institution] (Semester, Year) — Role: [Lecturer / TA]. Short description.</li>
        <li><strong>Hands-on workshops</strong> — Topics: [Python, Reproducible Research, Data Analysis].</li>
      </ul>
      <p>Full teaching record available in the Teaching page or file.</p>
    </section>

    <section id="publications" class="card">
      <h2>Selected Publications</h2>
      <ol>
        <li>
          <strong>Natipoltri, S.</strong>, et al. (2024). Title of the paper. Journal Name. <a href="#" target="_blank" rel="noopener">DOI</a>
        </li>
        <li>
          <strong>Natipoltri, S.</strong>, et al. (2022). Another paper title. Conference/Journal. <a href="#" target="_blank" rel="noopener">PDF</a>
        </li>
      </ol>
      <p><a class="button" href="publications.md">View full publications list</a></p>
    </section>

    <section id="contact" class="card">
      <h2>Contact</h2>
      <p>
        Email: <a href="mailto:snatipoltri@your-institution.edu">snatipoltri@your-institution.edu</a><br>
        OR contact me on Twitter / LinkedIn: <a href="https://twitter.com/yourhandle" target="_blank" rel="noopener">@yourhandle</a>
      </p>
      <p class="muted">If you want to cite my work or discuss collaborations, please reach out by email.</p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> Simone Natipoltri — Postdoctoral Researcher</p>
    </div>
  </footer>

  <script>
    // small script to set the year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
