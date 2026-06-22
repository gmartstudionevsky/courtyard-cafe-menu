# Courtyard Café Menu

Статическая веб-версия меню для GitHub Pages.

## Структура

```text
.
├─ index.html
├─ styles.css
├─ .nojekyll
└─ assets/
   ├─ menu.pdf
   └─ pages/
      ├─ page-01.webp / page-01.jpg / page-01.png
      ├─ page-02.webp / page-02.jpg / page-02.png
      ├─ page-03.webp / page-03.jpg / page-03.png
      ├─ page-04.webp / page-04.jpg / page-04.png
      ├─ page-05.webp / page-05.jpg / page-05.png
      ├─ page-06.webp / page-06.jpg / page-06.png
      ├─ page-07.webp / page-07.jpg / page-07.png
      ├─ page-08.webp / page-08.jpg / page-08.png
      └─ page-09.webp / page-09.jpg / page-09.png
```

## Как загрузить ассеты из Canva

1. В Canva откройте дизайн меню.
2. Нажмите **Share / Поделиться → Download / Скачать**.
3. Выберите формат **JPG** или **PNG**. Для быстрой загрузки лучше JPG, для максимальной четкости — PNG.
4. Скачайте все страницы.
5. Переименуйте изображения строго так:
   - `page-01.jpg`
   - `page-02.jpg`
   - ...
   - `page-09.jpg`
6. Загрузите изображения в `assets/pages/`.
7. PDF-версию меню загрузите как `assets/menu.pdf`.

Страница умеет искать изображения в трех форматах по очереди: `.webp`, `.jpg`, `.png`. Поэтому можно загрузить либо WebP, либо JPG, либо PNG, но названия должны быть `page-01`, `page-02` и так далее.

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
2. Скачайте новые страницы.
3. Сохраните их под теми же именами.
4. Замените файлы в `assets/pages/`.
5. Если менялся PDF, замените `assets/menu.pdf`.
6. Закоммитьте изменения.

QR-код менять не нужно, если адрес сайта остается прежним.
