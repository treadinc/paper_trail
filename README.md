# NOTE: this should no longer be necessary as upstream changes have been merged. 

this is a fork of [upstream](https://github.com/paper-trail-gem) with several prs applied:

- https://github.com/paper-trail-gem/paper_trail/pull/1485
- https://github.com/paper-trail-gem/paper_trail/pull/1450

## development notes

if you can't get `bundle install` to work on a mac, try installing `mysql2` manually first:

```
gem install mysql2 -v '0.5.6'  -- --with-opt-dir=$(brew --prefix openssl) --with-ldflags=-L/opt/homebrew/opt/zstd/lib
```
