# Сплетни Кавалы

Hugo-блог (Bear Blog тема) на GitHub Pages.
Сайт: https://spletnikava1a.github.io

## Добавить сплетню

1. `content/gossip/nazvanie.md`
2. Шапка:

```toml
+++
title = "Заголовок"
slug = "korotkiy-url"
date = "2026-07-25T12:00:00+00:00"
description = "Описание до 160 символов"
tags = ["имя героя"]
cover = "images/gossip/foto.jpg"
+++
```

3. Картинки в `static/images/gossip/`
4. `git add -A && git commit -m "новая сплетня" && git push`

## Добавить лицо

1. `content/people/imya.md`
2. Шапка:

```toml
+++
title = "Имя героя"
slug = "imya-latinicej"
date = "2026-07-25T12:00:00+00:00"
aka = "клички"
charges = "за что прославился"
description = "SEO до 160 символов"
photo = "images/people/foto.jpg"
+++
```

3. Фото в `static/images/people/`

## Комментарии

Cusdis (app ID: `40256950-4f8f-4671-8e45-afb7ea4c7378`). Кэш в `static/comments/*.json`.

## Локальный запуск

```bash
hugo server -D
```
