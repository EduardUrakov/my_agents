---
name: harden
description: "Подготовка проекта к продакшену (hardening)"
argument-hint: описание проекта или текущей конфигурации
license: MIT
metadata:
  effort: high
  version: 1.0.0
  category: operations
  tags: [production, hardening, security, monitoring]
---

# Production Hardening

## Когда использовать
- Перед деплоем на продакшен.
- Для повышения надежности и безопасности.
- Настройка мониторинга и алертинга.
- Подготовка к высокой нагрузке.

## Процесс
1. **Health Checks**: Добавить эндпоинты для проверки состояния.
2. **Graceful Shutdown**: Настроить корректное завершение.
3. **Logging**: Структурированное логирование.
4. **Rate Limiting**: Ограничение запросов.
5. **Monitoring**: Prometheus/Grafana, алерты.
6. **Backup**: Стратегия бэкапов.
7. **Load Tests**: k6, Apache Bench.
8. **Runbook**: Инструкция на случай инцидентов.

## Чеклист готовности
- [ ] Health check эндпоинт работает.
- [ ] Логирование структурировано.
- [ ] Rate limiting настроен.
- [ ] Мониторинг и алертинг работают.
- [ ] Бэкапы настроены.
- [ ] Load tests пройдены.
- [ ] Runbook написан.
- [ ] Secrets в переменных окружения.

## Инструменты
- **Prometheus**: Сбор метрик.
- **Grafana**: Визуализация.
- **k6**: Нагрузочное тестирование.
- **ELK Stack**: Логирование.
- **PagerDuty**: Алертинг.
