# Тестовое задание Street

## задание

Рейтинг посещаемости соседей

Моделируем Улицу на которой 5 заведений Продуктовый Магазин 1, Продуктовый Магазин 2, Аптека,
Парикмахерская, киоск а также вход на улицу и выход. (7 сущностей)
1. На входе в улицу случайно появляется посетитель из нормального распр. в среднем каждые 5 минут
и дисперсией 2 минуты.
2. У каждой сущности на улице есть изначально фиксированные вероятности посещения (кроме
входа=0).
P(Продуктовый Магазин 1)=3/10
P(Продуктовый Магазин 2)=3/10
P(Аптека) =1/10
P(Парикмахерская) =1/10
P(киоск)=1/10
P(выход)=1/10
3. Если посетитель посетил заведение A то он снова случайно посещает следующее после проведенного
времени в A. Он больше не хочет посещать A, поэтому вероятность посещения A прибавляется к выходу.
Например вышел из парикмахерской значит P(парикмахерской)=0, а P(выхода)=1/10+1/10
4.
-В продуктовых по 3 кассы посетитель равновероятно приходит на кассу, время обслуживания в

среднем 5 мин с дисперсией 2.

-В аптеке 2 кассы с теми же параметрами обслуживания,
-В киоске одна касса, среднее 3, дисперсия 2,
-В парикмахерской 2 парикмахера среднее время стрижки 20 и дисперсия 2
5. Составить таблицу путем моделирования жизни описанной улицы в течении 30 дней, рекомендуется
SimPy библиотека в питоне. Столбцы таблицы: [id_заведения, id_посетителя, время прихода, время ухода]. id_заведения, id_посетителя, время прихода, время ухода]. заведения, id_заведения, id_посетителя, время прихода, время ухода]. посетителя, время прихода, время ухода].
Представить ее в пандосе или в csv чтобы я мог ее увидеть и проверить.
6. Для всех компаний построить отчет (визуализация) количества посетителей по заведениям за час до и
за час после посещения заведения. Владелец например Аптеки Хочет видеть где бывают его посетители до него
и после него. Должен видеть количество посетителей в продуктовом за час до аптеки и за час после, и так же
количество в парикмахерской и остальных.


```python

```
