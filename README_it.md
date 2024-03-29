<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Isso per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/isso.svg)](https://dash.yunohost.org/appci/app/isso) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/isso.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/isso.maintain.svg)

[![Installa Isso con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=isso)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Isso su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Isso – *Ich schrei sonst* – is a lightweight commenting server written in Python and JavaScript. It aims to be a drop-in replacement for
[Disqus](http://disqus.com).

### Features

- Comments written in Markdown
- SQLite backend
- Disqus & WordPress Import
- Configurable JS client 

**Versione pubblicata:** 0.13.0~ynh3

**Prova:** <https://isso-comments.de>

## Screenshot

![Screenshot di Isso](./doc/screenshots/example.jpg)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://isso-comments.de>
- Documentazione ufficiale per gli utenti: <https://isso-comments.de/docs/reference/client-config/>
- Documentazione ufficiale per gli amministratori: <https://isso-comments.de/docs/reference/server-config/>
- Repository upstream del codice dell’app: <https://github.com/posativ/isso>
- Store di YunoHost: <https://apps.yunohost.org/app/isso>
- Segnala un problema: <https://github.com/YunoHost-Apps/isso_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/isso_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
o
sudo yunohost app upgrade isso -u https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
