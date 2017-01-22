<div class="meta_wrapper">
<p class="postdate">{{ page.date | date_to_string }}</p>
  <div class="tag">
    <ul>{% for tag in page.tags %}
      <li><a href="/tag/{{ tag | url_encode }}"><img border="0" alt="tag" src="/img/tags.png" width="10" height="10">{{ tag }}</a></li>
    {% endfor %}
    </ul>
  </div>
</div>
