---
layout: default
title: Journal
permalink: /journal/
---

<div class="ic-journal">

  <!-- =====================================================
       HERO
       ===================================================== -->

  <section class="ic-journal-hero">

    <div class="ic-journal-hero__image">
      <img
        src="{{ '/assets/images/heroes/journal-hero.jpg' | relative_url }}"
        alt="IceCore Dynasty Journal"
      >
    </div>

    <div class="ic-journal-hero__content">

      <span class="ic-journal-eyebrow">
        ICECORE DYNASTY · JOURNAL
      </span>

      <h1>
        Stories behind<br>
        the standings.
      </h1>

      <p>
        League news, franchise stories, guides, draft coverage
        and the decisions shaping IceCore Dynasty.
      </p>

    </div>

  </section>


  <!-- =====================================================
       FEATURED
       ===================================================== -->

  <section class="ic-journal-section">

    <header class="ic-journal-heading">
      <span>FEATURED</span>
      <h2>From the league.</h2>
    </header>


    <article class="ic-feature-story">

      <div class="ic-feature-story__meta">
        <span>LEAGUE</span>
        <span>LEAGUE 1</span>
        <time>2026</time>
      </div>

      <div class="ic-feature-story__content">

        <h2>
          A new dynasty begins.
        </h2>

        <p>
          Twenty franchises. Permanent identities. One shared history
          waiting to be written.
        </p>

        <p>
          IceCore Dynasty begins with a simple idea: build a fantasy league
          where franchises feel permanent, decisions matter beyond one
          season and dynasty hockey remains easy enough to enjoy.
        </p>

        <a href="{{ '/journal/inaugural-season/' | relative_url }}">
          Read story →
        </a>

      </div>

      <div class="ic-feature-story__number">
        001
      </div>

    </article>

  </section>


  <!-- =====================================================
       HEADLINES
       ===================================================== -->

  <section class="ic-journal-section">

    <header class="ic-journal-heading">
      <span>HEADLINES</span>
      <h2>Around IceCore.</h2>

      <p>
        League announcements, franchise developments and the stories
        moving the league.
      </p>
    </header>


    <div class="ic-headlines">

      <article>

        <div class="ic-headlines__meta">
          <span>LEAGUE</span>
          <time>2026</time>
        </div>

        <h3>IceCore Dynasty prepares for its inaugural season.</h3>

        <p>
          The first franchises prepare to enter a new long-term fantasy
          hockey competition.
        </p>

        <a href="{{ '/journal/inaugural-season/' | relative_url }}">
          Read →
        </a>

      </article>


      <article>

        <div class="ic-headlines__meta">
          <span>GUIDE</span>
          <time>2026</time>
        </div>

        <h3>What does it mean to manage an IceCore franchise?</h3>

        <p>
          A quick introduction to keepers, salaries, prospects and the
          decisions that carry from season to season.
        </p>

        <a href="{{ '/journal/gm-guide/' | relative_url }}">
          Read →
        </a>

      </article>


      <article>

        <div class="ic-headlines__meta">
          <span>DRAFT</span>
          <time>2026</time>
        </div>

        <h3>How the IceCore Entry Draft works.</h3>

        <p>
          One rookie per franchise, reverse standings and no lottery.
          The system behind IceCore's annual influx of young talent.
        </p>

        <a href="{{ '/journal/entry-draft-guide/' | relative_url }}">
          Read →
        </a>

      </article>

    </div>

  </section>


  <!-- =====================================================
       EXPLORE / FILTERS
       ===================================================== -->

  <section class="ic-journal-section ic-journal-explore">

    <header class="ic-journal-heading">
      <span>ARCHIVE</span>
      <h2>Explore the Journal.</h2>
    </header>


    <div class="ic-journal-filters">

      <label>
        <span>League</span>

        <select id="journalLeague">
          <option value="all">All Leagues</option>
          <option value="league-1">League 1</option>
          <option value="league-2">League 2</option>
        </select>
      </label>


      <label>
        <span>Category</span>

        <select id="journalCategory">
          <option value="all">All Categories</option>
          <option value="league">League News</option>
          <option value="franchise">Franchises</option>
          <option value="draft">Draft</option>
          <option value="guide">Guides</option>
          <option value="analysis">Analysis</option>
          <option value="history">History</option>
        </select>
      </label>


      <label>
        <span>Season</span>

        <select id="journalSeason">
          <option value="all">All Seasons</option>
          <option value="2026-27">2026–27</option>
        </select>
      </label>

    </div>


    <!-- ===================================================
         ARTICLES
         Add future articles by copying one article block.
         =================================================== -->

    <div class="ic-journal-archive" id="journalArchive">


      <article
        class="ic-journal-item"
        data-league="league-1"
        data-category="league"
        data-season="2026-27"
      >

        <div class="ic-journal-item__date">
          <strong>2026</strong>
          <span>PRESEASON</span>
        </div>

        <div class="ic-journal-item__body">

          <div class="ic-journal-item__tags">
            <span>League 1</span>
            <span>League News</span>
          </div>

          <h3>A new dynasty begins.</h3>

          <p>
            The story behind IceCore Dynasty and the philosophy behind
            its inaugural group of franchises.
          </p>

        </div>

        <a
          class="ic-journal-item__link"
          href="{{ '/journal/inaugural-season/' | relative_url }}"
          aria-label="Read A new dynasty begins"
        >
          →
        </a>

      </article>


      <article
        class="ic-journal-item"
        data-league="all"
        data-category="guide"
        data-season="2026-27"
      >

        <div class="ic-journal-item__date">
          <strong>2026</strong>
          <span>GUIDE</span>
        </div>

        <div class="ic-journal-item__body">

          <div class="ic-journal-item__tags">
            <span>All Leagues</span>
            <span>Guide</span>
          </div>

          <h3>The General Manager's Guide to IceCore.</h3>

          <p>
            The essential guide to salaries, keepers, prospects,
            drafts and long-term franchise management.
          </p>

        </div>

        <a
          class="ic-journal-item__link"
          href="{{ '/journal/gm-guide/' | relative_url }}"
          aria-label="Read General Manager's Guide"
        >
          →
        </a>

      </article>


      <article
        class="ic-journal-item"
        data-league="all"
        data-category="draft"
        data-season="2026-27"
      >

        <div class="ic-journal-item__date">
          <strong>2026</strong>
          <span>DRAFT</span>
        </div>

        <div class="ic-journal-item__body">

          <div class="ic-journal-item__tags">
            <span>All Leagues</span>
            <span>Draft</span>
          </div>

          <h3>Inside the IceCore Entry Draft.</h3>

          <p>
            Why every franchise receives one rookie and how the draft
            supports competitive balance without adding offseason chaos.
          </p>

        </div>

        <a
          class="ic-journal-item__link"
          href="{{ '/journal/entry-draft-guide/' | relative_url }}"
          aria-label="Read Entry Draft Guide"
        >
          →
        </a>

      </article>

    </div>


    <div class="ic-journal-empty" id="journalEmpty">
      No stories match these filters.
    </div>

  </section>


  <!-- =====================================================
       CATEGORIES
       ===================================================== -->

  <section class="ic-journal-section">

    <header class="ic-journal-heading">
      <span>SECTIONS</span>
      <h2>Inside the Journal.</h2>
    </header>


    <div class="ic-journal-categories">

      <article>
        <span>01</span>
        <h3>League News</h3>
        <p>
          Announcements, milestones, expansion and major developments
          across IceCore.
        </p>
      </article>


      <article>
        <span>02</span>
        <h3>Franchises</h3>
        <p>
          Team stories, rebuilds, rivalries, major trades and the people
          behind the league's permanent clubs.
        </p>
      </article>


      <article>
        <span>03</span>
        <h3>Draft</h3>
        <p>
          Entry Draft coverage, Salary Cap Draft stories and the decisions
          shaping the next generation.
        </p>
      </article>


      <article>
        <span>04</span>
        <h3>Guides</h3>
        <p>
          Straightforward explanations of IceCore systems for new and
          returning General Managers.
        </p>
      </article>


      <article>
        <span>05</span>
        <h3>Analysis</h3>
        <p>
          Salary value, roster construction, league trends and strategic
          stories worth looking at more closely.
        </p>
      </article>


      <article>
        <span>06</span>
        <h3>History</h3>
        <p>
          Championships, records, defining moments and the archive that
          grows with every IceCore season.
        </p>
      </article>

    </div>

  </section>


  <!-- =====================================================
       CLOSING
       ===================================================== -->

  <section class="ic-journal-closing">

    <span>THE ARCHIVE STARTS HERE</span>

    <h2>
      Today is news.<br>
      Tomorrow is history.
    </h2>

    <p>
      The Journal follows IceCore from its inaugural franchises through
      every draft, championship, rebuild and era that follows.
    </p>

    <strong>Season One · 2026–27</strong>

  </section>

