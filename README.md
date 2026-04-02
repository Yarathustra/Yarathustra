---
# GitHub Profile README.md（高度还原你原学术主页风格）
# 直接复制下方全部内容 → 新建/覆盖你的 GitHub 个人仓库（Yarathustra/Yarathustra）中的 README.md 即可
# 图片路径已自动适配 GitHub（请确保 assets/images/profile.jpg 已上传到你的个人仓库）
---

<style>
  /* 1. 兼容性变量：仅作用于我们自己的元素 */
  #academic-profile {
    --primary: #2c3e50;
    --accent: #007bff;
    --border: #e9ecef;
    --text-m: #666;
    color: var(--primary);
    line-height: 1.6;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  }

  /* 2. 修复重叠：给内容区顶部留出呼吸空间 */
  .profile-container {
    padding-top: 20px;
    display: block;
    overflow: hidden;
  }

  /* 3. 个人简介：浮动布局 */
  .header-box {
    margin-bottom: 30px;
    border-bottom: 1px solid var(--border);
    padding-bottom: 20px;
  }

  .profile-pic {
    float: right;
    width: 160px;
    border-radius: 12px;
    margin-left: 25px;
    margin-bottom: 15px;
    box-shadow: 0 6px 12px rgba(0,0,0,0.12);
  }

  @media (max-width: 768px) {
    .profile-pic { 
      float: none; 
      display: block; 
      margin: 0 auto 25px; 
      width: 140px;
    }
  }

  /* 4. 章节标题优化 */
  #academic-profile h2 {
    border-bottom: 2px solid var(--border);
    padding-bottom: 8px;
    margin-top: 45px !important;
    color: var(--primary);
    clear: both;
  }

  /* 5. 卡片系统 */
  .pub-card {
    border-left: 5px solid var(--accent);
    padding: 18px 20px;
    margin-bottom: 25px;
    background: #f8f9fa;
    border-radius: 4px;
  }

  .exp-card {
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 18px;
    margin-bottom: 18px;
    background: #fff;
    box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  }

  .badge-row { 
    margin-top: 12px; 
    display: flex; 
    gap: 10px; 
    flex-wrap: wrap; 
  }
  
  .pill {
    padding: 4px 12px;
    font-size: 0.82em;
    border-radius: 6px;
    text-decoration: none !important;
    display: inline-block;
    font-weight: 500;
  }
  .pill-blue { background: var(--accent); color: white !important; }
  .pill-red { background: #B31B1B; color: white !important; }
  .pill-gray { background: #24292e; color: white !important; }
  .pill-yellow { background: #fff3cd; color: #856404; border: 1px solid #ffeeba; }
  .pill-skill { 
    background: #f0f2f5; 
    color: #495057; 
    border: 1px solid #d1d9e6; 
    margin-right: 6px;
    padding: 3px 11px;
  }

  /* 6. 课程表 */
  .course-list {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    gap: 8px;
    list-style: none;
    padding: 0;
  }
  .course-list li::before { content: "• "; color: var(--accent); }
</style>

<div id="academic-profile">

  <div class="profile-container">
    <img src="https://github.com/Yarathustra/Yarathustra/blob/main/assets/images/profile.jpg?raw=true" class="profile-pic" alt="Zhangrui Yang">
    
    <div class="header-box">
      <h1 style="margin-top:0; font-size:2.3em;">Zhangrui Yang (杨章睿)</h1>
      <p style="font-size:1.15em; margin-bottom:8px;">
        Undergraduate Researcher<br>
        Computer Science and Technology (Elite Program)<br>
        <a href="https://ghc.tongji.edu.cn/" style="color:var(--accent);">Guohao College</a>, Tongji University
      </p>
      <p>
        <a href="mailto:jerry.zryang@hotmail.com">📧 Email</a> &nbsp;•&nbsp; 
        <a href="https://github.com/Yarathustra">🐙 GitHub</a> &nbsp;•&nbsp; 
        <a href="https://scholar.google.com/citations?user=1io0foEAAAAJ">🎓 Google Scholar</a>
      </p>
    </div>
  </div>

  <section>
    <h2>About</h2>
    <p style="font-size: 1.1em; color: #34495e; font-weight: 500;">
      I am an undergraduate researcher in the <strong style="color:var(--accent)">Elite Program</strong> at Tongji University. 
      My research lies at the intersection of <strong style="color:var(--accent)">vision-language models</strong> and <strong style="color:var(--accent)">spatial reasoning</strong>.
    </p>
    <p>
      My work investigates how multimodal models represent spatial structure and how evaluation protocols can distinguish genuine spatial reasoning from shortcut learning.
    </p>
  </section>

  <section>
    <h2>Publications</h2>
    
    <div class="pub-card">
      <strong style="display:block; font-size:1.15em;">Enhancing Adversarial Attacks with Decision Boundary Information</strong>
      <span style="color:#555"><strong>Zhangrui Yang</strong>, Shengming Yuan, Bo Wang, Yaya Cheng, Pengpeng Zeng, Zheng Wang, Xuanhan Wang, Jingkuan Song</span><br>
      <span style="font-style:italic">Information Fusion, 2026</span> <span style="color:#e67e22; font-weight:bold;">[Under Review]</span><br>
      <div class="badge-row">
        <a href="https://github.com/Yarathustra/BF-Attack" class="pill pill-gray">Code</a>
      </div>
    </div>

    <div class="pub-card">
      <strong style="display:block; font-size:1.15em;">Pseudo-Label Refinement for Robust Wheat Head Segmentation</strong>
      <span style="color:#555">Jiahao Jiang*, <strong>Zhangrui Yang</strong>*, Xuanhan Wang, Jingkuan Song</span><br>
      <span style="font-style:italic">CVPPA Workshop, ICCV 2025</span><br>
      <div class="badge-row">
        <a href="https://arxiv.org/abs/2512.11874" class="pill pill-red">arXiv</a>
      </div>
    </div>
    <small>* Equal contribution</small>
  </section>

  <section>
    <h2>Research Experience</h2>
    <div class="exp-card">
      <div style="display:flex; justify-content:space-between; align-items: center;">
        <strong>Global Wheat Full Semantic Segmentation</strong>
        <span class="pill pill-yellow">Global Rank #2</span>
      </div>
      <p style="margin-top:10px; color:#444;">
        Developed a pseudo-label refinement framework for wheat head segmentation, focusing on iterative teacher-student training.
      </p>
    </div>
  </section>

  <section>
    <h2>Selected Honors</h2>
    <ul style="list-style:none; padding:0;">
      <li style="margin-bottom:8px;">🏆 Global 2nd Place — Global Wheat Full Semantic Segmentation Competition</li>
      <li style="margin-bottom:8px;">🏆 National First Prize — iCAN AI Innovation Competition (SurgeryMind)</li>
      <li style="margin-bottom:8px;">🏆 Shanghai Second Prize — National Mathematical Modeling Contest</li>
      <li style="margin-bottom:8px;">🏆 Academic Scholarship — Guohao College, Tongji University</li>
    </ul>
  </section>

  <section>
    <h2>Technical Skills</h2>
    <p>
      <strong>Programming:</strong> 
      <span class="pill pill-skill">Python</span>
      <span class="pill pill-skill">C++</span>
      <span class="pill pill-skill">Verilog HDL</span>
      <span class="pill pill-skill">SQL</span><br><br>
      <strong>Frameworks:</strong> 
      <span class="pill pill-skill">PyTorch</span><br><br>
      <strong>Tools:</strong> 
      <span class="pill pill-skill">Linux</span>
      <span class="pill pill-skill">Git</span>
      <span class="pill pill-skill">LaTeX</span>
    </p>
  </section>

  <section>
    <h2>Education</h2>
    <div style="background: #f8f9fa; padding: 20px; border-radius: 10px; border-left: 5px solid var(--accent);">
      <div style="display:flex; justify-content:space-between; flex-wrap:wrap;">
        <strong>Tongji University</strong>
        <span style="color:#666">2023 – 2027</span>
      </div>
      <div>B.S. in Computer Science and Technology (Elite Program)</div>
      <p style="margin-top:16px; font-weight:600; font-size:0.95em; border-top:1px solid #ddd; padding-top:12px;">Selected Coursework:</p>
      <ul class="course-list">
        <li>Mathematical Analysis</li>
        <li>Data Structures</li>
        <li>Pattern Recognition</li>
        <li>Probability & Statistics</li>
      </ul>
    </div>
  </section>

</div>
