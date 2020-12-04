## Учебные проекты на курсе Data Science от Яндекс.Практикум
В репозитории собраны копии отчетов о проектах, выполненных на курсе [Data Science](https://praktikum.yandex.ru/data-scientist/) от [Яндекс.Практикум](https://praktikum.yandex.ru/) в 2020-2021 учебном году с использованием командной оболочки для интерактивных вычислений **Jupyter Notebook** на языке **Python**.

Проекты приведены в порядке выполнения, самый сложный - выпускной ([в конце списка](#Выпускной-проект)).

Репозиторий создан в первую очередь для демонстрации навыков автора **потенциальным работодателям**. Блокноты **Jupyter Notebook** поэтому переведены в формат pdf. Если Вы обучаетесь на курсе [Data Science](https://praktikum.yandex.ru/data-scientist/) от [Яндекс.Практикум](https://praktikum.yandex.ru/), настоятельно рекомендую Вам продолжать знакомиться с решениями уже после окончания соответствующего спринта. **Наборы данных не прикладываются** из-за правовых ограничений, так как являются плодом трудов многочисленного авторского коллектива, редакции и консультантов от ведущих компаний России.

### [Исследование надёжности заёмщиков](https://github.com/Bombardier2000/Data-Science-Yandex-Praktikum/tree/master/reports/01.01-Credit-Scoring.pdf)
Основной навык - предобработка данных (Jupyter Notebook, Python, pandas, re, pymorphy2).

Заказчик - кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка - статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга - специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

### [Исследование объявлений о продаже квартир](https://github.com/Bombardier2000/Data-Science-Yandex-Praktikum/tree/master/reports/01.02-Housing-market.pdf)
Основные навыки - классы Python, именованные кортежи (collections), HTTP-запросы (urllib.request), визуализация данных с помощью гистограмм и ящиков с усами (matplotlib, seaborn), изучение срезов данных (pandas), нахождение взаимосвязей разных параметров в данных (numpy), объединение таблиц, получение выводов по сгруппированным данным, отображение геопространственной информации ([folium](https://python-visualization.github.io/folium/), [OpenStreetMap](https://www.openstreetmap.org/)).

В вашем распоряжении данные сервиса Яндекс.Недвижимость - архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача - установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые - получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

### [Определение перспективного тарифа для телеком компании](https://github.com/Bombardier2000/Data-Science-Yandex-Praktikum/tree/master/reports/01.03-Telecom.pdf)
Основные навыки - выявление и обработка аномалий в данных, изучение объектов и их взаимосвязей методами статистики, работа с выборками, проверка гипотез (scipy.stats).

Вы аналитик федерального оператора сотовой связи. Клиентам предлагают два тарифных плана. Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять,
какой тариф приносит больше денег. Вам предстоит сделать предварительный анализ тарифов на небольшой выборке клиентов. Нужно проанализировать их поведение и сделать вывод, какой тариф лучше.

### [Определение перспектив продукта игровой компьютерной индустрии](https://github.com/Bombardier2000/Data-Science-Yandex-Praktikum/tree/master/reports/01.04-Combined-Project-1.pdf)
Сборный проект №1: основные навыки - все, приобретённые на предыдущих этапах обучения, а также специфическая визуализация данных (joypy) и парсинг сайтов (urllib, [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)). Мягкие навыки (англ. soft skills) - <u>юмор с элементами метасарказма</u>.

Вы работаете в интернет-магазине, который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о
продажах игр, оценки пользователей и экспертов, жанры и платформы. Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

### Выпускной проект
Отчет о выпускном проекте обязательно будет опубликован в своё время.
