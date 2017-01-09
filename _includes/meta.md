<div class="meta_wrapper">
<p class="postdate">{{ page.date | date_to_string }}</p>
  <div class="tag">
    <ul>{% for tag in page.tags %}
      <li><a href="/tag/{{ tag }}">{{ tag }}</a></li>
    {% endfor %}
    </ul>
  </div>
</div>
