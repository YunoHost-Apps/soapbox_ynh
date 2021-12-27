# SoapboxFE pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/soapbox.svg)](https://dash.yunohost.org/appci/app/soapbox) ![](https://ci-apps.yunohost.org/ci/badges/soapbox.status.svg)  ![](https://ci-apps.yunohost.org/ci/badges/soapbox.maintain.svg)
[![Installer soapbox avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=soapbox)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install soapbox quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Vue d'ensemble

SoapboxFE est un frontal alternatif pour Pleroma.

**Version incluse:** 1.3.0~ynh1

## Captures d'écran

![](./doc/screenshots/screenshot.jpg)

## Avertissements / informations importantes
- [Pleroma (Yunohost)](https://github.com/YunoHost-Apps/pleroma_ynh) doit être installé avant l'installation de cette application.
- SoapboxFE must be installed under a Pleroma domain (i.e soapboxfe.your-pleroma-instance-domain.net)
- AdminFE under SoapboxFE returns 404


## Documentations et ressources

* Site official de l'app: https://soapbox.pub/
* Dépôt de code officiel de l'app: https://gitlab.com/soapbox-pub/soapbox-fe
* Documentation YunoHost pour cette app: https://yunohost.org/app_soapbox
* Signaler un bug: https://github.com/YunoHost-Apps/soapbox_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/soapbox_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/soapbox_ynh/tree/testing --debug
or
sudo yunohost app upgrade soapbox -u https://github.com/YunoHost-Apps/soapbox_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications:** https://yunohost.org/packaging_apps