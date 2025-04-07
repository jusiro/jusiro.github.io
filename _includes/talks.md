## Talks, Tutorials
---

<h2 id="publications" style="margin: 2px 0px -15px;"></h2>

<div class="publications" style="height: 160px; overflow: auto;">
<ol class="bibliography">

{% for link in site.data.talks.main %}

<li style="min-height: 10px;">
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px; font-size:15px;">
      <div class="title"><a href="{{ link.website }}">{{ link.title }}</a></div>
      <div class="periodical"><em>{{ link.venue }}</em></div>
    <div class="links">
      {% if link.date %} 
      <div style="display: inline-block;">
      {{link.date}} -
      </div>
      {% endif %}
      {% if link.slides %} 
      <a href="{{ link.slides }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Slides</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.posts %} 
      <a href="{{ link.posts }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Posts</a>
      {% endif %}
      {% if link.medium %} 
      <a href="{{ link.medium }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Medium</a>
      {% endif %}
    </div>
  </div>
</div>
</li>

{% endfor %}

</ol>
</div>

