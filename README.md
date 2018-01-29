# Шаблонизатор jinja2 в Flask

## ДЗ

склонировать репозиторий к себе

git clone https://github.com/assigdev/template_lesson

1) В функции books к context добавить еще одну книгу в списке books

2) Открыть home.html и понять какой текст будет выводиться, а какой нет на главной и почему.

3) Добавить функцию 'my' с ссылкой 'route('/my/')' Для этой
функции создать html 'my.html'. Подключить в 'my.html' 'base.html'
и написать в блоке content свое имя и возраст.
также в 'base.html' добавить ссылку на эту страницу с помощью тега <a href>

4) Добавить функцию 'authors' с ссылкой 'route('/authors/')' Для этой
функции создать html 'authors.html'. Подключить в 'my.html' 'base.html'. 
В index.py есть переменная 'authors', нужно передать её в шаблон 'authors.html' 
и вывести всех авторов и количество написанных ими книг
также в 'base.html' добавить ссылку на эту страницу с помощью тега <a href>

5) Для той же страницы authors добавит в шаблон проверку на количество книг.
Если книг меньше 3, то вывести имя автора красным цветом.
Если больше или равно 3, то вывести имя автора фиолетовым цветом

6) Дополнительное, если все остальное оказалось easy:
http://jinja.pocoo.org/docs/2.10/templates/#builtin-filters
перейти по ссылке и посмотреть на другие фильтры. Создать новую страницу(назвать как угодно) на сайте и использовать
понравившиеся фильтры на этой странице.

Выполнение первых трех обязательно. 4 и 5 нужно хотя бы попытаться.
Результать нужно закомитить в свой репозиторий следующим образом:
делаем первое задание -> коммит с сообщением 'первое задание', 
потом делаем третье задание(второе не требует выполнение, нужно просто посмотреть) ->
коммит с сообщением 'первое задание',
Если с гитом проблемы возникнуть - можно совместно их решить в группе телеграмм.