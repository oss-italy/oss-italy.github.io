---
layout: default
---

# Events

L'Open Source Saturday Italy si tiene **tutti** i sabati.
Guarda a che progetti abbiamo contribuito negli eventi passati o mostra a cosa
hai lavorato durante l'evento con un commento:

{% for e in site.events %}
  {% if e.url != "/events/index.html" %}
  * <a href="{{ e.url }}">{{ e.event_date | date: "%Y/%m/%d" }}</a>
  {% endif %}
{% endfor %}