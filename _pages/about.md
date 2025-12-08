---
permalink: /
title: "Personal Information"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.academic-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.profile-content {
  margin-bottom: 3rem;
}

.profile-content p {
  font-size: 1.1rem;
  line-height: 1.7;
  margin-bottom: 1.5rem;
}

.contact-info {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
  margin: 1.5rem 0;
}

.contact-email {
  background: #f8f9fa;
  padding: 0.6rem 1.2rem;
  border-radius: 6px;
  text-decoration: none;
  color: #2c3e50;
  border: 1px solid #dee2e6;
  transition: all 0.3s ease;
  font-weight: 500;
}

.contact-email:hover {
  background: #3498db;
  color: white;
  border-color: #3498db;
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(52, 152, 219, 0.3);
}

.timeline {
  position: relative;
  padding-left: 2rem;
  margin: 2rem 0;
}

.timeline::before {
  content: "";
  position: absolute;
  left: 7px;
  top: 0;
  bottom: 0;
  width: 2px;
  background: linear-gradient(to bottom, #d4af37, #3498db);
}

.timeline-item {
  position: relative;
  margin-bottom: 2rem;
  padding: 1.5rem;
  background: #f8f9fa;
  border-radius: 8px;
  border-left: 4px solid #d4af37;
  transition: all 0.3s ease;
}

.timeline-item:hover {
  transform: translateX(5px);
  box-shadow: 0 4px 16px rgba(0,0,0,0.1);
}

.timeline-item::before {
  content: "🎓";
  position: absolute;
  left: -2.3rem;
  top: 1.5rem;
  background: white;
  border-radius: 50%;
  width: 1.8rem;
  height: 1.8rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 0.7rem;
  border: 2px solid #d4af37;
  z-index: 2;
}

.publications-table {
  width: 100%;
  border-collapse: collapse;
  margin: 2rem 0;
  background: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 16px rgba(0,0,0,0.08);
  border: 1px solid #e9ecef;
}

.publications-table th {
  background: #2c3e50;
  color: white;
  padding: 1.2rem 1rem;
  text-align: left;
  font-weight: 600;
  font-size: 1rem;
}

.publications-table td {
  padding: 1.2rem 1rem;
  border-bottom: 1px solid #e9ecef;
  transition: background-color 0.2s ease;
}

.publications-table tr:last-child td {
  border-bottom: none;
}

.publications-table tr:hover td {
  background: #f8f9fa;
}

.publications-table a {
  color: #3498db;
  text-decoration: none;
  font-weight: 500;
  padding: 0.3rem 0.8rem;
  border-radius: 4px;
  transition: all 0.2s ease;
}

.publications-table a:hover {
  background: #3498db;
  color: white;
  text-decoration: none;
}

.experience-card {
  background: white;
  border-radius: 8px;
  padding: 1.8rem;
  margin-bottom: 1.8rem;
  border-left: 4px solid #d4af37;
  box-shadow: 0 2px 12px rgba(0,0,0,0.06);
  border: 1px solid #e9ecef;
  transition: all 0.3s ease;
}

.experience-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 20px rgba(0,0,0,0.12);
}

.experience-header {
  margin-bottom: 1rem;
}

.experience-title {
  color: #2c3e50;
  margin: 0 0 0.5rem 0;
  font-size: 1.3rem;
  font-weight: 600;
}

.experience-advisor {
  color: #495057;
  font-weight: 500;
  margin-bottom: 0.8rem;
  font-style: italic;
}

.experience-card ul {
  margin: 0;
  padding-left: 1.2rem;
}

.experience-card li {
  margin-bottom: 0.5rem;
  line-height: 1.6;
  color: #495057;
}

.experience-card li:last-child {
  margin-bottom: 0;
}

.section-title {
  color: #2c3e50;
  border-bottom: 2px solid #d4af37;
  padding-bottom: 0.5rem;
  margin: 3rem 0 1.5rem 0;
  font-weight: 600;
}

.section-title:first-of-type {
  margin-top: 2rem;
}

