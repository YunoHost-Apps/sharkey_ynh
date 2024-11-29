<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Sharkey dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/sharkey)](https://ci-apps.yunohost.org/ci/apps/sharkey/)
![Status działania](https://apps.yunohost.org/badge/state/sharkey)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/sharkey)

[![Zainstaluj Sharkey z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sharkey)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Sharkey na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

## 🌎 A Sharkish microblogging platform 🦈🚀 

_Sharkey_ is an Misskey fork following upstream changes when possible, with added features!

### ⚠️ PLEASE READ CAREFULLY ⚠️

**Sharkey** requires **redis** version **7**, but YunoHost does not currently support this version.
Some functions will not be available if you install this package.

I advise you to wait for the release of _Bookworm_ Debian 12.


**Dostarczona wersja:** 2024.9.4~ynh1

## Zrzuty ekranu

![Zrzut ekranu z Sharkey](./doc/screenshots/screenshot-desktop.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://git.joinsharkey.org/Sharkey>
- Repozytorium z kodem źródłowym: <https://activitypub.software/TransFem-org/Sharkey>
- Sklep YunoHost: <https://apps.yunohost.org/app/sharkey>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/sharkey_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
lub
sudo yunohost app upgrade sharkey -u https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
