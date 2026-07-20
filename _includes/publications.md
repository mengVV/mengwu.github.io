<h2 id="publications">Publications</h2>

<div class="publications">
<ol class="bibliography">
{% for paper in site.data.publications.main %}
  <li>
    <div class="pub-entry">
      <div class="pub-title">
        {% if paper.pdf %}<a href="{{ paper.pdf }}">{{ paper.title }}</a>{% else %}{{ paper.title }}{% endif %}
      </div>
      <div class="author">{{ paper.authors }}</div>
      <div class="periodical"><em>{{ paper.conference }}</em></div>
      {% if paper.notes %}<div class="pub-note">{{ paper.notes }}</div>{% endif %}
      {% if paper.pdf or paper.code or paper.page %}
      <div class="links">
        {% if paper.pdf %}<a href="{{ paper.pdf }}" class="btn btn-sm" target="_blank" rel="noopener">PDF</a>{% endif %}
        {% if paper.code %}<a href="{{ paper.code }}" class="btn btn-sm" target="_blank" rel="noopener">Code</a>{% endif %}
        {% if paper.page %}<a href="{{ paper.page }}" class="btn btn-sm" target="_blank" rel="noopener">Project</a>{% endif %}
      </div>
      {% endif %}
    </div>
  </li>
{% endfor %}
</ol>
</div>
