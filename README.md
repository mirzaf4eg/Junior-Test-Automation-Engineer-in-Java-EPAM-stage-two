<p align="center">
  <a href="https://www.instagram.com/mirzaf4eg/">
   <img src="https://user-images.githubusercontent.com/66875374/98158093-742a2900-1eeb-11eb-9353-5f31780195d2.png" width="27%"></img> 
   <img src="https://user-images.githubusercontent.com/66875374/98158339-c3705980-1eeb-11eb-9ac8-4d693db33447.png" width="35%"></img> 
  </a>
</p>
<h1 align="center">
  mirzaf4eg (c)
</h1>

<h3 align="center">
   <img src="https://user-images.githubusercontent.com/66875374/99257257-cc382800-2827-11eb-9769-8c2f8b7aa29f.png" width="45%"></img>  
</h3>
<h3 align="center">
  В моем коде прошу никого не винить. Я честно и добросовестно слизал все с просторов интернета. Я очень старался!
</h3>
<p align="center">
  Практические задания второго этапа курса:

<h3 align="center">
  <a href="https://careers.epam.by/training/training-listings/training.2332/">EPAM. Junior Test Automation Engineer in Java</a>
</h3>

# Содержимое репозитория:

- [Java Error&Exceptions](#java-errorexceptions)
- [Java I\O Fundamentals](#java-io-fundamentals)
- [Java Threads](#java-threads)
- [WebDriver](#webdriver)
- [Framework](#framework)

## Java Error&Exceptions
<img src="https://user-images.githubusercontent.com/66875374/98227805-ca897d00-1f68-11eb-8269-31d7be0f9a2e.jpg" width="15%"></img>

В университете есть несколько факультетов, в которых учатся студенты, объединенные в группы. У каждого студента есть несколько учебных предметов по которым он получает оценки. Необходимо реализовать иерархию студентов, групп и факультетов.
Посчитать:
- Cредний балл по всем предметам студента
- Cредний балл по конкретному предмету в конкретной группе и на конкретном факультете
- Cредний балл по предмету для всего университета

Реализовать следующие исключения:
- Оценка ниже 0 или выше 10
- Отсутсвие предметов у студента (должен быть хотя бы один)
- Отсутствие студентов в группе
- Отсутствие групп на факультете
- Отсутствие факультетов в университете

[Вернуться к содержанию](#содержимое-репозитория)

## Java I\O Fundamentals
<img src="https://user-images.githubusercontent.com/66875374/98227805-ca897d00-1f68-11eb-8269-31d7be0f9a2e.jpg" width="15%"></img>

- [Java I\O Fundamentals: Main Task](#java-io-fundamentals-main-task)
- [Java I\O Fundamentals: Optional Task](#java-io-fundamentals-optional-task)

### Java I\O Fundamentals: Main Task

Реализовать программу которая будет получать в качестве аргумента командной строки путь к директории (например _D:/movies_). Записать в текстовый файл структуру папок и файлов в виде, похожем на выполнение программы **tree /F**.

Пример:

```             
Amon Amarth
    |-----2004 - Fate Of Norns
    |       01 - An Ancient Sign Of Coming Storm.mp3
    |       02 - Where Death Seems To Dwell.mp3
    |       03 - The Fate Of Norns.mp3
    |       04 - The Pursuit Of Vikings.mp3
    |       05 - Valkyries Ride.mp3
    |       06 - The Beheading Of A King.mp3
    |       07 - Arson.mp3
    |       08 - Once Sealed In Blood.mp3
    |
    |-----2016 - Jomsviking
    |       01 First Kill.mp3
    |       02 Wanderer.mp3
    |       03 On A Sea Of Blood.mp3
    |       04 One Against All.mp3
    |       05 Raise Your Horns.mp3
    |       06 The Way Of Vikings.mp3
    |       07 At Dawn’s First Light.mp3
    |       08 One Thousand Burning Arrows.mp3
    |       09 Vengeance Is My Name.mp3
    |       10 A Dream That Cannot Be (feat. Doro Pesch).mp3
    |       11 Back On Northern Shores.mp3
    |       12 Death In Fire 2016.mp3
    |       13 Death In Fire (Live).mp3
    |
    |-----2019 - Berserker
            01 Fafner's Gold.mp3
            02 Crack the Sky.mp3
            03 Mjölner, Hammer of Thor.mp3
            04 Shield Wall.mp3
            05 Valkyria.mp3
            06 Raven's Flight.mp3
            07 Ironside.mp3
            08 The Berserker at Stamford Bridge.mp3
            09 When Once Again We Can Set Our Sails.mp3
            10 Skoll and Hati.mp3
            11 Wings of Eagles.mp3
            12 Into the Dark.mp3
```
Если в качестве параметра в программу передается не путь к директории, а путь к _.txt_ файлу по образцу выше - прочитать файл и вывести в консоль следующие данные:
- Количество папок
- Количество файлов
- Среднее количество файлов в папке
- Среднюю длинну названия файла

### Java I\O Fundamentals: Optional Task

Выполнить указанные действия по чтению информации из файла, ее обработке и записи в файл. При разработке для вывода результатов создавать новую директорию и файл средствами класса **File**.

1. Создать и заполнить файл случайными целыми числами. Отсортировать содержимое файла по возрастанию.
2. Прочитать текст Java-программы и все слова public в объявлении атрибутов и методов класса заменить на слово private.
3. Прочитать текст Java-программы и записать в другой файл в обратном порядке символы каждой строки.
4. Прочитать текст Java-программы и в каждом слове длиннее двух символов все строчные символы заменить прописными.
5. В файле, содержащем фамилии студентов и их оценки, записать прописными буквами фамилии тех студентов, которые имеют средний балл более 7.
6. Файл содержит символы, слова, целые числа и числа с плавающей запятой. Определить все данные, тип которых вводится из командной строки.
7. Из файла удалить все слова, содержащие от трех до пяти символов, но при этом из каждой строки должно быть удалено только максимальное четное количество таких слов.
8. Прочитать текст Java-программы и удалить из него все «лишние» пробелы и табуляции, оставив только необходимые для разделения операторов.
9. Из текста Java-программы удалить все виды комментариев.
10. Прочитать строки из файла и поменять местами первое и последнее слова в каждой строке.
11. Ввести из текстового файла, связанного с входным потоком, последовательность строк. Выбрать и сохранить m последних слов в каждой из по-следних n строк.
12. Из текстового файла ввести последовательность строк. Выделить отдельные слова, разделяемые пробелами. Написать метод поиска слова по образцу-шаблону. Вывести найденное слово в другой файл.
13. Сохранить в файл, связанный с выходным потоком, записи о телефонах и их вла-дельцах. Вывести в файл записи, телефоны в которых начинаются на k и на j.

[Вернуться к содержанию](#содержимое-репозитория)

## Java Threads
<img src="https://user-images.githubusercontent.com/66875374/98227805-ca897d00-1f68-11eb-8269-31d7be0f9a2e.jpg" width="15%"></img>
- [Java Threads: Main Task](#java-threads-main-task)
- [Java Threads: Optional Task](#java-threads-optional-task)

### Java Threads: Main Task

Разработать консольное многопоточное приложение. Использовать возможности, предоставляемые пакетом **java.util.concurrent**. Все сущности, желающие получить доступ к ресурсу, должны быть потоками.

- Порт. Корабли заходят в порт для разгрузки/загрузки контейнеров. Число контейнеров, находящихся в текущий момент в порту и на корабле, должно быть неотрицательным и превышающим заданную грузоподъемность судна и вместимость порта. В порту работает несколько причалов. У одного причала может стоять один корабль. Корабль может загружаться у причала, разгружаться или выполнять оба действия.
- Автостоянка. Доступно несколько машиномест. На одном месте может находиться только один автомобиль. Если все места заняты, то автомобиль не станет ждать больше определенного времени и уедет на другую стоянку.
- Тоннель. В горах существует два железнодорожных тоннеля, по которым поезда могут двигаться в обоих направлениях. По обоим концам тоннеля собралось много поездов. Обеспечить безопасное прохождение тоннелей в обоих направлениях. Поезд можно перенаправить из одного тоннеля в другой при превышении заданного времени ожидания на проезд.
- Аукцион. На торги выставляется несколько лотов. Участники аукциона делают заявки. Заявку можно корректировать в сторону увеличения несколько раз за торги одного лота. Аукцион определяет победителя и переходит к следующему лоту. Участник, не заплативший за лот в заданный промежуток времени, отстраняется на несколько лотов от торгов.
- Аэропорт. Посадка/высадка пассажиров может осуществляться через конечное число терминалов и наземным способом через конечное число трапов. Самолеты бывают разной вместимости и дальности полета. Организовать функционирование аэропорта, если пунктов назначения 4–6, и зон дальности 2–3.

### Java Threads: Optional Task

В аэропорту есть 5 взлетно-посадочных полос. Самолету требуется 3 минуты чтобы выйти на полосу, набрать скорость и взлететь. После этого полоса свободна для вылета следующего самолета. Реализовать симуляцию вылета 10 самолетов используя все доступные полосы. 1 минуту реально времени заменить на 1 секунду в симуляции.

Вывести в консоль информацию о следующих событиях:
- Самолет начал выход на полосу
- Самолет взлетел
- Полоса "приняла" самолет
- Полоса освободилась

[Вернуться к содержанию](#содержимое-репозитория)

## WebDriver
<img src="https://user-images.githubusercontent.com/66875374/99146675-6151ea00-268b-11eb-898b-1c1d1db2422e.png" width="25%"></img> 

- [WebDriver create a simple paste at pastebin](#webdriver-create-a-simple-paste-at-pastebin)
- [WebDriver create a complex paste at pastebin and validate data](#webdriver-create-a-complex-paste-at-pastebin-and-validate-data)
- [WebDriver Google Cloud calculator](#webdriver-google-cloud-calculator)
- [WebDriver Google Cloud calculator with 10minute mail validation](#webdriver-google-cloud-calculator-with-10minute-mail-validation)

### WebDriver create a simple paste at pastebin

При выполнении задания необходимо использовать возможности Selenium WebDriver, юнит-тест фреймворка и концепцию Page Object.

1. Открыть https://pastebin.com или аналогичный сервис в любом браузере
2. Создать New Paste со следующими деталями:
    - Код: "Hello from WebDriver"
    - Paste Expiration: "10 Minutes"
    - Paste Name / Title: "helloweb"

### WebDriver create a complex paste at pastebin and validate data

При выполнении задания необходимо использовать возможности Selenium WebDriver, юнит-тест фреймворка и концепцию Page Object.

1. Открыть https://pastebin.com или аналогичный сервис в любом браузере
2. Создать New Paste со следующими деталями:
- Код:
```sh
git config --global user.name  "New Sheriff in Town"
git reset $(git commit-tree HEAD^{tree} -m "Legacy code")
git push origin master --force
```
- Syntax Highlighting: _Bash_
- Paste Expiration: _10 Minutes_
- Paste Name / Title: _how to gain dominance among developers_
3. Сохранить paste и проверить следующее:
- Заголовок страницы браузера соответствует **Paste Name / Title**
- Синтаксис подсвечен для **bash**
- Проверить что код соответствует введенному в пункте 2

### WebDriver Google Cloud calculator

При выполнении задания необходимо использовать возможности Selenium WebDriver, юнит-тест фреймворка и концепцию Page Object.

1. Открыть [https://cloud.google.com/]()
2. Нажав кнопку поиска по порталу вверху страницы, ввести в поле поиска **Google Cloud Platform Pricing Calculator**
3. Запустить поиск, нажав кнопку поиска.
4. В результатах поиска кликнуть **Google Cloud Platform Pricing Calculator** и перейти на страницу калькулятора.
5. Активировать раздел **COMPUTE ENGINE** вверху страницы
6. Заполнить форму следующими данными:
- Number of instances: _4_
- What are these instances for?: _оставить пустым_
- Operating System / Software: _Free: Debian, CentOS, CoreOS, Ubuntu, or other User Provided OS_
- VM Class: _Regular_
- Instance type: _n1-standard-8 (vCPUs: 8, RAM: 30 GB)_
- Выбрать _Add GPUs_
    - Number of GPUs: _1_
    - GPU type: _NVIDIA Tesla V100_
- Local SSD: _2x375 Gb_
- Datacenter location: _Frankfurt (europe-west3)_
- Commited usage: _1 Year_
7. Нажать **Add to Estimate**
8. Проверить соответствие данных следующих полей: _VM Class, Instance type, Region, local SSD, commitment term_
9. Проверить что сумма аренды в месяц совпадает с суммой получаемой при ручном прохождении теста.

### WebDriver Google Cloud calculator with 10minute mail validation

При выполнении задания необходимо использовать возможности Selenium WebDriver, юнит-тест фреймворка и концепцию Page Object.

1. Открыть [https://cloud.google.com/]()
2. Нажав кнопку поиска по порталу вверху страницы, ввести в поле поиска **Google Cloud Platform Pricing Calculator**
3. Запустить поиск, нажав кнопку поиска.
4. В результатах поиска кликнуть **Google Cloud Platform Pricing Calculator** и перейти на страницу калькулятора.
5. Активировать раздел **COMPUTE ENGINE** вверху страницы
6. Заполнить форму следующими данными:
- Number of instances: _4_
- What are these instances for?: _оставить пустым_
- Operating System / Software: _Free: Debian, CentOS, CoreOS, Ubuntu, or other User Provided OS_
- VM Class: _Regular_
- Instance type: _n1-standard-8 (vCPUs: 8, RAM: 30 GB)_
- Выбрать Add GPUs
    - Number of GPUs: _1_
    - GPU type: _NVIDIA Tesla V100_
- Local SSD: _2x375 Gb_
- Datacenter location: _Frankfurt (europe-west3)_
- Commited usage: _1 Year_
7. Нажать **Add to Estimate**
8. Выбрать пункт **EMAIL ESTIMATE**
9. В новой вкладке открыть _https://10minutemail.com_ или аналогичный сервис для генерации временных _email_'ов
10. Скопировать почтовый адрес сгенерированный в **10minutemail**
11. Вернуться в калькулятор, в поле _Email_ ввести адрес из предыдущего пункта
12. Нажать **SEND EMAIL**

[Вернуться к содержанию](#содержимое-репозитория)

## Framework
<img src="https://user-images.githubusercontent.com/66875374/99147053-9875ca80-268e-11eb-8fa8-1f97957f758b.jpg" width="25%"></img> 

Задача - построить фреймворк для автоматизации Hardcore задания из курса WebDriver (WebDriver Google Cloud calculator в это документе)

Что должно быть в итоговом фреймворке:

- _webdrivermanager_ для управления коннекторам к браузерам
- _Page Object / Page Factory_ для абстракций страниц
- Модель для бизнес-объектов необходимых сущностей
- _properties_ файлы с тестовыми данным для разных окружений (как минимум 2)
- _xml suites_ для _smoke_ тестов и всех тестов
- При падении теста должен быть сделан скриншот с датой и временем
- Фреймворк должен иметь возможность запуска с _Jenkins_ и параметризацией браузера, тест _suite_, _environment_. Результаты тестов должны быть на графике джобы, скриншоты должны быть заархивированны как артефакты

Пример проекта: [https://github.com/vitalliuss/github-automation]()

[Вернуться к содержанию](#содержимое-репозитория)

## :memo: License

Licensed under the [MIT License](https://github.com/mirzaf4eg/Junior-Test-Automation-Engineer-in-Java-EPAM-stage-two/blob/master/LICENSE.txt).

## 💜 Thanks

<p align="center">
   <img src="https://user-images.githubusercontent.com/66875374/98436488-b7071f00-20ec-11eb-8fc0-43ab2b93aee8.gif" width="30%"></img>
</p>

[Вернуться к содержанию](#содержимое-репозитория)
