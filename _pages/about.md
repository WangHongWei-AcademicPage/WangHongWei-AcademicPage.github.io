---
permalink: /
title: "Personal Information"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* 学术风格变量 */
:root {
  --academic-blue: #2c3e50;
  --academic-gold: #d4af37;
  --academic-light: #ecf0f1;
  --academic-dark: #34495e;
  --accent-color: #3498db;
}

/* 整体样式增强 */
.academic-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

/* 个人介绍卡片 */
.profile-card {
  background: linear-gradient(135deg, var(--academic-blue) 0%, var(--academic-dark) 100%);
  color: white;
  padding: 2.5rem;
  border-radius: 12px;
  margin-bottom: 2rem;
  box-shadow: 0 8px 32px rgba(0,0,0,0.1);
  position: relative;
  overflow: hidden;
}

.profile-card::before {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  width: 150px;
  height: 150px;
  background: radial-gradient(circle, var(--academic-gold) 0%, transparent 70%);
  opacity: 0.1;
}

.profile-header {
  display: flex;
  align-items: center;
  gap: 2rem;
  margin-bottom: 1.5rem;
}

.profile-content p {
  font-size: 1.1rem;
  line-height: 1.7;
  margin-bottom: 1rem;
  opacity: 0.95;
}

/* 教育经历时间线 */
.timeline {
  position: relative;
  padding-left: 2rem;
  margin: 2rem 0;
}

.timeline::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  width: 3px;
  background: linear-gradient(to bottom, var(--academic-gold), var(--accent-color));
}

.timeline-item {
  position: relative;
  margin-bottom: 2rem;
  padding: 1.5rem;
  background: var(--academic-light);
  border-radius: 8px;
  border-left: 4px solid var(--academic-gold);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.timeline-item:hover {
  transform: translateX(5px);
  box-shadow: 0 4px 16px rgba(0,0,0,0.1);
}

.timeline-item::before {
  content: "🎓";
  position: absolute;
  left: -2.5rem;
  top: 1.5rem;
  background: white;
  border-radius: 50%;
  width: 2rem;
  height: 2rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 0.8rem;
  border: 2px solid var(--academic-gold);
}

/* 文献表格增强 */
.publications-table {
  width: 100%;
  border-collapse: collapse;
  margin: 2rem 0;
  background: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 16px rgba(0,0,0,0.1);
}

.publications-table th {
  background: var(--academic-blue);
  color: white;
  padding: 1rem;
  text-align: left;
  font-weight: 600;
}

.publications-table td {
  padding: 1rem;
  border-bottom: 1px solid #eee;
}

.publications-table tr:hover {
  background: #f8f9fa;
  transition: background 0.3s ease;
}

.publications-table a {
  color: var(--accent-color);
  text-decoration: none;
  font-weight: 500;
}

.publications-table a:hover {
  text-decoration: underline;
}

/* 学术经历卡片 */
.experience-card {
  background: white;
  border-radius: 8px;
  padding: 1.5rem;
  margin-bottom: 1.5rem;
  border-left: 4px solid var(--academic-gold);
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
}

.experience-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 16px rgba(0,0,0,0.15);
}

.experience-header {
  display: flex;
  justify-content: between;
  align-items: flex-start;
  margin-bottom: 1rem;
}

.experience-title {
  color: var(--academic-blue);
  margin: 0;
  flex: 1;
}

.experience-date {
  color: #666;
  font-style: italic;
}

.experience-advisor {
  color: var(--academic-dark);
  font-weight: 500;
  margin-bottom: 0.5rem;
}

/* 联系信息样式 */
.contact-info {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
  margin: 1rem 0;
}

.contact-email {
  background: var(--academic-light);
  padding: 0.5rem 1rem;
  border-radius: 20px;
  text-decoration: none;
  color: var(--academic-blue);
  border: 1px solid #ddd;
  transition: all 0.3s ease;
}

.contact-email:hover {
  background: var(--accent-color);
  color: white;
  transform: translateY(-1px);
}

/* 响应式设计 */
@media (max-width: 768px) {
  .profile-header {
    flex-direction: column;
    text-align: center;
  }
  
  .publications-table {
    font-size: 0.9rem;
  }
  
  .experience-header {
    flex-direction: column;
  }
}
</style>

