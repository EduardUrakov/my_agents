---
name: test
description: "Генерация тестов для кода"
argument-hint: код или описание функционала
license: MIT
metadata:
  effort: medium
  version: 1.0.0
  category: quality-assurance
  tags: [testing, unit, integration, edge-cases]
---

# Test

## Когда использовать
- Генерация unit-тестов для нового кода.
- Добавление integration-тестов.
- Проверка edge-cases.

## Процесс
1. **Анализ**: Определить тестируемый функционал.
2. **Генерация**: Написать тесты (unit, integration).
3. **Покрытие**: Проверить edge-cases и ошибки.
4. **Запуск**: Убедиться, что все тесты проходят.

## Правила
- Использовать фреймворк проекта (jest, pytest, mocha и т.д.).
- Покрытие ключевых сценариев и ошибок.
- Тесты должны быть изолированными и воспроизводимыми.