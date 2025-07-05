---
layout: splash
permalink: /
title: "Palash Thakur"
subtitle: "Engineering Scalable, Intelligent Solutions"

header:
  overlay_color: "#002d5c"
  overlay_filter: "0.3"
  overlay_image: /assets/images/banner.png
  caption: "Turning ideas into high-impact software."
  actions:
    - label: "Download Résumé"
      url: /assets/resume.pdf
      icon: "fas fa-file-alt"
    - label: "Email Me"
      url: "mailto:palasht75@gmail.com"
      icon: "fas fa-paper-plane"
excerpt: >
  Senior Software Engineer with expertise in llm engineering, backend development, and designing no code low code agentic AI soltuions, and cloud infrastructure.
  Passionate about creating fast, resilient systems that deliver real value to the customers.

feature_row:
  - image_path: /assets/images/projects.png
    alt: "Projects"
    title: "Projects"
    excerpt: "Explore open-source and professional work."
    url: "/projects/"
    btn_label: "View Projects"
    btn_class: "btn--primary"
  - image_path: /assets/images/media.png
    alt: "Talks & Demos"
    title: "Talks & Demos"
    excerpt: "YouTube walkthroughs and LinkedIn highlights."
    url: "/media/"
    btn_label: "Watch & Read"
    btn_class: "btn--primary"
  - image_path: /assets/images/contact.png
    alt: "Contact"
    title: "Let's Connect"
    excerpt: "Interested in collaborating or hiring? Reach out."
    url: "/contact/"
    btn_label: "Contact Me"
    btn_class: "btn--primary"
---

<!-- ================== ABOUT SECTION ================== -->
<section class="about-me-section">
  <div class="about-me-container">
    <div class="about-me-avatar">
      <img src="/assets/images/avatar.jpg" alt="Palash Thakur">
    </div>
    <div class="about-me-text">
      <h2>About Me</h2>
      <p>
        I’m a senior software engineer focused on building <strong>scalable platforms</strong> and
        <strong>intelligent solutions</strong> that power businesses and improve user experiences.
        From designing cloud-native microservices to integrating AI models, I thrive on solving
        complex technical challenges and driving products to success.
      </p>
      <p>
        Over the past 3+ years, I’ve led projects ranging from financial analytics services used
        by millions to open-source tools adopted by researchers.
      </p>
      <ul class="about-me-highlights">
        <li><strong>Google Cloud Hackathon</strong> Winner — demo viewed by 7.8K+ people</li>
        <li><strong>2×</strong> peer-reviewed publications and Best Paper award</li>
        <li>Mentored 200+ students and new engineers</li>
        <li>Incoming M.Eng student at the University of Ottawa</li>
      </ul>
    </div>
  </div>
</section>

<style>
.about-me-container {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  justify-content: center;
  flex-wrap: wrap;
  gap: 3rem;
  max-width: 1100px;
  margin: 3rem auto 2rem;
  padding: 0 1rem;
}
.about-me-avatar {
  flex: 0 0 auto;
}
.about-me-avatar img {
  border-radius: 50%;
  width: 240px;
  height: 240px;
  object-fit: cover;
  box-shadow: 0 4px 15px rgba(0,0,0,0.2);
}
.about-me-text {
  flex: 1 1 500px;
  min-width: 320px;
}
.about-me-text h2 {
  margin-top: 0;
}
.about-me-text p {
  font-size: 1.1rem;
  line-height: 1.7;
  margin-bottom: 1rem;
}
.about-me-highlights {
  margin-top: 1rem;
  padding-left: 1.2rem;
}
.about-me-highlights li {
  margin-bottom: 0.6rem;
}
@media (max-width: 700px) {
  .about-me-container {
    flex-direction: column;
    text-align: center;
  }
  .about-me-text {
    max-width: 90%;
  }
}
</style>





<!-- ================== FEATURE TILES ================== -->
{% include feature_row %}

<!-- ================== CORE SKILLS ================== -->
### Core Skills

<div class="badges">
  <span class="badge">Python</span><span class="badge">FastAPI</span>
  <span class="badge">PostgreSQL</span><span class="badge">Redis</span>
  <span class="badge">Docker</span><span class="badge">Kubernetes</span>
  <span class="badge">AWS</span><span class="badge">CI/CD</span>
  <span class="badge">NLP</span><span class="badge">LLMs</span>
  <span class="badge">GraphQL</span><span class="badge">TypeScript</span>
</div>

<!-- ================== RECENT HIGHLIGHTS ================== -->
### Recent Highlights

<ul class="highlights">
  <li><strong>2025</strong>: Rolled out AI agent features to 1M+ QuickBooks users</li>
  <li><strong>2024</strong>: Scaled FastAPI microservice to 10,000 req/hr and cut latency by 36%</li>
  <li><strong>2023</strong>: Published research on multimodal emotion recognition (Springer)</li>
  <li><strong>2022</strong>: 1st Place — Google Cloud “Next Big Thing” Hackathon</li>
</ul>

<!-- ================== CALL TO ACTION ================== -->
<section class="cta">
  <a class="btn btn--primary btn--large" href="/projects/">Explore My Work →</a>
</section>


<style>
/* ...your other styles... */

.feature__item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 4px;
}
</style>
