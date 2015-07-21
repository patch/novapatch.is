<hr style="margin-top: 1.5em">
{% capture bio %}
*{{ site.title }} ({% include twitter.html %}) is software engineer on the
International Search team at [Shutterstock](http://tech.shutterstock.com/),
specializing in internationalization, localization, and multilingual search; and
focusing on developing a search and discovery experience that supports the
world’s languages, writing systems, and cultures. They are an open source
developer, contributor to the Unicode CLDR, and member of the Unicode
Consortium.*
{% endcapture %}
{{ bio | markdownify }}
