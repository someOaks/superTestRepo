### Проект имени чего-то там (keyboard layout)

Для настроения: https://coub.com/view/2bmya


________

Основные направления разработки проекта:
1) Подключаемые либы - анализируем входящую стрингу и определяем язык текста.
2) Пишем свою либу! Которая изначально на вход принимает стрингу и отсылает ее на определение языка. Если язык не определен - меняем раскладку и опять определяем язык текста.

3) Поднять web-сервис:
      - Разработка удобного RESTapi.
      - Собираем все в Docker! Собрать контейнер и запустить его локально. Настроить прослушиваемый порт и безопасность. Протестить работу сервиса локально (с заглушкой или уже работающим RESTapi).  


4) Интерфейс для использования:
    - Skype boot
    - Telegram boot

Не решенные вопросы:
  - Один  бот на все платформы или отдельный бот для каждой платформы?
  - Может-ли бот работать локально у каждого пользователя?
