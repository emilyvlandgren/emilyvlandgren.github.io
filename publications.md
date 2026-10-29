layout: default
title: Publications
---


# Publications

If you cannot access or wish to request an audio version of any publication, please send me an email: emilyvlandgren@gmail.com
 
<div class="filter-controls">
<button class="filter-btn active" data-filter="all">All</button>
<button class="filter-btn" data-filter="2026">2026</button>
<button class="filter-btn" data-filter="2025">2025</button>
<button class="filter-btn" data-filter="2024">2024</button>
<button class="filter-btn" data-filter="older">Older</button>
</div>

<ul class="papers-list">


<li class="paper-item" data-year="2026">
<span class="paper-year">2026</span>
<div class="paper-content">
<span class="paper-title">Mentoring Graduate Students with Disabilities: A Qualitative Evidence Synthesis and Review</span>
<span class="paper-authors">M Borrego, S Cawthorn, A Chasen, LG Alvarez, <strong>E Landgren</strong>, M O’Grady, D Lama, S Aldaco.</span>
<span class="paper-venue"> Education Sciences</span>
</div>
<a href="https://doi.org/10.3390/educsci16020212"></a>
</li>

<li class="paper-item" data-year="2026">
<span class="paper-year">2026</span>
<div class="paper-content">
<span class="paper-title">Qualifying Exams and Proposals in Science and Engineering: Existing Barriers to Accessibility and Avenues for Change</span>
<span class="paper-authors">C Wright, <strong>EV Landgren</strong>, M Borrego.</span>
<span class="paper-venue">ASEE Annual Conference, Charlotte, NC, USA (June 2026).</span>
</div>
</li>


<li class="paper-item" data-year="2025">
<span class="paper-year">2025</span>
<div class="paper-content">
<span class="paper-title">A scoping review on U.S. undergraduate students with disabilities in STEM courses and STEM majors</span>
<span class="paper-authors">M Borrego, A Chasen, HC Tripp, <strong>EV Landgren</strong>, E Koolman.</span>
<span class="paper-venue">Int. Journal STEM Education</span>
</div>
<a href="https://doi.org/10.1186/s40594-024-00522-2"></a>
</li>

<li class="paper-item" data-year="2025">
<span class="paper-year">2025</span>
<div class="paper-content">
<span class="paper-title">A systematic review of differences for disabled students in STEM versus other disciplinary undergraduate settings</span>
<span class="paper-authors">A Chasen, M Borrego, E Koolman, <strong>E Landgren</strong>, HC Tripp.</span>
<span class="paper-venue">Journal of Engineering Education</span>
</div>
<a href="https://doi-org.ezproxy.lib.utexas.edu/10.1002/jee.20627"></a>
</li>

<li class="paper-item" data-year="2025">
<span class="paper-year">2025</span>
<div class="paper-content">
<span class="paper-title">Student-based Recommendations to Increase Accessibility in Undergraduate Engineering Programs: “If there’s people who can’t access it, then it’s not accessible.”</span>
<span class="paper-authors"><strong>E Landgren</strong>, M Borrego.</span>
<span class="paper-venue">ASEE Collaborative Network for Engineering & Computing Diversity (CoNECD), San Antonio, Texas, USA (February, 2025).</span>
</div>
</li>

<li class="paper-item" data-year="2024">
<span class="paper-year">2024</span>
<div class="paper-content">
<span class="paper-title">“It’s just a lack of empathy, which is just honestly exhausting” – Engineering Student Experiences with Ableism</span>
<span class="paper-authors"><strong>E Landgren</strong>, M Borrego.</span>
<span class="paper-venue">IEEE Frontiers in Education Conference (FIE), Washington D.C., USA (October, 2024).</span>
</div>
</li>


<!-- Flores, B. C., & Boklage, A., & Borrego, M., & Landgren, E. V., & Vielma, K. I., & Chavez, E. (2024, June), Inclusive Mentoring in Engineering and Science: An Evolving Workshop Model (Experience). Presented at 2024 ASEE Annual Conference & Exposition, Portland, Oregon, USA. 10.18260/1-2—4760 // Landgren, E., Koolman, E., Chasen, A., & Borrego, M. (2023, October), Disabled Student Experiences in Engineering: How to Improve Our Classroom Accessibility. Presented at 2023 IEEE Frontiers in Education Conference (FIE), College Station, Texas, USA. 10.1109/FIE58773.2023.10342938. -->

</ul>
  
<script>
// Paper filter functionality
function setupPaperFilters() {
const allFilterBtns = document.querySelectorAll('.filter-btn, #mobile-paper-filters button');
	  
allFilterBtns.forEach(btn => {
btn.addEventListener('click', () => {
// Update active state for both desktop and mobile
document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
document.querySelectorAll('#mobile-paper-filters button').forEach(b => b.classList.remove('active'));
btn.classList.add('active');
		  
const filter = btn.dataset.filter;
document.querySelectorAll('.paper-item').forEach(item => {
if (filter === 'all' || item.dataset.year === filter) {
item.style.display = 'flex';
item.style.opacity = '1';
} else {
item.style.display = 'none';
item.style.opacity = '0';
}
});
});
});
}

	setupPaperFilters();
</script>


