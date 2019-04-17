# Dekyll

Jekyll theme based on default Jekyll's default style. All configurations are under `_config.yml` file. Dekyll does not compatible with Github Pages and in the future will re-architecture as gem-based theme.

### Demo
* [KAK Labs](https://www.kaklabs.com)
* [Railsmine](https://www.railsmine.net)

### Dependencies
* jekyll 3.8.0
* jekyll-sitemap 1.2.0
* jekyll-seo-tag 2.4.0
* jekyll-paginate-v2 1.9.4

### Features
* Support Jekyll 3
* No Javascript required
* CSS Compression
* Related articles
* Responsive
* Support pagination
* Sitemap
* Social media sharing buttons
* Google Analytic and Disqus
* Jekyll SEO tag
* Pagination on Category and Tag pages

### How to Build
Google Analytic and Disqus are only rendered in production environment, you must set `JEKYLL_ENV=production` when building Dekyll.

```
JEKYLL_ENV=production jekyll build
```
