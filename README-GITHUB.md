# 🪷 Lotus Ascension

Игра на чистом HTML/JS — качание, гильдии, арена, питомцы.

## Публикация на GitHub Pages

1. Создай репозиторий (New repository → имя любое → Public → Create).
2. Нажми «uploading an existing file» и перетащи ВСЕ файлы из этой папки:
   index.html, lotus-admin.html, manifest.json, version.json,
   icon-192.png, icon-512.png, apple-touch-icon.png, favicon-32.png
3. Внизу нажми зелёную «Commit changes».
4. Settings → Pages → Source: «Deploy from a branch», ветка main, папка / (root) → Save.
5. Через 1–3 минуты игра откроется по адресу:
   https://ТВОЙ-НИК.github.io/ИМЯ-РЕПОЗИТОРИЯ/

## Обновление версии

- В файле version.json лежит номер версии (сейчас 1.5.0).
- Когда в index.html меняется константа APP_VERSION, в version.json ставь тот же номер —
  тогда автообновлятор покажет баннер «Доступна новая версия» только когда реально есть что обновить.
- Не забывай обновлять номер в ОБЕИХ местах: в version.json и в APP_VERSION внутри index.html.

## Сейвы

- Сейв привязан к адресу страницы (localhost-файл и GitHub — разные хранилища).
- Перенос: Настройки → «📦 Экспорт / импорт сейва» → Копировать на старом адресе → Импортировать на новом.
- Админ-панель (lotus-admin.html) работает, когда открыта в том же браузере, что и игра.
