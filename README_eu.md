<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Isso YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/isso.svg)](https://dash.yunohost.org/appci/app/isso) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/isso.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/isso.maintain.svg)

[![Instalatu Isso YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=isso)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Isso YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Isso – *Ich schrei sonst* – is a lightweight commenting server written in Python and JavaScript. It aims to be a drop-in replacement for
[Disqus](http://disqus.com).

### Features

- Comments written in Markdown
- SQLite backend
- Disqus & WordPress Import
- Configurable JS client 

**Paketatutako bertsioa:** 0.13.0~ynh3

**Demoa:** <https://isso-comments.de>

## Pantaila-argazkiak

![Isso(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://isso-comments.de>
- Erabiltzaileen dokumentazio ofiziala: <https://isso-comments.de/docs/reference/client-config/>
- Administratzaileen dokumentazio ofiziala: <https://isso-comments.de/docs/reference/server-config/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/posativ/isso>
- YunoHost Denda: <https://apps.yunohost.org/app/isso>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/isso_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/isso_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
edo
sudo yunohost app upgrade isso -u https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
