<h2 id="awards" style="margin: 2px 0px 10px;">🎖 Awards</h2>

<div class="awards">
<ul class="award-list">

{% for award in site.data.awards.awards %}

<li class="award-item">
  <span class="award-year">{{ award.date }}</span>
  <span class="award-body">
    <span class="award-title">{{ award.title }}</span>
    {% if award.desc %}<span class="award-desc">{{ award.desc }}</span>{% endif %}
  </span>
</li>

{% endfor %}

</ul>
</div>
