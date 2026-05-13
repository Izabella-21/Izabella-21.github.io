---
layout: fullwidth
title: ""
permalink: /
---

<style>
  
  .hero-section {
    text-align: center;
    padding: 80px 20px 60px 20px;
    border-bottom: 1px solid rgba(0,0,0,0.08);
  }
  
  [data-theme="dark"] .hero-section {
    border-bottom: 1px solid rgba(255,255,255,0.08);
  }

  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    margin: 2rem 0;
  }
  
.skill-category {
  background: rgba(255, 255, 255, 0.03);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 20px;
  padding: 1.5rem;
  transition: all 0.3s ease;
}

[data-theme="dark"] .skill-category {
  background: rgba(255, 255, 255, 0.02);
}

.skill-category:hover {
  background: rgba(255, 255, 255, 0.05);
  transform: translateY(-4px);
  border-color: rgba(134, 89, 247, 0.5);
}
  
  .skill-list {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-top: 1rem;
  }
  
.skill-tag {
  background: rgba(0,0,0,0.05);
  padding: 0.25rem 0.75rem;
  border-radius: 6px;
  font-size: 0.85rem;
  font-family: monospace;
  transition: all 0.2s ease;
  display: inline-block;
}

[data-theme="dark"] .skill-tag {
  background: rgba(255,255,255,0.08);
}

.skill-tag:hover {
  transform: translateY(-2px);
  background: #8659f7;
  color: white;
}
  
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
    margin: 2rem 0;
  }
  
  .project-item {
    padding: 1.5rem;
    border-left: 3px solid var(--accent-color);
    background: var(--background-color);
  }
  
  .contact-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2rem;
    margin: 2rem 0;
  }
  
  .form-field {
    margin-bottom: 1rem;
  }
  
  .form-field input,
  .form-field textarea {
    width: 100%;
    padding: 10px 0;
    border: none;
    border-bottom: 1px solid rgba(0,0,0,0.2);
    background: transparent;
    font-size: 1rem;
  }
  
  [data-theme="dark"] .form-field input,
  [data-theme="dark"] .form-field textarea {
    border-bottom: 1px solid rgba(255,255,255,0.2);
    color: white;
  }
  
  .form-field input:focus,
  .form-field textarea:focus {
    outline: none;
    border-bottom-color: var(--accent-color);
  }
  
  .btn {
    display: inline-block;
    padding: 10px 24px;
    border-radius: 6px;
    font-weight: 500;
    text-decoration: none;
    transition: all 0.2s ease;
    cursor: pointer;
  }
  
  .btn-primary {
    background: var(--accent-color);
    color: white;
    border: none;
  }
  
  .btn-primary:hover {
    opacity: 0.9;
  }
  
  .btn-secondary {
    background: transparent;
    border: 1px solid var(--accent-color);
    color: var(--accent-color);
  }
  
  .btn-secondary:hover {
    background: var(--accent-color);
    color: white;
  }
  
  .social-link {
    display: inline-block;
    margin-right: 1.5rem;
    color: var(--text-color);
    text-decoration: none;
    font-size: 0.9rem;
  }
  
  .social-link:hover {
    color: var(--accent-color);
  }
  
  hr {
    margin: 2rem 0;
    border: none;
    border-top: 1px solid rgba(0,0,0,0.08);
  }
  
  [data-theme="dark"] hr {
    border-top: 1px solid rgba(255,255,255,0.08);
  }

  .custom-btn {
    position: relative;       
    overflow: hidden;         
    padding: 14px 36px;
    font-size: 1.1rem;
    font-weight: 500;
    transition: all 0.5s ease;
    display: inline-block;
    color: white;
    border: 1px solid #331a74;
    background: #482575;
    border-radius: 6px;
    text-decoration: none !important;
    cursor: pointer;
    z-index: 1;               
  }

  .custom-btn::before {
    content: '';
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%) translateY(100%);
    width: 0px;
    height: 0px;
    background: rgba(255, 255, 255, 0.3);
    border-radius: 50%;
    transition: all 0.8s cubic-bezier(0.2, 0.9, 0.4, 1.1);
    z-index: -1;
    pointer-events: none; /* Prevents circle from blocking hover */
  }

  .custom-btn:hover::before {
    width: 280px;
    height: 280px;
    transform: translateX(-50%) translateY(40%);
  }

  .custom-btn:hover {
    color: #8659f7;
    border-color: #96d1d4;
    background: #96d1d4;
    transform: translateY(-2px) scale(1.02);
    box-shadow: 0 8px 25px rgba(0,0,0,0.15);
    text-decoration: none !important;
  }

  .custom-btn:link,
  .custom-btn:visited,
  .custom-btn:active {
    text-decoration: none !important;
  }

  /* Large button */
  .custom-btn.large {
    padding: 5px 85px;
    font-size: 1rem;
  }
