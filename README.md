<div align="center"><img src="https://media.giphy.com/media/eCqFYAVjjDksg/giphy.gif" width="300"></div>

<h1 align="center">Petr Tolkachev · Толкачев Петр</h1>

<h3 align="center">Platform Engineer · Developer Experience</h3>

<p align="center">
  I build the infrastructure other developers ship on:<br>
  feature flags, progressive delivery, internal developer platforms.
</p>

<p align="center">
  <a href="https://ptolkachev.ru">ptolkachev.ru</a> ·
  <a href="https://tolkachev.space">tolkachev.space</a> ·
  <a href="https://www.linkedin.com/in/tolkachevpeter">LinkedIn</a> ·
  <a href="https://habr.com/ru/users/PeterTolkachev/">Habr</a> ·
  <a href="mailto:peter.tolkachev@gmail.com">peter.tolkachev@gmail.com</a> ·
  <a href="https://t.me/PeterTolkachev">Telegram</a>
</p>

---

<p align="left"> <img src="https://komarev.com/ghpvc/?username=tolkachevpeter&label=Profile%20views&color=0e75b6&style=flat" alt="tolkachevpeter" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=tolkachevpeter" alt="tolkachevpeter" /></a> </p>

I build the infrastructure other developers ship on. Feature flags, progressive delivery, internal platforms: the layer between somebody's laptop and production.

Most of that work is invisible when it goes well. Nobody thanks you for the release that didn't break. I made peace with this a while ago.

## Things I've built

### A release platform on a fork of Unleash

Started with seven product teams and ended up serving about fifty. I added a role model for access, dynamic segments and an SDK of our own. The numbers people usually ask about: change failure rate went from 2.4% to 0.9%, time to market from ten days to five, release frequency up four times.

The code was the easy part. The hard part is flag hygiene. Teams add flags happily and never delete them, and a year later you are reading conditionals nobody can explain. If I built it again I would put an owner and an expiry date on every temporary flag from day one, and make the platform nag people about it.

### A developer portal on Backstage

One place for services, CI/CD status and DORA metrics. Leadership stopped asking for reports and started opening a dashboard, which was most of the point. Onboarding a new engineer dropped to about two working days.

### A master data platform at a large bank (current)

Corporate reference data, TypeScript from end to end: Node.js services, a React frontend, versioning and change history so neighbouring systems can reconcile against a known state, SSO through Keycloak with roles on top of OAuth2 and OIDC, deploys into Kubernetes through CI/CD.

Reference data sounds boring until you watch four systems disagree about what counts as a legal entity.

### A university portal for 40,000+ students and staff

Node.js on the back, Vue and Nuxt with SSR on the front. I moved realtime delivery from WebSocket to SSE and got one particularly slow page from 30 seconds down to 1. I also migrated a pile of JavaScript and Perl to TypeScript, which removed a whole class of runtime errors and made me unpopular for about two weeks.

## Writing

