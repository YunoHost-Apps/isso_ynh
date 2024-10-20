<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Isso untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/isso.svg)](https://ci-apps.yunohost.org/ci/apps/isso/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/isso.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/isso.maintain.svg)

[![Pasang Isso dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=isso)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Isso secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Isso – *Ich schrei sonst* – is a lightweight commenting server written in Python and JavaScript. It aims to be a drop-in replacement for
[Disqus](http://disqus.com).

### Features

- Comments written in Markdown
- SQLite backend
- Disqus & WordPress Import
- Configurable JS client 

**Versi terkirim:** 0.13.0~ynh4

**Demo:** <https://isso-comments.de>

## Tangkapan Layar

![Tangkapan Layar pada Isso](./doc/screenshots/example.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://isso-comments.de>
- Dokumentasi pengguna resmi: <https://isso-comments.de/docs/reference/client-config/>
- Dokumentasi admin resmi: <https://isso-comments.de/docs/reference/server-config/>
- Depot kode aplikasi hulu: <https://github.com/posativ/isso>
- Gudang YunoHost: <https://apps.yunohost.org/app/isso>
- Laporkan bug: <https://github.com/YunoHost-Apps/isso_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/isso_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
atau
sudo yunohost app upgrade isso -u https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
