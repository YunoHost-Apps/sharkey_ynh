<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Sharkey untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/sharkey)](https://ci-apps.yunohost.org/ci/apps/sharkey/)
![Status kerja](https://apps.yunohost.org/badge/state/sharkey)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/sharkey)

[![Pasang Sharkey dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sharkey)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Sharkey secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

## 🌎 A Sharkish microblogging platform 🦈🚀 

_Sharkey_ is an Misskey fork following upstream changes when possible, with added features!

### ⚠️ PLEASE READ CAREFULLY ⚠️

**Sharkey** requires **redis** version **7**, but YunoHost does not currently support this version.
Some functions will not be available if you install this package.

I advise you to wait for the release of _Bookworm_ Debian 12.


**Versi terkirim:** 2024.9.4~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Sharkey](./doc/screenshots/screenshot-desktop.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://git.joinsharkey.org/Sharkey>
- Depot kode aplikasi hulu: <https://activitypub.software/TransFem-org/Sharkey>
- Gudang YunoHost: <https://apps.yunohost.org/app/sharkey>
- Laporkan bug: <https://github.com/YunoHost-Apps/sharkey_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
atau
sudo yunohost app upgrade sharkey -u https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
