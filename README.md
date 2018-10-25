### Анализ датасета "Los Angeles Metro Bike Share Trip Data"  из проекта Los Angeles Open Data. 

В этот датасет входят данные о поездках на арендованных велосипедах. Данные являются обезличенными, и сообщают нам о длительности маршрута, его датах и времени, виде поездки, виде тарифного плана (клиента) и координатах поездки за период с июля 2016 г. по апрель 2017 г. Данные получены из открытого источника при помощи API Socrata и Kaggle и предварительно очищены от лишних данных, тестовых и пустых значений.

Основная задача анализа и цель исследования - найти взаимосвязь между показателями поездок и установить что влияет на ее характер в численных значениях. Определить, как повысить эффективность данного бизнеса, увеличить прибыль и сократить издержки.

*Исследовательские задачи:*
- Какая средняя длительность поездки на велосипеде?
- Какие тарифные планы пользуются большей популярностью у покупателей?
- Есть ли какой-то велосипед, который берут чаще? (чтобы узнать какой нужно заменить или отремонтировать)

*Для анализа использовались следующие переменные:*
- Duration - длительность поездки в секундах, была переведена в минуты
- Plan duration - количество дней по плану, приобретенному владельцем карты
- Bike ID - уникальный идентификатор велосипеда
- Trip Route Category - тип маршрута, в одну сторону или туда-обратно
- Start time - время начала поездки
- End time - время конца поездки
- Starting Station ID - точка А маршрута
- Ending Station ID - точка Б маршрута, если значения А и Б совпадают, то это был маршрут туда-обратно, в противном случае в одну сторону


[Посмотреть на анализ данных](../blob/master/FinalReport_FedorovaEkaterina_BicycleTrip.ipynb)
```
