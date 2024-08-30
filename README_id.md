<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Stylo untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/stylo.svg)](https://ci-apps.yunohost.org/ci/apps/stylo/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/stylo.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/stylo.maintain.svg)

[![Pasang Stylo dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stylo)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Stylo secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Stylo is a text editor for scientific articles in the humanities and social sciences.

### Features

- a metadata editor
- versioning
- bibliography management
- different export formats: html5, xml (TEI, Erudit), pdf...
- the annotation
- document sharing

**Versi terkirim:** 3.0.6~ynh1

**Demo:** <https://stylo.huma-num.fr/>

## Tangkapan Layar

![Tangkapan Layar pada Stylo](./doc/screenshots/example.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://stylo.huma-num.fr/>
- Dokumentasi pengguna resmi: <https://stylo-doc.ecrituresnumeriques.ca/fr_FR/#!index.md>
- Dokumentasi admin resmi: <https://github.com/EcrituresNumeriques/stylo/blob/master/HOWTO.md>
- Depot kode aplikasi hulu: <https://github.com/EcrituresNumeriques/stylo/>
- Gudang YunoHost: <https://apps.yunohost.org/app/stylo>
- Laporkan bug: <https://github.com/YunoHost-Apps/stylo_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/stylo_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stylo_ynh/tree/testing --debug
atau
sudo yunohost app upgrade stylo -u https://github.com/YunoHost-Apps/stylo_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
