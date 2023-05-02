Курсовая №5.
Работа с базами данных 

В рамках проекта получаем данные о компаниях и вакансиях с сайта hh.ru,
проектируем таблицы в БД PostgreSQL и загружаем полученные данные в созданные таблицы.

Данный проект собирает данные с сайта hh.ru о вакансиях 10 компаний, обрабатывает данные
и загружает в базу данных PostgreSQL. Далее предлагаемое меню позволяет получить информацию
из полученной базы данных.

Для использования программы необходим доступ к БД PostgreSQL.
Сделайте клон данного репозитория в свой глобальный GitHub на портале https://github.com.
Скопируйте проект локально.
ВНИМАНИЕ! Для работы с БД необходимо создать и заполнить файл databese.ini данными по образцу:

[postgresql]
host=localhost
user=postgres
password="Ваш пароль от БД"
port="Ваш порт, стандатно - 5432"

Для работы программы могут потребоваться дополнительные библиотеки, загляните в .toml файл.

По всем возникающим вопросам готов ответить по почте alexd-78@yandex.ru.

Автор: Деревянных Алексей.