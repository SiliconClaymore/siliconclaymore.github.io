---
layout: default
title: Sponsors
---
Want to support us?

[Contact Us!](mailto:laisan13@hotmail.com)

<div class="sponsor">
	{% for sponsor in site.data.sponsors %}
		{% if sponsor.web %}
			<a href="{{ sponsor.web }}">
			{% endif %}
			<img src="/sponsors/{{ sponsor.name }}.png" alt="{{ sponsor.name }}" />
			{% if sponsor.web %}
			</a>
		{% endif %}
	{% endfor %}
</div>