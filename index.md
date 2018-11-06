---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home

# Make a more human readable title for the project
title: California Counties

---

{{page.title || site.github.project_title}}
===========================================

*{{site.github.project_tagline}}*

{% if site.keywords %}**{{ site.keywords }}** {% endif %}

{% if site.genre %}Genre: {{site.genre}}{% endif %}

{% if site.rights %}
{{ sites.rights }}
Or: {{site.rightsinfo.{{site.rights}}.prefLabel }}

The data for this project is under the [{{ site.rightsinfo.{{site.rights}}.prefLabel }}][{{site.rightsinfo.{{sites.rights}}.url}}]
{% endif %}

{% if site.license %}
This project is released under the [{{site.license.name}}][{{site.license.url}}].
{% endif %}

Distribution
------------
This dataset was last published {{site.datePublished}}, by [{{page.publisher.name }} | {{site.publisher.name }}][publisher]
{% if site.publisher.description %}{{site.publisher.description}}{% endif %}

Please see the project [releases] for direct access to the dataset. You can also vist the project [github] page.

{% for release in site.github.releases %}
  * [{{ release.name }}]({{ release.html_url }}) ({{release.published_at}}) - {{ release.body }}
{% endfor %}

{% if site.author.name | site.author.email %}
Author
------
{{site.author.name}} <{{site.author.email}}>
{% endif %}

Citation
--------

SEO
---

[website]: {{site.github.url}}
[releases]: {{site.github.releases_url}}
[github]: {{site.github.clone_url}}
{% if site.publisher.url %}
[publisher]: {{site.publisher.url}}
{%  endif %}
