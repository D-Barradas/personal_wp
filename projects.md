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
    
    <!-- Project 1 -->
    <div class="project-card" data-category="ml">
      <div class="project-image">🧠</div>
      <div class="project-content">
        <h3 class="project-title">Project Title 1</h3>
        <p style="color: #666; font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Category:</strong> Machine Learning
        </p>
        <p class="project-description">
          [Detailed project description explaining the problem, your approach, tools used, and results achieved]
        </p>
        <div class="project-tech">
          <span class="tech-badge">Python</span>
          <span class="tech-badge highlight">TensorFlow</span>
          <span class="tech-badge">Deep Learning</span>
        </div>
        <p style="color: #666; margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> [Describe the impact or outcome of this project]
        </p>
        <div class="project-links" style="margin-top: 20px;">
          <a href="#">View Details</a>
          <a href="#">GitHub Repo</a>
          <a href="#">Live Demo</a>
        </div>
      </div>
    </div>

    <!-- Project 2 -->
    <div class="project-card" data-category="viz">
      <div class="project-image">📊</div>
      <div class="project-content">
        <h3 class="project-title">Project Title 2</h3>
        <p style="color: #666; font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Category:</strong> Data Visualization
        </p>
        <p class="project-description">
          [Detailed project description explaining the problem, your approach, tools used, and results achieved]
        </p>
        <div class="project-tech">
          <span class="tech-badge">Plotly</span>
          <span class="tech-badge highlight">React</span>
          <span class="tech-badge">Interactive</span>
        </div>
        <p style="color: #666; margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> [Describe the impact or outcome of this project]
        </p>
        <div class="project-links" style="margin-top: 20px;">
          <a href="#">View Details</a>
          <a href="#">GitHub Repo</a>
          <a href="#">Live Demo</a>
        </div>
      </div>
    </div>

    <!-- Project 3 -->
    <div class="project-card" data-category="data">
      <div class="project-image">📈</div>
      <div class="project-content">
        <h3 class="project-title">Project Title 3</h3>
        <p style="color: #666; font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Category:</strong> Data Science
        </p>
        <p class="project-description">
          [Detailed project description explaining the problem, your approach, tools used, and results achieved]
        </p>
        <div class="project-tech">
          <span class="tech-badge">Python</span>
          <span class="tech-badge highlight">Pandas</span>
          <span class="tech-badge">Analytics</span>
        </div>
        <p style="color: #666; margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> [Describe the impact or outcome of this project]
        </p>
        <div class="project-links" style="margin-top: 20px;">
          <a href="#">View Details</a>
          <a href="#">GitHub Repo</a>
          <a href="#">Live Demo</a>
        </div>
      </div>
    </div>

    <!-- Project 4 -->
    <div class="project-card" data-category="ml">
      <div class="project-image">🤖</div>
      <div class="project-content">
        <h3 class="project-title">Project Title 4</h3>
        <p style="color: #666; font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Category:</strong> Machine Learning
        </p>
        <p class="project-description">
          [Detailed project description explaining the problem, your approach, tools used, and results achieved]
        </p>
        <div class="project-tech">
          <span class="tech-badge">PyTorch</span>
          <span class="tech-badge highlight">NLP</span>
          <span class="tech-badge">Transformers</span>
        </div>
        <p style="color: #666; margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> [Describe the impact or outcome of this project]
        </p>
        <div class="project-links" style="margin-top: 20px;">
          <a href="#">View Details</a>
          <a href="#">GitHub Repo</a>
          <a href="#">Live Demo</a>
        </div>
      </div>
    </div>

    <!-- Project 5 -->
    <div class="project-card" data-category="viz">
      <div class="project-image">🎨</div>
      <div class="project-content">
        <h3 class="project-title">Project Title 5</h3>
        <p style="color: #666; font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Category:</strong> Data Visualization
        </p>
        <p class="project-description">
          [Detailed project description explaining the problem, your approach, tools used, and results achieved]
        </p>
        <div class="project-tech">
          <span class="tech-badge">D3.js</span>
          <span class="tech-badge highlight">JavaScript</span>
          <span class="tech-badge">Interactive</span>
        </div>
        <p style="color: #666; margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> [Describe the impact or outcome of this project]
        </p>
        <div class="project-links" style="margin-top: 20px;">
          <a href="#">View Details</a>
          <a href="#">GitHub Repo</a>
          <a href="#">Live Demo</a>
        </div>
      </div>
    </div>

    <!-- Project 6 -->
    <div class="project-card" data-category="data">
      <div class="project-image">🔬</div>
      <div class="project-content">
        <h3 class="project-title">Project Title 6</h3>
        <p style="color: #666; font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Category:</strong> Data Science
        </p>
        <p class="project-description">
          [Detailed project description explaining the problem, your approach, tools used, and results achieved]
        </p>
        <div class="project-tech">
          <span class="tech-badge">R</span>
          <span class="tech-badge highlight">Statistics</span>
          <span class="tech-badge">ggplot2</span>
        </div>
        <p style="color: #666; margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> [Describe the impact or outcome of this project]
        </p>
        <div class="project-links" style="margin-top: 20px;">
          <a href="#">View Details</a>
          <a href="#">GitHub Repo</a>
          <a href="#">Live Demo</a>
        </div>
      </div>
    </div>

    <!-- Project 7 -->
    <div class="project-card" data-category="ml">
      <div class="project-image">🚀</div>
      <div class="project-content">
        <h3 class="project-title">Project Title 7</h3>
        <p style="color: #666; font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Category:</strong> Machine Learning
        </p>
        <p class="project-description">
          [Detailed project description explaining the problem, your approach, tools used, and results achieved]
        </p>
        <div class="project-tech">
          <span class="tech-badge">CUDA</span>
          <span class="tech-badge highlight">GPU Computing</span>
          <span class="tech-badge">NVIDIA</span>
        </div>
        <p style="color: #666; margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> [Describe the impact or outcome of this project]
        </p>
        <div class="project-links" style="margin-top: 20px;">
          <a href="#">View Details</a>
          <a href="#">GitHub Repo</a>
          <a href="#">Live Demo</a>
        </div>
      </div>
    </div>

    <!-- Project 8 -->
    <div class="project-card" data-category="viz">
      <div class="project-image">🎯</div>
      <div class="project-content">
        <h3 class="project-title">Project Title 8</h3>
        <p style="color: #666; font-size: 0.9rem; margin-bottom: 10px;">
          <strong>Category:</strong> Data Visualization
        </p>
        <p class="project-description">
          [Detailed project description explaining the problem, your approach, tools used, and results achieved]
        </p>
        <div class="project-tech">
          <span class="tech-badge">Tableau</span>
          <span class="tech-badge highlight">Business Intelligence</span>
          <span class="tech-badge">Analytics</span>
        </div>
        <p style="color: #666; margin-top: 15px; font-size: 0.9rem;">
          <strong>Impact:</strong> [Describe the impact or outcome of this project]
        </p>
        <div class="project-links" style="margin-top: 20px;">
          <a href="#">View Details</a>
          <a href="#">GitHub Repo</a>
          <a href="#">Live Demo</a>
        </div>
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
