## Практическое задание по теме “5. Структурные паттерны”

В этой самостоятельной работе тренируем умения:

1. Выбирать подходящий структурный шаблон
2. Применять структурные шаблоны в своем коде

Смысл: Для использования структурных шаблонов в своем коде

Последовательность действий:

- Можно сделать всё или одно на выбор, применив при этом один из структурных паттернов, либо аргументировать почему данные паттерны не были использованы:

1. Добавить декоратор для добавления связки url-view в приложение, чтобы можно было добавлять url-ы, как в фреймворке Flask `@app(‘/some_url/’)`
2. Добавить декоратор `@debug`, для view, если мы указываем данный декоратор над view, то в терминал выводятся название функции и время ее выполнения
3. Добавить подкатегорий.
   Т.е. категория курса может входит в другую категорию, а может не входить и вложенность может быть любая.
   Например:`Программирование->Web->Python->Django`.
   После на страницу списка категорий добавить вывод количества курсов в каждой из категорий.
   Например: `Программирование - 10, Web - 5, Python - 3, …`
4. Добавить 2 новых вида wsgi-application.
   - Первый - логирующий (такой же как основной, только он для каждого запроса выводит информацию (тип запроса и параметры) в консоль.
   - Второй - фейковый (на все запросы пользователя отвечает “200 OK”, “Hello from Fake”)
5. По желанию можно добавить любой другой полезный функционал.
