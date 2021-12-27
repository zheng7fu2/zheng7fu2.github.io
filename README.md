// 以下嵌入页面，page.url以 "/" 开头
<nav>
  {% for item in site.nav %}
    <a href="{{ item.link }}" 
      {% if page.url == item.link %} style="color: red;" {% endif %}
    >
      {{ item.name }}
    </a>
  {% endfor %}
</nav>

# blog
