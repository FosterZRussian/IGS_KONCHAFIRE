<p align="center">
  <img src="https://img.shields.io/github/downloads/GM-DONATE/IGS/total?label=%D0%97%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D0%BE%D0%BA">
  <img src="https://img.shields.io/github/languages/code-size/GM-DONATE/IGS">
  <img src="https://img.shields.io/github/license/GM-DONATE/IGS">
</p>

# InGameShop (IGS)
**Внутриигровой магазин от gm-donate.net** — аддон для Garry's Mod, который добавляет на сервер F1 меню, через которое игроки могут сделать пожертвование и обменять полученные баллы на виртуальные привилегии: группы прав, оружие, модельки, хвосты, транспорт и т.д.

<img align="left" width="450" src="https://user-images.githubusercontent.com/9200174/111821738-aad96c80-88eb-11eb-91ba-a98a2c3d770a.png">

## Инструкция по установке

1. Скачайте `igs-modification`: [скачать](https://github.com/GM-DONATE/IGS/releases/latest/download/igs-mod.zip) и распакуйте его в папку /addons на сервере. `igs-core` скачивать не нужно. Этот скрипт используется для настройки автодоната, а также сам его обновляет
2. В файле `config_sv.lua` укажите ID проекта и секретный ключ, который указан на странице проекта [на сайте](https://gm-donate.net/panel/) (проект нужно создать)

Напишите нам [в поддержку](https://gm-donate.net/support), если возникли какие-то вопросы, а наш живой оператор вам поможет. Также вы можете обратиться [на форум](https://forum.gm-donate.net).

## Главная ошибка при установке

> ❗ **Папки `igs-core` не должно быть в addons**. `igs-modification` сама проследит и скачает все необходимые файлы.

В 99% случаев `igs-core` распаковывают в addons, чтобы что-то сделать, что можно сделать без распаковки. Просто спросите у поддержки, либо на форуме, а мы вам поможем не сделать глупость.

`igs-core` в addons лишает вас автоматических обновлений и исправлений, если очередная обнова в гмоде снова все сломает, как с `debug.getregistry()`

## Полезные ресурсы

- 🔥 [Более подробная инструкция по установке](http://gm-donate.net/instructions)
- 📰 [VK](https://vk.com/public143836547): Главная группа VK с основными новостями
- 💬 [Forum](https://forum.gm-donate.net): Форум гмоддеров. Ответы и помощь с любыми гмод вопросами, включая GMD
- 📣 [GMD Stream](https://t.me/notafaq): Telegram канал с информацией, которая мало известна, но может быть полезна
- 📣 [GMD Mods](https://t.me/gmodder): Telegram канал с модами и различными публикациями, которых нет в группе ВК
- 🔧 [Настройка итемов](https://gm-donate.net/docs): информация про методы, которые наделяют донат предметы функционалом
