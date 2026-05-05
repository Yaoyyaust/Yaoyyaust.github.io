---
layout: default
title: Yuyou Yao
description: Computer Graphics · Power Diagram · Emergency Management
---

<style>
:root {
  --yy-primary: #12355b;
  --yy-primary-soft: #1f5f8b;
  --yy-accent: #f2a541;
  --yy-bg: #f7f9fc;
  --yy-card: #ffffff;
  --yy-text: #1f2933;
  --yy-muted: #5f6c7b;
  --yy-border: #e6edf5;
  --yy-shadow: 0 18px 45px rgba(18, 53, 91, 0.12);
  --yy-radius: 22px;
}

.yy-page {
  color: var(--yy-text);
  line-height: 1.72;
  font-size: 16px;
}

.yy-page a {
  color: var(--yy-primary-soft);
  text-decoration: none;
}

.yy-page a:hover {
  color: var(--yy-accent);
  text-decoration: none;
}

.yy-hero {
  position: relative;
  overflow: hidden;
  margin: 24px 0 34px;
  padding: 34px;
  border-radius: 30px;
  background:
    radial-gradient(circle at 12% 18%, rgba(242, 165, 65, 0.26), transparent 28%),
    radial-gradient(circle at 86% 8%, rgba(31, 95, 139, 0.24), transparent 30%),
    linear-gradient(135deg, #f9fbff 0%, #eef5fb 52%, #fdf8ef 100%);
  box-shadow: var(--yy-shadow);
  border: 1px solid rgba(230, 237, 245, 0.9);
}

.yy-hero::after {
  content: "";
  position: absolute;
  right: -90px;
  bottom: -120px;
  width: 340px;
  height: 340px;
  border-radius: 50%;
  border: 42px solid rgba(18, 53, 91, 0.06);
}

.yy-hero-inner {
  position: relative;
  z-index: 2;
  display: grid;
  grid-template-columns: 230px minmax(0, 1fr);
  gap: 32px;
  align-items: center;
}

.yy-photo-wrap {
  position: relative;
}

.yy-photo-wrap::before {
  content: "";
  position: absolute;
  inset: 15px -12px -12px 15px;
  background: linear-gradient(135deg, var(--yy-primary-soft), var(--yy-accent));
  border-radius: 26px;
  z-index: 0;
}

.yy-photo {
  position: relative;
  z-index: 1;
  width: 220px;
  height: 270px;
  object-fit: cover;
  border-radius: 26px;
  border: 6px solid rgba(255, 255, 255, 0.94);
  box-shadow: 0 18px 36px rgba(18, 53, 91, 0.20);
  background: #eaf0f6;
}

.yy-kicker {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 6px 12px;
  margin-bottom: 12px;
  border-radius: 999px;
  background: rgba(18, 53, 91, 0.08);
  color: var(--yy-primary);
  font-size: 0.86rem;
  font-weight: 700;
  letter-spacing: 0.02em;
}

.yy-name {
  margin: 0;
  color: var(--yy-primary);
  font-size: clamp(2.2rem, 5vw, 4rem);
  line-height: 1.05;
  letter-spacing: -0.04em;
}

.yy-cn-name {
  color: var(--yy-primary-soft);
  font-weight: 650;
}

.yy-title {
  margin: 14px 0 12px;
  color: var(--yy-text);
  font-size: 1.12rem;
}

.yy-affiliation {
  margin: 0 0 16px;
  color: var(--yy-muted);
}

.yy-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 20px 0 0;
}

.yy-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 9px 15px;
  border-radius: 999px;
  border: 1px solid rgba(18, 53, 91, 0.14);
  background: rgba(255, 255, 255, 0.76);
  color: var(--yy-primary) !important;
  font-weight: 700;
  box-shadow: 0 8px 22px rgba(18, 53, 91, 0.08);
}

.yy-button.primary {
  background: var(--yy-primary);
  color: #ffffff !important;
  border-color: var(--yy-primary);
}

.yy-button:hover {
  transform: translateY(-1px);
  box-shadow: 0 12px 25px rgba(18, 53, 91, 0.13);
}

