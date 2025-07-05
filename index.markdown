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
  Senior Software Engineer specialising in LLM engineering, backend development and
  no-code/low-code agentic-AI solutions on the cloud. I create fast, resilient systems
  that deliver real value.

---

<!-- ================== ABOUT SECTION ================== -->
<section class="about-me-section">
  <div class="about-me-container">
    <div class="about-me-avatar">
      <a href="https://www.linkedin.com/in/palash-thakur-8b5a34193/" target="_blank" rel="noopener" title="LinkedIn">
        <img src="/assets/images/avatar.jpg" alt="Palash Thakur – LinkedIn Profile">
      </a>
      <p class="avatar-contact">
        <a href="https://linkedin.com/in/palasht75" target="_blank" rel="noopener" class="contact-link">
          <i class="fab fa-linkedin"></i> LinkedIn
        </a><br>
        <a href="mailto:palasht75@gmail.com" class="contact-link">
          <i class="fas fa-envelope"></i> palasht75@gmail.com
        </a>
      </p>
    </div>

    <div class="about-me-text">
      <h2>About Me</h2>
      <p>
        I’m a senior software engineer who <strong>designs cloud-native back-ends</strong> in Python and AWS,
        optimised to handle tens of thousands of <strong>LLM / Agentic-AI requests</strong> per minute.
        Recently I co-engineered Intuit’s <em>Finance Agent</em>—a flagship agentic-AI feature for
        QuickBooks Online Advanced &amp; Plus—now serving <strong>millions of global customers</strong>.
        I’ve also delivered production AI and data platforms for top healthcare providers,
        integrating NLP, UMLS pipelines and privacy-first analytics at scale.
      </p>

      <p>
        Whether it’s a microservice that auto-scales in Kubernetes, a streaming pipeline that fuels
        real-time dashboards, or a LangChain-powered tool that explains a balance sheet,
        I turn ideas into <strong>robust, measurable outcomes</strong>.  My sweet-spot:
        combining rock-solid engineering practices with cutting-edge ML so businesses
        can move faster—and users simply <em>enjoy the magic</em>.
      </p>
      <ul class="about-me-highlights">
        <li><strong>Google Cloud Hackathon</strong> Winner — demo viewed by 7.8 K+ people</li>
        <li><strong>2×</strong> peer-reviewed publications and Best Paper award</li>
        <li>Mentored 200+ students and new engineers</li>
        <li>Incoming M.Eng student at the University of Ottawa</li>
      </ul>
    </div>
  </div>
</section>

<!-- ================== PROJECT / MEDIA / CONTACT CARDS ================== -->
<section class="card-grid">
  <a class="card" href="/projects/project.md">
    <img src="/assets/images/projects.png" alt="Projects">
    <div class="card-body">
      <h3>Projects</h3>
      <p>Explore open-source and professional work.</p>
    </div>
  </a>

  <a class="card" href="/media/">
    <img src="/assets/images/media.png" alt="Talks and Demos">
    <div class="card-body">
      <h3>Talks & Demos</h3>
      <p>YouTube walkthroughs and LinkedIn highlights.</p>
    </div>
  </a>

  <a class="card" href="/contact/">
    <img src="/assets/images/contact.png" alt="Let's Connect">
    <div class="card-body">
      <h3>Let's Connect</h3>
      <p>Interested in collaborating or hiring? Reach out.</p>
    </div>
  </a>
</section>

