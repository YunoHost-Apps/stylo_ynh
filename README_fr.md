<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Stylo pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/stylo.svg)](https://ci-apps.yunohost.org/ci/apps/stylo/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/stylo.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/stylo.maintain.svg)

[![Installer Stylo avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stylo)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Stylo rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Stylo est un éditeur de textes pour articles scientifiques en sciences humaines et sociales.

### Features

- un éditeur de métadonnées
- un versionnage
- une gestion de la bibliographie
- différents formats exports : html5, xml (TEI, Erudit), pdf...
- l'annotation
- le partage de document


**Version incluse :** 3.0.6~ynh1

**Démo :** <https://stylo.huma-num.fr/>

## Captures d’écran

![Capture d’écran de Stylo](./doc/screenshots/example.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://stylo.huma-num.fr/>
- Documentation officielle utilisateur : <https://stylo-doc.ecrituresnumeriques.ca/fr_FR/#!index.md>
- Documentation officielle de l’admin : <https://github.com/EcrituresNumeriques/stylo/blob/master/HOWTO.md>
- Dépôt de code officiel de l’app : <https://github.com/EcrituresNumeriques/stylo/>
- YunoHost Store : <https://apps.yunohost.org/app/stylo>
- Signaler un bug : <https://github.com/YunoHost-Apps/stylo_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/stylo_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stylo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade stylo -u https://github.com/YunoHost-Apps/stylo_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
