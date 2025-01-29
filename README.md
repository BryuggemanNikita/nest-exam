Краткая инструкция по запуску проекта

1. Создание папки services

Выполните следующую команду в терминале:

```mkdir -p services && cd services```

2. Клонирование репозиториев

Склонируйте два репозитория в папку services:

```git clone https://github.com/BryuggemanNikita/nest-exam-questionService questionService```

```git clone https://github.com/BryuggemanNikita/nest-exam-clientService clientService```

3. Вернуться в корневую папку проекта

После клонирования выйдите из папки services:

```cd ..```

4. Запуск docker-compose

Запустите контейнеры с помощью Docker Compose:

```docker-compose up -d --build```

После запуска docker-compose сервисы questionService и clientService должны быть доступны и готовы к работе.

По умолчанию порты на.

                        questionService - 5000
                        clientService - 5001

