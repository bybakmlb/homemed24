# HomeMed24 — медсестра на дом, Тараз

Одностраничный сайт (RU / KZ). Всё в одном файле `index.html`, без сборки.

## Как выложить на GitHub Pages бесплатно

1. Зарегистрируйтесь на https://github.com
2. Нажмите **New repository** → имя, например `homemed24` → **Public** → **Create repository**.
3. На странице репозитория нажмите **uploading an existing file** и перетащите файлы `index.html` и `README.md` → **Commit changes**.
4. Откройте **Settings → Pages**. В разделе **Branch** выберите `main` и папку `/ (root)` → **Save**.
5. Через 1–2 минуты сайт будет доступен по адресу:
   `https://ВАШ-ЛОГИН.github.io/homemed24/`

## Как обновить сайт

Загрузите в репозиторий `homemed24` (кнопка **Add file → Upload files**) файлы `index.html` и `og.png` → **Commit changes**.
`og.png` — картинка, которая показывается при отправке ссылки в WhatsApp/Instagram/Telegram.

Казахская версия открывается по адресу `https://bybakmlb.github.io/homemed24/?lang=kz`.

## Как поменять цены

Откройте `index.html`, найдите `data-price="5000"` и замените число — и в атрибуте, и в тексте рядом (`от 5 000 ₸`).

## Как поменять тексты

Все тексты лежат внизу файла в блоке `var I18N = { ru: {...}, kz: {...} }` — меняйте в обоих языках.
