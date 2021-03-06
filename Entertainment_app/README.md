# Описание проекта - Оптимизация маркетинговых затрат развлекательного приложения

## Данные

Структура visits_info.csv:  
User Id — уникальный идентификатор пользователя  
Region — страна пользователя  
Device — тип устройства пользователя  
Channel — идентификатор источника перехода  
Session Start — дата и время начала сессии  
Session End — дата и время окончания сессии.

Структура orders_info.csv:  
User Id — уникальный идентификатор пользователя  
Event Dt — дата и время покупки  
Revenue — сумма заказа.

Структура costs_info.csv:  
Channel — идентификатор рекламного источника  
Dt — дата проведения рекламной кампании  
Costs — расходы на эту кампанию.



## Задачи проекта
Нужно изучить:  
- как клиенты пользуются приложением
- когда начинают покупать
- сколько денег приносит каждый клиент
- когда расходы на привлечение клиента окупаются
- какие факторы мешают привлечению клиентов

## Описание проекта
Проведен анализ данных от Procrastinate Pro+ с целью оптимизации маркетинговых затрат.
Рассчитаны метрики LTV, CAC, ROI, Retention rate, DAU, WAU, MAU.


## Используемые библиотеки
pandas  
matplotlib