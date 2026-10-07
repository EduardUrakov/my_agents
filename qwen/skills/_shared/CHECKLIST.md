# Shared Utilities

## Checklist для скиллов

### Общие правила
- Все скиллы должны иметь frontmatter metadata.
- Четкие триггеры использования.
- Пошаговые инструкции.
- Чеклисты готовности.

### Структура SKILL.md
```markdown
---
name: skill-name
description: "Описание"
argument-hint: "Что передавать"
license: MIT
metadata:
  effort: low|medium|high
  version: 1.0.0
  category: category-name
  tags: [tag1, tag2]
---

# Название скилла

## Когда использовать
- Ситуации использования

## Процесс
1. Шаг 1
2. Шаг 2

## Правила
- Правила и ограничения

## Результат
- Что на выходе
```

### Категории скиллов
- **project-creation**: Создание новых проектов.
- **daily-work**: Ежедневная работа.
- **quality-assurance**: Проверка качества.
- **operations**: Операции и деплой.
- **workflow**: Управление процессами.
- **research**: Исследования.
- **integration**: Интеграции.
- **efficiency**: Эффективность.
- **advisory**: Консультации.
