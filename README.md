# Лабораторная работа №1 — «Изучение HTML-тегов и CSS-стилей»

Вариант 4: **Мариуполь**.

Учебный многостраничный сайт выполнен на HTML5 и SCSS. В проект также включена отдельная страница с анимированным персонажем South Park, реализованным **только HTML + CSS, без изображений и SVG**.

## Структура проекта

```text
/index.html              — главная страница
/about.html              — о разработчике
/history.html            — история города
/infrastructure.html     — инфраструктура и карта
/culture.html            — культура и искусство
/contact.html            — форма обратной связи
/southpark.html          — усложнённое задание South Park
/scss/styles.scss        — исходные SCSS-стили
/css/styles.css          — готовый CSS
/img/developer.jpg       — фотография разработчика
/EMMET.md                — Emmet-инструкции для всех страниц
/CONTROL_QUESTIONS.md    — ответы на вопросы
/SOURCES.md              — источники материалов и фотографий
```

## Что выполнено по требованиям

- 7 полноценных HTML-страниц, то есть больше требуемых 6.
- 65 различных HTML-тегов во всём проекте.
- Используются HTML5-элементы: `header`, `footer`, `nav`, `main`, `section`, `article`, `aside`, `figure`, `figcaption`, `details`, `summary`, `mark`, `time`, `progress`, `meter` и др.
- На главной странице 7 фотографий города с адаптивной сеткой.
- На странице истории таблица из 12 значимых событий.
- На странице инфраструктуры встроена карта OpenStreetMap.
- На странице разработчика есть горизонтальная диаграмма навыков.
- Форма использует HTML5-валидацию: `required`, `type="email"`, `pattern`, `minlength`, `maxlength`.
- Применены `position: static`, `relative`, `absolute`, `fixed`, `sticky`.
- Применён `float` для обтекания фотографии разработчика.
- Используются селекторы по тегу, классу, ID, универсальный `*`, селекторы по атрибуту и псевдоклассы.
- Используются комбинаторы потомка, дочерний `>`, соседний `+`, общий соседний `~`.
- Используется более 10 псевдоклассов: `:link`, `:visited`, `:hover`, `:active`, `:focus`, `:first-child`, `:nth-child()`, `:nth-of-type()`, `:lang()`, `:disabled`, `:not()`, `:required`, `:valid`, `:invalid`, `:checked`.
- Используются `::before` и `::after`.
- SCSS содержит переменные, миксины, `%placeholder` + `@extend`, вложенность.
- Есть адаптивные правила `@media`.
- Для каждой страницы подготовлена отдельная комбинированная Emmet-инструкция.

## Перед сдачей

1. Проверить ФИО и текст биографии в `about.html`.
2. При необходимости скорректировать проценты навыков.
3. Указать ФИО, группу и вариант в отчёте.
4. Проверить открытие всех страниц после полной распаковки архива.

## Запуск

**Сначала полностью распакуйте ZIP-архив.** Не запускайте `index.html` прямо из окна ZIP-архива: Windows/браузер может временно извлечь только один HTML-файл, поэтому `css/styles.css` и соседние страницы (`history.html`, `culture.html` и т. д.) не будут найдены.

После распаковки откройте `index.html` из обычной папки. Все HTML-файлы и папки `css`, `scss`, `img` должны лежать рядом в структуре проекта.

Удобнее запускать проект через расширение **Live Server** в VS Code: открыть **всю папку проекта**, нажать правой кнопкой по `index.html` → `Open with Live Server`.

## Работа с SCSS

Файл для редактирования: `scss/styles.scss`.

Если Sass установлен, компиляция один раз:

```bash
sass scss/styles.scss css/styles.css
```

Автоматическая перекомпиляция при сохранении:

```bash
sass --watch scss/styles.scss:css/styles.css
```

Установка Sass через npm:

```bash
npm install -g sass
```

## Публикация на GitHub

Создать публичный репозиторий, например `mariupol-city-history`, затем из папки проекта выполнить:

```bash
git init
git add .
git commit -m "Lab 1: Mariupol city website"
git branch -M main
git remote add origin АДРЕС_ВАШЕГО_РЕПОЗИТОРИЯ
git push -u origin main
```

Для GitHub Pages: **Settings → Pages → Deploy from a branch → main → /root**.