.yy-nav {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: -8px 0 30px;
  padding: 12px;
  border: 1px solid var(--yy-border);
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.74);
  box-shadow: 0 10px 28px rgba(18, 53, 91, 0.06);
}

.yy-nav a {
  padding: 7px 13px;
  border-radius: 999px;
  color: var(--yy-muted);
  font-weight: 700;
  font-size: 0.92rem;
}

.yy-nav a:hover {
  background: var(--yy-primary);
  color: #fff;
}

.yy-section {
  margin: 34px 0;
}

.yy-section-title {
  display: flex;
  align-items: center;
  gap: 12px;
  margin: 0 0 18px;
  color: var(--yy-primary);
  font-size: 1.58rem;
  letter-spacing: -0.02em;
}

.yy-section-title::before {
  content: "";
  display: inline-block;
  width: 8px;
  height: 28px;
  border-radius: 99px;
  background: linear-gradient(180deg, var(--yy-primary-soft), var(--yy-accent));
}

.yy-grid {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 18px;
}

.yy-card {
  background: var(--yy-card);
  border: 1px solid var(--yy-border);
  border-radius: var(--yy-radius);
  padding: 22px;
  box-shadow: 0 14px 34px rgba(18, 53, 91, 0.07);
}

.yy-span-4 {
  grid-column: span 4;
}

.yy-span-6 {
  grid-column: span 6;
}

.yy-span-8 {
  grid-column: span 8;
}

.yy-span-12 {
  grid-column: span 12;
}

.yy-card h3 {
  margin-top: 0;
  margin-bottom: 10px;
  color: var(--yy-primary);
  font-size: 1.12rem;
}

.yy-card p {
  margin: 8px 0;
}

.yy-muted {
  color: var(--yy-muted);
}

.yy-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 12px;
}

.yy-tag {
  display: inline-flex;
  padding: 5px 10px;
  border-radius: 999px;
  background: #eef5fb;
  color: var(--yy-primary-soft);
  font-size: 0.82rem;
  font-weight: 700;
}

.yy-tag.gold {
  background: #fff3dc;
  color: #9a5a00;
}

