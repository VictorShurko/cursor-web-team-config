# Как внедрить в рабочий сайт

Репозиторий с конфигом: [https://github.com/VictorShurko/cursor-web-team-config](https://github.com/VictorShurko/cursor-web-team-config)

1. Откройте папку сайта в Cursor (**File → Open Folder**).
2. Склонируйте или скачайте репозиторий и скопируйте в корень сайта:
   - `AGENTS.md`
   - `.cursorignore`
   - папку `.cursor/`
3. Откройте новый чат (`Ctrl+I`) и напишите:

```text
Прочитай AGENTS.md и правила в .cursor/rules.
Кратко подтверди, какая это CMS/самопис по файлам проекта.
Ничего не меняй, только определи платформу.
```

4. Дальше работайте командами:
   - `/verst-block` — вёрстка
   - `/content-update` — контент
   - `/migrate-block` — перенос
   - `/check-page` — проверка перед сдачей

## Что уже настроено

| Файл | Назначение |
|---|---|
| `00-no-hallucinations` | Не выдумывать файлы/API/классы |
| `01-process-ru` | Русский язык, план, минимальные правки |
| `02-bem-modern-layout` | БЭМ, семантика, адаптив, a11y, чистый код |
| `03-wordpress` | WordPress / WooCommerce |
| `04-bitrix` | 1C-Bitrix |
| `05-other-cms` | Tilda, MODX, Megagroup, Joomla, OpenCart, самопис |
| `06-content-safe` | Безопасные контент-правки |
| skills + commands | Повседневные сценарии |
| `layout-reviewer` | Субагент-ревьюер вёрстки |
