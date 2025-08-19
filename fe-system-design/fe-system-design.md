---
title: &laquo;System Design для Frontend разработчиков&raquo;
description: &laquo;Что это такое, зачем нужно знать и&nbsp;как к&nbsp;этому готовиться&raquo;
---

## System Design для Frontend разработчиков

### Что&nbsp;/ Зачем&nbsp;/ Как?

<!-- v -->

<strong>System design</strong>&nbsp;&mdash; это проектирование того, как устроена программа:
<ul>
<li>из&nbsp;каких частей она состоит</li>
<liкак они взаимодействуют</li>
<li>почему выбраны именно такие технологии и&nbsp;решения</li>
</ul>
<!--s-->

### Василий Ванчук

### @vvscode

<!-- v -->
<ul>
<li>кандидат-разрядник, несколько лет подряд брал планку в&nbsp;120 собеседований</li>
<li>активный интервьюер (100 собеседований в&nbsp;год для компаний Bolt и&nbsp;Т-Банк)</li>
<li>собеседую спикеров на&nbsp;HolyJS</li>
</ul>
<!-- v -->

### Личный опыт

<ul>
<li class="fragment"><strong>EPAM, Минск (2018)</strong>&nbsp;&mdash; первая встреча с&nbsp;секцией при обсуждении новостного сайта</li>
<li class="fragment"><strong>Яндекс, Авито</strong>&nbsp;&mdash; секции системного дизайна</li>
<li class="fragment"><strong>Bolt</strong>&nbsp;&mdash; проходил, а&nbsp;позже лидил секцию для фронтендщиков и&nbsp;фуллстеков</li>
<li class="fragment"><strong>Т-Банк</strong>&nbsp;&mdash; и&nbsp;кандидат, и&nbsp;интервьюер</li>
</ul>

<!-- s -->

## О&nbsp;чем сегодня поговорим

<ul>
<li class="fragment"> Что это за&nbsp;секция интервью и&nbsp;где ее&nbsp;можно встретить </li>
<li class="fragment"> Почему &laquo;на&nbsp;скилле&raquo; не&nbsp;вывезти </li>
<li class="fragment"> Зачем это вам, если вы&nbsp;не&nbsp;архитектор </li>
<li class="fragment"> На&nbsp;что смотрят интервьюеры </li>
<li class="fragment"> Как прокачаться, даже делая лендинги </li>
<li class="fragment"> Частые ошибки кандидатов </li>
<li class="fragment"> Материалы для подготовки </li>
</ul>
<!--s-->

## Что это за&nbsp;секция?

<!-- v -->

<div class="fragment">
Про способность <strong>проектировать</strong>, а&nbsp;не&nbsp;только писать код. 

Она оценивает: <br />

<ul>
<li>как вы&nbsp;собираете требования</li>
<li>выбираете технологии</li>
<li>обосновываете решения</li>
<li>предвидите будущие проблемы</li>
</ul>
</div>

<!-- v -->

### Где можно встретить:

🇺🇸 Google 🇺🇸 Meta/Facebook 🇺🇸 Amazon 🇺🇸 Apple 🇺🇸 Netflix 🇺🇸 Microsoft 🇺🇸 Uber 🇺🇸 Airbnb 🇺🇸 Stripe 🇺🇸 Dropbox 🇺🇸 Lyft 🇧🇾 EPAM Systems 🇷🇺 Яндекс 🇷🇺 Авито 🇷🇺 Т-Банк 🇷🇺 VK 🇷🇺 Ozon 🇪🇪 Bolt 🇳🇱 Booking.com 🇳🇱 Adyen 🇸🇪 Spotify 🇸🇪 Klarna 🇩🇪 Zalando 🇬🇧 Revolut

<!--v-->

## Почему &laquo;на&nbsp;скилле&raquo; не&nbsp;вывезти?

<!--v-->

### Аналогия&nbsp;с [TOEFL](https://magoosh.com/toefl/toefl-tuesday-do-native-speakers-get-perfect-scores-on-the-toefl/)

**Можно быть native speaker, но&nbsp;провалить экзамен**

<ul>
<li class="fragment"> не&nbsp;знаете формат</li>
<li class="fragment"> не&nbsp;понимаете ожиданий</li>
<li class="fragment"> нет подготовки к&nbsp;специфике теста</li>
</ul>
<!--v-->

### Собеседование &ne; Реальная работа

<!--v-->

**В&nbsp;работе:**

<ul>
<li>есть время на&nbsp;исследование</li>
<li>можно консультироваться с&nbsp;коллегами</li>
<li>итеративный подход</li>
</ul>
<!--v-->

**На&nbsp;интервью:**

