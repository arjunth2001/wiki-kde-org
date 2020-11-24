# wiki.kde.org

A version of https://wiki.kde.org/ that I contributed to KDE Open Source Community, converted to Jekyll Theme. Original Repository at https://invent.kde.org/arjunth/wikis-kde-org

## Build instruction

```
gem install bundler jekyll
bundle install --path vendor/bundle
```

## Run development

```
bundle exec jekyll serve
```

## Run production

```
bundle exec jekyll build
```

The configuration are located in `_config.yml`. You should also change the path to the theme in Gemfile
