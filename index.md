---
layout: null
---
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="The AKBC workshop at ACL 2027 in Kyoto, Japan.">
    <title>AKBC 2027 · Knowledge at the Center</title>
    <style>
      :root {
        color-scheme: light;
        font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
        color: #172c32;
        background: #18343a;
        font-synthesis: none;
        text-rendering: optimizeLegibility;
      }

      * {
        box-sizing: border-box;
      }

      html {
        scroll-behavior: smooth;
      }

      body {
        min-width: 320px;
        margin: 0;
        background: #18343a url("assets/kyoto-landscape.svg") center / cover fixed;
      }

      a {
        color: inherit;
      }

      .skip-link {
        position: absolute;
        top: -5rem;
        left: 1rem;
        z-index: 2;
        padding: 0.75rem 1rem;
        background: #fff;
      }

      .skip-link:focus {
        top: 1rem;
      }

      .page {
        min-height: 100vh;
        padding: clamp(1rem, 4vw, 3.5rem);
        background: linear-gradient(90deg, rgb(14 36 40 / 76%), rgb(14 36 40 / 38%) 60%, rgb(14 36 40 / 15%));
      }

      .site-header,
      main,
      footer {
        width: min(100%, 1080px);
        margin-inline: auto;
      }

      .site-header {
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 2rem;
        color: #fff;
      }

      .wordmark {
        font-size: 1rem;
        font-weight: 750;
        letter-spacing: 0.08em;
        text-decoration: none;
      }

      nav {
        display: flex;
        flex-wrap: wrap;
        gap: clamp(1rem, 3vw, 2rem);
      }

      nav a {
        color: #f1f4ed;
        font-size: 0.9rem;
        text-decoration-thickness: 1px;
        text-underline-offset: 0.3em;
      }

      .hero {
        max-width: 740px;
        padding: clamp(5rem, 16vh, 10rem) 0 clamp(4rem, 12vh, 8rem);
        color: #fff;
      }

      .eyebrow {
        margin: 0 0 1rem;
        color: #f0c79b;
        font-size: 0.78rem;
        font-weight: 750;
        letter-spacing: 0.17em;
        text-transform: uppercase;
      }

      h1 {
        max-width: 10ch;
        margin: 0;
        font-family: Georgia, "Times New Roman", serif;
        font-size: clamp(3.5rem, 10vw, 7.5rem);
        font-weight: 500;
        letter-spacing: -0.055em;
        line-height: 0.95;
      }

      .hero-summary {
        max-width: 42rem;
        margin: 1.5rem 0 0;
        color: #f2f0e9;
        font-size: clamp(1.1rem, 2.2vw, 1.4rem);
        line-height: 1.65;
      }

      .event-meta {
        display: flex;
        flex-wrap: wrap;
        gap: 0.75rem 2rem;
        margin-top: 2.25rem;
        color: #fff;
        font-weight: 650;
      }

      .event-meta span::before {
        margin-right: 0.6rem;
        color: #f0c79b;
        content: "—";
      }

      .content {
        display: grid;
        grid-template-columns: minmax(0, 1.1fr) minmax(260px, 0.9fr);
        gap: clamp(2rem, 6vw, 5rem);
        padding: clamp(2rem, 6vw, 4.5rem);
        background: #fbfaf6;
        box-shadow: 0 1.5rem 5rem rgb(5 22 25 / 25%);
      }

      section + section {
        margin-top: 2.5rem;
      }

      h2 {
        margin: 0 0 1rem;
        color: #a24e3f;
        font-family: Georgia, "Times New Roman", serif;
        font-size: 1.7rem;
        font-weight: 500;
      }

      .content p {
        max-width: 42rem;
        margin: 0;
        color: #46575a;
        line-height: 1.8;
      }

      .organizers {
        margin: 0;
        padding: 0;
        list-style: none;
      }

      .organizers li {
        padding: 0.75rem 0;
        border-bottom: 1px solid #e4e1d9;
        line-height: 1.55;
      }

      .organizers li:last-child {
        border-bottom: 0;
      }

      .organizers sup {
        color: #a24e3f;
        font-weight: 700;
      }

      .affiliations {
        margin: 1.25rem 0 0;
        padding-left: 1.25rem;
        color: #657477;
        font-size: 0.9rem;
        line-height: 1.8;
      }

      footer {
        padding: 1.5rem 0 0.25rem;
        color: #e6e8df;
        font-size: 0.8rem;
        line-height: 1.6;
      }

      footer a {
        text-underline-offset: 0.2em;
      }

      @media (max-width: 700px) {
        .site-header {
          align-items: flex-start;
          flex-direction: column;
          gap: 1rem;
        }

        .content {
          grid-template-columns: 1fr;
        }

        .page {
          background: linear-gradient(180deg, rgb(14 36 40 / 73%), rgb(14 36 40 / 36%) 65%, rgb(14 36 40 / 12%));
        }
      }

      @media (prefers-reduced-motion: reduce) {
        html {
          scroll-behavior: auto;
        }
      }
    </style>
  </head>
  <body>
    <a class="skip-link" href="#main-content">Skip to content</a>
    <div class="page">
      <header class="site-header">
        <a class="wordmark" href="#top">AKBC · 2027</a>
        <nav aria-label="Main navigation">
          <a href="#about">About</a>
          <a href="#event">Event details</a>
          <a href="#organizers">Organizers</a>
        </nav>
      </header>

      <main id="main-content">
        <section class="hero" id="top" aria-labelledby="page-title">
          <p class="eyebrow">At ACL 2027 · Kyoto, Japan</p>
          <h1 id="page-title">Knowledge at the center.</h1>
          <p class="hero-summary">The AKBC workshop brings together ideas and research around knowledge and language.</p>
          <div class="event-meta" id="event">
            <span>August 18 or 19, 2027</span>
            <span>Kyoto, Japan</span>
          </div>
        </section>

        <div class="content">
          <div>
            <section id="about" aria-labelledby="about-title">
              <h2 id="about-title">About the workshop</h2>
              <p>Workshop information, including the call for papers and program, will be announced here.</p>
            </section>

            <section aria-labelledby="details-title">
              <h2 id="details-title">Event details</h2>
              <p>AKBC 2027 will be held alongside ACL in Kyoto, Japan. The workshop date is to be confirmed.</p>
            </section>
          </div>

          <section id="organizers" aria-labelledby="organizers-title">
            <h2 id="organizers-title">Organizers</h2>
            <ul class="organizers">
              <li>Jan-Christoph Kalo<sup>1</sup></li>
              <li>Russa Biswas<sup>2</sup></li>
              <li>Simon Razniewski<sup>3</sup></li>
              <li><strong>Fabian M. Suchanek<sup>4</sup></strong></li>
              <li><strong>Andrew McCallum<sup>5</sup></strong></li>
            </ul>
            <ol class="affiliations">
              <li>University of Amsterdam</li>
              <li>Aalborg University</li>
              <li>ScaDS.AI &amp; TU Dresden</li>
              <li>Télécom Paris, Institut Polytechnique de Paris</li>
              <li>University of Massachusetts Amherst</li>
            </ol>
          </section>
        </div>
      </main>

      <footer>
        <p>Kyoto background illustration created for this site. No external image source or attribution required.</p>
      </footer>
    </div>
  </body>
</html>
