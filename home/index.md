---
layout: default
title: Home
nav: home
hero_kicker: Academic Research Group
hero_title: Yumin Li
hero_text: Postdoctoral Associate at the Institute for Atmospheric and Climate Science, ETH Zurich. Research interests include atmospheric organic aerosol, air pollution, atmospheric chemistry-climate interactions, and atmospheric modeling.
---

<div class="lead-grid">
  <div>
    <img class="profile-image" src="{{ '/images/profile.jpg' | relative_url }}" alt="Group profile or principal investigator photo">
  </div>
  <div>
    <p><strong>Institute for Atmospheric and Climate Science</strong><br>
    ETH Zurich<br>
    CHN building, ETH Zurich, 8092, Switzerland</p>

    <p>Email: <a href="mailto:yumin.li@env.ethz.ch">yumin.li@env.ethz.ch</a></p>

    <p>Yumin Li is a Postdoctoral Associate at ETH Zurich. Her work focuses on atmospheric organic aerosols, nitrogen-containing aerosol components, atmospheric modeling, and the climate and ecosystem impacts of air pollution.</p>

    <div class="social-links">
      <a href="https://orcid.org/0000-0002-5686-3249">ORCID</a>
      <a href="https://scholar.google.com/citations?user=yhuEUm0AAAAJ&hl=zh-CN">Google Scholar</a>
      <a href="https://www.researchgate.net/profile/Yumin-Li-11/research">ResearchGate</a>
    </div>
  </div>
</div>

## Welcome

Before joining ETH Zurich in March 2024, Yumin Li was a Research Associate at the Hong Kong University of Science and Technology and completed her Ph.D. in Environmental Science, Policy and Management at HKUST in 2023. Her thesis focused on the global sources and impacts of absorptive components in atmospheric organic aerosols.

## Research Themes

<div class="info-panel">
  <div class="info-box">
    <strong>Theme 1. Atmospheric Organic Aerosol</strong><br>
    Sources, composition, brown carbon and brown nitrogen, and optical evolution during atmospheric aging.
  </div>
  <div class="info-box">
    <strong>Theme 2. Atmospheric Modeling</strong><br>
    GEOS-Chem based global modeling of aerosol chemistry, nitrogen deposition, and aerosol-climate interactions.
  </div>
  <div class="info-box">
    <strong>Theme 3. Environmental Impacts</strong><br>
    Climate forcing, ecosystem nitrogen supply, and health effects associated with aerosol composition and phase state.
  </div>
</div>

<div class="section-header">
  <h2>Recent News</h2>
  <a href="{{ '/news/' | relative_url }}">View all news</a>
</div>

<ol class="simple-news-list">
  <li><strong>April 2026:</strong> Home page updated to feature curated recent news and recent publications sections.</li>
  <li><strong>2026:</strong> Co-authored work on the global budget of atmospheric glyoxal was published in <em>Atmospheric Chemistry and Physics</em>.</li>
  <li><strong>2025:</strong> Presented work on global impacts of organic aerosol phase state at the European GEOS-Chem Meeting, the Atmospheric Chemistry GRS/GRC, and EGU General Assembly.</li>
  <li><strong>2025:</strong> <em>Science</em> published "Nitrogen dominates global atmospheric organic aerosol absorption."</li>
  <li><strong>2025:</strong> Published a perspective on organic nitrogen and climate impacts of organic aerosols in <em>Chinese Science Bulletin</em>.</li>
  <li><strong>December 2024:</strong> Presented on the global impacts of organic aerosol phase state at the AGU Fall Meeting.</li>
  <li><strong>March 2024:</strong> Joined ETH Zurich as a Postdoctoral Associate in the Institute for Atmospheric and Climate Science.</li>
  <li><strong>October 2023 to January 2024:</strong> Worked as a Research Associate at the Hong Kong University of Science and Technology.</li>
  <li><strong>2023:</strong> <em>National Science Review</em> published work on the contributions of organic nitrogen aerosols to global atmospheric nitrogen deposition.</li>
  <li><strong>2021:</strong> <em>Environmental Science &amp; Technology</em> published work on atmospheric levoglucosan degradation and biomass-burning source attribution.</li>
</ol>

<div class="section-header">
  <h2>Recent Publications</h2>
  <a href="{{ '/publications/' | relative_url }}">View all publications</a>
</div>

{% assign home_publications = site.data.publications | where: "featured_home", true | sort: "home_rank" %}
{% for pub in home_publications limit: 10 %}
  {% include publication-card.html pub=pub %}
{% endfor %}
