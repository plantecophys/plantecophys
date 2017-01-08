<div class="meta_wrapper">
<p class="postdate">{{ page.date | date_to_string }}</p>
<ul class="tag_list_in_post">{% for tag in page.tags %}
  <li class="inline tag_list_item"><a class="tag_list_link" href="/tag/{{ tag }}">{{ tag }}</a></li>
  {% endfor %}
</ul>
</div>