@media (max-width: 768px) {
  .academic-container {
    padding: 0 15px;
  }
  
  .profile-content p {
    font-size: 1rem;
  }
  
  .contact-info {
    flex-direction: column;
    gap: 0.8rem;
  }
  
  .contact-email {
    text-align: center;
  }
  
  .timeline {
    padding-left: 1.5rem;
  }
  
  .timeline-item::before {
    left: -1.8rem;
  }
  
  .publications-table {
    font-size: 0.9rem;
  }
  
  .publications-table th,
  .publications-table td {
    padding: 0.8rem 0.6rem;
  }
  
  .experience-card {
    padding: 1.2rem;
  }
  
  .experience-title {
    font-size: 1.1rem;
  }
}

.fade-in {
  opacity: 0;
  transform: translateY(20px);
  transition: all 0.6s ease;
}

.fade-in.visible {
  opacity: 1;
  transform: translateY(0);
}
</style>

<div class="academic-container">
  <div class="profile-content">
<p>I'm a year 4 undergraduate student from <a href="https://www.xjtlu.edu.cn/zh/study/departments/school-of-mathematics-and-physics">School of Mathematics and Physics</a>, <a href="https://www.xjtlu.edu.cn/">Xi'an Jiaotong-Liverpool University(XJTLU)</a>.</p>

<p>As a <strong>pure mathematics</strong> student, I focus on <strong>Algebraic Topology and Homotopy Theory</strong>, with extending interests in <strong>Homotopy Type Theory</strong> and formal verification of mathematics using the <strong>Lean Theorem Prover</strong>.</p>

<p>You can find my CV here: <a href="../assets/CV.pdf"><strong>Hongwei.Wang CV, 11/09/25 updated</strong></a>. The attached document is a <strong>reverse-chronological summary</strong> of my study. You can also read the content in this website for a <strong>detailed narrative</strong> of my study and experiences.</p>

<p>On this website, you can explore my <strong>undergraduate works</strong>, <strong>academic talks</strong>, <strong>teaching experience</strong> and my <strong>pure math exploration journey</strong> via the links in the navigation bar above. If my academic pursuits align with your interests, please feel free to contact me:</p>
    <div class="contact-info">
      <a href="mailto:1972396871@qq.com" class="contact-email">1972396871@qq.com</a>
      <a href="mailto:Hongwei.wang22@student.xjtlu.edu.cn" class="contact-email">Hongwei.wang22@student.xjtlu.edu.cn</a>
    </div>
  </div>

<h2 class="section-title">Education</h2>
<div class="timeline" style="--timeline-color: #2c3e50;">
  <div class="timeline-item fade-in" onclick="window.open('https://www.xjtlu.edu.cn/zh/study/departments/school-of-mathematics-and-physics', '_blank')" style="cursor: pointer; border-left-color: #2c3e50;">
    <strong>B.Sc. in Mathematics and Applied Mathematics (09/2022 - Expected 06/2026)</strong><br>
    School of Mathematics and Physics, Xi'an Jiaotong-Liverpool University (XJTLU), Suzhou, China
    <div style="margin-top: 8px; font-size: 0.9em; color: #3498db;">
      → Click to visit XJTLU School of Mathematics and Physics
    </div>
  </div>
  <div class="timeline-item fade-in" onclick="window.open('https://its.westlake.edu.cn', '_blank')" style="cursor: pointer; border-left-color: #2c3e50;">
    <strong>Visiting Scholar in Westlake University (09/2025 - Expected 03/2026)</strong><br>
    Prof. Gu Xing's Group, Institute for Theoretical Sciences, Westlake University, Hangzhou, China
    <div style="margin-top: 8px; font-size: 0.9em; color: #3498db;">
      → Click to visit Westlake University Institute for Theoretical Sciences
    </div>
  </div>
</div>

