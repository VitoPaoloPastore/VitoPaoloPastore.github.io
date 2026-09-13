---
permalink: /
title: "Vito Paolo Pastore"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
/* ---------------------------------------------------------------
   Home page. Scoped under .home so nothing leaks into the rest of
   the Minimal Mistakes / academicpages theme. Shares its tokens
   with the news page: if you change --accent, change it there too.
   --------------------------------------------------------------- */

.home {
  --accent: #2f7d95;
  --rule: rgba(128, 128, 128, 0.28);
  --wash: rgba(128, 128, 128, 0.07);
  line-height: 1.5;
}

/* Lede: the one place this page raises its voice ------------------ */

.home .lede {
  margin: 0 0 3rem;
  max-width: 46ch;
  font-size: 1.35rem;
  font-weight: 400;
  line-height: 1.45;
  letter-spacing: -0.01em;
}

.home .lede em {
  font-style: normal;
  font-weight: 600;
}

/* Sections -------------------------------------------------------- */

.home .section {
  margin: 0 0 3rem;
}

.home .section:last-child {
  margin-bottom: 0;
}

.home .section__title {
  margin: 0 0 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 1px solid var(--rule);
  font-size: 1.3rem;
  font-weight: 600;
  letter-spacing: -0.02em;
  line-height: 1.2;
}

/* Research threads: run-in headings, not cards -------------------- */

.home .threads {
  margin: 0;
  padding: 0;
  list-style: none;
}

.home .thread {
  padding: 0 0 1.1rem;
  margin: 0 0 1.1rem;
  border-bottom: 1px solid var(--rule);
  max-width: 66ch;
  font-size: 1rem;
  line-height: 1.55;
}

.home .thread:last-child {
  padding-bottom: 0;
  margin-bottom: 0;
  border-bottom: 0;
}

.home .thread__name {
  font-weight: 700;
  letter-spacing: -0.01em;
}

/* Recent work: same venue-marker language as the news page -------- */

.home .feed {
  margin: 0 0 1.25rem;
  padding: 0;
  list-style: none;
}

.home .feed__item {
  display: grid;
  grid-template-columns: 7.5rem 1fr;
  align-items: start;
}

.home .feed__marker {
  padding: 0.1rem 1.5rem 0 0;
  text-align: right;
}

.home .feed__venue {
  display: block;
  font-size: 1.05rem;
  font-weight: 700;
  letter-spacing: -0.015em;
  line-height: 1.25;
}

.home .feed__year {
  display: block;
  margin-top: 0.15rem;
  font-size: 0.8rem;
  font-variant-numeric: tabular-nums;
  opacity: 0.6;
}

.home .feed__body {
  padding: 0 0 1.6rem 1.75rem;
  border-left: 1px solid var(--rule);
}

.home .feed__item:last-child .feed__body {
  padding-bottom: 0;
}

.home .entry {
  margin: 0;
  max-width: 64ch;
  font-size: 1rem;
  font-weight: 500;
  line-height: 1.45;
}

/* Background: a year rail ----------------------------------------- */

.home .track {
  margin: 0;
  padding: 0;
  list-style: none;
}

.home .track__row {
  display: grid;
  grid-template-columns: 7.5rem 1fr;
  align-items: baseline;
  padding: 0.7rem 0;
  border-bottom: 1px solid var(--rule);
}

.home .track__row:last-child {
  border-bottom: 0;
}

.home .track__years {
  padding-right: 1.5rem;
  font-size: 0.95rem;
  font-weight: 700;
  letter-spacing: -0.015em;
  text-align: right;
  font-variant-numeric: tabular-nums;
  white-space: nowrap;
}

.home .track__what {
  max-width: 60ch;
  font-size: 1rem;
  line-height: 1.45;
}

.home .track__where {
  display: block;
  margin-top: 0.15rem;
  font-size: 0.875rem;
  opacity: 0.72;
}

/* Callout: the one filled block ----------------------------------- */

.home .callout {
  padding: 1.25rem 1.5rem;
  background: var(--wash);
  border-left: 3px solid var(--accent);
}

.home .callout p {
  margin: 0 0 0.7rem;
  max-width: 62ch;
  font-size: 1rem;
  line-height: 1.5;
}

.home .callout p:last-child {
  margin-bottom: 0;
}

/* Links ----------------------------------------------------------- */

.home .link {
  font-weight: 500;
  color: var(--accent);
  text-decoration: underline;
  text-underline-offset: 0.2em;
  text-decoration-thickness: 1px;
}

.home .link:hover,
.home .link:focus {
  text-decoration-thickness: 2px;
}

.home .link--more {
  display: inline-block;
  font-size: 0.9rem;
}

.home a:focus-visible {
  outline: 2px solid var(--accent);
  outline-offset: 3px;
}

/* Small screens --------------------------------------------------- */

@media (max-width: 40em) {
  .home .lede {
    font-size: 1.2rem;
  }

  .home .feed__item {
    grid-template-columns: 1fr;
    padding-top: 1rem;
    border-top: 1px solid var(--rule);
  }

  .home .feed__item:first-child {
    padding-top: 0;
    border-top: 0;
  }

  .home .feed__marker {
    display: flex;
    align-items: baseline;
    gap: 0.5rem;
    padding: 0 0 0.4rem;
    text-align: left;
  }

  .home .feed__venue,
  .home .feed__year {
    display: inline;
    margin-top: 0;
  }

  .home .feed__body {
    padding: 0 0 1.2rem;
    border-left: 0;
  }

  .home .track__row {
    grid-template-columns: 1fr;
  }

  .home .track__years {
    padding: 0 0 0.15rem;
    text-align: left;
  }
}

