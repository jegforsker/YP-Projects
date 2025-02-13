# Принятие решений в бизнесе на основе данных

## Данные

Файл /datasets/hypothesis.csv
- Hypothesis — краткое описание гипотезы;
- Reach — охват пользователей по 10-балльной шкале;
- Impact — влияние на пользователей по 10-балльной шкале;
- Confidence — уверенность в гипотезе по 10-балльной шкале;
- Efforts — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.

Файл /datasets/orders.csv
- transactionId — идентификатор заказа;
- visitorId — идентификатор пользователя, совершившего заказ;
- date — дата, когда был совершён заказ;
- revenue — выручка заказа;
- group — группа A/B-теста, в которую попал заказ.

Файл /datasets/visitors.csv.
- date — дата;
- group — группа A/B-теста;
- visitors — количество пользователей в указанную дату в указанной группе A/B-теста

## Задача
В крупном интернет-магазине совместно с отделом маркетинга необходимо проверить сформулированные гипотезы, запустить A/B-тест и проанализировать результаты

## Выводы
Показатели группы В лучше показателей группы А.  
Достоверно известно, что среднее кол-во заказов в группе В выше, чем в группе А, при этом средние чеки по очищенным данным примерно равны и статистически значимых результатов по разнице в них мы не получили. Поскольку результаты группы В зафиксировались, продолжение А/В-теста вряд ли имеет смысл.

## Используемые библиотеки
pandas, scipy, matplotlib, seaborn, datetime, numpy
