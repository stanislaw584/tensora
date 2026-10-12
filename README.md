# Tensora. Подготовка к старту карьеры в ML

Учебный проект: визуальный концепт сайта курса для ML-разработчиков, перенесенный из Figma в код.
Адаптивная одностраничная верстка (десктоп 1440, планшет, мобильная 390) на чистых HTML, CSS и JavaScript, без сборки и зависимостей.

Макет в Figma: https://www.figma.com/design/EEst6NeJy9adb4qPM24TZC

## Структура

```
index.html        разметка страницы
css/style.css     стили, цветовые токены в :root, адаптив
js/main.js        мобильное меню и появление блоков при скролле
assets/img/       фотографии
```

## Запуск

Открой папку в VS Code и запусти `index.html` через расширение **Live Server** (Go Live), либо:

```bash
python3 -m http.server 5500
```

После этого сайт будет доступен на http://localhost:5500.

## Секции

Hero · Статистика · Траектории · Как это работает · Проекты · Карьерный трекер · Менторы · Отзывы · Тарифы · CTA · Футер

## Технологии

- Шрифты: Unbounded, Inter, JetBrains Mono (Google Fonts)
- CSS Grid / Flex, `clamp()`, `color-mix()`, `IntersectionObserver`
- Поддержка `prefers-reduced-motion`

## Материалы

Фотографии — [Unsplash](https://unsplash.com) (бесплатная лицензия Unsplash). Имена, цифры, отзывы и компании на сайте вымышленные.
