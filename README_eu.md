<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Sharkey YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/sharkey.svg)](https://dash.yunohost.org/appci/app/sharkey) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/sharkey.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/sharkey.maintain.svg)

[![Instalatu Sharkey YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sharkey)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Sharkey YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

## 🌎 A Sharkish microblogging platform 🦈🚀 

_Sharkey_ is an Misskey fork following upstream changes when possible, with added features!

### ⚠️ PLEASE READ CAREFULLY ⚠️

**Sharkey** requires **redis** version **7**, but YunoHost does not currently support this version.
Some functions will not be available if you install this package.

I advise you to wait for the release of _Bookworm_ Debian 12.


**Paketatutako bertsioa:** 2024.3.3~ynh1

## Pantaila-argazkiak

![Sharkey(r)en pantaila-argazkia](./doc/screenshots/screenshot-desktop.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://git.joinsharkey.org/Sharkey>
- Jatorrizko aplikazioaren kode-gordailua: <https://activitypub.software/TransFem-org/Sharkey>
- YunoHost Denda: <https://apps.yunohost.org/app/sharkey>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/sharkey_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
edo
sudo yunohost app upgrade sharkey -u https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
