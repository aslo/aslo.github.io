{% for link in site.data.links %}
  * {: .pull-left} [{{ link.name }}]({{ link.url }})
{% endfor %} {: .footer-ul .alignable}

---

This site was built using [jekyll](https://jekyllrb.com/), with typography and layouts 
borrowed from the [researcher](https://github.com/bk2dcradle/researcher) theme.
Source is on [github]({{ site.source_repository }}).
{: .small}
