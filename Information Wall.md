# H5P Information Wall в Moodle: Подробное руководство

## Содержание
- [Введение в H5P](#введение-в-h5p)
- [Что такое Information Wall](#что-такое-information-wall)
- [Установка H5P в Moodle](#установка-h5p-в-moodle)
- [Создание активности Information Wall](#создание-активности-information-wall)
- [Подробные настройки Information Wall](#подробные-настройки-information-wall)
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

## Что такое Information Wall

Information Wall (Информационная стена) — это тип активности в H5P, который позволяет создавать интерактивные доски с карточками или плитками информации, организованными в визуально привлекательную сетку. Каждый элемент информационной стены может содержать заголовок, изображение, текст и дополнительный контент, который отображается при нажатии на карточку. Этот формат особенно полезен для:

- Создания структурированных коллекций информации
- Организации справочных материалов и глоссариев
- Представления разнообразных концепций в едином интерфейсе
- Создания интерактивных досок объявлений или информационных щитов
- Представления учебных материалов в формате, напоминающем доску Pinterest или Instagram

Information Wall позволяет учащимся исследовать информацию в удобном для них темпе и порядке, обеспечивая наглядный и интуитивно понятный доступ к различным темам или концепциям, связанным с определенной областью знаний.

## Установка H5P в Moodle

Прежде чем создавать активности Information Wall, необходимо установить H5P в вашей системе Moodle:

1. Войдите в Moodle как администратор
2. Перейдите в раздел "Администрирование сайта" > "Плагины" > "Установка плагинов"
3. Нажмите кнопку "Установить плагины из каталога плагинов Moodle"
4. Найдите "H5P" в списке плагинов и установите его
5. Следуйте инструкциям по установке
6. После завершения установки активируйте плагин

## Создание активности Information Wall

### Шаг 1: Добавление активности H5P в курс

1. Перейдите на страницу вашего курса в Moodle
2. Включите режим редактирования, нажав кнопку "Режим редактирования" в правом верхнем углу
3. В нужном разделе курса нажмите "Добавить элемент или ресурс"
4. В открывшемся окне выберите "H5P интерактивный контент" и нажмите "Добавить"

### Шаг 2: Настройка основных параметров

1. Введите название для вашей активности в поле "Название"
2. При необходимости добавьте описание в поле "Описание"
3. В разделе "Настройки H5P" нажмите кнопку "Создать" или "Загрузить контент"
4. Из списка доступных типов контента выберите "Information Wall"

### Шаг 3: Создание информационной стены

1. В поле "Заголовок" введите название для вашей информационной стены
2. При необходимости добавьте инструкции в поле "Инструкции для пользователя"
3. Нажмите "Добавить панель" для создания первой карточки на информационной стене
4. Для каждой панели настройте следующие элементы:
   - **Заголовок панели**: введите краткий заголовок карточки
   - **Изображение**: загрузите изображение, которое будет отображаться на карточке
   - **Текст**: добавьте основной текст или описание
   - **Дополнительный контент**: добавьте медиа или текст, который будет отображаться при нажатии на карточку
   
5. Повторите процесс добавления панелей для создания всех необходимых карточек
6. Организуйте порядок карточек с помощью кнопок перемещения вверх/вниз

### Шаг 4: Добавление дополнительного контента в панели

1. Для каждой панели определите, какой тип дополнительного контента вы хотите добавить:
   - **Нет дополнительного контента**: только заголовок, изображение и текст
   - **Видео**: встроенное видео, которое будет воспроизводиться при открытии карточки
   - **Изображение**: дополнительное полноразмерное изображение
   - **Текст**: дополнительный текстовый блок с расширенной информацией
   
2. Настройте выбранный тип дополнительного контента для каждой панели
3. Убедитесь, что дополнительный контент дополняет и расширяет основную информацию на карточке

## Подробные настройки Information Wall

### Настройки внешнего вида

- **Режим отображения панелей**: выбор между отображением в виде сетки или списка
- **Цветовая схема**: настройка основных цветов для панелей и элементов управления
- **Ширина и высота панелей**: настройка геометрических параметров карточек
- **Интервал между панелями**: настройка расстояния между карточками
- **Фильтрация контента**: настройка возможности фильтрации карточек по категориям

### Настройки поведения панелей

- **Эффект при открытии панели**: выбор анимации при открытии дополнительного контента
- **Режим открытия дополнительного контента**: выбор между всплывающим окном и раскрытием внутри стены
- **Автоматическое закрытие**: настройка автоматического закрытия панели при открытии другой
- **Кнопка закрытия**: показывать или скрывать явную кнопку для закрытия панели

### Настройки отзывчивости

- **Адаптивная сетка**: настройка поведения сетки на различных устройствах
- **Количество колонок**: настройка количества колонок для разных размеров экрана
- **Мобильный вид**: настройка отображения на мобильных устройствах

### Настройки доступности

- **Альтернативный текст для изображений**: добавление описаний для поддержки скринридеров
- **Поддержка клавиатурной навигации**: настройка управления с клавиатуры
- **Высокий контраст**: настройки для улучшения читаемости текста

### Шаг 5: Сохранение и публикация

1. После завершения всех настроек нажмите "Сохранить и показать"
2. Проверьте, как работает ваша информационная стена с точки зрения студента
3. При необходимости вернитесь к редактированию и внесите изменения

## Примеры использования для авиационного английского

### Пример 1: Аэропортовая информационная доска

```
Заголовок: International Airport Information Board
Инструкции: "Click on any airport facility to learn more about its services and the related aviation terminology in English."

Панель 1:
Заголовок: Terminal Buildings
Изображение: Фотография современного терминала аэропорта
Текст: "The primary facilities for passenger processing and services before departure or after arrival."
Дополнительный контент (Текст):
"Key areas of a terminal include:
- Check-in counters (where passengers confirm their presence and drop luggage)
- Security checkpoint (where passengers and luggage are screened)
- Departure lounge (waiting area for boarding)
- Arrival hall (where passengers exit after landing)
- Baggage claim (where passengers collect checked luggage)
- Customs and immigration (border control)"

Панель 2:
Заголовок: Control Tower
Изображение: Фотография диспетчерской вышки
Текст: "The facility that manages aircraft movements on the ground and in the air near the airport."
Дополнительный контент (Изображение и текст):
[Детальное изображение внутренней части диспетчерской вышки]
"The control tower houses air traffic controllers who:
- Authorize takeoffs and landings
- Manage ground movement of aircraft
- Issue taxi instructions
- Monitor runway usage
- Coordinate with approach and departure control
Common phrases: 'Cleared for takeoff', 'Cleared to land', 'Taxi to holding point'"

Панель 3:
Заголовок: Runways
Изображение: Аэрофотоснимок взлетно-посадочных полос
Текст: "Long strips of prepared surface for aircraft takeoff and landing."
Дополнительный контент (Видео):
[Видео взлета и посадки самолета с комментариями о стандартной фразеологии, используемой при операциях на ВПП]

Панель 4:
Заголовок: Taxiways
Изображение: Фотография самолета на рулежной дорожке
Текст: "Paths for aircraft to travel between runways and other airport facilities."
Дополнительный контент (Текст):
"Taxiways are identified by letters (e.g., Taxiway A, B, C) and connect:
- Runways to terminals
- Runways to hangars
- Runways to other runways
Communication example:
ATC: 'Fastair 345, taxi to holding point runway 27 via taxiway A'
Pilot: 'Taxi to holding point runway 27 via taxiway A, Fastair 345'"

[Дополнительные панели для других объектов аэропорта: Hangars, Cargo Facilities, Navigation Aids, etc.]
```

### Пример 2: Системы самолета и авиационная терминология

```
Заголовок: Aircraft Systems and Terminology
Инструкции: "Explore different aircraft systems to learn technical terminology and components in aviation English."

Панель 1:
Заголовок: Hydraulic System
Изображение: Схема гидравлической системы самолета
Текст: "The system that uses pressurized fluid to power flight controls, landing gear, and other components."
Дополнительный контент (Текст и изображение):
[Детальная схема гидравлической системы с подписями]
"Key components and terminology:
- Hydraulic pumps (engine-driven or electric)
- Reservoirs (fluid storage tanks)
- Accumulators (pressure storage devices)
- Actuators (converts hydraulic pressure to mechanical movement)
- Selectors (control valves for directing hydraulic flow)
- Pressure relief valves (prevent overpressure conditions)"

Панель 2:
Заголовок: Flight Controls
Изображение: Фотография органов управления в кабине
Текст: "Devices that allow pilots to control the aircraft's attitude and trajectory."
Дополнительный контент (Видео):
[Видео демонстрирующее работу основных органов управления с пояснениями на английском языке]

Панель 3:
Заголовок: Electrical System
Изображение: Схема электрической системы
Текст: "System that generates, stores, and distributes electrical power throughout the aircraft."
Дополнительный контент (Текст):
"Main components of aircraft electrical systems:
- Generators (primary power source, driven by engines)
- Auxiliary Power Unit (APU) generator (ground and backup power)
- Batteries (for starting and emergency power)
- Bus bars (electrical power distribution points)
- Circuit breakers (protection against overloads)
- Inverters (convert DC to AC power)
- Transformers (modify voltage levels)"

Панель 4:
Заголовок: Avionics
Изображение: Фотография современной цифровой приборной панели
Текст: "Electronic systems used for communication, navigation, and aircraft control."
Дополнительный контент (Изображение и текст):
[Детальное изображение приборной панели с подписями]
"Major avionics systems include:
- Primary Flight Display (PFD) - shows attitude, airspeed, altitude
- Navigation Display (ND) - shows route, waypoints, weather
- Engine Indicating and Crew Alerting System (EICAS)
- Flight Management System (FMS)
- Weather Radar
- Traffic Collision Avoidance System (TCAS)
- Automatic Flight Control System (AFCS)"

[Дополнительные панели для других систем: Fuel System, Landing Gear, Engines, Pressurization, etc.]
```

### Пример 3: Метеорологические явления и авиационный английский

```
Заголовок: Weather Phenomena in Aviation
Инструкции: "Learn about various weather conditions affecting flight and related aviation English terminology."

Панель 1:
Заголовок: Thunderstorms
Изображение: Фотография кучево-дождевых облаков
Текст: "Powerful atmospheric disturbances with lightning, heavy precipitation, and potentially severe turbulence."
Дополнительный контент (Видео и текст):
[Видео о влиянии грозовой активности на полеты]
"Aviation terminology related to thunderstorms:
- Cumulonimbus (CB): cloud type associated with thunderstorms
- Convective activity: vertical air movement creating storms
- Lightning strike: electrical discharge hazard
- Cell: individual thunderstorm unit
- Squall line: line of thunderstorms
METAR example: 'TEMPO 1416 TSRA FEW010 SCT030CB BKN040'
(Temporarily between 14:00-16:00 UTC, thunderstorm with rain, few clouds at 1,000 ft, scattered cumulonimbus at 3,000 ft, broken clouds at 4,000 ft)"

Панель 2:
Заголовок: Icing
Изображение: Фотография обледенения на крыле самолета
Текст: "Formation of ice on aircraft surfaces, which can affect aerodynamics, weight, and performance."
Дополнительный контент (Текст и изображение):
[Изображения различных типов обледенения]
"Types of airframe icing:
- Clear ice: transparent, heavy, hard to detect
- Rime ice: rough, opaque, brittle
- Mixed ice: combination of clear and rime

Severity terminology:
- Trace: barely perceptible
- Light: noticeable but not hazardous with ice protection
- Moderate: potentially hazardous, ice protection needed
- Severe: beyond capability of ice protection systems

Pilot report example: 'Moderate mixed icing between FL080 and FL120'"

Панель 3:
Заголовок: Visibility Restrictions
Изображение: Фотография аэропорта в тумане
Текст: "Atmospheric conditions that reduce visibility, affecting takeoff, landing, and visual navigation."
Дополнительный контент (Текст):
"Common visibility restrictions in aviation:
- Fog (FG): water droplets suspended near ground
- Mist (BR): less dense than fog, visibility > 1000m
- Haze (HZ): fine dust or salt particles
- Smoke (FU): suspended products of combustion

Visibility reporting terminology:
- RVR (Runway Visual Range): measured in meters
- CAVOK: Ceiling and Visibility OK (visibility >10km)
- FEW, SCT, BKN, OVC: cloud coverage descriptors

METAR example: 'EHAM 121030Z 24008KT 0800 FG VV002 10/10 Q1013'
(Amsterdam Schiphol, 12th day at 10:30 UTC, wind 240° at 8 knots, visibility 800 meters in fog, vertical visibility 200 feet, temperature and dew point both 10°C, QNH 1013 hPa)"

Панель 4:
Заголовок: Wind Shear
Изображение: Графическая иллюстрация ветрового сдвига
Текст: "A sudden change in wind speed or direction over a short distance, potentially hazardous during takeoff and landing."
Дополнительный контент (Видео):
[Обучающее видео о технике прохождения зоны ветрового сдвига с профессиональным комментарием на английском]

[Дополнительные панели для других метеоявлений: Turbulence, Microbursts, Volcanic Ash, High-Altitude Winds, etc.]
```

### Пример 4: Авиационные профессии и должностные обязанности

```
Заголовок: Aviation Professions and Responsibilities
Инструкции: "Learn about different aviation professionals and their roles using English terminology."

Панель 1:
Заголовок: Pilot (Captain)
Изображение: Фотография капитана самолета
Текст: "The commander of the aircraft with ultimate responsibility for safety and operations."
Дополнительный контент (Текст):
"Key responsibilities of a captain:
- Overall aircraft safety and operation
- Final authority for all decisions
- Crew management and leadership
- Communication with ATC and company
- Completion of flight documentation
- Implementation of standard operating procedures (SOPs)

Common English phrases used:
- 'I have control' (when taking control of aircraft)
- 'My aircraft' (confirming active control)
- 'Standard calls' (callouts during critical phases)
- 'Decision to continue/abort' (during critical phases)"

Панель 2:
Заголовок: First Officer (Co-pilot)
Изображение: Фотография второго пилота за работой
Текст: "The second-in-command pilot who assists the captain in flying and managing the aircraft."
Дополнительный контент (Видео):
[Видео, демонстрирующее взаимодействие между капитаном и вторым пилотом в кабине с акцентом на используемую профессиональную лексику]

Панель 3:
Заголовок: Air Traffic Controller
Изображение: Фотография диспетчера за работой
Текст: "Professional responsible for directing aircraft on the ground and in the air to maintain safe separation."
Дополнительный контент (Аудио и текст):
[Аудиозаписи примеров радиообмена между диспетчером и пилотами]
"Types of air traffic controllers:
- Tower (TWR): manage takeoff, landing, and airport movements
- Ground (GND): manage aircraft on taxiways
- Approach (APP): control arriving and departing aircraft
- Area (CTR): handle en-route traffic

Standard phraseology examples:
- 'Cleared for takeoff' (permission to begin takeoff)
- 'Descend to flight level 100' (instruction to descend)
- 'Report established on the localizer' (request for position confirmation)
- 'Squawk 7421' (instruction to set transponder code)"

Панель 4:
Заголовок: Aircraft Maintenance Engineer
Изображение: Фотография техника, обслуживающего самолет
Текст: "Professional responsible for ensuring the airworthiness and proper functioning of aircraft."
Дополнительный контент (Текст с изображениями):
[Серия изображений, показывающих различные аспекты технического обслуживания]
"Key responsibilities:
- Scheduled maintenance checks (A, B, C, D checks)
- Troubleshooting and fault rectification
- Component replacement and repair
- Documentation of maintenance actions
- Adherence to airworthiness directives (ADs)

Technical communication terminology:
- Malfunctions, defects, failures
- Serviceable vs. unserviceable
- Minimum Equipment List (MEL)
- Sign-off and return to service
- Technical log entries"

[Дополнительные панели для других профессий: Flight Dispatcher, Cabin Crew, Ground Handling Agent, Aviation Meteorologist, etc.]
```

### Пример 5: Процедуры безопасности и аварийные ситуации

```
Заголовок: Safety Procedures and Emergency Situations
Инструкции: "Explore different safety procedures and emergency situations to learn related aviation English terminology."

Панель 1:
Заголовок: Engine Failure
Изображение: Предупреждающий индикатор отказа двигателя
Текст: "Loss of engine power requiring immediate pilot action and communication."
Дополнительный контент (Текст и изображение):
[Схема порядка действий при отказе двигателя]
"Standard procedure terminology:
- 'Engine failure' or 'Engine out' (declaration of condition)
- 'Securing the engine' (shutting down the engine safely)
- 'Pan-Pan, Pan-Pan, Pan-Pan' (urgency signal)
- 'Mayday, Mayday, Mayday' (if situation is life-threatening)

Example ATC communication:
Pilot: 'Mayday, Mayday, Mayday, Fastair 345, engine failure, request immediate landing runway 27'
ATC: 'Fastair 345, cleared straight-in approach runway 27, wind 270 degrees 5 knots, emergency services alerted'
Pilot: 'Cleared straight-in approach runway 27, Fastair 345'"

Панель 2:
Заголовок: Cabin Depressurization
Изображение: Фотография кислородных масок в салоне
Текст: "Loss of cabin pressure requiring immediate descent and emergency procedures."
Дополнительный контент (Видео):
[Обучающее видео о правильных действиях экипажа при разгерметизации]

Панель 3:
Заголовок: In-flight Fire
Изображение: Предупреждающий индикатор пожара
Текст: "Fire onboard the aircraft, one of the most serious emergency situations."
Дополнительный контент (Текст):
"Types of in-flight fires:
- Engine fire
- Electrical fire
- Galley fire
- Cabin fire
- Cargo compartment fire

Critical terminology:
- 'Fire indication' (warning of possible fire)
- 'Confirmed fire' (visual confirmation)
- 'Fire containment' (actions to limit spread)
- 'Fire extinguished' (fire is out)
- 'Smoke removal' (clearing smoke after fire)

Emergency checklist elements:
- Identification of fire source
- Use of appropriate fire extinguishers
- Isolation of electrical systems if needed
- Communication with cabin crew
- Preparation for potential diversion or emergency landing"

Панель 4:
Заголовок: Medical Emergency
Изображение: Фотография медицинского оборудования на борту
Текст: "Health-related situations requiring immediate attention and possibly diversion."
Дополнительный контент (Текст):
"Standard procedures for medical emergencies:
1. Assessment of the situation
2. Request for medical professionals among passengers
3. Use of onboard medical kit
4. Communication with ground-based medical services
5. Decision regarding continuation or diversion

Key phrases:
- 'Medical emergency on board'
- 'Request medical assistance'
- 'Passenger requires immediate medical attention'
- 'Medical diversion required/not required'
- 'Request priority handling'"

[Дополнительные панели для других аварийных ситуаций: Bird Strike, Fuel Emergency, Hydraulic Failure, etc.]
```

## Советы и лучшие практики

1. **Четкая организация**: Организуйте панели в логические группы или категории для облегчения поиска и изучения.

2. **Краткость заголовков**: Создавайте лаконичные, но информативные заголовки для каждой панели, которые ясно указывают на ее содержание.

3. **Качественные изображения**: Используйте чёткие, профессиональные изображения, которые визуально передают ключевую информацию о содержании панели.

4. **Сбалансированный текст**: Основной текст панели должен быть кратким и информативным, оставляя более подробную информацию для дополнительного контента.

5. **Множественные медиаформаты**: Комбинируйте различные типы медиа (текст, изображения, видео, аудио) для создания разнообразного и вовлекающего учебного опыта.

6. **Точная терминология**: Уделяйте особое внимание точности авиационной терминологии и фразеологии, используя стандарты ICAO и общепринятые профессиональные термины.

7. **Последовательное оформление**: Поддерживайте единый стиль оформления панелей для создания профессионального и сбалансированного внешнего вида.

8. **Приоритизация содержания**: Размещайте наиболее важную информацию в верхней части информационной стены, где она будет сразу заметна.

9. **Внутренние связи**: При возможности создавайте перекрестные ссылки между связанными панелями для построения более целостной картины знаний.

10. **Фильтрация по категориям**: Если ваша информационная стена содержит много панелей, добавьте возможность фильтрации по категориям для облегчения навигации.

11. **Поддержка доступности**: Обеспечьте высокий контраст текста и фона, добавьте альтернативные описания для изображений и поддержите навигацию с клавиатуры.

12. **Регулярное обновление**: Поддерживайте актуальность информации, особенно когда речь идет о технических деталях, процедурах и стандартах, которые могут меняться со временем.

---

H5P Information Wall — это эффективный инструмент для создания визуально привлекательных и интерактивных коллекций информации, особенно для предметов с богатой терминологией, такими как авиационный английский. Информационные стены позволяют структурировать разнообразную информацию в едином интерфейсе, давая учащимся возможность исследовать связанные концепции и терминологию в индивидуальном темпе. Следуя этому руководству, вы сможете создавать информативные и вовлекающие информационные стены, которые помогут вашим студентам эффективно изучать авиационный английский язык.
