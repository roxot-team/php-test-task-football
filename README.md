# Тестовое задание для php разработчика
## Описание
У нас есть популярный (высоконагруженный) сайт с текстовыми трансляциями футбольных матчей.
Мы сотрудничаем с посредником, который предоставляет логи матчей. 
Каждый лог состоит из списка событий разного типа в json формате. 
Необходимо разработать модуль генерации статичных html страниц с текстовыми трансляциями матчей на основе данных из логов. 

## Бизнес задача
Получить страницу с текстовой трансляцией матча в удобном и приятном для читателей виде.
 
## Техническая задача
Вы должны разработать модуль, который парсит логи из дирректории **/source/matches/**, 
генерирует html страницы с текстовыми трансляциями матчей и информационными блоками 
и сохраняет результат в html файлы в директорию **result/**.

Информационный блок матча должен содержать:
* Общий результат матча;
* Краткое описание важных событий;
* Список основных игроков;
* Список игроков, которые вышли на замену;
* Список запасных игроков;
* Время, проведенное каждым игроком на поле;
* Информацию о том, сколько игрок забил мячей и сколько сделал голевых передач;
* Получал ли игрок желтые и красные карточки;

## Результат
Код должен быть оформлен в виде git репозитория, который содержит несколько коммитов, показывающих ход вашей работы. 

Проект должен содержать README.md файл, который:
* Содержит ФИО автора;
* Содержит потраченное на тестовое задание время;
* Описывает архитектуру модуля;
* Поясняет принятые решения;
* Содержит инструкцию по интеграции и использованию модуля;

**Дополнительным плюсом** будет покрытие модуля unit тестами.

Репозиторий Вы можете либо выслать нам на почту в виде архива, либо разместить на любом публичном хостинге репозиториев (GitHub, BitBucket).

## Что мы хотим увидеть
* Использование php 5.6 или 7.0;
* Использование ООП;
* Использование twitter bootstrap;
* Понятный код;
* Уверенное владение git;

## Мы не требуем
* Идеального дизайна;
* Интерактивности на сгенерированной html странице;
* Адаптивной верстки;

## Для справки
Это лог реального матча между командами Маккаби (Тель-Авив) и Зенит (Санкт-Петербург), который прошел 15 сентября 2016 года. Матч получился очень интересным и драматичным.

Текстовую трансляцию мы брали с сайта soccer.ru (https://www.soccer.ru/matches/1024102/makkabi-zenit-15-09-2016). Ее провел Старчеус Сергей, за что ему большое спасибо.