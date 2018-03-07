## Local development

### Required software

* Ruby 2.5.0
* Ruby on Rails 5.1.5
* PostgreSQL 9.5 or later

### Database setup

```shell
bin/rails db:setup
```

### Run Specs (Tests)

```shell
bundle exec rspec

bundle exec rspec <file>

bundle exec rspec <file>:<line_number>
-> Run the nearest spec from the specified line number.
```
> Using keyboard shortcut is recommended.
