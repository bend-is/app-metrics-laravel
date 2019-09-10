<p align="center">
  <img src="https://laravel.com/assets/img/components/logo-laravel.svg" alt="Laravel" width="240" />
</p>

# Application Metrics endpoint for Laravel applications

[![Version][badge_packagist_version]][link_packagist]
[![Version][badge_php_version]][link_packagist]
[![Build Status][badge_build_status]][link_build_status]
[![Coverage][badge_coverage]][link_coverage]
[![Downloads count][badge_downloads_count]][link_packagist]
[![License][badge_license]][link_license]

Using this package provides easy way for integration metrics endpoint into your Illuminate-based application.

## Install

Require this package with composer using the following command:

```shell
$ composer require avto-dev/app-metrics-laravel "^1.0"
```

> Installed `composer` is required ([how to install composer][getcomposer]).

> You need to fix the major version of package.

## Usage

...

### Testing

For package testing we use `phpunit` framework and `docker-ce` + `docker-compose` as develop environment. So, just write into your terminal after repository cloning:

```bash
$ make build
$ make latest # or 'make lowest'
$ make test
```

## Changes log

[![Release date][badge_release_date]][link_releases]
[![Commits since latest release][badge_commits_since_release]][link_commits]

Changes log can be [found here][link_changes_log].

## Support

[![Issues][badge_issues]][link_issues]
[![Issues][badge_pulls]][link_pulls]

If you will find any package errors, please, [make an issue][link_create_issue] in current repository.

## License

This is open-sourced software licensed under the [MIT License][link_license].

[badge_packagist_version]:https://img.shields.io/packagist/v/avto-dev/app-metrics-laravel.svg?maxAge=180
[badge_php_version]:https://img.shields.io/packagist/php-v/avto-dev/app-metrics-laravel.svg?longCache=true
[badge_build_status]:https://travis-ci.org/avto-dev/app-metrics-laravel.svg?branch=master
[badge_coverage]:https://img.shields.io/codecov/c/github/avto-dev/app-metrics-laravel/master.svg?maxAge=60
[badge_downloads_count]:https://img.shields.io/packagist/dt/avto-dev/app-metrics-laravel.svg?maxAge=180
[badge_license]:https://img.shields.io/packagist/l/avto-dev/app-metrics-laravel.svg?longCache=true
[badge_release_date]:https://img.shields.io/github/release-date/avto-dev/app-metrics-laravel.svg?style=flat-square&maxAge=180
[badge_commits_since_release]:https://img.shields.io/github/commits-since/avto-dev/app-metrics-laravel/latest.svg?style=flat-square&maxAge=180
[badge_issues]:https://img.shields.io/github/issues/avto-dev/app-metrics-laravel.svg?style=flat-square&maxAge=180
[badge_pulls]:https://img.shields.io/github/issues-pr/avto-dev/app-metrics-laravel.svg?style=flat-square&maxAge=180
[link_releases]:https://github.com/avto-dev/app-metrics-laravel/releases
[link_packagist]:https://packagist.org/packages/avto-dev/app-metrics-laravel
[link_build_status]:https://travis-ci.org/avto-dev/app-metrics-laravel
[link_coverage]:https://codecov.io/gh/avto-dev/app-metrics-laravel/
[link_changes_log]:https://github.com/avto-dev/app-metrics-laravel/blob/master/CHANGELOG.md
[link_issues]:https://github.com/avto-dev/app-metrics-laravel/issues
[link_create_issue]:https://github.com/avto-dev/app-metrics-laravel/issues/new/choose
[link_commits]:https://github.com/avto-dev/app-metrics-laravel/commits
[link_pulls]:https://github.com/avto-dev/app-metrics-laravel/pulls
[link_license]:https://github.com/avto-dev/app-metrics-laravel/blob/master/LICENSE
[getcomposer]:https://getcomposer.org/download/