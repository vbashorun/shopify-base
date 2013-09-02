## Shopify Base.
A really sparse starting point for **Shopify theme development**. The code and guidelines are based on my own requirements.

#### General Guidelines
Always try and keep liquid `output` and `tag`, as close to Shopify's own guidelines as possible. Make use of `filters`.

Use liquid `{% comment %}` where possible as this won't be rendered in the HTML.
Also make use of your `settings.html` file. Add in general wording, theme styles, etc.

Zepto.js with fallback to jQuery is included.

#### Markup Guidelines

`<h1>` should be used for the logo.

`<h2>` should be used for product titles / article titles if its the page directly.

`<h3>` should be used for products / article tiles on an index like page (category / blog page).

`<h4>` should be used for product sub headings, sidebar titles, etc.

`<h5>` should be used for headings in footer.

#### References
* Shopify Theme Guide: [Shopify Theme Guide](http://wiki.shopify.com/Shopify_Theme_Guide)
* Shopify Cheat Sheet: [Shopify Cheat Sheet](http://cheat.markdunkley.com/)
* Shopify Skeleton Theme: [Shopify Skeleton Theme](https://github.com/Shopify/skeleton-theme/)
* HTML5 References: [HTML5 Doctor](http://html5doctor.com/)
* CSS Style Guide: [Idomatic-CSS](https://github.com/necolas/idiomatic-css)
* Javascript Style Guide: [Idomatic-JS](https://github.com/rwldrn/idiomatic.js/)

#### Feel free to download and use.
