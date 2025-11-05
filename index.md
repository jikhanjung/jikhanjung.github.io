---
layout: default
title: 고생물학 소프트웨어
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
</style>

<div class="profile-section">
  <h2>🦴 About</h2>
  <p>고생물학 연구자이자 소프트웨어 개발자입니다. 형태학적 데이터 분석과 계통수 시각화를 위한 도구들을 개발하고 있습니다.</p>
  <p>Paleontologist and software developer creating tools for morphological data analysis and phylogenetic visualization.</p>
</div>

<div class="projects-section">
  <h2 style="text-align: center; color: #2c3e50; margin-bottom: 1em;">Projects</h2>
  <p style="text-align: center; color: #555; margin-bottom: 2em;">고생물학 연구를 지원하기 위해 개발된 소프트웨어 도구들입니다.</p>

  <div class="software-grid">
    <div class="software-card">
      <h3>Modan2</h3>
      <p>Comprehensive geometric morphometrics software</p>
      <p class="description-ko">포괄적인 기하학적 형태 측정학 소프트웨어</p>
      <div class="button-container">
        <a href="https://github.com/jikhanjung/Modan2" class="btn btn-github" target="_blank">GitHub</a>
        <a href="https://jikhanjung.github.io/Modan2/" class="btn btn-docs" target="_blank">문서</a>
      </div>
    </div>

    <div class="software-card">
      <h3>PhyloForester</h3>
      <p>Interactive phylogenetic tree visualization and analysis tool</p>
      <p class="description-ko">대화형 계통수 시각화 및 분석 도구</p>
      <div class="button-container">
        <a href="https://github.com/jikhanjung/PhyloForester" class="btn btn-github" target="_blank">GitHub</a>
        <a href="https://jikhanjung.github.io/PhyloForester/" class="btn btn-docs" target="_blank">문서</a>
      </div>
    </div>

    <div class="software-card">
      <h3>CTHarvester</h3>
      <p>CT image stack preprocessing software</p>
      <p class="description-ko">CT 이미지 스택 전처리 소프트웨어</p>
      <div class="button-container">
        <a href="https://github.com/jikhanjung/CTHarvester" class="btn btn-github" target="_blank">GitHub</a>
        <a href="https://jikhanjung.github.io/CTHarvester/" class="btn btn-docs" target="_blank">문서</a>
      </div>
    </div>
  </div>
</div>

---

<p style="text-align: center; margin-top: 3em; color: #666;">
  &copy; 2025 Paleontology Software | <a href="https://github.com/jikhanjung" target="_blank">GitHub</a>
</p>
