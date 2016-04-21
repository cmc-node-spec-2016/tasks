# Задания с репозиториями

Все задания должны храниться в git-репозитории (например, GitHub), включать в себя тесты (по выбору), интеграцию с CI (например, Travis), работу с базой данных.

Интерфейс ко всем заданиям не обязателен (по желанию), на оценку не повлияет.

## 4 курс и магистры
1. **Шейдаев Вадим**
 
 Чат с авторизацией через соц.сети, websocket, тесты
 Xранение — MongoDB.
 Команды (через !команда) — поиск в гугле и выдача первого результата с заголовком, выдача первого абзаца описания из вики по названию статьи.
 
 Репозиторий — ???.

2. **Глейзерман Светлана**
 
 Чат, хранение — MariaDB.
 Команды — регистрация, авторизация, кик пользователя, рассылка сообщений всем, отправка приватных сообщений.
 Тесты должны в т.ч. эмулировать клиента, то есть проходить процедуру регистрации, писать, убеждаться, что получают сообщения.
 
 Репозиторий — ???.

3. **Беляев Михаил**
 
 Тасклисты, с регистрацией и возможностью шаринга.
 У тасклиста есть владелец (создатель), который может выдавать другим пользователям доступ (или запрещать).
 В тасклисте есть название и список тасков, которыми может управлять любой пользователь с доступом
 У таска несколько статусов завершённости (список заранее задан, 4-5, придумайте) и комментарии от пользователей
 БД — любая не SQL, но база данных.
 Регистрация — POST (или PUT)-запрос, обмен данными в тасклисте — WebSocket. Тесты.

 Дополнительно можно приделать авторизацию через гитхаб (или что-нибудь другое), но это по желанию. Либо можно приделать её же вместо регистрации вообще.
 Если делать через гитхаб, то можно и тасклисты к репозиториям привязать, но это, опять же, абсолютно не обязательно — по желанию. См https://waffle.io/, например.
 
 Репозиторий — ???.

4. **Жуков Владимир**
 
 «Морской бой», по WebSocket, авторизация через любую соцсеть по выбору (или через GitHub/Google/что угодно). MongoDB (сам попросил). Историю игр и ходов хранить.
 По человеку считать статистику выигрышей-проигрышей. Обязательна только серверная часть, интерфейс — по желанию.
 Должна быть возможность закрыть окно и открыть его заново, вернувшись к игре, а так же вести несколько игр одновременно.
 Только серверная часть, так что на практике это значит что надо хранить и передавать по запросу состояние.
 
 Репозиторий — ???.

5. **Закляков Роман**
 
 «Крестики-нолики», на бесконечном поле, по WebSocket, авторизация через любую соцсеть по выбору (или через GitHub/Google/что угодно). MongoDB (сам попросил). Историю игр и ходов хранить.
 По человеку считать статистику выигрышей-проигрышей. Обязательна только серверная часть, интерфейс — по желанию.
 Должна быть возможность закрыть окно и открыть его заново, вернувшись к игре, а так же вести несколько игр одновременно.
 Только серверная часть, так что на практике это значит что надо хранить и передавать по запросу состояние.
 
 Репозиторий — ???.
 
6. **Луценко Юрий**

 Планировщик событий.
 Пользователи, с регистрацией (логин-пароль).
 События привязываются к дате и времени, могут быть определённой продолжительности. События могут пересекаться (тут никакой хитрой логики делать не надо).
 Пользователи могут создавать списки событий, которые могут быть публичные (доступны всем), и приватные (доступны всем, у кого есть общий токен).
 Пользователи могут отмечаться в событиях (придёт/не придёт/возможно придёт), с комментарием. На каждого пользователя комментарий один, но может быть обновлён.
 REST API для всех операций, WebSocket для получения обновлений по конкретному событию.
 Интерфейс не обязателен. БД — любая не SQL, но база данных.
 
 Репозиторий — ???.

