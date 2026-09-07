---
layout: default
title: Recipes
---
# {{ page.title }}
<table id="recipes" cellspacing="0">
{% for recipe in site.recipes %}
<tr>
    <td class="recipe-idx-name"><h2><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.title }}</a></h2></td>
    <td class="recipe-idx-tags">{% include recipe_tags.html recipe_tags=recipe.recipe_tags %}</td>
</tr>
{% endfor %}
</table>
