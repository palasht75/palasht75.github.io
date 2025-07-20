---
layout: splash
title: "Projects"
permalink: /projects/
---
<style>
:root{--grad1:#e3f2fd;}/* same colour */
body{background:var(--grad1);}
</style>


<style>
/* ===== PROJECT GRID ===== */
.project-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(340px,1fr));
  gap:2rem;
  max-width:1200px;
  margin:3rem auto 2.5rem;
  padding:0 1rem;
}

/* ===== CARD ===== */
.project-card{
  background:#fff;
  border-radius:12px;
  overflow:hidden;
  box-shadow:0 5px 14px rgba(0,0,0,.08);
  transition:.25s transform,.25s box-shadow;
  text-decoration:none;color:inherit;
}
.project-card:hover{
  transform:translateY(-6px);
  box-shadow:0 10px 24px rgba(0,0,0,.15);
}
.project-thumb{
  width:100%;
  height:200px;
  object-fit:cover;
  display:block;
}
.project-body{
  padding:1.25rem 1.5rem;
}
.project-body h3{
  margin:.25rem 0 .6rem;
  font-size:1.3rem;
  color:#002d5c;
}
.project-body p{
  font-size:.95rem;
  line-height:1.55;
  color:#444;
}
.tech-tags{
  margin-top:1rem;
  display:flex;flex-wrap:wrap;gap:.4rem;
}
.tech-tags span{
  padding:4px 8px;
  font-size:.75rem;
  background:#f0f4ff;
  border-radius:4px;
  color:#002d5c;
  font-weight:600;
}
</style>

# Projects

A selection of open-source libraries, prototypes, and production systems I have authored or led.
Click any card to view the repository or live demo.

<div class="project-grid">

<!-- ========== PROJECT 1 ========== -->
<a class="project-card" href="https://github.com/palasht75/umls-python-client" target="_blank" rel="noopener">
  <img class="project-thumb" src="/assets/images/proj-umls.png" alt="UMLS Python Client">
  <div class="project-body">
    <h3>UMLS Python Client</h3>
    <p>Lightweight SDK that wraps the UMLS REST APIs, with async and retry support.
       Published on PyPI and featured by the National Library of Medicine.</p>

    <div class="tech-tags">
      <span>Python</span><span>FastAPI</span><span>Healthcare</span>
    </div>
  </div>
</a>

<!-- ========== PROJECT 2 ========== -->
<a class="project-card" href="https://github.com/palasht75/llm-evidence-summarizer" target="_blank" rel="noopener">
  <img class="project-thumb" src="/assets/images/llm-summarization.png" alt="LLM Evidence Summarizer">
  <div class="project-body">
    <h3>LLM Evidence Summarizer</h3>
    <p>Compliance-grade summarization with transparent sentence-level evidence mapping.</p>

    <div class="tech-tags">
      <span>Python</span><span>OpenAI SDK</span><span>llama</span><span>GPT4o</span><span>Git CI/CD</span><span>Github Actions</span>
    </div>
  </div>
</a>


 <!-- ========== PROJECT 3 ========== -->
<a class="project-card" href="https://github.com/palasht75/LeaseCheck-Multi-Shot-RAG" target="_blank" rel="noopener">
  <img class="project-thumb" src="/assets/images/llm-summarization.jpg" alt="LeaseCheck-Multi Shot RAG">
  <div class="project-body">
    <h3>LeaseCheck-Multi Shot RAG</h3>
    <p>Detect illegal lease clauses in Canadian rentals using RAG, multi-shot prompting, and a minimal Python tool.
</p>

    <div class="tech-tags">
      <span>Python</span><span>OpenAI SDK</span><span>GPT4o</span><span>FAISS</span><span>RAG</span><span>Prompt Engineering</span><span>Git CI/CD</span><span>Github Actions</span>
    </div>
  </div>
</a>

<!-- ========== PROJECT 4 ========== -->
<!-- <a class="project-card" href="https://github.com/palasht75/llm-evidence-summarizer" target="_blank" rel="noopener">
  <img class="project-thumb" src="/assets/images/llm-summarization.jpg" alt="LLM Evidence Summarizer">
  <div class="project-body">
    <h3>LLM Evidence Summarizer</h3>
    <p>Compliance-grade summarization with transparent sentence-level evidence mapping.</p>

    <div class="tech-tags">
      <span>Python</span><span>OpenAI SDK</span><span>llama</span><span>GPT4o</span><span>Git CI/CD</span><span>Github Actions</span>
    </div>
  </div>
</a> -->

</div>

<!-- > **Add more:** copy a `<a class="project-card"> … </a>` block,
> update the image, link, text, and tech tags.
>
> Thumbnails should be 1200×800 px (or similar 3:2 ratio) JPEG/PNG
> stored in `/assets/images/`. -->
{% include easter-egg.html %}
