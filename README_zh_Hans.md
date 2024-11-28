<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Sharkey

[![集成程度](https://apps.yunohost.org/badge/integration/sharkey)](https://ci-apps.yunohost.org/ci/apps/sharkey/)
![工作状态](https://apps.yunohost.org/badge/state/sharkey)
![维护状态](https://apps.yunohost.org/badge/maintained/sharkey)

[![使用 YunoHost 安装 Sharkey](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sharkey)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Sharkey。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

## 🌎 A Sharkish microblogging platform 🦈🚀 

_Sharkey_ is an Misskey fork following upstream changes when possible, with added features!

### ⚠️ PLEASE READ CAREFULLY ⚠️

**Sharkey** requires **redis** version **7**, but YunoHost does not currently support this version.
Some functions will not be available if you install this package.

I advise you to wait for the release of _Bookworm_ Debian 12.


**分发版本：** 2024.9.4~ynh1

## 截图

![Sharkey 的截图](./doc/screenshots/screenshot-desktop.png)

## 文档与资源

- 官方应用网站： <https://git.joinsharkey.org/Sharkey>
- 上游应用代码库： <https://activitypub.software/TransFem-org/Sharkey>
- YunoHost 商店： <https://apps.yunohost.org/app/sharkey>
- 报告 bug： <https://github.com/YunoHost-Apps/sharkey_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
或
sudo yunohost app upgrade sharkey -u https://github.com/YunoHost-Apps/sharkey_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
