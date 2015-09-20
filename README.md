# Gollum on Heroku
auto generated git powered wiki ([Gollum](https://github.com/gollum/gollum)) for Heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

# Use Deploy to Heroku button

* Click Deploy to Heroku button
* Fill App name
* Fill environment variables

| variable | requirement | description | 
| -------- | ----------- | ----------- |
| GIT_REPO_URL_1 | true | e.g https://github.com/naoa/test.git https://github.com/naoa/test.wiki|
| GIT_REPO_URL_2~  |  |  |
| GITHUB_TOKEN |  | need this if update from heroku |
| AUTHOR_NAME |  |  |
| AUTHOR_EMAIL |  |  |
| BASIC_AUTH_USERNAME |  |  |
| BASIC_AUTH_PASSWORD |  |  |
| GOLLUM_UNIVERSAL_TOC |  |  |
| GOLLUM_ALLOW_EDITING |  |  |
| GOLLUM_LIVE_PREVIEW |  |  |
| GOLLUM_ALLOW_UPLOADS |  |  |
| GOLLUM_SHOW_ALL |  |  |
| GOLLUM_COLLAPSE_TREE |  |  |
| GOLLUM_H1_TITLE |  |  |
| GOLLUM_USER_ICONS |  |  |
| GOLLUM_CSS |  |  |
| GOLLUM_JS |  |  |
| GOLLUM_TEMPLATE_DIR |  |  |

* Access to https://[App name].herokuapp.com/[GIT_REPO_URL_[0-9]+]

# Use local

```
bundle exec rackup config.ru
```