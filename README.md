# Rails Application Templates

My Rails application templates

## Usage

```
mkdir YOUR_RAILS_PROJECT && cd YOUR_RAILS_PROJECT
bundle init # And Remove rails gem comment
bundle install --path vendor/bundle --jobs=4
```

for postgres

```
bundle exec rails new . --database=postgresql --skip-test-unit --skip-turbolinks -m https://gitlab.fusic.co.jp/team-fake/rails-application-templates/raw/master/rails4_template.rb
```

for mysql

```
bundle exec rails new . --database=mysql --skip-test-unit --skip-turbolinks -m https://gitlab.fusic.co.jp/team-fake/rails-application-templates/raw/master/rails4_template.rb
```
