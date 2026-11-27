---
title: "Auditory Intelligence Lab - Awards"
layout: textlay
excerpt: "Awards and Achievements"
sitemap: false
permalink: /awards/
---

<div class="awards-page" markdown="0">

  <h1>Awards</h1>

  <div class="awards-timeline">

    {% for group in site.data.awards %}

    <section class="awards-year-section">

      <!-- Year -->

      <div class="awards-year">
        <h2>{{ group.year }}</h2>
      </div>


      <!-- Events -->

      <div class="awards-events">

        {% for event in group.events %}

        <article class="award-event">

          <h3 class="award-event-title">
            {{ event.title | escape }}
          </h3>

          {% if event.date or event.organizer %}

          <p class="award-event-meta">

            {% if event.date %}
              {{ event.date | escape }}
            {% endif %}

            {% if event.date and event.organizer %}
              &nbsp;&middot;&nbsp;
            {% endif %}

            {% if event.organizer %}
              {{ event.organizer | escape }}
            {% endif %}

          </p>

          {% endif %}


          <!-- Award Details -->

          <ul class="award-results">

            {% for award in event.awards %}

            <li class="award-result">

              <h4 class="award-prize">
                {{ award.prize | escape }}
              </h4>

              {% if award.track or award.team %}

              <p class="award-track">

                {% if award.track %}
                  {{ award.track | escape }}
                {% endif %}

                {% if award.track and award.team %}
                  &nbsp;&middot;&nbsp;
                {% endif %}

                {% if award.team %}
                  Team {{ award.team | escape }}
                {% endif %}

              </p>

              {% endif %}

              {% if award.members %}

              <p class="award-members">
                {{ award.members | escape }}
              </p>

              {% endif %}

            </li>

            {% endfor %}

          </ul>

        </article>

        {% endfor %}

      </div>

    </section>

    {% endfor %}

  </div>

</div>