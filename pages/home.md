---
layout: base/home
title: Onan Agaba
subtitle: Graduate Student | Researcher
banner_image: /assets/images/Audi.jpg
permalink: /
---

<style>
  h1 {
    font-size: 2.5rem;
    margin-bottom: 0.2rem;
    font-weight: 700;
  }
  h2.subtitle {
    font-size: 1.25rem;
    color: #444;
    margin-top: 0;
    margin-bottom: 2rem;
  }
  section {
    margin: 3rem 0;
  }
  mark {
    color: rgb(200,0,0);
    background-color: white;
  }
  img.full-width {
    width: 100%;
    height: auto;
    margin-bottom: 2rem;
    border-radius: 0.3rem;
  }
  p {
    font-size: 1.1rem;
    line-height: 1.5;
  }
</style>

<h1>{{ page.title }}</h1>
<h2 class="subtitle">{{ page.subtitle }}</h2>

<img src="{{ page.banner_image | relative_url }}" alt="Banner Image" class="full-width" />

<p>Welcome to Agaba's Website. Here is some information about me and what I do.</p>

<section>
  <h2>About Me</h2>
  <p>Section text, add an image, whatever you'd like. See
  <a href="https://www.markdownguide.org/basic-syntax/" target="_blank">Markdown Guide</a>
  for how to write page content in markdown (it's easy!).</p>

  <img src="{{ 'assets/images/chemical-reaction-science-chemistry.jpg' | relative_url }}" alt="Glassware" style="max-width: 600px; width: 100%; border-radius: 0.2rem;" />
</section>
