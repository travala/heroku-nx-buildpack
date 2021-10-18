# Heroku nx buildpack

## Usage

Just add it to `app.json` definition, like:

```json
 {
  "buildpacks": [
    { "url": "heroku/nodejs"},
    { "url":  "https://github.com/travala/heroku-nx-buildpack.git" }
  ]
}
```

Note: this buildpack should be added after nodejs buildpack