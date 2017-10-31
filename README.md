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

### SEO hint

Use [Metatag](https://www.drupal.org/project/metatag) module for add _only right_ META information to your site. This is trust way to grow up position in Google, Yandex, etc.

### Install

* Download [ZIP with module](https://github.com/koddr/unset_html_head_link/archive/master.zip), unpack and upload to ``./modules/`` folder in your server.
* Enable this module at ``/admin/modules`` (look in ``Search engine optimization`` pack).
* _Don't forget to flush cache!_

### Author & maintainers

Development and maintenance engaged by [Vic Shóstak](https://github.com/koddr) (aka Koddr).
If you want to say «thank you» and/or ask me about `Unset HTML head link` — [create new issue](https://github.com/webartisans-org/drupal_8_unset_html_head_link/issues/new).

___
> ### Your assistance will help make project even better!
>
> * [Donate with PayPal](https://www.paypal.me/koddr/9.99usd)
> * [Donate with Yandex.Money](https://money.yandex.ru/to/41001601525977/599)
>
> #### Thanks for supporting!
___

### License

[The MIT License (MIT)](https://github.com/webartisans-org/drupal_8_unset_html_head_link/blob/master/LICENSE)
