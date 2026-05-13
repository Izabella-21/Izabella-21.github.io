---
layout: fullwidth
title: Portfolio
permalink: /portfolio/
---

<style>
  .fullwidth-container {
    max-width: 1400px !important;
    width: 100% !important;
  }
  .page-content {
    max-width: 100% !important;
  }
  .project-item {
    position: relative;
    background: var(--background-color);
    border: 1px solid rgba(0,0,0,0.1);
    border-radius: 16px;
    padding: 1.5rem;
    transition: all 0.3s ease;
    overflow: hidden;
  }

[data-theme="dark"] .project-item {
  border: 1px solid rgba(255,255,255,0.1);
}

.project-item::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(135deg, #8659f7, #a855f7);
  opacity: 0;
  transition: opacity 0.3s ease;
  z-index: -1;
}

.project-item:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 25px rgba(0,0,0,0.1);
}

.project-item:hover::before {
  opacity: 0.05;
}
</style>

## Featured Projects

<div class="projects-grid">
  <div class="project-card">
    <div class="project-header">
      <span class="project-status">Active</span>
    </div>
    <h3 class="project-title">Python API Testing Framework</h3>
    <p class="project-description">Enterprise-grade API testing suite built with Pytest and Requests. Features automated validation, response schema checking, and CI/CD integration.</p>
    <div class="project-tech">
      <span class="tech-tag">Python</span>
      <span class="tech-tag">Pytest</span>
      <span class="tech-tag">REST API</span>
      <span class="tech-tag">GitHub Actions</span>
    </div>
    <div class="project-links">
      <a href="https://github.com/Izabella-21" class="project-link" target="_blank">View on GitHub →</a>
    </div>
  </div>
  
  <div class="project-card">
    <div class="project-header">
      <span class="project-status">In Development</span>
    </div>
    <h3 class="project-title">Cypress E2E Test Suite</h3>
    <p class="project-description">Complete end-to-end testing solution for web applications with visual regression testing and automated reporting.</p>
    <div class="project-tech">
      <span class="tech-tag">Cypress</span>
      <span class="tech-tag">JavaScript</span>
      <span class="tech-tag">TypeScript</span>
    </div>
    <div class="project-links">
      <a href="https://github.com/Izabella-21" class="project-link" target="_blank">View on GitHub →</a>
    </div>
  </div>
  
  <div class="project-card">
    <div class="project-header">
      <span class="project-status">Experimental</span>
    </div>
    <h3 class="project-title">AI-Powered Test Generator</h3>
    <p class="project-description">Research project using LLMs to automatically generate test cases from natural language requirements.</p>
    <div class="project-tech">
      <span class="tech-tag">Python</span>
      <span class="tech-tag">OpenAI API</span>
      <span class="tech-tag">LangChain</span>
    </div>
    <div class="project-links">
      <a href="https://github.com/Izabella-21" class="project-link" target="_blank">Coming soon →</a>
    </div>
  </div>
</div>