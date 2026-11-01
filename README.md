# HealthyTeeeeth

Учебный проект Skillbox: статический сайт стоматологической клиники.
Страницы проекта: «О клинике», «Блог» и «Лечение зубов во сне».

## Стек технологий

- HTML5 и SCSS с модульной структурой `global/` и `blocks/`.
- Методология БЭМ.
- Локальные шрифты Rubik и Nunito Sans в формате `.woff2`.
- SVG-спрайты.

## Структура проекта

- `fonts/` — локальные файлы шрифтов.
- `images/` — изображения и SVG-спрайты.
- `scss/` — исходные стили: глобальные настройки и блоки.
- `about.html`, `blog.html`, `sedation.html` — страницы сайта в корне проекта.

## Быстрый старт

Откройте `about.html` или `sedation.html` в браузере либо используйте Live Server в VS Code.

## Особенности реализации

На странице [«Лечение зубов во сне»](./sedation.html) модификатор БЭМ `.text-block--sedation` переопределяет шрифт заголовков и ячеек таблицы на Nunito Sans, задаёт ширину столбцов таблицы и формирует арку главного изображения с помощью `clip-path`.

## О доработке

Детали изменений приведены в [CHANGES.md](./CHANGES.md).
Живой diff: [base/original...main](https://github.com/romiusricco/Healthy-Teeeeth/compare/base/original...main).

## Лицензия

MIT — подробности в [LICENSE](./LICENSE).
