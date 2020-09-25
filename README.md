# jekyll-travis-ci-integration-test
https://github.com/jekyll/jekyll/blob/master/docs/_docs/continuous-integration/travis-ci.md

We do not need to use `NOKOGIRI_USE_SYSTEM_LIBRARIES` to make CI build faster.

> If a branch does not have its own cache, Travis CI fetches the default branch cache.

from https://docs.travis-ci.com/user/caching/#fetching-and-storing-caches
