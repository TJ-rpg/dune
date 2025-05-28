{% assign children_pages = site.pages | where: 'parent', page.title %}

{% assign links_pages = "" | split: "," %}
{% for entry in site.data.markdown_links.file[page.path] %}
	{% assign captured_page = site.pages | where: 'path', entry.url %}
	{% assign links_pages = links_pages | push: captured_page[0] | uniq %}
{% endfor %}

{% assign all_references = children_pages | push: links_pages | uniq | sort: 'nav_order' %}

<p>
{% assign count = all_references | where: 'type', 'people' | size %}
{% if count > 0 %}
<b>People</b> ({{ count }})<br>
{% for my_page in all_references %}
	{% if my_page.type == 'people' %}
        {% if my_page.status %}
	        <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a>, {{ my_page.status }}<br>
        {% else %}
            <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a><br>
        {% endif %}
      {% endif %}
{% endfor %}
<br>
{% endif %}

{% assign count = all_references | where: 'type', 'faction' | size %}
{% if count > 0 %}
<b>Factions</b> ({{ count }})<br>
{% for my_page in all_references %}
	{% if my_page.type == 'faction' %}
        {% if my_page.status %}
	        <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a>, {{ my_page.status }}<br>
        {% else %}
            <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a><br>
        {% endif %}
      {% endif %}
{% endfor %}
<br>
{% endif %}

{% assign count = all_references | where: 'type', 'location' | size %}
{% if count > 0 %}
<b>Locations</b> ({{ count }})<br>
{% for my_page in all_references %}
	{% if my_page.type == 'location' %}
        {% if my_page.status %}
	        <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a>, {{ my_page.status }}<br>
        {% else %}
            <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a><br>
        {% endif %}
      {% endif %}
{% endfor %}
<br>
{% endif %}

{% assign count = all_references | where: 'type', 'creature' | size %}
{% if count > 0 %}
<b>Folklore</b> ({{ count }})<br>
{% for my_page in all_references %}
	{% if my_page.type == 'creature' %}
        {% if my_page.status %}
	        <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a>, {{ my_page.status }}<br>
        {% else %}
            <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a><br>
        {% endif %}
      {% endif %}
{% endfor %}
<br>
{% endif %}

{% assign count = all_references | where: 'type', 'session' | size %}
{% if count > 0 %}
<b>Chapters</b> ({{ count }})<br>
{% for my_page in all_references %}
	{% if my_page.type == 'session' %}
	    {{ my_page.parent }}: <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a>, {{ my_page.region }} - {{ my_page.timestamp | date: "%B %-d"}}<br>
      {% endif %}
{% endfor %}
{% endif %}
</p>
{: .text-delta}

{% comment %}
connected_to v0.5.0
{% endcomment %}
