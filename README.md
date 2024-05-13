# Описание проекта
В даном проекте анализируется рынок вторичного жилья в Москве. Рассматриваются 1, 2, 3 - комнатные квартиры(апартаменты не рассматриваются) в разных районах города. Цель проекта - выявление показателей, которые влияют на цену квартир, а так же выявление характерных особенностей квартир с похожими характеристиками. В результате проекта планируется создание модели, которая будет предсказывать цены на вторичное жилье.

Проект включает в себя 4 части: парсинг, eda и визуализации, проверка гипотез, машинное обучение. 
# Парсинг
Данные собирались из объявлений о продаже квартир с Циана. Собирплись следующие признаки:
1. Район - район, в котором находится находится квартира
2. Улица - улица, на которой находится дом
3. Станция метро - ближайшая к дому станция метро
4. Время до метро, мин. - время до ближайшей станции метро
5. Количество комнат - количество комнат в квартире
6. Общая площадь, м.кв. - общая площадь квартиры
7. Жилая площадь, м.кв. - площадь жилых комнат квартиры
8. Цена - цена квартиры
9. Год постройки - год постройки дома
10. Тип дома - тип постройки дома
11. Этаж - этаж, на котором находится квартира
12. Количество этажей в доме - общее количество этажей в доме, в котором находится квартира
13. Площадь кухни, м.кв. - площадь помещения кухни
14. Количество санузлов - количество санузлов в кваптире
15. Тип ремонта - тип ремонта в квартире
16. Количество подъездов в доме - количество подъездов в доме
Целевая переменная - цена.
После сбора данных они были сохранены в файл cian.csv
# EDA и визуализации 
В ходе этапа таблица с данными была изменена для удобной работы: пропуски были изменены на 0/пустые значения, изменен тип данных некоторых столбцов, новый датафрейм был сохранен в файл cian1.сsv.

С помощью метода describe получили основные статистические характеристики признаков, которые были в численном виде. Далее была составлена матрица корреляции и выявлены взаимосвязи(или их отсутствие) между признаками. Также были созданы графики распределения и зависимости признаков. 

# Проверка гипотез
На основе визуализаций нами были выдвинуты следующие гипотезы: 
1. Самые дорогие квартиры находятся ближе к центру Москвы
2. Самые большие по площади квартиры находятся ближе к центру Москвы, а самые маленькие - ближе к окраинам
3. Чаще всего продают 3-комнатные квартиры
4. Чаще всего продают квартиры, которые находятся ближе к центру
5. Количество подъездов в доме не влияет ни на что

(будет дополняться)

