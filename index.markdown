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
      url: /assets/Palash_Resume_24_25.pdf
      icon: "fas fa-file-alt"
    - label: "Email Me"
      url: "mailto:palasht75@gmail.com"
      icon: "fas fa-paper-plane"
excerpt: >
  Senior Software Engineer focused on cloud-native back-end development and 
  applied AI projects. I build fast, resilient Python + AWS services and have 
  delivered agentic-AI prototypes and LLM coursework projects that showcase my 
  growing expertise in large-language-model pipelines.
---

<style>
:root {
  --accent: #1e88e5;
  --grad1: #e3f2fd;
  --grad2: #bbdefb;
  --grad3: #90caf9;
  --grad4: #64b5f6;
  --grad5: #42a5f5;
}
body {
  margin: 0;
  transition: background 1s ease;
}

/* PANEL BASE */
.panel {
  padding: 1.5rem 1rem;
  max-width: 1200px;
  margin: 0 auto;
  opacity: 0;
  transform: translateY(20px);
  transition: opacity .6s ease, transform .6s ease;
  color: #002d5c;
  background: transparent;
}
.panel.active {
  opacity: 1;
  transform: translateY(0);
}

/* ABOUT */
.about-me-container {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 1rem;
  margin-bottom: 1.5rem;
}
.about-me-avatar {
  flex: 0 0 auto;
  text-align: center;
}
.about-me-avatar img {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: cover;
  box-shadow: 0 6px 18px rgba(0,0,0,.2);
  transition: transform .25s;
}
.about-me-avatar img:hover {
  transform: scale(1.05);
  cursor: pointer;
}
.avatar-contact {
  margin-top: .5rem;
  line-height: 1.4;
}
.contact-link {
  color: var(--accent);
  text-decoration: none;
  display: block;
}
.contact-link:hover {
  text-decoration: underline;
}
.about-me-text {
  flex: 1 1 350px;
}
.about-me-text h2 {
  margin-top: 0;
  font-size: 1.8rem;
}
.about-me-text p {
  margin-bottom: .8rem;
  line-height: 1.5;
  font-size: 1rem;
}

/* TIMELINE */
.timeline {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  position: relative;
  margin: 1.5rem 0;
}
.timeline::before {
  content: "";
  position: absolute;
  top: 16px;
  left: 3%;
  width: 94%;
  height: 4px;
  background: rgba(0,0,0,.2);
  z-index: 0;
}
.timeline-item {
  position: relative;
  width: 22%;
  text-align: center;
  z-index: 1;
  opacity: .5;
  transition: opacity .4s;
}
.timeline-item.active {
  opacity: 1;
}
.timeline-dot {
  width: 14px;
  height: 14px;
  background: var(--accent);
  border-radius: 50%;
  margin: 0 auto;
}
.timeline-content h4 {
  margin: .4rem 0 .2rem;
  font-size: 1rem;
}
.timeline-content p {
  margin: 0;
  font-size: .85rem;
  color: rgba(0,0,0,.7);
}

/* CARDS */
.card-panel h2 {
  text-align: center;
  margin-bottom: 1rem;
}
.card-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  justify-content: center;
  margin-bottom: 1.5rem;
}
.card {
  width: 260px;
  background: rgba(255,255,255,.6);
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,.15);
  opacity: 0;
  transform: translateY(20px);
  transition: opacity .55s, transform .55s;
  text-align: center;
}
.card.show {
  opacity: 1;
  transform: translateY(0);
}
.card:hover {
  transform: translateY(-6px);
}
.card img {
  width: 100%;
  height: 150px;
  object-fit: cover;
}
.card-body {
  padding: .8rem 1rem;
}
.card-body h3 {
  margin: 0 0 .4rem;
  font-size: 1.2rem;
  color: #002d5c;
}
.card-body p {
  margin: 0;
  font-size: .88rem;
  color: rgba(0,0,0,.7);
}

