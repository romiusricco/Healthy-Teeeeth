# HealthyTeeeeth — «О клинике»

статическая страница стоматологической клиники HealthyTeeeeth.
Страница собрана на HTML и SCSS, использует локальные шрифты и изображения.

## О проекте

На странице представлены:

- шапка сайта с навигацией и ссылкой записи на приём;
- хлебные крошки;
- текстовые разделы о клинике и её обслуживании;
- фотографии с подписями, цитата и список преимуществ;
- таблица вакансий;
- подвал с контактным телефоном и иконками соцсетей.

Классы HTML и стили организованы по БЭМ: блоки `header`, `breadcrumbs`, `text-block`, `footer`, элементы с `__` и модификаторы с `--`.

## Стек технологий

- HTML5.
- SCSS с модулями `global/` и `blocks/`.
- CSS — готовые стили страницы в `style.css`.
- Rubik и Nunito Sans — локальные шрифты `.woff2`.
- SVG-спрайт для логотипа и иконок.

## Структура папок

```text
.
├── fonts/              # Файлы Rubik и Nunito Sans
├── images/             # Фотографии и SVG-спрайт
│   └── sprite/          # SVG-файлы логотипа и иконок
├── scss/
│   ├── blocks/          # SCSS-компоненты страницы
│   ├── global/          # Шрифты, переменные и базовые стили
│   └── style.scss       # Главный SCSS-файл
├── index.html           # Страница «О клинике»
├── style.css            # Готовые стили, подключённые в HTML
├── style.css.map        # Карта исходников CSS
├── CHANGES.md           # Сведения о доработках
└── LICENSE              # Лицензия MIT
```

## Как запустить

Сборка и установка зависимостей для просмотра страницы не требуются. Откройте `*.html` в браузере или используйте расширение **Live Server** в VS Code.

## О доработке

Исходник проекта находится в ветке [`base/original`](https://github.com/romiusricco/Healthy-Teeeeth/tree/base/original) и отмечен тегом [`original-source`](https://github.com/romiusricco/Healthy-Teeeeth/tree/original-source).
Сведения о внесённых изменениях приведены в [`CHANGES.md`](./CHANGES.md).
Живое сравнение исходной версии с текущей: [base/original...main](https://github.com/romiusricco/Healthy-Teeeeth/compare/base/original...main).
Сам diff в этом README не приводится.

## Лицензия

Проект распространяется по лицензии [MIT](./LICENSE).
