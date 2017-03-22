![Иллюстрация к проекту](https://github.com/dingosmart/Physics-Simulations-and-Animations-Alex-Ponomariov-/blob/master/example%20_%204.jpg)

# Physics-Simulations-and-Animations
Physics Simulations and Animations ( The example of Physics modeling and simulations on c#) 

Данные проекты появились в рамках выполенния тестовых заданий для корпорации http://www.transas.com/ , конкретно для отдела моделирования. Уж больно им требовался специалист с инженерным образованием , со знанием C# , с опытом работы и не требовательный к уровню ЗП.  

Тестовые задания широким фронтом охватывали задачи гидравлики, автоматики, програмирования, проектирования систем.
Высказывалось желание что бы проекты были  выполненны за срок не превышающий 2 недели.  На языке высокго уровня  типа c# или С++

Сформированное решение должно было содержать в себе:

1. Описание решаемой задачи,
2. Исходные коды,
3. Математическую модель в формате Exel

Дополнительно заказчик хотел что бы решение ( программа) работала в реальном режиме времени RealTime. Можно было менять параметры работы  физической  системы в любой момент врмени. в частности:
включать и выключать клапаны, включать и выключать потребителей, отображать на экране уровни жидкостей или других рабочих сред. 
Обновление парметров должно было происходить с интервалом в 1 с.

На решение задач отводилось не более двух недель времени. Это только кажется , что задачи простые, но реально самое большое время занимает написание физической модели.

В качестве вводной было полученна информация , что предыдущие 8 гидромехаников не смогли решить данные условно "простые" задачи, а кто решил не смог запрограмировать. Еще требовалось показать "лаконичный" код, меня пугали, что решение будут оценивать опытные програмисты.

Я решил бросить вызов моим неудачлиым колегам.  И получив задния с минимальными вводными приступил к мат моделированию, а потом к програмированию.

В общей сложности  было создано 4 проекта , при этом пришлось решить не 4 задачи, а гораздо больше:

- необходимо было решить задачи просто на бумаге в соотвествии с предметной областью ( обновить знания по гидростатике, гидравлике, пневматике, автоматике)
- построить физическую модель в Exel
- построить объектную модель
- оттестировать объекты
- собрать интерфейсы программ
- придумать как использовать только стандартные библиотеки и инструменты
- собрать решение полностью и протестировать его на адекватность физической модели

 Для реализации проекта использовался продукт: Visual Studio Community 2017 (бетта)
 Для уменьшения времени програмированнния интерфейса использовались windows form.
 Для отображения графиков использовался стандарный класс Graph, важным достижением было научить его отображать графики в   RealTime режиме имулируя работу приборов или осцилоскопа.
 
 При этом пришлось задачу решать в два этапа:
 1. Статическое решение задачи - решение для статического тестирования объектов, когда по фискированным параметрам производится физический перасчет.
 2. Динамический расчет , когда все параметры меняются и система сама приходит к динамическому равновесию и отображает все  возможные параметры рассчетов, такие как Давления на входе, давления всасывания или нагнетания, температуру масла холодильника , температуру поступающей забортной воды,  срабатывание аварийного клапана воздушного компрессора и т.д.
 
 После дня работы над проектом  стало понятно почему ребята которые приходили устраиватся на работу терпели фиаско, работа програмисткая явно не для уровня Junior , надо строить мат модель , а это умеют не все. По факту надо было решать не те задачи которым меня учили, а родственные. вместо гидромеханики требовалась гидравлика и автоматика и т.д.  
 
 Но все было решено правильно модели написаны и запрограмированны, написан код... 
 
 Работу от компании я не получил, но вот  много чего повторил или узнал :) полезного для себя. 
 
 Цель проекта поделится наработанным опытом по моделированию физических процессов который будет полезен молодым ученым и програмистам  работающим в области автоматики, гидравлики, гидростатики и всем тем кому требуется отображать параметры в режиме Realtime




#A bit about me (CV):
mailto:  AA_Ponomariov@mail.ru 
phonenumber:  +7(911) 086-56-51
Пономарёв Алексей Александрович (СПб. Россия)
Профиль специалиста:
Высшее экономическое и техническое образование.
Опыт работы более 10 лет в области внутреннего аудита, внутреннего контроля.
Образование:

1992-1996 Государственный Морской Технический Университет (Далее СПбГМТУ). Инженер-экономист. Специализация «Экономика и управление на предприятиях машиностроения»;1992-1997 СПбГМТУ. Специальность инженер- исследователь (гидроаэродинамика);
1997-2000 Очная аспирантура. СПбГМТУ (динамика жидкости , газа и плазмы);
1999  Институт внешнеэкономических связей, экономики и права. Бухгалтер-эксперт. (Повышение уровня знаний).

Аттестаты:
Сертификат Microsoft Virtual Academy Ускоренный курc: «Программирование в С# (17 марта 2014)»  »
Аттестаты ЦБ России (серия 1.0, 3.0, 5.0 — ценные бумаги)
Аттестат профессионального бухгалтера, бухгалтера-эксперта (консультанта)
Опыт работы [1993-2017]:
[1993-2008] Судостроительный холдинг
Зам. главного бухгалтера, главный бухгалтер, заместитель директора в ДЗО

[2008 — 2016]  Северо-Западный филиал НАУФОР
Инспектор-контролер (аудитор-консультант).
НАУФОР (Национальной Ассоциации участников фондового рынка). Инспекционные проверки организаций членов НАУФОР Проведение выездных и камеральных проверок. Осуществление проверок в других регионах. Проведение совместных проверок с государственными контролирующими органами. Работа с большими массивами разряженных и мультиструктурных данных. Разработка методологических рекомендаций по улучшению внутренних процедур и документов  организаций. Удаленное консультирование.
[2014-2017] Программирование С# в различных Freelance проектах., моделирование  физических и экономических процессов, составление технических заданий.
Дополнительно
Программирование  С#, JavaScript, HTML 5 + CSS, Jquery, JSON б, Frontend, Bootstrap.
Администрирование windows, Ubuntu, 1C 7.7
Анализ и моделирование систем.
Английский язык.


These projects came within vypolenniya test items for the corporation http://www.transas.com/, particularly for modeling department. Painfully, they needed a person with an engineering degree, with C # zanniem, with experience and is not demanding to the level of the RFP.

Tests covered a broad front hydraulics problem, automation, programming, systems design. It has been a desire to have projects were carried out over a period not exceeding 2 weeks. In the language-in high-level type c # or C ++

The formed solution was to contain:

Description of the problem,
Source code,
Mathematical models in Exel format
Additionally, the customer wanted a solution that would be (program) working in real mode RealTime time. It was possible to change the parameters of the physical system at any time vrmeni. in particular: to enable or disable the valves, enable and disable users to display on-screen fluid levels and other working environments. Update parameter memory should occur at intervals of 1 s.

In problem solving was given less than two weeks time. It just seems that the problems are simple, but really the biggest time of writing takes a physical model.

As an introduction to the information received was that the previous 8 fluid mechanics failed to solve the data conditionally "simple" tasks, and who decided could not be programmed. More needed to show a "concise" code, I was scared that the decision will be evaluated by experienced programmers.

I decided to challenge my unfortunate Colleges. And get the back with minimal introductory started modeling mat, and then to the programming.

A total of 4 projects were created, while it was necessary to solve the problem is not 4, and much more:

it was necessary to solve the problem just on paper In accordance with the subject area (update knowledge on hydrostatics, hydraulics, pneumatics, automation)
build a physical model in Exel
build an object model
test the objects
assemble programming interfaces
to come up as soon as the use of standard libraries and tools
collect the solution thoroughly and test it on the adequacy of the physical model
To implement the project to use the product: Visual Studio Community 2017 (beta) To reduce the time used programirovannniya interface windows form. To display charts used standarny class Graph, an important achievement was to teach him to display graphics in RealTime mode imuliruya work equipment or ostsiloskopa.

This problem had to be solved in two stages:

Static solution of the problem - a solution for static testing facilities when fiskirovannym physical parameters produced peraschet.
Dynamic analysis when all the parameters are changed and the system will come to a dynamic equilibrium and displays all possible parameters of calculations, such as inlet pressure, suction or discharge pressure, the temperature of the refrigerator oil, the temperature of the incoming seawater, triggering emergency valve air compressor, etc. .
After a day of work on the project, it became clear why the guys who came to work suffered a fiasco, work  implicitly to Junior level, it is necessary to build a model , which are able to not all. In fact it was necessary to address not the tasks that I had been taught, and related. instead of hydraulics and fluid mechanics required equipment, etc.

But it was decided correctly models written and programmed to, written code ...

The work of the company, I did not get, but that's a lot of things :) repeated or learned useful things.

Purpose of the project will share the accumulated experience on the modeling of the physical processes that will benefit young scientists and programmers working in the field of automation, hydraulics, hydrostatics and all those who want to display parameters in the Realtime Mode

#A Bit about me (CV): 
mailto: AA_Ponomariov@mail.ru phonenumber: +7 (911) 086-56-51 
Alexey Ponomarev (Russia SPb.) 
Profile of the expert: Higher economic or technical education. Experience over 10 years in the field of internal audit, internal control. Education:

1992-1996 State Marine Technical University (SMTU Next). Engineer-economist. Specialization «Economics and management at machine-building enterprises"; 1992-1997 SPbSMTU. Occupation research engineer (fluid dynamics); 1997-2000 Full-time post-graduate course. SPbSMTU (fluid dynamics, gas and plasma); 1999 Institute of Foreign Economic Relations, Economics and Law. Accountant expert. (Raising awareness).

Certificates: Certificate of Microsoft Virtual Academy Accelerated kurc: "Programming in C # (March 17, 2014)» »Russian Central Bank Certificates (Series 1.0, 3.0, 5.0 - securities) Certificate of professional accountant, expert accountant (consultant) Experience [1993- 2017] [1993-2008] Shipbuilding holding Deputy. Chief Accountant, Chief Accountant, Deputy Director of SDC

[2008 - 2016] of the North-West Branch NAUFOR inspector-controller (auditor-consultant). NAUFOR 
NAUFOR (National Association of Securities Market Participants). Inspections member organizations NAUFOR fielding and off-site inspections. Implementation of checks in other regions. Carrying out joint inspections with state regulatory authorities. Working with large arrays and discharged multistructural data. Development of methodological recommendations to improve internal procedures and documents. Remote Consulting.
[2014-2017] Programming C # Freelance in various projects., Modeling of physical and economic processes, drawing up technical specifications.
Additionally
Programming C #, JavaScript, HTML 5 + CSS, Jquery, JSON used, Frontend, Bootstrap.
Administration windows, Ubuntu, 1C 7.7
Analysis and modeling systems.
English.
