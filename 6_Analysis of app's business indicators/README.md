# Анализ бизнес показателей приложения 
В данном проекте проведен поиск причин убытка развлекательного приложения в последние несколько месяцев и поиск путей выхода компании в плюс. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д.
## Задачи:
1. поиск каналов откуда приходят пользователи и используемых устройств;
2. выявление стоимости привлечения пользователей из различных рекламных каналов;
3. определение доходов с каждого клиента;
4. выявление факторов окупаемости расходов на привлечение клиента;
5. выявление факторов мешающие привлечению клиентов.
## Ход исследования:
- Предобработка данных;
- Расчёт и анализ LTV, ROI, удержания и конверсии;
- Исследовательский анализа данных;
- Маркетинговый анализ;
- Оценка окупаемости рекламы;
- Выводы.

## Общие выводы
Анализ подтвердил, что развлекательное приложение Procrastinate Pro+ вкладывает огромные инвестиции в рекламу, которые не окупаются последние несколько месяцев. В выбранный отрезок месяцев (май-сентябрь), показал сезонный рост LTV пользователей в середине июня и августа, но в то же время увеличились вложения в рекламу (CAC), но не окупаемость (ROI). Тем не менее, в целом динамика в сторону окупаемости стабильно растет и стал чуть выше 80% Были сделаны следующие основные выводы по странам, устройствам и рекламным каналы, которые могут оказывать негативное влияние на окупаемость рекламы:
- Почти половина с общей суммой расходов на маркетинг идет на канал 'TipTop', с которого пришло относительно большое количество пользователей, но канал является самым не окупаемым. Каналы, которые больше всего проседают по удержанию пользователей -Faceboom, AdNonSense. Оба канала занимают второе и третье место по полученным вложениям за рекламу, но их стоимость привлечения не изменялась и намного ниже канала лидера по стоимости - TipTop. TipTop хоть и имеет средние показатели по конверсии и динамике удержания платящих пользователей (относительно других), но в сравнении с тем насколько были значительны вложения в него по рекламе, результаты могли были быть намного лучше. YRabbit и RocketSuperAds являются более перспективными.
- В графике стоимости вложений за рекламу США является лидером, а также он имеет самое большое количество платящих пользователей, но среди удержания платящих пользователей он является самым отстающим.
- Самым популярным устройством среди пользователей платформы является iPhone. Среди платящих пользователей большая доля у устройств Mac и iPhone, на которые приложение также инвестирует значительную стоимость на рекламу для привлечения пользователей. В то же время устройства iPhone и Mac имеют высокие показатели конверсии и средние в удержании платящих пользователей. Однако, так же как и TipTop, по сравнению со стоимость вложений в них, от них ожидаются лучше результаты.


Таким образом, возможной проблемой окупаемости может быть то, что каналы не учли определенные региональные особенности американских пользователей, например, содержание рекламы, форма его подачи, частота и время отправлений.

## Рекомендации:
- Стоит отметить, что на платформу пришли больше всего органических пользователей, тем самым факторами, мешающими привлечению пользователей и проблемой в окупаемости может быть навязчивая или не таргетированная реклама. Возможно стоит пересмотреть необходимость большого объема вложений на рекламу в целом и вышеуказанных рекламных каналов, устройств и страны.
- Во всех графиках прослеживается сезонный фактор, что желательно учитывать для удержания пользователей. Расходы на привлечение клиента окупаются чаще всего во время летних сезонных периодов где-то в середине июня и августа.
- Стоит обратить внимание на Android пользователей, поскольку на них тратиться среднее количество рекламы, они ближе к окупаемости и имеют высокую положительную динамику LTV, то есть платящих пользователей.
- Среди каналов выделяется YRabbit, который является лидером по окупаемости с самым наименьшим вкладом на рекламу. Количество пользователей и динамика платящих пользователей выше среднего. Также стоит обратить внимание на канал lambdaMediaAds, на которую меньше вкладываются на рекламу, но который окупается и имеет больше всего платящих пользователей.
