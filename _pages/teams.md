---
title: Teams
permalink: /teams/
layout: icecore-page
author_profile: false
---

<section class="teams-hero">

  <div class="teams-hero__inner">

    <div class="teams-hero__copy">

      <span class="teams-hero__eyebrow">OUR FRANCHISES</span>

      <h1>
        EVERY FRANCHISE<br>
        HAS A STORY<span>.</span>
      </h1>

      <div class="teams-hero__line"></div>

      <p>
        Every city. Every identity.<br>
        Every dynasty begins somewhere.
      </p>

    </div>

    <div class="teams-hero__mark" aria-hidden="true">
      IC
    </div>

  </div>

</section>


<section class="teams-directory">

  <div class="teams-directory__inner">

    <div class="teams-directory__top">

      <div>
        <span class="teams-section-label">ACTIVE FRANCHISES</span>
        <div class="teams-section-line"></div>
      </div>

      <div class="teams-filters">

        <label class="teams-filter">
          <span>League</span>

          <select id="league-filter">
            <option value="1">League I</option>
          </select>
        </label>

        <label class="teams-filter">
          <span>Conference</span>

          <select id="conference-filter">
            <option value="all">All Conferences</option>
            <option value="east">Eastern</option>
            <option value="west">Western</option>
          </select>
        </label>

      </div>

    </div>

    {% include team-grid.html %}

  </div>

</section>