.profile-photo {
  transition: all 0.3s cubic-bezier(0.2, 0.9, 0.4, 1.1);
}

.profile-photo:hover {
  transform: scale(1.03);
  box-shadow: 0 15px 35px rgba(134, 89, 247, 0.2);
  border-color: #a855f7;
}
</style>

<div class="hero-section" style="text-align: left; padding: 40px 20px 40px 20px;">
  <div style="display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 2rem;">
    
    <div style="flex: 2; min-width: 280px;">
      <h1 style="font-size: 3rem; margin-bottom: 0.5rem; font-weight: 500;">Izabella Molnar</h1>
      <p style="font-size: 1.25rem; color: #8659f7; margin-bottom: 0.5rem;">Quality Assurance Engineer</p>
      <p style="font-size: 1rem; opacity: 0.7; max-width: 500px;">Test Automation • Full Stack Quality • CI/CD Integration</p>
      
      <div style="margin-top: 2rem; display: flex; gap: 1rem; flex-wrap: wrap;">
        <a href="/resume" class="custom-btn large">Resume</a>
        <a href="/portfolio" class="custom-btn large">Portfolio</a>
      </div>
    </div>
    
    <div style="flex: 1; min-width: 180px; text-align: center;">
      <img src="/assets/images/profile.jpg" 
           alt="Izabella Molnar" 
           class="profile-photo"
           style="width: 180px; height: 180px; border-radius: 50%; object-fit: cover; border: 3px solid #8659f7; box-shadow: 0 10px 25px rgba(0,0,0,0.1);">
    </div>
    
  </div>
</div>

## Professional Summary

Quality Assurance Engineer specializing in test automation and full-stack quality practices. Experienced in building robust testing frameworks from the ground up, integrating quality gates into CI/CD pipelines, and bridging the gap between development and operations.

Currently focused on AI-assisted testing workflows and improving release reliability through automated validation strategies.

---

## Technical Competencies

<!-- Full width category (Test Automation) -->
<div style="margin-bottom: 2rem;">
  <div class="skill-category" style="display: flex; align-items: center; gap: 1rem; flex-wrap: wrap;">
    <div style="min-width: 180px;">
      <strong style="font-size: 1.1rem;">Test Automation</strong>
    </div>
    <div class="skill-list" style="flex: 1;">
      <span class="skill-tag"><i class="fab fa-js" style="margin-right: 4px;"></i> Cypress, JavaScript, TypeScript</span>
      <span class="skill-tag"><i class="fab fa-python" style="margin-right: 4px;"></i> Python API testing (requests + pytest)</span>
      <span class="skill-tag"><i class="fas 	fa-tachometer-alt" style="margin-right: 4px;"></i> Performance testing (k6)</span>
      <span class="skill-tag"><i class="fas fa-brain" style="margin-right: 4px;"></i> AI-augmented testing</span>
      <span class="skill-tag"><i class="fas fa-plug" style="margin-right: 4px;"></i> Functional, regression, integration, API</span>
    </div>
  </div>
</div>

