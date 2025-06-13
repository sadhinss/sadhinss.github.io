---
title: "About Me"
permalink: /about/
layout: single
author_profile: false
---

<style>
  .bio-container {
    display: flex;
    align-items: flex-start;
    justify-content: center;
    gap: 3rem;
    max-width: 1200px; /* ⬅️ Wider than before */
    margin: 2rem auto;
    padding: 0 2rem;
    flex-wrap: nowrap; /* ⬅️ Prevent stacking */
  }

  .bio-image {
    flex-shrink: 0;
  }

  .bio-image img {
    width: 260px;
    border-radius: 12px;
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
  }

  .bio-text {
    font-size: 1.05rem;
    line-height: 1.8;
    max-width: 800px; /* ⬅️ More breathing room */
  }

  .bio-text p {
    margin-bottom: 1.25rem;
  }

  @media screen and (max-width: 900px) {
    html {
      overflow-x: auto;
    }

    .bio-container {
      padding: 1rem 2rem;
    }

    .bio-text {
      min-width: 300px;
    }
  }
</style>

<div class="bio-container">
  <div class="bio-image">
    <img src="/assets/images/biopic.jpg" alt="Shams Sadhin headshot" />
  </div>

  <div class="bio-text">
    <p>Hi! I’m <strong>Shams Sadhin</strong>, an undergraduate at the University of Cincinnati, double majoring in <em>Economics</em> and <em>Business Analytics</em> with a minor in <em>Mathematics</em>.</p>

    <p>I’m passionate about applying data-driven approaches to solve real-world problems, particularly in urban economics, real estate, and policy research.</p>

    <p>My experience includes being a research assistant for Dr. Gary Painter at the Lindner Real Estate Center, Resident Advisor, and PACE Leader. I love combining academic research with hands-on application, and I’m exploring opportunities in data analytics, policy, and finance.</p>

    <p>Outside of work, I enjoy tennis, badminton, basketball, traveling, watching TV shows, and eating!</p>
  </div>
</div>
