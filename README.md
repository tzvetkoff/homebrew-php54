# homebrew-php54

PHP 5.4 formulae micro-repo

## Why?

There is an existing [PHP repository](https://github.com/josegonzalez/homebrew-php) that provides 5.4 via `--devel` option, but it's old. At the time of creating this repo, PHP is of version 5.4.3, and it *will* update, so the key objective was to provide an up-to-date PHP formula.

For the moment, the repository does not contain any PHP extensions - they can be easily installed with `phpize` and then manually added to `php.ini`.

## How to install?

Open your favorite terminal and type:

    $ brew tap tzvetkoff/php54
    $ brew install php

## List of formulae
`php`
`phpsh`
