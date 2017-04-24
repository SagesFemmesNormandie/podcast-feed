---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

# Cloudstitch Podcast Example

This project helps you create the easiest podcast hosting site imaginable. Once set up, you can manage the podcast entirely from Google Drive or Microsoft OneDrive:

* Just drag MP3 files into the `audio/` folder
* Then add a new episode to your spreadsheet

## My Podcast URL

This site is already hosting a podcast! The URL is:

{% capture siteurl %}{% if site.github.url %}{{ site.github.url }}{% else %}{{ site.url }}{% endif %}{% endcapture %}
<a href="{{ siteurl }}/feed.xml">{{ siteurl }}/feed.xml</a>

