# Courtyard Café Menu

Статическая веб-версия меню для GitHub Pages.

## Текущая структура

```text
.
├─ index.html
├─ styles.css
├─ .nojekyll
└─ assets/
   ├─ Menu.pdf
   └─ Pages/
      ├─ 1.jpg
      ├─ 2.jpg
      ├─ 3.jpg
      ├─ 4.jpg
      ├─ 5.jpg
      ├─ 6.jpg
      ├─ 7.jpg
      ├─ 8.jpg
      └─ 9.jpg
```

`index.html` настроен именно под эту структуру: изображения берутся из `assets/Pages/`, PDF — из `assets/Menu.pdf`.

## Как выгружать ассеты из Canva

1. В Canva откройте дизайн меню.
2. Нажмите **Share / Поделиться → Download / Скачать**.
3. Выберите формат **JPG**.
4. Скачайте все страницы.
5. Переименуйте изображения строго так:
   - `1.jpg`
   - `2.jpg`
   - ...
   - `9.jpg`
6. Загрузите изображения в `assets/Pages/`.
7. PDF-версию меню загрузите как `assets/Menu.pdf`.

Важно: GitHub Pages чувствителен к регистру символов. `assets/Pages/1.jpg` и `assets/pages/page-01.jpg` — разные пути.

## Как включить GitHub Pages

1. Откройте репозиторий на GitHub.
2. Перейдите в **Settings → Pages**.
3. В блоке **Build and deployment** выберите **Deploy from a branch**.
4. Branch: `main`.
5. Folder: `/root`.
6. Нажмите **Save**.

После публикации сайт будет доступен по адресу:

```text
https://gmartstudionevsky.github.io/courtyard-cafe-menu/
```

## Как обновлять меню

1. Обновите дизайн в Canva.
2. Скачайте новые страницы в JPG.
3. Сохраните их под теми же именами: `1.jpg` ... `9.jpg`.
4. Замените файлы в `assets/Pages/`.
5. Если менялся PDF, замените `assets/Menu.pdf`.
6. Закоммитьте изменения.

QR-код менять не нужно, если адрес сайта остается прежним.
