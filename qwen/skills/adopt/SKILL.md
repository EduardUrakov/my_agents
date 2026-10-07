---
name: adopt
description: "Онбординг legacy проекта через активный хост адаптер"
argument-hint: описание legacy проекта или текущей конфигурации
license: MIT
metadata:
  effort: high
  version: 1.0.0
  category: project-creation
  tags: [adopt, legacy, onboarding, bootstrap]
---

# Adopt

## Когда использовать
- Для онбординга legacy проекта.
- При переходе на новую методологию.
- Для.bootstrap canonical контрактов.
- При смене хост адаптера.

## Процесс
1. **Анализ**: Изучить текущее состояние проекта.
2. **Адаптер**: Определить активный хост адаптер.
3. **Bootstrap**: Создать .itd/ контракты.
4. **State**: Инициализировать .itd-memory/.
5. **Документация**: Записать изменения.

## Хост адаптеры
- **Claude Code**: CLAUDE.md + .claude/settings.json.
- **Codex**: AGENTS.md + hooks.
- **Другие**: Adapter-defined.

## Правила
- Не реверс-инжинирить план-документы.
- Сохранять совместимость.
- Фиксировать все изменения.
