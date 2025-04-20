---
layout: home
title: ""
---

<style>
  html {
    scroll-behavior: smooth;
  }

  body {
    background-color: #F4F7FB;
  }

  .site-title,
  .site-footer,
  .footer-col-wrapper,
  .footer-heading {
    display: none !important;
  }

  .banner-wrapper {
    background: linear-gradient(135deg, #00244E, #003F88);
    color: #ffffff;
    padding: 2rem;
    text-align: center;
    margin-bottom: 0;
    font-family: 'Segoe UI', sans-serif;
    border-top: 8px solid #FDB913;
    border-bottom: 8px solid #FDB913;
    box-shadow: 0px 6px 14px rgba(0, 0, 0, 0.2);
  }

  .banner-wrapper h1 {
    margin: 0;
    font-size: 2.5rem;
    font-weight: 800;
    text-shadow: 1px 1px 6px rgba(0, 0, 0, 0.35);
  }

  .banner-wrapper h2 {
    margin: 0.3rem 0;
    font-size: 1.5rem;
    font-weight: 600;
    color: #FDB913;
    text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.3);
  }

  .banner-wrapper h3 {
    margin: 0.2rem 0;
    font-size: 1.2rem;
    font-style: italic;
    font-weight: 400;
    color: #FDB913;
    text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.3);
  }

  .sticky-nav {
    position: sticky;
    top: 0;
    z-index: 100;
    background-color: #00244E;
    padding: 0.5rem 1rem 0.4rem 1rem;
    font-family: 'Segoe UI', sans-serif;
    border-bottom: 4px solid #FDB913;
    text-align: center;
    margin-top: 1rem;
    border-top: 1px solid #FDB913;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.2rem;
  }

  .sticky-nav a {
    color: #FDB913;
    text-decoration: underline;
    text-underline-offset: 2px;
    font-weight: 600;
    font-size: 0.85rem;
    white-space: nowrap;
    cursor: pointer;
    transition: color 0.2s ease, text-decoration 0.2s ease;
  }

  .sticky-nav a:hover {
    color: #ffffff;
    text-decoration: underline;
  }

  .section-card {
    background: #ffffff;
    padding: 1.5rem;
    margin: 2rem auto;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    max-width: 800px;
    scroll-margin-top: 120px;
    border: 1px solid #D8D8D8;
    opacity: 0;
    transform: translateY(4px);
    transition: opacity 0.6s ease-out, transform 0.6s ease-out, background-color 0.3s ease;
  }

  .section-card.visible {
    opacity: 1;
    transform: none;
  }

  .section-card h2 {
    border-left: 5px solid #FDB913;
    padding-left: 1rem;
    margin-top: 0;
    color: #00244E;
  }

  .clickable-card {
    cursor: pointer;
  }

  .clickable-card:hover {
    background-color: #FAFAFF;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    transform: translateY(-4px);
    border: 1px solid #FDB913;
  }

  .clickable-card:active {
    transform: translateY(1px);
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  footer {
    text-align: center;
    font-size: 0.85rem;
    color: #666;
    padding: 2rem 0 1rem 0;
    margin-top: 4rem;
  }

  .back-to-top {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-color: #00244E;
    color: #FDB913;
    padding: 10px 14px;
    border: none;
    border-radius: 5px;
    font-weight: bold;
    cursor: pointer;
    font-size: 0.8rem;
    box-shadow: 0px 2px 8px rgba(0,0,0,0.2);
    display: none;
    z-index: 200;
    transition: background-color 0.2s ease;
  }

  .back-to-top:hover {
    background-color: #001B47;
  }

  .video-container {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
    max-width: 100%;
  }

  .video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
</style>

<div class="banner-wrapper">
  <h1>Nick Crescentini</h1>
  <h2>SNHU</h2>
  <h3>CS499 Capstone Project & ePortfolio</h3>
</div>

<div class="sticky-nav">
  <a href="#welcome">Welcome</a>
  <a href="#code-review">Code Review</a>
  <a href="#enh1">Enhancement 1</a>
  <a href="#enh2">Enhancement 2</a>
  <a href="#enh3">Enhancement 3</a>
  <a href="#self-assessment">Professional Self-Assessment</a>
</div>

<div class="section-card" id="welcome">
  <h2 style="border-left: 5px solid #FDB913; padding-left: 1rem; color: #00244E; margin-top: 0;">
  Welcome to my ePortfolio!
  </h2>
  <p>My capstone journey begins with the very first project I submitted at SNHU: a text-based adventure game written in Python. In the game, the player explores a castle in search of six items that will help them defeat a hidden dragon.</p>
  <p>For this capstone, I chose to revisit and enhance that original codebase, both to honor where my programming journey began and to demonstrate how far I've come. In this project, I've completed three major enhancements, each aligned with a different area of computer science:</p>
<ul>
  <li><strong>Enhancement One – Software Design & Engineering</strong>: Improved modularity and user experience by introducing a start menu system and restructuring gameplay logic into dedicated functions.</li>
  <li><strong>Enhancement Two – Algorithms & Data Structures</strong>: Replaced inefficient <code>if</code>/<code>elif</code> chains with a dynamic dictionary-based system, improving maintainability and scalability.</li>
  <li><strong>Enhancement Three – Databases</strong>: Integrated a custom SQLite database to add save/load functionality, introducing persistent storage and opening the door for future features.</li>
</ul>
  <p>Using this same project across all three enhancements is symbolic of my growth throughout the Computer Science program. It represents both my starting point and my final achievement—showcasing not just the technical skills I’ve gained, but also how my design thinking, coding practices, and confidence have evolved.</p>
</div>

<div class="section-card" id="code-review">
  <h2>Code Review</h2>
  <p>This video walks through the original artifacts used in my CS499 Capstone, identifying areas for improvement and outlining the planned enhancements. It includes a walkthrough along with code commentary and goals.</p>
  <p><strong>View Original Artifacts:</strong> <a href="https://github.com/ncrescentini/CS499-Capstone/blob/main/InitialCodebase/TrogdorsRevenge.py" target="_blank">TrogdorsRevenge.py on GitHub</a></p>
  <div class="video-container">
    <iframe src="https://player.vimeo.com/video/1076984032?h=1a3232b6d4&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479"
      frameborder="0"
      allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media"
      title="Initial Code Base Review"
      allowfullscreen>
    </iframe>
  </div>
</div>

<div class="section-card clickable-card" id="enh1" onclick="window.open('https://github.com/ncrescentini/CS499-Capstone/tree/main/enhancement1', '_blank')">
  <h2>Enhancement One – Software Design and Engineering</h2>
  <p>Refactors the original IT-140 artifact by adding a menu system, improving modularity, and separating gameplay and logic functions. Click to view the <strong>Enhancement One Codebase and Narrative.</strong></p>
</div>

<div class="section-card clickable-card" id="enh2" onclick="window.open('https://github.com/ncrescentini/CS499-Capstone/tree/main/enhancement2', '_blank')">
  <h2>Enhancement Two – Algorithms and Data Structures</h2>
  <p>Refactors the item detection logic by replacing inefficient if/elif chains with a scalable dictionary-based algorithm. Enhances maintainability, efficiency, and lays groundwork for more complex game logic. Click to view the <strong>Enhancement Two Codebase and Narrative.</strong></p>
</div>

<div class="section-card clickable-card" id="enh3" onclick="window.open('https://github.com/ncrescentini/CS499-Capstone/tree/main/enhancement3', '_blank')">
  <h2>Enhancement Three – Databases</h2>
  <p>Adds SQLite-based save/load functionality by integrating a custom database into the original program. Demonstrates ability to design new features, build scalable architecture, and apply database principles. Click to view the <strong>Enhancement Three Codebase and Narrative.</strong></p>
</div>

<div class="section-card" id="self-assessment">
  <h2>Professional Self-Assessment</h2>
  <p>TODO</p>
</div>

<footer>
  Nick Crescentini • CS499 Capstone at SNHU • Built with GitHub Pages
</footer>

<button class="back-to-top" onclick="window.scrollTo({ top: 0, behavior: 'smooth' });">
  ↑ Back to Top
</button>

<script>
  window.addEventListener('scroll', function () {
    const btn = document.querySelector('.back-to-top');
    btn.style.display = window.scrollY > 300 ? 'block' : 'none';
  });
</script>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    const cards = document.querySelectorAll('.section-card');

    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
          observer.unobserve(entry.target);
        }
      });
    }, {
      threshold: 0.1
    });

    cards.forEach(card => {
      observer.observe(card);
    });
  });
</script>
