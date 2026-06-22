---
layout: default
title: Home
nav: home
hero_kicker: IAC ETH Zurich
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

    <p>Yumin Li is a Postdoctoral Associate at ETH Zurich. Her research focused on global atmospheric chemistry and its implications for climate change and air quality. Key research areas included atmospheric organic aerosols, nitrogen-containing aerosol species, atmospheric chemical transport modeling, aerosol phase state and the impacts of air pollution on climate and ecosystem health.</p>

    <div class="social-links">
      <a href="https://orcid.org/0000-0002-5686-3249">ORCID</a>
      <a href="https://scholar.google.com/citations?user=yhuEUm0AAAAJ&hl=zh-CN">Google Scholar</a>
      <a href="https://www.researchgate.net/profile/Yumin-Li-11/research">ResearchGate</a>
    </div>
  </div>
</div>

## Biography

Research Associate                                                                                                                       10/2023–01/2024
-Hong Kong University of Science and Technology, China, Division of Environment and Sustainability 

Hong Kong University of Science and Technology, China                                                                                    2019–2023
- Ph.D., Environmental Science, Policy and Management

Southern University of Science and Technology, China                                                                                     2015–2019
- B.Sc., Environmental Science and Engineering 

## Research

<div class="research-hero">
  <img src="{{ '/images/Research1.png' | relative_url }}" alt="Research overview">
  <div class="research-points">
    <div class="info-box">
      <span class="research-label">Atmospheric organic aerosol</span>: sources, composition, brown carbon and brown nitrogen, atmospheric aging, and phase state.
    </div>
    <div class="info-box">
      <span class="research-label">Atmospheric modeling</span>: GEOS-Chem global modeling of aerosol chemistry, RRTMG, and coupling with other models and AI.
    </div>
    <div class="info-box">
      <span class="research-label">Environmental impacts</span>: climate change, air quality, and ecosystem effects.
    </div>
  </div>
</div>

<div class="section-header">
  <h2>Recent News</h2>
  <a href="{{ '/news/' | relative_url }}">View all news</a>
</div>

<div class="home-news-list">
  <div class="home-news-item">
    <img class="news-marker" src="{{ '/images/news-phoenix-marker.png' | relative_url }}" alt="">
    <div><span class="news-date">Apr 2026</span> Home page updated to feature curated recent news and recent publications sections.</div>
  </div>
  <div class="home-news-item">
    <img class="news-marker" src="{{ '/images/news-phoenix-marker.png' | relative_url }}" alt="">
    <div><span class="news-date">2026</span> Co-authored work on the global budget of atmospheric glyoxal was published in <em>Atmospheric Chemistry and Physics</em>.</div>
  </div>
  <div class="home-news-item">
    <img class="news-marker" src="{{ '/images/news-phoenix-marker.png' | relative_url }}" alt="">
    <div><span class="news-date">2025</span> Presented work on global impacts of organic aerosol phase state at the European GEOS-Chem Meeting, the Atmospheric Chemistry GRS/GRC, and EGU General Assembly.</div>
  </div>
  <div class="home-news-item">
    <img class="news-marker" src="{{ '/images/news-phoenix-marker.png' | relative_url }}" alt="">
    <div><span class="news-date">2025</span> <em>Science</em> published "Nitrogen dominates global atmospheric organic aerosol absorption."</div>
  </div>
  <div class="home-news-item">
    <img class="news-marker" src="{{ '/images/news-phoenix-marker.png' | relative_url }}" alt="">
    <div><span class="news-date">2025</span> Published a perspective on organic nitrogen and climate impacts of organic aerosols in <em>Chinese Science Bulletin</em>.</div>
  </div>
  <div class="home-news-item">
    <img class="news-marker" src="{{ '/images/news-phoenix-marker.png' | relative_url }}" alt="">
    <div><span class="news-date">Dec 2024</span> Presented on the global impacts of organic aerosol phase state at the AGU Fall Meeting.</div>
  </div>
  <div class="home-news-item">
    <img class="news-marker" src="{{ '/images/news-phoenix-marker.png' | relative_url }}" alt="">
    <div><span class="news-date">Mar 2024</span> Joined ETH Zurich as a Postdoctoral Associate in the Institute for Atmospheric and Climate Science.</div>
  </div>
  <div class="home-news-item">
    <img class="news-marker" src="{{ '/images/news-phoenix-marker.png' | relative_url }}" alt="">
    <div><span class="news-date">Oct 2023</span> Worked as a Research Associate at the Hong Kong University of Science and Technology.</div>
  </div>
  <div class="home-news-item">
    <img class="news-marker" src="{{ '/images/news-phoenix-marker.png' | relative_url }}" alt="">
    <div><span class="news-date">2023</span> <em>National Science Review</em> published work on the contributions of organic nitrogen aerosols to global atmospheric nitrogen deposition.</div>
  </div>
  <div class="home-news-item">
    <img class="news-marker" src="{{ '/images/news-phoenix-marker.png' | relative_url }}" alt="">
    <div><span class="news-date">2021</span> <em>Environmental Science &amp; Technology</em> published work on atmospheric levoglucosan degradation and biomass-burning source attribution.</div>
  </div>
</div>

<div class="section-header">
  <h2>Recent Publications</h2>
  <a href="{{ '/publications/' | relative_url }}">View all publications</a>
</div>

{% assign home_publications = site.data.publications | where: "featured_home", true | where: "status", "Published" | sort: "home_rank" %}
{% for pub in home_publications limit: 10 %}
  {% include publication-card.html pub=pub %}
{% endfor %}