</div>


<script>
document.addEventListener("DOMContentLoaded", function () {

  const leagueFilter = document.getElementById("journalLeague");
  const categoryFilter = document.getElementById("journalCategory");
  const seasonFilter = document.getElementById("journalSeason");

  const articles = document.querySelectorAll(".ic-journal-item");
  const emptyState = document.getElementById("journalEmpty");

  function filterJournal() {

    const league = leagueFilter.value;
    const category = categoryFilter.value;
    const season = seasonFilter.value;

    let visible = 0;

    articles.forEach(function (article) {

      const articleLeague = article.dataset.league;
      const articleCategory = article.dataset.category;
      const articleSeason = article.dataset.season;

      const leagueMatch =
        league === "all" ||
        articleLeague === "all" ||
        articleLeague === league;

      const categoryMatch =
        category === "all" ||
        articleCategory === category;

      const seasonMatch =
        season === "all" ||
        articleSeason === season;

      const show =
        leagueMatch &&
        categoryMatch &&
        seasonMatch;

      article.hidden = !show;

      if (show) {
        visible++;
      }

    });

    emptyState.style.display = visible === 0 ? "block" : "none";

  }

  leagueFilter.addEventListener("change", filterJournal);
  categoryFilter.addEventListener("change", filterJournal);
  seasonFilter.addEventListener("change", filterJournal);

  filterJournal();

});
</script>
