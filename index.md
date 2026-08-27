---
layout: page
title: Yuyou Yao
description: Lecturer, Anhui University of Science & Technology
---

<style>
.profile-page {
  max-width: 1100px;
  margin: 0 auto;
  line-height: 1.7;
  color: #222;
  font-size: 16px;
}

.profile-header {
  display: flex;
  align-items: flex-start;
  gap: 28px;
  margin-top: 20px;
  margin-bottom: 28px;
  padding-bottom: 24px;
  border-bottom: 1px solid #e5e5e5;
}

.profile-photo {
  width: 190px;
  height: auto;
  border-radius: 6px;
  border: 1px solid #ddd;
  object-fit: cover;
}

.profile-info {
  flex: 1;
}

.profile-position {
  font-size: 1.05em;
  margin-bottom: 8px;
}

.profile-info h1 {
  margin: 0 0 12px 0;
  font-size: 2.2em;
  line-height: 1.2;
  color: #111;
}

.profile-info p {
  margin: 4px 0;
}

.profile-page a {
  color: #1f5f9f;
  text-decoration: none;
}

.profile-page a:hover {
  text-decoration: underline;
}

.notice-box {
  background: #f7f9fc;
  border-left: 4px solid #2f5597;
  padding: 14px 18px;
  margin: 24px 0 30px 0;
}

.notice-box p {
  margin: 6px 0;
}

.section {
  margin-top: 34px;
}

.section h2 {
  font-size: 1.55em;
  margin-bottom: 14px;
  padding-bottom: 6px;
  border-bottom: 1px solid #ddd;
  color: #111;
}

.section h3 {
  font-size: 1.15em;
  margin-top: 20px;
  margin-bottom: 8px;
  color: #222;
}

.research-list,
.teaching-list,
.software-list,
.student-list {
  margin-top: 8px;
  padding-left: 24px;
}

.research-list li,
.teaching-list li,
.software-list li,
.student-list li {
  margin-bottom: 6px;
}

.timeline-item {
  margin-bottom: 14px;
}

.timeline-date {
  font-weight: bold;
  color: #111;
}

.pub-list {
  counter-reset: pub-counter;
  padding-left: 0;
}

.pub-item {
  counter-increment: pub-counter;
  list-style: none;
  margin-bottom: 18px;
  padding-left: 34px;
  position: relative;
}

.pub-item::before {
  content: "[" counter(pub-counter) "]";
  position: absolute;
  left: 0;
  top: 0;
  font-weight: bold;
  color: #111;
}

.pub-title {
  font-weight: normal;
}

.pub-links {
  white-space: nowrap;
}

.pub-links a {
  margin-left: 6px;
  font-size: 0.95em;
}

.publication-item {
  display: flex;
  align-items: center;
  gap: 24px;
  margin-bottom: 34px;
}

.publication-image {
  flex: 0 0 245px;
  width: 245px;
  text-align: center;
}

.publication-image img {
  width: 100%;
  max-height: 180px;
  object-fit: contain;
  border: none;
}

.publication-info {
  flex: 1;
  min-width: 0;
}

.publication-title {
  font-size: 1.08em;
  font-weight: 600;
  line-height: 1.5;
  margin-bottom: 10px;
  color: #111;
}

.publication-authors {
  margin-bottom: 9px;
  line-height: 1.6;
}

.publication-venue {
  margin-bottom: 9px;
  line-height: 1.6;
}

.publication-links a {
  margin-right: 8px;
  font-weight: 500;
}

@media (max-width: 720px) {
  .publication-item {
    flex-direction: column;
    align-items: flex-start;
  }

  .publication-image {
    width: 100%;
    max-width: 300px;
    flex: none;
  }
}

.project-item {
  margin-bottom: 14px;
}

.contact-box {
  background: #f7f7f7;
  padding: 16px 18px;
  border-radius: 4px;
  border: 1px solid #e2e2e2;
}

.contact-box p {
  margin: 5px 0;
}

.student-name {
  display: inline-block;
  width: 5em;
  text-align: left;
  margin-right: 0.8em;
}

.student-name.two-char {
  letter-spacing: 1em;
}

@media (max-width: 720px) {
  .profile-header {
    flex-direction: column;
  }

  .profile-photo {
    width: 180px;
  }

  .pub-links {
    white-space: normal;
  }
}
</style>

