# Дашборд 'Dream Parser Dashboard' выполнен в DataLens

Ссылка на дашборд: https://datalens.yandex/1wwva6aigvp0q

### Описание дашборда
Данные парсят ежедневно с джобордов: hh, vseti, хабр. На дашборде вы можете увидеть количество вакансий, работодателей, среднуюю зп за выбранный период. Показана динамику количества вакансий и динамику заработной платы. Выделены топы по количеству вакансий по разным категориям (компания, направление аналитики, город и др.). Можно подобрать релевантные вакансии с помощью фильтров и перейти по ссылки на вакансию. Дополнительно, можно оценить наиболее востребованные навыки и посмотреть географию размещения вакансий.

## Что было сделано
Перед разборкой дашборда была проведена предобработка сырых данных на уровне датасета. Изменены необходимые типы данных, созданы дополнительные расчетные поля, параметры, фильтры. Использовались SQL запросы к СУБД Click House, регулярные выражения, оконные функции, ранжирование, URL ссылки.

## Чарты
Индикаторы, комбинированные диаграммы со скользящим средним, линейчатые и столбчатые диаграммы, таблица, карта. 
