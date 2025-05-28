---
layout: default
title: Directory
template: 0.4
has_children: true
nav_order: 51
has_toc: false

---

{% comment %}

# Directory

<br>
<details close markdown="block">
  <summary id="index">
    <b>People</b><br> 
  </summary>
{: .text-delta .fs-5}
<p>
{% for my_page in site.pages %}
	{% if my_page.type == 'people' %}
        {% if my_page.status %}
	        <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a>, {{ my_page.status }}<br>
        {% else %}
            <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a><br>
        {% endif %}
      {% endif %}
{% endfor %}
</p>
{: .text-delta .fs-3}
</details>

<iframe style="border-radius:12px" src="https://petracoding.github.io/pinterest/board.html?link=estevaoseco/unsettled/people/&hideHeader=1&hideFooter=1&transparent=1" width="100%" height="352" style="color-scheme: site" frameBorder="0" allowfullscreen=""></iframe>

<br>
<details close markdown="block">
  <summary id="index">
    <b>Factions</b><br> 
  </summary>
{: .text-delta .fs-5}
<p>
{% for my_page in site.pages %}
     {% if my_page.type == 'faction' %}
        <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a><br>
    {% endif %}
{% endfor %}
</p>
{: .text-delta .fs-3}
</details>

<iframe style="border-radius:12px" src="https://petracoding.github.io/pinterest/board.html?link=estevaoseco/unsettled/factions/&hideHeader=1&hideFooter=1&transparent=1" width="100%" height="352" style="color-scheme: site" frameBorder="0" allowfullscreen=""></iframe>

<br>
<details close markdown="block">
  <summary id="index">
    <b>Locations</b><br> 
  </summary>
{: .text-delta .fs-5}
<p>
{% for my_page in site.pages %}
     {% if my_page.type == 'location' %}
        <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a><br>
    {% endif %}
{% endfor %}
</p>
{: .text-delta .fs-3}
</details>

<iframe style="border-radius:12px" src="https://petracoding.github.io/pinterest/board.html?link=estevaoseco/unsettled/vistas/&hideHeader=1&hideFooter=1&transparent=1" width="100%" height="352" style="color-scheme: site" frameBorder="0" allowfullscreen=""></iframe>

<br>
<details close markdown="block">
  <summary id="index">
    <b>Folklore</b><br> 
  </summary>
  {: .text-delta .fs-5}
<p>
{% for my_page in site.pages %}
     {% if my_page.type == 'creature' %}
        <a href="{{ site.url }}{{ my_page.url }}">{{ my_page.title }}</a><br>
    {% endif %}
{% endfor %}
</p>
{: .text-delta .fs-3}
</details>

<iframe style="border-radius:12px" src="https://petracoding.github.io/pinterest/board.html?link=estevaoseco/unsettled/folklore/&hideHeader=1&hideFooter=1&transparent=1" width="100%" height="352" frameBorder="0" style="color-scheme: site" allowfullscreen=""></iframe>

{% endcomment %}

{% include header_directories.md %}