<ul>
<li>ограниченное время (45-60&nbsp;минут)</li>
<li>нужно показать мыслительный процесс</li>
<li>формат whiteboarding</li>
</ul>
<!--s-->

## Зачем это мне? Я&nbsp;ж не&nbsp;архитектор

<!--v-->

### Кто проходит эту секцию?

<ul>
<li class="fragment">Senior/Lead</li>
<li class="fragment">Middle+</li>
<li class="fragment">Junior</li>
</ul>

<!-- v -->

System Design про:
<ul>
<li>картину целиком</li>
<li>осознанные решения</li>
<li>умение объяснять их</li>
<li>быстро адаптироваться к&nbsp;новым проектам и&nbsp;работать в&nbsp;команде</li>
</ul>
<!-- Это универсальные умения, которые пригодятся в любом техническом интервью и в реальной разработке. -->

<!-- v -->

### Вес в&nbsp;финальной оценке

**Самый большой вес среди всех секций!**

<!--s-->

### Что проверяется через System Design

<ul>
<li class="fragment">комплексные навыки</li>
<li class="fragment">опыт с&nbsp;разных сторон</li>
<li class="fragment">подход к&nbsp;решению новых задач</li>
<li class="fragment">коммуникационные навыки</li>
</ul>
<!-- v -->

**Результат:** Профиль сильных и&nbsp;слабых сторон

<!--s-->

## На&nbsp;что смотрят в&nbsp;процессе

<!--v-->

### 1. Сбор требований

<strong class="fragment">Что проверяем:</strong>

<ul>
<li class="fragment">работа с&nbsp;нечеткой спецификацией</li>
<li class="fragment">сбор функциональных требований</li>
<li class="fragment">выявление нефункциональных требований</li>
<li class="fragment">оценка ограничений</li>
</ul>
<!-- v -->

**Как проверяем:**

Поверхностное описание + скриншот &rarr; детализация требований

<!--v-->

### 2. Технический кругозор<!-- .element: class="fragment" -->

**Что проверяем:**<!-- .element: class="fragment" -->

<ul>
<li class="fragment">выбор подходящих технологий</li>
<li class="fragment">знание альтернатив</li>
<li class="fragment">обоснование решений</li>
</ul>
<!-- v -->

**Как проверяем:**
Выбор стека для всей системы и&nbsp;ее&nbsp;частей (не&nbsp;только frontend)

<!--v-->

### 3. Верхнеуровневый дизайн

<strong class="fragment">Что проверяем:</strong>

<ul>
<li class="fragment">описание компонентов системы<sup>*</sup></li>
<li class="fragment">взаимодействие между компонентами</li>
<li class="fragment">понимание границ ответственности</li>
</ul>
<!-- v -->

**Как проверяем:**
Схематическое изображение системы целиком

<!--v-->

### 4. Архитектура приложения

<strong class="fragment">Что проверяем:</strong>

<ul>
<li class="fragment">компонентная структура</li>
<li class="fragment">разделение на&nbsp;уровни</li>
<li class="fragment">проектирование API</li>
</ul>
<!-- v -->

**Как проверяем:**
Детализация одной страницы + API дизайн

<!--v-->

### 5. Производительность<sup>\*</sup>

**Что проверяем:**<!-- .element: class="fragment" -->

<ul>
<li class="fragment">определение узких мест</li>
<li class="fragment">подходы к&nbsp;оптимизации</li>
<li class="fragment">методы тестирования</li>
</ul>
<!-- v -->

**Как проверяем:**

<ul>
<li>анализ bottlenecks</li>
<li>стратегии кэширования</li>
<li>опыт с&nbsp;реальными задачами</li>
</ul>
<!--v-->

### 6. Безопасность<sup>\*</sup>

**Что проверяем:**

<ul>
<li>выявление уязвимостей</li>
<li>знание базовых принципов</li>
<li>практический опыт</li>
</ul>
<!-- v -->

**Как проверяем:**

<ul>
<li>OWASP Top 10&nbsp;для фронтенда</li>
<li>XSS, CSRF, CSP</li>
<li>аутентификация и&nbsp;авторизация</li>
</ul>
<!--v-->

### Дополнительные темы<sup>\*</sup>

<ul>
<li>Accessibility (a11y)</li>
<li>Internationalization (i18n)</li>
<li>SEO оптимизация</li>
<li>Progressive Web Apps</li>
<li>Micro Frontends</li>
</ul>
<!--s-->

## Область проектирования

<!--v-->

### Что входит в&nbsp;System Design?

<ul>
<li class="fragment">организация репозиториев</li>
<li class="fragment">выбор технологий и&nbsp;библиотек</li>
<li class="fragment">определение процесса деплоя</li>
<li class="fragment">стратегия тестирования</li>
<li class="fragment">дизайн API</li>
</ul>
<!--v-->