<style>
.timeline::before {
  background: linear-gradient(to bottom, var(--timeline-color, #2c3e50), var(--timeline-color, #2c3e50)) !important;
}

.timeline-item::before {
  border: 2px solid #2c3e50 !important;
}
</style>

  <h2 class="section-title">Expository Writings</h2>
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
       <tr class="fade-in">
        <td><strong>A Unifying Framework of Galois Connections: From Adjoint Functors to Galois Theory and Topological Covering Spaces</strong></td>
        <td>Dec 2025</td>
        <td><a href="../assets/Galois_Connection.pdf">[PDF]</a></td>
      </tr>
      <tr class="fade-in">
        <td><strong>Categorical Algebra and Homotopy Theory (The Homotopic Interpretation of Mathematical Proofs: a Categorical and Type-Theoretic Study of Structural Equivalence)</strong></td>
        <td>In Progress</td>
        <td><a href="../assets/categorical_algebra_1208.pdf">[PDF]</a></td>
      </tr>
      <tr class="fade-in">
        <td><strong>An Upper Bound for the Hausdorff Dimension of Fractals under Symmetry Group Action</strong></td>
        <td>May 2025</td>
        <td><a href="../assets/Hausdorff_dimension.pdf">[PDF]</a></td>
      </tr>
      <tr class="fade-in">
        <td><strong>AI-Driven Python Code Generation for Solving Specific Mathematics Problems</strong></td>
        <td>Apr 2025</td>
        <td><a href="../assets/Ai_Driven_Code.pdf">[PDF]</a></td>
      </tr>
      <tr class="fade-in">
        <td><strong>The Futurama Theorem: Group Theory and Permutations in a Body-Swapping Problem</strong></td>
        <td>Mar 2025</td>
        <td><a href="../assets/Futurama.pdf">[PDF]</a></td>
      </tr>
      <tr class="fade-in">
        <td><strong>Introduction to Commutative Algebra: Rings and Ideals</strong></td>
        <td>Aug 2024</td>
        <td><a href="../assets/Introduction_to_Rings_Ideals.pdf">[PDF]</a></td>
      </tr>
      <tr class="fade-in">
        <td><strong>Poster of Visualizing The Distribution of Prime Numbers</strong></td>
        <td>Aug 2024</td>
        <td><a href="../assets/poster_prime.pdf">[PDF]</a></td>
      </tr>
      <tr class="fade-in">
        <td><strong>Arithmetical Functions and Elementary Theorems on the Distribution of Primes</strong></td>
        <td>July 2024</td>
        <td><a href="../assets/Arithmatical_Functions.pdf">[PDF]</a></td>
      </tr>
    </tbody>
  </table>

  <h2 class="section-title">Academic Experience</h2>
  
  <div class="experience-card fade-in">
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

  <div class="experience-card fade-in">
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

  <div class="experience-card fade-in">
    <div class="experience-header">
      <h3 class="experience-title">Global Mathematics Students' Summer School</h3>
    </div>
    <div class="experience-advisor">Westlake University (06/2025 - 07/2025) | Organizer: Prof. Huayi Chen</div>
    <ul>
      <li>Participated in intensive summer program with daily mathematics discussion sessions</li>
      <li>Studied fundamental structures across multiple fields: <strong>information geometry</strong>, <strong>algebraic geometry</strong>, <strong>algebraic number theory</strong>, <strong>elliptic PDE regularity theory</strong>, and <strong>modular forms</strong></li>
      <li>Organized core theorems and proof techniques for each topic, creating comprehensive study notes</li>
      <li>Developed cross-disciplinary mathematical framework through systematic summarization</li>
    </ul>
  </div>

  <div class="experience-card fade-in">
    <div class="experience-header">
      <h3 class="experience-title">Undergraduate Category Theory Seminar</h3>
    </div>
    <div class="experience-advisor">Xi'an Jiaotong-Liverpool University (02/2025 - 05/2025) | Organizer: Prof. Adam-Chrisiaan von</div>
    <ul>
      <li>Mastered category theory fundamentals: categories, functors, natural transformations, limits, representable functors, and Yoneda lemma</li>
      <li>Delivered special lecture on representable functors and Yoneda lemma as student lecturer</li>
      <li>Explained abstract categorical constructions using concrete examples from algebra and topology</li>
      <li>Illustrated concepts through set representations, group actions, and category of presheaves</li>
    </ul>
  </div>

  <div class="experience-card fade-in">
    <div class="experience-header">
      <h3 class="experience-title">XJTLU Winter Pure Math Seminar <a href="../assets/seminar.pdf">[poster]</a></h3>
    </div>
    <div class="experience-advisor">Xi'an Jiaotong-Liverpool University (12/2024 - 01/2025) | Organizer: Stud. Hongwei Wang</div>
    <ul>
      <li>Independently sourced guest lecturers, orchestrated the seminar schedule and topics, and designed promotional posters, subsequently securing official endorsement from the School.</li>
      <li>Delivered an in-depth lecture on Galois theory, guiding the audience from its historical origins in solving polynomial equations to its profound conclusion: the unsolvability of the quintic by radicals. The talk meticulously detailed the construction of the Galois group for a polynomial and explained the fundamental Galois correspondence between subfields of a field extension and subgroups of its Galois group.</li>
      <li>Seminar included functional analysis, measure theory, and topology, etc. The program also featured specialized sessions on spectral graph theory and another advanced topic. All session recordings were uploaded to social media platforms, where they garnered significant positive feedback and extensive viewership.</li>
    </ul>
  </div>

  <div class="experience-card fade-in">
    <div class="experience-header">
      <h3 class="experience-title">Analytic Number Theory Study</h3>
    </div>
    <div class="experience-advisor">Xi'an Jiaotong-Liverpool University (06/2024 - 09/2024) | Advisor: Prof. Pietro Sgobba</div>
    <ul>
      <li>Studied Tom M. Apostol's <em>Introduction to Analytic Number Theory</em>, mastering arithmetical functions and Chebyshev estimates</li>
      <li>Learned elementary forms of Prime Number Theorem through guided study</li>
      <li>Wrote review paper <em>"Arithmetical Functions and Elementary Theorems on the Distribution of Primes"</em></li>
      <li>Programmed <strong>Python</strong> visualizations generating prime number spirals (Ulam, Klauber, Sacks)</li>
      <li>Investigated properties of prime-rich polynomials through computational analysis</li>
    </ul>
  </div>

  <h2 class="section-title">Academic Projects</h2>

  <div class="experience-card fade-in">
    <div class="experience-header">
      <h3 class="experience-title">AI in Mathematics Learning Workshop</h3>
    </div>
    <div class="experience-advisor">Xi'an Jiaotong-Liverpool University (10/2024 - 04/2025) | Advisor: Prof. Jinsong Xu</div>
    <ul>
      <li>Designed and coordinated six-month study applying generative programming to pure mathematics</li>
      <li>Developed interactive learning tools for <strong>complex analysis</strong>, <strong>abstract algebra</strong>, and <strong>topology</strong></li>
      <li>Created machine-learning analysis of Ramsey's Theorem case on K₅ through computer self-play optimization</li>
      <li>Built visualization tool for conformal mappings with automatic singularity detection</li>
      <li>Programmed scalar field visualization with automatic gradient computation and plotting</li>
      <li>Presented findings in report <em>"AI-Driven Python Code Generation for Solving Specific Mathematics Problems"</em></li>
    </ul>
  </div>

  <div class="experience-card fade-in">
    <div class="experience-header">
      <h3 class="experience-title">Stellar Cluster Analysis Project</h3>
    </div>
    <div class="experience-advisor">Xi'an Jiaotong-Liverpool University (10/2022 - 06/2023) | Advisor: Prof. Xiaoying Pang</div>
    <ul>
      <li>Processed <strong>Gaia DR3</strong> star catalog data using <strong>Python</strong> for cleaning and dimensionality reduction</li>
      <li>Applied <strong>Gaussian Mixture Model (GMM)</strong> to identify member stars of Beehive Cluster</li>
      <li>Identified 387 high-confidence member stars (confidence > 90%) through statistical analysis</li>
      <li>Produced color-magnitude diagram (CMD) for stellar population analysis</li>
      <li>Implemented <strong>Self-Organizing Map (SOM)</strong> for unsupervised clustering of stellar data</li>
    </ul>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const fadeElements = document.querySelectorAll('.fade-in');
  
  const fadeObserver = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, { threshold: 0.1 });
  
  fadeElements.forEach(element => {
    fadeObserver.observe(element);
  });
  
  const tableRows = document.querySelectorAll('.publications-table tr');
  tableRows.forEach((row, index) => {
    row.style.transitionDelay = `${index * 0.05}s`;
  });
});
</script>
