# SoapboxFE pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/soapbox.svg)](https://dash.yunohost.org/appci/app/soapbox) ![](https://ci-apps.yunohost.org/ci/badges/soapbox.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/soapbox.maintain.svg)  
[![Installer SoapboxFE avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=soapbox)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer SoapboxFE rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

SoapboxFE is an alternative frontend for Pleroma.


**Version incluse :** 1.3.0~ynh1



## Captures d'écran

![](./doc/screenshots/screenshot.jpg)

## Avertissements / informations importantes

### Important points to read before installing

- [Pleroma (Yunohost ver.)](https://github.com/YunoHost-Apps/pleroma_ynh) must be installed locally before you install SoapboxFE
- SoapboxFE must be installed under a Pleroma domain (i.e soapboxfe.your-pleroma-instance-domain.net)
- AdminFE under SoapboxFE returns 404

Using screen in case of disconnects

``` 
sudo apt-get install screen
screen
sudo yunohost app install https://github.com/YunoHost-Apps/soapbox_ynh.git
```
Recover after disconnect:
```
screen -d
screen -r
```

## Documentations et ressources

* Site officiel de l'app : https://soapbox.pub/
* Documentation officielle de l'admin : https://docs.soapbox.pub/
* Dépôt de code officiel de l'app : https://gitlab.com/soapbox-pub/soapbox-fe
* Documentation YunoHost pour cette app : https://yunohost.org/app_soapbox
* Signaler un bug : https://github.com/YunoHost-Apps/soapbox_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/soapbox_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/soapbox_ynh/tree/testing --debug
ou
sudo yunohost app upgrade soapbox -u https://github.com/YunoHost-Apps/soapbox_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps