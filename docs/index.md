# Описание дисцплинв Основы разработки Веб-сервисов

## Цели изучения дисциплины

### Содержание дисциплины
* Дисциплина: Основы разработки Веб-сервисов
* Длительность: 1 семестр
* Количество лабораторных: 4 лабораторных работ
* Баллы за лабораторные: 60 баллов
* ИМ: Зачет

### Вариант на семестр

Описание:
У каждого студента свой вариант предметной области, прикрепленный в ЛМС. Предметная область меняется на каждую работу. 

### Цель изучения дисциплины

Овладение концепцией и принципами разработки web-приложений на языке JavaScript.

### Задачи изучения дисциплины

- формирование знаний о парадигмах программирования, архитектурных особенностях, семантике и синтаксисе языка JavaScript, а также о назначении, устройстве и свойствах основных структур данных, используемых при проектировании, отладке, проверке работоспособности, создании (модификации) и сопровождении информационных систем (ИС);

- формирование умений разрабатывать математические методы и алгоритмы для проектирования, отладки, проверки работоспособности, создания (модификации) и сопровождения информационных систем (ИС), автоматизирующих задачи организационного управления и бизнес-процессы с целью повышения эффективности деятельности организаций;

- формирование практического опыта чтения, написания, проектирования, отладки, проверки работоспособности, создания (модификации) и сопровождения информационных систем на высокоуровневом языке программирования в интегрированных средах разработки;

- формирование уровня знаний, умений и опыта деятельности в рамках программы подготовки кадров для цифровой экономики, построенной на основе программы «Цифровая экономика России»;

- формирование умений по созданию инфраструктуры различных видов телекоммуникационных сетей на основе знаний и понимания требований отраслевых стандартов, а также развития профессиональных навыков, соответствующих лучшим практикам в области информационных и коммуникационных технологий и компетенциям формата WorldSkills.

### Темы курса

1. Web-сервис и API: основы обмена данными
   *(web как платформа, client–server, web-сайт vs web-приложение vs SPA, роль API; HTTP/HTTPS, запрос–ответ, REST на уровне понятий, JSON/XML, CORS)*

2. Проектирование клиентской части: HTML как архитектурный слой
   *(структура HTML-документа, семантика HTML5, DOM как модель, “контракт” для JS через id/class/data-*, формы как источник данных; цепочка UI → DOM → JS(events) → API(HTTP) → DB)*

3. Стилизация интерфейса: CSS как слой представления
   *(подключение CSS, каскад и специфичность, селекторы, box model, layout (Flex/Grid), адаптивность, состояния и доступность, базовая оптимизация UI)*

4. Клиентская бизнес-логика: JavaScript в браузере
   *(базовый синтаксис, управляющие конструкции, функции, массивы/объекты; DOM-манипуляции и события; формы и валидация; асинхронность (Promise/async-await/fetch), обработка ошибок, интеграция с API)*

5. Инженерная дисциплина разработки 
   *(DevTools, отладка, структура проекта, качество кода, читаемость, обработка ошибок, безопасные практики на базовом уровне)*

---

| № | Название лабораторной работы                                                                 | Описание лабораторной работы                                                                                                                                                                                                                                                                                                                 | Баллы  |
| - | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| 1 | Web-сервис и API. JSON / XML                                                             | Изучение модели client–server и протокола HTTP. Анализ структуры API-ответов и форматов JSON/XML. Реализация клиентского запроса к API (fetch), разбор ответа, обработка ошибок и статусов. Понимание REST-взаимодействия и ограничений браузера (CORS — на уровне концепции).                                                   | 10     |
| 2 | Проектирование структуры клиентской части Web-приложения (HTML + архитектурное мышление) | Проектирование UI-структуры как системы: UI(HTML) → DOM → JS(events) → API(HTTP) → DB. Создание семантической разметки, выделение интерфейсных блоков (layout), формирование “контракта” для JS через id/class/data-атрибуты, проектирование форм и сценариев ввода/вывода данных. Учет доступности и базовых SEO-требований в HTML. | 10    |
| 3 | Стилизация интерфейса Web-приложения                                                     | Реализация слоя представления через CSS: подключение стилей, каскад/специфичность, селекторы, box model, позиционирование и layout (Flexbox/Grid), адаптивность (media queries), состояния элементов (hover/focus/active), базовые правила доступности (контраст, focus-visible).                                                    | 20     |
| 4 | Реализация клиентской бизнес-логики Web-приложения (JavaScript)                          | Реализация поведения интерфейса: обработка событий, работа с DOM, управление состоянием UI, валидация форм (встроенная HTML + JS + RegExp), операции с массивами/объектами, асинхронные сценарии и интеграция с API через fetch/async-await, обработка ошибок, отображение результатов пользователю без перезагрузки страницы.           | 20    |
|   | Итого                                                                                    |                                                                                                                                                                                                                                                                                                                                              | 60 |
---

