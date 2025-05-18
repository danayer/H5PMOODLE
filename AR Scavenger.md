# H5P AR Scavenger в Moodle: Подробное руководство

## Содержание
- [Введение в H5P](#введение-в-h5p)
- [Что такое AR Scavenger](#что-такое-ar-scavenger)
- [Установка H5P в Moodle](#установка-h5p-в-moodle)
- [Создание активности AR Scavenger](#создание-активности-ar-scavenger)
- [Подробные настройки AR Scavenger](#подробные-настройки-ar-scavenger)
- [Примеры использования для авиационного английского](#примеры-использования-для-авиационного-английского)
- [Советы и лучшие практики](#советы-и-лучшие-практики)

## Введение в H5P

H5P (HTML5 Package) — это открытая и бесплатная технология для создания интерактивного контента. Она позволяет преподавателям создавать разнообразные интерактивные элементы обучения, которые можно встраивать в систему управления обучением (LMS), такую как Moodle.

Основные преимущества H5P:
- Интерактивность и вовлечение
- Множество типов контента (более 40 различных видов активностей)
- Адаптивность для мобильных устройств
- Возможность повторного использования
- Поддержка мультимедиа

## Что такое AR Scavenger

AR Scavenger (Поиск с дополненной реальностью) — это тип активности в H5P, который использует технологию дополненной реальности для создания интерактивных образовательных квестов и заданий по поиску объектов в физическом пространстве. Учащиеся используют мобильные устройства для сканирования AR-маркеров или объектов в реальном мире, получая доступ к образовательному контенту, заданиям и информации. AR Scavenger особенно полезен для:

- Создания иммерсивных обучающих сценариев в реальной среде
- Соединения теоретических знаний с практическими объектами
- Обучения профессиональной терминологии в контексте
- Ознакомления с оборудованием и системами в их физическом расположении
- Развития навыков узнавания и идентификации объектов и элементов

AR Scavenger предоставляет мощный инструмент для контекстуализированного обучения, помогая студентам соотносить профессиональные термины и концепции с объектами реального мира, что критически важно в технических сферах, таких как авиация.

## Установка H5P в Moodle

Прежде чем создавать активности AR Scavenger, необходимо установить H5P в вашей системе Moodle:

1. Войдите в Moodle как администратор
2. Перейдите в раздел "Администрирование сайта" > "Плагины" > "Установка плагинов"
3. Нажмите кнопку "Установить плагины из каталога плагинов Moodle"
4. Найдите "H5P" в списке плагинов и установите его
5. Следуйте инструкциям по установке
6. После завершения установки активируйте плагин

## Создание активности AR Scavenger

### Шаг 1: Добавление активности H5P в курс

1. Перейдите на страницу вашего курса в Moodle
2. Включите режим редактирования, нажав кнопку "Режим редактирования" в правом верхнем углу
3. В нужном разделе курса нажмите "Добавить элемент или ресурс"
4. В открывшемся окне выберите "H5P интерактивный контент" и нажмите "Добавить"

### Шаг 2: Настройка основных параметров

1. Введите название для вашей активности в поле "Название"
2. При необходимости добавьте описание в поле "Описание"
3. В разделе "Настройки H5P" нажмите кнопку "Создать" или "Загрузить контент"
4. Из списка доступных типов контента выберите "AR Scavenger"

### Шаг 3: Создание AR квеста

1. В поле "Заголовок" введите название для вашего AR квеста
2. Добавьте вводный текст в поле "Инструкции" с объяснением целей активности и как использовать AR функционал
3. Нажмите "Добавить AR объект" для создания первой точки квеста
4. Для каждого AR объекта настройте:
   - **Идентификатор объекта**: уникальный ID для отслеживания прогресса
   - **Название объекта**: краткое описание того, что учащиеся должны найти
   - **AR маркер**: загрузите изображение-маркер или выберите тип объекта для распознавания
   - **Информация об объекте**: добавьте образовательный контент, связанный с объектом

5. Настройте задания и вопросы, связанные с AR объектом:
   - **Типы вопросов**: выбор из нескольких вариантов, заполнение пропусков, верно/неверно
   - **Инструкции**: что именно студенты должны сделать после нахождения объекта
   - **Обратная связь**: реакция системы на правильные и неправильные ответы

6. Добавьте все необходимые AR объекты для полного маршрута квеста
7. Настройте порядок объектов и зависимости между ними (последовательный или свободный порядок)

### Шаг 4: Настройка дополнительных параметров

1. Настройте параметры завершения квеста
2. Определите, какие объекты обязательны для завершения, а какие дополнительны
3. Настройте систему подсчета баллов и оценивания
4. Добавьте подсказки для сложных для нахождения объектов

## Подробные настройки AR Scavenger

### Настройки AR распознавания

- **Типы маркеров**: выбор между QR-кодами, распознаванием изображений или объектов
- **Чувствительность распознавания**: настройка точности определения маркеров
- **Стабилизация маркера**: настройки для предотвращения колебаний при распознавании
- **Дополнительные указания**: подсказки и изображения для помощи в поиске объектов

### Настройки образовательного контента

- **Типы медиа**: выбор формата контента (текст, изображения, видео, 3D модели)
- **Интерактивные элементы**: добавление интерактивных вопросов и заданий
- **Аудио сопровождение**: добавление звуковых подсказок и объяснений
- **Дополнительная информация**: включение расширенного контента для углубленного изучения

### Настройки навигации и последовательности

- **Карта объектов**: включение визуальной карты AR объектов
- **Порядок доступа**: настройка линейного или нелинейного прохождения
- **Условия прогресса**: установка требований для перехода к следующим объектам
- **Временные ограничения**: настройка лимита времени для выполнения квеста

### Настройки оценивания и отзывов

- **Система баллов**: настройка весов для разных объектов и заданий
- **Обратная связь**: настройка немедленной обратной связи при взаимодействии
- **Итоговая оценка**: настройка параметров для финального оценивания
- **Сертификат завершения**: настройка сертификата для успешного прохождения

### Шаг 5: Сохранение и публикация

1. После завершения всех настроек нажмите "Сохранить и показать"
2. Проверьте, как работает ваш AR квест с точки зрения студента
3. При необходимости вернитесь к редактированию и внесите изменения

## Примеры использования для авиационного английского

### Пример 1: AR поиск элементов кабины самолета

```
Заголовок: Cockpit Familiarization AR Quest
Инструкции: "Use your mobile device to scan the AR markers placed in the cockpit training area. Identify each control and instrument, learn its function and related terminology, and complete associated tasks."

AR объект 1:
Название: "Primary Flight Controls"
Маркер: [Изображение штурвала/сайдстика]
Информация: "Primary flight controls are used by the pilot to control the aircraft's attitude, altitude, and flight path. They include the control column (yoke) or sidestick, which controls pitch (up and down) and roll (side to side movements), and the rudder pedals, which control yaw (left and right movement of the nose)."
Интерактивное задание: Multiple Choice
Вопрос: "What axis is controlled by the rudder pedals?"
Варианты: "Pitch", "Roll", "Yaw", "Longitudinal"
Правильный ответ: "Yaw"
Обратная связь: "Correct! The rudder pedals control movement around the yaw axis (vertical axis), causing the aircraft nose to move left or right."

AR объект 2:
Название: "Engine Instruments"
Маркер: [Изображение приборной панели двигателя]
Информация: "Engine instruments provide information about engine performance and status. Key parameters include N1 (fan speed), EGT (Exhaust Gas Temperature), fuel flow, and oil pressure and temperature. Modern aircraft display these on the Engine Indication and Crew Alerting System (EICAS) or Engine Monitoring Display (EMD)."
Интерактивное задание: Fill in the Blanks
Предложение: "The ________ (EGT) is a critical parameter that must be monitored to prevent engine damage due to overheating."
Правильный ответ: "Exhaust Gas Temperature"
Обратная связь: "Correct! Exhaust Gas Temperature is a critical parameter that pilots monitor to ensure the engine is operating within temperature limits."

AR объект 3:
Название: "Navigation Display"
Маркер: [Изображение навигационного дисплея]
Информация: "The Navigation Display (ND) shows the aircraft's position relative to the planned route, waypoints, airports, and navigation aids. It can also display weather radar information and terrain data."
Интерактивное задание: Drag and Drop
Задание: "Match each symbol on the Navigation Display with its meaning."
Элементы: [Различные символы с ND - треугольники для VOR, линии для маршрутов, значки аэропортов и т.д.]
Ответы: [Соответствия между символами и их описаниями]
Обратная связь: "Great job! Understanding these symbols is essential for effective flight navigation."

[Дополнительные AR объекты для других элементов кабины: автопилот, радио, системные панели и т.д.]
```

### Пример 2: AR предполетный осмотр самолета

```
Заголовок: Pre-flight Inspection AR Training
Инструкции: "Complete a virtual pre-flight walk-around inspection of the aircraft using AR. Scan the markers at different inspection points, learn the correct terminology and procedures, and answer questions about each area."

AR объект 1:
Название: "Pitot-Static System"
Маркер: [Изображение трубки Пито]
Информация: "The pitot-static system provides airspeed, altitude, and vertical speed information. The pitot tube measures ram air pressure, while static ports measure static air pressure. These measurements are used by the airspeed indicator, altimeter, and vertical speed indicator. Always check that pitot tube covers are removed before flight and that the tubes and ports are free from obstructions."
Интерактивное задание: True/False
Утверждение: "The pitot tube should be covered during pre-flight inspection to prevent contamination."
Правильный ответ: False
Обратная связь: "Incorrect. The pitot tube cover must be REMOVED during pre-flight inspection, and the tube should be checked to ensure it's free from obstructions."

AR объект 2:
Название: "Landing Gear"
Маркер: [Изображение стойки шасси]
Информация: "The landing gear should be inspected for proper extension, retraction mechanism integrity, tire condition, and brake system status. Check tires for proper inflation, wear, and damage. Brake pads should be inspected for wear and hydraulic lines for leaks."
Интерактивное задание: Multiple Choice
Вопрос: "Which of the following is NOT a standard item to check when inspecting landing gear?"
Варианты: "Tire pressure", "Brake pad wear", "Hydraulic fluid leaks", "Engine oil level"
Правильный ответ: "Engine oil level"
Обратная связь: "Correct! Engine oil level is checked separately as part of the engine inspection, not the landing gear inspection."

AR объект 3:
Название: "Control Surfaces"
Маркер: [Изображение элеронов/рулей высоты]
Информация: "Control surfaces include ailerons, elevators, rudder, flaps, slats, spoilers, and trim tabs. During pre-flight, check for freedom of movement (within limits), security of attachments, and absence of damage or deformation. Also verify the proper operation of trim systems."
Интерактивное задание: Fill in the Blanks
Предложение: "The ________ control roll movement of the aircraft, while the ________ control pitch movement."
Правильные ответы: "ailerons", "elevators"
Обратная связь: "Correct! Ailerons control roll (banking), and elevators control pitch (nose up/down)."

[Дополнительные AR объекты для других точек предполетного осмотра: двигатели, топливные баки, фюзеляж, хвостовое оперение и т.д.]
```

### Пример 3: AR тренировка по аэропортовой навигации

```
Заголовок: Airport Navigation and Signage AR Training
Инструкции: "Explore the airport environment using AR markers placed around the terminal or on a airport diagram. Learn to identify and understand various airport signs, markings, and navigational aids."

AR объект 1:
Название: "Runway Identification Signs"
Маркер: [Изображение знака идентификации ВПП]
Информация: "Runway identification signs have white text on a red background. They display the runway designator, which indicates the magnetic heading of the runway to the nearest 10 degrees. For example, Runway 27 is oriented approximately 270 degrees magnetic."
Интерактивное задание: Multiple Choice
Вопрос: "What does the runway designator '18L' indicate?"
Варианты: "Runway oriented at 180 degrees magnetic, left of parallel runway", "Runway 18 kilometers long", "Runway with 18 degrees inclination, left turn required", "Runway with 18 meter width, landing only"
Правильный ответ: "Runway oriented at 180 degrees magnetic, left of parallel runway"
Обратная связь: "Correct! '18L' indicates a runway oriented at approximately 180 degrees magnetic, and it is the left one of two parallel runways."

AR объект 2:
Название: "Taxiway Guidance Signs"
Маркер: [Изображение указателя рулежной дорожки]
Информация: "Taxiway guidance signs have black text on a yellow background. They provide direction to specific taxiways, runways, or airport areas. Directional signs include arrows indicating the direction of turn required to access the designated taxiway."
Интерактивное задание: Matching
Задание: "Match each taxiway sign with its meaning."
Элементы: [Изображения различных указателей рулежных дорожек]
Ответы: [Соответствующие описания значений знаков]
Обратная связь: "Great job! Understanding taxiway signage is essential for safe ground operations."

AR объект 3:
Название: "Holding Position Markings"
Маркер: [Изображение маркировки места ожидания]
Информация: "Holding position markings consist of four yellow lines (two solid and two dashed) and run perpendicular to the taxiway centerline. Aircraft must stop at these markings and may not proceed beyond them without explicit ATC clearance."
Интерактивное задание: True/False
Утверждение: "An aircraft may cross holding position markings when ready, without ATC clearance."
Правильный ответ: False
Обратная связь: "Correct! Aircraft must receive explicit clearance from ATC before crossing holding position markings."

[Дополнительные AR объекты для других аэропортовых знаков, маркировок и навигационных средств: ILS, VOR, PAPI, стоп-огни и т.д.]
```

### Пример 4: AR терминология авиационного технического обслуживания

```
Заголовок: Aircraft Maintenance Terminology AR Challenge
Инструкции: "Explore the aircraft maintenance hangar using AR markers to learn technical terminology associated with different aircraft systems and maintenance procedures."

AR объект 1:
Название: "Hydraulic System Components"
Маркер: [Изображение гидравлического насоса]
Информация: "The hydraulic system provides power for various aircraft functions including flight controls, landing gear, and brakes. Key components include hydraulic pumps, reservoirs, accumulators, actuators, and servo valves. The system operates using hydraulic fluid under high pressure, typically 3,000-5,000 PSI in commercial aircraft."
Интерактивное задание: Labeling
Задание: "Identify the components of the hydraulic system on this diagram."
Элементы: [Схема гидравлической системы с пронумерованными элементами]
Ответы: [Названия компонентов, которые нужно сопоставить с номерами]
Обратная связь: "Excellent! Understanding hydraulic system components is crucial for effective maintenance."

AR объект 2:
Название: "Engine Inspection Points"
Маркер: [Изображение авиационного двигателя]
Информация: "Regular engine inspections include checking for fluid leaks, damage to compressor and turbine blades, proper operation of controls, and integrity of mountings and casings. Borescope inspections allow technicians to examine internal engine components without disassembly."
Интерактивное задание: Multiple Choice
Вопрос: "What tool is commonly used to inspect internal engine components without disassembly?"
Варианты: "Torque wrench", "Ultrasonic thickness gauge", "Borescope", "Multimeter"
Правильный ответ: "Borescope"
Обратная связь: "Correct! A borescope is an optical device that allows inspection of internal engine components through small access ports, without requiring engine disassembly."

AR объект 3:
Название: "Avionics Troubleshooting"
Маркер: [Изображение авионики/приборной панели]
Информация: "Avionics troubleshooting involves diagnosing and resolving issues with aircraft electronics, including communication, navigation, monitoring, and flight management systems. Common procedures include system power cycling, running built-in tests, checking connections, and component replacement."
Интерактивное задание: Fill in the Blanks
Предложение: "When troubleshooting avionics issues, the first step is often to check ________ integrity, followed by running ________ tests to isolate the fault."
Правильные ответы: "electrical", "diagnostic"
Обратная связь: "Correct! Checking electrical integrity (connections, power supply) and running diagnostic or built-in tests are critical first steps in avionics troubleshooting."

[Дополнительные AR объекты для других систем самолета: электрическая система, топливная система, противообледенительная система и т.д.]
```

### Пример 5: AR тренировка по аварийным процедурам

```
Заголовок: Emergency Procedures AR Training
Инструкции: "Use AR technology to practice emergency procedures in a simulated environment. Scan markers to access information about different emergency scenarios, required actions, and standard communication protocols."

AR объект 1:
Название: "Engine Fire Procedures"
Маркер: [Изображение предупреждающего индикатора пожара двигателя]
Информация: "Engine fire procedures vary by aircraft type but generally include: identifying the affected engine, shutting it down using the Engine Fire Handle, discharging fire extinguishers, and communicating with ATC. Communication should include declaring an emergency, nature of the emergency, intentions, and any assistance required."
Интерактивное задание: Sequencing
Задание: "Arrange the following steps in the correct order for engine fire response."
Элементы: ["Communicate with cabin crew", "Discharge fire extinguishers", "Identify affected engine", "Declare emergency to ATC", "Pull and rotate Engine Fire Handle"]
Правильный порядок: ["Identify affected engine", "Pull and rotate Engine Fire Handle", "Discharge fire extinguishers", "Declare emergency to ATC", "Communicate with cabin crew"]
Обратная связь: "Correct sequence! Prompt identification and shutdown of the affected engine is critical before extinguisher discharge and communications."

AR объект 2:
Название: "Cabin Depressurization"
Маркер: [Изображение кислородных масок]
Информация: "Cabin depressurization requires immediate action. The priority sequence is: oxygen (crew masks on), emergency descent (typically to 10,000 feet or minimum safe altitude), communication (with ATC and cabin crew), and navigation (diversion planning). Standard phraseology includes declaring an emergency and requesting priority handling."
Интерактивное задание: Multiple Choice
Вопрос: "What is the primary reason for initiating an emergency descent during depressurization?"
Варианты: "To reduce structural stress on the aircraft", "To reach an altitude where supplemental oxygen is not required", "To improve radio communications", "To prepare for immediate landing"
Правильный ответ: "To reach an altitude where supplemental oxygen is not required"
Обратная связь: "Correct! The emergency descent aims to reach an altitude (typically 10,000 feet) where atmospheric pressure is sufficient for human breathing without supplemental oxygen."

AR объект 3:
Название: "Emergency Communication Protocol"
Маркер: [Изображение радиопанели с аварийной частотой]
Информация: "Emergency communications use standard phrases and frequencies. 'Mayday, Mayday, Mayday' indicates life-threatening emergencies, while 'Pan-Pan, Pan-Pan, Pan-Pan' signals urgent situations without immediate danger to life. Emergency communications should be clear, concise, and include: aircraft identification, nature of emergency, intentions, position, altitude, and assistance needed."
Интерактивное задание: Fill in the Blanks
Предложение: "For life-threatening emergencies, use '________, ________, ________' followed by aircraft identification, while '________, ________, ________' is used for urgent situations without immediate life threat."
Правильные ответы: "Mayday", "Mayday", "Mayday", "Pan-Pan", "Pan-Pan", "Pan-Pan"
Обратная связь: "Correct! 'Mayday' is the international distress signal for life-threatening emergencies, while 'Pan-Pan' indicates urgency without immediate danger to life."

[Дополнительные AR объекты для других аварийных ситуаций: разгерметизация, отказ гидравлики, проблемы с управлением, аварийная посадка и т.д.]
```

## Советы и лучшие практики

1. **Тщательное планирование маршрута**: Создавайте логический маршрут AR квеста, учитывая физическое расположение объектов и эргономику поиска.

2. **Четкие и распознаваемые маркеры**: Используйте высококачественные, контрастные изображения для AR маркеров, которые легко сканируются в различных условиях освещения.

3. **Контекстуальный контент**: Связывайте образовательный контент непосредственно с физическими объектами для создания значимых ассоциаций и улучшения запоминания.

4. **Поэтапное усложнение**: Начинайте с простых заданий и постепенно увеличивайте сложность по мере продвижения учащихся по маршруту квеста.

5. **Баланс информации и заданий**: Сочетайте информационные блоки с интерактивными заданиями для поддержания вовлеченности и проверки понимания.

6. **Альтернативные пути**: Предусмотрите альтернативные маршруты или дополнительные объекты для учета различных темпов обучения и интересов.

7. **Интеграция с реальными объектами**: По возможности, размещайте AR маркеры непосредственно на тех объектах, о которых идет речь, для создания прямой связи между реальным миром и образовательным контентом.

8. **Подготовка к техническим проблемам**: Предусмотрите альтернативные способы прохождения в случае технических проблем с распознаванием AR маркеров или работой устройств.

9. **Групповая динамика**: Проектируйте AR квесты, которые могут выполняться как индивидуально, так и в парах или малых группах для стимулирования коммуникации и сотрудничества.

10. **Безопасность прежде всего**: Убедитесь, что участники AR квеста могут безопасно перемещаться по маршруту, не отвлекаясь от окружающей обстановки в критические моменты.

11. **Документация и подсказки**: Предоставляйте вспомогательные материалы и карты для помощи в навигации по квесту, особенно в сложных или больших пространствах.

12. **Оценка эффективности**: Регулярно анализируйте результаты и обратную связь от учащихся для улучшения AR квестов и повышения их образовательной ценности.

---

H5P AR Scavenger — это инновационный инструмент, который объединяет физический мир с цифровым образовательным контентом, создавая уникальные возможности для изучения авиационного английского в аутентичном контексте. Технология дополненной реальности позволяет студентам взаимодействовать с реальными объектами авиационной среды, одновременно получая детальную информацию и выполняя задания, связанные с этими объектами. Следуя этому руководству, вы сможете создавать вовлекающие AR квесты, которые эффективно соединяют теоретические знания авиационного английского с практическим контекстом их применения.
