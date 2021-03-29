# Техническое задание

**Название**: Covid DI

**Прототип:** https://marvelapp.com/prototype/58hdf35/screen/78028767

**Назначение**: приложение дает пользователю актуальную информацию о корона вирусной инфекции, информирует о числе заболевших, умерших и выздоровевших по каждой стране, дает возможность (с помощью тестов) оценить свой уровень знаний о Covid -19.   

**Целевая аудитория:**
-	Пользователи от 12 лет

**Функциональность приложения:**
1.	Выбор страны, по которой планируется получить информацию
3.	Предоставление статистических данных
4.	Прохождение тестов о Covid - 19
5.	Предоставление актуальной информации о коронавирусной инфекции (симптомы, мифы о корона вирусе, памятки о профилактике).
6.	Настройки:

    ●	Языка (автоматически, в соответствии с локалью, установленной на устройстве)
  
    ●	Информация о приложении
  
    ●	Обратная связь

**Описание экранов:**

   1. *Главный экран*

Этот экран содержит статистические данные о текущем числе заболевших, выздоровевших и умерших от корона вирусной инфекции. Есть диаграмма по этим данным и кнопки для перехода к тестам и к актуальной информации о Covid - 19, кнопка выбора конкретной страны. 

![1](https://user-images.githubusercontent.com/71034773/112837702-e0791500-90a4-11eb-9f5b-12542e71c73f.jpg)
![2](https://user-images.githubusercontent.com/71034773/112837730-e7a02300-90a4-11eb-87ea-9275d1abf96f.jpg)

   2. *Экран настроек*

На этом экране находятся глобальные настройки приложения

![3](https://user-images.githubusercontent.com/71034773/112838208-7e6cdf80-90a5-11eb-8f4d-f05f1b95becd.jpg)

   3. *Экран с актуальной информацией о Covid – 19.*

На этом экране пользователь может ознакомиться с актуальной информационной сводкой.

![4](https://user-images.githubusercontent.com/71034773/112838283-8fb5ec00-90a5-11eb-90ee-23e0158336a7.jpg)

   4. *Экран прохождения теста*

На этом экране пользователь может проверить свои знания о корона вирусной инфекции, пройдя несложный тест

![5](https://user-images.githubusercontent.com/71034773/112838365-a78d7000-90a5-11eb-843d-26287da1441e.jpg)

**Архитектура:**

   Для отслеживания статистики о Covid - 19, вероятно, будет использоваться [COVID-19](https://github.com/M-Media-Group/Covid-19-API) (фича исследуется)
    
   Работа с сетью: выгрузка статистики из API.
    
   Использование хранилища: кэширование статистических данных, чтобы можно было пользоваться приложением без сети.

   Активности:
    
    ● MainActivity

    ● SettingsActivity

    ● TestActivity

    ● InfoActivity

**Команда:** DEADline

**Разработчики:**

    ● Низовцев Роман

    ● Светашева Юлия

    ● Драгун Илья

**Репозиторий:** https://github.com/romanizovtsev/DEADline


