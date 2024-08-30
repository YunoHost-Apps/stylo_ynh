<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Stylo

[![集成程度](https://dash.yunohost.org/integration/stylo.svg)](https://ci-apps.yunohost.org/ci/apps/stylo/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/stylo.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/stylo.maintain.svg)

[![使用 YunoHost 安装 Stylo](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stylo)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Stylo。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Stylo is a text editor for scientific articles in the humanities and social sciences.

### Features

- a metadata editor
- versioning
- bibliography management
- different export formats: html5, xml (TEI, Erudit), pdf...
- the annotation
- document sharing

**分发版本：** 3.0.6~ynh1

**演示：** <https://stylo.huma-num.fr/>

## 截图

![Stylo 的截图](./doc/screenshots/example.jpg)

## 文档与资源

- 官方应用网站： <https://stylo.huma-num.fr/>
- 官方用户文档： <https://stylo-doc.ecrituresnumeriques.ca/fr_FR/#!index.md>
- 官方管理文档： <https://github.com/EcrituresNumeriques/stylo/blob/master/HOWTO.md>
- 上游应用代码库： <https://github.com/EcrituresNumeriques/stylo/>
- YunoHost 商店： <https://apps.yunohost.org/app/stylo>
- 报告 bug： <https://github.com/YunoHost-Apps/stylo_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/stylo_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stylo_ynh/tree/testing --debug
或
sudo yunohost app upgrade stylo -u https://github.com/YunoHost-Apps/stylo_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
