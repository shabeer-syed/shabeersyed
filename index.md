---
layout: post
title: Shabeer Syed
categories: [About]
---

<style>
  /* Modern CSS Reset & Typography tailored for this page */
  .syed-modern-layout {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    color: #2d3748;
    line-height: 1.7;
    max-width: 850px;
    margin: 0 auto;
  }

  .syed-modern-layout p {
    color: #4a5568;
    font-size: 1.05rem;
  }

  /* Hero Section */
  .syed-hero {
    display: flex;
    align-items: center;
    gap: 2.5rem;
    margin-bottom: 3.5rem;
    padding-bottom: 2rem;
    border-bottom: 1px solid #e2e8f0;
  }
  
  .syed-hero-img {
    flex-shrink: 0;
    width: 180px;
    height: 180px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
    border: 4px solid white;
  }

  /* Role Cards */
  .syed-card {
    background: #ffffff;
    border: 1px solid #edf2f7;
    border-radius: 12px;
    padding: 2.5rem;
    margin-bottom: 2.5rem;
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .syed-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.08);
  }

  .syed-card-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 1.5rem;
    border-bottom: 2px solid #f7fafc;
    padding-bottom: 1rem;
  }

  .syed-card-header h2 {
    margin: 0;
    color: #1a202c;
    font-size: 1.5rem;
    font-weight: 600;
  }

  .syed-logo {
    max-height: 55px;
    max-width: 130px;
    object-fit: contain;
  }

  /* List Styling */
  .syed-list {
    list-style: none;
    padding-left: 0;
    margin: 0;
  }

  .syed-list > li {
    margin-bottom: 1.2rem;
    position: relative;
    padding-left: 1.5rem;
  }

  .syed-list > li::before {
    content: "•";
    color: #4299e1;
    font-weight: bold;
    font-size: 1.5rem;
    position: absolute;
    left: 0;
    top: -4px;
  }

  .syed-sublist {
    list-style-type: circle;
    color: #4a5568;
    margin-top: 0.8rem;
    padding-left: 1.5rem;
  }

  .syed-sublist li {
    margin-bottom: 0.5rem;
  }

  /* Accents & Buttons */
  .syed-link {
    color: #3182ce;
    text-decoration: none;
    font-weight: 500;
    border-bottom: 1px solid transparent;
    transition: border-color 0.2s;
  }
  
  .syed-link:hover {
    border-bottom: 1px solid #3182ce;
  }

  .syed-button {
    display: inline-block;
    margin-top: 1.5rem;
    padding: 0.75rem 1.5rem;
    background-color: #2b6cb0;
    color: #ffffff !important;
    text-decoration: none !important;
    border-radius: 8px;
    font-weight: 500;
    font-size: 0.95rem;
    transition: background-color 0.2s ease, transform 0.1s ease;
  }

  .syed-button:hover {
    background-color: #2c5282;
  }

  .syed-badge-nhs {
    display: inline-block;
    background-color: #005EB8;
    color: white;
    padding: 2px 8px;
    border-radius: 4px;
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 0.5px;
    margin-right: 8px;
    vertical-align: middle;
  }

  /* Mobile Responsiveness */
  @media (max-width: 768px) {
    .syed-hero {
      flex-direction: column;
      text-align: center;
      gap: 1.5rem;
    }
    .syed-card-header {
      flex-direction: column-reverse;
      gap: 1rem;
    }
    .syed-card {
      padding: 1.5rem;
    }
  }
</style>

<div class="syed-modern-layout">

  <!-- Hero / Bio Section -->
  <div class="syed-hero">
    <!-- Updated image URL here -->
    <img class="syed-hero-img" src="https://raw.githubusercontent.com/shabeer-syed/shabeersyed/refs/heads/master/images/shabeer%20syed.png" alt="Shabeer Syed" />
    <div>
      <p><strong>Clinical Psychologist</strong> specialising in child and adolescent mental health (CAMHS) and <strong>Senior Research Associate</strong> in Epidemiology at UCL Great Ormond Street Institute of Child Health.</p>
      <p>My research focuses on understanding the negative health effects of adverse childhood experiences (ACEs) and providing epidemiological evidence to inform policy change for improved care pathways for children and families affected by ACEs. This website is currently acting as a host for the domain name only, with the potential for future expansion.</p>
    </div>
  </div>

  <!-- Clinical Psychologist Card -->
  <div class="syed-card">
    <div class="syed-card-header">
      <h2>Clinical Psychologist</h2>
      <img class="syed-logo" src="https://raw.githubusercontent.com/shabeer-syed/shabeersyed/master/images/ox%20logo.png" alt="University of Oxford Logo"/>
    </div>
    <ul class="syed-list">
      <li>
        <strong>Doctor of Clinical Psychology (DClinPsych)</strong>, University of Oxford
        <ul class="syed-sublist">
          <li>HCPC registered, CBT Therapist BABCP Level 2 Accredited, Family & Systemic Training AFT Foundation Level, AMBIT Trained, NVR trained, ADOS-2 trained, ADI-R trained, EMDR trained, YMCA Level 3 Certificate in PT, etc.</li>
          <li>Specialise within adolescent outreach and high-risk young people with multimorbidity.</li>
          <li style="margin-top: 12px; list-style: none; padding-left: 0;">
            <span class="syed-badge-nhs">NHS</span> <em>I work only within the NHS</em>
          </li>
        </ul>
      </li>
    </ul>
  </div>

  <!-- Researcher Card -->
  <div class="syed-card">
    <div class="syed-card-header">
      <h2>Researcher</h2>
      <img class="syed-logo" src="https://raw.githubusercontent.com/shabeer-syed/shabeersyed/master/images/ucl%20logo.png" alt="UCL Logo"/>
    </div>
    <ul class="syed-list">
      <li>
        <strong>Senior Research Associate</strong>, <a class="syed-link" href="https://www.ucl.ac.uk/children-policy-research/">NIHR Children and Families Policy Research Unit</a>, UCL Great Ormond Street Institute of Child Health.
      </li>
      <li>
        <strong>Founder</strong> of <a class="syed-link" href="https://acesinehrs.com/">www.ACEsinEHRs.com</a>, an online platform of validated indicators of ACEs for research using electronic health records.
      </li>
    </ul>
    
    <a class="syed-button" href="https://shabeer-syed.github.io/shabeersyed/publications/">
      View Publication List &rarr;
    </a>
  </div>

</div>

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-TZ0Q814394"></script>
<script>
  window.dataLayer = window.dataLayer ||
