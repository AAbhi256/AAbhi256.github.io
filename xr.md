---
layout: default
title: Game Dev/XR
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
  .section-subheader {
    font-size: 0.7rem;
    font-weight: 600;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #bbb;
    margin: 1.5rem 0 0.75rem;
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

  .showcase-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(320px, 1fr)); gap: 2rem; }
  .showcase-item { display: flex; flex-direction: column; gap: 0.75rem; }
  .showcase-video {
    position: relative;
    width: 100%;
    padding-bottom: 56.25%; /* 16:9 */
    border-radius: 8px;
    overflow: hidden;
    background: #000;
  }
  .showcase-video iframe {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    border: none;
  }
  .showcase-icon {
    width: 160px;
    height: 160px;
    position: relative;
    border-radius: 8px;
    border: 1px solid #e0e0e0;
    background: #f9f9f9;
  }
  .showcase-icon .si-inner {
    position: absolute;
    inset: 0;
    border-radius: 8px;
    overflow: hidden;
  }
  .showcase-icon .si-inner img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  .showcase-meta { display: flex; flex-direction: column; gap: 0.3rem; }
  .showcase-title { font-weight: 600; font-size: 1rem; }
  .showcase-links { display: flex; gap: 0.75rem; flex-wrap: wrap; }
  .showcase-link {
    font-size: 0.8rem;
    padding: 0.3rem 0.7rem;
    border: 1px solid #ddd;
    border-radius: 4px;
    text-decoration: none;
    color: #333;
    transition: border-color 0.15s, box-shadow 0.15s;
  }
  .showcase-link:hover { border-color: #aaa; box-shadow: 0 1px 6px rgba(0,0,0,0.08); }
</style>

# Game Dev/XR

<div class="section-header">Game Development</div>

<div class="writeup-grid">

  <a class="writeup-card" href="/xr/game-dev-philosophy">
    <div class="wc-title">On Learning Game Dev</div>
    <div class="wc-desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>
  </a>

</div>

<div class="section-header">Extended, Mixed, Virtual & Augmented Reality</div>
<div class="section-subheader">Or, the reason why I ought to switch from glasses to contact lenses</div>

<div class="writeup-grid">

  <a class="writeup-card" href="/xr/xr-intro">
    <div class="wc-title">Why XR</div>
    <div class="wc-desc">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur excepteur sint.</div>
  </a>

</div>

<div class="section-header">Showcase</div>

<div class="showcase-grid">

  <!-- <div class="showcase-item">
    <div class="showcase-video">
      <iframe src="https://www.youtube.com/embed/YOUTUBE_VIDEO_ID" allowfullscreen loading="lazy"></iframe>
    </div>
    <div class="showcase-meta">
      <div class="showcase-title">Game Title</div>
      <div class="showcase-links">
        <a class="showcase-link" href="#" target="_blank" rel="noopener">itch.io</a>
        <a class="showcase-link" href="#" target="_blank" rel="noopener">GitHub</a>
      </div>
    </div>
  </div> -->


  <div class="showcase-item">
    <div class="showcase-meta">
      <div class="showcase-title">Devices &amp; Dragons</div>
      <div class="showcase-links">
        <a class="showcase-link" href="https://trickster-forge.itch.io/devices-and-dragons" target="_blank" rel="noopener">itch.io</a>
        <a class="showcase-link" href="https://github.com/Lophane/GMTK-Built-to-Scale" target="_blank" rel="noopener">GitHub</a>
      </div>
    </div>
    <div class="showcase-icon">
      <div class="si-inner"><img src="/assets/d&d.png" alt="Devices &amp; Dragons"></div>
    </div>
  </div>

</div>
