---
layout: fullwidth
title: Resume
permalink: /resume/
---

<style>
  /* ===== RESUME PAGE SPECIFIC STYLES ===== */
  .resume-section {
    margin: 2rem 0 2.5rem 0;
  }
  
  .resume-section h2 {
    font-size: 1.5rem;
    font-weight: 500;
    letter-spacing: -0.3px;
    border-bottom: 2px solid var(--accent-color, #8659f7);
    padding-bottom: 0.5rem;
    margin-bottom: 1.5rem;
  }
  
  .experience-item {
    margin-bottom: 2rem;
  }
  
  .experience-header {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    margin-bottom: 0.5rem;
  }
  
  .experience-title {
    font-weight: 600;
    font-size: 1.1rem;
    color: var(--accent-color, #8659f7);

  }
  
  .experience-company {
    font-weight: 500;
  }
  
  .experience-date {
    font-size: 0.85rem;
    opacity: 0.7;
  }
  
  .experience-location {
    font-size: 0.85rem;
    opacity: 0.6;
    margin-bottom: 0.75rem;
  }
  
  .skills-summary {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    margin: 2rem 0;
    padding: 1rem 0;
    border-top: 1px solid rgba(0,0,0,0.05);
    border-bottom: 1px solid rgba(0,0,0,0.05);
  }
  
  .skill-group {
    flex: 1;
    min-width: 180px;
  }
  
  .skill-group strong {
    display: block;
    font-size: 0.8rem;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    opacity: 0.7;
    margin-bottom: 0.5rem;
  }
  
  .skill-items {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }
  
  .skill-items span {
    background: rgba(134, 89, 247, 0.1);
    padding: 0.2rem 0.6rem;
    border-radius: 12px;
    font-size: 0.75rem;
    font-weight: 500;
    color: #8659f7;
  }
  
  .achievement {
    display: flex;
    gap: 0.5rem;
    align-items: flex-start;
    margin-bottom: 0.5rem;
  }
  
  .achievement-icon {
    font-size: 1rem;
    min-width: 20px;
    color: #8659f7;
  }
  
  .featured-project {
    background: rgba(134, 89, 247, 0.03);
    border-left: 3px solid #8659f7;
    padding: 1rem 1.25rem;
    border-radius: 8px;
    margin: 1.5rem 0;
  }
  
  .project-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    margin-bottom: 0.5rem;
  }
  
  .project-status {
    font-size: 0.7rem;
    padding: 0.2rem 0.6rem;
    border-radius: 20px;
    background: rgba(134, 89, 247, 0.1);
    color: #8659f7;
    font-weight: 500;
  }
  
  .project-tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin: 0.75rem 0;
  }
  
  .project-tech-stack span {
    background: var(--background-color);
    padding: 0.2rem 0.6rem;
    border-radius: 4px;
    font-size: 0.7rem;
    font-family: monospace;
  }
  
  .project-link {
    font-size: 0.85rem;
    font-weight: 500;
    color: #8659f7;
    text-decoration: none;
    transition: all 0.2s ease;
  }
  
  .project-link:hover {
    transform: translateX(4px);
    display: inline-block;
  }
  
  .contact-links {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    margin: 1.5rem 0;
  }
  
  .contact-item {
    display: flex;
    align-items: baseline;
    gap: 0.5rem;
    padding: 0.5rem 1rem;
    background: rgba(0,0,0,0.03);
    border-radius: 30px;
    text-decoration: none;
    transition: all 0.2s ease;
  }
  
  [data-theme="dark"] .contact-item {
    background: rgba(255,255,255,0.03);
  }
  
  .contact-item:hover {
    background: rgba(134, 89, 247, 0.1);
    transform: translateY(-2px);
  }
  
  .contact-icon {
    font-size: 1.1rem;
  }
  
  .contact-handle {
    font-family: monospace;
    font-size: 0.85rem;
    opacity: 0.7;
  }
  
  .info-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
    margin: 1.5rem 0;
    padding: 1rem;
    background: rgba(0,0,0,0.02);
    border-radius: 12px;
  }
  
  [data-theme="dark"] .info-grid {
    background: rgba(255,255,255,0.02);
  }
  
  .info-item strong {
    font-weight: 600;
  }
  
  .education-item {
    margin-bottom: 1rem;
  }
  
  .education-degree {
    font-weight: 600;
  }
  
  .education-date {
    font-size: 0.85rem;
    opacity: 0.7;
  }
  
  .availability-badge {
    display: inline-block;
    background: rgba(0,128,0,0.1);
    color: #2e7d32;
    padding: 0.25rem 0.75rem;
    border-radius: 20px;
    font-size: 0.8rem;
    font-weight: 500;
  }
  
  [data-theme="dark"] .availability-badge {
    background: rgba(0,255,0,0.1);
    color: #4caf50;
  }
  
  .connect-link {
    font-size: 0.85rem;
    color: #8659f7;
    text-decoration: none;
    transition: all 0.2s ease;
  }
  
  .connect-link:hover {
    transform: translateX(3px);
  }
</style>

<!-- Header / Open to opportunities -->
<div class="resume-section">
  <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; margin-bottom: 1rem;">
    <span class="availability-badge">Open to opportunities</span>
    <a href="https://www.linkedin.com/in/izabella-molnar/" class="connect-link" target="_blank">Connect on LinkedIn →</a>
  </div>
  
  <p style="font-size: 1.05rem; line-height: 1.6;">
    QA Automation Engineer with nearly 7 years of experience across SaaS, enterprise configurators, 
    medical device software, and digital experience platforms. Currently the sole automation engineer 
    supporting 5 teams, owning the Cypress test suite, managing cloud and VM infrastructure, and 
    integrating AI tools (Claude, Copilot) to accelerate testing. PhD background in biomedical 
    engineering brings analytical rigor and systematic problem-solving.
  </p>
</div>

<!-- Core Competencies Summary -->

## Core Competencies

<div class="skills-summary">
  <div class="skill-group">
    <strong>Test Automation</strong>
    <div class="skill-items">
      <span><i class="devicon-cypressio-plain"></i> Cypress</span>
      <span><i class="devicon-javascript-plain"></i> JavaScript/TypeScript</span>
      <span><i class="devicon-postman-plain"></i> Postman</span>
      <span><i class="fab fa-python"></i> API Testing (pytest)</span>
    </div>
  </div>
  <div class="skill-group">
    <strong>Infrastructure & Environment</strong>
    <div class="skill-items">
      <span><i class="fab fa-aws"></i> AWS</span>
      <span><i class="fas fa-server"></i> vSphere</span>
      <span><i class="fab fa-linux"></i> Linux</span>
      <span><i class="fas fa-database"></i> SQL</span>
      <span><i class="fab fa-docker"></i> Docker</span>
    </div>
  </div>
  <div class="skill-group">
    <strong>CI/CD & Tools</strong>
    <div class="skill-items">
      <span><i class="fas fa-city"></i> TeamCity</span>
      <span><i class="devicon-jenkins-plain"></i> Jenkins</span>
      <span><i class="fab fa-git-alt"></i> Git</span>
      <span><i class="fab fa-jira"></i> Jira/Confluence</span>
      <span><i class="devicon-vscode-plain"></i> VS Code</span>
    </div>
  </div>
</div>

<!-- Professional Experience -->

## Professional Experience

<div class="resume-section">
  
  <div class="experience-item">
    <div class="experience-header">
      <span class="experience-title">QA Automation Engineer</span>
      <span class="experience-date">Nov 2024 – Present</span>
    </div>
    <div class="experience-company">Stefanini EMEA</div>
    <div class="experience-location">Bucharest, Romania (Remote)</div>
    <ul style="margin-top: 0.5rem; padding-left: 1.25rem; list-style: none;">
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Sole automation engineer supporting 5 teams in structured Agile environment</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Own and maintain Cypress end-to-end automation suite</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Accelerate automation development using Claude and GitHub Copilot</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Manage test infrastructure across TeamCity, AWS (Tower), and vSphere</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Mentor manual testers in automation best practices</span></li>
    </ul>
  </div>

  <div class="experience-item">
    <div class="experience-header">
      <span class="experience-title">QA Engineer</span>
      <span class="experience-date">Sep 2022 – Oct 2024</span>
    </div>
    <div class="experience-company">Eviden</div>
    <div class="experience-location">Cluj-Napoca, Romania (Remote)</div>
    <ul style="margin-top: 0.5rem; padding-left: 1.25rem; list-style: none;">
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Designed automated tests using Cypress and JavaScript for enterprise configurator</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Built complex API test suites in Postman with environment variables and test chaining</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Maintained test environments via Jenkins</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Validated AWS database data; monitored logs with Kibana</span></li>
    </ul>
  </div>

  <div class="experience-item">
    <div class="experience-header">
      <span class="experience-title">QA Engineer</span>
      <span class="experience-date">Oct 2021 – Aug 2022</span>
    </div>
    <div class="experience-company">eggs unimedia romania</div>
    <div class="experience-location">Cluj-Napoca, Romania (Hybrid)</div>
    <ul style="margin-top: 0.5rem; padding-left: 1.25rem; list-style: none;">
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Created test cases in Jira/Xray; executed regression cycles</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Tested frontend UI and Adobe Experience Manager (AEM) configurations</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Tested mobile web apps using BrowserStack</span></li>
    </ul>
  </div>

  <div class="experience-item">
    <div class="experience-header">
      <span class="experience-title">QA Engineer</span>
      <span class="experience-date">Jun 2019 – Oct 2021</span>
    </div>
    <div class="experience-company">STRATEC SE</div>
    <div class="experience-location">Cluj-Napoca, Romania (Hybrid)</div>
    <ul style="margin-top: 0.5rem; padding-left: 1.25rem; list-style: none;">
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Created test plans based on requirements, not just implementation</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Performed regression, exploratory, and defect verification testing</span></li>
      <li class="achievement"><span class="achievement-icon">▹</span> <span>Used Microsoft Azure and SQL for test data validation</span></li>
    </ul>
  </div>
