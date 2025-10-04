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
/* CSS - add this to your main stylesheet or inside <style> tags */

.ucr-navbar {
  display: flex; 
  justify-content: left; 
  align-items: center;
  padding: 1em 2.5em;
  background: #003470;
  font-weight: bold;
  font-size: 1.2em;
  color: white;
}
.ucr-navbar a {
  color: white;
  text-decoration: none;
  margin-right: 2em;
  letter-spacing: 0.04em;
  font-weight: 700;
}

.banner-section {
  position: relative;
  width: 100%;
  height: 350px;
  background: url('/assets/images/Audi.jpg') center/cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
}
.banner-overlay {
  position: absolute; 
  top: 0; 
  left: 0; 
  width: 100%; 
  height: 100%;
  background: rgba(0, 52, 120, 0.5); /* Darker overlay for better contrast */
  z-index: 1;
}
.banner-content {
  position: relative;
  z-index: 2;
  text-align: center;
  color: white;
  padding: 0 2rem;
}
.banner-content h1 {
  font-size: 3em;
  font-weight: 700;
  margin-bottom: 0.3em;
  letter-spacing: 0.01em;
  text-shadow: 0 2px 8px rgba(0,0,0,0.3);
}
.banner-content h2 {
  font-size: 1.5em;
  font-weight: 500;
  margin-top: 0;
  opacity: 0.9;
}

.main-content {
  max-width: 700px;
  margin: 2em auto;
  padding: 1.5em 2.5em;
  background: white;
  color: #222;
  border-radius: 10px;
  box-shadow: 0 6px 20px rgba(0,0,0,0.06);
}
