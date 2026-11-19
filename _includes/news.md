<div class="news">

{% assign news_items = site.data.news %}
{% assign visible_count = 10 %}
{% capture latest_news %}{% for item in news_items limit: visible_count %}- {{ item }}
{% endfor %}{% endcapture %}
{{ latest_news | markdownify }}

{% if news_items.size > visible_count %}
{% assign earlier_count = news_items.size | minus: visible_count %}
<details class="news-more">
<summary><span class="news-more-show">Show earlier news ({{ earlier_count }})</span><span class="news-more-hide">Hide earlier news</span></summary>

{% capture earlier_news %}{% for item in news_items offset: visible_count %}- {{ item }}
{% endfor %}{% endcapture %}
{{ earlier_news | markdownify }}

</details>
{% endif %}

</div>
