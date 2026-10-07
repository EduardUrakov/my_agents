---
name: github-workflow
description: "GitHub интеграция — PR, CI, release workflow"
argument-hint: описание задачи или PR
license: MIT
metadata:
  effort: medium
  version: 1.0.0
  category: integration
  tags: [github, ci-cd, pr, release, workflow]
---

# GitHub Workflow

## Когда использовать
- Для работы с GitHub PR и Issues.
- Настройка CI/CD пайплайнов.
- Подготовка релизов.
- Управление ветками.

## Процесс
1. **PR**: Создать/проверить pull request.
2. **CI**: Проверить статус проверок.
3. **Release**: Подготовить релизные нуты.
4. **Branch**: Управлять ветками.

## Правила
- Явный вызов, без push/merge без подтверждения.
- Поддерживать `.rubric-status` в актуальном состоянии.
- Логировать все действия.
- Фиксировать изменения в CHANGELOG.

## Инструменты
- **GitHub Actions**: CI/CD.
- **gh CLI**: Управление репозиторием.
- **Probot**: Автоматизация GitHub.
