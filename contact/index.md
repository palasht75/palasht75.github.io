---
layout: splash
title: "Let’s Connect"
permalink: /contact/
classes: wide
header:
  overlay_color: "#001e3c"
  overlay_filter: "0.35"
  overlay_image: /assets/images/contact-hero.png   # 2400×900
  caption: "Open to new ideas, research collaborations, and AI-back-end roles."
  cta_label: "Download Résumé"
  cta_url: /assets/resume.pdf
---

<style>
:root{
  --accent:#0ea5e9;
}

/* ===== PAGE WRAPPER (no more negative margin) ===== */
.contact-wrapper{
  max-width:1400px;
  margin:0 auto 4rem;          /* sits _below_ hero now */
  padding:0 1.5rem;
  animation:slideDown .8s ease .1s both;
}
@keyframes slideDown{from{opacity:0;transform:translateY(-30px)}to{opacity:1;transform:translateY(0)}}

/* ===== GRID ===== */
.contact-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(420px,1fr));
  gap:3rem;
}

/* ===== CARDS ===== */
.glass{
  background:#ffffffeb;        /* 92% white, readable */
  border-radius:16px;
  padding:2.4rem 2.6rem;
  box-shadow:0 8px 26px rgba(0,0,0,.12);
  transition:.25s transform,.25s box-shadow;
}
.glass:hover{
  transform:translateY(-6px);
  box-shadow:0 14px 34px rgba(0,0,0,.18);
}

/* ===== INFO CARD ===== */
.info-card h2{margin-top:0;font-size:1.7rem;color:#002d5c;}
.contact-links{display:flex;flex-direction:column;gap:1.15rem;margin:2rem 0 0;}
.contact-link{display:flex;align-items:center;gap:.8rem;font-size:1.05rem;font-weight:600;
  color:#002d5c;text-decoration:none;transition:transform .25s;}
.contact-link i{color:var(--accent);font-size:1.4rem;}
.contact-link:hover{transform:translateX(4px);}

/* social ring */
.social-ring{display:flex;gap:1rem;margin-top:2.2rem;}
.ring{width:44px;height:44px;border-radius:50%;background:#f0f4ff;
  display:flex;align-items:center;justify-content:center;border:1px solid #d0e3ff;
  transition:.3s transform;background:#f0f4ff;}
.ring i{color:#002d5c;font-size:1.25rem;}
.ring:hover{transform:scale(1.15);background:var(--accent);color:#fff;}
.ring:hover i{color:#fff}

/* ===== FORM CARD ===== */
.form-card h2{margin:0 0 1.2rem;font-size:1.7rem;color:#002d5c;}
.form-group{margin-bottom:1.25rem;}
.form-group label{display:block;font-weight:600;color:#002d5c;font-size:.95rem;margin-bottom:.35rem;}
.form-group input,.form-group textarea{
  width:100%;background:#f8faff;border:1px solid #cfd9ff;border-radius:8px;
  padding:.75rem .9rem;font-size:.95rem;color:#002d5c;}
.form-group input:focus,.form-group textarea:focus{
  outline:none;border-color:var(--accent);box-shadow:0 0 0 2px rgba(14,165,233,.25);}
.form-group textarea{min-height:150px;resize:vertical;}
.send-btn{
  background:var(--accent);border:none;color:#fff;font-weight:700;
  padding:.85rem 2.4rem;border-radius:8px;font-size:1rem;cursor:pointer;
  transition:.25s transform,.25s box-shadow;}
.send-btn:hover{transform:translateY(-3px);box-shadow:0 8px 22px rgba(0,0,0,.22);}
small.form-note{display:block;margin-top:.9rem;color:#555;font-size:.8rem}

/* ===== MAP (optional) ===== */
.map-frame{width:100%;height:260px;border:0;border-radius:12px;box-shadow:0 3px 10px rgba(0,0,0,.1);margin-top:1.6rem;}

@media(max-width:600px){
  .glass{padding:1.8rem 1.5rem;}
  .contact-link{font-size:.95rem;}
}
</style>

<div class="contact-wrapper">

<div class="contact-grid">

<!-- ░░░ INFO CARD ░░░ -->
<section class="glass info-card">
  <h2>Say hello 👋</h2>

  <div class="contact-links">
    <a class="contact-link" href="mailto:palasht75@gmail.com">
      <i class="fas fa-envelope"></i> palasht75@gmail.com
    </a>
    <a class="contact-link" href="https://www.linkedin.com/in/palash-thakur-8b5a34193/" target="_blank" rel="noopener">
      <i class="fab fa-linkedin"></i> linkedin.com
    </a>
    <a class="contact-link" href="https://github.com/palasht75" target="_blank" rel="noopener">
      <i class="fab fa-github"></i> github.com/palasht75
    </a>
    <span class="contact-link" style="cursor:default;">
      <i class="fas fa-map-marker-alt"></i> Nagpur, India (UTC&nbsp;+5:30)
    </span>
  </div>

  <div class="social-ring">
    <a class="ring" href="mailto:palasht75@gmail.com"><i class="fas fa-envelope"></i></a>
    <a class="ring" href="https://linkedin.com/in/palasht75" target="_blank">
      <i class="fab fa-linkedin-in"></i>
    </a>
    <a class="ring" href="https://github.com/palasht75" target="_blank">
      <i class="fab fa-github"></i>
    </a>
  </div>

  <!-- Optional map; comment out if you don't want it -->
  <!--
  <iframe class="map-frame"
    src="https://www.google.com/maps/embed/v1/place?key=YOUR_GOOGLE_MAPS_API_KEY&q=Nagpur+Maharashtra" 
    loading="lazy" allowfullscreen referrerpolicy="no-referrer-when-downgrade">
  </iframe>
  -->
</section>

<!-- ░░░ FORM CARD ░░░ -->
<section class="glass form-card">
  <h2>Drop me a line</h2>

  <form action="https://formspree.io/f/xldnkobz" method="POST">
    <div class="form-group">
      <label for="name">Name <span style="color:#e11d48">*</span></label>
      <input type="text" id="name" name="name" required>
    </div>

    <div class="form-group">
      <label for="email">Email <span style="color:#e11d48">*</span></label>
      <input type="email" id="email" name="_replyto" required>
    </div>

    <div class="form-group">
      <label for="message">Message <span style="color:#e11d48">*</span></label>
      <textarea id="message" name="message" required></textarea>
    </div>

    <input type="text" name="_gotcha" style="display:none">

    <button type="submit" class="send-btn">Send Message</button>
    <small class="form-note">Powered by Formspree. You’ll get a confirmation email.</small>
  </form>
</section>

</div><!-- /.contact-grid -->
</div><!-- /.contact-wrapper -->