/* SKILLS */
.skills-panel h2 {
  text-align: center;
  margin-bottom: 1rem;
}
.skills-grid {
  display: flex;
  flex-wrap: wrap;
  gap: .6rem;
  justify-content: center;
  margin-bottom: 1.5rem;
}
.skill-tag {
  background: rgba(255,255,255,.6);
  padding: 6px 12px;
  border-radius: 30px;
  color: #002d5c;
  font-size: .85rem;
  font-weight: 600;
  display: inline-flex;
  align-items: center;
  gap: .3rem;
  opacity: 0;
  transform: translateY(20px);
  transition: opacity .5s, transform .5s, background .3s, transform .3s;
}
.skill-tag.show {
  opacity: 1;
  transform: translateY(0);
}
.skill-tag i {
  color: var(--accent);
}
/* interactive hover */
.skill-tag:hover {
  background: rgba(255,255,255,.8);
  transform: scale(1.1);
  box-shadow: 0 4px 12px rgba(0,0,0,.2);
  cursor: pointer;
}

/* HIGHLIGHTS */
.highlights-panel h2 {
  text-align: center;
  margin-bottom: .8rem;
}
.highlights {
  list-style: none;
  padding: 0;
  margin: 0 auto 1.5rem;
  max-width: 600px;
  text-align: center;
  color: rgba(0,0,0,.7);
}
.highlights li {
  margin: .4rem 0;
  font-size: .9rem;
}
.highlights li strong {
  color: var(--accent);
}

/* CTA */
.cta {
  text-align: left;
  margin-bottom: 1.5rem;
}

/* EASTER EGG BUTTON */
#egg {
  position: fixed;
  bottom: 16px;
  right: 16px;
  z-index: 9999;
  background: var(--accent);
  color: #fff;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.6rem;
  cursor: pointer;
  opacity: 0;
  transform: translateY(30px);
  transition: opacity .6s, transform .6s;
  animation: pulse 2s ease-in-out infinite;
}
#egg.show {
  opacity: 1;
  transform: translateY(0);
}
@keyframes pulse {
  0%,100% { transform: scale(1); }
  50% { transform: scale(1.2); }
}

/* MODAL */
.modal {
  display: none;
  position: fixed;
  top: 0; left: 0; right: 0; bottom: 0;
  background: rgba(0,0,0,.6);
  justify-content: center;
  align-items: center;
  z-index: 10000;
}
.modal-content {
  background: #fff;
  color: #002d5c;
  padding: 1.5rem;
  border-radius: 8px;
  text-align: center;
  max-width: 300px;
}
.modal-content h3 {
  margin-top: 0;
}
.close-btn {
  margin-top: 1rem;
  background: var(--accent);
  color: #fff;
  border: none;
  padding: .5rem 1rem;
  border-radius: 4px;
  cursor: pointer;
}

/* responsive */
@media(max-width:720px){
  .about-me-container { flex-direction: column; text-align: center; }
  .timeline { display: block; }
  .timeline-item { width: 100%; margin-bottom: 1rem; }
}

/* ---- EASTER EGG TRIGGER ---- */
#egg {
  position: fixed;
  bottom: 24px;
  right: 24px;
  width: 56px; height: 56px;
  background: var(--accent);
  color: #fff;
  font-size: 1.5rem;
  line-height: 56px;
  text-align: center;
  border-radius: 50%;
  box-shadow: 0 4px 12px rgba(0,0,0,.3);
  cursor: pointer;
  z-index: 10001;
  animation: pulse 2s ease-in-out infinite;
  transition: background .3s;
}
#egg:hover {
  background: #1565c0;
}
@keyframes pulse {
  0%,100% { transform: scale(1); }
  50% { transform: scale(1.2); }
}

/* ---- SLIDING SIDE PANEL ---- */
#easterPanel {
  position: fixed;
  top: 0; right: -320px;
  width: 280px; height: 100%;
  background: rgba(255,255,255,0.95);
  backdrop-filter: blur(8px);
  box-shadow: -4px 0 16px rgba(0,0,0,.2);
  transition: right .5s ease;
  z-index: 10000;
  display: flex;
  flex-direction: column;
}
#easterPanel.open { right: 0; }

