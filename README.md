# heroku-buildpack-geoipdata
a simple Heroku buildpack that downloads a geo ip data database file to go along with your build

Looks at your Heroku config and either downloads from a s3 repo/path or from MaxMind if not found.
Adds this file to your Heroku build.