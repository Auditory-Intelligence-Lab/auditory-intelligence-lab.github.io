---
title: "Auditory Intelligence Lab - Current Members"
layout: teamtabs
team_tab: members
permalink: /team/members/
---

<div class="members-page" markdown="0">

  <h1>Current Members</h1>

  {% for group in site.data.members %}

  <section class="member-section">

    <h2 class="section-title">
      {{ group.group }}
    </h2>

    <div class="member-grid">

      {% for member in group.members %}

      <article class="member-card">

        {% if member.photo and member.photo != "" %}

        <img class="member-photo"
             src="{{ site.baseurl }}/images/members/{{ member.photo }}"
             alt="{{ member.name | escape }}"
             loading="lazy">

        {% else %}

        <div class="member-photo-placeholder"
             aria-label="Profile photo unavailable"
             role="img">
          <i data-lucide="user-round"
             aria-hidden="true"></i>
        </div>

        {% endif %}

        <h3>{{ member.name }}</h3>

        <p class="member-start">
          Since {{ member.start }}
        </p>

        <p class="member-research">
          {{ member.research }}
        </p>

      </article>

      {% endfor %}

    </div>

  </section>

  {% endfor %}

</div>