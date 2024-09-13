<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Sharkey para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/sharkey.svg)](https://ci-apps.yunohost.org/ci/apps/sharkey/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/sharkey.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/sharkey.maintain.svg)

[![Instalar Sharkey con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sharkey)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarSharkey rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

## 🌎 A Sharkish microblogging platform 🦈🚀 

_Sharkey_ is an Misskey fork following upstream changes when possible, with added features!

### ⚠️ PLEASE READ CAREFULLY ⚠️

**Sharkey** requires **redis** version **7**, but YunoHost does not currently support this version.
Some functions will not be available if you install this package.

I advise you to wait for the release of _Bookworm_ Debian 12.


**Versión actual:** 2024.8.1~ynh1

## Capturas

![Captura de Sharkey](./doc/screenshots/screenshot-desktop.png)

## Documentaciones y recursos

- Sitio web oficial: <https://git.joinsharkey.org/Sharkey>
- Repositorio del código fuente oficial de la aplicación : <https://activitypub.software/TransFem-org/Sharkey>
- Catálogo YunoHost: <https://apps.yunohost.org/app/sharkey>
- Reportar un error: <https://github.com/YunoHost-Apps/sharkey_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
o
sudo yunohost app upgrade sharkey -u https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
