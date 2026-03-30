---
layout: default
title: Gaiden
---

<style>
  .gaiden-intro { color: #888; font-style: italic; margin-bottom: 2.5rem; }

  .section-header {
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: #aaa;
    margin: 3rem 0 1rem;
    padding-bottom: 0.4rem;
    border-bottom: 1px solid #eee;
  }

  .section-subheader {
    font-size: 0.7rem;
    font-weight: 600;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #bbb;
    margin: 1.5rem 0 0.75rem;
  }

  /* Appearance cards — horizontal feel */
  .card-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(260px, 1fr)); gap: 1.2rem; }
  .card {
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    padding: 1.2rem 1.4rem;
    text-decoration: none;
    color: inherit;
    display: block;
    transition: box-shadow 0.15s, border-color 0.15s;
  }
  .card:hover { box-shadow: 0 4px 16px rgba(0,0,0,0.10); border-color: #aaa; }
  .card-tag {
    font-size: 0.7rem;
    font-weight: 600;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: #888;
    margin-bottom: 0.4rem;
  }
  .card-title { font-size: 1rem; font-weight: 600; margin-bottom: 0.4rem; }
  .card-desc { font-size: 0.875rem; color: #555; line-height: 1.5; }

  /* Side quest section rows */
  .quest-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 1rem; }
  .quest-tile {
    border-radius: 8px;
    padding: 1.2rem 1.4rem;
    text-decoration: none;
    color: inherit;
    display: block;
    transition: opacity 0.15s;
  }
  .quest-tile:hover { opacity: 0.8; }
  .quest-tile .qt-icon { font-size: 1.6rem; margin-bottom: 0.5rem; }
  .quest-tile .qt-title { font-weight: 600; margin-bottom: 0.3rem; }
  .quest-tile .qt-desc { font-size: 0.82rem; color: #555; line-height: 1.45; }

  .qt-japanese { background: #fff8f0; border: 1px solid #f5d9b8; }
  .qt-books    { background: #f3f7ff; border: 1px solid #c8d8f8; }
  .qt-misc     { background: #f6f6f6; border: 1px solid #ddd; }

  .misc-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 1rem; }
  .misc-tile {
    border-radius: 8px;
    padding: 1.2rem 1.4rem;
    text-decoration: none;
    color: inherit;
    display: block;
    transition: opacity 0.15s;
  }
  .misc-tile:hover { opacity: 0.8; }
  .misc-tile .mt-icon { font-size: 1.6rem; margin-bottom: 0.5rem; }
  .misc-tile .mt-title { font-weight: 600; margin-bottom: 0.3rem; }
  .misc-tile .mt-desc { font-size: 0.82rem; color: #555; line-height: 1.45; }

</style>

# Gaiden

<p class="gaiden-intro">Gotta squeeze this stuff in somewhere...</p>

<div class="section-header">Appearances</div>
<div class="section-subheader">I'm a popular guy; here are some other places I show up.</div>


<div class="card-grid">

  <a class="card" href="https://www.ncsa.illinois.edu/2025/05/29/spin-closes-out-a-year-of-accomplishments-and-recognizes-the-outstanding-work-of-the-programs-interns-and-mentors/" target="_blank" rel="noopener">
    <div class="card-tag">NCSA @ Illinois &middot; 2025</div>
    <div class="card-title">SPIN Year-End Recognition</div>
    <div class="card-desc">The National Center for Supercomputing Applications wraps up an awesome year of the SPIN program and shouts out standout interns and mentors.</div>
  </a>

</div>

<div class="section-header">Side Quests</div>

<div class="quest-grid">

  <a class="quest-tile qt-japanese" href="/gaiden/japanese">
    <div class="qt-icon">🈶</div>
    <div class="qt-title">Learning Japanese</div>
    <div class="qt-desc">notes, resources, ramblings.</div>
  </a>

  <a class="quest-tile qt-books" href="/gaiden/books">
    <div class="qt-icon">📖</div>
    <div class="qt-title">Books</div>
    <div class="qt-desc">reccs and reviews</div>
  </a>

</div>

<div class="section-header">Misc</div>

<div class="misc-grid">

  <a class="misc-tile qt-misc" href="/gaiden/latex-macros">
    <div class="mt-icon">∑</div>
    <div class="mt-title">LaTeX Macros</div>
    <div class="mt-desc">my personal macro setup</div>
  </a>

</div>
