<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Sharkey pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/sharkey.svg)](https://ci-apps.yunohost.org/ci/apps/sharkey/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/sharkey.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/sharkey.maintain.svg)

[![Installer Sharkey avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sharkey)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Sharkey rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

## 🌎 Une plateforme de microblogging 🦈🚀 

_Sharkey_ est un fork de Misskey qui suit les changements en amont lorsque c'est possible, avec des fonctionnalités supplémentaires !

### ⚠️ A LIRE ATTENTIVEMENT ⚠️

Attention **Sharkey** nécessite la version **7** de **redis** hors YunoHost ne permet pas actuellement de bénéficier de cette version.
Certaines fonctions ne seront pas disponible si vous installez ce package.

Je vous conseille d'attendre la sortie de _Bookworm_ Debian 12.


**Version incluse :** 2024.8.2~ynh1

## Captures d’écran

![Capture d’écran de Sharkey](./doc/screenshots/screenshot-desktop.png)

## Documentations et ressources

- Site officiel de l’app : <https://git.joinsharkey.org/Sharkey>
- Dépôt de code officiel de l’app : <https://activitypub.software/TransFem-org/Sharkey>
- YunoHost Store : <https://apps.yunohost.org/app/sharkey>
- Signaler un bug : <https://github.com/YunoHost-Apps/sharkey_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
ou
sudo yunohost app upgrade sharkey -u https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
