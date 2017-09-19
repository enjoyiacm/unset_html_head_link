# Unset HTML head link (Drupal 8.x)

If you want SEO boosting with Drupal 8.x site, we recomended to delete this HTML head links:

```html
<link rel="delete-form" href="/node/1/delete" />
<link rel="edit-form" href="/node/1/edit" />
<link rel="version-history" href="/node/1/revisions" />
<link rel="revision" href="/page-1-name" />
<link rel="canonical" href="http://example.com/" />
```

Support:

* Node
* Taxonomy term

## SEO hint

Use [Metatag](https://www.drupal.org/project/metatag) module for add _only right_ META information to your site. This is trust way to grow up position in Google, Yandex, etc.

## Install

* Download [ZIP with module](https://github.com/koddr/unset_html_head_link/archive/master.zip), unpack and upload to ``./modules/`` folder in your server.
* Enable this module at ``/admin/modules`` (look in ``Search engine optimization`` pack).
* _Don't forget to flush cache!_

## Developers

Development and maintenance of `Unset HTML head link` project engaged by Vikky Shostak ([Koddr](https://koddr.me)). If you want to write a «thank you» or ask us about something, [use this e-mail](mailto:koddr.me@gmail.com).

## Your help

If you want help, we will be glad reviews about `Unset HTML head link` on personal blogs (including Twitter), online media and/or specialized IT-portals. Thank you!