.yy-highlight {
  border-left: 5px solid var(--yy-accent);
  background: linear-gradient(135deg, #fffaf1, #ffffff);
}

.yy-research-map {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 15px;
}

.yy-research-node {
  position: relative;
  min-height: 150px;
  padding: 20px;
  border-radius: 22px;
  background:
    radial-gradient(circle at top right, rgba(242, 165, 65, 0.18), transparent 42%),
    #ffffff;
  border: 1px solid var(--yy-border);
  box-shadow: 0 12px 30px rgba(18, 53, 91, 0.07);
}

.yy-research-node::after {
  content: "";
  position: absolute;
  right: 16px;
  bottom: 16px;
  width: 38px;
  height: 38px;
  border-radius: 50%;
  background: rgba(31, 95, 139, 0.10);
  box-shadow:
    -34px -28px 0 rgba(242, 165, 65, 0.12),
    -72px 4px 0 rgba(31, 95, 139, 0.08);
}

.yy-research-node h3 {
  margin: 0 0 10px;
  color: var(--yy-primary);
}

.yy-stat {
  text-align: center;
}

.yy-stat-number {
  display: block;
  color: var(--yy-primary);
  font-size: 2rem;
  font-weight: 800;
  line-height: 1;
}

.yy-stat-label {
  color: var(--yy-muted);
  font-size: 0.92rem;
}

.yy-timeline {
  position: relative;
  padding-left: 20px;
}

.yy-timeline::before {
  content: "";
  position: absolute;
  left: 4px;
  top: 6px;
  bottom: 6px;
  width: 2px;
  background: linear-gradient(var(--yy-primary-soft), var(--yy-accent));
  border-radius: 2px;
}

.yy-timeline-item {
  position: relative;
  margin: 0 0 18px;
  padding-left: 16px;
}

.yy-timeline-item::before {
  content: "";
  position: absolute;
  left: -21px;
  top: 7px;
  width: 10px;
  height: 10px;
  background: var(--yy-accent);
  border: 3px solid #fff;
  border-radius: 50%;
  box-shadow: 0 0 0 2px rgba(242, 165, 65, 0.35);
}

.yy-timeline-item strong {
  color: var(--yy-primary);
}

.yy-pub {
  padding: 18px 0;
  border-bottom: 1px dashed var(--yy-border);
}

.yy-pub:last-child {
  border-bottom: none;
}

.yy-pub-title {
  color: var(--yy-primary);
  font-weight: 800;
}

.yy-pub-meta {
  margin-top: 4px;
  color: var(--yy-muted);
  font-size: 0.95rem;
}

.yy-footer {
  margin: 42px 0 10px;
  padding: 26px;
  border-radius: 26px;
  background: var(--yy-primary);
  color: #ffffff;
}

.yy-footer a {
  color: #ffe2a8;
}

@media (max-width: 860px) {
  .yy-hero {
    padding: 24px;
  }

  .yy-hero-inner {
    grid-template-columns: 1fr;
  }

  .yy-photo {
    width: 190px;
    height: 235px;
  }

  .yy-span-4,
  .yy-span-6,
  .yy-span-8,
  .yy-span-12 {
    grid-column: span 12;
  }

  .yy-research-map {
    grid-template-columns: 1fr;
  }

  .yy-nav {
    border-radius: 22px;
  }
}
</style>

<div class="yy-page">

<section class="yy-hero">
  <div class="yy-hero-inner">
    <div class="yy-photo-wrap">
      <img class="yy-photo" src="{{ '/assets/img/yaoyy.jpg' | relative_url }}" alt="Yuyou Yao">
    </div>

    <div>
      <div class="yy-kicker">Computer Graphics · Power Diagram · Emergency Management</div>

      <h1 class="yy-name">Yuyou Yao <span class="yy-cn-name">姚裕友</span></h1>

      <p class="yy-title">
        <strong>Lecturer</strong>, School of Public Safety and Emergency Management<br>
        <strong>Master’s Supervisor</strong>, School of Computer Science and Engineering
      </p>

      <p class="yy-affiliation">
        Anhui University of Science & Technology (AUST)<br>
        Hefei, Anhui, China
      </p>

      <div class="yy-buttons">
        <a class="yy-button primary" href="mailto:yaoyy@aust.edu.cn">Email Me</a>
        <a class="yy-button" href="#research">Research</a>
        <a class="yy-button" href="#publications">Publications</a>
        <a class="yy-button" href="#students">Students</a>
      </div>
    </div>
  </div>
</section>

<nav class="yy-nav">
  <a href="#about">About</a>
  <a href="#research">Research</a>
  <a href="#publications">Publications</a>
  <a href="#projects">Projects</a>
  <a href="#teaching">Teaching</a>
  <a href="#students">Students</a>
  <a href="#contact">Contact</a>
</nav>

<section class="yy-section">
  <div class="yy-grid">
    <div class="yy-card yy-span-8 yy-highlight">
      <h3>Looking for Students / 欢迎加入</h3>
      <p>
        I am looking for motivated students interested in
        <strong>Computer Graphics</strong>,
        <strong>Computer Aided Geometric Design</strong>,
        <strong>Power Diagrams</strong>, and
        <strong>Computer-Aided Emergency Decision-Making</strong>.
      </p>
      <p class="yy-muted">
        欢迎对计算机图形学、计算机辅助几何设计、Power 图、应急设施选址分配、应急疏散与智能应急决策感兴趣的同学加入。
      </p>
    </div>

    <div class="yy-card yy-span-4">
      <h3>Research Keywords</h3>
      <div class="yy-tags">
        <span class="yy-tag">Power Diagram</span>
        <span class="yy-tag">Voronoi Diagram</span>
        <span class="yy-tag">Network Partition</span>
        <span class="yy-tag">Facility Location</span>
        <span class="yy-tag">Emergency Management</span>
        <span class="yy-tag gold">Intelligent Emergency Decision</span>
      </div>
    </div>
  </div>
</section>

<section id="about" class="yy-section">
  <h2 class="yy-section-title">About</h2>

  <div class="yy-grid">
    <div class="yy-card yy-span-8">
      <p>
        I obtained my B.S. and Ph.D. degrees from
        <strong>Hefei University of Technology (HFUT)</strong> in 2018 and 2023, respectively.
        My Ph.D. supervisor was <strong>Prof. Liping Zheng</strong>.
        I joined the <strong>School of Public Safety and Emergency Management</strong>,
        Anhui University of Science & Technology (AUST), in July 2023.
      </p>

      <p>
        My research interests include <strong>Computer Graphics</strong>,
        <strong>Computer Aided Geometric Design</strong>, and
        <strong>Emergency Management</strong>. I am particularly interested in
        computational geometry-based modeling and optimization methods, especially
        <strong>Power diagram-based algorithms</strong> and their applications in
        facility location, capacity-constrained allocation, emergency evacuation,
        and intelligent emergency decision-making.
      </p>
    </div>

    <div class="yy-card yy-span-4">
      <h3>At a Glance</h3>
      <div class="yy-grid">
        <div class="yy-card yy-span-6 yy-stat">
          <span class="yy-stat-number">9</span>
          <span class="yy-stat-label">Publications</span>
        </div>
        <div class="yy-card yy-span-6 yy-stat">
          <span class="yy-stat-number">3</span>
          <span class="yy-stat-label">Projects</span>
        </div>
        <div class="yy-card yy-span-6 yy-stat">
          <span class="yy-stat-number">4</span>
          <span class="yy-stat-label">Software Copyrights</span>
        </div>
        <div class="yy-card yy-span-6 yy-stat">
          <span class="yy-stat-number">2023</span>
          <span class="yy-stat-label">Joined AUST</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="research" class="yy-section">
  <h2 class="yy-section-title">Research</h2>

  <div class="yy-research-map">
    <div class="yy-research-node">
      <h3>Power Diagram Algorithms</h3>
      <p>
        Developing Power diagram and capacity-constrained geometric partition algorithms
        for dense demand, surface remeshing, and network-constrained spatial allocation.
      </p>
    </div>

    <div class="yy-research-node">
      <h3>Emergency Facility Location</h3>
      <p>
        Modeling emergency facility location-allocation problems with capacity,
        service areas, demand distribution, and disaster-response constraints.
      </p>
    </div>

    <div class="yy-research-node">
      <h3>Computer-Aided Emergency Decision</h3>
      <p>
        Integrating computational geometry, visualization, optimization, and emergency
        management scenarios to support intelligent emergency decision-making.
      </p>
    </div>
  </div>
</section>

<section id="experience" class="yy-section">
  <h2 class="yy-section-title">Education & Experience</h2>

  <div class="yy-card">
    <div class="yy-timeline">
      <div class="yy-timeline-item">
        <strong>2023.07 – Present</strong><br>
        Lecturer, Anhui University of Science & Technology
      </div>

      <div class="yy-timeline-item">
        <strong>2018.09 – 2023.07</strong><br>
        Ph.D., Hefei University of Technology<br>
        <span class="yy-muted">Supervisor: Prof. Liping Zheng</span>
      </div>

      <div class="yy-timeline-item">
        <strong>2014.09 – 2018.06</strong><br>
        B.S., Hefei University of Technology
      </div>
    </div>
  </div>
</section>

<section id="publications" class="yy-section">
  <h2 class="yy-section-title">Selected Publications</h2>

  <div class="yy-grid">
    <div class="yy-card yy-span-4">
      <h3>Capacity-Constrained Power Diagram</h3>
      <p>
        <strong>A heuristic computation method of the bi-level maximal capacity constrained centroidal power diagram</strong>
      </p>
      <p class="yy-muted">
        Communications in Information and Systems, 2025
      </p>
    </div>

    <div class="yy-card yy-span-4">
      <h3>Visualization via Power Diagram</h3>
      <p>
        <strong>PowerHierarchy: visualization approach of hierarchical data via power diagram</strong>
      </p>
      <p class="yy-muted">
        The Visual Computer, 2024
      </p>
    </div>

    <div class="yy-card yy-span-4">
      <h3>Surface Remeshing</h3>
      <p>
        <strong>PowerRTF: Power diagram based restricted tangent face for surface remeshing</strong>
      </p>
      <p class="yy-muted">
        Computer Graphics Forum, 2023
      </p>
    </div>
  </div>

  <div class="yy-card" style="margin-top:18px;">
    <div class="yy-pub">
      <div class="yy-pub-title">
        Yuyou Yao*, Boning Liu, Ensheng Liu, Dongjun Zhu, Chengjie Gu, Liping Zheng.
        A heuristic computation method of the bi-level maximal capacity constrained centroidal power diagram.
      </div>
      <div class="yy-pub-meta">
        Communications in Information and Systems, 2025, 25(1): 155–178.
      </div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">
        Yuyou Yao, Tao Li, Wenming Wu, Gaofeng Zhang, Liping Zheng*.
        PowerHierarchy: visualization approach of hierarchical data via power diagram.
      </div>
      <div class="yy-pub-meta">
        The Visual Computer, 2024, 40(3): 1499–1514.
      </div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">
        Dongjun Zhu, Chengjie Gu, Junjun Zhang, Yuyou Yao, Dayu Tan.
        Global-Margin Uncertainty and Collaborative Sampling for Active Learning in Complex Aerial Images Object Detection.
      </div>
      <div class="yy-pub-meta">
        IEEE Geoscience and Remote Sensing Letters, 2024, 21: 1–5.
      </div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">
        Jingjing Liu, Yuyou Yao, Yue Fei, Gaofeng Zhang, Liping Zheng*.
        Surface remeshing with preservation of sharp features through iterative identification and optimization of sample points.
      </div>
      <div class="yy-pub-meta">
        Computers & Graphics, 2024, 121: 103949.
      </div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">
        Yuyou Yao, Jingjing Liu, Yue Fei, Wenming Wu, Gaofeng Zhang, Dong-Ming Yan, Liping Zheng*.
        PowerRTF: Power diagram based restricted tangent face for surface remeshing.
      </div>
      <div class="yy-pub-meta">
        Computer Graphics Forum, 2023, 42(5): e14897.
      </div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">
        Yuyou Yao, Jingjing Liu, Wenming Wu, Gaofeng Zhang, Benzhu Xu, Liping Zheng*.
        Accelerating surface remeshing through GPU-based computation of the restricted tangent face.
      </div>
      <div class="yy-pub-meta">
        Computer Aided Geometric Design, 104: 102216.
      </div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">
        Yuyou Yao, Wenming Wu, Gaofeng Zhang, Benzhu Xu, Liping Zheng*.
        Power diagram based algorithm for the facility location and capacity acquisition problem with dense demand.
      </div>
      <div class="yy-pub-meta">
        Frontiers of Computer Science, 2022, 16(6): 166709.
      </div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">
        Tao Li, Yuyou Yao, Wenming Wu, Liping Zheng*.
        Pixelated Image Abstraction via Power Diagram.
      </div>
      <div class="yy-pub-meta">
        Proceedings of 2022 Asian Simulation Conference, 2022: 60–74.
      </div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">
        Liping Zheng, Yuyou Yao, Wenming Wu, Benzhu Xu, Gaofeng Zhang*.
        A novel computation method of hybrid capacity constrained centroidal power diagram.
      </div>
      <div class="yy-pub-meta">
        Computers & Graphics, 2021, 97: 108–116.
      </div>
    </div>
  </div>
</section>

<section id="projects" class="yy-section">
  <h2 class="yy-section-title">Projects</h2>

  <div class="yy-grid">
    <div class="yy-card yy-span-4">
      <h3>容量限制选址-分配-疏散</h3>
      <p>
        基于Power图的容量限制选址-分配-疏散算法研究
      </p>
      <p class="yy-muted">
        安徽理工大学校青年科技基金，2024.03–2026.03，主持
      </p>
    </div>

    <div class="yy-card yy-span-4">
      <h3>表面重网格化</h3>
      <p>
        平面近似下基于受限切平面的重新网格化方法研究
      </p>
      <p class="yy-muted">
        安徽理工大学引进人才科研启动基金，2023.10–2026.10，主持
      </p>
    </div>

    <div class="yy-card yy-span-4">
      <h3>多约束 Power 图</h3>
      <p>
        多约束Power图快速计算算法研究
      </p>
      <p class="yy-muted">
        国家自然科学基金面上项目，2020.01–2023.12，参与
      </p>
    </div>
  </div>
</section>

<section id="software" class="yy-section">
  <h2 class="yy-section-title">Patents & Software Copyrights</h2>

  <div class="yy-card">
    <div class="yy-pub">
      <div class="yy-pub-title">安途智选应急资源智能调配平台 V1.0</div>
      <div class="yy-pub-meta">软件著作权：2026SR0572466</div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">多约束 Power 图选址辅助决策系统 V1.0</div>
      <div class="yy-pub-meta">软件著作权：2026SR0252470</div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">容量限制 Power 图选址决策平台 V1.0</div>
      <div class="yy-pub-meta">软件著作权：2026SR0252460</div>
    </div>

    <div class="yy-pub">
      <div class="yy-pub-title">智慧应急设施选址评估决策平台 V1.0</div>
      <div class="yy-pub-meta">软件著作权：2026SR0119100</div>
    </div>
  </div>
</section>

<section id="teaching" class="yy-section">
  <h2 class="yy-section-title">Teaching</h2>

  <div class="yy-grid">
    <div class="yy-card yy-span-3">
      <h3>《C语言程序设计》</h3>
      <p class="yy-muted">Programming Foundation</p>
    </div>

    <div class="yy-card yy-span-3">
      <h3>《应急管理信息系统》</h3>
      <p class="yy-muted">Emergency Management Information Systems</p>
    </div>

    <div class="yy-card yy-span-3">
      <h3>《信息安全》</h3>
      <p class="yy-muted">Information Security</p>
    </div>

    <div class="yy-card yy-span-3">
      <h3>《创新创业》</h3>
      <p class="yy-muted">Innovation and Entrepreneurship</p>
    </div>
  </div>
</section>

<section id="students" class="yy-section">
  <h2 class="yy-section-title">Student Projects & Competitions</h2>

  <div class="yy-grid">
    <div class="yy-card yy-span-6">
      <h3>Undergraduate Innovation Projects</h3>

      <div class="yy-pub">
        <div class="yy-pub-title">智绘选址——基于Power图的应急设施选址优化领航者</div>
        <div class="yy-pub-meta">国家级，2025；项目负责人：柯卓彦</div>
      </div>

      <div class="yy-pub">
        <div class="yy-pub-title">智安逸行——城市应急疏散智能规划先锋</div>
        <div class="yy-pub-meta">省级，2025；项目负责人：刘博宁</div>
      </div>

      <div class="yy-pub">
        <div class="yy-pub-title">基于Power图的多状态障碍耦合环境应急逃生引导方法研究</div>
        <div class="yy-pub-meta">省级，2024；项目负责人：钟嘉浩</div>
      </div>
    </div>

    <div class="yy-card yy-span-6">
      <h3>Student Competitions</h3>

      <div class="yy-pub">
        <div class="yy-pub-title">中国国际大学生创新大赛</div>
        <div class="yy-pub-meta">2025，省级银奖；项目负责人：刘博宁</div>
      </div>

      <p class="yy-muted">
        I welcome students with interests in computational geometry, emergency management,
        optimization, visualization, and intelligent decision-making systems.
      </p>
    </div>
  </div>
</section>

<section id="contact" class="yy-section">
  <h2 class="yy-section-title">Contact</h2>

  <div class="yy-footer">
    <p>
      <strong>Yuyou Yao（姚裕友）</strong><br>
      School of Public Safety and Emergency Management<br>
      Anhui University of Science & Technology
    </p>

    <p>
      Room 309, Industry Education Integration Building<br>
      Hefei Campus, Anhui University of Science & Technology<br>
      Hefei, Anhui, 231131, China
    </p>

    <p>
      E-mail: <a href="mailto:yaoyy@aust.edu.cn">yaoyy@aust.edu.cn</a>
    </p>
  </div>
</section>

</div>