</div>

<!-- Featured Project
## Featured Project

<div class="featured-project">
  <div class="project-header">
    <strong>Python API Testing Framework</strong>
    <span class="project-status">Active</span>
  </div>
  <p>End-to-end API testing suite using Pytest and Requests. Features automated schema validation, CI/CD integration, and HTML reporting.</p>
  <div class="project-tech-stack">
    <span>Pytest</span> <span>Requests</span> <span>GitHub Actions</span> <span>Allure</span>
  </div>
  <a href="https://github.com/Izabella-21" class="project-link" target="_blank">View on GitHub →</a>
</div> -->

<!-- Additional Experience -->

## Additional Experience

<div class="experience-item">
  <div class="experience-header">
    <span class="experience-title">Doctoral Researcher (ABD)</span>
    <span class="experience-date">Oct 2015 – Sep 2020</span>
  </div>
  <div class="experience-company">Technical University of Cluj-Napoca</div>
  <ul style="margin-top: 0.5rem; padding-left: 1.25rem; list-style: none;">
    <li class="achievement"><span class="achievement-icon">▹</span> <span>Modeled electrical behaviors in coronary artery disease using MATLAB and CFD (Ansys)</span></li>
    <li class="achievement"><span class="achievement-icon">▹</span> <span>Developed simulation workflows for data analysis and model validation</span></li>
  </ul>
</div>

<!-- Education -->

## Education

<div class="resume-section">
  <div class="education-item">
    <div class="education-degree">Doctoral Studies – Biomedical Engineering</div>
    <div>Technical University of Cluj-Napoca</div>
  </div>
  
  <div class="education-item" style="margin-top: 1rem;">
    <div class="education-degree">Master's Degree – Biomedical Engineering</div>
    <div>Technical University of Cluj-Napoca</div>
  </div>
  
  <div class="education-item" style="margin-top: 1rem;">
    <div class="education-degree">Engineer's Degree – Biomedical Engineering</div>
    <div>Technical University of Cluj-Napoca</div>
  </div>
</div>

<!-- Languages -->

## Languages

<div style="margin: 1.5rem 0;">
  <div style="margin-bottom: 1.5rem;">
    <div style="display: flex; justify-content: space-between; margin-bottom: 0.5rem;">
      <span style="font-weight: 600; font-size: 1.05rem;">English</span>
      <span style="opacity: 0.7;">Professional proficiency</span>
    </div>
    <div style="height: 6px; background: rgba(0,0,0,0.08); border-radius: 10px; overflow: hidden;">
      <div style="width: 95%; height: 100%; background: #8659f7; border-radius: 10px;"></div>
    </div>
  </div>
  
  <div style="margin-bottom: 1.5rem;">
    <div style="display: flex; justify-content: space-between; margin-bottom: 0.5rem;">
      <span style="font-weight: 600; font-size: 1.05rem;">Hungarian</span>
      <span style="opacity: 0.7;">Intermediate proficiency</span>
    </div>
    <div style="height: 6px; background: rgba(0,0,0,0.08); border-radius: 10px; overflow: hidden;">
      <div style="width: 55%; height: 100%; background: #8659f7; border-radius: 10px;"></div>
    </div>
  </div>
  
  <div>
    <div style="display: flex; justify-content: space-between; margin-bottom: 0.5rem;">
      <span style="font-weight: 600; font-size: 1.05rem;">Romanian</span>
      <span style="opacity: 0.7;">Native</span>
    </div>
    <div style="height: 6px; background: rgba(0,0,0,0.08); border-radius: 10px; overflow: hidden;">
      <div style="width: 100%; height: 100%; background: #8659f7; border-radius: 10px;"></div>
    </div>
  </div>
</div>

## Let's Connect

<div class="contact-links">
  <a href="https://github.com/Izabella-21" class="contact-item" target="_blank">
    <span class="contact-icon">📁</span>
    <span>GitHub</span>
    <span class="contact-handle">/Izabella-21</span>
  </a>
  <a href="https://www.linkedin.com/in/izabella-molnar/" class="contact-item" target="_blank">
    <span class="contact-icon">🔗</span>
    <span>LinkedIn</span>
    <span class="contact-handle">/in/izabella-molnar</span>
  </a>
  <a href="mailto:m.izabella21@gmail.com" class="contact-item">
    <span class="contact-icon">✉️</span>
    <span>Email</span>
    <span class="contact-handle">m.izabella21@gmail.com</span>
  </a>
</div>
