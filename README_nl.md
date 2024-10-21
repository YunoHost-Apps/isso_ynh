<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Isso voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/isso.svg)](https://ci-apps.yunohost.org/ci/apps/isso/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/isso.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/isso.maintain.svg)

[![Isso met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=isso)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Isso snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Isso – *Ich schrei sonst* – is a lightweight commenting server written in Python and JavaScript. It aims to be a drop-in replacement for
[Disqus](http://disqus.com).

### Features

- Comments written in Markdown
- SQLite backend
- Disqus & WordPress Import
- Configurable JS client 

**Geleverde versie:** 0.13.0~ynh5

**Demo:** <https://isso-comments.de>

## Schermafdrukken

![Schermafdrukken van Isso](./doc/screenshots/example.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://isso-comments.de>
- Officiele gebruikersdocumentatie: <https://isso-comments.de/docs/reference/client-config/>
- Officiele beheerdersdocumentatie: <https://isso-comments.de/docs/reference/server-config/>
- Upstream app codedepot: <https://github.com/posativ/isso>
- YunoHost-store: <https://apps.yunohost.org/app/isso>
- Meld een bug: <https://github.com/YunoHost-Apps/isso_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/isso_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
of
sudo yunohost app upgrade isso -u https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
