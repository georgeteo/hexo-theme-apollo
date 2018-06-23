![hexo-theme-apollo](https://cloud.githubusercontent.com/assets/9530963/13026956/08e76eca-d277-11e5-8bfc-2e80cea20a0d.png)

Forked from [wicksome](https://github.com/wicksome/hexo-theme-apollo) and [pinggod](https://github.com/pinggod/hexo-theme-apollo).

## Using with Hexo

``` bash
hexo init Blog
cd Blog
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git clone https://github.com/pinggod/hexo-theme-apollo.git themes/apollo
```

## Configuration

Update `_config.yml` in Hexo project:

```yaml
theme: apollo

archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## License

MIT
