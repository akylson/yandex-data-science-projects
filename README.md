# Yandex Praktikum Data Science Projects

These projects were completed during the training at Yandex.Practicum

<table width=100% valign=top >
  <tr>
    <td>Project</td>
    <td>Description</td>
    <td>Used libraries</td>
  </tr>
  <tr>
    <td><a href="#">Toxic-comments</a></td>
    <td>Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.
Постройте модель со значением метрики качества F1 не меньше 0.75.</td>
    <td>Pandas</td>
  </tr>
  <tr>
    <td><a href="#">Taxi-timeline</a></td>
    <td>Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.
Значение метрики RMSE на тестовой выборке должно быть не больше 48.</td>
    <td>Pandas</td>
  </tr>
  <tr>
    <td><a href="#">Auto-price-prediction</a></td>
    <td>Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Вам нужно построить модель для определения стоимости.</td>
    <td>Pandas</td>
  </tr>
  <tr>
    <td><a href="#">Insurance-company</a></td>
    <td>Вам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы.
Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.</td>
    <td>Pandas</td>
  </tr>
  <tr>
    <td><a href="#">Gold-Prediction</a></td>
    <td>Подготовьте прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.
Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В вашем распоряжении данные с параметрами добычи и очистки.
Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.</td>
    <td>Pandas</td>
  </tr>
  <tr>
    <td><a href="#">GeoData-Prediction</a></td>
    <td>Вам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Постройте модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски техникой Bootstrap.</td>
    <td>Pandas</td>
  </tr>
  <tr>
    <td><a href="#">Bank-Churn-prediction</a></td>
    <td>Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.
Постройте модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте F1-меру на тестовой выборке самостоятельно.
Дополнительно измеряйте AUC-ROC, сравнивайте её значение с F1-мерой.</td>
    <td>Machine Learning</td>
  </tr>
  <tr>
    <td><a href="#">Mobile-Operator-machine learning</a></td>
    <td>В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы (из проекта курса «Статистический анализ данных»). Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных не понадобится — вы её уже сделали.

Постройте модель с максимально большим значением accuracy. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75. Проверьте accuracy на тестовой выборке самостоятельно.</td>
    <td>Machine Learning</td>
  </tr>
  <tr>
  <td><a href="#">Games-Analysis</a></td>
    <td>Интернет-магазин «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

Перед нами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и мы планируем кампанию на 2017-й. Нужно отработать принцип работы с данными. Не важно, прогнозируем ли мы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.
</td>
    <td>Pandas</td>
  </tr>
  <tr>
  <td><a href="#">Determination-of-promising-tariff-for-Megaline</a></td>
    <td>«Мегалайн» — федеральный оператор сотовой связи.
Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Проведем предварительный анализ тарифов на небольшой выборке клиентов. В нашем распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Проанализируем поведение клиентов и сделаем вывод - какой тариф лучше</td>
    <td>Pandas, Numpy, SciPy, Matplotlib, Math</td>
  </tr>
     <tr>
  <td><a href="#">EDA-of-apartments-for-sale</a></td>
    <td>В вашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.</td>
    <td>Pandas</td>
  </tr>
   <tr>
  <td><a href="#">Research-on-the-reliability-of-borrowers</a></td>
    <td>Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.</td>
    <td>Pandas</td>
  </tr>
  <tr>
  <td><a href="#">Yandex-Music</a></td>
    <td>Как музыка, которая звучит по дороге на работу в понедельник утром, отличается от той, что играет в среду или в конце рабочей недели? Имеются Данные для Москвы и Петербурга. Сравним, что и в каком режиме слушают их жители.</td>
    <td>Pandas</td>
  </tr>
</table>
