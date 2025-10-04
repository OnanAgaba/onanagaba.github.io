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
  width: 100%;
  display: flex;
  justify-content: left;
  align-items: center;
  padding: 1.0em 2.5em 1.0em 2.5em;
  background: #003470;
  font-weight: bold;
  font-size: 1.2em;
}
.ucr-navbar a {
  color: white;
  text-decoration: none;
  margin-right: 2em;
  letter-spacing: 0.03em;
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
  position: absolute; top: 0; left: 0; width: 100%; height: 100%;
  background: rgba(0, 50, 150, 0.35);
}
.banner-content {
  position: relative;
  z-index: 2;
  color: white;
  text-align: center;
}
.banner-content h1 {
  font-size: 2.8em;
  font-weight: bold;
  letter-spacing: 0.01em;
  margin-bottom: 0.3em;
  text-shadow: 0 2px 8px rgba(0,0,0,0.2);
}
.banner-content h2 {
  font-size: 1.4em;
  font-weight: 500;
  margin-top: 0;
  opacity: 0.95;
}
.main-content {
  max-width: 730px;
  margin: 3em auto 0 auto;
  padding: 1.2em 2.5em;
  background: white;
  color: #222;
  border-radius: 12px;
  box-shadow: 0 6px 32px rgba(0,0,0,0.07);
}
</style>

<!-- Navbar (edit links as needed) -->
<div class="ucr-navbar">
  <a href="/">HOME</a>
  <a href="#">PROJECTS</a>
  <a href="#">PUBLICATIONS</a>
  <a href="#">NEWS</a>
  <a href="#">MORE</a>
</div>

<!-- Banner section -->
<section class="banner-section">
  <div class="banner-overlay"></div>
  <div class="banner-content">
    <h1>{{ page.title }}</h1>
    <h2>{{ page.subtitle }}</h2>
  </div>
</section>

<!-- Main content block -->
<div class="main-content">
  Welcome to Agaba's Website.<br>
  Here is some information about me and and what I do.

  ### About Me

  Section text, add an image, whatever you'd like.<br>
  See <a href="https://www.markdownguide.org/basic-syntax/">markdown syntax guide</a> for how to write page content in markdown (it's easy!).

  <br><br>
  ![Glassware]({{ "assets/images/chemical-reaction-science-chemistry.jpg" | relative_url }})
</div>
