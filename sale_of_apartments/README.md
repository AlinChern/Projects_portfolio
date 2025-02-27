# Исследование объявлений о продаже квартир

**Данные для исследования** — это архив объявлений сервиса Яндекс.Недвижимость о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет.

**Цель исследования** — установить параметры, которые больше всего влияют на общую (полную) стоимость объекта. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

**Ход исследования** — выполним предобработку данных и изучим их, чтобы найти интересные особенности и зависимости, которые существуют на рынке недвижимости.

## Используемые библиотеки: pandas, matplotlib, seaborn, sklearn

# Общий вывод


В ходе исследования проанализировали архив объявлений сервиса Яндекс.Недвижимость о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет.

**Выявили параметры, которые больше всего влияют на общую стоимость объекта:**


- чем больше общая площадь объекта, тем выше его стоимость;
- чем больше жилая площадь объекта, тем выше его стоимость;
- чем больше количество комнат, тем выше его стоимость;
- объекты не на первом и не на последнем этажах, стоят дороже.


**Сформировали портрет основной части объектов. Это:**


- объекты с общей площадью примерно от 30 до 100 кв. м.;
- самое большое количество объектов с жилой площадью от 15 до 50 кв. м.;
- наибольшее количество объявлений с площадью кухни от 5 до 18 кв. м.;
- большая часть объектов в диапозоне от 2,5 млн. до 5,5 млн.;
- самыми популярными являются объекты с одной, двумя и тремя комнатами;
- основная часть объявлений с типом этажа - другой (не первый и не последний), самые популярные этажи до пятого;
- больше всего объектов с высотой потолков от 2,5 до 3 м.
- самые популярные объявления - это объекты в пятиэтажных и девятиэтажных домах;
- самое большое количество объявлений с расстоянием до центра города от 11 до 17 км, до ближайшего аэропорта 11-27 км, до ближайшего парка 200-600 м;
- чаще всего объявления публикуют с ПН по ПТ, с февраля по апрель и с сентября по ноябрь;

  **Заметим, что основная часть объектов продается в срок от 9 до 90 дней. В 2014 году была наиболее высокая стоимость квадратного метра. Самая высокая стоимость квадратного метра в центре Санкт-Петербурга, там же наибольшее количество объявлений.**
