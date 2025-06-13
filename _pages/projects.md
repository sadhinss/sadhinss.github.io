---
title: "Projects"
permalink: /projects/
layout: single
---

<style>
.card-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  margin-top: 2rem;
}

.project-card {
  width: 300px;
  height: 370px;
  position: relative;
  overflow: hidden;
  border-radius: 16px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.08);
  transition: transform 0.3s ease;
  cursor: pointer;
}
.project-card:hover {
  transform: translateY(-6px);
}
.project-card img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}
.project-overlay {
  position: absolute;
  bottom: 0;
  background: rgba(0,0,0,0.7);
  color: white;
  padding: 1rem;
  width: 100%;
  transform: translateY(100%);
  transition: transform 0.3s ease;
  font-size: 0.9rem;
}
.project-card:hover .project-overlay {
  transform: translateY(0);
}
.project-title {
  position: absolute;
  top: 0;
  left: 0;
  background: rgba(0,0,0,0.6);
  color: #fff;
  padding: 0.5rem 1rem;
  font-size: 1.2rem;
  font-weight: bold;
  border-bottom-right-radius: 10px;
}
</style>

<div class="card-grid">

  <a href="/projects/job_shock/" class="project-card">
    <img src="/assets/images/projects/jobs-shock.jpg" alt="Job Shock Analysis">
    <div class="project-title">Job Shock</div>
    <div class="project-overlay">Manufacturing decline and population movement using CBP + OA data</div>
  </a>

  <a href="/projects/housing-inequality/" class="project-card">
    <img src="/assets/images/projects/housing-thumb.png" alt="Housing and Inequality">
    <div class="project-title">Housing Equity</div>
    <div class="project-overlay">Inequality in schools, property tax, and segregation in cities</div>
  </a>

  <a href="/projects/flavor-dashboard/" class="project-card">
    <img src="/assets/images/projects/flavor-thumb.png" alt="Flavor Analytics">
    <div class="project-title">Flavor Dashboard</div>
    <div class="project-overlay">Power BI dashboard for sensory and flavor replacement systems</div>
  </a>

</div>
