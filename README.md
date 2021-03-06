# Репозиторий по направлению "Аналитик данных" и "Специалист по Data Science"

## Описание проектов в README.md

Рекомендация по тарифам.
Есть данные о поведении клиентов, которые уже перешли на тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных не предполагается.
Строим модель с максимально большим значением *accuracy*. 

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Classification_model_for_tariffs_telecom_operator] | Строим модель для задачи классификации с максимально большим значением *accuracy*. | *pandas*, *sklearn* |

Проект для интернет-магазина.
Интернет-магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Необходимо обучить модель классифицировать комментарии на позитивные и негативные. 
В распоряжении есть набор данных с разметкой о токсичности правок. Строим модель со значением метрики качества F1 не меньше 0.75.

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Classification_model_NLP_BERT] | Обучение модели с целью классифицировать комментарии на позитивные и негативные. | *pandas*, *sklearn*, *nltk* |

Определение возраста покупателей.
Данные взяты с сайта ChaLearn Looking at People. Нужно построить модель для определения возраста покупателя на основе фотографии на основе большой выборки.

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Customers_age_definition] | Строим модель для определения возраста покупателя на основе фотографии на основе большой выборки. | *pandas*, *tensorflow*, *statsmodels* |

Спрос на рейсы авиакомпании.
Важно понять предпочтения пользователей, покупающих билеты на разные направления (внутренние пассажирские перевозки).
Стоит задача изучить базу данных и проанализировать спрос пассажиров на рейсы в города, где проходят крупнейшие культурные фестивали.

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Flights_query_analysis] | Задача изучить базу данных и проанализировать спрос пассажиров на рейсы в города | *pandas*, *stats* |

Интернет-магазин компьютерных игр.
В интернет-магазине, который продаёт по всему миру компьютерные игры, доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы 
(например, Xbox или PlayStation). Необходимо выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. 

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Games_production_analysis] | Строим модель для закономерностей успешности компьютерных игр. | *pandas*, *scipy* |

Восстановление золота из руды.
Стоит задача подготовить прототип модели машинного обучения для компании, которая разрабатывает решения для эффективной работы промышленных предприятий.
Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Используются данные с параметрами добычи и очистки.
Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [ML_model_for_coefficient_prediction] | Строим модель для задачи прогнозирования коэффициента восстановления золота из золотосодержащей руды. | *pandas*, *sklearn* |

Выбор локации для скважины.
В данных есть пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Стоит задача построить модель машинного обучения, которая поможет определить регион, где добыча 
принесёт наибольшую прибыль. Анализ возможной прибыли и рисков осуществлен техникой Bootstrap.

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [ML_model_for_maximizing_PnL] | Стоит задача построить модель машинного обучения, которая поможет определить регион, где добыча нефти принесёт наибольшую прибыль | *pandas*, *sklearn*, *scipy* |

Исследование объявлений о продаже квартир.
В архиве объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет представлены данные сервиса Яндекс.Недвижимость. Определим рыночную стоимость объектов недвижимости. 
Задача — установить параметры, которые позволят построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

| Название проекта | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Model_for_defenition_of_real_estate_price] | Задача — определить рыночную стоимость объектов недвижимости и построить автоматизированную систему для отслеживания аномалий | *pandas*, *seaborn*, *matplotlib* |

Определение стоимости автомобилей.
В распоряжении есть исторические данные: технические характеристики, комплектации и цены автомобилей, предоставленных сервисом по продаже автомобилей с пробегом. Стоит задача построить модель для определения стоимости автомобиля.

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Model_to_define_car_price] | Стоит задача построить модель для определения стоимости автомобиля. | *pandas*, *sklearn*, *CatBoostRegressor*, *LGBMRegressor*, *DecisionTreeRegressor* |

Отток клиентов.
Поставлена задача спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Есть исторические данные о поведении клиентов и расторжении договоров с банком.
Построим модель с предельно большим значением F1-меры (до 0.59). Проверка F1-меру на тестовой выборке. Дополнительно измеряйте AUC-ROC, сравнивайте её значение с F1-мерой.

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Prediction_of_churn_rate_in_bank] | Поставлена задача спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. | *pandas*, *sklearn*, *matplotlib* |

Рекомендация по оттоку.
Оператор связи хочет прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные 
данные о некоторых клиентах, информацию об их тарифах и договорах.

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Prediction_of_churn_rate_of clients] | Строим модель для прогноза оттока клиентов из сотового оператора. | *pandas*, *sklearn*, *matplotlib*, *CatBoostClassifier*, *LGBMRegressor*, *Pipeline* |

Прогнозирование заказов такси.
Построим модель для предсказания количество заказов такси на следующий час (для привлечения большего числа водителей в период пиковой нагрузки).
Значение метрики RMSE на тестовой выборке должно быть не больше определенного порога (48).

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Prediction_of_taxi_orders] | Построим модель для предсказания количество заказов такси на следующий час. | *pandas*, *sklearn*, *catboost*, *lightgbm*, *xgboost*, *statsmodels* |

Исследование надёжности заёмщиков.
Стоит задача разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Research_of_borrowers_reliability] | Стоит задача разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. | *pandas* |

Рекомендация по тарифам.
В данном проекте предстоит сделать предварительный анализ тарифов федерального оператора сотовой связи на небольшой выборке клиентов.
С целью скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

| Название папки | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [User_behavior_analysis] | С целью скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. | *pandas*, *sklearn*, *seaborn*, *matplotlib* |















