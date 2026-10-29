<p align="center">
  <img src="assets/icon.png" width="128" alt="mdview icon">
</p>

<h1 align="center">mdview</h1>

<p align="center">Минималистичный ридер и редактор Markdown для macOS · by <a href="https://github.com/theoron-apps">Theoron</a></p>

<p align="center">
  <a href="https://github.com/theoron-apps/mdview/releases"><img src="https://img.shields.io/badge/pre--release-0.2.3-0A84FF?style=flat-square" alt="pre-release 0.2.3"></a>
  <a href="https://github.com/theoron-apps/mdview/releases"><img src="https://img.shields.io/github/downloads/theoron-apps/mdview/total?style=flat-square&label=downloads&color=30D158&logo=github&logoColor=white" alt="downloads"></a>
  <img src="https://img.shields.io/badge/macOS-13%2B-1C1C1E?style=flat-square&logo=apple&logoColor=white" alt="macOS 13+">
  <a href="https://t.me/TheoronApps"><img src="https://img.shields.io/badge/news-@TheoronApps-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
</p>

<p align="center">
  <a href="https://github.com/theoron-apps/mdview/releases"><b>Скачать pre-release</b></a> ·
  <a href="README.md">English</a> · Русский · <a href="README.uk.md">Українська</a>
</p>

<p align="center">
  <img src="assets/workspace.png" width="900" alt="Исходный Markdown и живой предпросмотр в mdview">
</p>

---

## Возможности

Файл из Finder открывается в лёгком ридере. Кнопка **«Открыть в mdview»** переносит документ в полное рабочее пространство для редактирования.

- **Три режима:** чтение, исходный Markdown и редактор рядом с предпросмотром.
- **Документы под рукой:** вкладки, папки, недавние файлы, оглавление и поиск.
- **Инструменты редактирования:** заголовки H1–H6, жирный, курсив, ссылки, изображения, код, списки, цитаты, таблицы и отмена действий.
- **Markdown офлайн:** таблицы, списки задач, подсветка кода, диаграммы Mermaid и формулы KaTeX.
- **Настройки под себя:** светлая и тёмная темы, шрифты, ширина страницы, четыре стиля панели инструментов и Liquid Glass в поддерживаемых версиях macOS.
- **Удобство:** автосохранение существующих файлов, восстановление черновиков, проверка внешних изменений и экспорт PDF через системную печать.
- **Украинский, русский и английский** языки интерфейса.

## Установка

1. Откройте [Releases](https://github.com/theoron-apps/mdview/releases) и выберите предварительный выпуск.
2. Скачайте **mdview-0.2.3.dmg**, откройте образ и перетащите **mdview** в **Applications / Программы**.
3. Извлеките образ и запустите mdview из «Программ».

Для обновления закройте mdview и замените существующее приложение. Проверка обновлений внутри этой сборки пока не подключена; новые версии доступны в Releases.

**Сборка имеет локальную ad-hoc подпись и не нотарифицирована Apple.** macOS может заблокировать первый запуск. Если вы доверяете загрузке, воспользуйтесь [инструкцией Apple](https://support.apple.com/en-au/102445). К выпуску прилагается контрольная сумма SHA-256.

## Требования

**0.2.3 · сборка 5 · pre-release.** Возможности и оформление ещё меняются. Храните резервные копии важных документов. О проблемах сообщайте через [Issues](https://github.com/theoron-apps/mdview/issues), указав версии macOS и приложения и шаги для воспроизведения.

| | Поддержка |
| --- | --- |
| Минимальная система | macOS 13 |
| Процессоры | Universal: Apple Silicon и Intel |
| Liquid Glass | macOS 26 и новее; системные материалы на предыдущих версиях |
| Проверено | Apple Silicon и x86_64 через Rosetta на компьютере разработчика |
| Пока не проверено | Старые macOS, физический Intel Mac и установка на чистом Mac |

Редактирование выполняется в исходном Markdown. Состояние списков задач меняется в исходнике; MDX не выполняет JSX-компоненты.

## Конфиденциальность

Документы остаются в выбранных папках. Рендеринг Markdown работает без сети. Внешние изображения по умолчанию отключены; их можно включить в настройках. mdview не отправляет документы и не собирает аналитику.

История версий находится в **«Настройки → Что нового»**.

## Об этом репозитории

Здесь размещены страница проекта и готовые выпуски. Исходный код приложения не опубликован; открытая лицензия для mdview не предоставляется. Сторонние компоненты сохраняют свои лицензии: [уведомления и тексты лицензий](THIRD_PARTY.md).

## Связь

Новости и поддержка — Telegram [@TheoronApps](https://t.me/TheoronApps).
