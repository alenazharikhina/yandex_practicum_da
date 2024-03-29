# Анализ бизнес-показателей развлекательного приложения Procrastinate Pro+
### Описание проекта
В нашем распоряжении данные для анализа развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки.
Есть данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года:
- лог сервера с данными об их посещениях,
- выгрузка их покупок за этот период,
- рекламные расходы.
### Цель проекта
Наша задача — разобраться в причинах убытков и помочь компании выйти в плюс. Нам предстоит изучить:
- откуда приходят пользователи и какими устройствами они пользуются,
- сколько стоит привлечение пользователей из различных рекламных каналов;
- сколько денег приносит каждый клиент,
- когда расходы на привлечение клиента окупаются,
- какие факторы мешают привлечению клиентов
## Stack
- Pandas
- Matplotlib
- Numpy
- Seaborn
## Общий вывод
Реклама, направленная на привечение пользователей в целом, не окупается, в конце второй недели уровень достигает лишь 80%. Динамика стоимости привлечения пользователей постоянно растет, что говорит об увеличении расходов на рекламу от месяца к месяцу.
В разрезе по странам мы видим, что реклама окупается в странах Европы, но не окупается в США. При детальном рассмотрении рекламных каналов видно, что убыточны два самых крупных канала привлечения в США - TipTop и FaceBoom и один канал Европы - AdNonSense.

С учетом того, что рынок США составляет 67% от общей массы пользователей, убытки от привлечения пользователей страны полностью перекрывают доходы окупаемых стран. Итоговой причиной убытков компании за представленный период - маркетинг, направленный в большей мере на привлечение пользователей по двум источникам: TipTop и FaceBoom. Расходы, потраченные на рекламу в этих каналах значительно превышают выручку, которую приносят пришедшие в приложение пользователи.

**Рекомендации отделу маркетинга**
- Постараться выяснить причину плохого удержания пользователей каналов FaceBoom и AdNonSense.
- Оценить целесооразность высокой стоимости привлечения в канале TipTop.
- Наиболее перспективными и эффективными рекламными каналами мы можем назвать lambdaMediaAds в Европе и RocketSuperAds в США, там мы видим хороший уровень окупаемости и конверсии пользователей при высоком уровне их удержания и средней стоимости привлечения, на них стоит обратить внимание впервую очередь.
