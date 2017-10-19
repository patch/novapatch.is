<hr style="margin-top: 1.5em">
{% capture bio %}
*{{ site.title }} ({% include twitter.html %}) is a principal engineer at
[Shutterstock](http://www.shutterstock.com/), specializing in
internationalization, multilingual search, and building products that support
the world’s languages, writing systems, and cultures. They are an open source
developer, contributor to the Unicode CLDR, and member of the Unicode
Consortium.*
{% endcapture %}
{{ bio | markdownify }}
