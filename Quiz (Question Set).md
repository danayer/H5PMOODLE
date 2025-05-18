# H5P Quiz (Question Set) в Moodle: Подробное руководство

## Содержание
- [Введение в H5P](#введение-в-h5p)
- [Что такое Quiz (Question Set)](#что-такое-quiz-question-set)
- [Установка H5P в Moodle](#установка-h5p-в-moodle)
- [Создание активности Quiz (Question Set)](#создание-активности-quiz-question-set)
- [Подробные настройки Quiz (Question Set)](#подробные-настройки-quiz-question-set)
- [Примеры упражнений по авиационному английскому](#примеры-упражнений-по-авиационному-английскому)
- [Советы и лучшие практики](#советы-и-лучшие-практики)

## Введение в H5P

H5P (HTML5 Package) — это открытая и бесплатная технология для создания интерактивного контента. Она позволяет преподавателям создавать разнообразные интерактивные элементы обучения, которые можно встраивать в систему управления обучением (LMS), такую как Moodle.

Основные преимущества H5P:
- Интерактивность и вовлечение
- Множество типов контента (более 40 различных видов активностей)
- Адаптивность для мобильных устройств
- Возможность повторного использования
- Поддержка мультимедиа

## Что такое Quiz (Question Set)

Quiz (Question Set) — это тип активности в H5P, который позволяет создавать последовательные наборы вопросов различных типов с настраиваемой обратной связью и оцениванием. Этот формат особенно полезен для:

- Создания полноценных тестов с разнообразными типами вопросов
- Организации комплексного оценивания знаний
- Предоставления детальной обратной связи по результатам
- Оценки разных уровней понимания материала
- Проведения формативного и суммативного оценивания

Quiz (Question Set) отличается от отдельных типов вопросов H5P тем, что позволяет комбинировать различные форматы заданий в едином тесте с общим итоговым результатом и настройками поведения.

## Установка H5P в Moodle

Прежде чем создавать активности Quiz (Question Set), необходимо установить H5P в вашей системе Moodle:

1. Войдите в Moodle как администратор
2. Перейдите в раздел "Администрирование сайта" > "Плагины" > "Установка плагинов"
3. Нажмите кнопку "Установить плагины из каталога плагинов Moodle"
4. Найдите "H5P" в списке плагинов и установите его
5. Следуйте инструкциям по установке
6. После завершения установки активируйте плагин

## Создание активности Quiz (Question Set)

### Шаг 1: Добавление активности H5P в курс

1. Перейдите на страницу вашего курса в Moodle
2. Включите режим редактирования, нажав кнопку "Режим редактирования" в правом верхнем углу
3. В нужном разделе курса нажмите "Добавить элемент или ресурс"
4. В открывшемся окне выберите "H5P интерактивный контент" и нажмите "Добавить"

### Шаг 2: Настройка основных параметров

1. Введите название для вашей активности в поле "Название"
2. При необходимости добавьте описание в поле "Описание"
3. В разделе "Настройки H5P" нажмите кнопку "Создать" или "Загрузить контент"
4. Из списка доступных типов контента выберите "Question Set"

### Шаг 3: Создание вопросов

1. В полях "Заголовок" и "Вводный текст" введите название и описание теста
2. Нажмите кнопку "Добавить вопрос" для создания первого вопроса
3. Выберите тип вопроса из выпадающего списка:

#### Доступные типы вопросов:

- **Multiple Choice** (Множественный выбор): один или несколько правильных ответов из списка
- **True/False Question** (Верно/Неверно): простой выбор между двумя вариантами
- **Fill in the Blanks** (Заполнение пропусков): ввод слов в пропуски в тексте
- **Drag the Words** (Перетаскивание слов): перемещение слов в правильные позиции
- **Mark the Words** (Отметьте слова): выделение определенных слов в тексте
- **Drag and Drop** (Перетаскивание объектов): размещение объектов в определенных зонах
- **Image Hotspots** (Интерактивные точки на изображении): выбор областей на изображении
- **Image Sequencing** (Последовательность изображений): расположение изображений в правильном порядке
- **Find the Hotspot** (Найдите точку): поиск определенных областей на изображении
- **Image Pairing** (Сопоставление изображений): сопоставление пар изображений
- **Dictation** (Диктант): ввод прослушанного текста
- **Essay** (Эссе): написание развернутого ответа с ручной проверкой

4. Настройте выбранный тип вопроса, заполнив соответствующие поля
5. Повторите процесс добавления для всех нужных вопросов

### Шаг 4: Настройка порядка вопросов

1. Используйте стрелки вверх/вниз для изменения порядка вопросов
2. При необходимости активируйте опцию "Рандомизировать вопросы", чтобы они отображались в случайном порядке

## Подробные настройки Quiz (Question Set)

### Настройки поведения

- **Показать кнопку "Повторить"**: позволяет учащимся перезапустить тест
- **Показать кнопку "Показать решение"**: дает возможность увидеть правильные ответы
- **Требовать ответа на все вопросы**: нужно ответить на все вопросы перед завершением
- **Переходить сразу к следующему вопросу**: автоматический переход после ответа
- **Отключить обратное перемещение**: запрет возврата к предыдущим вопросам
- **Рандомизировать вопросы**: отображение вопросов в случайном порядке
- **Сбросить баллы при повторении**: обнуление результатов при повторной попытке

### Настройки интерфейса

- **Фоновое изображение вопроса**: добавление изображения фона для каждого вопроса
- **Показать индикатор прогресса**: отображение шкалы прохождения теста
- **Показать очки**: отображение набранных баллов
- **Заголовок результата**: настройка текста для экрана результатов
- **Визуализация результатов**: настройка отображения успешности выполнения

### Настройки оценивания

- **Проходной балл**: минимальный балл для успешного прохождения теста
- **Вес вопроса**: указание разной значимости вопросов в общей оценке
- **Штрафы**: настройка вычитания баллов за неправильные ответы
- **Отзыв на основе результата**: настраиваемые сообщения для разных уровней выполнения
  - "Отлично!" для 90-100%
  - "Хорошая работа!" для 70-89%
  - "Попробуйте еще раз" для 0-69%

### Шаг 5: Сохранение и публикация

1. После завершения всех настроек нажмите "Сохранить и показать"
2. Проверьте, как работает ваш тест с точки зрения студента
3. При необходимости вернитесь к редактированию и внесите изменения

## Примеры упражнений по авиационному английскому

### Пример 1: Тест на знание авиационной терминологии

```
Вопрос 1 (Multiple Choice):
Вопрос: Which of the following is NOT a part of an aircraft?
Варианты ответов:
- Fuselage [неверно]
- Aileron [неверно]
- Propeller [неверно]
- Rudder [неверно]
- Carburettor [правильно, часть двигателя, но не самолета в целом]

Вопрос 2 (Fill in the Blanks):
Вопрос: Complete the sentences with the correct aviation terms.
Текст: The *altitude* is measured in feet above sea level, while *heading* indicates the direction of flight in degrees.

Вопрос 3 (Drag and Drop):
Вопрос: Place each instrument in its correct position on the cockpit panel.
[Изображение панели приборов с областями для перетаскивания элементов]

Вопрос 4 (True/False):
Вопрос: ATC stands for "Air Traffic Communication".
Ответ: False (правильно: Air Traffic Control)

Вопрос 5 (Multiple Choice):
Вопрос: What does the acronym METAR refer to?
Варианты ответов:
- Meteorological Terminal Air Report [правильно]
- Measurement of Terminal Approach Radar [неверно]
- Method of Evaluating Terminal Area Routes [неверно]
- Maximum Effective Terminal Approach Rate [неверно]
```

### Пример 2: Проверка знания радиосвязи

```
Вопрос 1 (Multiple Choice):
Вопрос: What is the correct way to state the time 3:45 PM in aviation radio communication?
Варианты ответов:
- Fifteen forty-five [неверно]
- Three forty-five PM [неверно]
- Fifteen hundred forty-five [правильно]
- Quarter to four [неверно]

Вопрос 2 (Fill in the Blanks):
Вопрос: Complete the standard radio transmission.
Текст: "Tower, G-ABCD, *request* taxi, information *Charlie* received, at terminal 2."

Вопрос 3 (Drag the Words):
Вопрос: Arrange the words to form a correct clearance transmission.
Текст: *Cleared* to *land* runway *two seven*, wind *zero nine zero* degrees at *five* knots.

Вопрос 4 (Mark the Words):
Вопрос: Mark the non-standard phraseology that should be avoided in professional radio communication.
Текст: Roger that | Wilco | Take care | Good day | See you later | Hope to see you soon | Standing by | Over and out

Вопрос 5 (Multiple Choice):
Вопрос: What is the correct response to "Squawk 7421"?
Варианты ответов:
- "Roger, squawking 7421" [правильно]
- "OK, 7421" [неверно]
- "7421, understood" [неверно]
- "Setting transponder to 7421 now" [неверно]
```

### Пример 3: Тест на знание аварийных процедур

```
Вопрос 1 (Multiple Choice):
Вопрос: Which transponder code should be set in case of radio communication failure?
Варианты ответов:
- 7500 [неверно]
- 7600 [правильно]
- 7700 [неверно]
- 7000 [неверно]

Вопрос 2 (Image Hotspots):
Вопрос: Identify areas on the aircraft that would be checked during a pre-flight inspection for possible damage.
[Изображение самолета с интерактивными точками]

Вопрос 3 (Fill in the Blanks):
Вопрос: Complete the MAYDAY call.
Текст: "*MAYDAY*, *MAYDAY*, *MAYDAY*, This is *callsign* [G-ABCD], *position* [10 miles south of airport], *nature of emergency* [engine failure], *intentions* [forced landing], *persons on board* [number], *endurance* [time]."

Вопрос 4 (Drag and Drop):
Вопрос: Order the emergency actions in case of cabin depressurization.
Элементы: 
- Put on oxygen mask
- Secure own mask before helping others
- Check that the mask is providing oxygen
- Secure loose items
- Prepare for emergency descent
- Review emergency landing procedures

Вопрос 5 (True/False):
Вопрос: In case of fire in the cabin, you should open the windows to let the smoke out.
Ответ: False (нельзя открывать окна во время полета)
```

### Пример 4: Тест на знание правил воздушного движения

```
Вопрос 1 (Multiple Choice):
Вопрос: Which aircraft has the right of way?
Варианты ответов:
- Aircraft on final approach [правильно]
- Aircraft at higher altitude [неверно]
- Faster aircraft [неверно]
- Larger aircraft [неверно]

Вопрос 2 (Image Sequencing):
Вопрос: Arrange the phases of flight in the correct order.
Изображения: 
- Pre-flight check
- Taxi
- Take-off
- Climb
- Cruise
- Descent
- Approach
- Landing
- Taxi to gate

Вопрос 3 (Fill in the Blanks):
Вопрос: Complete the aviation regulation text.
Текст: VFR flights require minimum *visibility* of 5 km and a cloud ceiling of at least *1000* feet above ground level.

Вопрос 4 (Multiple Choice):
Вопрос: What does QNH refer to?
Варианты ответов:
- Altimeter setting to show elevation above mean sea level [правильно]
- Direction of runway in use [неверно]
- Wind speed at ground level [неверно]
- Runway visual range [неверно]

Вопрос 5 (Drag and Drop):
Вопрос: Match each airspace class with its description.
Элементы для сопоставления:
- Class A: Controlled, only IFR flights
- Class B: Controlled, IFR and VFR flights, clearance required
- Class C: Controlled, IFR and VFR flights, partial clearance
- Class D: Controlled, tower service
- Class E: Controlled, no clearance for VFR
- Class G: Uncontrolled airspace
```

### Пример 5: Тест на знание авиационных карт и навигации

```
Вопрос 1 (Image Hotspots):
Вопрос: Identify the following elements on the aeronautical chart.
[Изображение аэронавигационной карты с интерактивными точками: аэропорт, воздушный коридор, опасная зона, навигационное средство, возвышенность]

Вопрос 2 (Multiple Choice):
Вопрос: What does a blue circle with "R" inside indicate on an aeronautical chart?
Варианты ответов:
- Restricted area [правильно]
- Radar coverage [неверно]
- Radio mandatory zone [неверно]
- Recreational flight zone [неверно]

Вопрос 3 (Fill in the Blanks):
Вопрос: Complete the navigation calculations.
Текст: If an aircraft flies at *groundspeed* of 240 knots, it will cover a distance of 400 nautical miles in *100* minutes.

Вопрос 4 (Drag and Drop):
Вопрос: Match each navigation system with its purpose.
Элементы для сопоставления:
- VOR: Direction finding using radio signals
- DME: Distance measuring equipment
- ILS: Precision approach guidance
- NDB: Non-directional radio beacon
- GPS: Global positioning system
- RNAV: Area navigation

Вопрос 5 (True/False):
Вопрос: Magnetic variation is the difference between true north and magnetic north.
Ответ: True
```

## Советы и лучшие практики

1. **Разнообразие типов вопросов**: Используйте различные типы вопросов для оценки разных аспектов знаний и навыков.

2. **Прогрессивная сложность**: Организуйте вопросы от простых к сложным для постепенного вовлечения учащихся.

3. **Четкие инструкции**: Предоставляйте ясные указания для каждого типа вопроса, особенно если они смешаны в одном тесте.

4. **Содержательная обратная связь**: Включайте объяснения как для правильных, так и для неправильных ответов, превращая тест в обучающий инструмент.

5. **Баланс сложности**: Обеспечьте баланс между легкими, средними и сложными вопросами для объективной оценки знаний.

6. **Техническая точность**: Особенно в авиационной сфере, убедитесь в точности всей терминологии и процедур, описанных в вопросах.

7. **Визуальные элементы**: Включайте изображения, диаграммы и схемы, где это уместно, особенно для технических тем.

8. **Разумное количество вопросов**: Оптимально включать 10-15 вопросов в один тест для поддержания концентрации учащихся.

9. **Настройка времени**: Если необходимо, устанавливайте ограничение времени на выполнение теста, но оно должно быть реалистичным.

10. **Предварительное тестирование**: Обязательно проверьте работу всех вопросов и общего поведения теста перед его публикацией.

11. **Гибкие настройки**: Настраивайте параметры теста в зависимости от его цели (обучение, практика, оценивание).

12. **Анализ результатов**: Используйте данные о результатах для выявления проблемных областей и совершенствования учебных материалов.

---

H5P Quiz (Question Set) — это мощный инструмент для создания комплексных тестов с различными типами вопросов. Благодаря гибким настройкам и разнообразным форматам вопросов, вы можете эффективно оценивать знания учащихся на различных уровнях. Следуя этому руководству, вы сможете создавать профессиональные тесты для проверки знаний авиационного английского или любой другой специализированной темы.
