layout: default
title: Publications
---

To request an audio version of any publication, please send me an email!

# Publications
   
<div class="filter-controls">
<button class="filter-btn active" data-filter="all">All</button>
<button class="filter-btn" data-filter="2026">2026</button>
<button class="filter-btn" data-filter="2025">2025</button>
<button class="filter-btn" data-filter="2024">2024</button>
<button class="filter-btn" data-filter="older">Older</button>
</div>

<ul class="papers-list">

<li class="paper-item" data-year="2025">
<span class="paper-year">2025</span>
<div class="paper-content">
<span class="paper-title">A scoping review on U.S. undergraduate students with disabilities in STEM courses and STEM majors</span>
<span class="paper-authors"> M Borrego, A Chasen, HC Tripp, <strong>Emily Landgren</strong>, E Koolman.</span>
<span class="paper-venue"> Int. Journal STEM Education (January 2025).</span>
</div>
<a href="https://doi.org/10.1186/s40594-024-00522-2"></a>
</li>

<li class="paper-item" data-year="2025">
<span class="paper-year">2025</span>
<div class="paper-content">
<span class="paper-title">A systematic review of differences for disabled students in STEM versus other disciplinary undergraduate settings</span>
<span class="paper-authors"> A Chasen, M Borrego, E Koolman, <strong>Emily Landgren</strong>, HC Tripp.</span>
<span class="paper-venue"> Journal of Engineering Education (January 2025).</span>
</div>
<a href="https://doi-org.ezproxy.lib.utexas.edu/10.1002/jee.20627"></a>
</li>

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


