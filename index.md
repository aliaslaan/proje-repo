---
layout: default
---

# Proje İlerleme Raporları

Bu blog, **Sistem Analizi ve Tasarımı** dersi kapsamında geliştirilen **Depo Stok Kayıt - Takip Otomasyonu** projesinin haftalık gelişim sürecini takip etmek amacıyla oluşturulmuştur.

## Son Güncellemeler

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
*{{ post.date | date: "%-d %B %Y" }}*  
{{ post.excerpt | strip_html | truncatewords: 30 }}
<hr>
{% endfor %}

[Hakkında Sayfası]({{ "/about/" | relative_url }})
