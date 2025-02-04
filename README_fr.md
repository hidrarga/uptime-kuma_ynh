# Uptime Kuma pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/uptime-kuma.svg)](https://dash.yunohost.org/appci/app/uptime-kuma) ![](https://ci-apps.yunohost.org/ci/badges/uptime-kuma.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/uptime-kuma.maintain.svg)  
[![Installer Uptime Kuma avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Uptime Kuma rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

It is a self-hosted monitoring tool like "Uptime Robot".

### Features

- Monitoring uptime for HTTP(s) / TCP / Ping / DNS Record / Push.
- Fancy, Reactive, Fast UI/UX.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP), and 70+ notification services, click here for the full list.
- 20 second intervals.
- Multi Languages
- Simple Status Page
- Ping Chart
- Certificate Info


**Version incluse :** 1.13.1~ynh1

**Démo :** https://demo.uptime.kuma.pet

## Captures d'écran

![](./doc/screenshots/example.jpg)

## Avertissements / informations importantes

- Requires a full dedicated domain
- node_modules folder is backed up and shouldn't be (600Mo...)
- ARM architecture not supported
- This app needs a manual post-install
- Uses N to install specific nodejs version
- We could pre-configure mail notifications with YunoHost mail server as an improvement. See comments in file to try to do it with Curl and WebSockets or Sqlite.

## Documentations et ressources

* Site officiel de l'app : https://uptime.kuma.pet/
* Documentation officielle utilisateur : https://github.com/louislam/uptime-kuma/wiki
* Documentation officielle de l'admin : https://github.com/louislam/uptime-kuma/wiki
* Dépôt de code officiel de l'app : https://github.com/louislam/uptime-kuma
* Documentation YunoHost pour cette app : https://yunohost.org/app_uptime-kuma
* Signaler un bug : https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
ou
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps