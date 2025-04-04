# feedbaker_for_art final
# ![example workflow](https://github.com/serebrennikovalexander/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)
## Описание:
### feedbaker_for_art final
Проект создано на основе приложения [feedbacker_for_art](https://github.com/kultmet/api_yamdb)

>feedbaker_for_art - это платформа для сбора отзывов и оценок по различным категориям.

Приложение feedbaker_for_art было упаковано в контейнера с помощью технологии [Docker](https://www.docker.com/).

Для приложния настроены CI (continuous Integration) и CD (Continuous Deployment).
CI и CD реализованы на основе облачного сервиса [GitHub Actions](https://github.com/features/actions).

В файле `yamdb_final/.github/workflows/yamdb_workflow.yml` описаны следующие команды:
- проверка кода на соответствие стандарту PEP8 (с помощью пакета flake8) и запуск pytest из репозитория
- сборка и доставка докер-образа для контейнера web на [Docker Hub](https://hub.docker.com/)
- автоматический деплой проекта на удалённом сервере
- отправка уведомления в Telegram о том, что процесс деплоя успешно завершился

Развёрнутый на удалённом сервере, проект можно посмотреть по следующим ссылкам:
```
http://62.84.116.232/api/v1/
http://62.84.116.232/admin/
http://62.84.116.232/redoc/
```