## Полезные ресурсы для изучения JavaScript

### Официальная документация и стандарты

* MDN Web Docs — JavaScript (RU)
  [https://developer.mozilla.org/ru/docs/Web/JavaScript](https://developer.mozilla.org/ru/docs/Web/JavaScript)
  Официальная документация по JavaScript с примерами, описанием синтаксиса, встроенных объектов и Web API.

* ECMAScript (ECMA-262)
  [https://tc39.es/ecma262/](https://tc39.es/ecma262/)
  Спецификация языка JavaScript, описывающая формальный стандарт ECMAScript.

### Учебные материалы и справочники

* JavaScript.info (Илья Кантор)
  [https://javascript.info/](https://javascript.info/)
  Подробный русскоязычный учебник по JavaScript: основы языка, работа с DOM, асинхронное программирование, объектная модель.

* Eloquent JavaScript
  [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
  Онлайн-книга, ориентированная на понимание принципов работы языка и развитие алгоритмического мышления.

* You Don’t Know JS (Yet)
  [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
  Серия книг, посвящённых внутренним механизмам JavaScript и продвинутым аспектам языка.

### Практика и интерактивные среды

* Codewars (JavaScript)
  [https://www.codewars.com/](https://www.codewars.com/)
  Платформа для решения алгоритмических задач на JavaScript с автоматической проверкой решений.

* JSFiddle
  [https://jsfiddle.net/](https://jsfiddle.net/)
  Онлайн-песочница для экспериментов с JavaScript, HTML и CSS.

* CodePen
  [https://codepen.io/](https://codepen.io/)
  Среда для создания и демонстрации фронтенд-примеров и небольших web-компонентов.

* StackBlitz
  [https://stackblitz.com/](https://stackblitz.com/)
  Онлайн-IDE для разработки JavaScript- и Node.js-проектов в браузере.

### Статьи, обзоры и профессиональное сообщество

* Habr — раздел JavaScript
  [https://habr.com/ru/hub/javascript/](https://habr.com/ru/hub/javascript/)
  Публикации, разборы практических кейсов, обзоры инструментов и обсуждение современных подходов к разработке.

* Hexlet Blog
  [https://ru.hexlet.io/blog](https://ru.hexlet.io/blog)
  Аналитические статьи по JavaScript, архитектуре приложений и качеству кода.

### Дополнительные ресурсы для изучения JavaScript

* learn.javascript.ru
  [https://learn.javascript.ru/](https://learn.javascript.ru/)
  Русскоязычный учебный ресурс, подробно раскрывающий основы и продвинутые возможности JavaScript.

* W3Schools — JavaScript
  [https://www.w3schools.com/js/](https://www.w3schools.com/js/)
  Справочник и практические примеры по JavaScript, ориентированные на быстрое освоение базовых конструкций.

* Code.mu — JavaScript
  [https://code.mu/ru/javascript/book/prime/](https://code.mu/ru/javascript/book/prime/)
  Русскоязычный учебник по JavaScript с последовательной подачей материала и практическими заданиями.

---

## Полезные ресурсы для изучения HTML

### Официальная документация и стандарты

* MDN Web Docs — HTML (RU)
  [https://developer.mozilla.org/ru/docs/Web/HTML](https://developer.mozilla.org/ru/docs/Web/HTML)
  Справочник по элементам, атрибутам, семантике и практикам разметки.

* HTML Living Standard (WHATWG)
  [https://html.spec.whatwg.org/](https://html.spec.whatwg.org/)
  Актуальный “живой” стандарт HTML (то, на что ориентируются браузеры).

* W3C — HTML / спецификации и рекомендации
  [https://www.w3.org/TR/](https://www.w3.org/TR/)
  Репозиторий спецификаций W3C (полезно для ссылки на формальные определения).

### Учебные материалы и справочники

* web.dev — Learn HTML
  [https://web.dev/learn/html/](https://web.dev/learn/html/)
  Практический курс по HTML от команды Google, фокус на семантике и современных подходах.

* HTML Reference
  [https://htmlreference.io/](https://htmlreference.io/)
  Краткий визуальный справочник по тегам и атрибутам.

* W3Schools — HTML
  [https://www.w3schools.com/html/](https://www.w3schools.com/html/)
  Быстрый справочник + интерактивные примеры.

### Семантика, доступность, SEO (HTML-ориентированно)

* MDN — Accessibility (A11y)
  [https://developer.mozilla.org/en-US/docs/Web/Accessibility](https://developer.mozilla.org/en-US/docs/Web/Accessibility)
  Практики доступности: семантика, ARIA, клавиатурная навигация.

* ARIA Authoring Practices Guide (APG)
  [https://www.w3.org/WAI/ARIA/apg/](https://www.w3.org/WAI/ARIA/apg/)
  Рекомендации W3C по паттернам доступных интерфейсов.

* Google Search Central — SEO Basics
  [https://developers.google.com/search/docs/fundamentals/seo-starter-guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
  Базовые принципы SEO, важные для структуры HTML и метаданных.

### Практика

* Frontend Mentor (HTML/CSS проекты)
  [https://www.frontendmentor.io/](https://www.frontendmentor.io/)
  Задачи с макетами и требованиями — идеально под отработку верстки.

* Can I use
  [https://caniuse.com/](https://caniuse.com/)
  Проверка поддержки HTML/CSS/JS возможностей в браузерах.

---

## Полезные ресурсы для изучения CSS

### Официальная документация и стандарты

* MDN Web Docs — CSS (RU)
  [https://developer.mozilla.org/ru/docs/Web/CSS](https://developer.mozilla.org/ru/docs/Web/CSS)
  Справочник по свойствам, селекторам, layout-моделям, анимациям.

* CSS Specifications (W3C Drafts / TR)
  [https://www.w3.org/Style/CSS/specs.en.html](https://www.w3.org/Style/CSS/specs.en.html)
  Точка входа в спецификации CSS-модулей (Selectors, Flexbox, Grid и т.д.).

### Учебные материалы и справочники

* web.dev — Learn CSS
  [https://web.dev/learn/css/](https://web.dev/learn/css/)
  Курс по CSS: каскад, специфичность, layout, responsive, modern CSS.

* CSS Tricks — Guides
  [https://css-tricks.com/guides/](https://css-tricks.com/guides/)
  Практические гайды (Flexbox, Grid, responsive паттерны, UI-решения).

* Flexbox Froggy
  [https://flexboxfroggy.com/](https://flexboxfroggy.com/)
  Игра-тренажёр по Flexbox.

* Grid Garden
  [https://cssgridgarden.com/](https://cssgridgarden.com/)
  Игра-тренажёр по CSS Grid.

* W3Schools — CSS
  [https://www.w3schools.com/css/](https://www.w3schools.com/css/)
  Быстрый справочник и практические примеры.

### Инструменты и практика (layout, debug, качество)

* DevTools CSS debugging (Chrome DevTools docs)
  [https://developer.chrome.com/docs/devtools/css/](https://developer.chrome.com/docs/devtools/css/)
  Отладка каскада, computed styles, box model, grid/flex overlays.

* Specificity Calculator
  [https://specificity.keegan.st/](https://specificity.keegan.st/)
  Быстрая проверка специфичности селекторов.

* Autoprefixer (PostCSS)
  [https://autoprefixer.github.io/](https://autoprefixer.github.io/)
  Инструмент для совместимости CSS (в рамках инженерной дисциплины).

### Доступность и UX (CSS-ориентированно)

* WebAIM Contrast Checker
  [https://webaim.org/resources/contrastchecker/](https://webaim.org/resources/contrastchecker/)
  Проверка контраста (важно для текста, кнопок, состояний focus).

* MDN — :focus-visible
  [https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-visible](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-visible)
  Корректные стили фокуса без ущерба UX.

