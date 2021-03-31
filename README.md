## Привет!👋 Меня зовут Денис.
Я Web-разработчик.
- 👯 Я буду рад работать в продвинутой команде
- 🌱 Создаю web-интерфейсы приложений, а также Api для них
- 🤔 Знаком с серверной инфраструктурой и безопасностью web-приложений
- ⚡ Открыт к диалогу: 
  - https://t.me/srvds8080 (Telegram)
### Краткий обзор моих проектов

Все проекты выполнены мной самостоятельно (за исключением "Turbina"), по техническому заданию. Каждый из проектов прошел код-ревью старшим разработчиком.

> ### Проект ["Поиск фильмов"](https://srvds8080.xyz).

Веб-приложение с возможностью поиска фильмов. Выполнено как дипломный проект по курсу Яндекс Практикума "Web-разработчик". Проект состоит из 2-ч частей: 
* 1. [фронтенд](https://github.com/srvds8080diploma/movies-explorer-frontend) часть написанная на React. Использован стиль написания кода Airbnb. Функциональные компоненты, настроена валидация всех форм (в основе useState). 
 * 2. [бэкенд](https://github.com/srvds8080diploma/movies-explorer-api). Api для приложения на Express.js. Реализована авторизация, аутентификация, валидация ошибок на роутах до обработки контроллерами с помощью celebrate. Реализована централизованная обработка ошибок. Взаимодействие с MongoDB.
 
Приложение после авторизации обращается к api https://api.nomoreparties.co/beatfilm-movies получает массив с данными фильмов и сохраняет их в localStorage браузера. Дальнейший поиск по фильмам производится из данных localStorage. Приложение позволяет найти фильм по содержащейся в названии букве или слову, как на английской раскладке так и на русской, без учета регистра. Понравившийся фильм пользователь может добавить в коллекцию избранных фильмов. которая является для него персонализированной. Отображение изменений добавления\удаления фильма происходит мгновенно, без обновления страницы, и дополнительных запросов к Api. Также существует возможность редактирования пользовательских данных: "имя" или  "email". Для авторизации используется jwt, который хранится в localStorage. При повторном посещении приложения, не требуется дополнительного ввода данных для входа в приложение, если не был очищен localStorage браузера. Срок действия jwt ограничен.

Приложение размещенно на ВМ на базе linux. Использован web-server nginx. Приложение можно "положить" по адресу https://api.srvds8080.xyz/crash-test. Через несколько секунд функциональность будет востановлена автоматически.

На приложение есть планы для развития: 
* дополнить соощения об ошибках пользователю, сообщениями celebrate.
* дополнить взаимодейтсвие через websocket
* провести миграцию приложения на typescript
* написать админку для управления контентом на главной странице
* добавить возможность воспроизведения трейлера во встроенном кастомном проигрывателе на странице приложения.

Демонстрация работы приложения: [https://srvds8080.xyz](https://srvds8080.xyz)
Исходный код: [https://github.com/srvds8080diploma](https://github.com/srvds8080diploma)


> ### Проект ["Turbina"](https://rinata0912.github.io/turbina).

Веб-приложение с возможностью прослушивания музыки. Выполнено в ходе хакатона по разработке приложения для некомерческих организаций, в команде из двух разработчиков. Мой вклад в проект включает верстку отдельных блоков, валидацию формы, ревью кода.
Демонстрация работы приложения: https://rinata0912.github.io/turbina
Исходный код: https://github.com/srvds8080/turbina


> ### Проект ["Mesto"](https://srvds8080.github.io/mesto/) (frontend).

Идея проекта предоставить пользователю возможность делиться интересными географическими местами. Использован основной технологический стек: HTML, CSS, JavaScript, WebPack, БЭМ.
Демонстрация работы приложения: https://srvds8080.github.io/mesto/
Исходный код: https://github.com/srvds8080/mesto
Так же был произведен рефакторинг кода и миграция приложения на React.js. с последующим объединением с backend-частью приложения на Express.js. Выполнена регистрация и авторизация пользователей.
Исходный код приложения по ссылке: https://github.com/srvds8080/react-mesto-api-full


> ### Проект ["Mesto"](https://github.com/srvds8080/express-mesto) (backend)

Серверное API для frontend-части. Основной технологический стек: Node.Js, Express, MongoDB. Выполнена централизованная обработка ошибок, валидация входящих данных от клиентской части, работа с БД MongoDB.
Исходный код по ссылке: https://github.com/srvds8080/express-mesto
### Мой технологический стек:
<p>
<img align="center" alt="react" width="60px" src="https://raw.githubusercontent.com/srvds8080/srvds8080/develop/images/react_original_logo_icon_146374.svg" />
<img align="center" alt="js" width="60px" src="https://raw.githubusercontent.com/srvds8080/srvds8080/develop/images/javascript_original_logo_icon_146455.svg" />
<img align="center" alt="ts" width="60px" src="https://raw.githubusercontent.com/srvds8080/srvds8080/develop/images/typescript_plain_logo_icon_146316.svg" />
<img align="center" alt="html5" width="60px" src="https://raw.githubusercontent.com/srvds8080/srvds8080/develop/images/html_original_wordmark_logo_icon_146478.svg" />
<img align="center" alt="css3" width="60px" src="https://raw.githubusercontent.com/srvds8080/srvds8080/develop/images/css_original_wordmark_logo_icon_146576.svg" />
<img align="center" alt="linux" width="60px" src="https://raw.githubusercontent.com/srvds8080/srvds8080/develop/images/linux_original_logo_icon_146433.svg" />
<img align="center" alt="git" width="60px" src="https://raw.githubusercontent.com/srvds8080/srvds8080/develop/images/git_plain_logo_icon_146507.svg" />
<img align="center" alt="mongo" width="60px" src="https://raw.githubusercontent.com/srvds8080/srvds8080/develop/images/mongodb_original_wordmark_logo_icon_146425.svg" />
<img align="center" alt="nginx" width="60px" src="https://raw.githubusercontent.com/srvds8080/srvds8080/develop/images/nginx_original_logo_icon_146413.svg" />
<img align="center" alt="webpack" width="60px" src="https://raw.githubusercontent.com/srvds8080/srvds8080/develop/images/webpack_plain_logo_icon_146297.svg" />
</p>

 ### Моя Статистика
![Dan Suranov`s GitHub stats](https://github-readme-stats.vercel.app/api?username=srvds8080&count_private=true&show_icons=true&theme=radical&")