/* Panel Header */
.easter-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1rem;
  border-bottom: 1px solid #ddd;
}
.easter-header h3 {
  margin: 0;
  font-size: 1.1rem;
  color: var(--accent);
}
.easter-header button {
  background: none;
  border: none;
  font-size: 1.4rem;
  line-height: 1;
  cursor: pointer;
  color: #333;
}

/* Panel List */
.easter-list {
  list-style: none;
  margin: 1rem;
  padding: 0;
  flex: 1;
}
.easter-list li {
  margin: .6rem 0;
  font-size: .95rem;
  color: #333;
  position: relative;
  padding-left: 1.5rem;
}
.easter-list li::before {
  content: "✔";
  position: absolute;
  left: 0;
  color: var(--accent);
  font-size: .9rem;
}

/* Footer */
.easter-footer {
  padding: 1rem;
  font-size: .85rem;
  text-align: center;
  border-top: 1px solid #ddd;
  color: #555;
}

/* CONFETTI */
#confetti {
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  pointer-events: none;
  overflow: hidden;
  z-index: 10000;
}
.confetto {
  position: absolute;
  width: 8px; height: 8px;
  background: var(--accent);
  opacity: .9;
  transform-origin: center;
  animation: fall 2.5s linear forwards, spin 1s linear infinite;
}
@keyframes fall {
  to { transform: translateY(110vh) rotate(720deg); opacity: 0; }
}
@keyframes spin { to { transform: rotate(360deg); } }

</style>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const egg = document.getElementById('egg');
  const panel = document.getElementById('easterPanel');
  const close = document.getElementById('closeEgg');
  const confetti = document.getElementById('confetti');

  // Show panel + confetti
  egg.addEventListener('click', () => {
    panel.classList.add('open');
    launchConfetti(30);
  });
  // Close panel
  close.addEventListener('click', () => panel.classList.remove('open'));
  panel.addEventListener('click', e => {
    if (e.target === panel) panel.classList.remove('open');
  });

  // Confetti generator
  function launchConfetti(count) {
    for (let i=0; i<count; i++) {
      const c = document.createElement('div');
      c.classList.add('confetto');
      c.style.left = Math.random()*100 + 'vw';
      c.style.top = '-10px';
      c.style.background = `hsl(${200 + Math.random()*50}, 80%, 60%)`;
      c.style.animationDelay = (Math.random()*0.5) + 's';
      confetti.appendChild(c);
      setTimeout(() => c.remove(), 3000);
    }
  }
});
</script>


<script>
document.addEventListener('DOMContentLoaded', () => {
  // gradient mapping
  const grades = {
    about:      'var(--grad1)',
    cards:      'var(--grad2)',
    skills:     'var(--grad3)',
    highlights: 'var(--grad4)',
    cta:        'var(--grad5)'
  };
  document.querySelectorAll('.panel').forEach(panel => {
    const sec = panel.dataset.section;
    panel.__grad = grades[sec]||grades.about;
    new IntersectionObserver(entries => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          document.body.style.background = e.target.__grad;
          e.target.classList.add('active');
        }
      });
    },{threshold:0.5}).observe(panel);
  });

  // timeline reveal
  document.querySelectorAll('.timeline-item').forEach(item=>{
    new IntersectionObserver(entries=>{
      entries.forEach(e=>{
        if(e.isIntersecting) e.target.classList.add('active');
      });
    },{rootMargin:'0px 0px -40% 0px'}).observe(item);
  });

  // cards reveal
  document.querySelectorAll('.card').forEach(card=>{
    new IntersectionObserver(entries=>{
      entries.forEach(e=>{
        if(e.isIntersecting) e.target.classList.add('show');
      });
    },{threshold:0.3}).observe(card);
  });
  // skills reveal
  document.querySelectorAll('.skill-tag').forEach(tag=>{
    new IntersectionObserver(entries=>{
      entries.forEach(e=>{
        if(e.isIntersecting) e.target.classList.add('show');
      });
    },{threshold:0.3}).observe(tag);
  });

  // easter egg & modal
  const egg = document.getElementById('egg'),
        modal = document.getElementById('eggModal'),
        close = document.getElementById('closeEgg');
  setTimeout(() => egg.classList.add('show'), 2000);
  egg.onclick = () => {
    modal.style.display = 'flex';
  };
  close.onclick = () => {
    modal.style.display = 'none';
  };
  modal.onclick = e => {
    if(e.target===modal) modal.style.display = 'none';
  };
});
</script>

