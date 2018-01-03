We took the legacy app.buzzn.net offline when it's SSL certificate expired. This is a temporary notice/placeholder HTML page until we release the new admin.buzzn.io and display.buzzn.io apps.

**How to configure**

This repository is hosted on heroku using [heroku-buildpack-static](https://github.com/keepworks/heroku-buildpack-static). Some aspects of the application can be configured with the file static.json.

**How to deploy**

1. Add the git remote for Heroku, once:
   `git remote add heroku https://git.heroku.com/app-buzzn-net.git`
2. Then simply `git push heroku`.