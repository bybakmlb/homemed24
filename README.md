# HomeMed24 — медсестра на дом, Тараз

Одностраничный сайт (RU / KZ). Всё в одном файле `index.html`, без сборки.

## Как выложить на GitHub Pages бесплатно

1. Зарегистрируйтесь на https://github.com
2. Нажмите **New repository** → имя, например `homemed24` → **Public** → **Create repository**.
3. На странице репозитория нажмите **uploading an existing file** и перетащите файлы `index.html` и `README.md` → **Commit changes**.
4. Откройте **Settings → Pages**. В разделе **Branch** выберите `main` и папку `/ (root)` → **Save**.
5. Через 1–2 минуты сайт будет доступен по адресу:
   `https://ВАШ-ЛОГИН.github.io/homemed24/`

## Как поменять цены

Откройте `index.html`, найдите `data-price="5000"` и замените число.

## Как поменять тексты

Все тексты лежат внизу файла в блоке `var I18N = { ru: {...}, kz: {...} }` — меняйте в обоих языках.
