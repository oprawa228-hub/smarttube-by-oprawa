# Авторство SmartTube by Oprawa

## SmartTube

Основной проект: [yuliskov/SmartTube](https://github.com/yuliskov/SmartTube).

Copyright (c) 2020-present yuliskov. Лицензия MIT, точная копия включена в `LICENSE-SmartTube.txt`.

Основа этой версии: commit `0b421183d34625d423fbc2a0d48348cc9ec71b87`, SmartTube 32.70. Исходные сервисы, авторизация и движок воспроизведения сохранены. Изменения интерфейса и поведения плеера находятся в прилагаемом patch.

## Современный интерфейс

Часть нативных компонентов интерфейса адаптирована из работы **Mirco Ramundo**, [SmartTube PR6334 — feat: add an optional modern interface](https://github.com/yuliskov/SmartTube/pull/6334), commit `eebce9afde01e658b8d7b94464f35cc3b8f9e9df`. Это отдельный открытый PR, не официальный релиз SmartTube. Из него перенесена UI-часть; изменения буферизации и предварительной загрузки медиаданных исключены.

Настройки с превью, пользовательские значения по умолчанию, навигация, отдельный пакет и сопутствующие исправления подготовлены для SmartTube by Oprawa.

## Зависимости и визуальные ориентиры

Лицензии исходных зависимостей сохраняются в проекте и составе приложения. Подмодули зафиксированы в `SOURCE.md`. Материалы YouTube Android TV использовались как визуальные ориентиры; изображения из этих публикаций не включены в приложение. SmartTube by Oprawa — самостоятельная модификация, не официальный продукт YouTube или релиз команды SmartTube.

Оформление версии .2 согласовано с пользовательским проектом Twitch TV by Oprawa. Контуры SmartTube и растровые ресурсы воспроизводятся локальным генератором `../tools/create_brand.ps1`.

Значок повторной попытки основан на Material Icons Refresh (Google), Apache License 2.0; исходный набор: https://github.com/google/material-design-icons. Текст лицензии включён в `LICENSE-Apache-2.0.txt`.
