# Брендинг Positive Technologies

## Что есть в этом репозитории
1. Папка design-tokens — дизайн-токены
2. Папка favicons — набор всех нужных размеров фавиконок
3. Папка webfonts — набор шрифтов

## Как брать файлы
Лучше не скачивать из репозитория отдельные файлы, а подключить npm-пакет [@ptsecurity/branding](https://www.npmjs.com/package/@ptsecurity/branding).

## Логотипы
Логотипы разных версий [лежат в Фигме](https://www.figma.com/file/FtKbhjXaX3LsmFpgvFoJyh/?node-id=0%3A1)

## Как добавлять фавиконки в проект
1. Подключить npm-пакет или скачать все файлы из папки favicons.
2. Подключить файлы к проекту, например, так: https://evilmartians.com/chronicles/how-to-favicon-in-2021-six-files-that-fit-most-needs (не забудьте поменять пути к иконкам, manifest.webmanifest)
3. Отдельно можно добавить theme color, тогда в браузере Chrome цвет шапки браузера будет меняться. Метод описан здесь: https://css-tricks.com/how-to-favicon-in-2021/
