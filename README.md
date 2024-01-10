
<strong>Привет! Меня зовут Вячеслав.</strong>
Я начинающий аналитик данных.
В данном репозитории вы можете ознакомиться с моими проектами которые я выполнял во время обучения и практики.

Инструменты для анализа данных: <strong>SQL/Excel/PYTHON</strong>

<strong>МОИ ПРОЕКТЫ:</strong>

<h2>Калькулятор юнит-экономики онлайн кинотеатра (Excel) </h2>

<strong>Что требовалось сделать:</strong>
Онлайн-кинотеатр работает по модели ежемесячной подписки. У руководства возник вопрос: насколько это эффективная система с точки зрения финансовой составляющей? 
Это значит, что необходимо посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность и собрать наглядную визуализацию, где будет показано, кто, где и в каком объеме смотрит фильмы на данной платформе.

<strong>Ссылка для ознакомления с проектом:</strong>
https://docs.google.com/spreadsheets/d/1qIltf-s3egnjlFE6oSyC10edBtaJk6tY/edit?usp=sharing&ouid=101742594754056706914&rtpof=true&sd=true

<strong>Вывод:</strong>
При пересчёте маржинальности до уровня 25 % наблюдается рост следующих показателей: Retention увеличился с 80,6 % до 96,7%; Life time за месяц вырос с 5,15 до 30,45; LTR увеличился с 1610 рублей до 11607 рублей. Не значительный рост показывает показатели фактической цены и прайс на юнит, цена выросла  с 312,46 рублей она поднялась до 381,20 рублей, а прайс на юнит с 350 рублей до 427 рублей соответственно. Без изменений остался объём скидок и CAC. А вот CAC на юнит резко снизился и составил 19 %.
В ходе исследования выявлено что большинство пользователей пользуются онлайн кинотеатром из западных регионов страны. Динамика оплат и как следствие прибыль с марта по июнь показывали уверенный рост, но к августу снизились. Снижение к концу лета показывала и динамика просмотров. Возможно, это является следствием того, что Retention показал снижение с июня по август.   


<h2>Аналитика онлайн университета (SQL)</h2>

<strong>Что требовалось сделать:</strong>
В данном проекте я создал модель изменения балансов студентов. (Баланс — это количество уроков, которое есть у каждого студента). 
Чтобы проверить, всё ли в порядке с  данными и составить список гипотез и вопросов, важно было понимать: 
- Сколько всего уроков было на балансе <strong>всех учеников</strong> за каждый календарный день
- Как это количество менялось под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков)
- Создание таблицы, где отображаются балансы <strong>каждого студента</strong> за каждый день

<strong>Ссылка для ознакомления с проектом:</strong>
https://docs.google.com/document/d/15F0qg_hDmYk-EctN6SWz6YXHaYrvlYa6/edit?usp=sharing&ouid=101742594754056706914&rtpof=true&sd=true

<strong>Вывод:</strong>
Модель изменения балансов студентов показывает то, как они менялись в течении 2016 года. На графике видно, что суммы транзакций и суммы уроков за рассматриваемый период времени оставалась примерно на одном и том же уровне. При этом наблюдается плавный рост суммы баланса к концу года и более резкий рост кумулятивных сумм как транзакций, так и уроков. 
Кроме вышеизложенного, при анализе данных возник вопрос к дата инженерам. Дело в том, что если отобрать 1000 строк из СТЕ balance с сортировкой по user_id и dt то видно что часть строк из колонки balance принимают отрицательные значения. Например, транзакций было 24, при этом списано, уроков 27 и как итог balance -3. А вот в самом начале таблицы всё вполне обычно и таких странных перекосов нет.

<h2>Аналитика онлайн университета (PYTHON/EXCEL)</h2>

<strong>Что требовалось сделать:</strong> 
Основная задача – в качестве сотрудника отдела продуктовой аналитики проанализировать АБ-Тест крупного ретейлера, тест был проведен в различных городах России. Я анализировал и визуализировал результаты, провел сегментацию, а также сделал выводы и сформулировал рекомендации для дальнейших запусков АБ Теста. Построил таблицу, которая в удобной форме хранит результаты АБ Теста.

<strong>Ссылка для ознакомления с проектом:</strong>
https://drive.google.com/file/d/1uyFK7P259dBvlhyIwaOJJA3aNGJZOti4/view?usp=sharing

</strong>Вывод:</strong>
После исключения торговых точек не имеющих платежей, а также точек с пустой контрольной либо тестовой группы, в результирующие таблицы попала 51 торговая точка. Из них 33% или 17 торговых точек прошли тестирование с позитивным исходом (тест был успешен), 6% или 3 торговые точки прошли тестирование с негативным исходом (тест не был успешным) и 61% или 31 торговая точка в результате проведённого А/Б тестирования не выявили существенной разницы между контрольной и тестовой группами. 



