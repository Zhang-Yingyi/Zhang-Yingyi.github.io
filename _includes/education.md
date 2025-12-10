<h2 id="education" style="margin: 2px 0px 0px;">Education</h2>

<div class="education">
<ol class="bibliography">

{% for edu in site.data.education.education %}


<li>
  <div class="pub-row">
    <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
      {% if edu.logo %}
      <img src="{{ edu.logo }}" style="width: 30px; height: auto;">
      {% endif %}
    </div>
    <div class="col-sm-9" style="position: relative;padding-right: 15px; padding-left: 20px;">
      <div style="display:flex; justify-content:space-between; align-items:baseline;">
        <div class="title"><strong>{{ edu.name }}</strong></div>
        <div style="font-style: italic; white-space: nowrap;">{{ edu.date }}</div>
      </div>
      <div class="author">{{ edu.position }}</div>
    </div>
<!-- 
    <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><strong>{{ edu.name }}</strong></div>
      <div class="author">{{ edu.position }}</div>
      <div class="periodical"><em>{{ edu.date }}</em></div>
    </div> -->


  </div>
</li>
<br>

{% endfor %}

</ol>
</div>