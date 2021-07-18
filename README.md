# clone GitHub

I read [this article](https://www.wired.com/2015/06/problem-putting-worlds-code-github/) and thought, "perhaps I should make it easy to back up GitHub repos, just in case".

## running this

1. Install [Bundler](https://bundler.io/) (which requires Ruby)
2. Make yourself a [personal GitHub access token](https://github.com/settings/tokens) and write it down
3. Run `bundle install` in this directory

And then:

```sh
CLONE_GITHUB_TOKEN='your personal github access token' ./clone-github username1 username2 username3
```

Pow pow!
