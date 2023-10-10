# Курсовые работы

## 1. Каталог NFC меток
Приложение представляет собой каталог NCF меток
Приложение должно обеспечивать следующий функционал:
+ Чтение информации из меток типа MIFARE Classic и MIFARE Plus и хранения данных в БД. 
+ Необходимо читать и хранить следующие параметры: 
  * тип метки,
  * поддерживаемые технологии,
  * серийный номер,
  * все NDEF тэги,
  * комментарии к метке
+ При чтении уже зарегистированной метки должно запускаться приложение и отображать карточку метки
+ При чтении еще не зарегистрированой метки должно запускаться приложение с предложением сохранить метку в БД.

## 2. Карточки для интервального повторонения (Anki).
Доработать приложения Anki Light. Добавить функционал [интервальных повторений](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D1%80%D0%B2%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5_%D0%BF%D0%BE%D0%B2%D1%82%D0%BE%D1%80%D0%B5%D0%BD%D0%B8%D1%8F).
Приложение должно обеспечивать следующий функционал:
+ Пользователь должен иметь возможность указать сколько слов в день он хочет изучать.
+ Должно существовать как минимум 3 интервала: Не помню, Легко, Очень легко. Длительность каждого интервала настраивается пользователем. 
+ На каждый день должен формироваться список слов в зависимости от усвоения.
+ Программа должна содержать механизм для массовой загрузки слов из файла.

## 3. Тэги для карточек Anki
Доработать приложение Anki Light. Добавить функционал присвоения тегов для карточек.
Приложение должно обеспечивать следующий функционал:
+ Ведение каталога тэгов (наименовние, цвет). 
+ Присвоение одного или несколько тегов карточке.
+ Поиск карточки по тегам с возможность поиска по нескольким тегам (OR или AND)
+ Массовое присвоение или удаление тэгов
+ Механизм экспорта и импорта слов и тегов в файлы.

## 4. Курсы криптовалют
Разработать приложение для получения и отображения курсов криптовалют используя общедоступный API https://www.coinlore.com/ru/cryptocurrency-data-api
Приложение должно обеспечивать следующий функционал:
+ Получение списка всех криптовалют в виде списка с автоматической подгрузкой
+ Получение списка тикеров для монет.  Графики курса приветствуются.
+ Получение информации о биржах где торгуется криптовалюта
+ Получение курса как по отношению к USD, так и по отношению к другим криптовалютам.

## 5. Расписание занятий  БелГУ
Разработать приложение для просмотра расписания занятий БелГУ
Приложение должно обеспечивать следующий функционал:
+ Приложение позволяет просматривать расписание занятий любой группы за любой промежуток времени.
+ Приложение позволяет ввести заметки к занятиям.

## 6. Диктофон
Разработать приложение для ведения голосовых заметок.
Приложение должно обеспечивать следующий функционал:
+ Запись и хранение голосовых заметок.
+ Хранение мета информации к заметке: наименование, дата записи, длительность записи, геокоординаты записи.
+ Удаление заметок (массовое и единичное)
+ Отправку заметок с помощью других приложений ("Поделиться")


## 7. Любимые места на Yandex картах  
Разработать приложение для отображение любимых мест на Yandex картах.
Приложение должно обеспечивать следующий функционал:
+ Использовать [MapKit](https://yandex.ru/dev/maps/mapkit/?from=mapsapi) для отображения карт
+ Пользователь может установить на карте метку любимого места. Метка должна содержать:
  * Описание места
  * Фотографию места
  * Комментарии
+ Любимые места должны отображаться на карте, а также в виде списка. 

## 8. Манга-чтец
Разработать приложение для чтения манги в формате CBZ
Приложение должно обеспечивать следующий функционал:
+ Каталог файлов в формате CBZ с thumbnail первой страницы. 
+ Добавление удаление нового файла
+ Просмотр содержимого файла 
+ Переход межу страницами вперед и назад
+ Сохранение закладки для чтения

## 9. Общий ToDo List в Firebase
Разработать приложение для ведения общего списка дел.
+ Список дел доступен только авторизованным пользователям (Авторизация по логину/паролю)
+ В приложении доступна саморегистрация пользователей
+ Для хранения списка дел используется Firebase Realtime Database
+ При изменении списка дел всем пользователям отправляется Push уведомление

## 10. Своя тема




