Это набор учебных проектов, выполненных в процессе обучения на профессии "Специалист по Data Science" в Яндекс.Практикуме. <br>Каждый проект направлен на развитие практических навыков анализа данных и Data Science в различных областях, таких как машинное обучение, анализ временных рядов, работа с текстовыми данными и другие. Эти проекты помогают студентам применить теоретические знания в реальных задачах и подготовиться к работе в индустрии.


| Название проекта | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Сравнение пользователей сервиса Яндекс.Музыка](01_music_service) | В рамках проекта было проанализировано сравнение музыкальных предпочтений пользователей Яндекс.Музыки в Москве и Санкт-Петербурге в зависимости от времени суток (утро и вечер) и дня недели (понедельник, среда, пятница). Были использованы данные о проигрывании музыки пользователями этих городов в определенные периоды времени. Целью проекта было выявление различий в музыкальных предпочтениях пользователей в различных географических и временных условиях.| *Python pandas* |
| [Анализ банковских данных](02_bank_borrowers) |В данном проекте анализируются данные о платежеспособности клиентов с целью выяснить, как семейное положение и количество детей могут влиять на своевременность возврата кредитов. Предполагается, что есть зависимость между этими факторами и вероятностью возврата кредита в срок. Для анализа используются статистические методы.|*Python pandas* | 
| [Анализ рынка недвижимости](03_real_estate_market) | Для данного проекта используются данные сервиса Яндекс.Недвижимость для определения рыночной стоимости объектов недвижимости и выявления типичных параметров квартир. В процессе анализа данных будет изучено влияние таких параметров как площадь, количество комнат, этаж, удалённость от центра города, а также другие факторы на рыночную стоимость квартиры. Основная цель проекта - выявить наиболее значимые параметры и сформировать типичный портрет квартиры, чтобы помочь пользователям лучше понимать рынок недвижимости и принимать обоснованные решения при покупке или продаже недвижимости. | *Python Pandas Matplotlib* | 
| [Определение выгодного тарифа для телеком компании](04_tariff_telecom) | В рамках проекта необходимо проанализировать данные клиентов оператора сотовой связи с целью выявления особенностей их поведения. Используя полученные знания, требуется найти наиболее оптимальный тариф для клиентов, учитывая их потребности и поведение в использовании связи.| *Python Pandas Matplotlib NumPy SciPy* | 
| [CV. Обработка фотографий покупателя](05_age_determination) | Этот проект заключается в разработке алгоритма, который автоматически определяет возраст человека на фотографии. Для этого используются методы компьютерного зрения и машинного обучения, которые анализируют характеристики изображения для определения возраста.  | *Python Keras* | 
| [Классификаиция клиентов телеком компании](06_telecom_clients) | Данный проект предполагает анализ данных о поведении клиентов и подбор наиболее подходящего тарифа для каждого клиента. Для этого необходимо исследовать использование услуг каждым клиентом на разных тарифных планах, определить наиболее востребованные услуги и предложить клиентам тарифный план, который максимально соответствует их потребностям и может принести компании максимальную прибыль. | *Python Pandas Matplotlib Scikit-learn* | 
| [Прогнозирование оттока клиента Банка](07_churn_customer_bank) | Данный проект заключается в анализе данных банка с целью выявления клиентов, которые могут покинуть банк в ближайшее время. Для этого необходимо провести анализ различных параметров клиентов на основе исторических данных о поведении клиентов, которые ранее покинули банк. По результатам анализа строится модель, которая позволяет определить клиентов, которые наиболее вероятно покинут банк в ближайшее время. | *Python Pandas Matplotlib Scikit-learn* | 
| [Определение наиболее выгодного региона нефтедобычи](08_region_oil_production) | Этот проект направлен на выбор района добычи нефти на основе данных геологической разведки. Для этого требуется построить модель, которая на основе геологических данных будет определять наиболее подходящий район для добычи нефти. | *Pandas Scikit-learn бутстреп* | 
| [Исследование технологического процесса очистки золота](09_gold_refining) | На основе данных о процессе очистки золота необходимо построить модель  для прогнозирования концентрации золота в продукте после очистки. | *Python Pandas Matplotlib NumPy Scikit-learn* | 
| [Изучение закономерностей, определяющих успешность игр](10_game_success) | Этот проект заключается в анализе исторических данных о продажах компьютерных игр, а также оценок пользователей и экспертов, жанров и платформ. Цель проекта заключается в выявлении закономерностей, которые могут оказывать влияние на успешность игры. Используя эти данные, можно построить модель, которая предсказывает, какая игра может стать успешной в будущем, и определить на какую платформу лучше выпустить игру в зависимости от того, какие игры там наиболее популярны. | *Python Pandas NumPy Matplotlib* | 
| [Построение модели определения стоимости автомобиля](11_car_cost) | Данный проект заключается в разработке модели машинного обучения для системы рекомендации стоимости автомобиля на основе его описания. В процессе работы использовались различные характеристики автомобилей, такие как марка, модель, год выпуска, пробег, тип коробки передач и т.д., чтобы определить цену, по которой автомобиль может быть продан на рынке. | *Python Pandas lightgbm* | 
| [Прогнозирование количества заказов такси на следующий час](12_taxi_order_forecasting) | Используя исторические данные о заказах такси, разрабатывается система, которая предсказывает будущие объемы заказов. Это позволяет компаниям такси оптимизировать процессы планирования и распределения ресурсов, повышая эффективность работы и улучшая удобство обслуживания для клиентов. | *Python Pandas Scikit-learn statsmodels* | 
| [Обучение модели классификации комментариев](13_toxic_comments) | Данный проект заключается в анализе комментариев, оставленных пользователями в интернет-магазине, и определении токсичных комментариев. Это сделано с использованием алгоритмов машинного обучения, которые могут классифицировать комментарии как токсичные или нет, на основе различных признаков, таких как выбранные слова и выражения, длина комментария, использование символов и пр. | *Python Pandas nltk tf-idf* | 
