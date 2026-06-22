---
layout: default
title: Welcome
---

<meta name="description" content="Aleksandra Stamper – researcher in climate, data science, and public health.">
<meta name="author" content="Aleksandra Stamper">

<style>
:root {
  --bg: #CADBC0;
  --text: #000;
  --muted: #333;
  --accent: #e83f5b;
  --line: rgba(0,0,0,0.25);
}
body.dark {
  --bg: #1f1f1f;
  --text: #f2f2f2;
  --muted: #d0d0d0;
  --accent: #ff6b8a;
  --line: rgba(255,255,255,0.25);
}
body {
  background: var(--bg);
  color: var(--text);
}
a { color: var(--accent); }
.site-wrap {
  max-width: 1150px;
  margin: 0 auto;
  padding: 1.5rem;
}
.top-nav {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  border-bottom: 1px solid var(--line);
  padding-bottom: 1rem;
  margin-bottom: 3rem;
  font-size: 1.4rem;
}
.top-nav a {
  color: var(--text);
  text-decoration: none;
}
.top-nav a.active {
  font-weight: 700;
  border-bottom: 3px solid var(--text);
  padding-bottom: 0.5rem;
}
.theme-toggle {
  margin-left: 0;
  background: none;
  border: none;
  font-size: 1.4rem;
  cursor: pointer;
  color: var(--text);
}
.layout {
  display: grid;
  grid-template-columns: 260px 1fr;
  gap: 3rem;
  align-items: start;
}
.sidebar img {
  width: 170px;
  height: 170px;
  object-fit: cover;
  border-radius: 50%;
  border: 2px solid var(--line);
}
.sidebar h2 {
  margin-top: 1rem;
}
.sidebar p {
  color: var(--muted);
  line-height: 1.45;
}
.content h1 {
  font-size: 2.5rem;
  margin-top: 0;
}
.content p, .content li {
  font-size: 1.25rem;
  line-height: 1.6;
}
.tab-content {
  display: none;
}
.tab-content.active {
  display: block;
}
@media (max-width: 800px) {
  .layout {
    grid-template-columns: 1fr;
  }
  .top-nav {
    gap: 1.25rem;
    font-size: 1.1rem;
    flex-wrap: wrap;
  }
}
</style>

<div class="site-wrap">

  <nav class="top-nav">
    <a href="#" class="tab-link active" data-tab="about">Aleksandra Stamper</a>
    <a href="#" class="tab-link" data-tab="cv">CV</a>
    <a href="#" class="tab-link" data-tab="research">Research</a>
    <button class="theme-toggle" onclick="toggleTheme()">☀︎</button>
  </nav>

  <div class="layout">
    <aside class="sidebar">
      <img src="images/02-Aleksandra Stamper-1920.jpg" alt="Aleksandra Stamper">
      <h2>Aleksandra Stamper</h2>
      <p>she/her</p>
      <p>
        PhD candidate in Epidemiology @ Brown University School of Public Health |
        Baker Group | climate and infectious disease dynamics
      </p>
      <p>
        <a href="https://scholar.google.com/citations?user=e10nsZ8AAAAJ&hl=en">Google Scholar</a><br>
        <a href="/assets/20260616_AStamper_CV.pdf">CV</a>
      </p>
    </aside>

    <main class="content">

      <section id="about" class="tab-content active">
        <h1>About</h1>
        <p>
          Hi, I’m Aleksandra. I’m an epidemiologist and infectious disease modeler interested in how climate,
          environment, and human behavior shape infectious disease dynamics.
        </p>
        <p>
          I’m currently a PhD candidate in Epidemiology at the Brown University School of Public Health, where I work
          in the <a href="https://www.rachelelizabethbaker.com">Baker group</a> with
          <a href="https://vivo.brown.edu/display/rebaker">Dr. Rachel Baker</a>. My research uses mechanistic models,
          statistical approaches, and public health surveillance data to understand respiratory virus transmission
          across different climate settings.
        </p>
        <p>
          My recent work focuses on influenza seasonality, climate-sensitive transmission, and how climate variability
          and climate change may alter outbreak timing and intensity.
        </p>
      </section>

      <section id="cv" class="tab-content">
        <h1>CV</h1>
        <p><a href="/assets/20260616_AStamper_CV.pdf">Download my full CV here.</a></p>

        <h2>Education</h2>
        <p><strong>PhD in Epidemiology</strong><br>Brown University School of Public Health</p>
        <p><strong>Master of Applied Science in Spatial Analysis for Public Health</strong><br>Johns Hopkins Bloomberg School of Public Health, 2022</p>
        <p><strong>Bachelor of Arts in Biochemistry and Anthropology</strong><br>Smith College, 2018</p>

        <h2>Honors</h2>
        <ul>
          <li><strong>Outstanding Doctoral Student Publication Award Recipient</strong>, Spring 2025</li>
          <li><strong>NASA Rhode Island Space Grant Fellow</strong>, Fall 2024</li>
        </ul>

        <h2>Skills</h2>
        <ul>
          <li>R, Python, SAS, SQL, ArcGIS</li>
          <li>SIR/SIRS models, generalized linear models, fixed effects regression, spatial analysis</li>
        </ul>
      </section>

      <section id="research" class="tab-content">
        <h1>Research</h1>

        <h2>Climate-disease dynamics</h2>
        <p>
          <strong>Projecting the impact of climate change on influenza outbreaks across temperate and tropical regions.</strong>
          I worked with climate-driven transmission models to characterize influenza dynamics across a wide range of
          climate regions. This work was published in
          <a href="https://academic.oup.com/pnasnexus/article/5/6/pgag160/8708116?login=true">PNAS Nexus</a>.
        </p>
        <p>
          <strong>Modeling the impact of climate extremes on seasonal influenza outbreaks.</strong>
          We used a SIR model with climate-sensitive transmission to assess influenza outbreaks in the United States,
          Hong Kong, and Bangladesh. This work was published in
          <a href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2024GH001138">GeoHealth</a>.
        </p>
        <p>
          I have also investigated climate factors and COVID-19 activity in the United States, published in
          <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0342510">PLOS ONE</a>, and
          contributed to work on climate and seasonality of hospitalizations in Mexico.
        </p>

        <h2>Respiratory virus surveillance</h2>
        <p>
          I have contributed to analyses of influenza activity on a
          <a href="https://onlinelibrary.wiley.com/doi/full/10.1111/irv.13151">college campus</a>, work featured in
          <a href="https://www.cdc.gov/mmwr/volumes/70/wr/mm7049e1.htm">MMWR</a>, and analyses of
          <a href="https://academic.oup.com/ofid/article/11/5/ofae192/7641318">human adenovirus</a>.
        </p>
      </section>

    </main>
  </div>
</div>

<script>
function showTab(tabId) {
  document.querySelectorAll(".tab-content").forEach(section => {
    section.classList.remove("active");
  });
  document.querySelectorAll(".tab-link").forEach(link => {
    link.classList.remove("active");
  });
  document.getElementById(tabId).classList.add("active");
  document.querySelector(`[data-tab="${tabId}"]`).classList.add("active");
}
document.querySelectorAll(".tab-link").forEach(link => {
  link.addEventListener("click", event => {
    event.preventDefault();
    showTab(link.dataset.tab);
  });
});
function toggleTheme() {
  document.body.classList.toggle("dark");
  localStorage.setItem("theme", document.body.classList.contains("dark") ? "dark" : "light");
}
if (localStorage.getItem("theme") === "dark") {
  document.body.classList.add("dark");
}
</script>
