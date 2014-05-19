# DEPRECATED

GrowlyBird no longer provides the original DMG this module is based on. Using this module is just going to give you errors at this point. If you were using this module, please remove it from your setup.


# Growly Puppet Module for Boxen

[Growly](http://growlybird.com/notes/index.html) for OSX. A Office
OneNote like tool.

[![Build Status](https://travis-ci.org/boxen/puppet-growly.png?branch=master)](https://travis-ci.org/boxen/puppet-growly)

## Usage

```puppet
include growly
```

## Required Puppet Modules

* `boxen`

## Development

Set `GITHUB_API_TOKEN` in your shell with a [Github oAuth
Token](https://help.github.com/articles/creating-an-oauth-token-for-command-line-use)
to raise your API rate limit. You can get some work done without it, but
you're less likely to encounter errors like `Unable to find module
'boxen/puppet-boxen' on https://github.com`.

Then write some code. Run `script/cibuild` to test it. Check the
`script` directory for other useful tools.
