## gzip-brunch

Adds gzip support to [brunch](http://brunch.io).

The plugin will gzipfy HTML files, JS files and CSS files.

## Usage

Install the plugin via npm with `npm install --save gzip-brunch`.

Or, do manual install:

* Add `"gzip-brunch": "x.y.z"` to `package.json` of your brunch app.
  Pick a plugin version that corresponds to your minor (y) brunch version.
* If you want to use git version of plugin, add
`"gzip-brunch": "git+ssh://git@github.com:banyan/gzip-brunch.git"`.

## Config

To specify gzip options, use `config.plugins.gzip` object, for example:

```coffeescript
config =
  plugins:
    gzip:
      paths:
        javascript: 'javascripts'
        stylesheet: 'stylesheets'
```

### Default

* `gzip.paths.javascript`: 'javascripts'
* `gzip.paths.stylesheet:`: 'stylesheets'

## CHANGELOG

### gzip-brunch 1.0.0 (29 Sep 2013)

* Initial release

## License

The MIT License (MIT)

Copyright (c) 2013 Kohei Hasegawa