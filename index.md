---
title: Pokeballroom
---

| Pokemon | Natures | Ability | Egg moves | Ball | On Hand? | Breedable? |
|-|-|-|-|-|-|
{% for item in site.data.list %} | {{ item.pokemon }} | {{ item.nature }} | {{ item.ability }} | {{ item.egg_moves }} | {{ item.ball }} | {% if item.on_hand == true %}✔{% elsif item.on_hand == false %}✘{% endif %} | {% if item.can_breed == true %}✔{% elsif item.can_breed == false %}✘{% endif %} |
{% endfor %}
