# 测试模板

{% for author in book.authors %}
  - {{ author.name }}
{% endfor %}