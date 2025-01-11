# Cache overflow exploration

This repo is meant to be a test bed to assess the behavior of <https://github.com/actions/cache> when we reach the limit of the cache storage. In [CDCgov/cfa-actions](https://github.com/CDCgov/cfa-actions/issues/10), we found an issue where the cache step flagged a cache-hit when there was none.
