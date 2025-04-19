---
layout: home
title: ""
---

<style>
  html {
    scroll-behavior: smooth;
  }

  body {
    background-color: #ECECEC;
  }
  
  .site-title,
  .site-footer,
  .footer-col-wrapper,
  .footer-heading {
    display: none !important;
  }
  
  .banner-wrapper {
    background-color: #00205B;
    color: #ffffff;
    padding: 2rem;
    text-align: center;
    margin-bottom: 0;
    font-family: 'Segoe UI', sans-serif;
    border-top: 8px solid #FFC600;
    border-bottom: 8px solid #FFC600;
    box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.25);
  }

  .banner-wrapper h1 {
    margin: 0;
    font-size: 2.5rem;
    font-weight: 800;
  }

  .banner-wrapper h2 {
    margin: 0.3rem 0;
    font-size: 1.5rem;
    font-weight: 600;
    color: #FFC600;
  }

  .banner-wrapper h3 {
    margin: 0.2rem 0;
    font-size: 1.2rem;
    font-style: italic;
    font-weight: 400;
    color: #FFC600;
  }

  .sticky-nav {
    position: sticky;
    top: 0;
    z-index: 100;
    background-color: #112B5C;
    padding: 0.5rem 1rem 0.4rem 1rem;
    font-family: 'Segoe UI', sans-serif;
    border-bottom: 4px solid #FFC600;
    text-align: center;
    margin-top: 1rem;
    border-top: 1px solid #FFC600;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.2rem;
  }
  
  .sticky-nav a {
    color: #FFC600;
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
  }

  .section-card h2 {
    border-left: 5px solid #FFC600;
    padding-left: 1rem;
    margin-top: 0;
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
    background-color: #00205B;
    color: #FFC600;
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
</style>

<div class="banner-wrapper">
  <h1>Nick Crescentini</h1>
  <h2>SNHU</h2>
  <h3>CS499 Capstone Project &amp; ePortfolio</h3>
</div>

<div class="sticky-nav">
  <a href="#overview">Capstone Overview</a>
  <a href="#code-review">Code Review</a>
  <a href="#enh1">Enhancement 1</a>
  <a href="#enh2">Enhancement 2</a>
  <a href="#enh3">Enhancement 3</a>
  <a href="#self-assessment">Professional Self-Assessment</a>
</div>

<div class="section-card">
  <p>
    Welcome to my ePortfolio! The capstone begins with the original codebase from my first project submission at SNHU. The project is a text-based adventure game written in Python, where the player explores a castle to collect items that will help them defeat a hidden dragon. For this capstone, I chose to return to that original project and use it as the foundation for three major enhancements in the following areas:
  </p>
  <ul>
    <li><strong>Software Design & Engineering</strong> – Refactored the structure and added a modular start menu system</li>
    <li><strong>Algorithms & Data Structures</strong> – Replaced inefficient item logic with a dynamic dictionary-based system</li>
    <li><strong>Databases</strong> – Added the ability to save/load game progress using an SQLite database</li>
  </ul>
  <p>
    Using this same project for all three enhancements is symbolic of my journey through the Computer Science program. It represents both my first and final submissions, and highlights how my technical skills, design thinking, and confidence have grown. Each enhancement builds upon the last to transform a simple script into a more robust, scalable, and professional program.
  </p>
</div>

<div class="section-card" id="overview">
  <h2>Capstone Overview</h2>
  <p>TODO</p>
  <!-- Link to capstone repo coming soon -->
</div>

<div class="section-card" id="code-review">
  <h2>Code Review</h2>
  <p>TODO</p>
  <!-- Link to code review coming soon -->
</div>

<div class="section-card" id="enh1">
  <h2>
    <a href="https://github.com/ncrescentini/CS499-Capstone/tree/main/enhancement1" target="_blank">
      Enhancement One – Software Design and Engineering
    </a>
  </h2>
  <p>
    Refactors the original IT-140 artifact by adding a menu system, improving modularity, and separating gameplay and logic functions.
    Click to view the <strong>README</strong> and enhanced codebase.
  </p>
</div>

<div class="section-card" id="enh2">
  <h2><a href="https://ncrescentini.github.io/CS499-Capstone/enhancement2/" target="_blank" style="text-decoration: none; color: #3b5fb2;">
    Enhancement Two – Algorithms and Data Structures
  </a></h2>
  <p>
    Refactors the item detection logic by replacing inefficient if/elif chains with a scalable dictionary-based algorithm. 
    Enhances maintainability, efficiency, and lays groundwork for more complex game logic. 
    Click to view the <strong>README</strong> and enhanced codebase.
  </p>
</div>

<div class="section-card" id="enh3">
  <h2>
    <a href="https://ncrescentini.github.io/CS499-Capstone/enhancement3/" target="_blank" style="text-decoration: none; color: #3b5fb2;">
      Enhancement Three – Databases
    </a>
  </h2>
  <p>
    Adds SQLite-based save/load functionality by integrating a custom database into the original program.
    Demonstrates ability to design new features, build scalable architecture, and apply database principles.
    Click to view the <strong>README</strong> and enhanced codebase.
  </p>
</div>

<div class="section-card" id="self-assessment">
  <h2>Professional Self-Assessment</h2>
  <p>TODO</p>
  <!-- Self-assessment link coming soon -->
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
