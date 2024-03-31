<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Sharkey per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/sharkey.svg)](https://dash.yunohost.org/appci/app/sharkey) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/sharkey.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/sharkey.maintain.svg)

[![Installa Sharkey con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sharkey)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Sharkey su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

## 🌎 A Sharkish microblogging platform 🦈🚀 

_Sharkey_ is an Misskey fork following upstream changes when possible, with added features!

### ⚠️ PLEASE READ CAREFULLY ⚠️

**Sharkey** requires **redis** version **7**, but YunoHost does not currently support this version.
Some functions will not be available if you install this package.

I advise you to wait for the release of _Bookworm_ Debian 12.


**Versione pubblicata:** 2024.3.2~ynh1

## Screenshot

![Screenshot di Sharkey](./doc/screenshots/screenshot-desktop.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://git.joinsharkey.org/Sharkey>
- Repository upstream del codice dell’app: <https://activitypub.software/TransFem-org/Sharkey>
- Store di YunoHost: <https://apps.yunohost.org/app/sharkey>
- Segnala un problema: <https://github.com/YunoHost-Apps/sharkey_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
o
sudo yunohost app upgrade sharkey -u https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
