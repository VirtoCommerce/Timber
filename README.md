Virto Commerce Timber (based on Shopify Timber)
=====================

Timber is a theme framework for Virto Commerce that helps you get your store up and running quickly. It provides all required theme templates, a starter set of liquid tags, and some basic styles and modules for you to extend on.

Styling and customization is left up to you. Some base styles and helpers are included, but there is **no need to remove any code before you start**. Simply download and get designing.

Ways to Get Started
---------------------
- Download the [latest release](https://github.com/VirtoCommerce/Timber/releases)
- Clone the repo `git clone https://github.com/VirtoCommerce/Timber.git`

Documentation
---------------------
Visit the [Timber's Documentation](http://virtocommerce.github.io/timber) page to find out more about the templates, liquid tags, CSS framework, and JavaScript modules included.

Timber's documentation is hosted on [GitHub Pages](http://pages.github.com/). View the raw files in the [gh-pages branch](https://github.com/VirtoCommerce/Timber/tree/gh-pages). Please report any discrepancies, bugs, or requests in [issues](https://github.com/VirtoCommerce/Timber/issues).

Demo Stores
---------------------

For a set of demo products to use during development, [download this CSV file](http://www.tetchi.ca/wp-content/uploads/2013/04/products1.csv) and import it on our products page.

Basic structure
---------------
```
├── assets
│   └── Javascript, CSS, and theme images
├── layout
│   ├── theme.liquid
│   └── optional alternate layouts
├── snippets
│   └── custom code snippets
├── spec
│   └── tests and helpers
├── templates
│   ├── 404.liquid
│   ├── article.liquid
│   ├── blog.liquid
│   ├── cart.liquid
│   ├── collection.liquid
│   ├── collection.list.liquid
│   ├── index.liquid
│   ├── list-collections.liquid
│   ├── page.contact.liquid
│   ├── page.liquid
│   ├── product.liquid
│   ├── search.liquid
│   └── customers
│         └── required templates if customer accounts are enabled
├── config.yml
│   └── if using the theme gem (see link under Additional Resources)
```


Additional resources
---------------------
- [Themes Documentation][1]: Learn more about Liquid and theme templates.
- [Liquid Tag Cheat Sheet][2]

License
---------------------
Timber is released under the [MIT License](LICENSE).

[1]: http://docs.virtocommerce.com
[2]: http://cheat.markdunkley.com
