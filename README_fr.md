<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Kresus pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/kresus)](https://ci-apps.yunohost.org/ci/apps/kresus/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/kresus)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/kresus)

[![Installer Kresus avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kresus)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Kresus rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Kresus est un gestionnaire de finances personnelles gratuit et libre qui tourne sur votre serveur. Il récupère automatiquement et quotidiennement toutes vos nouvelles transactions bancaires et vous permet de les catégoriser, étudier via des graphiques, et établir un budget.


**Version incluse :** 0.22.1~ynh2

**Démo :** <https://kresus.org/en/demo.html>

## Captures d’écran

![Capture d’écran de Kresus](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://kresus.org>
- Documentation officielle de l’admin : <https://kresus.org/en/doc.html>
- Dépôt de code officiel de l’app : <https://framagit.org/kresusapp/kresus>
- YunoHost Store : <https://apps.yunohost.org/app/kresus>
- Signaler un bug : <https://github.com/YunoHost-Apps/kresus_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/kresus_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kresus_ynh/tree/testing --debug
ou
sudo yunohost app upgrade kresus -u https://github.com/YunoHost-Apps/kresus_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