<div class="academic-container">
  <!-- 个人介绍部分 -->
  <div class="profile-card">
    <div class="profile-content">
      <p>I'm a year 4 undergraduate student from <a href="https://www.xjtlu.edu.cn/zh/study/departments/school-of-mathematics-and-physics" style="color: var(--academic-gold);">School of Mathematics and Physics</a>, <a href="https://www.xjtlu.edu.cn/" style="color: var(--academic-gold);">Xi'an Jiaotong-Liverpool University (XJTLU)</a>.</p>

      <p>As a pure mathematics student, I focus on Algebraic Topology and Homotopy Theory, with extending interests in Homotopy Type Theory and formal verification of mathematics using the Lean Theorem Prover.</p>

      <p>You can find my CV here: <a href="../assets/CV.pdf" style="color: var(--academic-gold); font-weight: 600;">Hongwei.Wang CV, 11/09/25 updated</a>. The attached document is a reverse-chronological summary of my study. You can also read the content in this website for a detailed narrative of my study and experiences.</p>

      <p>On this website, you can explore my undergraduate works, academic talks, teaching experience and academic portfolio via the links in the navigation bar above. If my academic pursuits align with your interests, please feel free to contact me:</p>
      
      <div class="contact-info">
        <a href="mailto:1972396871@qq.com" class="contact-email">1972396871@qq.com</a>
        <a href="mailto:Hongwei.wang22@student.xjtlu.edu.cn" class="contact-email">Hongwei.wang22@student.xjtlu.edu.cn</a>
      </div>
    </div>
  </div>

  <!-- 教育经历 -->
  <h2>Education</h2>
  <div class="timeline">
    <div class="timeline-item">
      <strong>B.Sc. in Mathematics and Applied Mathematics (09/2022 - Expected 06/2026)</strong><br>
      School of Mathematics and Physics, Xi'an Jiaotong-Liverpool University (XJTLU), Suzhou, China
    </div>
    <div class="timeline-item">
      <strong>Visiting Scholar in Westlake University (09/2025 - Expected 03/2026)</strong><br>
      Prof. GU Xing's Group, Institute for Theoretical Sciences, Westlake University, Hangzhou, China
    </div>
  </div>

  <!-- 文献著作 -->
  <h2>Expository Writings</h2>
  <p><em>(See detailed information in the <a href="/writings">Writings</a> section)</em></p>
  
  <table class="publications-table">
    <thead>
      <tr>
        <th>Title</th>
        <th>Date</th>
        <th>Link</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>Categorical Algebra and Homotopy Theory</strong></td>
        <td>In Progress</td>
        <td><a href="../assets/categorical_algebra_homotopy_theory.pdf">[PDF]</a></td>
      </tr>
      <tr>
        <td><strong>An Upper Bound for the Hausdorff Dimension of Fractals under Symmetry Group Action</strong></td>
        <td>May 2025</td>
        <td><a href="../assets/Hausdorff_dimension.pdf">[PDF]</a></td>
      </tr>
      <tr>
        <td><strong>AI-Driven Python Code Generation for Solving Specific Mathematics Problems</strong></td>
        <td>Apr 2025</td>
        <td><a href="../assets/Ai_Driven_Code.pdf">[PDF]</a></td>
      </tr>
      <tr>
        <td><strong>The Futurama Theorem: Group Theory and Permutations in a Body-Swapping Problem</strong></td>
        <td>Mar 2025</td>
        <td><a href="../assets/Futurama.pdf">[PDF]</a></td>
      </tr>
      <tr>
        <td><strong>Introduction to Commutative Algebra: Rings and Ideals</strong></td>
        <td>Aug 2024</td>
        <td><a href="../assets/Introduction_to_Rings_Ideals.pdf">[PDF]</a></td>
      </tr>
      <tr>
        <td><strong>Poster of Visualizing The Distribution of Prime Numbers</strong></td>
        <td>Aug 2024</td>
        <td><a href="../assets/main.pdf">[PDF]</a></td>
      </tr>
      <tr>
        <td><strong>Arithmetical Functions and Elementary Theorems on the Distribution of Primes</strong></td>
        <td>July 2024</td>
        <td><a href="../assets/Arithmatical_Functions.pdf">[PDF]</a></td>
      </tr>
    </tbody>
  </table>

  <!-- 学术经历 -->
  <h2>Academic Experience</h2>
  
  <div class="experience-card">
    <div class="experience-header">
      <h3 class="experience-title">Categorical Algebra & Homotopy Theory</h3>
    </div>
    <div class="experience-advisor">Xi'an Jiaotong-Liverpool University (09/2025 - Expected 06/2026) | Advisor: Prof. Alastair Darby</div>
    <ul>
      <li>Conducted systematic study of algebraic topology and homotopy theory, developing understanding of fundamental groups, groupoids, covering spaces, and simplicial homology</li>
      <li>Explored connections between category theory and algebraic topology, examining equivalence between van Kampen theorem and groupoid formulations</li>
      <li>Investigated categorical approaches to Galois theory of covering spaces, analyzing connections between topological and algebraic structures</li>
      <li>Studied dependent type theory and used <strong>Lean</strong> theorem prover to formalize fundamental theorems, completing verification of π₁(S¹) ≅ ℤ</li>
    </ul>
  </div>

  <!-- 其他经历卡片保持相同结构 -->
  <div class="experience-card">
    <div class="experience-header">
      <h3 class="experience-title">Visiting Scholar in Algebraic Topology</h3>
    </div>
    <div class="experience-advisor">Westlake University (09/2025 - Expected 03/2026) | Advisor: Prof. Xing Gu</div>
    <ul>
      <li>Attended graduate-level algebraic topology seminars weekly, deepening understanding of advanced topics</li>
      <li>Studied basic homotopy theory under supervision, conducting undergraduate thesis work</li>
      <li>Engaged in self-directed study of modern algebraic topology using Haynes Miller's lectures</li>
      <li>Examined simplicial homology theory and homotopy theory, focusing on categorical interpretations</li>
    </ul>
  </div>

  <!-- 继续其他经历部分... -->
  <!-- 为节省篇幅，这里省略了其他经历的重复代码，您只需要保持相同的卡片结构即可 -->

</div>

<script>
// 简单的交互效果
document.addEventListener('DOMContentLoaded', function() {
  // 为时间线项目添加动画
  const timelineItems = document.querySelectorAll('.timeline-item');
  timelineItems.forEach((item, index) => {
    item.style.opacity = '0';
    item.style.transform = 'translateX(-20px)';
    
    setTimeout(() => {
      item.style.transition = 'all 0.6s ease';
      item.style.opacity = '1';
      item.style.transform = 'translateX(0)';
    }, index * 200);
  });

  // 表格行悬停效果
  const tableRows = document.querySelectorAll('.publications-table tr');
  tableRows.forEach(row => {
    row.addEventListener('mouseenter', function() {
      this.style.backgroundColor = '#f8f9fa';
    });
    row.addEventListener('mouseleave', function() {
      this.style.backgroundColor = '';
    });
  });
});
</script>