<div class="profile-page">

  <div class="profile-header">

    <img src="{{ '/assets/images/yaoyy.jpg' | relative_url }}" alt="Yuyou Yao" class="profile-photo">

    <div class="profile-info">
      <h1>Yuyou Yao（姚裕友）</h1>
    
      <p class="profile-position">
        <strong>Lecturer</strong> | <strong>Master's Supervisor</strong>
      </p>
    
      <p>School of Public Safety and Emergency Management</p>
      <p>School of Computer Science and Engineering</p>
      <p>Anhui University of Science &amp; Technology</p>
    
      <br>
    
      <p>Room 309, Industry Education Integration Building</p>
      <p>Hefei Campus, Anhui University of Science &amp; Technology</p>
      <p>Hefei, Anhui, 231131, China</p>
    
      <p><strong>Email:</strong> <a href="mailto:yaoyy@aust.edu.cn">yaoyy@aust.edu.cn</a></p>
    </div>

  </div>

  <div class="notice-box">
    <p>
      I am looking for motivated students interested in
      <strong>Computer Graphics</strong>,
      <strong>Computer Aided Geometric Design</strong>, and
      <strong>Computer-Aided Emergency Decision-Making</strong>.
    </p>
    <p>
      欢迎对<strong>计算机图形学、计算机辅助几何设计、计算机辅助应急决策</strong>等方向感兴趣的同学加入。
    </p>
  </div>

  <div class="section" id="about">
    <h2>About Me</h2>

    <p>
      I obtained my B.S. and Ph.D. degrees from
      <strong>Hefei University of Technology (HFUT)</strong> in 2018 and 2023, respectively.
      My Ph.D. supervisor was <strong>Prof. Liping Zheng</strong>.
      I joined the <strong>School of Public Safety and Emergency Management, Anhui University of Science &amp; Technology (AUST)</strong>
      in July 2023.
    </p>

    <p>
      My research interests mainly focus on <strong>Computer Graphics</strong>,
      <strong>Computer Aided Geometric Design</strong>, and
      <strong>Computer-Aided Emergency Decision-Making</strong>.
      I am particularly interested in computational geometry-based modeling and optimization methods,
      especially <strong>Power diagram-based algorithms</strong> and their applications in facility location,
      capacity-constrained allocation, emergency evacuation, and intelligent emergency decision-making.
    </p>
  </div>

  <div class="section" id="research">
    <h2>Research Interests</h2>

    <ul class="research-list">
      <li>Computer Graphics</li>
      <li>Computer Aided Geometric Design</li>
      <li>Computer-Aided Emergency Decision-Making</li>
    </ul>
  </div>

  <div class="section" id="experience">
    <h2>Education and Experience</h2>

    <div class="timeline-item">
      <div class="timeline-date">2023.07 – Present</div>
      <div>Lecturer, Anhui University of Science &amp; Technology</div>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">2018.09 – 2023.07</div>
      <div>Ph.D., Hefei University of Technology</div>
      <div>Supervisor: Prof. Liping Zheng</div>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">2014.09 – 2018.06</div>
      <div>B.S., Hefei University of Technology</div>
    </div>
  </div>

  <div class="section" id="publications">
    <h2>Selected Publications</h2>

    <div class="publication-item">
      <div class="publication-image">
        <img src="{{ '/assets/publications/2026-cag-mccnpd/teaser.png' | relative_url }}" alt="MCCNPD">
      </div>
    </div>
    <div class="publication-info">
      <div class="publication-title">
        Network Power Diagrams with Maximum-Capacity Constraints for Embedded Network Partitioning
      </div>
      <div class="publication-authors">
        <strong>Yuyou Yao</strong><sup>#</sup>, Shouyan Xia, Ensheng Liu, Chengjie Gu
      </div>
      <div class="publication-venue">
        <em>Computers & Graphics</em>, 2026, 140: 104735.
      </div>
      <div class="publication-links">
        <a href="{{ '/assets/publications/2026-cag-mccnpd/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
      </div>
    </div>

    <ol class="pub-list">

      <li class="pub-item">
        <strong>Yuyou Yao</strong><sup>#</sup>, Shouyan Xia, Ensheng Liu, Chengjie Gu. 
        <span class="pub-title">Network Power Diagrams with Maximum-Capacity Constraints for Embedded Network Partitioning.</span>
        <em>Computers & Graphics</em>, 2026, 140: 104735.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2026-cag-mccnpd/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        Yue Fei, Jingjing Liu, <strong>Yuyou Yao</strong>, Yusheng Peng, Liping Zheng<sup>#</sup>.
        <span class="pub-title">A Remeshing Method via Adaptive Multiple Original-Facet-Clipping and Centroidal Voronoi Tessellation.</span>
        <em>2026 International Conference on 3D Vision (3DV)</em>, 2026, 1588-1597.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2026-3dv-remeshing/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        Dongyue Zhao, Qian Chen, <strong>Yuyou Yao</strong>, Yunhe Tong<sup>#</sup>.
        <span class="pub-title">A Candidate-Free Location Optimization Framework for Gas Repair Stations Under Stochastic Road Resistance Conditions.</span>
        <em>Urban Science</em>, 2026, 10(6): 303.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2026-uc-location/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        <strong>Yuyou Yao</strong><sup>#</sup>, Boning Liu, Ensheng Liu, Dongjun Zhu, Chengjie Gu, Liping Zheng.
        <span class="pub-title">A heuristic computation method of the bi-level maximal capacity constrained centroidal power diagram.</span>
        <em>Communications in Information and Systems</em>, 2025, 25(1): 155–178.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2025-cis-mccpd/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        <strong>Yuyou Yao</strong>, Tao Li, Wenming Wu, Gaofeng Zhang, Liping Zheng<sup>#</sup>.
        <span class="pub-title">PowerHierarchy: visualization approach of hierarchical data via power diagram.</span>
        <em>The Visual Computer</em>, 2024, 40(3): 1499–1514.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2024-tvc-powerhierarchy/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
          <a href="https://link.springer.com/article/10.1007/s00371-023-02864-4" target="_blank" rel="noopener">[video]</a>
        </span>
      </li>

      <li class="pub-item">
        Dongjun Zhu, Chengjie Gu, Junjun Zhang, <strong>Yuyou Yao</strong>, Dayu Tan.
        <span class="pub-title">Global-Margin Uncertainty and Collaborative Sampling for Active Learning in Complex Aerial Images Object Detection.</span>
        <em>IEEE Geoscience and Remote Sensing Letters</em>, 2024, 21: 1–5.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2024-lgrs-activelearning/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        Jingjing Liu, <strong>Yuyou Yao</strong>, Yue Fei, Gaofeng Zhang, Liping Zheng<sup>#</sup>.
        <span class="pub-title">Surface remeshing with preservation of sharp features through iterative identification and optimization of sample points.</span>
        <em>Computers &amp; Graphics</em>, 2024, 121: 103949.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2024-cag-sharpfeatures/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        <strong>Yuyou Yao</strong>, Jingjing Liu, Yue Fei, Wenming Wu, Gaofeng Zhang, Dong-Ming Yan, Liping Zheng<sup>#</sup>.
        <span class="pub-title">PowerRTF: Power diagram based restricted tangent face for surface remeshing.</span>
        <em>Computer Graphics Forum</em>, 2023, 42(5): e14897.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2023-cgf-powerrtf/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
          <a href="https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14897" target="_blank" rel="noopener">[video]</a>
        </span>
      </li>

      <li class="pub-item">
        <strong>Yuyou Yao</strong>, Jingjing Liu, Wenming Wu, Gaofeng Zhang, Benzhu Xu, Liping Zheng<sup>#</sup>.
        <span class="pub-title">Accelerating surface remeshing through GPU-based computation of the restricted tangent face.</span>
        <em>Computer Aided Geometric Design</em>, 2023, 104: 102216.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2023-cagd-rtf/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        <strong>Yuyou Yao</strong>, Wenming Wu, Gaofeng Zhang, Benzhu Xu, Liping Zheng<sup>#</sup>.
        <span class="pub-title">Power diagram based algorithm for the facility location and capacity acquisition problem with dense demand.</span>
        <em>Frontiers of Computer Science</em>, 2022, 16(6): 166709.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2022-fcs-powerlap/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
          <a href="{{ '/assets/publications/2022-fcs-powerlap/supplementary.zip' | relative_url }}" target="_blank" rel="noopener">[supplementary]</a>
        </span>
      </li>

      <li class="pub-item">
        Tao Li, <strong>Yuyou Yao</strong>, Wenming Wu, Liping Zheng<sup>#</sup>.
        <span class="pub-title">Pixelated Image Abstraction via Power Diagram.</span>
        <em>Proceedings of 2022 Asian Simulation Conference</em>, 2022: 60–74.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2022-asiansim-powerpixelated/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        Liping Zheng, <strong>Yuyou Yao</strong>, Wenming Wu, Benzhu Xu, Gaofeng Zhang<sup>#</sup>.
        <span class="pub-title">A novel computation method of hybrid capacity constrained centroidal power diagram.</span>
        <em>Computers &amp; Graphics</em>, 2021, 97: 108–116.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2021-cag-hcccpd/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        <strong>姚裕友</strong>, 张高峰, 徐本柱, 郑利平<sup>#</sup>.
        <span class="pub-title">变容量限制质心Power图的计算.</span>
        <em>图学学报</em>, 2021, 42(3): 492–500.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2021-jog-vcccpd/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        桂志强, <strong>姚裕友</strong>, 张高峰, 徐本柱, 郑利平<sup>#</sup>.
        <span class="pub-title">3D-Power图的快速生成方法.</span>
        <em>浙江大学学报（理学版）</em>, 2021, 48(4): 410–417.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2021-zjtu-3dpower/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

      <li class="pub-item">
        费月, 桂志强, <strong>姚裕友</strong>, 徐本柱, 郑利平<sup>#</sup>.
        <span class="pub-title">面状LED发光体灯珠分布和组合连接优化算法.</span>
        <em>系统仿真学报</em>, 2020, 32(12): 2317–2323.
        <span class="pub-links">
          <a href="{{ '/assets/publications/2020-jos-powerled/paper.pdf' | relative_url }}" target="_blank" rel="noopener">[paper]</a>
        </span>
      </li>

    </ol>
  </div>

  <div class="section" id="graduate-students">
    <h2>Graduate Students</h2>
    <p>
      I supervise graduate student in the areas of computer graphics, computer aided geometric design, and computer-aided emergency decision-making.
    </p>
    
    <h3>Master Students</h3>

    <ul class="student-list">
      <li>
        <strong>2025</strong>: 
        <span class="student-name">夏守岩</span>
      </li>
      <li>
        <strong>2026</strong>: 
        <span class="student-name two-char">魏杭</span>
        <span class="student-name">段金亮</span>
        <span class="student-name two-char">蓝瑞</span>
      </li>
    </ul>
  </div>

  <div class="section" id="projects">
    <h2>Projects</h2>

    <div class="project-item">
      <strong>[1]</strong>
      基于Power图的容量限制选址-分配-疏散算法研究，安徽理工大学校青年科技基金，2024.03–2026.03，主持。
    </div>

    <div class="project-item">
      <strong>[2]</strong>
      平面近似下基于受限切平面的重新网格化方法研究，安徽理工大学引进人才科研启动基金，2023.10–2026.10，主持。
    </div>

    <div class="project-item">
      <strong>[3]</strong>
      多约束Power图快速计算算法研究，国家自然科学基金面上项目，2020.01–2023.12，参与。
    </div>
  </div>

  <div class="section" id="software">
    <h2>Software Copyrights</h2>

    <ul class="software-list">
      <li>安途智选应急资源智能调配平台 V1.0，2026SR0572466</li>
      <li>多约束 Power 图选址辅助决策系统 V1.0，2026SR0252470</li>
      <li>容量限制 Power 图选址决策平台 V1.0，2026SR0252460</li>
      <li>智慧应急设施选址评估决策平台 V1.0，2026SR0119100</li>
    </ul>
  </div>

  <div class="section" id="teaching">
    <h2>Teaching</h2>

    <ul class="teaching-list">
      <li>《应急管理信息系统》</li>
      <li>《C语言程序设计》</li>
      <li>《信息安全》</li>
    </ul>
  </div>

  <div class="section" id="students">
    <h2>Student Projects and Competitions</h2>

    <h3>Undergraduate Innovation Projects</h3>

    <ul class="student-list">
      <li>
        路网约束下基于Power图的城市应急设施选址分配协同优化方法研究，国家级，2026 (项目负责人：秦梦圆)
      </li>
      <li>
        智绘选址——基于Power图的应急设施选址优化领航者，国家级，2025 (项目负责人：柯卓彦)
      </li>
      <li>
        基于Power图的应急救援机器人风险感知路径规划与动态避障导航研究，省级，2026 (项目负责人：孟繁旭)
      </li>
      <li>
        智安逸行——城市应急疏散智能规划先锋，省级，2025 (项目负责人：刘博宁)
      </li>
      <li>
        基于Power图的多状态障碍耦合环境应急逃生引导方法研究，省级，2024 (项目负责人：钟嘉浩)
      </li>
    </ul>

    <h3>Student Competitions</h3>

    <ul class="student-list">
      <li>
        中国国际大学生创新大赛，2025，省级银奖 (项目负责人：刘博宁)
      </li>
    </ul>
  </div>

  <div class="section" id="contact">
    <h2>Contact</h2>

    <div class="contact-box">
      <p><strong>Yuyou Yao（姚裕友）</strong></p>
      <p>School of Public Safety and Emergency Management</p>
      <p>Anhui University of Science &amp; Technology</p>
      <br>
      <p>Room 309, Industry Education Integration Building</p>
      <p>Hefei Campus, Anhui University of Science &amp; Technology</p>
      <p>Hefei, Anhui, 231131, China</p>
      <p><strong>Email:</strong> <a href="mailto:yaoyy@aust.edu.cn">yaoyy@aust.edu.cn</a></p>
    </div>
  </div>

</div>