@media (prefers-reduced-motion: reduce) {
  .home * {
    transition: none !important;
  }
}
</style>

<div class="home">

  <p class="lede">I work on making machine learning models <em>fair, reliable and usable when data is scarce</em> &mdash; and on putting them to work in medicine and biology, where those three things decide whether a model is worth deploying at all.</p>

  <!-- ============================================================ -->
  <section class="section">
    <h2 class="section__title">Research</h2>

    <ul class="threads">
      <li class="thread">
        <span class="thread__name">Model debiasing and fairness.</span>
        Neural networks latch onto spurious correlations in their training data and carry them into their predictions. My group develops methods to discover these biases without having to annotate them in advance, and to remove them from models that have already learned them.
      </li>
      <li class="thread">
        <span class="thread__name">Medical and biological imaging.</span>
        Anatomical landmark detection in X-ray and MRI, and image analysis for cells and microorganisms. These settings have little labelled data and a low tolerance for silent failure, which makes them a demanding test of everything above.
      </li>
      <li class="thread">
        <span class="thread__name">Learning from limited, unlabelled or distributed data.</span>
        Few-shot and self-supervised pre-training, unsupervised domain adaptation, and federated learning for cases where the data cannot be pooled in one place.
      </li>
    </ul>
  </section>

  <!-- ============================================================ -->
  <section class="section">
    <h2 class="section__title">Recent work</h2>

    <ol class="feed">
      <li class="feed__item">
        <div class="feed__marker">
          <span class="feed__venue">ECCV</span>
          <span class="feed__year">2026</span>
        </div>
        <div class="feed__body">
          <p class="entry">AracNet: Revealing Debiasing Signals across Layers with Shallow Monitors</p>
        </div>
      </li>
      <li class="feed__item">
        <div class="feed__marker">
          <span class="feed__venue">CVPR</span>
          <span class="feed__year">2026</span>
        </div>
        <div class="feed__body">
          <p class="entry">Bias In, Bias Out? Finding Unbiased Subnetworks in Vanilla Models</p>
        </div>
      </li>
      <li class="feed__item">
        <div class="feed__marker">
          <span class="feed__venue">NeurIPS</span>
          <span class="feed__year">2025</span>
        </div>
        <div class="feed__body">
          <p class="entry">Diffusing DeBias: Synthetic Bias Amplification for Model Debiasing</p>
        </div>
      </li>
    </ol>

    <a class="link link--more" href="{{ base_path }}/news/">All papers, workshops and talks</a>
  </section>

  <!-- ============================================================ -->
  <section class="section">
    <h2 class="section__title">Background</h2>

    <ul class="track">
      <li class="track__row">
        <span class="track__years">2025&ndash;</span>
        <span class="track__what">Tenure-track assistant professor (RTT) in Computer Science
          <span class="track__where">DIBRIS and the <a class="link" href="https://malga.unige.it/">Machine Learning Genoa Center (MaLGa)</a>, University of Genova. Affiliated researcher, AIGO &ndash; AI for Good, <a class="link" href="https://www.iit.it/">Istituto Italiano di Tecnologia</a>.</span>
        </span>
      </li>
      <li class="track__row">
        <span class="track__years">2022&ndash;2025</span>
        <span class="track__what">Assistant professor in Computer Science
          <span class="track__where">MaLGa&ndash;DIBRIS, University of Genova.</span>
        </span>
      </li>
      <li class="track__row">
        <span class="track__years">2020&ndash;2022</span>
        <span class="track__what">Postdoctoral researcher, visual perception for robotics
          <span class="track__where">Istituto Italiano di Tecnologia, Genova.</span>
        </span>
      </li>
      <li class="track__row">
        <span class="track__years">2018&ndash;2020</span>
        <span class="track__what">Postdoctoral researcher, machine learning for cellular image analysis
          <span class="track__where">IBM Research Almaden, San Jose, California.</span>
        </span>
      </li>
      <li class="track__row">
        <span class="track__years">2018</span>
        <span class="track__what">PhD in Bioengineering and Robotics, University of Genova
          <span class="track__where">Thesis: <em>Estimating Functional Connectivity and Topology in Large-scale Neuronal Assemblies: Statistical and Computational Methods.</em> Awarded the GNB &ldquo;Alberto Mazzoldi&rdquo; prize and published in the Springer Theses series.</span>
        </span>
      </li>
      <li class="track__row">
        <span class="track__years">2014</span>
        <span class="track__what">MSc in Bioengineering, summa cum laude
          <span class="track__where">University of Genova.</span>
        </span>
      </li>
    </ul>
  </section>

  <!-- ============================================================ -->
  <section class="section">
    <h2 class="section__title">Working with me</h2>

    <div class="callout">
      <p>I am looking for PhD students and postdocs interested in fairness, medical imaging, and learning with limited data. If your background is in machine learning, computer vision, bioengineering or a related area, get in touch &mdash; tell me which of the threads above interests you and why.</p>
      <p><a class="link" href="{{ base_path }}/news/">Current openings</a> &nbsp;&middot;&nbsp; <a class="link" href="https://malga.unige.it/#open-positions">All positions at MaLGa</a></p>
    </div>
  </section>

</div>
