---
layout: mypost
title: Links
---

欢迎各位朋友与我建立友友情链，如需友链请到[Bullentin Board](chat.html)留言，我看到留言后会添加上的，本站的友情链接信息如下

```
名称：{{ site.title }}
描述：{{ site.description }}
地址：{{ site.domainUrl }}{{ site.baseurl }}
头像：{{ site.domainUrl }}{{ site.baseurl }}/static/img/logo.jpg
```

Link Exchange:

<ul>
  {%- for link in site.links %}
  <li>
    <p><a href="{{ link.url }}" title="{{ link.desc }}" target="_blank" >{{ link.title }}</a></p>
  </li>
  {%- endfor %}
</ul>
