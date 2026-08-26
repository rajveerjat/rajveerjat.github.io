---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.home-wrap { --line: #e3e3e3; --ink: #222; --sub: #6b6b6b; --accent: #3b5bdb; }

.tag-filter { margin: 0.8em 0 1.2em; }
.tag-btn { border:1px solid var(--line); background:#fff; border-radius:14px; padding:0.32em 0.9em; font-size:0.8em; cursor:pointer; margin:0 0.4em 0.4em 0; color:var(--ink); }
.tag-btn.active { background:var(--accent); color:#fff; border-color:var(--accent); }

.timeline { border-left:2px solid var(--line); margin-left:0.5em; padding-left:1.2em; }
.t-item { position:relative; margin-bottom:1.1em; }
.t-item::before { content:""; position:absolute; left:-1.53em; top:0.35em; width:9px; height:9px; border-radius:50%; background:var(--accent); }
.t-item h4 { margin:0 0 0.25em; font-size:0.98em; }
.t-item .terms { font-size:0.9em; color:var(--sub); line-height:1.5; }

.n-tag { display:inline-block; font-size:0.64em; font-weight:700; text-transform:uppercase; letter-spacing:0.02em; border-radius:8px; padding:0.15em 0.55em; margin-right:0.5em; vertical-align:middle; }
.n-tag-publication { background:#e8ecff; color:#3b5bdb; }
.n-tag-talk        { background:#e6f4ea; color:#1a7f37; }
.n-tag-award       { background:#fff1e0; color:#b5641a; }
.n-tag-position    { background:#fdeaea; color:#c0392b; }
.n-tag-media       { background:#f3e8ff; color:#7c3aed; }
.n-tag-milestone   { background:#eef1f4; color:#555; }

.news-more-row { text-align:center; margin-top:0.6em; }
</style>

Welcome!

I work in the AI/ML team at Western Digital. Out of personal interest, I teach at UC Berkeley and pursue academic research.

I hold a PhD in Econometrics from the University of California, Riverside, an MS with academic distinction from the Indian Statistical Institute, and a Bachelor's in Electrical Engineering from IIT Roorkee.

Research Areas: Econometric Methods (High-dimensions, Causal, Nonparametrics), Machine Learning.

Application Areas: Finance, Development, IO, Macro.

## News

<!--
  HOW TO ADD A NEW ITEM
  ----------------------
  1. Copy one <div class="t-item" data-tag="...">...</div> block below.
  2. Set data-tag AND the n-tag class/label together (must match):
       publication | talk | award | position | media | milestone
       e.g. data-tag="award" pairs with class "n-tag n-tag-award" and label "Award"
  3. Paste it in chronological order (newest at the top of the list).
  4. No need to worry about the 12-item cap or "See more" button — those
     are handled automatically by the script at the bottom of this file.
-->

<div class="home-wrap">

<div class="tag-filter">
<button class="tag-btn active" data-filter="all">All</button>
<button class="tag-btn" data-filter="publication">Publication</button>
<button class="tag-btn" data-filter="talk">Talk</button>
<button class="tag-btn" data-filter="award">Award</button>
<button class="tag-btn" data-filter="position">Position</button>
<button class="tag-btn" data-filter="media">Media</button>
<button class="tag-btn" data-filter="milestone">Milestone</button>
</div>

<div class="timeline" id="news-timeline">

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Jun 2026</h4>
<div class="terms">Paper accepted for oral presentation at the 2026 North American Summer Meeting (NASM) of the Econometric Society, Atlanta, GA, USA.</div>
</div>

<div class="t-item" data-tag="position">
<h4><span class="n-tag n-tag-position">Position</span>Jun 2026</h4>
<div class="terms">Will be teaching in the Dept. of Economics at UC Berkeley.</div>
</div>

<div class="t-item" data-tag="media">
<h4><span class="n-tag n-tag-media">Media</span>Mar 2026</h4>
<div class="terms">Article published in <a href="https://voxdev.org/topic/agriculture/rethinking-agricultural-productivity-gap-informality-matters">VoxDev</a>.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Jan 2026</h4>
<div class="terms">Paper accepted for presentation at the 2026 Asia Meeting of the Econometric Society (AMES-CSW 2026).</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Dec 2025</h4>
<div class="terms">Paper accepted for presentation at the European Winter Meeting of the Econometric Society 2025.</div>
</div>

<div class="t-item" data-tag="position">
<h4><span class="n-tag n-tag-position">Position</span>Oct 2025</h4>
<div class="terms">Started serving as a member of the Program Committee of the <a href="https://www.isid.ac.in/~acegd/acegd2025/committees.html">Annual Conference on Economic Growth and Development</a> to judge/referee papers in econometric methodology.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Oct 2025</h4>
<div class="terms">Presented paper at the 35th Annual Midwest Econometrics Group Conference, UIUC, IL, USA.</div>
</div>

<div class="t-item" data-tag="publication">
<h4><span class="n-tag n-tag-publication">Publication</span>Sep 2025</h4>
<div class="terms"><a href="https://www.sciencedirect.com/science/article/pii/S0304387825001683">Paper</a> published in the Journal of Development Economics.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Sep 2025</h4>
<div class="terms">Presented paper at the 2025 California Econometrics Conference.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Aug 2025</h4>
<div class="terms">Paper accepted for weekly seminar at Indian Statistical Institute, Delhi Center.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Aug 2025</h4>
<div class="terms">Gave a research talk at Indian Institute of Technology (IIT) Delhi.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Apr 2025</h4>
<div class="terms">Presented paper in the 13th World Congress of the Econometric Society in Seoul, South Korea.</div>
</div>

<div class="t-item" data-tag="milestone">
<h4><span class="n-tag n-tag-milestone">Milestone</span>Jun 2025</h4>
<div class="terms">Concluded my term as Head of the Graduate Quantitative Methods Center (GradQuant), University of California, Riverside (2024–25).</div>
</div>

<div class="t-item" data-tag="position">
<h4><span class="n-tag n-tag-position">Position</span>Jun 2025</h4>
<div class="terms">Joined Western Digital Corporation in San Jose.</div>
</div>

<div class="t-item" data-tag="milestone">
<h4><span class="n-tag n-tag-milestone">Milestone</span>Jun 2025</h4>
<div class="terms">Graduated with PhD in Economics from the University of California, Riverside (<a href="https://drive.google.com/drive/folders/1N3D09IK0m17JpCIaavQb6asZdZbu0MNj?usp=sharing">Pictures</a>).</div>
</div>

<div class="t-item" data-tag="milestone">
<h4><span class="n-tag n-tag-milestone">Milestone</span>Jun 2025</h4>
<div class="terms">Defended PhD at the University of California, Riverside (<a href="https://drive.google.com/drive/folders/1fgSVJVuRGopWwEjnBq3r0GocauOEpA0u?usp=sharing">Pictures</a>).</div>
</div>

<div class="t-item" data-tag="award">
<h4><span class="n-tag n-tag-award">Award</span>May 2025</h4>
<div class="terms">Awarded Outstanding Teaching Award by the University of California, Riverside.</div>
</div>

<div class="t-item" data-tag="award">
<h4><span class="n-tag n-tag-award">Award</span>Apr 2025</h4>
<div class="terms">Received a USD 2,000 award for being among the top researchers presenting at the 13th World Congress of the Econometric Society.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Apr 2025</h4>
<div class="terms">Paper accepted for presentation at the 13th World Congress of the Econometric Society (held once every five years). <a href="https://www.eswc2025.org/">Learn more</a>.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Apr 2025</h4>
<div class="terms">Delivered a research talk at the Ontario Agricultural College, University of Guelph, Canada.</div>
</div>

<div class="t-item" data-tag="award">
<h4><span class="n-tag n-tag-award">Award</span>Apr 2025</h4>
<div class="terms">Best Presentation Award in the Graduate Research Symposium at the University of California, Riverside.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Mar 2025</h4>
<div class="terms">Paper accepted for presentation at the 2025 International Association for Applied Econometrics Conference (IAAE Italy 2025). <a href="https://sites.google.com/view/iaae2025/">Learn more</a>.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Jan 2025</h4>
<div class="terms">Delivered a research talk at Southern Illinois University Carbondale (SIUC), Illinois, USA.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Jan 2025</h4>
<div class="terms">Delivered a research talk at Gettysburg College, Pennsylvania, USA.</div>
</div>

<div class="t-item" data-tag="publication">
<h4><span class="n-tag n-tag-publication">Publication</span>Dec 2024</h4>
<div class="terms">Got R&amp;R (Revise and Resubmit) from the <a href="https://www.sciencedirect.com/journal/journal-of-development-economics">Journal of Development Economics</a>. My paper (with <a href="https://scholar.google.co.in/citations?user=aGVkcp8AAAAJ&hl=en">Bharat Ramaswami</a>), <a href="https://rajveerjat.com/files/APG.pdf">The Agricultural Productivity Gap: Informality Matters</a>, received Revise and Resubmit.</div>
</div>

<div class="t-item" data-tag="award">
<h4><span class="n-tag n-tag-award">Award</span>Nov 2024</h4>
<div class="terms">Awarded Earle C. Anthony Graduate Student Travel Award (USD 1,950) in Fall 2024 for traveling to international conferences, by the University of California, Riverside.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Oct 2024</h4>
<div class="terms">Paper accepted for presentation at the <a href="https://www.econometricsociety.org/regional-activities/schedule/2024/12/16/2024-European-Winter-Meeting-Palma-de-Majorca-Spain">European Winter Meeting of the Econometric Society, 2024</a>, held in Dec 2024 in Palma de Mallorca, Spain.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Oct 2024</h4>
<div class="terms">Paper accepted for presentation at the <a href="https://www.isid.ac.in/~acegd/acegd2024/index.html">19th Annual Conference on Economic Growth and Development, 2024</a>, organized by the Indian Statistical Institute.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Oct 2024</h4>
<div class="terms">Paper accepted for presentation at the <a href="https://gatton.uky.edu/meg2024">34th Annual Midwest Econometrics Group Conference</a>, held in Nov 2024 in Lexington, KY, USA.</div>
</div>

<div class="t-item" data-tag="talk">
<h4><span class="n-tag n-tag-talk">Talk</span>Sep 2024</h4>
<div class="terms">Presented at the California Econometric Conference, hosted by UC Davis. <a href="https://www.gsb.stanford.edu/faculty-research/faculty/conferences/california-econometrics">Learn more</a>.</div>
</div>

<div class="t-item" data-tag="publication">
<h4><span class="n-tag n-tag-publication">Publication</span>Aug 2024</h4>
<div class="terms"><a href="https://rajveerjat.com/files/APG.pdf">The Agricultural Productivity Gap: Informality Matters</a> paper under review at the Journal of Development Economics.</div>
</div>

<div class="t-item" data-tag="position">
<h4><span class="n-tag n-tag-position">Position</span>Jul 2024</h4>
<div class="terms">Appointed Lead of the <a href="https://gradquant.ucr.edu/">Graduate Quantitative Methods Center</a> at UC Riverside.</div>
</div>

<div class="t-item" data-tag="publication">
<h4><span class="n-tag n-tag-publication">Publication</span>Jul 2024</h4>
<div class="terms"><a href="https://rajveerjat.com/files/Kernel_3PRF.pdf">Kernel Three Pass Regression Filter</a> paper under review at the <a href="https://onlinelibrary.wiley.com/journal/10991255">Journal of Applied Econometrics</a>.</div>
</div>

</div>

<div class="news-more-row"><button class="tag-btn" id="news-more-btn">See more updates</button></div>

</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  var items = Array.prototype.slice.call(document.querySelectorAll("#news-timeline .t-item"));
  var filterBtns = document.querySelectorAll(".tag-filter .tag-btn");
  var moreBtn = document.getElementById("news-more-btn");
  var VISIBLE_COUNT = 12;
  var currentFilter = "all";
  var expanded = false;

  function render() {
    var shown = 0;
    items.forEach(function (item) {
      var tag = item.getAttribute("data-tag");
      var matches = currentFilter === "all" || tag === currentFilter;
      if (!matches) {
        item.style.display = "none";
        return;
      }
      if (currentFilter !== "all" || expanded || shown < VISIBLE_COUNT) {
        item.style.display = "";
        shown++;
      } else {
        item.style.display = "none";
      }
    });
    if (moreBtn) {
      moreBtn.style.display = currentFilter === "all" ? "" : "none";
      moreBtn.textContent = expanded ? "Show fewer updates" : "See more updates";
    }
  }

  filterBtns.forEach(function (btn) {
    btn.addEventListener("click", function () {
      filterBtns.forEach(function (b) { b.classList.remove("active"); });
      btn.classList.add("active");
      currentFilter = btn.getAttribute("data-filter");
      render();
    });
  });

  if (moreBtn) {
    moreBtn.addEventListener("click", function () {
      expanded = !expanded;
      render();
    });
  }

  render();
});
</script>

---

## Connect
- Email: rjat001@ucr.edu