<!-- ABOUT PANEL -->
<section class="panel about-panel" data-section="about">
  <div class="about-me-container">
    <div class="about-me-avatar">
      <a href="https://www.linkedin.com/in/palash-thakur-8b5a34193/" target="_blank" rel="noopener">
        <img src="/assets/images/avatar.jpg" alt="Palash Thakur – LinkedIn">
      </a>
      <div class="avatar-contact">
        <a href="https://www.linkedin.com/in/palash-thakur-8b5a34193/" class="contact-link"><i class="fab fa-linkedin"></i> LinkedIn</a>
        <a href="mailto:palasht75@gmail.com" class="contact-link"><i class="fas fa-envelope"></i> palasht75@gmail.com</a>
      </div>
    </div>
    <div class="about-me-text">
      <h2>About Me</h2>
      <p>
      I'm a Senior Software Engineer with over <strong>3.6 years of experience</strong> designing cloud-native, scalable backend solutions optimized for handling tens of thousands of <strong>LLM and agentic AI requests</strong> per minute. My expertise spans Python development, AWS cloud services, and advanced NLP solutions tailored for global healthcare clients, including notable collaborations with institutions such as Harvard Medical School. At Persistent Systems, I've co-engineered Intuit's Finance Agent, <strong>serving over 1 million users</strong>, enhancing performance, scalability, and reliability significantly.
      </p>
      <p>
      In addition to technical accomplishments, I am deeply committed to mentorship and education. I've <strong>guided over 200 undergraduate</strong> students at my alma mater, Shri Ramdeobaba College of Engineering and Management, providing essential support for research, career development, and interview preparation. My passion for fostering innovation in younger generations was recognized by Google Cloud India, where I served as the <strong>mentor and face</strong> of the <strong>#HumBanayenge campaign</strong>, advocating tech-driven problem-solving.
      </p>
      <p>
      Starting Fall 2025, I'll be pursuing a Master of Engineering (MEng) in Electrical and Computer Engineering (ECE) at the University of Ottawa. I'm eager to apply my expertise in NLP, agentic AI, and healthcare technologies through industry roles and academic positions such as Teaching Assistant or Research Assistant. My goal is to further advance intelligent solutions that drive impactful healthcare outcomes within an innovative and collaborative academic and professional environment.
      </p>
    </div>
  </div>
  <div class="timeline">
    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-content">
        <h4>2022 – Research Intern</h4>
        <p>Delivered Microscopy image-enhancement tool at Persistent Systems for florida based client.</p>
      </div>
    </div>
    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-content">
        <h4>2023 – Associate Data Scientist</h4>
        <p>Developed end-to-end NLP pipelines for EMR data at Harvard Medical School and led research on Indian diabetic datasets, applying statistical methods to derive actionable insights.</p>     </div>
    </div>
    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-content">
        <h4>2024 – Senior Software Engineer</h4>
        <p>Worked as Database admin. Optimised Postgres & AWS HealthLake for Connxus HIE.</p>
      </div>
    </div>
    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-content">
        <h4>2025 – Senior Software Engineer</h4>
        <p>Leading the development of scalable backend systems and AI agent features at Intuit, serving millions of users. Preparing to begin a Master of Engineering at the University of Ottawa in Fall 2025.</p>     </div>
    </div>
  </div>
  
</section>

