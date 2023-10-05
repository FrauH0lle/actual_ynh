<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Actual for YunoHost

[![Integration level](https://dash.yunohost.org/integration/actual.svg)](https://dash.yunohost.org/appci/app/actual) ![Working status](https://ci-apps.yunohost.org/ci/badges/actual.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/actual.maintain.svg)

[![Install Actual with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=actual)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Actual quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Actual is a local-first personal finance tool. It is 100% free and open-source, written in NodeJS, it has a synchronization element so that all your changes can move between devices without any heavy lifting.

**Shipped version:** 23.10.0~ynh1

## Screenshots

![Screenshot of Actual](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official admin documentation: <https://actualbudget.github.io/docs/>
* Upstream app code repository: <https://github.com/actualbudget/actual-server>
* Report a bug: <https://github.com/YunoHost-Apps/actual_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/actual_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/actual_ynh/tree/testing --debug
or
sudo yunohost app upgrade actual -u https://github.com/YunoHost-Apps/actual_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
