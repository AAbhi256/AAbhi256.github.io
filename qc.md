---
layout: default
title: Quantum Computing
---

<style>
  .section-header {
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: #aaa;
    margin: 2.5rem 0 1rem;
    padding-bottom: 0.4rem;
    border-bottom: 1px solid #eee;
  }
  .writeup-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(260px, 1fr)); gap: 1.2rem; }
  .writeup-card {
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    padding: 1.2rem 1.4rem;
    text-decoration: none;
    color: inherit;
    display: block;
    transition: box-shadow 0.15s, border-color 0.15s;
  }
  .writeup-card:hover { box-shadow: 0 4px 16px rgba(0,0,0,0.10); border-color: #aaa; }
  .writeup-card .wc-title { font-weight: 600; margin-bottom: 0.4rem; }
  .writeup-card .wc-desc { font-size: 0.875rem; color: #555; line-height: 1.5; }
  .course-block { margin-bottom: 2rem; }
  .course-title { font-weight: 600; font-size: 1rem; margin-bottom: 0.75rem; }
  .resource-list { list-style: none; padding: 0; margin: 0; display: flex; flex-direction: column; gap: 0.5rem; }
  .resource-list li a {
    display: flex; align-items: center; gap: 0.5rem;
    padding: 0.6rem 0.9rem;
    border: 1px solid #e0e0e0; border-radius: 6px;
    text-decoration: none; color: inherit; font-size: 0.9rem;
    transition: box-shadow 0.15s, border-color 0.15s;
  }
  .resource-list li a:hover { box-shadow: 0 2px 10px rgba(0,0,0,0.08); border-color: #aaa; }
  .resource-list li a .res-icon { font-size: 0.8rem; color: #aaa; flex-shrink: 0; }
  .resource-list li a .res-label { flex: 1; }
  .link-list { list-style: none; padding: 0; margin: 0; display: flex; flex-direction: column; gap: 0.5rem; }
  .link-list li a {
    display: flex; align-items: center; gap: 0.5rem;
    padding: 0.6rem 0.9rem;
    border: 1px solid #e0e0e0; border-radius: 6px;
    text-decoration: none; color: inherit; font-size: 0.9rem;
    transition: box-shadow 0.15s, border-color 0.15s;
  }
  .link-list li a:hover { box-shadow: 0 2px 10px rgba(0,0,0,0.08); border-color: #aaa; }
  .link-list li a .ll-label { flex: 1; }
  .link-list li a .ll-url { font-size: 0.75rem; color: #aaa; }
</style>

# Quantum Computing

<div class="section-header">Quantum Error Correction</div>
<!-- <img src="/assets/qecc-banner.png" alt="Quantum Error Correction" style="width:50%; border-radius:6px; margin-bottom:1rem;"> -->

<div class="writeup-grid">

  <a class="writeup-card" href="/qc/surface-codes">
    <div class="wc-title">Surface Codes</div>
    <div class="wc-desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>
  </a>

</div>

<div class="section-header">TCS</div>

<div class="writeup-grid">

  <a class="writeup-card" href="/qc/linear-programming">
    <div class="wc-title">Linear Programming</div>
    <div class="wc-desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>
  </a>

</div>

<div class="section-header">Class Notes &amp; Presentations</div>

<div class="course-block">
  <div class="course-title">Math 595</div>
  <ul class="resource-list">
    <li>
      <a href="https://felixleditzky.info/teaching/FT25/characters.pdf" target="_blank" rel="noopener">
        <span class="res-icon">PDF</span>
        <span class="res-label">Characters of Finite Groups</span>
      </a>
    </li>
  </ul>
</div>

<div class="course-block">
  <div class="course-title">CS 579</div>
  <ul class="resource-list">
    <li>
      <a href="https://granha.github.io/cs579_fall25/Lecture_07.pdf" target="_blank" rel="noopener">
        <span class="res-icon">PDF</span>
        <span class="res-label">From Graph Isomorphism to Interactive Proofs and the PCP Theorem: Randomness, Verification, and Hardness of Approximation</span>
      </a>
    </li>
  </ul>
</div>

<div class="section-header">Resources</div>

<ul class="link-list">
  <li>
    <a href="https://people.eecs.berkeley.edu/~jswright/quantumcodingtheory24/" target="_blank" rel="noopener">
      <span class="ll-label">Quantum Coding Theory — John Wright (UC Berkeley, 2024)</span>
      <span class="ll-url">people.eecs.berkeley.edu</span>
    </a>
  </li>
</ul>
