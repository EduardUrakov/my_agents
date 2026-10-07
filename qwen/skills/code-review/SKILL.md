---
name: code-review
description: "Проверка кода на соответствие стандартам и безопасность"
argument-hint: код или ссылка на файл
license: MIT
metadata:
  effort: medium
  version: 1.0.0
  category: quality-assurance
  tags: [review, security, quality, standards]
---

# Code Review

## Когда использовать
- Проверка кода перед слиянием.
- Аудит безопасности.
- Оценка соответствия стандартам проекта.

## Чеклист
- [ ] Стек: PostgreSQL/Supabase/NocoDB.
- [ ] Безопасность: Секреты в `.env`.
- [ ] Верстка: Относительные единицы, адаптив.
- [ ] Ошибки: `try/catch` везде.
- [ ] Качество: Читаемость, логирование.

## Результат
- Статус: `PASSED` / `PASSED_WITH_WARNINGS` / `BLOCKED`.
- Список рекомендаций по исправлению.