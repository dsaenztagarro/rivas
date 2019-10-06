# README

### Installation

```
# On macOS with Homebrew:
#   gem install pg -- --with-pg-config=/usr/local/bin/pg_config
```

#### Heroku commands

```
heroku ps:scale web=1
heroku ps
heroku open
heroku logs
heroku logs --tail
heroku addons
heroku logs -p postgres -t
heroku apps:rename newname
heroku info --app rivas
```

Deploy with: `git push heroku master`
