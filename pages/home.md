---
layout: base/home
title: Onan Agaba
subtitle: Graduate Student | Researcher
banner_image: /assets/images/Audi.jpg
permalink: /
---

<!-- Banner and nav styling to match UCR -->
<style>
/* Navigation bar style (place inside your main layout or _includes/header) */
.ucr-navbar {
  display: flex;
  background: #003470;
  padding: 1em 2.5em;
  font-weight: bold;
  font-size: 1.2em;
  gap: 2em;
}
.ucr-navbar a, .ucr-navbar .dropbtn {
  color: white;
  text-decoration: none;
  letter-spacing: 0.04em;
  font-weight: 700;
  text-transform: uppercase;
  padding: 0.2em 0.6em;
}
.ucr-navbar .dropdown {
  position: relative;
}
.ucr-navbar .dropdown-content {
  display: none;
  position: absolute;
  background: #003470;
  min-width: 160px;
  margin-top: 0.7em;
  z-index: 1000;
  box-shadow: 0 8px 16px rgba(0,0,0,0.15);
}
.ucr-navbar .dropdown:hover .dropdown-content {
  display: block;
}
.ucr-navbar .dropdown-content a {
  display: block;
  color: white;
  padding: 0.6em 1.2em;
  font-size: 1em;
}
.ucr-navbar .dropdown-content a:hover {
  background: #0D396F;
}
