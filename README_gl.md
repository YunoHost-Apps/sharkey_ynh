<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Sharkey para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/sharkey)](https://ci-apps.yunohost.org/ci/apps/sharkey/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/sharkey)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/sharkey)

[![Instalar Sharkey con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sharkey)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Sharkey de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

## 🌎 A Sharkish microblogging platform 🦈🚀 

_Sharkey_ is an Misskey fork following upstream changes when possible, with added features!

### ⚠️ PLEASE READ CAREFULLY ⚠️

**Sharkey** requires **redis** version **7**, but YunoHost does not currently support this version.
Some functions will not be available if you install this package.

I advise you to wait for the release of _Bookworm_ Debian 12.


**Versión proporcionada:** 2024.9.4~ynh1

## Capturas de pantalla

![Captura de pantalla de Sharkey](./doc/screenshots/screenshot-desktop.png)

## Documentación e recursos

- Web oficial da app: <https://git.joinsharkey.org/Sharkey>
- Repositorio de orixe do código: <https://activitypub.software/TransFem-org/Sharkey>
- Tenda YunoHost: <https://apps.yunohost.org/app/sharkey>
- Informar dun problema: <https://github.com/YunoHost-Apps/sharkey_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
ou
sudo yunohost app upgrade sharkey -u https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
