This page is a memorial to my dear sweet departed cat, Romashka. 2021 - Nov. 2022

{% for image in site.static_files %}
 {% if image.path contains 'Romashka/' %}
  ![image]({{ image.path }} 'image')
 {% endif %}
{% endfor %}
