---
layout: splash
title: ""
permalink: /media/
---

<style>
/* ====== CONTAINER ====== */
.media-block {
  max-width: 1200px;
  margin: 3rem auto 2.5rem;
  padding: 0 1rem;
}

/* ====== TWO-COLUMN GRID ====== */
.media-columns {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(520px, 1fr));
  gap: 2rem;
  align-items: start;
}

/* ====== COLUMN HEADERS ====== */
.media-col h2 {
  margin-bottom: 1rem;
  color: #002d5c;
  font-size: 1.5rem;
  text-align: center;
}

/* ====== CARD ====== */
.embed-card {
  background: #fff;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,.08);
  transition: transform .25s, box-shadow .25s;
  margin-bottom: 2rem;
}
.embed-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 22px rgba(0,0,0,.15);
}
.embed-card iframe,
.embed-card img {
  width: 100%;
  display: block;
}
.embed-card.youtube iframe {
  height: 315px;
}
.embed-card.linkedin iframe {
  height: 600px;
}
.embed-card img {
  height: 600px;
  object-fit: cover;
}

/* ====== CAPTION ====== */
.caption {
  padding: 1rem 1.25rem;
  font-size: .95rem;
  line-height: 1.4;
  text-align: center;
  color: #444;
}
.caption strong {
  display: block;
  margin-bottom: .25rem;
  color: #002d5c;
}

/* ====== RESEARCH GRID ====== */
.paper-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
  gap: 2rem;
  margin-top: 2.5rem;
}
.paper-card {
  border-radius: 10px;
  overflow: hidden;
  background: #fff;
  box-shadow: 0 4px 12px rgba(0,0,0,.08);
  transition: transform .25s, box-shadow .25s;
}
.paper-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 22px rgba(0,0,0,.15);
}
.paper-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}
.paper-body {
  padding: 1rem 1.25rem;
  font-size: .95rem;
  text-align: center;
}
.paper-body strong {
  display: block;
  margin-bottom: .25rem;
  color: #002d5c;
}
</style>

<div class="media-block">

  <!-- Main Title -->
  <h1 style="text-align:center; margin-bottom:2rem; color:#002d5c;">Talks & Media</h1>

  <!-- Two Columns: YouTube & LinkedIn -->
  <div class="media-columns">

    <!-- Left Column: YouTube -->
    <div class="media-col">
      <h2>YouTube Videos</h2>

      <div class="embed-card youtube">
        <iframe
          src="https://www.youtube-nocookie.com/embed/tGOLaD2Zu2c?rel=0&modestbranding=1"
          title="Google Cloud Hackathon Winning Demo"
          frameborder="0" allowfullscreen loading="lazy">
        </iframe>
        <div class="caption">
          <strong>Google Cloud Hackathon</strong>
          Invited to Google's office to record a winning video – 7.8K+ views
        </div>
      </div>

      <div class="embed-card youtube">
        <iframe
          src="https://www.youtube-nocookie.com/embed/od_AkgvJqq4?rel=0&modestbranding=1"
          title="GEMS Mentorship – Persistent Systems"
          frameborder="0" allowfullscreen loading="lazy">
        </iframe>
        <div class="caption">
          <strong>GEMS Mentorship</strong>
          Onboarding insights for new engineers at Persistent Systems
        </div>
      </div>
    </div>

    <!-- Right Column: LinkedIn -->
    <div class="media-col">
      <h2>LinkedIn Highlights</h2>


      <div class="embed-card linkedin">
        <iframe
          src="https://www.linkedin.com/embed/feed/update/urn:li:share:7034522317976133633?collapsed=1"
          title="Semicolons appreciation post"
          frameborder="0" allowfullscreen loading="lazy">
        </iframe>
        <div class="caption">
          <strong>Semicolons Appreciation</strong>
          Recognition from Persistent Systems finals
        </div>
      </div>

      <div class="embed-card linkedin">
        <iframe
          src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7030875756268318720?collapsed=1"
          title="Google Cloud Hackathon recap"
          frameborder="0" allowfullscreen loading="lazy">
        </iframe>
        <div class="caption">
          <strong>Hackathon Recap</strong>
          Winner of Google Cloud Hackathon – LinkedIn post
        </div>
      </div>



      <div class="embed-card linkedin">
        <iframe
          src="https://www.linkedin.com/embed/feed/update/urn:li:activity:7030875831258267648?collapsed=1"
          title="HumBanayenge event"
          frameborder="0" allowfullscreen loading="lazy">
        </iframe>
        <div class="caption">
          <strong>HumBanayenge Spotlight</strong>
          Young-Developer keynote at Google Cloud APAC
        </div>
      </div>
    </div>

  </div>

  <!-- Research Publications -->
  <h2 style="text-align:center; margin-top:3rem; color:#002d5c;">Research Publications</h2>
  
  <div class="paper-grid">
    <a class="paper-card" href="https://bbrc.in/wp-content/uploads/2021/03/13_14-SPL-Galley-proof-115.pdf" target="_blank" rel="noopener">
      <img src="/assets/images/paper-traffic.png" alt="Traffic Sign paper thumbnail" style="height:300px;">
      <div class="paper-body" style="min-height:110px;">
        <strong>Traffic-Sign Detection</strong>
        Best Paper – ICESC 2020
      </div>
    </a>

    <a class="paper-card" href="https://link.springer.com/chapter/10.1007/978-981-19-8865-3_41" target="_blank" rel="noopener">
      <img src="/assets/images/paper-emotion.jpg" alt="Emotion Recognition paper thumbnail" style="height:300px;">
      <div class="paper-body" style="min-height:110px;">
        <strong>Emotion Recognition System</strong>
        Springer LNEE 992 – ICMEET 2023
      </div>
    </a>
  </div>

</div>
