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
/* assets/css/main.css or a custom CSS file */
.navbar {
  display: flex; justify-content: space-between; align-items: center;
  background: #0047AB; color: white; padding: 1em 2em;
  font-weight: bold; font-size: 1.2em;
}
.navbar a { color: white; text-decoration: none; margin-right: 2em; }
.navbar .nav-right { float: right; }

.ucr-banner {
  position: relative;
  height: 380px;
  background: url('/assets/img/your-bg.jpg') center/cover no-repeat;
  display: flex; align-items: center; justify-content: center;
}
.ucr-overlay {
  position: absolute; top: 0; left: 0; width: 100%; height: 100%;
  background: rgba(0, 50, 150, 0.35);
}
.ucr-content {
  position: relative; z-index: 1; color: white; text-align: center;
}
.ucr-content h1 {
  font-size: 3em; font-weight: bold; letter-spacing: 0.02em;
  text-shadow: 0 2px 8px rgba(0,0,0,0.3);
  line-height: 1.1;
}
/* Add yellow underline/highlight as needed */
