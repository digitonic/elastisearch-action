# ElasticSearch GitHub Action

This [GitHub Action](https://github.com/features/actions) sets up ElasticSearch instance.

Inspired by https://github.com/zhulik/redis-action, @zhulik Thanks!

# Usage

See [action.yml](action.yml)

Basic:
```yaml
steps:
- uses: digitonic/elastisearch-action@0.0.
  with:
    elesticsearch-version: '6.3.1'
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
