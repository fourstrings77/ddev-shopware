[![tests](https://github.com/ddev/ddev-addon-template/actions/workflows/tests.yml/badge.svg)](https://github.com/ddev/ddev-addon-template/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2025.svg)

# DDEV Shopware Addon

## What's this?
This Repo allows usage of the Shopware 6 CLI and watch/build scripts as DDEV commands. Plus Ports for the Admin-Watcher are exposed (thx to susi.dev).

## Installation

For DDEV v1.23.5 or above run

```sh
ddev add-on get fourstrings77/ddev-shopware
```

For earlier versions of DDEV run

```sh
ddev get fourstrings77/ddev-shopware
```

Afterward run `ddev restart`

## Usage after install

After successful installation, you can use the following commands:


Run a Shopwware 6 CLI command - eg Install a plugin:

```sh
ddev sw plugin:install -a <PLUGINNAME>
```

Build or watch Storefront:
```sh
ddev build-storefront
ddev watch-storefront
```
Watched Storefront will be available under: https://your_project.ddev.site:9998


Build or watch Admin
```sh
ddev build-admin
ddev watch-admin
```
Watched Admin will be available under: https://your_project.ddev.site:9997