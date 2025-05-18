# H5P Mark the Words в Moodle: Подробное руководство

## Содержание
- [Введение в H5P](#введение-в-h5p)
- [Что такое Mark the Words](#что-такое-mark-the-words)
- [Установка H5P в Moodle](#установка-h5p-в-moodle)
- [Создание активности Mark the Words](#создание-активности-mark-the-words)
- [Подробные настройки Mark the Words](#подробные-настройки-mark-the-words)
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

## Что такое Mark the Words

Mark the Words (Выделение слов) — это интерактивная активность в H5P, которая позволяет создавать упражнения, где учащиеся должны выделить определенные слова или фразы в тексте согласно заданным критериям. Активность развивает навыки внимательного чтения, распознавания и идентификации конкретных элементов в тексте.

Этот формат особенно полезен для:
- Идентификации ключевых терминов и понятий в профессиональном тексте
- Выделения грамматических структур или частей речи
- Распознавания ошибок или нестандартных формулировок
- Проверки понимания специфической терминологии
- Тренировки навыка быстрого сканирования текста для поиска важной информации

В контексте авиационного английского Mark the Words является эффективным инструментом для работы со стандартной фразеологией, выделения ключевых команд в расшифровках радиообмена, идентификации терминов в технических документах, распознавания правильных и неправильных формулировок в процедурах, а также для изучения и закрепления профессиональной лексики в контексте.

## Установка H5P в Moodle

Прежде чем создавать активности Mark the Words, необходимо установить H5P в вашей системе Moodle:

1. Войдите в Moodle как администратор
2. Перейдите в раздел "Администрирование сайта" > "Плагины" > "Установка плагинов"
3. Нажмите кнопку "Установить плагины из каталога плагинов Moodle"
4. Найдите "H5P" в списке плагинов и установите его
5. Следуйте инструкциям по установке
6. После завершения установки активируйте плагин

## Создание активности Mark the Words

### Шаг 1: Добавление активности H5P в курс

1. Перейдите на страницу вашего курса в Moodle
2. Включите режим редактирования, нажав кнопку "Режим редактирования" в правом верхнем углу
3. В нужном разделе курса нажмите "Добавить элемент или ресурс"
4. В открывшемся окне выберите "H5P интерактивный контент" и нажмите "Добавить"

### Шаг 2: Настройка основных параметров

1. Введите название для вашей активности в поле "Название"
2. При необходимости добавьте описание в поле "Описание"
3. В разделе "Настройки H5P" нажмите кнопку "Создать" или "Загрузить контент"
4. Из списка доступных типов контента выберите "Mark the Words"

### Шаг 3: Создание текста с маркируемыми словами

1. В поле "Заголовок задания" введите название вашего упражнения
   - Название должно четко указывать, что нужно искать в тексте
   - Например: "Выделите все команды диспетчера в этом радиообмене"

2. В поле "Текст задания" добавьте инструкции для учащихся:
   - Объясните, какие слова или фразы нужно выделять
   - Уточните, должны ли учащиеся выделять целые фразы или только отдельные слова
   - Укажите, какими критериями руководствоваться при выборе слов

3. В поле текста введите основной текст задания:
   - Включите слова, которые должны быть выделены, в специальные маркеры: *слово*
   - Например: "The pilot reported *low fuel* and requested *priority landing*"
   - Все слова или фразы между звездочками будут считаться правильными ответами

4. Проверьте, что все целевые слова правильно отмечены:
   - Убедитесь, что звездочки стоят только вокруг слов, которые должны быть выделены
   - Если нужно показать звездочку как часть текста (не как маркер), используйте обратный слэш: \*
   - Проверьте, что нет пробелов между звездочками и словами: " *слово* " (неправильно), "*слово*" (правильно)

### Шаг 4: Настройка обратной связи и оценивания

1. Настройте обратную связь:
   - Добавьте текст, который будет показан при правильном выполнении задания
   - Напишите сообщение для случаев, когда есть ошибки
   - При желании включите подсказки

2. Настройте параметры оценивания:
   - Выберите, будут ли вычитаться баллы за неправильно выделенные слова
   - Определите, сколько попыток дается учащемуся
   - Настройте проходной балл (если необходимо)

### Шаг 5: Дополнительные настройки поведения

1. Настройте поведение задания:
   - Выберите, будут ли слова автоматически проверяться после выделения
   - Определите, сразу ли показывать, правильно ли выделено слово
   - Настройте возможность повторных попыток

2. Настройте интерфейс:
   - Выберите цвета для правильно и неправильно выделенных слов
   - Настройте текст кнопок ("Проверить", "Повторить" и т.д.)
   - Определите, показывать ли решение

### Шаг 6: Сохранение и публикация

1. После завершения всех настроек нажмите "Сохранить и показать"
2. Проверьте, как работает ваша активность с точки зрения студента
3. При необходимости вернитесь к редактированию и внесите изменения

## Подробные настройки Mark the Words

### Настройки текста и содержания

- **Форматирование текста**: настройка размера шрифта, стиля и выравнивания
- **Разделение на параграфы**: структурирование текста для лучшей читаемости
- **Включение элементов HTML**: добавление базовой HTML-разметки для форматирования
- **Плотность маркируемых слов**: обеспечение оптимального количества слов для выделения
- **Контекстуальное окружение**: создание достаточного контекста вокруг выделяемых слов

### Настройки выделения

- **Поведение выделения**: настройка способа выделения (клик, двойной клик, перетаскивание)
- **Визуальное оформление**: настройка цветов и стилей выделения
- **Чувствительность к регистру**: настройка учета регистра при проверке ответов
- **Целые слова vs. части слов**: определение, нужно ли выделять только целые слова
- **Выделение фраз**: настройка правил для выделения нескольких слов подряд

### Настройки обратной связи

- **Немедленная обратная связь**: настройка мгновенного отображения результатов
- **Итоговая обратная связь**: настройка сообщения после завершения задания
- **Индикация правильности**: настройка способа отображения правильных/неправильных ответов
- **Уровни обратной связи**: настройка различных сообщений в зависимости от результата
- **Пояснения**: добавление объяснений, почему конкретные слова должны быть выделены

### Настройки оценивания

- **Схема начисления баллов**: настройка баллов за правильные выделения
- **Штрафные баллы**: настройка вычитания баллов за неправильные выделения
- **Минимальный проходной балл**: установка порога для успешного прохождения
- **Показ результатов**: настройка отображения баллов и процента правильных ответов
- **Режим практики vs. оценивания**: настройка режима использования активности

## Примеры использования для авиационного английского

### Пример 1: Выделение команд диспетчера в транскрипции радиообмена

```
Заголовок: Identify ATC Instructions in Radio Communication
Инструкция: "Read the following ATC-pilot communication transcript and mark all direct instructions given by the controller."

Текст:
ATC: "Speedbird 276, *descend to flight level 280*, traffic at your 2 o'clock, same level."
Pilot: "Descending to flight level 280, Speedbird 276."
ATC: "Speedbird 276, *reduce speed to 250 knots*, *contact London Control on 126.82*."
Pilot: "Speed 250 knots, contact London 126.82, Speedbird 276."
ATC: "KLM 1507, caution wake turbulence from heavy Boeing 777 departing, *line up and wait runway 27R*."
Pilot: "Line up and wait 27R, KLM 1507."
ATC: "Lufthansa 392, traffic is a light aircraft at your 10 o'clock, 5 miles, altitude unknown. Do you have visual?"
Pilot: "Negative contact, Lufthansa 392."
ATC: "Roger, *turn right heading 050 degrees* for spacing from that traffic, Lufthansa 392."
Pilot: "Right heading 050 degrees, Lufthansa 392."

Обратная связь при правильном выполнении:
"Excellent! You've correctly identified all controller instructions. Being able to quickly recognize direct instructions is critical for accurate readbacks and safe operations."

Обратная связь при ошибках:
"Review the transcript again. Remember to focus specifically on direct instructions (commands) given by the controller, not information, questions, or acknowledgments."
```

### Пример 2: Идентификация авиационной терминологии в техническом тексте

```
Заголовок: Identify Aviation Weather Terminology
Инструкция: "Read the following METAR and TAF reports and mark all specific weather phenomena mentioned."

Текст:
METAR EGLL 121550Z 25015G25KT 220V290 3000 *RA* *BR* BKN006 OVC010 12/11 Q1002 TEMPO 2000 *+RA*

TAF KJFK 121720Z 1218/1324 15012KT P6SM BKN035 TEMPO 1218/1220 6SM *BR* BKN025 FM122000 15015G25KT P6SM BKN035 TEMPO 1222/1302 4SM *-RA* BKN020 PROB30 1222/1300 2SM *TSRA* OVC015CB FM130200 20012KT P6SM SCT035 BECMG 1306/1308 23010KT SCT045

The importance of understanding weather terminology cannot be overstated. Phenomena such as *fog*, *thunderstorms*, and *freezing rain* directly impact flight safety. Conditions like *wind shear* and *microbursts* pose significant risks during take-off and landing phases, while high-altitude hazards such as *clear air turbulence* and *icing* can affect cruising flight. Both *visibility* restrictions and *ceiling* limitations determine applicable minimums and whether an approach can be conducted.

Обратная связь при правильном выполнении:
"Great job! You have successfully identified all specific weather phenomena mentioned in these reports. Recognizing these terms quickly is essential for operational weather assessment."

Обратная связь при ошибках:
"Take another look. Focus specifically on actual weather phenomena (like rain, fog, turbulence) rather than general descriptors or measurements."
```

### Пример 3: Определение ошибок в стандартной фразеологии

```
Заголовок: Identify Non-Standard Phraseology
Инструкция: "Read the following pilot-ATC communications and mark all instances of non-standard phraseology that should be corrected."

Текст:
ATC: "Airbus 320, cleared for takeoff, runway 27L."
Pilot: "*Roger, taking off* from 27L, Airbus 320." [Should be: "Cleared for takeoff, runway 27L, Airbus 320"]

ATC: "Delta 472, descend to flight level 270."
Pilot: "Descending to flight level 270, Delta 472."

ATC: "United 857, turn left heading 180, descend to 3000 feet, QNH 1013."
Pilot: "*Wilco*, turning left heading 180, *down to* 3000 feet, QNH 1013, United 857." [Should be: "Left heading 180, descending to 3000 feet, QNH 1013, United 857"]

ATC: "Golf Alpha Bravo, cleared to land runway 23, wind 240 degrees 12 knots."
Pilot: "*Got it*, landing runway 23, Golf Alpha Bravo." [Should be: "Cleared to land runway 23, Golf Alpha Bravo"]

ATC: "Speedbird 744 heavy, caution wake turbulence, Boeing 747 departing, line up and wait runway 27R."
Pilot: "*Will do*, lining up runway 27R, Speedbird 744 heavy." [Should be: "Lining up and waiting runway 27R, Speedbird 744 heavy"]

Обратная связь при правильном выполнении:
"Excellent! You've correctly identified all instances of non-standard phraseology. Using standard phraseology ensures clear and unambiguous communication, reducing the risk of misunderstandings."

Обратная связь при ошибках:
"Review the communications again. Look for colloquial expressions, ambiguous terms, and responses that don't properly acknowledge the instruction content."
```

### Пример 4: Идентификация компонентов самолета в техническом описании

```
Заголовок: Identify Aircraft Primary Flight Controls
Инструкция: "Read the following text about aircraft control systems and mark all primary flight controls mentioned."

Текст:
Aircraft control systems allow pilots to direct the aircraft in flight. The most essential controls are the primary flight controls, which directly affect the aircraft's attitude and flight path. The *ailerons*, mounted on the trailing edge of each wing, control roll by moving in opposite directions to create differential lift. The *elevator*, typically located on the horizontal stabilizer, controls pitch by altering the downforce produced by the tail. The *rudder*, attached to the vertical stabilizer, controls yaw by deflecting the airflow, allowing the aircraft to turn left or right while maintaining coordination.

In larger aircraft, secondary controls include flaps, slats, spoilers, and trim systems. Flaps and slats increase lift during low-speed operations like takeoff and landing. Spoilers disrupt airflow over the wing, reducing lift and increasing drag. Trim tabs help reduce control forces during sustained flight conditions.

Fly-by-wire systems have largely replaced direct mechanical connections in modern aircraft. In these systems, computers interpret pilot inputs and move the *ailerons*, *elevators*, and *rudder* via electrical signals to hydraulic actuators. This technology allows for envelope protection and improved handling characteristics. Nevertheless, the fundamental purpose of the primary flight controls remains unchanged: the *ailerons* control roll, the *elevator* controls pitch, and the *rudder* controls yaw.

Обратная связь при правильном выполнении:
"Well done! You've correctly identified all primary flight controls (ailerons, elevator, rudder). Understanding these components is essential for communications about aircraft handling and potential technical issues."

Обратная связь при ошибках:
"Take another look. Primary flight controls are those that directly control the aircraft's rotation around its three axes. Don't confuse them with secondary controls like flaps, slats, and spoilers."
```

### Пример 5: Выделение ключевых фраз в инструкциях по безопасности

```
Заголовок: Identify Key Safety Phrases in Emergency Procedures
Инструкция: "Read the following emergency evacuation procedure and mark all critical action phrases."

Текст:
EMERGENCY EVACUATION PROCEDURE

In the event of an emergency evacuation, cabin crew must assess the conditions before opening any exit. Upon hearing the evacuation command or signal, crew members should:

1. *Secure your own safety equipment* before assisting others.
2. *Move quickly to your assigned exit* and check outside conditions.
3. If the exit is unusable, *clearly announce "Exit blocked, use alternative exits"*.
4. When opening the exit, *adopt the proper brace position* to prevent injury.
5. After opening, *command passengers to leave all belongings behind*.
6. *Direct passengers to jump onto the slide* with arms folded across chest.
7. *Continuously shout "Jump! Jump! Jump!"* to maintain evacuation momentum.
8. If fire or smoke is present, *instruct passengers to stay low* and cover mouth and nose.
9. When possible, *assist special needs passengers* after the main flow has begun.
10. After all passengers have evacuated, *conduct a final cabin check* before exiting yourself.
11. Once outside, *direct passengers upwind from the aircraft* to a safe assembly area.
12. *Report to the senior crew member* at the assembly point.

Remember that a successful evacuation must be completed within 90 seconds with half the exits blocked. Clear communication and decisive action are essential.

Обратная связь при правильном выполнении:
"Excellent! You've correctly identified all critical action phrases in the emergency evacuation procedure. These are the specific instructions that must be followed precisely during an emergency."

Обратная связь при ошибках:
"Review the procedure again. Focus on the specific action instructions rather than explanatory or contextual information."
```

## Советы и лучшие практики

1. **Ясные инструкции**: Предоставляйте четкие и однозначные инструкции о том, какие именно слова или фразы следует выделять, чтобы избежать путаницы и разочарования учащихся.

2. **Оптимальное количество маркируемых слов**: Следите за балансом между словами для выделения и общим объемом текста. Рекомендуемое соотношение — 15-25% текста для выделения, чтобы задание было достаточно сложным, но не фрустрирующим.

3. **Релевантный контекст**: Используйте аутентичные авиационные тексты или реалистичные симуляции коммуникаций, которые отражают реальные профессиональные ситуации и терминологию.

4. **Градация сложности**: Создавайте задания разного уровня сложности, начиная с очевидных, ярко выраженных элементов для выделения и постепенно переходя к более тонким различиям и нюансам.

5. **Информативная обратная связь**: Предоставляйте содержательную обратную связь, объясняющую, почему определенные слова должны быть выделены и какое значение они имеют в авиационном контексте.

6. **Тематическая фокусировка**: Концентрируйте каждое задание на конкретном аспекте авиационного английского (например, погодные явления, команды управления, технические термины) для более эффективного обучения.

7. **Предварительная подготовка**: Убедитесь, что учащиеся знакомы с терминологией или концепциями до выполнения упражнения Mark the Words, чтобы активность служила закреплению, а не первичному ознакомлению.

8. **Визуальная ясность**: Форматируйте текст так, чтобы он был легко читаемым, с достаточным межстрочным интервалом и четким шрифтом, что особенно важно при работе на мобильных устройствах.

9. **Проверка функциональности**: Тестируйте активность сами перед предоставлением студентам, проверяя, что все маркеры правильно установлены и система корректно идентифицирует выделения.

10. **Связь с реальной практикой**: Объясняйте учащимся, как навык быстрого распознавания ключевых элементов в тексте непосредственно применяется в реальных авиационных сценариях.

11. **Комбинирование с другими активностями**: Используйте Mark the Words как часть комплексного подхода к изучению темы, дополняя его другими типами активностей H5P для разностороннего развития навыков.

12. **Постепенное усложнение**: Развивайте серию взаимосвязанных упражнений, которые постепенно повышают сложность идентификации, переходя от однозначных терминов к более контекстуально зависимым элементам.

---

H5P Mark the Words является мощным инструментом для преподавания авиационного английского, позволяя учащимся развивать навыки внимательного чтения и быстрой идентификации ключевых элементов в профессиональных текстах. Эта активность особенно эффективна для работы со специализированной терминологией, стандартной фразеологией и командами, важными для безопасной коммуникации в авиационной среде.

Процесс выделения слов в контексте помогает учащимся интернализировать профессиональную лексику, развивать навык мгновенного распознавания критически важной информации в текстах и коммуникациях, а также лучше понимать структуру и особенности авиационного дискурса. Кроме того, данный формат активности способствует развитию аналитического мышления и внимания к деталям — качеств, крайне важных для авиационных специалистов.

Следуя рекомендациям, представленным в этом руководстве, вы сможете создавать эффективные, содержательные и педагогически обоснованные упражнения Mark the Words, которые будут способствовать повышению языковой компетентности ваших учащихся в сфере авиационного английского языка.
