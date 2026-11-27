---
title: "Auditory Intelligence Lab - Projects"
layout: textlay
excerpt: "Research Projects"
sitemap: false
permalink: /projects/
---

<div class="projects-page" markdown="0">

  <h1>Projects</h1>


  <!-- Ongoing Projects -->

  <section class="projects-section">

    <h2 class="section-title">Ongoing Projects</h2>

    <div class="ongoing-projects">

      {% for project in site.data.projects.ongoing %}

      <article class="ongoing-project">

        <p class="project-period">
          {{ project.period | escape }}
        </p>

        <h3 class="project-title">
          {{ project.title | escape }}
        </h3>

        <p class="project-agency">
          {{ project.agency | escape }}
        </p>

      </article>

      {% endfor %}

    </div>

  </section>


  <!-- Past Projects -->

  <section class="projects-section">

    <h2 class="section-title">Past Projects</h2>

    <div class="past-projects">

      {% for project in site.data.projects.past %}

      <article class="past-project">

        <div class="project-period">
          {{ project.period | escape }}
        </div>

        <div class="project-content">

          <h3 class="project-title">
            {{ project.title | escape }}
          </h3>

          <p class="project-agency">
            {{ project.agency | escape }}
          </p>

        </div>

      </article>

      {% endfor %}

    </div>

  </section>

</div>