<style>
/* ---------- ABOUT LAYOUT ---------- */
.about-me-container{
  display:flex;flex-wrap:wrap;gap:3rem;align-items:flex-start;justify-content:center;
  max-width:1100px;margin:3rem auto 2rem;padding:0 1rem;
}
.about-me-avatar{text-align:center;}
.about-me-avatar img{
  width:240px;height:240px;border-radius:50%;object-fit:cover;
  box-shadow:0 4px 15px rgba(0,0,0,.2);transition:transform .25s;
}
.about-me-avatar img:hover{transform:scale(1.05);}
.avatar-contact{margin-top:1rem;line-height:1.6;}
.contact-link{color:#0069d9;text-decoration:none;}
.contact-link:hover{text-decoration:underline;}

.about-me-text{flex:1 1 500px;min-width:320px;}
.about-me-text h2{margin-top:0;}
.about-me-text p{font-size:1.1rem;line-height:1.7;margin-bottom:1rem;}
.about-me-highlights{margin-top:1rem;padding-left:1.2rem;}
.about-me-highlights li{margin-bottom:.6rem;}

@media(max-width:700px){
  .about-me-container{flex-direction:column;text-align:center;}
  .about-me-text{max-width:90%;}
}

/* ---------- CARD GRID ---------- */
.card-grid{
  display:flex;flex-wrap:wrap;gap:2rem;justify-content:center;
  max-width:1100px;margin:2rem auto;
  padding:0 1rem;
}
.card{
  display:flex;flex-direction:column;text-align:center;
  width:320px;max-width:100%;text-decoration:none;color:inherit;
  border-radius:6px;overflow:hidden;box-shadow:0 4px 12px rgba(0,0,0,.08);
  transition:transform .25s,box-shadow .25s;
}
.card:hover{
  transform:scale(1.04);
  box-shadow:0 6px 18px rgba(0,0,0,.15);
}
.card img{
  width:100%;height:180px;object-fit:cover;
}
.card-body{padding:1rem 1.25rem;}
.card-body h3{margin:0 0 .5rem;font-size:1.25rem;color:#002d5c;}
.card-body p{margin:0;color:#555;font-size:.95rem;line-height:1.5;}

/* ---------- BADGES & BUTTONS ---------- */
.badge{white-space:nowrap;}
.btn{transition:transform .2s,box-shadow .2s;}
.btn:hover{transform:translateY(-2px);box-shadow:0 4px 12px rgba(0,0,0,.15);}

/* ---------- SKILLS TAGS ---------- */
.skills-grid{
  display:flex;
  flex-wrap:wrap;
  gap:.6rem;
  justify-content:center;
  margin-top:1rem;
}

.skill-tag{
  display:inline-flex;
  align-items:center;
  gap:.35rem;
  padding:6px 12px;
  font-size:.95rem;
  font-weight:600;
  color:#002d5c;
  background:#f0f4ff;
  border-radius:30px;
  box-shadow:0 2px 6px rgba(0,0,0,.05);
  transition:transform .2s,box-shadow .2s;
}
.skill-tag i{font-size:1rem;}      /* icon size */
.skill-tag:hover{
  transform:translateY(-2px);
  box-shadow:0 4px 12px rgba(0,0,0,.12);
}

</style>

<!-- ================== CORE SKILLS ================== -->
### Core Skills

<div class="skills-grid">

  <!-- Languages & Frameworks -->
  <span class="skill-tag"><i class="fab fa-python"></i> Python</span>
  <span class="skill-tag"><i class="fas fa-code"></i> FastAPI</span>
  <span class="skill-tag"><i class="fas fa-code"></i> TypeScript</span>

  <!-- Databases -->
  <span class="skill-tag"><i class="fas fa-database"></i> PostgreSQL</span>
  <span class="skill-tag"><i class="fas fa-database"></i> Redis</span>

  <!-- DevOps / Cloud -->
  <span class="skill-tag"><i class="fab fa-docker"></i> Docker</span>
  <span class="skill-tag"><i class="fas fa-network-wired"></i> Kubernetes</span>
  <span class="skill-tag"><i class="fab fa-aws"></i> AWS</span>
  <span class="skill-tag"><i class="fas fa-shipping-fast"></i> CI/CD</span>
  <span class="skill-tag"><i class="fas fa-ship"></i> Argo&nbsp;CD</span>

  <!-- AI / Data -->
  <span class="skill-tag"><i class="fas fa-brain"></i> NLP</span>
  <span class="skill-tag"><i class="fas fa-robot"></i> LLMs</span>
  <span class="skill-tag"><i class="fas fa-cogs"></i> LLM&nbsp;Engineering</span>
  <span class="skill-tag"><i class="fas fa-rocket"></i> Agentic&nbsp;AI</span>
  <span class="skill-tag"><i class="fas fa-lightbulb"></i> OpenAI&nbsp;API</span>
  <span class="skill-tag"><i class="fas fa-project-diagram"></i> GraphQL</span>
  <span class="skill-tag"><i class="fas fa-project-diagram"></i> TensorFlow</span>

</div>


<!-- ================== RECENT HIGHLIGHTS ================== -->
### Recent Highlights

<ul class="highlights">
  <li><strong>2025</strong>: Rolled out AI agent features to 1 M+ QuickBooks users</li>
  <li><strong>2024</strong>: Scaled FastAPI microservice to 10 000 req/hr; cut latency 36 %</li>
  <li><strong>2023</strong>: Published research on multimodal emotion recognition (Springer)</li>
  <li><strong>2022</strong>: 1st Place — Google Cloud “Next Big Thing” Hackathon</li>
</ul>

<!-- ================== CALL TO ACTION ================== -->
<section class="cta">
  <a class="btn btn--primary btn--large" href="/projects/">Explore My Work →</a>
</section>
