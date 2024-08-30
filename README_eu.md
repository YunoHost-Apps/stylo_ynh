<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Stylo YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/stylo.svg)](https://ci-apps.yunohost.org/ci/apps/stylo/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/stylo.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/stylo.maintain.svg)

[![Instalatu Stylo YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stylo)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Stylo YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Stylo is a text editor for scientific articles in the humanities and social sciences.

### Features

- a metadata editor
- versioning
- bibliography management
- different export formats: html5, xml (TEI, Erudit), pdf...
- the annotation
- document sharing

**Paketatutako bertsioa:** 3.0.6~ynh1

**Demoa:** <https://stylo.huma-num.fr/>

## Pantaila-argazkiak

![Stylo(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://stylo.huma-num.fr/>
- Erabiltzaileen dokumentazio ofiziala: <https://stylo-doc.ecrituresnumeriques.ca/fr_FR/#!index.md>
- Administratzaileen dokumentazio ofiziala: <https://github.com/EcrituresNumeriques/stylo/blob/master/HOWTO.md>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/EcrituresNumeriques/stylo/>
- YunoHost Denda: <https://apps.yunohost.org/app/stylo>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/stylo_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/stylo_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stylo_ynh/tree/testing --debug
edo
sudo yunohost app upgrade stylo -u https://github.com/YunoHost-Apps/stylo_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
