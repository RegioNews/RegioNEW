# 🇷🇺 РегионМонитор

Готовый GitHub Pages пакет для дашборда новостей регионов РФ.

## Что внутри
- `index.html`
- `css/style.css`
- `js/config.js` — RSS_SOURCES по 89 субъектам РФ
- `js/app.js`
- `.github/workflows/deploy.yml`

## Публикация
GitHub рекомендует деплой Pages через `actions/configure-pages`, `actions/upload-pages-artifact` и `actions/deploy-pages`.[web:170][web:172]

1. Загрузите содержимое папки в репозиторий.
2. Убедитесь, что основная ветка — `main`.
3. Сделайте push — workflow опубликует сайт.

## Важно
Часть RSS-источников в списке требует валидации. Для Telegram используются публичные RSS-мосты.[web:123][web:119]
