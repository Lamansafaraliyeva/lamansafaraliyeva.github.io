---
layout: default
title: Projects
permalink: /projects/
---

<div class="projects-page">
  <h1>Projects</h1>
  
  <div class="projects-list">
    
    <article class="project-item">
      <div class="project-image">
        <img src="/assets/images/project1.jpg" alt="How Does Hardware Work?">
      </div>
      <div class="project-content">
        <h2>How Does Hardware Work?</h2>
        <p>Project 1 was a hands-on assignment for our SITE1101 course, designed to explore the fundamentals of digital electronics and logic gate design. Our team, Group 50, consisted of four members who collaborated to design and implement basic logic gates — AND, OR, NOT, NAND, and XOR — in the laboratory.</p>
        <p>Throughout the project, we gained practical experience in understanding how hardware components process information and interact to perform logical operations. Our team worked closely with other outstanding teams — 38, 46, 77, and 83 — exchanging ideas and troubleshooting challenges to ensure the successful completion of the project. This project enhanced our understanding of the building blocks of digital systems and strengthened our skills in teamwork and experimental design.</p>
      </div>
    </article>

    <article class="project-item">
      <div class="project-image">
        <img src="/assets/images/project2.jpg" alt="Hour of Code">
      </div>
      <div class="project-content">
        <h2>Hour of Code</h2>
        <p>Hour of Code is a global movement introducing millions of students to computer science through one-hour coding activities. As part of this initiative, I participated in various coding challenges and tutorials designed to make programming accessible and engaging for beginners.</p>
        <p>Through this project, I explored fundamental programming concepts, problem-solving techniques, and logical thinking. The Hour of Code experience helped me develop a stronger foundation in computational thinking and sparked my interest in pursuing further studies in technology and programming.</p>
      </div>
    </article>

  </div>
</div>

<style>
.projects-page {
  max-width: 800px;
  margin: 0 auto;
}

.projects-page h1 {
  font-size: 2.5rem;
  font-weight: 600;
  margin-bottom: 3rem;
  color: #333;
  text-align: center;
}

.projects-list {
  display: flex;
  flex-direction: column;
  gap: 4rem;
}

.project-item {
  display: flex;
  gap: 2rem;
  align-items: flex-start;
  padding-bottom: 3rem;
  border-bottom: 1px solid #e0e0e0;
}

.project-item:last-child {
  border-bottom: none;
  padding-bottom: 0;
}

.project-image {
  flex-shrink: 0;
  width: 250px;
}

.project-image img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  border: 1px solid #e0e0e0;
  object-fit: cover;
}

.project-content {
  flex: 1;
}

.project-content h2 {
  font-size: 1.75rem;
  font-weight: 600;
  margin-bottom: 1rem;
  color: #333;
}

.project-content p {
  font-size: 1rem;
  line-height: 1.8;
  color: #666;
  margin-bottom: 1rem;
}

.project-content p:last-child {
  margin-bottom: 0;
}

@media (max-width: 768px) {
  .projects-page h1 {
    font-size: 2rem;
    margin-bottom: 2rem;
  }

  .project-item {
    flex-direction: column;
    gap: 1.5rem;
    padding-bottom: 2rem;
  }

  .project-image {
    width: 100%;
  }

  .project-content h2 {
    font-size: 1.5rem;
  }
}
</style>
