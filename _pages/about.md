---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
* { box-sizing: border-box; }

.home-wrapper {
  max-width: 680px;
  margin: 0 auto;
  padding: 2rem 1rem;
  text-align: center;
  font-family: inherit;
}

.home-photo {
  width: 130px;
  height: 130px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1.2rem;
}

.home-name {
  font-size: 1.8rem;
  font-weight: 700;
  color: #222;
  margin: 0 0 0.4rem 0;
}

.home-bio {
  font-size: 1rem;
  color: #666;
  font-style: italic;
  margin: 0 0 1.4rem 0;
  line-height: 1.6;
}

.home-social {
  display: flex;
  justify-content: center;
  gap: 1.2rem;
  margin-bottom: 2.5rem;
  flex-wrap: wrap;
}

.home-social a {
  color: #555;
  font-size: 0.88rem;
  text-decoration: none;
  display: flex;
  align-items: center;
  gap: 0.3rem;
  transition: color 0.2s;
}

.home-social a:hover {
  color: #222;
  text-decoration: none;
}

.divider {
  border: none;
  border-top: 1px solid #e0e0e0;
  margin: 0 auto 2.5rem auto;
  width: 60%;
}

.topic-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 0.9rem;
  justify-content: center;
  margin-bottom: 0.9rem;
}

.topic-btn {
  display: inline-block;
  padding: 0.7rem 1.4rem;
  border: 1.5px solid #333;
  border-radius: 6px;
  color: #333;
  font-size: 0.92rem;
  font-weight: 600;
  text-decoration: none !important;
  transition: background 0.2s, color 0.2s;
  min-width: 190px;
  background: transparent;
}

.topic-btn:hover {
  background: #333;
  color: #fff;
  text-decoration: none !important;
}

.about-btn {
  display: inline-block;
  margin-top: 0.8rem;
  padding: 0.65rem 2.2rem;
  border: 1.5px solid #888;
  border-radius: 6px;
  color: #555;
  font-size: 0.88rem;
  font-weight: 500;
  text-decoration: none !important;
  transition: background 0.2s, color 0.2s;
  background: transparent;
}

.about-btn:hover {
  background: #555;
  color: #fff;
  text-decoration: none !important;
}
</style>

<div class="home-wrapper">

  <img src="/images/profile.jpeg" alt="Jonathan David Barrantes Segovia" class="home-photo">

  <h1 class="home-name">Jonathan David Barrantes Segovia</h1>

  <p class="home-bio">
    Exploring computation, physics, and philosophy<br>through original research and theoretical work.
  </p>

  <div class="home-social">
    <a href="mailto:tu@email.com">✉ Email</a>
    <a href="https://github.com/tuusuario">GitHub</a>
    <a href="https://instagram.com/tuusuario">Instagram</a>
    <a href="https://twitter.com/tuusuario">X</a>
  </div>

  <hr class="divider">

  <div class="topic-buttons">
    <a href="/publications/" class="topic-btn">Computer Science</a>
    <a href="/talks/" class="topic-btn">Physics</a>
    <a href="/writing/" class="topic-btn">Philosophy & Politics</a>
  </div>

  <a href="/cv/" class="about-btn">About Me</a>

</div>
