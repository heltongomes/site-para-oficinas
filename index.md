---
title: Home
---

# Um site feito com Jekyll e GitHub Pages

## Conteúdo:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

> built using [Jekyll](https://jekyllrb.com/), [GitHub Pages](https://pages.github.com/), and [workshop-template](https://github.com/evanwill/workshop-template).
>
> licensed cc-by-sa <a href="https://github.com/tonidandel">Danny Tonidandel</a> {{ site.pub_year }}. (get [source code]({{ site.repo }}))
> 
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
