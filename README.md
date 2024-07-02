# <center> ML. Decision Trees and Random Forest

## Оглавление  
[1. Описание проекта](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Описание-проекта)  
[2. Задачи](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Задачи)  
[3. Краткая информация о данных](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Результаты)    
[6. Выводы](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Выводы) 

### Описание проекта    
Прогнозирование оттока клиентов банка. 

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Оглавление)


### Задачи    
1. Подготовка данных для моделирования и построение простейшей модели логистической регрессии, оценка качества модели и анализ результов её работы;
2. Построение моделей дерева решений и случайного леса, сравнение результатов пстроенных моделей.
  

**Метрика качества**     
* Верное решение поставленных задач.


**Что практикуем**     
* Построение моделей машинного обучения для решения задачи бинарной классификации.

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Оглавление)


### Краткая информация о данных
Для анализа была предоставлена таблица, содержащая следующую информацию:
* RowNumber (тип данных int64);
* CustomerId (тип данных int64);
* Surname (тип данных object);
* CreditScore (тип данных int64); 
* Geography (тип данных object);
* Gender (тип данных object);
* Age (тип данных int64);
* Tenure (тип данных int64);
* Balance (тип данных float64);
* NumOfProducts (тип данных int64);
* HasCrCard (тип данных int64);
* IsActiveMember (тип данных int64); 
* EstimatedSalary (тип данных float64);
* Exited (тип данных int64).

  
:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Оглавление)


### Этапы работы над проектом  
**Разведывательный анализ данных:**
* Построение графиков распределения целевого признака - Exited;
* Подготовка данных к моделированию:
1. Создание новых признаков;
2. Разделение данных на тренировочную и тестовую выборки;
3. Нормализация данных. 


**Решение задачи классификации:**
* Построение модели логистической регрессии;
* Построение модели логистической регрессии на полиномных признаках;
* Подобор значения порога вероятности, при котором наблюдается наибольшее значение целевой метрики (F1 -score) на тестовой выборке;
* Построение модели дерева решенией;
* Построение модели случайного леса.

 

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Оглавление)


### Результаты:  
В результате проделанной работы был получен практический опыт рашения задачи бинарной классификации с помощью построения моделей машиного обучения.    

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Оглавление)


### Выводы:  
Решение настоящей задачи дает более детальное представление об алгоритмах машинного обучения, предназначенных для решения задачи классификации, а также о метриках качества таких моделей. Стоит также отметить, что для достижения оптимального результата нельзя ограничиваться построением одной модели, способной решить поставленную задачу, а необходимо использовать разные инструменты и в итоге выбрать ту моедль котарая демонстрирует наилучший результат.      


:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/ML.-Decision-Trees-and-Random-Forest/blob/main/README.md#Оглавление)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами
