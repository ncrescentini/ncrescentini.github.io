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
    text-decoration: none;
    font-weight: 600;
    font-size: 0.85rem;
    white-space: nowrap;
    transition: color 0.2s ease;
  }
  
  .sticky-nav a:hover {
    color: #ffffff;
  }

  .section-card {
    background: #ffffff;
    padding: 1.5rem;
    margin: 2rem auto;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    max-width: 800px;
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
  <p>Welcome to my ePortfolio, which showcases my CS499 Capstone Project and other work from the SNHU Computer Science Program.</p>
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
  <h2>Enhancement One – Software Design and Engineering</h2>
  <p>TODO</p>
  <!-- Enhancement 1 link coming soon -->
</div>

<div class="section-card" id="enh2">
  <h2>Enhancement Two – Algorithms and Data Structures</h2>
  <p>TODO</p>
  <!-- Enhancement 2 link coming soon -->
</div>

<div class="section-card" id="enh3">
  <h2>Enhancement Three – Databases</h2>
  <p>TODO</p>
  <!-- Enhancement 3 link coming soon -->
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
