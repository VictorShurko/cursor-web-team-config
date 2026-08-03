# Cursor: конфиг для команды сайтов

Репозиторий: [https://github.com/VictorShurko/cursor-web-team-config](https://github.com/VictorShurko/cursor-web-team-config)

Готовый набор правил, skills и команд для работы с сайтами:

- чистый HTML / CSS / JS
- WordPress (+ WooCommerce)
- 1C-Bitrix (Управление сайтом / контентом)
- Tilda, MODX, Megagroup, Joomla, OpenCart
- самописные сайты

## Как использовать

### Вариант A — копировать в каждый проект

Склонируйте или скачайте репозиторий и скопируйте в корень сайта:

- `AGENTS.md`
- `.cursorignore`
- папку `.cursor/` (целиком)

### Вариант B — открыть этот репозиторий как образец

Откройте сайт клиента в Cursor и попросите агента:

```text
Возьми правила и skills из @AGENTS.md и папки .cursor/
этого шаблона и адаптируй под текущий проект.
Ничего не выдумывай — сначала изучи структуру проекта.
```

## Роли

| Роль | Чем пользоваться чаще |
|---|---|
| Верстальщик | `/verst-block`, skill `layout-block`, правила БЭМ |
| Контент-менеджер | `/content-update`, skill `safe-content-update` |
| Веб-разработчик | `/migrate-block`, skill `site-migrate-page`, `/check-page`, CMS-правила |

Инструкции:
- `docs/cursor-instruction.html` — работа в Cursor
- `docs/site-migration-instruction.html` — перенос сайта
- `docs/site-migration-prompt.md` — универсальный промпт переноса

## Важно

Правила требуют: **не выдумывать** файлы, классы, хуки, API плагинов и «типичную» структуру CMS, если её нет в проекте. Сначала читать проект, при сомнении — спросить.
