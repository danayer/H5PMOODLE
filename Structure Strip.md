# H5P Structure Strip в Moodle: Подробное руководство

## Содержание
- [Введение в H5P](#введение-в-h5p)
- [Что такое Structure Strip](#что-такое-structure-strip)
- [Установка H5P в Moodle](#установка-h5p-в-moodle)
- [Создание активности Structure Strip](#создание-активности-structure-strip)
- [Подробные настройки Structure Strip](#подробные-настройки-structure-strip)
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

## Что такое Structure Strip

Structure Strip (Структурная полоса) — это тип активности в H5P, который помогает учащимся анализировать структуру текста путем разметки его различных компонентов, частей или аспектов. Этот инструмент позволяет создать интерактивное задание, где учащиеся читают текст и идентифицируют его различные структурные элементы с помощью цветной разметки. Structure Strip особенно полезен для:

- Развития навыков чтения и анализа текста
- Обучения распознаванию структуры текста и его компонентов
- Понимания организации и логики профессиональных документов
- Развития критического мышления при работе с техническими текстами
- Тренировки внимания к деталям и точности интерпретации информации

Structure Strip является ценным инструментом для обучения целенаправленному чтению и пониманию структуры технических документов, что особенно важно в авиационной сфере с её строгими требованиями к точности и последовательности.

## Установка H5P в Moodle

Прежде чем создавать активности Structure Strip, необходимо установить H5P в вашей системе Moodle:

1. Войдите в Moodle как администратор
2. Перейдите в раздел "Администрирование сайта" > "Плагины" > "Установка плагинов"
3. Нажмите кнопку "Установить плагины из каталога плагинов Moodle"
4. Найдите "H5P" в списке плагинов и установите его
5. Следуйте инструкциям по установке
6. После завершения установки активируйте плагин

## Создание активности Structure Strip

### Шаг 1: Добавление активности H5P в курс

1. Перейдите на страницу вашего курса в Moodle
2. Включите режим редактирования, нажав кнопку "Режим редактирования" в правом верхнем углу
3. В нужном разделе курса нажмите "Добавить элемент или ресурс"
4. В открывшемся окне выберите "H5P интерактивный контент" и нажмите "Добавить"

### Шаг 2: Настройка основных параметров

1. Введите название для вашей активности в поле "Название"
2. При необходимости добавьте описание в поле "Описание"
3. В разделе "Настройки H5P" нажмите кнопку "Создать" или "Загрузить контент"
4. Из списка доступных типов контента выберите "Structure Strip"

### Шаг 3: Создание Structure Strip

1. В поле "Заголовок" введите название для вашего задания
2. В поле "Описание задания" объясните, что должны делать учащиеся
3. В поле "Текст для анализа" добавьте текст, который будут анализировать учащиеся
4. Нажмите "Добавить категорию" для создания категорий структурного анализа

5. Для каждой категории настройте:
   - **Заголовок категории**: краткое описание того, что учащиеся должны искать в тексте (например, "Технические термины", "Стандартные фразы", "Инструкции")
   - **Цвет категории**: выберите цвет, которым будет выделяться данная категория
   - **Описание категории**: добавьте подробное объяснение, что именно входит в эту категорию

6. Добавьте все необходимые категории для полного структурного анализа текста
7. При необходимости настройте образец решения (модельный ответ) для проверки

### Шаг 4: Настройка отображения и интерфейса

1. Настройте ширину структурной полосы
2. Определите тип выделения текста (полное слово или произвольное выделение)
3. Настройте визуальное оформление категорий и их отображение
4. Добавьте описания для разных уровней успешности выполнения задания

## Подробные настройки Structure Strip

### Настройки текста

- **Форматирование текста**: настройка шрифта, размера и оформления анализируемого текста
- **Разделение на параграфы**: структурирование текста для облегчения анализа
- **Подсветка ключевых слов**: возможность предварительного выделения важных элементов

### Настройки категорий

- **Количество категорий**: определение числа структурных элементов для анализа
- **Описания категорий**: настройка подробности инструкций для каждой категории
- **Обязательные категории**: определение, какие категории должны быть обязательно найдены

### Настройки обратной связи

- **Мгновенная обратная связь**: настройка отображения правильности выделения в реальном времени
- **Итоговая обратная связь**: настройка сообщений по результатам выполнения задания
- **Подсказки**: добавление подсказок для сложных случаев

### Настройки оценивания

- **Критерии оценки**: настройка параметров для автоматической оценки выполнения
- **Пороговые значения**: определение уровней успешности (отлично, хорошо, удовлетворительно)
- **Отображение баллов**: настройка показа результатов учащимся

### Шаг 5: Сохранение и публикация

1. После завершения всех настроек нажмите "Сохранить и показать"
2. Проверьте, как работает ваше задание с точки зрения студента
3. При необходимости вернитесь к редактированию и внесите изменения

## Примеры использования для авиационного английского

### Пример 1: Анализ авиационного METAR и TAF

```
Заголовок: Identifying Components of METAR and TAF Reports
Описание задания: "Read the following aviation weather reports and use the structure strip to mark different components according to the categories provided. This will help you understand the structured format of aviation meteorological reports."

Текст для анализа:
"METAR UUEE 151530Z 19005MPS 9999 FEW033 SCT066 10/06 Q1024 R24R/CLRD70 NOSIG

TAF UUEE 151100Z 1512/1612 20006MPS 9999 BKN033 
     TEMPO 1512/1516 26008G13MPS 4000 -SHRA BR BKN014 BKN030CB
     BECMG 1522/1524 VRB03MPS
     BECMG 1606/1608 18005MPS"

Категории:
1. Заголовок: "Location Identifier" | Цвет: желтый | Описание: "ICAO airport code, e.g., UUEE for Sheremetyevo International Airport"
2. Заголовок: "Time and Date" | Цвет: зеленый | Описание: "Date and time in UTC, format: day/hour/minute, e.g., 151530Z means 15th day, 15:30 UTC"
3. Заголовок: "Wind Information" | Цвет: красный | Описание: "Direction (in degrees) and speed of wind, e.g., 19005MPS means 190 degrees at 5 meters per second"
4. Заголовок: "Visibility" | Цвет: синий | Описание: "Horizontal visibility in meters, e.g., 9999 means visibility 10 km or more"
5. Заголовок: "Weather Phenomena" | Цвет: фиолетовый | Описание: "Current weather conditions using standard abbreviations, e.g., -SHRA means light shower rain"
6. Заголовок: "Cloud Information" | Цвет: оранжевый | Описание: "Cloud cover and height, e.g., FEW033 means few clouds at 3,300 feet"
7. Заголовок: "Change Indicators" | Цвет: голубой | Описание: "Terms indicating changing conditions, e.g., TEMPO (temporary), BECMG (becoming)"
```

### Пример 2: Анализ процедуры нормальной эксплуатации

```
Заголовок: Analyzing Standard Operating Procedure (SOP) Components
Описание задания: "Review the following excerpt from an aircraft SOP and identify its different structural elements using the color-coded categories. This will help you understand how SOPs are organized and the specific language used for each component."

Текст для анализа:
"NORMAL PROCEDURES: ENGINE START

1. PREFLIGHT CHECKLIST................COMPLETED
2. PARKING BRAKE..........................SET
3. ENGINE AREA.............................CLEAR
4. BATTERY SWITCH........................ON
5. THROTTLE................................IDLE
6. MIXTURE...................................RICH
7. PROPELLER................................HIGH RPM
8. FUEL SELECTOR........................ON
9. MASTER SWITCH........................ON
10. BEACON LIGHT.........................ON
11. IGNITION SWITCH.....................START
    When engine starts:
12. OIL PRESSURE..........................CHECK (within 30 seconds)
13. IGNITION SWITCH.....................BOTH
14. ENGINE INSTRUMENTS..............CHECK
15. ALTERNATOR...........................ON
16. RADIOS....................................AS REQUIRED

CAUTION: If engine fails to start within 10 seconds of cranking, release starter button, allow starter to cool for 20 seconds, then try again. If engine fails to start after three attempts, discontinue start procedure and determine cause.

NOTE: In cold weather conditions, engine preheat is recommended for temperatures below +10°C (50°F)."

Категории:
1. Заголовок: "Section Headers" | Цвет: красный | Описание: "Main section titles and subtitles, e.g., 'NORMAL PROCEDURES: ENGINE START'"
2. Заголовок: "Sequential Steps" | Цвет: зеленый | Описание: "Numbered procedural steps that must be followed in order"
3. Заголовок: "Action Items" | Цвет: желтый | Описание: "Specific actions to be performed, typically in uppercase, e.g., 'COMPLETED', 'SET', 'ON'"
4. Заголовок: "Conditional Instructions" | Цвет: синий | Описание: "Instructions that apply only under certain conditions, e.g., 'When engine starts:'"
5. Заголовок: "Cautions and Warnings" | Цвет: оранжевый | Описание: "Safety-critical information prefaced with 'CAUTION' or 'WARNING'"
6. Заголовок: "Notes and Additional Information" | Цвет: фиолетовый | Описание: "Supplementary information prefaced with 'NOTE'"
```

### Пример 3: Анализ радиообмена пилот-диспетчер

```
Заголовок: Analyzing Pilot-Controller Communication Structure
Описание задания: "Study the following ATC-pilot communication transcript and identify the different components of standard radio communication using the structure strip. This will help you recognize and understand the patterns and phraseology used in aviation communications."

Текст для анализа:
"ATC: Fastair 345, Heathrow Tower, runway 27L, cleared for takeoff, wind 270 degrees 8 knots.

PILOT: Cleared for takeoff runway 27L, Fastair 345.

[After takeoff]

PILOT: Heathrow Tower, Fastair 345, passing 2,500 feet.

ATC: Fastair 345, contact London Departure on 126.9, good day.

PILOT: Contact London Departure on 126.9, Fastair 345, good day.

[Frequency change]

PILOT: London Departure, good day, Fastair 345, passing 3,000 feet, climbing to flight level 80.

ATC: Fastair 345, London Departure, identified, climb to flight level 120, direct to TIMBA.

PILOT: Climb to flight level 120, direct to TIMBA, Fastair 345.

ATC: Fastair 345, expect higher in 5 minutes.

PILOT: Roger, Fastair 345.

[Weather deterioration]

PILOT: London Departure, Fastair 345, requesting deviation 10 miles right of track due to weather.

ATC: Fastair 345, deviation approved, report when able to resume normal routing."

Категории:
1. Заголовок: "Call Signs" | Цвет: желтый | Описание: "Aircraft identifiers (e.g., Fastair 345) and ATC unit names (e.g., Heathrow Tower)"
2. Заголовок: "Instructions" | Цвет: красный | Описание: "Directives from ATC to pilots, e.g., 'cleared for takeoff', 'climb to flight level 120'"
3. Заголовок: "Readbacks" | Цвет: зеленый | Описание: "Pilot's repetition of ATC instructions to confirm understanding"
4. Заголовок: "Position Reports" | Цвет: синий | Описание: "Information about aircraft's current position or altitude, e.g., 'passing 2,500 feet'"
5. Заголовок: "Requests" | Цвет: фиолетовый | Описание: "Pilot's requests for specific clearances or deviations, e.g., 'requesting deviation'"
6. Заголовок: "Acknowledgments" | Цвет: оранжевый | Описание: "Simple confirmations like 'Roger' or 'Good day'"
7. Заголовок: "Contextual Notes" | Цвет: серый | Описание: "Text in brackets that provides context but is not part of the actual communication"
```

### Пример 4: Анализ авиационного отчета о происшествии

```
Заголовок: Analyzing Aviation Incident Report Structure
Описание задания: "Examine the following aviation incident report and identify its structural components using the color categories. This exercise will help you understand how aviation incidents are documented and the specific language used in official reports."

Текст для анализа:
"INCIDENT REPORT
Date: 15 March 2023
Aircraft: Boeing 737-800
Registration: G-ABCD
Operator: Fastair
Flight Number: FA345
Route: London Heathrow (EGLL) to Amsterdam Schiphol (EHAM)

SUMMARY:
During the climb phase passing FL180, the flight crew observed a pressurization system caution message. The aircraft leveled off and the crew performed the appropriate checklist procedures. The aircraft returned to London Heathrow and landed safely with no injuries to passengers or crew.

SEQUENCE OF EVENTS:
1. At 10:23 UTC, during climb through FL180, the PRESS SYS caption illuminated on the warning display.
2. The Captain took control of the aircraft while the First Officer ran the Pressurization System Failure checklist.
3. The crew leveled off at FL200 and informed ATC of the technical issue.
4. After completing the checklist, the cabin pressure remained within acceptable limits but was not normalizing.
5. At 10:27 UTC, the crew declared PAN-PAN and requested to return to London Heathrow.
6. The aircraft was cleared for an immediate return and given priority handling.
7. At 11:05 UTC, the aircraft landed safely on runway 27L.

TECHNICAL FINDINGS:
Initial inspection revealed a faulty outflow valve controller. The component was replaced and the aircraft returned to service after appropriate testing.

OPERATIONAL RECOMMENDATIONS:
1. Crew response was in accordance with SOPs and manufacturer recommendations.
2. Communication between flight crew and ATC was clear and effective.
3. No additional operational recommendations are required.

SAFETY RECOMMENDATIONS:
1. Maintenance department to review component service history for potential pattern of premature failures.
2. Consider including this scenario in simulator training sessions.

Report compiled by: John Smith, Safety Investigation Officer
Approved by: Jane Wilson, Chief Safety Officer"

Категории:
1. Заголовок: "Report Headers" | Цвет: красный | Описание: "Main section titles, e.g., 'INCIDENT REPORT', 'SUMMARY', 'TECHNICAL FINDINGS'"
2. Заголовок: "Identification Information" | Цвет: желтый | Описание: "Details identifying the flight, aircraft, and circumstances (date, registration, operator, etc.)"
3. Заголовок: "Chronological Events" | Цвет: зеленый | Описание: "Time-stamped descriptions of what happened in sequence"
4. Заголовок: "Technical Information" | Цвет: синий | Описание: "Technical details about aircraft systems, malfunctions, or components"
5. Заголовок: "Procedural References" | Цвет: фиолетовый | Описание: "References to procedures, checklists, or standard practices followed"
6. Заголовок: "Recommendations" | Цвет: оранжевый | Описание: "Suggestions for improvements or actions to be taken"
7. Заголовок: "Authorization Information" | Цвет: серый | Описание: "Names, titles, and roles of people involved in creating the report"
```

### Пример 5: Анализ руководства по эксплуатации воздушного судна

```
Заголовок: Analyzing Aircraft Manual Content Structure
Описание задания: "Study the following excerpt from an aircraft operating manual and identify the different structural elements using the categories provided. This will help you understand how technical aviation manuals are organized and how to quickly locate specific information."

Текст для анализа:
"CHAPTER 2: LIMITATIONS

2.1 INTRODUCTION
This chapter provides operating limitations, instrument markings, and basic placards necessary for the safe operation of the aircraft, its engines, standard systems and standard equipment.

2.2 AIRSPEED LIMITATIONS
The indicated airspeed limitations and their operational significance are shown in Table 2-1.

Table 2-1: Airspeed Limitations
SPEED | KCAS | REMARKS
VMO | 340 | Maximum operating speed
MMO | 0.82 | Maximum operating Mach number
VA | 250 | Maneuvering speed at maximum weight
VFE | 200 | Maximum flap extended speed

WARNING: Exceeding VMO/MMO may result in reduced controllability of the aircraft or structural damage.

NOTE: For operations at airspeeds greater than 250 KCAS below 10,000 ft, refer to approved special procedures.

2.3 POWERPLANT LIMITATIONS
2.3.1 Engine Limits
Maximum takeoff thrust: 24,000 lbs (5 min)
Maximum continuous thrust: 22,000 lbs

CAUTION: Operation above maximum continuous thrust limits is restricted to takeoff and go-around phases only.

2.3.2 Engine Operating Limits
Engine operating limitations are displayed on the Engine Indicating System (EIS) as shown in Table 2-2.

REFERENCE: For detailed engine operation parameters, see Chapter 7: Powerplant."

Категории:
1. Заголовок: "Section Headers" | Цвет: красный | Описание: "Chapter titles and section numbers, e.g., 'CHAPTER 2: LIMITATIONS', '2.1 INTRODUCTION'"
2. Заголовок: "Definitions and Descriptions" | Цвет: зеленый | Описание: "Explanatory text that defines or describes systems, limits, or procedures"
3. Заголовок: "Numerical Values and Limits" | Цвет: синий | Описание: "Specific quantitative parameters, measurements, or restrictions, e.g., 'Maximum takeoff thrust: 24,000 lbs'"
4. Заголовок: "Tables and Structured Data" | Цвет: желтый | Описание: "Organized information presented in tabular format, e.g., 'Table 2-1: Airspeed Limitations'"
5. Заголовок: "Warnings, Cautions, Notes" | Цвет: оранжевый | Описание: "Safety information or special emphasis items marked as WARNING, CAUTION, or NOTE"
6. Заголовок: "Cross-References" | Цвет: фиолетовый | Описание: "References to other sections or chapters, e.g., 'For detailed engine operation parameters, see Chapter 7'"
```

## Советы и лучшие практики

1. **Четкие инструкции**: Предоставляйте ясные и подробные инструкции о том, что именно учащиеся должны выделять в тексте и по каким критериям.

2. **Адекватное количество категорий**: Ограничьте число категорий до 5-7, чтобы не перегружать учащихся и сохранить фокус на ключевых структурных элементах.

3. **Различимые цвета**: Выбирайте контрастные и хорошо различимые цвета для разных категорий, учитывая возможные проблемы с цветовосприятием.

4. **Осмысленная категоризация**: Создавайте категории, которые действительно отражают важные аспекты структуры текста и помогают понять его организацию.

5. **Подготовительная работа**: Перед использованием Structure Strip проведите предварительное обсуждение типа анализируемого текста и его типичных структурных особенностей.

6. **Постепенное усложнение**: Начинайте с простых, коротких текстов и постепенно переходите к более сложным и длинным документам по мере развития навыков учащихся.

7. **Комбинирование с другими активностями**: Используйте Structure Strip как часть более широкого учебного процесса, дополняя его обсуждениями, письменными заданиями или другими интерактивными элементами.

8. **Баланс между точностью и гибкостью**: Позволяйте некоторую гибкость в интерпретации, особенно для сложных текстов, где границы между категориями могут быть размыты.

9. **Моделирование процесса**: Демонстрируйте процесс анализа на примере, показывая учащимся, как идентифицировать и маркировать различные элементы текста.

10. **Обратная связь по анализу**: Обеспечивайте содержательную обратную связь не только о правильности выделения, но и о понимании структуры текста в целом.

11. **Связь с профессиональной практикой**: Объясняйте, как умение анализировать структуру авиационных текстов связано с реальными профессиональными ситуациями и задачами.

12. **Самостоятельный анализ**: Поощряйте учащихся создавать собственные категории для анализа текстов, развивая их метакогнитивные навыки и понимание структуры документов.

---

H5P Structure Strip — это эффективный инструмент для развития навыков критического чтения и анализа текста, особенно полезный в контексте изучения авиационного английского. Он помогает учащимся видеть и понимать организационные паттерны в технических документах, отчетах, руководствах и коммуникациях, что критически важно для безопасности и эффективности в авиационной отрасли. Следуя этому руководству, вы сможете создавать целенаправленные задания по анализу структуры текста, которые подготовят ваших студентов к уверенной работе с разнообразными авиационными документами на английском языке.
