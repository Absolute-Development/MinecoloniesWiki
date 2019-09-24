---
title: hastebin-paste Wiki
layout: default
---
# Welcome to the hastebin-paste Wiki!

### About

hastebin-paste is a free npm package for everyone to use!

---

<div class="row">
{% for item in site.data.subnav.subnav %}
    <div class="col-lg col-md-3 col-sm-12 text-center">
        <h3 class="button p-1">{{ item.title }}</h3>
        {% for entry in item.subitems %}
            <a class="" href="{{ entry.url | relative_url }}">{{ entry.page }}</a><br />
        {% endfor %}
    </div>
{% endfor %}
</div>

---

hastebin-paste is a free and open source npm package developed by Absolute Development (AD), a non-profit community. The source code is available on [GitHub](https://github.com/Absolute-Development/hastebin-paste).  But we are always looking for more people to contribute to our project! Found any bugs? Report it as an [issue](https://github.com/Absolute-Development/hastebin-paste/issues/new) to help us ensure you have the best coding experience.
