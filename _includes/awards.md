<h2 id="awards" style="margin: 2px 0px 10px;">🎖 Awards</h2>

<div class="awards">
<ul class="award-list">

{% for award in site.data.awards.awards %}

<li class="award-item">
  <div class="award-row">
    <span class="award-year">[{{ award.date }}]</span>
    <strong class="award-title">{{ award.title }}</strong>
    <span class="award-desc">{{ award.desc }}</span>
  </div>
</li>

{% endfor %}

</ul>
</div>
