# SASSLint Config

[![Build Status](https://travis-ci.org/troyblank/sasslint-config.svg?branch=master)](https://travis-ci.org/troyblank/eslint-config)

This is a central location to keep sass linting shared amongst all of the projects.

## Requirements

* npm >= 3.8.3

### Usage
In your project configure any flavor of sasslint to use the contained configure file:

```
configFile: 'node_modules/@troyblank/sasslint-config-troyblank/.sass-lint.yml'
```

### Test

    npm run lint