[Забудьте о локальных if-ах: как централизованные feature flags делают жизнь разработчика проще](https://habr.com/ru/articles/897376/), Habr, 22K reads.

It is an overview piece, and the commenters were right that it stays too general. The specific version, with the fork, the rollout and everything that went wrong on the way, is what I am writing next.

Essays on platforms, digital labour and how infrastructure shapes the people working inside it live at [ptolkachev.ru](https://ptolkachev.ru).

## Stack

`TypeScript` `Node.js` `React` `Vue / Nuxt` `PostgreSQL` `Kubernetes` `Docker` `GitLab CI` `TeamCity` `Unleash` `Backstage` `Keycloak / OAuth2 / OIDC`

## Before the code

I have a PhD in philosophy from Moscow State University, where I taught and published for several years before I wrote anything that ran in production. Less of a detour than it sounds. My subject was how tools shape the people using them, which is what developer experience is about once you strip out the tooling vocabulary.

My first computer arrived when I was a kid. I broke it on day one and fixed it on day two. That is more or less still the method.

## A note on the repositories here

Most of what is public on this account is old, from evenings spent learning frontend. The platform work lives inside companies and cannot be pushed here. I am moving some of it out: an open source tool for feature flag hygiene is the next thing on the list.

## What I am after

Remote platform engineering, developer experience and TypeScript backend work. Full time or contract. English B2, French B1.

Write to me about release engineering, feature flags or internal platforms and I will answer.

<details>
<summary>🇷🇺 Русская версия</summary>

<br>

Я строю инфраструктуру, на которой выкатываются другие разработчики. Фичефлаги, progressive delivery, внутренние платформы: слой между чьим-то ноутбуком и продакшеном.

Когда этот слой работает, его не видно. За релиз, который не сломался, никто не благодарит. Я с этим давно смирился.

### Что построил

**Релизная платформа на форке Unleash.** Начиналось с семи продуктовых команд, закончилось примерно пятьюдесятью. Сделал ролевую модель доступа, динамические сегменты и собственный SDK. Цифры, про которые обычно спрашивают: change failure rate с 2,4% до 0,9%, time-to-market с десяти дней до пяти, частота релизов выросла вчетверо.

Код был простой частью. Сложная часть это гигиена флагов. Команды заводят их охотно и никогда не удаляют, а через год читаешь условия, которые никто не может объяснить. Если бы делал заново, на каждый временный флаг сразу вешал бы владельца и срок жизни, а платформа бы про это напоминала.

**Портал разработчика на Backstage.** Одно место для сервисов, статуса CI/CD и DORA-метрик. Руководство перестало просить отчёты и начало открывать дашборд, ради чего всё и затевалось. Онбординг нового инженера сократился примерно до двух рабочих дней.

**Платформа мастер-данных в крупном банке (сейчас).** Корпоративные справочники, TypeScript от начала до конца: сервисы на Node.js, фронтенд на React, версионирование и история изменений, чтобы смежные системы могли сверяться с известным состоянием, SSO через Keycloak с ролями поверх OAuth2 и OIDC, деплой в Kubernetes через CI/CD.

Справочные данные кажутся скучными ровно до момента, когда четыре системы расходятся в том, что считать юридическим лицом.

**Портал вуза на 40 000+ студентов и сотрудников.** Node.js на бэкенде, Vue и Nuxt с SSR на фронте. Перевёл realtime-доставку с WebSocket на SSE и ускорил одну особенно медленную страницу с 30 секунд до 1. Ещё перевёл кучу JavaScript и Perl на TypeScript: это убрало целый класс ошибок времени выполнения и сделало меня непопулярным недели на две.

### До кода

Кандидат философских наук МГУ, несколько лет преподавал и публиковался до того, как написал первую строчку, дошедшую до продакшена. Это меньший крюк, чем кажется. Я занимался тем, как инструменты формируют работающих с ними людей, а это и есть developer experience, если убрать словарь про тулинг.

Первый компьютер появился у меня в детстве. В первый день я его сломал, во второй починил. С тех пор метод примерно тот же.

### Про репозитории

Почти всё публичное здесь старое, из вечеров, когда я разбирался с фронтендом. Платформенная работа живёт внутри компаний и сюда не выкладывается. Часть я вытаскиваю наружу: следующий пункт в списке это опенсорсный инструмент для гигиены фича-флагов.

### Чего ищу

Удалённые задачи по платформенной инженерии, developer experience и бэкенду на TypeScript. Полная занятость или контракт.

Пишите про релиз-инженерию, фичефлаги и внутренние платформы, отвечу.

peter.tolkachev@gmail.com · Telegram [@PeterTolkachev](https://t.me/PeterTolkachev)

</details>

<details>
<summary>&nbsp;</summary>

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Мета-тэги для SEO -->
    <title>Толкачев Петр / Petr Tolkachev — Platform Engineer</title>
    <meta name="description" content="Пётр Толкачёв (Petr Tolkachev) — платформенный инженер: feature flags, progressive delivery, internal developer platforms. TypeScript, Node.js, React, Kubernetes, Unleash, Backstage, Keycloak.">
    <meta name="keywords" content="Толкачев Петр, Толкачёв Пётр, Petr Tolkachev, Peter Tolkachev, TolkachevPeter, Platform Engineer, платформенный инженер, Developer Experience, feature flags, фичефлаги, progressive delivery, Unleash, Backstage, DORA, TypeScript, JavaScript, Node.js, React, Kubernetes, Docker, CI/CD, Keycloak, OAuth2, OIDC, PostgreSQL, МГУ, MSU, работа, удалённо">
    <meta name="robots" content="index, follow">
    <meta property="og:title" content="Petr Tolkachev — Platform Engineer">
    <meta property="og:description" content="Feature flags, progressive delivery, internal developer platforms. TypeScript · Node.js · Kubernetes.">

    <!-- Schema.org markup для дополнительной индексации -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org/",
        "@type": "Person",
        "name": "Petr Tolkachev",
        "alternateName": ["Peter Tolkachev", "Толкачёв Пётр", "Толкачев Петр", "TolkachevPeter"],
        "jobTitle": "Platform Engineer",
        "description": "Platform engineer: feature flags, progressive delivery, internal developer platforms. TypeScript, Node.js, Kubernetes.",
        "knowsAbout": ["Platform Engineering", "Developer Experience", "Feature Flags", "Progressive Delivery", "TypeScript", "Node.js", "React", "Kubernetes", "Backstage", "Unleash", "DORA Metrics", "Keycloak", "OAuth2", "OIDC"],
        "alumniOf": "Lomonosov Moscow State University",
        "url": "https://tolkachev.space",
        "sameAs": [
            "https://github.com/TolkachevPeter",
            "https://www.linkedin.com/in/tolkachevpeter",
            "https://habr.com/ru/users/PeterTolkachev/",
            "https://career.habr.com/tolkachevpeter",
            "https://istina.msu.ru/profile/peter.tolkachev/",
            "https://tolkachev.space",
            "https://ptolkachev.ru"
        ]
    }
    </script>
</head>
```
</details>
