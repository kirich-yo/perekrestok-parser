# perekrestok-parser
Парсер сайта Перекресток

## Принцип работы

На вход в качестве аргумента при запуске парсера принимается путь к категории, находящийся в URL-адресе страницы магазина после ее доменного имени:

![Путь к категории в URL страницы Перекрестка](https://github.com/kirich-yo/perekrestok-parser/blob/master/res/screenshots/4.png)

В случае успешного завершения программа сохраняет все полученные и обработанные данные в Excel-таблицу со списком всех товаров и соответствующие им изображения в отдельную директорию.

![Выходные данные](https://github.com/kirich-yo/perekrestok-parser/blob/master/res/screenshots/5.png)

## Процесс парсинга

![Процесс парсинга](https://github.com/kirich-yo/perekrestok-parser/blob/master/res/screenshots/3.gif)

## Вывод парсера

Таблица Excel с перечнем всех товаров:

![Таблица Excel](https://github.com/kirich-yo/perekrestok-parser/blob/master/res/screenshots/1.jpg)

Картинки товаров с соответствующими ИД в таблице:

![Фото товаров](https://github.com/kirich-yo/perekrestok-parser/blob/master/res/screenshots/2.jpg)

## Необходимые модули

requests, BeautifulSoup, openpyxl, pyfiglet, Rich

Их можно установить, выполнив следующие команды:

```shell
pip install requests
pip install beautifulsoup4
pip install openpyxl
pip install pyfiglet
pip install rich
```