<!-- 3-Column Grid for remaining categories -->
<div class="skills-grid">
  
  <!-- Infrastructure & Tools -->
  <div class="skill-category">
    <div style="display: flex; align-items: center; gap: 0.5rem; margin-bottom: 1rem;">
      <strong>Infrastructure & Tools</strong>
    </div>
    <div class="skill-list">
      <span class="skill-tag"><i class="fab fa-aws" style="margin-right: 4px;"></i> AWS</span>
      <span class="skill-tag"><i class="fab fa-linux" style="margin-right: 4px;"></i> Linux (Ubuntu/Mint)</span>
      <span class="skill-tag"><i class="fab fa-jira" style="margin-right: 4px;"></i> Jira/Confluence</span>
      <span class="skill-tag"><i class="fab fa-git-alt" style="margin-right: 4px;"></i> Git</span>
      <span class="skill-tag"><i class="fas fa-cube" style="margin-right: 4px;"></i> Containerized test environments</span>
      <span class="skill-tag"><i class="fas fa-database" style="margin-right: 4px;"></i> SQL</span>
      <span class="skill-tag"><i class="fas fa-server" style="margin-right: 4px;"></i> vSphere & VM management</span>
    </div>
  </div>

  <!-- AI & Collaboration Tools -->
  <div class="skill-category">
    <div style="display: flex; align-items: center; gap: 0.5rem; margin-bottom: 1rem;">
      <strong>AI & Collaboration</strong>
    </div>
    <div class="skill-list">
      <span class="skill-tag"><i class="fas fa-comment-dots" style="margin-right: 4px;"></i> Claude & Claude API</span>
      <span class="skill-tag"><i class="fas fa-code-branch" style="margin-right: 4px;"></i> GitHub Copilot</span>
      <span class="skill-tag"><i class="fab fa-jira" style="margin-right: 4px;"></i> Jira/Confluence</span>
      <span class="skill-tag"><i class="fas fa-code" style="margin-right: 4px;"></i> VS Code</span>
      <span class="skill-tag"><i class="fas fa-code-branch" style="margin-right: 4px;"></i> GitKraken</span>
    </div>
  </div>

  <!-- CI/CD & DevOps -->
  <div class="skill-category">
    <div style="display: flex; align-items: center; gap: 0.5rem; margin-bottom: 1rem;">
      <strong>CI/CD & DevOps</strong>
    </div>
    <div class="skill-list">
      <span class="skill-tag"><i class="fas fa-city" style="margin-right: 4px;"></i> TeamCity</span>
      <span class="skill-tag"><i class="fas fa-cogs" style="margin-right: 4px;"></i> Jenkins</span>
      <span class="skill-tag"><i class="fab fa-github" style="margin-right: 4px;"></i> GitHub Actions</span>
      <span class="skill-tag"><i class="fab fa-docker" style="margin-right: 4px;"></i> Docker</span>
    </div>
  </div>
</div>

---

## Recent Writings

<div class="recent-posts-grid">
  {% for post in site.posts limit:3 %}
  <div class="recent-post-card">
    <div class="recent-post-meta">
      <span class="recent-post-date">{{ post.date | date: "%b %d, %Y" }}</span>
      <span class="recent-post-category">{{ post.categories | first | default: "QA" }}</span>
    </div>
    <h4 class="recent-post-title">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h4>
    <p class="recent-post-excerpt">{{ post.excerpt | strip_html | truncatewords: 15 }}</p>
  </div>
  {% endfor %}
</div>

<div style="text-align: left; margin-top: 1.5rem;">
  <a href="/blog" class="read-more">View full blog →</a>
</div>

---

## Contact

  <div>
    <p><strong>Direct</strong><br>
    <a href="mailto:m.izabella21@gmail.com" style="color: var(--accent-color);">m.izabella21@gmail.com</a></p>
    
    <p style="margin-top: 1.5rem;"><strong>Professional Profiles</strong><br>
    <a href="https://github.com/Izabella-21" class="social-link">GitHub</a>
    <a href="https://www.linkedin.com/in/izabella-molnar/" class="social-link">LinkedIn</a></p>
    
    <p style="margin-top: 1.5rem;"><strong>Availability</strong><br>
    <span style="font-size: 0.9rem; opacity: 0.7;">Open for freelance, contract, and permanent positions.</span></p>
  </div>

---

<div style="text-align: center; font-size: 0.8rem; opacity: 0.5; margin-top: 3rem; padding-top: 2rem; border-top: 1px solid rgba(0,0,0,0.05);">
  Izabella Molnar — Quality Assurance Engineering
</div>
