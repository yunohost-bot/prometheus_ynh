<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Prometheus for YunoHost

[![Integration level](https://dash.yunohost.org/integration/prometheus.svg)](https://dash.yunohost.org/appci/app/prometheus) ![Working status](https://ci-apps.yunohost.org/ci/badges/prometheus.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/prometheus.maintain.svg)

[![Install Prometheus with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prometheus)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Prometheus quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Monitoring system and time series database

**Shipped version:** 2.42.0~ynh1

**Demo:** https://demo.do.prometheus.io
## Disclaimers / important information

* Port assigned to the app can be read in `/etc/yunohost/apps/prometheus/settings.yml`
 or within CLI with `yunohost app info prometheus --full`
* The app is configurable within the file `/opt/yunohost/prometheus/prometheus.yml`, then reboot the app service.

## Documentation and resources

* Official app website: <https://prometheus.io>
* Official admin documentation: <https://prometheus.io/docs>
* Upstream app code repository: <https://github.com/prometheus/prometheus>
* YunoHost documentation for this app: <https://yunohost.org/app_prometheus>
* Report a bug: <https://github.com/YunoHost-Apps/prometheus_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/prometheus_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/prometheus_ynh/tree/testing --debug
or
sudo yunohost app upgrade prometheus -u https://github.com/YunoHost-Apps/prometheus_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
