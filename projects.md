---
layout: default
title: Projects & Portfolio
permalink: /projects/
---

<!-- Hero Section -->
<section class="hero-section" style="min-height: 400px;">
  <div class="hero-content">
    <h1>Featured Projects</h1>
    <p class="subtitle">Data Science, Machine Learning & Scientific Computing</p>
    <p class="tagline">Explore my work in research, visualization, and AI applications</p>
  </div>
</section>

<!-- Project Filter (Optional) -->
<section class="section-container">
  <div style="text-align: center; max-width: 1000px; margin: 0 auto;">
    <div style="display: flex; gap: 10px; flex-wrap: wrap; justify-content: center; margin-bottom: 40px;">
      <button style="padding: 10px 20px; background: var(--primary-blue); color: white; border: none; border-radius: 20px; cursor: pointer; font-weight: 600; transition: all 0.3s;" onclick="filterProjects('all')">All Projects</button>
      <button style="padding: 10px 20px; background: white; color: var(--primary-blue); border: 2px solid var(--primary-blue); border-radius: 20px; cursor: pointer; font-weight: 600; transition: all 0.3s;" onclick="filterProjects('ml')">Machine Learning</button>
      <button style="padding: 10px 20px; background: white; color: var(--primary-blue); border: 2px solid var(--primary-blue); border-radius: 20px; cursor: pointer; font-weight: 600; transition: all 0.3s;" onclick="filterProjects('viz')">Visualization</button>
      <button style="padding: 10px 20px; background: white; color: var(--primary-blue); border: 2px solid var(--primary-blue); border-radius: 20px; cursor: pointer; font-weight: 600; transition: all 0.3s;" onclick="filterProjects('data')">Data Science</button>
    </div>
  </div>
</section>

<!-- Full Projects Grid -->
<section class="section-container alternate">
  <div class="project-grid" style="max-width: 1200px; margin: 0 auto;">
    
    <!-- Project 1: Micro-fossil Classification -->
    <div class="project-card" data-category="ml">
      <div class="project-image">🔬</div>
      <div class="project-content">
        <h3 class="project-title">Micro-fossil Classification</h3>
        <p style="color: rgba(255, 255, 255, 0.7); font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Organization:</strong> KAUST Visualization Lab | <strong>Period:</strong> 2025 - 2026
        </p>
        <p class="project-description">
          Led a team of KAUST staff to develop an advanced deep learning system for micro-fossil classification from 2D Micro-CT slices. 
          Managed data provenance and coordinated analysis workflows to achieve high-accuracy species identification.
        </p>
        <div class="project-tech">
          <span class="tech-badge highlight">Deep Learning</span>
          <span class="tech-badge">PyTorch</span>
          <span class="tech-badge">Micro-CT Imaging</span>
          <span class="tech-badge">Team Leadership</span>
        </div>
        <p style="color: rgba(255, 255, 255, 0.7); margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> Enabled automated foraminifera species classification with unprecedented accuracy
        </p>
      </div>
    </div>

    <!-- Project 2: Coral Health Assessment -->
    <div class="project-card" data-category="ml">
      <div class="project-image">🪸</div>
      <div class="project-content">
        <h3 class="project-title">Coral Health Assessment</h3>
        <p style="color: rgba(255, 255, 255, 0.7); font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Organization:</strong> KAUST Visualization Lab | <strong>Period:</strong> 2023 - 2025
        </p>
        <p class="project-description">
          Developed an AI-powered coral health assessment application using Meta's Segment Anything Model (SAM) to analyze underwater coral photographs. 
          Created containerized solutions and built a user-friendly application for marine scientists to assess coral health indicators.
        </p>
        <div class="project-tech">
          <span class="tech-badge highlight">Computer Vision</span>
          <span class="tech-badge">SAM (Meta AI)</span>
          <span class="tech-badge">Docker</span>
          <span class="tech-badge">Python</span>
          <span class="tech-badge">Marine Biology</span>
        </div>
        <p style="color: rgba(255, 255, 255, 0.7); margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> Published tool (Coral-CAT) enabling semi-automatic coral color analysis for researchers
        </p>
        <div class="project-links" style="margin-top: 20px;">
          <a href="https://github.com/D-Barradas">GitHub Repo</a>
        </div>
      </div>
    </div>

    <!-- Project 3: SlideGAN Optimization -->
    <div class="project-card" data-category="ml">
      <div class="project-image">⚡</div>
      <div class="project-content">
        <h3 class="project-title">SlideGAN Optimization</h3>
        <p style="color: rgba(255, 255, 255, 0.7); font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Organization:</strong> KAUST Visualization Lab | <strong>Period:</strong> 2023 - 2025
        </p>
        <p class="project-description">
          Led engineering team to refactor and optimize SlideGAN code for 3D seismic microstructure generation. 
          Conducted comprehensive strong scalability testing across multiple GPU configurations to maximize performance.
        </p>
        <div class="project-tech">
          <span class="tech-badge highlight">GANs</span>
          <span class="tech-badge">GPU Optimization</span>
          <span class="tech-badge">HPC</span>
          <span class="tech-badge">Code Refactoring</span>
          <span class="tech-badge">Performance Testing</span>
        </div>
        <p style="color: rgba(255, 255, 255, 0.7); margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> Achieved significant performance improvements enabling faster seismic data generation
        </p>
      </div>
    </div>

    <!-- Project 4: Protein-Protein Interaction Prediction -->
    <div class="project-card" data-category="ml">
      <div class="project-image">🧬</div>
      <div class="project-content">
        <h3 class="project-title">AI for Protein-Protein Interaction Prediction</h3>
        <p style="color: rgba(255, 255, 255, 0.7); font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Organization:</strong> KAUST AI Initiative | <strong>Period:</strong> 2019 - 2023 | <strong>Funding:</strong> USD $112,000
        </p>
        <p class="project-description">
          Secured major funding from KAUST AI Initiative to develop innovative AI strategies for protein-protein interaction prediction at the structural level. 
          Implemented weakly supervised data augmentation and created three enhanced machine learning classifiers. Produced three peer-reviewed publications.
        </p>
        <div class="project-tech">
          <span class="tech-badge highlight">Machine Learning</span>
          <span class="tech-badge">Structural Biology</span>
          <span class="tech-badge">Data Augmentation</span>
          <span class="tech-badge">Protein Docking</span>
          <span class="tech-badge">Bioinformatics</span>
        </div>
        <p style="color: rgba(255, 255, 255, 0.7); margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> Advanced protein interaction prediction accuracy, resulting in 3 scientific publications
        </p>
        <div class="project-links" style="margin-top: 20px;">
          <a href="https://scholar.google.com/citations?user=YOUR_ID">Publications</a>
        </div>
      </div>
    </div>

    <!-- Project 5: Shaheen III Performance Testing -->
    <div class="project-card" data-category="data">
      <div class="project-image">🖥️</div>
      <div class="project-content">
        <h3 class="project-title">Shaheen III Supercomputer Performance Testing</h3>
        <p style="color: rgba(255, 255, 255, 0.7); font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Organization:</strong> KAUST RCCL | <strong>Period:</strong> 2022 - 2023
        </p>
        <p class="project-description">
          Developed comprehensive benchmark suite for Shaheen III supercomputer performance evaluation. 
          Created Python-based HPC applications to identify performance bottlenecks and optimize system efficiency for production workloads.
        </p>
        <div class="project-tech">
          <span class="tech-badge highlight">HPC</span>
          <span class="tech-badge">Python</span>
          <span class="tech-badge">Benchmarking</span>
          <span class="tech-badge">Performance Analysis</span>
          <span class="tech-badge">Supercomputing</span>
        </div>
        <p style="color: rgba(255, 255, 255, 0.7); margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> Validated performance capabilities of Shaheen III before production deployment
        </p>
      </div>
    </div>

  </div>
</section>

<!-- Call to Action -->
<section class="section-container">
  <div style="text-align: center; max-width: 600px; margin: 0 auto;">
    <h2 style="color: var(--primary-blue); font-size: 2rem; margin-bottom: 20px;">Want to Collaborate?</h2>
    <p style="color: #555; font-size: 1.1rem; line-height: 1.8; margin-bottom: 30px;">
      If you have an interesting project or research idea you'd like to discuss, I'd love to hear about it. 
      Let's create something impactful together!
    </p>
    <a href="/#contact" class="btn-cta">Get In Touch</a>
  </div>
</section>

<script>
function filterProjects(category) {
  const projects = document.querySelectorAll('.project-card');
  
  projects.forEach(project => {
    if (category === 'all' || project.dataset.category === category) {
      project.style.display = 'block';
    } else {
      project.style.display = 'none';
    }
  });
  
  // Update button styles
  const buttons = document.querySelectorAll('button[onclick]');
  buttons.forEach(btn => {
    btn.style.background = 'white';
    btn.style.color = 'var(--primary-blue)';
    btn.style.border = '2px solid var(--primary-blue)';
  });
  
  event.target.style.background = 'var(--primary-blue)';
  event.target.style.color = 'white';
  event.target.style.border = '2px solid var(--primary-blue)';
}
</script>
