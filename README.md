# Курс Машинное обучение, ФТиАД 2018

### Где и когда
Занятия проходят по субботам, 12:10 - 15:00, ауд. 311.

### Ссылки
Канал в telegram для объявлений: https://t.me/joinchat/AAAAAFDWMYIkKSfGPEb_4w

Anytask курса: https://anytask.org/course/390 (инвайт Kw4G1Bf). Все практические задания нужно сдавать в Anytask (загрузить в соответствующую задачу).

[Таблица с оценками](https://docs.google.com/spreadsheets/d/1u832G7b9aRyayoncaKXr7XPD6WisDr85AYRBKSVCMq0/edit?usp=sharing)

### Правила выставления оценок
В курсе предусмотрено несколько форм контроля знания:
* Самостоятельные работы на семинарах, проверяющие знание основных фактов с лекций
* Домашние работы (на Python и теоретические)
* Контрольная работа
* Письменный экзамен

Итоговая оценка вычисляется на основе оценки за работу в семестре и оценки за экзамен:

O<sub>итоговая</sub> = 0.7 * O<sub>накопленная</sub> + 0.3 * О<sub>экз</sub>

Оценка за работу в семестре вычисляется по формуле

O<sub>накопленная</sub> = 0.2 * O<sub>самостоятельные</sub> + 0.6 * О<sub>домашние задания</sub> + 0.2 * О<sub>контрольная</sub>

Оценка за самостоятельную работу вычисляется как среднее по всем самостоятельным, оценка за домашнюю работу — как среднее по всем домашним заданиям.

Накопленная, экзаменационная и итоговая оценки округляются арифметически.

### Правила сдачи домашних заданий

Дедлайн по теоретическим заданиям — начало следующего занятия (жесткий).

Дедлайн по практическим заданиям — 02:00 следующей пятницы (мягкий), 23:59 воскресенья (жесткий). 

За каждый день просрочки после мягкого дедлайна снимается 2 балла. После жёсткого дедлайна работы не принимаются. Два раза за курс жесткий дедлайн можно просрочить.

Некоторые практические задания нужно не только загрузить в Anytask, но и предварительно сдать в Яндекс контест. В этом случае в контесте вы будете видеть результаты проверки своих функций. Предварительно на контесте нужно зарегистрироваться. Чтобы ваши решения было возможно идентифицировать, __обязательно__ указывайте в решении ссылку на вашу финальную посылку в Яндекс контест.

При обнаружении плагиата оценки за домашнее задание обнуляются всем задействованным в списывании студентам, а также подаётся докладная записка в деканат. Следует помнить, что при повторном списывании деканат имеет право отчислить студента.

При наличии уважительной причины пропущенную проверочную можно написать позднее, а дедлайн по домашнему заданию может быть перенесён (при этом получить дополнительные баллы за призовые места на конкурсе можно только при участии в общий срок). Дедлайн по домашнему заданию переносится на количество дней, равное продолжительности уважительной причины. Решение о том, является ли причина уважительной, принимает исключительно учебный офис.

### Контрольная работа
Контрольная работа будет проводиться 3 ноября в 12:10 вместо лекции в ауд.311. Длительность контрольной работы - 1 час 20 минут. Второй пары в этот день не будет.

[Вопросы к контрольной работе](https://github.com/ftad/ML2018/blob/master/materials/%D0%92%D0%BE%D0%BF%D1%80%D0%BE%D1%81%D1%8B%20%D0%BA%20%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%BE%D0%BB%D1%8C%D0%BD%D0%BE%D0%B8%CC%86%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B5.pdf)

Контрольная работа будет включать в себя два теоретических вопроса, составленных из вопросов в списке, а также две задачи.

### Материалы занятий
__1. Введение в машинное обучение. Основы языка python__
* [Презентация по введению](https://github.com/ftad/ML2018/blob/master/materials/lesson1/lecture_intro.pdf) (по материалам Е. Соколова)
* [Ноутбук по python](https://github.com/ftad/ML2018/blob/master/materials/lesson1/Seminar_python.ipynb) (ссылки на материалы в конце ноутбука)
* [Конспект по введению](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/lecture-notes/lecture01-intro.pdf)

__2. Библиотеки numpy и pandas__
* [Ноутбук с семинара](https://github.com/ftad/ML2018/blob/master/materials/lesson/Numpy_pandas_seminar.ipynb)
* [Advanced problems](https://github.com/ftad/ML2018/blob/master/materials/lesson/problems_numpy.ipynb)
* Материалы по numpy:
    * [Ноутбук с прошлогоднего семинара: numpy, pandas, matplotlib __MUSTREAD__](https://github.com/nadiinchi/HSE_FCS_seminars/blob/master/materials/sem.01.ipynb)
    * [Англоязычный подробный туториал по numpy](http://nbviewer.jupyter.org/github/Atlas7/scipy-tentative-numpy-tutorials/blob/master/tentative-numpy-tutorial.ipynb)
    * [Вводный ноутбук - более подробно основы](https://github.com/nadiinchi/HSE_minor_DataAnalysis_seminars_iad16/blob/master/materials/Sem2_NumPy.ipynb)
*  Материалы по pandas:
    * [Официальная документация pandas - подробнейшие туториалы на английском](http://pandas.pydata.org/pandas-docs/stable/10min.html)
    * [Подробный ноутбук-туториал про pandas с майнора](https://github.com/nadiinchi/HSE_minor_DataAnalysis_seminars_iad16/blob/master/materials/Seminar3_pandas.ipynb)
    
__3. Градиентные методы оптимизации. Линейная регрессия__
* [Конспект лекции](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/lecture-notes/lecture02-linregr.pdf)
* [Конспект семинара](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/seminars/sem03-linregr.pdf)
* [Ipynb по предобработке данных](https://github.com/ftad/ML2018/blob/master/materials/lesson3/sem_preprocessing.ipynb)
* [Базовый туториал по sklearn в офиц. документации](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)
* Дополнительно: [Материалы по матричному дифференцированию](https://www.cs.ox.ac.uk/files/723/NA-08-01.pdf)

__4. Фнукции потерь в регрессии. Регуляризация в линейной регрессии__
* [Конспект по функциям потерь 1](https://github.com/ftad/ML2018/blob/master/materials/lesson4/preprocessing_and_loss_funcs.ipynb) (вторая часть)
* [Конспект по функциям потерь 2](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/lecture-notes/lecture02-linregr.pdf)
* [Конспект по регуляризации](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/lecture-notes/lecture03-linregr.pdf)

__5. Вероятностный подход к машинному обучению. Линейная классификация__
* [Конспект по вероятностному подходу](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/seminars/sem04-linregr.pdf)
* [Конспект по линейной классификации (до метрик)](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/lecture-notes/lecture04-linclass.pdf)
* [Конспект по оцениванию вероятностей и логистической регрессии](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/lecture-notes/lecture05-linclass.pdf)

__6. Линейная классификация (продолжение). Метрики качества классификации__
* [Конспект по SVM](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/lecture-notes/lecture05-linclass.pdf)
* [Конспект по метрикам качества](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/lecture-notes/lecture04-linclass.pdf)
* [Конспект по построению ROC кривой + задачи на ROC кривую](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/seminars/sem05-linclass-metrics.pdf)
* [Конспект по многоклассовой классификации](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/lecture-notes/lecture06-linclass.pdf)
* [Ноутбук с визуализацией кривых](https://github.com/ftad/ML2018/blob/master/materials/lesson6/roc_rpc_vis.ipynb)

__7. Решающие деревья__
* [Конспект лекции](https://github.com/esokolov/ml-course-hse/blob/master/2017-fall/lecture-notes/lecture07-trees.pdf)
* [Конспект с задачами на критерии информативности](https://github.com/esokolov/ml-course-hse/blob/master/2017-fall/seminars/sem07-trees.ipynb)

__8. Метрические методы__
* [Конспект лекции](https://github.com/esokolov/ml-course-hse/blob/master/2017-fall/seminars/sem06-knn.pdf)
* [Более подробно про Locality Sensitive Hashing](https://github.com/esokolov/ml-course-msu/blob/master/ML16/lecture-notes/Sem03_knn.pdf)
* [Презентация с описание метода отбора объектов STOLP (слайды 15-19)](http://www.machinelearning.ru/wiki/images/archive/c/c3/20150216123138%21Voron-ML-Metric-slides.pdf)
* [Презентация про применение 1NN в базах данных](http://www.machinelearning.ru/wiki/images/9/95/BMMO_16_Ivanov_DBMS.pdf)

### Задания
* [Домашнее задание 1: python](https://github.com/ftad/ML2018/blob/master/materials/lesson1/homework1.ipynb). Дедлайн: мягкий 02:00 15.09.18, жесткий 23:59 16.09.18
* [Домашнее задание 2: numpy, pandas](https://github.com/ftad/ML2018/blob/master/materials/lesson/homework2.ipynb) Деллайн: мягкий 02:00 22.09.18, жесткий 23:59 23.09.18
* [Домашнее задание 3: векторное дифференцирование](https://github.com/ftad/ML2018/blob/master/materials/lesson3/homework03-linreg.pdf) Деллайн: 12:10 29.09.12 (сдавать на листочке на занятии 29 сент)
* [Домашнее задание 4: линейная регрессия](https://github.com/ftad/ML2018/blob/master/materials/lesson4/homework4.ipynb). [Данные](https://github.com/esokolov/ml-course-hse/blob/master/2018-fall/homeworks-practice/data/homework-practice-03-data.csv). [Яндекс контест](https://contest.yandex.ru/contest/9247). [Альтернативная ссылка на Яндекс контест](https://official.contest.yandex.ru/contest/9247) В Anytask: задача linreg. Дедлайн: мягкий 02:00 06.10.18, жесткий 23:59 07.10.18
* [Домашнее задание 5: вероятностный подход](https://github.com/ftad/ML2018/blob/master/materials/lesson5/homework5.pdf) Деллайн: 12:10 13.10.12 (сдавать на листочке на занятии 13 октября)
* [Домашнее задание 6 (опциональное)](https://github.com/ftad/ML2018/blob/master/materials/lesson6/homework6_opt.ipynb) Дедлайн: мягкий 02:00 20.10.18, жесткий 23:59 21.10.18. Все баллы добавляются как бонусные к баллам за домашнюю работу.
* [Домашнее задание 7: решающие деревья](https://github.com/ftad/ML2018/blob/master/materials/lesson7/homework7.ipynb) Дедлайн: мягкий 23:59 04.11.2018, жесткий 09.11.2018 (-1 балл/день). 
* [Домашнее задание 8: классификация цифр и смс-сообщений](https://github.com/ftad/ML2018/blob/master/materials/lesson8/homework8.ipynb) Дедлайн: мягкий 23:59 20.11.2018, жесткий: 23:59 22.11.2018

### Полезные материалы
Книги:
* Hastie T., Tibshirani R, Friedman J. The Elements of Statistical Learning (2nd edition). Springer, 2009.
* Bishop C. M. Pattern Recognition and Machine Learning. Springer, 2006.
* Mohri M., Rostamizadeh A., Talwalkar A. Foundations of Machine Learning. MIT Press, 2012.
* Murphy K. Machine Learning: A Probabilistic Perspective. MIT Press, 2012.
* Mohammed J. Zaki, Wagner Meira Jr. Data Mining and Analysis. Fundamental Concepts and Algorithms. Cambridge University Press, 2014.
* Willi Richert, Luis Pedro Coelho. Building Machine Learning Systems with Python. Packt Publishing, 2013.

Курсы по машинному обучению и анализу данных:
* [Курс по машинному обучению К.В. Воронцова](http://www.machinelearning.ru/wiki/index.php?title=Машинное_обучение_%28курс_лекций%2C_К.В.Воронцов%29)
* [Видеозаписи лекций курса Школы Анализа Данных, К.В. Воронцов](https://yandexdataschool.ru/edu-process/courses/machine-learning)
* [Coursera: Машинное обучение и анализ данных (специализация)](https://www.coursera.org/specializations/machine-learning-data-analysis)
* [Coursera: Введение в машинное обучение, К.В. Воронцов](https://www.coursera.org/learn/introduction-machine-learning)
