---
layout: default
title: 软件
lang: cn
---

# 软件

我们将长期积累的雷达遥感处理方法沉淀为专业软件，服务于冰川与冻土研究、基础设施监测和地表变化分析。以下为星合工作室的软件产品。

<div class="software-list">
{% for item in site.data.software %}
  {% include software-card.html item=item lang="cn" %}
{% endfor %}
</div>