### Метафора

![Картина с&nbsp;ограниченным полем](https://news.itmo.ru/images/news/big/p12881.jpg)

<!-- v -->

**Вся система = картина**

<ul>
<li class="fragment">ограниченное время</li>
<li class="fragment">формат интервью</li>
<li class="fragment">движение и&nbsp;масштаб &laquo;кружка&raquo; зависит от&nbsp;обеих сторон</li>
<li class="fragment">почти никогда не&nbsp;охватываем картину целиком</li>
</ul>

<!--s-->

## Как прокачаться даже делая лендинги

<!--v-->

### Методика &laquo;50&nbsp;ветвлений&raquo;

<ul>
<li class="fragment">знать точки выбора</li>
<li class="fragment">понимать альтернативы</li>
<li class="fragment">yметь обосновать решение</li>
</ul>
<!-- v -->

#### Шаг&nbsp;1: Анализ существующего приложения

<div class="fragment">Описать 50+&nbsp;решений в&nbsp;существующем приложении</div>

<!-- v -->

#### Шаг&nbsp;2: Для каждой точки определить

<ul>
<li>какую проблему решает</li>
<li>2-3 альтернативы</li>
<li>критерии выбора</li>
</ul>

<!--v-->

<strike><strong>Р</strong></strike>рeшенеия

<strike><strong>П</strong></strike>проблемы

<!-- Типичная ошибка в этом упражнении думать про Проблемы и Решенеия, а не про  -->

<!-- v -->

### Примеры точек ветвления для лендинга

<ul>
<li>как раскладывать файлы и&nbsp;папки</li>
<li>какие библиотеку подключать</li>
<li>система сборки приложения</li>
<li>куда деплоить</li>
<li>как деплоить</li>
</ul>
<!--v-->

[Варианты точек для Landing Page](https://docs.google.com/spreadsheets/d/1P7S29zjmWdhfRqEmZNzBUBQIFT6X4nLRy5aWyjxKOnk/edit?gid=1431647587#gid=1431647587)

<!-- v -->

### Шаг&nbsp;3: Формулирование вопросов

<div class="fragment">

<strong>Для выбора сборщика:</strong>

<ul>
<li>какой размер проекта?</li>
<li>нужна&nbsp;ли кастомная конфигурация?</li>
<li>критична&nbsp;ли скорость разработки?</li>
<li>планируется&nbsp;ли масштабирование?</li>
<li>что нужно от&nbsp;сборщика? Какие клиенты?</li>
</ul>

<strong>Эти вопросы = основа сбора требований</strong>

</div>

<!--s-->

## Частые ошибки

<!--v-->

### 1. Не&nbsp;понимание границ задачи

<strong>Проблема:</strong> Не&nbsp;проясняют scope

<strong>Решение:</strong> Активно задавать вопросы

<!-- v -->

### 2. Неправильная подготовка

**Проблема:** Готовятся по&nbsp;backend-материалам

**Решение:** Фокус на&nbsp;frontend-специфичные ресурсы

<!--v-->

### 3. Не&nbsp;собирают требования

#### Аналогия с&nbsp;едой<!-- .element: class="fragment" -->

<div>Заказ &laquo;еды&raquo; может означать:<br />
<ul>
<li>Баланду из&nbsp;столовой</li>
<li>Фуа-гра в&nbsp;ресторане</li>
</ul>
</div><!-- .element: class="fragment" -->

**Требования определяют решение!**<!-- .element: class="fragment" -->

<!--v-->

### 4. Не&nbsp;показывают процесс принятия решений

**Нужно:**<!-- .element: class="fragment" -->

<ul>
<li class="fragment"> Знать точки выбора</li>
<li class="fragment"> Понимать альтернативы</li>
<li class="fragment"> Уметь обосновать решение</li>
</ul>
<!--v-->

### 5. Малый кругозор

**Симптомы:**

<ul>
<li class="fragment"> &laquo;Мы&nbsp;всегда деплоим в&nbsp;облако&raquo;</li>
<li class="fragment"> &laquo;Все используют webpack&raquo;</li>
<li class="fragment"> Не&nbsp;знают о&nbsp;существовании альтернатив</li>
</ul>
<div><strong>Решение:</strong> Расширение технического кругозора</div><!-- .element: class="fragment" -->

<!--s-->

## Материалы для подготовки

<!-- v -->

### Проблема материалов

<strong class="fragment">[Большинство материалов ориентированы на&nbsp;backend](https://www.google.com/search?q=system+design+book):</strong>

<ul>
<li class="fragment"> Очереди, балансеры, CAP теорема</li>
<li class="fragment"> Книги
<ul>
<li><a href="https://bytebytego.com/" target="_blank">Alex Xu&nbsp;&laquo;System Design Interview&raquo;</a></li>
<li><a href="https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/" target="_blank">Martin Kleppmann &laquo;Designing Data-Intensive Applications&raquo;</a></li>
</ul>
</li>
<li class="fragment"> Системы целиком, а&nbsp;не&nbsp;frontend-часть </li>
</ul>
<!--v-->

### Frontend System Design &ne; Backend System Design

<strong class="fragment">Frontend фокус:</strong>

<ul>
<li class="fragment"> Компонентная архитектура<sup>*</sup></li>
<li class="fragment"> Состояние приложения</li>
<li class="fragment"> Дизайн апи</li>
<li class="fragment"> Производительность UI</li>
</ul>

<!--v-->

### Бесплатные ресурсы

<ul>
<li class="fragment"><a href="https://frontendinterviewhandbook.com/" target="_blank">Front End Interview Handbook</a></li>
<li class="fragment"><a href="https://patterns.dev/" target="_blank">Patterns.dev</a></li>
<li class="fragment"><a href="https://github.com/krasimir/react-in-patterns" target="_blank">React in&nbsp;Patterns</a></li>
<li class="fragment"><a href="https://github.com/greatfrontend/awesome-front-end-system-design" target="_blank">Awesome Frontend System Design</a></li>
</ul>
<!--v-->

### Платные курсы

<ul>
<li class="fragment"><a href="https://www.greatfrontend.com/front-end-system-design-playbook" target="_blank">GreatFrontEnd System Design Playbook</a></li>
<li class="fragment"><a href="https://www.educative.io/courses/grokking-frontend-system-design-interview" target="_blank">Educative: Grokking Frontend System Design</a></li>
<li class="fragment"><a href="https://frontendmasters.com/courses/frontend-system-design/" target="_blank">Frontend Masters: Front-End System Design</a></li>
</ul>
<!--v-->

### Книги

<!-- v -->

**English:**

<ul>
<li class="fragment"><a href="https://www.oreilly.com/library/view/frontend-architecture-for/9781491926772/" target="_blank">Frontend Architecture for Design Systems</a></li>
<li class="fragment"><a href="https://refine.dev/blog/react-design-patterns/" target="_blank">React Design Patterns</a></li>
<li class="fragment"><a href="https://www.oreilly.com/library/view/building-micro-frontends/9781492082989/" target="_blank">Building Micro-Frontends</a></li>
</ul>
<!-- v -->

**Русский:**

<ul>
<li class="fragment"><a href="https://www.litres.ru/book/dzhenifer-tidvell-32/razrabotka-interfeysov-patterny-proektirovaniya-pdf-e-68332339/" target="_blank">Разработка интерфейсов. Паттерны проектирования</a></li>
</ul>

<!-- s -->

## Практические советы

<!--v-->

### Структура ответа

<ol>
<li>Сбор требований (5-10&nbsp;минут)</li>
<li>Высокоуровневый дизайн (10-15&nbsp;минут)</li>
<li>Детализация компонентов (15-20&nbsp;минут)</li>
<li>Обсуждение производительности (5-10&nbsp;минут)</li>
<li>Безопасность и&nbsp;дополнительно (5&nbsp;минут)</li>
</ol>
<!--v-->

### Что говорить в&nbsp;процессе

<!-- v -->

✅ **Хорошо:**

<ul>
<li>&laquo;Давайте уточним требования...&raquo;</li>
<li>&laquo;Рассмотрю несколько вариантов...&raquo;</li>
<li>&laquo;Это зависит&nbsp;от [критерий]...&raquo;</li>
<li>&laquo;Альтернативой может быть...&raquo;</li>
</ul>
<!-- v -->

❌ **Плохо:**

<ul>
<li>&laquo;Всегда делаем так...&raquo;</li>
<li>&laquo;Не&nbsp;знаю других способов...&raquo;</li>
<li>Молчание во&nbsp;время размышлений</li>
</ul>
<!--s-->

## Для закрепления

1. выберите любое приложение (даже простое)
2. найдите 30&nbsp;точек ветвления в&nbsp;его архитектуре
3. для каждой точки опишите 2-3 альтернативы
4. сформулируйте вопросы для выбора решения
5. создайте схему взаимодействия компонентов

<!--v-->

## Удачи на&nbsp;собеседованиях! 🚀

**Помните⚠️**

System Design&nbsp;&mdash; <strike> экзамен на&nbsp;знание фактов</strike> демонстрация мыслительного процесса

<!-- s -->

**Контакты для вопросов:**

<ul>
<li>Telegram: <a href="https://t.me/vvscode">@vvscode</a></li>
<li>Linkedin: <a href="https://www.linkedin.com/in/vvanchuk/">https://www.linkedin.com/in/vvanchuk/</a></li>
</ul>