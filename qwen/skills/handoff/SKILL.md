---
name: handoff
description: "Сохранение контекста для следующей сессии"
argument-hint: описание прогресса и следующих шагов
license: MIT
metadata:
  effort: low
  version: 1.0.0
  category: workflow
  tags: [context, save, handoff, continuity]
---

# Handoff

## Когда использовать
- Перед завершением сессии.
- При передаче проекта другому агенту или разработчику.
- Для сохранения прогресса и решений.

## Что сохранять
- Что было сделано.
- Какие решения приняты.
- Какие blockers остались.
- Следующие шаги.

## Формат
Создавать файл `.itd-memory/SESSION-{date}.json` или обновлять `STATE.json`.

## Пример
```json
{
  "session": "2024-01-15",
  "status": "in_progress",
  "completed": ["setup", "auth"],
  "next": ["payments", "deploy"],
  "notes": "Оплата через Stripe, нужен webhook"
}
```