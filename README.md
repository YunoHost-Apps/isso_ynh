<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Isso for YunoHost

[![Integration level](https://dash.yunohost.org/integration/isso.svg)](https://dash.yunohost.org/appci/app/isso) ![Working status](https://ci-apps.yunohost.org/ci/badges/isso.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/isso.maintain.svg)

[![Install Isso with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=isso)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Isso quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Isso – *Ich schrei sonst* – is a lightweight commenting server written in Python and JavaScript. It aims to be a drop-in replacement for
[Disqus](http://disqus.com).

### Features

- Comments written in Markdown
- SQLite backend
- Disqus & WordPress Import
- Configurable JS client 

**Shipped version:** 0.13.0~ynh3

**Demo:** https://isso-comments.de

## Screenshots

![Screenshot of Isso](./doc/screenshots/example.jpg)

## Documentation and resources

* Official app website: <https://isso-comments.de>
* Official user documentation: <https://isso-comments.de/docs/reference/client-config/>
* Official admin documentation: <https://isso-comments.de/docs/reference/server-config/>
* Upstream app code repository: <https://github.com/posativ/isso>
* YunoHost Store: <https://apps.yunohost.org/app/isso>
* Report a bug: <https://github.com/YunoHost-Apps/isso_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/isso_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
or
sudo yunohost app upgrade isso -u https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
