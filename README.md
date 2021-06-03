# Example app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/example.svg)](https://dash.yunohost.org/appci/app/example) ![](https://ci-apps.yunohost.org/ci/badges/example.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/example.maintain.svg)  
[![Install Example app with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Example app quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Automatic TV shows downloader

**Shipped version:** 0.5.12~ynh1



## Screenshots

![](./doc/screenshots/home.jpg)

## Documentation and resources

* Official app website: https://pymedusa.com/
* Upstream app code repository: https://github.com/pymedusa/Medusa
* YunoHost documentation for this app: https://yunohost.org/app_example
* Report a bug: https://github.com/YunoHost-Apps/example_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
or
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps