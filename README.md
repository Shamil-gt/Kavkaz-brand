# Кавказ — Хадж и Умра. Брендбук-сайт

Один файл `index.html` + папка `assets/`. Никакой сборки и сервера не нужно.

## Как выложить на GitHub Pages

1. Создайте репозиторий на github.com (например `kavkaz-brand`), можно приватный.
2. Нажмите **Add file → Upload files**, перетащите `index.html`, `README.md` и папку `assets` целиком. Нажмите **Commit changes**.
3. Откройте **Settings → Pages**. В блоке *Build and deployment* выберите **Source: Deploy from a branch**, ветка `main`, папка `/ (root)`. Сохраните.
4. Через 1–2 минуты сайт появится по адресу `https://ВАШ_ЛОГИН.github.io/kavkaz-brand/`.

Чтобы обновить — загрузите новый `index.html` поверх старого, сайт пересоберётся сам.

## Как выложить на Netlify (ещё проще)

1. Зайдите на app.netlify.com/drop.
2. Перетащите всю папку с сайтом в окно браузера.
3. Готово — получите ссылку вида `что-то.netlify.app`. Имя можно поменять в настройках сайта.

## Что внутри

- `index.html` — весь брендбук: интро-анимация логотипа, разделы, интерактив.
- `assets/kavkaz-logo.svg` — оригинальный логотип.
- `assets/kavkaz-logo-white.svg` — белая версия для тёмных и цветных фонов.
- `assets/kavkaz-emblem*.svg` — знак без слова.
- `assets/kavkaz-logo-mono-*.svg` — одноцветные версии.
- `assets/*.png` — растровые копии 2000 px с прозрачным фоном.
- `assets/kavkaz-gradient.png` — фирменный градиент.
- `assets/kavkaz-colors.txt` — коды цветов.

Тексты и данные (имена на визитке, номера) — заглушки, замените их в `index.html` обычным поиском по файлу.
