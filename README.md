### npm run seed
  Запуск скрипта для создания таблиц и инициализации их данными
### node src/app.js 
### app.js

содержит основные маршруты
  * возвращаются все пользователи
  * возвращаются все покемоны
  * регистрируется пользователь

### Postman
* post запрос по адресу http://localhost:5000/registration с телом запроса, например {
	"login":"user@mail.ru",
	"password":"user@mail.ru"
} зарегистрирует нового пользователя

* get запрос по адресу http://localhost:5000/show вернет всех пользователей
* get запрос по адресу http://localhost:5000/pokemons вернет всех покемонов




