# Docker image for PHP 5.6.lastest

A powerful yet highly customizable image for PHP 5.6.lastest FPM & CLI

## Features

- Based on CentOS 7
- PHP 5.6.lastest
- Both FPM & CLI
- Easy to customize

## PHP Extensions

- `mysqlnd` (`mysql`/`mysqli`/`pdo` included)
- `gd`
- `mcrypt`
- `mbstring`
- `pecl-memcache`
- `pecl-memcached`
- `opcache`
- ... (Very easy to install any other extensions)

## Defaults

- Volume: `/opt/www`
- Port: `9000`
- PHP Timezone: `PRC` (China)

## Why not based on the official PHP image?

- Hard to install extensions
- Hard to customize
- Too many versions