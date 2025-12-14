---
layout: default
title: Home
---

<div class="home-intro">
  <div class="profile-section">
    <img src="/assets/images/profile.jpg" alt="Leman" class="profile-photo">
  </div>
  <div class="intro-section">
    <h1>Hi, I'm Leman</h1>
    <p>My name is Leman, I am a first-year student at ADA University. I am interested in technology, programming, and web development. I enjoy learning new tools, working on small projects, and improving my skills. This portfolio website is part of my SITE 1101 course project.</p>
  </div>
</div>

<section class="around-web">
  <h2 class="section-title">Around the Web</h2>
  
  <div class="link-section">
    <h3 class="link-section-title">Learning</h3>
    <ul class="link-list">
      <li>
        <a href="https://www.codecademy.com/profiles/LamanSafaraliyeva" target="_blank" rel="noopener noreferrer" class="external-link">
          <svg class="link-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path>
            <polyline points="15 3 21 3 21 9"></polyline>
            <line x1="10" y1="14" x2="21" y2="3"></line>
          </svg>
          Codecademy
        </a>
      </li>
    </ul>
  </div>

  <div class="link-section">
    <h3 class="link-section-title">Code</h3>
    <ul class="link-list">
      <li>
        <a href="https://github.com/Lamansafaraliyeva" target="_blank" rel="noopener noreferrer" class="external-link">
          <svg class="link-icon" viewBox="0 0 24 24" fill="currentColor">
            <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
          </svg>
          GitHub
        </a>
      </li>
    </ul>
  </div>
</section>

<style>
.home-intro {
  display: flex;
  align-items: center;
  gap: 3rem;
  margin-bottom: 4rem;
  flex-wrap: wrap;
}

.profile-section {
  flex-shrink: 0;
}

.profile-photo {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #e0e0e0;
}

.intro-section {
  flex: 1;
  min-width: 300px;
}

.intro-section h1 {
  font-size: 2rem;
  font-weight: 600;
  margin-bottom: 1rem;
  color: #333;
}

.intro-section p {
  font-size: 1.1rem;
  line-height: 1.8;
  color: #666;
}

@media (max-width: 768px) {
  .home-intro {
    flex-direction: column;
    text-align: center;
    gap: 2rem;
  }

  .profile-photo {
    width: 150px;
    height: 150px;
  }

  .intro-section {
    min-width: 100%;
  }
}
</style>
