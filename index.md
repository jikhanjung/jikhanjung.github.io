---
layout: default
title: Jikhan Jung
lang: ko
---

<style>
  .profile-section {
    text-align: center;
    padding: 2em 1em;
    background: #f8f9fa;
    border-radius: 8px;
    margin-bottom: 2em;
  }

  .profile-section h2 {
    color: #2c3e50;
    margin-bottom: 1em;
  }

  .profile-section p {
    color: #333;
    font-size: 1.1em;
    line-height: 1.6;
  }

  .projects-section {
    margin-top: 3em;
  }

  .software-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
    margin-top: 30px;
  }

  .software-card {
    background: #f8f9fa;
    border-radius: 8px;
    padding: 30px;
    border: 2px solid #e9ecef;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .software-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
    border-color: #667eea;
  }

  .software-card h3 {
    color: #667eea;
    margin-bottom: 15px;
    font-size: 1.5em;
  }

  .software-card p {
    color: #666;
    margin-bottom: 15px;
  }

  .software-card .description-ko {
    font-size: 0.9em;
    color: #888;
    margin-bottom: 20px;
  }

  .button-container {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
  }

  .btn {
    display: inline-block;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s ease;
    flex: 1;
    text-align: center;
    min-width: 100px;
    color: white !important;
  }

  .btn-github {
    background: #2c3e50;
  }

  .btn-github:hover {
    background: #34495e;
  }

  .btn-docs {
    background: #667eea;
  }

  .btn-docs:hover {
    background: #5568d3;
  }

  .project-detail {
    background: #f8f9fa;
    border-radius: 8px;
    padding: 40px;
    margin-bottom: 30px;
    border: 2px solid #e9ecef;
  }

  .project-detail h3 {
    color: #667eea;
    font-size: 2em;
    margin-bottom: 20px;
  }

  .project-detail p {
    color: #333;
    font-size: 1.1em;
    line-height: 1.8;
    margin-bottom: 15px;
  }

  .project-detail ul {
    color: #333;
    font-size: 1.05em;
    line-height: 1.8;
    margin-bottom: 20px;
    margin-left: 20px;
  }

  .project-detail .links {
    margin-top: 25px;
  }

  .software-card {
    background: #f8f9fa;
    border-radius: 8px;
    padding: 30px;
    border: 2px solid #e9ecef;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    cursor: pointer;
  }

  .software-card a.card-link {
    text-decoration: none;
    color: inherit;
    display: block;
  }
</style>

<div class="profile-section">
  <h2>About me</h2>
  <p>Paleontologist and software developer creating tools for paleontology, geometric morphometrics, phylogenetics, visualization, and more.</p>
</div>

<div class="projects-section">
  <h2 style="text-align: center; color: #00ff00; margin-bottom: 1em;">Projects</h2>

  <div class="software-grid">
    <div class="software-card">
      <a href="#modan2" class="card-link">
        <h3>Modan2</h3>
        <p>Comprehensive geometric morphometrics software</p>
      </a>
    </div>

    <div class="software-card">
      <a href="#phyloforester" class="card-link">
        <h3>PhyloForester</h3>
        <p>GUI shell for phylogenetic analysis using TNT/IQTree/MrBayes</p>
      </a>
    </div>

    <div class="software-card">
      <a href="#ctharvester" class="card-link">
        <h3>CTHarvester</h3>
        <p>CT image stack preprocessing software</p>
      </a>
    </div>
  </div>
</div>

---

<div id="modan2" class="project-detail">
  <h3>Modan2</h3>
  <p>Modan2 is a comprehensive software package for geometric morphometrics analysis. It provides a complete workflow for analyzing shape variation in biological structures.</p>

  <p><strong>Key Features:</strong></p>
  <ul>
    <li>2D and 3D landmark-based geometric morphometric analysis</li>
    <li>Generalized Procrustes Analysis (GPA)</li>
    <li>Principal Component Analysis (PCA) for shape variation</li>
    <li>Canonical Variate Analysis (CVA)</li>
    <li>Interactive visualization tools</li>
    <li>Statistical analysis and hypothesis testing</li>
    <li>Export capabilities for publication-ready figures</li>
  </ul>

  <p>Perfect for researchers studying morphological variation in paleontology, evolutionary biology, and related fields.</p>

  <div class="links button-container">
    <a href="https://github.com/jikhanjung/Modan2" class="btn btn-github" target="_blank">GitHub Repository</a>
    <a href="https://jikhanjung.github.io/Modan2/" class="btn btn-docs" target="_blank">Documentation</a>
  </div>
</div>

<div id="phyloforester" class="project-detail">
  <h3>PhyloForester</h3>
  <p>PhyloForester is a user-friendly GUI application that serves as a unified interface for multiple phylogenetic analysis tools, making complex phylogenetic workflows more accessible.</p>

  <p><strong>Key Features:</strong></p>
  <ul>
    <li>Integrated support for TNT, IQTree, and MrBayes</li>
    <li>Intuitive graphical interface for phylogenetic analysis</li>
    <li>Tree visualization and manipulation tools</li>
    <li>Batch processing capabilities</li>
    <li>Parameter optimization helpers</li>
    <li>Result comparison and consensus tree generation</li>
    <li>Export trees in multiple formats (Newick, Nexus, etc.)</li>
  </ul>

  <p>Designed to streamline phylogenetic research by combining multiple powerful tools into a single, easy-to-use interface.</p>

  <div class="links button-container">
    <a href="https://github.com/jikhanjung/PhyloForester" class="btn btn-github" target="_blank">GitHub Repository</a>
    <a href="https://jikhanjung.github.io/PhyloForester/" class="btn btn-docs" target="_blank">Documentation</a>
  </div>
</div>

<div id="ctharvester" class="project-detail">
  <h3>CTHarvester</h3>
  <p>CTHarvester is a specialized tool for preprocessing CT (Computed Tomography) image stacks, designed to handle large-scale 3D imaging data efficiently.</p>

  <p><strong>Key Features:</strong></p>
  <ul>
    <li>Batch processing of CT image stacks</li>
    <li>Region of interest (ROI) extraction</li>
    <li>Format conversion (PNG, TIFF, etc.)</li>
    <li>Multi-level image generation for Level of Detail (LoD) optimization - creates downsampled versions at different resolutions for efficient visualization and processing</li>
  </ul>

  <p>The LoD feature generates multiple resolution levels from high-resolution CT data, enabling faster preview and navigation while maintaining access to full-resolution details when needed. This is particularly useful for handling large CT datasets that would otherwise be too memory-intensive to work with interactively.</p>

  <p>Essential for researchers working with CT scan data in paleontology, anatomy, and medical imaging.</p>

  <div class="links button-container">
    <a href="https://github.com/jikhanjung/CTHarvester" class="btn btn-github" target="_blank">GitHub Repository</a>
    <a href="https://jikhanjung.github.io/CTHarvester/" class="btn btn-docs" target="_blank">Documentation</a>
  </div>
</div>

---

<p style="text-align: center; margin-top: 3em; color: #666;">
  &copy; 2025 Jikhan Jung | <a href="https://github.com/jikhanjung" target="_blank">GitHub</a>
</p>
