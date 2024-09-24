<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Sharkey для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/sharkey.svg)](https://ci-apps.yunohost.org/ci/apps/sharkey/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/sharkey.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/sharkey.maintain.svg)

[![Установите Sharkey с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sharkey)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Sharkey быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

## 🌎 A Sharkish microblogging platform 🦈🚀 

_Sharkey_ is an Misskey fork following upstream changes when possible, with added features!

### ⚠️ PLEASE READ CAREFULLY ⚠️

**Sharkey** requires **redis** version **7**, but YunoHost does not currently support this version.
Some functions will not be available if you install this package.

I advise you to wait for the release of _Bookworm_ Debian 12.


**Поставляемая версия:** 2024.8.2~ynh1

## Снимки экрана

![Снимок экрана Sharkey](./doc/screenshots/screenshot-desktop.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://git.joinsharkey.org/Sharkey>
- Репозиторий кода главной ветки приложения: <https://activitypub.software/TransFem-org/Sharkey>
- Магазин YunoHost: <https://apps.yunohost.org/app/sharkey>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/sharkey_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
или
sudo yunohost app upgrade sharkey -u https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>