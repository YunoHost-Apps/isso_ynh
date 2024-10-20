<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Isso для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/isso.svg)](https://ci-apps.yunohost.org/ci/apps/isso/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/isso.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/isso.maintain.svg)

[![Установите Isso с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=isso)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Isso быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Isso – *Ich schrei sonst* – is a lightweight commenting server written in Python and JavaScript. It aims to be a drop-in replacement for
[Disqus](http://disqus.com).

### Features

- Comments written in Markdown
- SQLite backend
- Disqus & WordPress Import
- Configurable JS client 

**Поставляемая версия:** 0.13.0~ynh4

**Демо-версия:** <https://isso-comments.de>

## Снимки экрана

![Снимок экрана Isso](./doc/screenshots/example.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://isso-comments.de>
- Официальная документация пользователя: <https://isso-comments.de/docs/reference/client-config/>
- Официальная документация администратора: <https://isso-comments.de/docs/reference/server-config/>
- Репозиторий кода главной ветки приложения: <https://github.com/posativ/isso>
- Магазин YunoHost: <https://apps.yunohost.org/app/isso>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/isso_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/isso_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
или
sudo yunohost app upgrade isso -u https://github.com/YunoHost-Apps/isso_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