<!-- CARDS PANEL -->
<section class="panel card-panel" data-section="cards">
  <h2>Explore My Work</h2>
  <div class="card-grid">
    <a class="card" href="/projects/"><img src="/assets/images/projects.png" alt=""><div class="card-body"><h3>Projects</h3><p>Open-source & professional work.</p></div></a>
    <a class="card" href="/media/"><img src="/assets/images/media.png" alt=""><div class="card-body"><h3>Talks & Demos</h3><p>YouTube & LinkedIn highlights.</p></div></a>
    <a class="card" href="/contact/"><img src="/assets/images/contact.png" alt=""><div class="card-body"><h3>Let's Connect</h3><p>Reach out to collaborate.</p></div></a>
  </div>
</section>

<!-- SKILLS PANEL -->
<section class="panel skills-panel" data-section="skills">
  <h2>Core Skills</h2>
  <div class="skills-grid">
    <span class="skill-tag"><i class="fab fa-python"></i> Python</span>
    <span class="skill-tag"><i class="fas fa-code"></i> FastAPI</span>
    <span class="skill-tag"><i class="fas fa-code"></i> JavaScript</span>
    <span class="skill-tag"><i class="fas fa-database"></i> PostgreSQL</span>
    <span class="skill-tag"><i class="fas fa-database"></i> Redis</span>
    <span class="skill-tag"><i class="fab fa-docker"></i> Docker</span>
    <span class="skill-tag"><i class="fas fa-network-wired"></i> Kubernetes</span>
    <span class="skill-tag"><i class="fab fa-aws"></i> AWS</span>
    <span class="skill-tag"><i class="fas fa-robot"></i> LLM Engineering</span>
    <span class="skill-tag"><i class="fas fa-rocket"></i> Agentic AI</span>
    <span class="skill-tag"><i class="fas fa-desktop"></i> Gradio</span>
    <span class="skill-tag"><i class="fas fa-plug"></i> OpenAI API</span>
    <span class="skill-tag"><i class="fas fa-brain"></i> LLAMA</span>
    <span class="skill-tag"><i class="fab fa-git-alt"></i> Git CI/CD</span>
    <span class="skill-tag"><i class="fab fa-github"></i> GitHub Actions</span>
    <span class="skill-tag"><i class="fab fa-tensorflow"></i> TensorFlow</span>
    <span class="skill-tag"><i class="fas fa-cloud"></i> Argo CD</span>
  </div>
</section>

<!-- HIGHLIGHTS PANEL -->
<section class="panel highlights-panel" data-section="highlights">
  <h2>Recent Highlights</h2>
  <ul class="highlights">
    <li><strong>2025</strong>: Rolled out AI agent features to 1M+ QuickBooks users</li>
    <li><strong>2024</strong>: Scaled FastAPI service to 10K req/hr; cut latency 36%</li>
    <li><strong>2023</strong>: Published multimodal emotion recognition (Springer)</li>
    <li><strong>2022</strong>: 1st Place — Google Cloud “Next Big Thing” Hackathon</li>
  </ul>
</section>

<!-- CTA PANEL -->
<section class="panel cta-panel" data-section="cta">
  <div class="cta">
    <a class="btn btn--primary btn--large" href="/projects/">Explore My Work →</a>
  </div>
</section>

<!-- ================== EASTER EGG TRIGGER & PANEL ================== -->
<!-- Floating “?” Trigger -->
<div id="egg" role="button" aria-label="Surprise me!" title="Click for a surprise!">?</div>

<!-- Sliding Side-Panel
<aside id="easterPanel" aria-hidden="true">
  <header class="easter-header">
    <h3>🔧 Built With</h3>
    <button id="closeEgg" aria-label="Close">×</button>
  </header>
  <ul class="easter-list">
    <li>Jekyll</li>
    <li>HTML5</li>
    <li>CSS3</li>
    <li>JavaScript</li>
    <li>IntersectionObserver API</li>
  </ul>
  <footer class="easter-footer">
    Crafted by <strong>Palash Thakur</strong>
  </footer>
</aside>

<!-- Confetti Container -->
<!-- <div id="confetti"></div> -->

