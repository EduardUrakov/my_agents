---
name: infra
description: "Генерация инфраструктуры как код (Terraform, Docker, Kubernetes)"
argument-hint: описание инфраструктуры или требований
license: MIT
metadata:
  effort: high
  version: 1.0.0
  category: operations
  tags: [infrastructure, terraform, docker, kubernetes, iac]
---

# Infrastructure as Code

## Когда использовать
- Настройка облачной инфраструктуры.
- Создание Docker-контейнеров.
- Развертывание в Kubernetes.
- Автоматизация деплоя.

## Процесс
1. **Анализ**: Определить требования к инфраструктуре.
2. **Проектирование**: Схему сервисов и зависимостей.
3. **Генерация**: IaC-конфиги (Terraform, Docker, K8s).
4. **Тестирование**: Применить на staging.
5. **Деплой**: Применить на продакшене.
6. **Мониторинг**: Настроить логи и метрики.

## Инструменты
- **Terraform**: Управление облачной инфраструктурой.
- **Docker**: Контейнеризация приложений.
- **Kubernetes**: Оркестрация контейнеров.
- **Helm**: Пакеты для Kubernetes.
- **Ansible**: Конфигурационное управление.

## Шаблоны
- **Dockerfile**: Для Node.js, Python, PHP.
- **docker-compose.yml**: Для локальной разработки.
- **Terraform**: Для AWS, DigitalOcean, Hetzner.
- **Kubernetes**: Deployments, Services, Ingress.

## Безопасность
- Использовать secrets management (Vault, AWS Secrets Manager).
- Настроить network policies.
- Ограничить привилегии контейнеров.
- Регулярно обновлять образы.
