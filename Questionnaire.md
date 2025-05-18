# H5P Questionnaire в Moodle: Подробное руководство

## Содержание
- [Введение в H5P](#введение-в-h5p)
- [Что такое Questionnaire](#что-такое-questionnaire)
- [Установка H5P в Moodle](#установка-h5p-в-moodle)
- [Создание активности Questionnaire](#создание-активности-questionnaire)
- [Подробные настройки Questionnaire](#подробные-настройки-questionnaire)
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

## Что такое Questionnaire

Questionnaire (Анкета) — это интерактивная активность в H5P, которая позволяет создавать структурированные опросы с различными типами вопросов для сбора мнений, отзывов или оценки знаний учащихся. В отличие от традиционных тестов, Questionnaire часто используется не для оценивания правильности ответов, а для сбора разнообразной информации от пользователей и стимулирования рефлексии.

Этот формат особенно полезен для:
- Сбора обратной связи о курсе или учебных материалах
- Оценки начального уровня знаний и опыта учащихся
- Стимулирования рефлексии и самоанализа учащихся
- Сбора профессиональных мнений по конкретным кейсам или ситуациям
- Проведения предварительного и последующего опроса для оценки эффективности обучения

В контексте авиационного английского Questionnaire может служить эффективным инструментом для оценки опыта работы с различными аспектами авиации, сбора мнений о сложных профессиональных ситуациях, выявления областей, требующих дополнительного внимания, и помощи учащимся в осознании своих сильных и слабых сторон в контексте профессиональной коммуникации.

## Установка H5P в Moodle

Прежде чем создавать активности Questionnaire, необходимо установить H5P в вашей системе Moodle:

1. Войдите в Moodle как администратор
2. Перейдите в раздел "Администрирование сайта" > "Плагины" > "Установка плагинов"
3. Нажмите кнопку "Установить плагины из каталога плагинов Moodle"
4. Найдите "H5P" в списке плагинов и установите его
5. Следуйте инструкциям по установке
6. После завершения установки активируйте плагин

## Создание активности Questionnaire

### Шаг 1: Добавление активности H5P в курс

1. Перейдите на страницу вашего курса в Moodle
2. Включите режим редактирования, нажав кнопку "Режим редактирования" в правом верхнем углу
3. В нужном разделе курса нажмите "Добавить элемент или ресурс"
4. В открывшемся окне выберите "H5P интерактивный контент" и нажмите "Добавить"

### Шаг 2: Настройка основных параметров

1. Введите название для вашей активности в поле "Название"
2. При необходимости добавьте описание в поле "Описание"
3. В разделе "Настройки H5P" нажмите кнопку "Создать" или "Загрузить контент"
4. Из списка доступных типов контента выберите "Questionnaire"

### Шаг 3: Настройка общих параметров анкеты

1. В поле "Заголовок" введите название вашей анкеты
   - Название должно быть информативным и отражать цель опроса
   - Например: "Оценка опыта работы с радиообменом на английском языке"

2. Добавьте вводный текст в поле "Введение"
   - Объясните цель анкеты и как будут использоваться результаты
   - Укажите приблизительное время заполнения
   - Дайте любые необходимые инструкции или контекст

3. Настройте параметры прогресса и навигации:
   - Включите/отключите индикатор прогресса
   - Настройте кнопки перехода между страницами
   - Определите, можно ли пропускать вопросы или все они обязательны

### Шаг 4: Добавление вопросов различных типов

1. Нажмите "Добавить вопрос" и выберите тип вопроса:
   - **Текстовый ввод** (короткий или длинный): для сбора свободных ответов
   - **Likert шкала**: для оценки степени согласия с утверждениями
   - **Множественный выбор**: для выбора одного или нескольких вариантов из списка
   - **Открытый вопрос**: для развернутых ответов на открытые вопросы

2. Для каждого вопроса:
   - Введите четкую формулировку вопроса
   - Определите, является ли вопрос обязательным
   - Настройте специфические параметры для конкретного типа вопроса (варианты ответов, шкалы и т.д.)
   - При необходимости добавьте пояснения или инструкции

3. Организуйте вопросы по страницам:
   - Группируйте связанные вопросы на одной странице
   - Не перегружайте одну страницу слишком большим количеством вопросов
   - Используйте логический порядок следования вопросов

### Шаг 5: Настройка условной логики (если необходимо)

1. Создайте условные переходы между вопросами:
   - Определите, какие вопросы будут показаны в зависимости от ответов на предыдущие вопросы
   - Настройте ветвление для создания персонализированного пути прохождения анкеты

2. Настройте зависимости между вопросами:
   - Определите, какие вопросы становятся доступными в зависимости от ответов на другие вопросы
   - Создайте динамические цепочки вопросов, адаптирующиеся к ответам пользователя

### Шаг 6: Настройка завершения и отправки результатов

1. Настройте экран завершения:
   - Добавьте сообщение благодарности
   - Предоставьте информацию о дальнейших шагах
   - При необходимости включите возможность просмотра сводки ответов

2. Настройте параметры отправки результатов:
   - Определите, куда будут отправляться результаты
   - Настройте формат данных для анализа
   - Включите/отключите возможность экспорта ответов

## Подробные настройки Questionnaire

### Настройки общего вида

- **Стиль оформления**: настройка цветовой схемы, шрифтов и общего визуального стиля
- **Логотип или изображение**: добавление брендинга или тематического изображения
- **Заголовки и подзаголовки**: настройка оформления различных уровней заголовков
- **Фон страниц**: выбор цвета или изображения для фона
- **Адаптивный дизайн**: настройка отображения на устройствах с различными размерами экрана

### Настройки текстовых вопросов

- **Минимальная/максимальная длина**: ограничение длины текстового ответа
- **Плейсхолдеры**: добавление подсказок внутри поля ввода
- **Проверка формата**: настройка формата ответа (например, только числа или email)
- **Размер поля ввода**: настройка размера текстового поля
- **Правила валидации**: настройка правил проверки введенного текста

### Настройки Likert шкалы

- **Количество пунктов шкалы**: настройка количества делений (обычно от 3 до 7)
- **Метки шкалы**: настройка текстовых меток для крайних и/или промежуточных значений
- **Ориентация шкалы**: выбор между горизонтальной и вертикальной ориентацией
- **Визуальное представление**: настройка внешнего вида шкалы (кнопки, ползунок и т.д.)
- **Группировка утверждений**: объединение нескольких утверждений в одну матрицу

### Настройки множественного выбора

- **Тип выбора**: настройка выбора одного или нескольких вариантов
- **Расположение вариантов**: вертикальное или горизонтальное расположение
- **Случайный порядок**: включение/отключение случайного порядка вариантов
- **Опция "Другое"**: добавление поля для ввода своего варианта
- **Обязательность**: настройка минимального/максимального количества выбираемых вариантов

### Настройки открытых вопросов

- **Рекомендуемая длина ответа**: указание ожидаемого объема ответа
- **Инструменты форматирования**: включение/отключение возможности форматирования текста
- **Возможность прикрепления файлов**: настройка возможности загрузки файлов
- **Временное ограничение**: установка лимита времени на ответ
- **Подсказки и направляющие вопросы**: добавление вспомогательной информации

### Настройки навигации и прогресса

- **Тип навигации**: линейный или свободный порядок прохождения вопросов
- **Кнопки навигации**: настройка текста и внешнего вида кнопок
- **Индикатор прогресса**: настройка типа и расположения индикатора
- **Сохранение прогресса**: настройка автоматического сохранения частично заполненной анкеты
- **Возможность возврата**: настройка возможности изменения уже данных ответов

### Шаг 7: Сохранение и публикация

1. После завершения всех настроек нажмите "Сохранить и показать"
2. Проверьте, как работает ваша анкета с точки зрения пользователя
3. При необходимости вернитесь к редактированию и внесите изменения

## Примеры использования для авиационного английского

### Пример 1: Оценка опыта и уверенности в радиообмене

```
Заголовок: Aviation English Radiotelephony Self-Assessment
Введение: "This questionnaire aims to assess your experience and confidence level with aviation English radiotelephony. Your responses will help tailor the course to your specific needs and track your progress. The information you provide is confidential and will only be used for educational purposes."

Страница 1: Общие сведения и опыт

Вопрос 1 (множественный выбор, один ответ):
"What is your primary role in aviation?"
- Pilot (Commercial)
- Pilot (Private)
- Air Traffic Controller
- Flight Dispatcher
- Aviation Student
- Other (please specify): [текстовое поле]

Вопрос 2 (числовой ввод):
"How many years of experience do you have in this role?"
[Числовое поле] years

Вопрос 3 (множественный выбор, несколько ответов):
"In which of the following environments have you used aviation English? (Select all that apply)"
- Domestic flights/operations only
- International flights/operations
- High-density airspace
- Remote or oceanic airspace
- Emergency situations
- Training and simulation only
- No practical experience yet

Страница 2: Самооценка навыков радиообмена

Вопрос 4 (Likert шкала, 5 пунктов от "Not confident at all" до "Very confident"):
"Please rate your confidence level in the following radiotelephony situations:"
- Standard departure clearances
- Position reporting
- Requesting weather information
- Managing non-routine situations
- Handling emergency communications
- Understanding accented speech
- Speaking clearly under pressure

Вопрос 5 (открытый вопрос):
"Describe a specific situation where you found aviation English communication challenging. What made it difficult, and how did you handle it?"
[Большое текстовое поле]

Страница 3: Приоритеты обучения

Вопрос 6 (ранжирование):
"Please rank the following areas of aviation English communication according to your learning priorities (1 = highest priority):"
- Standard phraseology
- Plain English for non-routine situations
- Pronunciation and accent reduction
- Active listening skills
- Readback techniques
- Managing communication under stress
- Technical vocabulary expansion

Вопрос 7 (открытый вопрос):
"What specific aspects of aviation English radiotelephony would you like to focus on during this course?"
[Текстовое поле]

Завершающий экран:
"Thank you for completing this self-assessment. Your responses will help us customize the course materials to address your specific needs and learning goals. Based on your input, we will suggest personalized practice exercises focusing on your priority areas."
```

### Пример 2: Анализ кейса по управлению коммуникацией в нестандартной ситуации

```
Заголовок: Case Study Analysis: Non-Routine Communication Scenario
Введение: "This questionnaire presents a case study of a non-routine aviation situation requiring effective communication. Please analyze the scenario and provide your professional assessment of the communication challenges and strategies used. There are no right or wrong answers—we are interested in your analysis and reasoning based on your experience and knowledge."

Страница 1: Сценарий и начальный анализ

[Включите описание сценария, например, ситуация с технической проблемой на борту, требующая обмена информацией между экипажем и ATC. Можно добавить аудиозапись фактического или симулированного радиообмена.]

Вопрос 1 (множественный выбор, несколько ответов):
"What were the main communication challenges present in this scenario? (Select all that apply)"
- Time pressure
- Technical complexity
- Unclear information
- Language barriers
- Procedural uncertainty
- Multiple parties involved
- Environmental factors (noise, workload)
- Other (please specify): [текстовое поле]

Вопрос 2 (открытый вопрос):
"How would you evaluate the effectiveness of the communication between the pilot and ATC in this scenario? Identify specific strengths and weaknesses."
[Большое текстовое поле]

Страница 2: Детальный анализ

Вопрос 3 (Likert шкала, 5 пунктов от "Strongly disagree" до "Strongly agree"):
"Please rate your agreement with the following statements about the communication in this scenario:"
- The pilot effectively communicated the nature of the problem
- The ATC understood the severity of the situation
- Clear phraseology was used throughout the exchange
- The communication followed standard protocols where appropriate
- Plain English was used effectively when standard phraseology was insufficient
- The parties confirmed understanding appropriately
- The communication led to effective resolution of the situation

Вопрос 4 (открытый вопрос):
"What specific phrases or communication techniques in this scenario were particularly effective or ineffective? Please provide examples and explain your reasoning."
[Большое текстовое поле]

Страница 3: Применение и рефлексия

Вопрос 5 (текстовый ввод):
"If you were the pilot in this situation, what would you have communicated differently? Please provide specific phrasing you would use."
[Текстовое поле]

Вопрос 6 (открытый вопрос):
"Based on this scenario, what lessons about aviation English communication in non-routine situations can be applied to your own practice?"
[Большое текстовое поле]

Завершающий экран:
"Thank you for your thoughtful analysis of this communication scenario. Your professional insights will be discussed during our next session, where we will compare different approaches and develop best practices for similar situations. Your responses demonstrate how experienced aviation professionals might approach the same communication challenge in different but equally valid ways."
```

### Пример 3: Оценка понимания стандартной фразеологии и процедур

```
Заголовок: Standard Phraseology Comprehension Assessment
Введение: "This questionnaire will assess your understanding of ICAO standard phraseology in various flight scenarios. This is not a test but a diagnostic tool to identify areas where you may benefit from additional practice. Please select the most appropriate phraseology or explain your reasoning for each situation."

Страница 1: Предполетные и взлетные фазы

Вопрос 1 (множественный выбор, один ответ):
"Which phrase would you use to acknowledge that you have received a transmission but will NOT comply with it?"
- "Roger."
- "Wilco."
- "Affirm."
- "Negative."

Вопрос 2 (множественный выбор, один ответ):
"When ready to depart, what is the correct phraseology to request takeoff clearance?"
- "Ready for departure."
- "Ready for takeoff."
- "Request takeoff."
- "Request departure now."

Вопрос 3 (открытый вопрос):
"A controller instructs you: 'Fastair 345, winds 270 degrees at 10 knots, runway 23, cleared for takeoff.' Write your exact readback response."
[Текстовое поле]

Страница 2: Полетная фаза и навигация

Вопрос 4 (множественный выбор, один ответ):
"You need to inform ATC that you cannot maintain the assigned altitude due to turbulence. Which is the most appropriate phraseology?"
- "Unable assigned altitude due turbulence."
- "Unable to maintain assigned altitude due to turbulence."
- "Requesting different altitude, turbulence."
- "Turbulence too strong for this altitude."

Вопрос 5 (множественный выбор, несколько ответов):
"Which of the following phrases use correct standard phraseology? (Select all that apply)"
- "Descend to FL130."
- "Climb to altitude 10,000 feet."
- "Proceed direct to ECHO DELTA FOXTROT."
- "Turn left heading two five zero."
- "Increase your speed to two hundred knots."

Вопрос 6 (Likert шкала, от "Not confident" до "Very confident"):
"How confident are you in your ability to correctly use standard phraseology in the following situations?"
- Initial contact with a new ATC unit
- Position reporting
- Weather deviation requests
- Communicating technical problems
- Emergency situations

Страница 3: Применение в сложных ситуациях

Вопрос 7 (открытый вопрос):
"You need to communicate a non-normal situation (smoke in the cabin, no immediate danger) to ATC. Write the exact phraseology you would use for the initial call."
[Текстовое поле]

Вопрос 8 (множественный выбор, один ответ):
"In case of complete radio communication failure, what is the correct transponder code to set?"
- "7500"
- "7600"
- "7700"
- "7000"

Завершающий экран:
"Thank you for completing this assessment. Based on your responses, we have identified specific areas of standard phraseology where additional practice may be beneficial. During the upcoming sessions, we will focus on these areas to enhance your confidence and precision in radiotelephony communications."
```

### Пример 4: Предкурсовое анкетирование для определения потребностей и опыта

```
Заголовок: Aviation English Course Pre-Assessment
Введение: "Welcome to the Aviation English course! This questionnaire will help us understand your background, experience, and specific learning needs. Your responses will help us tailor the course materials to better serve your professional development. Please answer all questions as completely as possible."

Страница 1: Личная информация и опыт

Вопрос 1 (текстовый ввод):
"Please provide your full name:"
[Текстовое поле]

Вопрос 2 (множественный выбор, один ответ):
"What is your current ICAO Language Proficiency level?"
- Level 3 (Operational)
- Level 4 (Operational)
- Level 5 (Extended)
- Level 6 (Expert)
- Not yet assessed
- I don't know

Вопрос 3 (множественный выбор, несколько ответов):
"What types of aircraft have you operated/controlled/worked with? (Select all that apply)"
- Narrow-body commercial jets
- Wide-body commercial jets
- Regional jets
- Turboprops
- General aviation piston aircraft
- Helicopters
- Military aircraft
- Other (please specify): [текстовое поле]

Вопрос 4 (множественный выбор, один ответ):
"How frequently do you use English in aviation contexts?"
- Daily
- Several times a week
- Several times a month
- Rarely
- Never, but I expect to in the future

Страница 2: Самооценка навыков и трудностей

Вопрос 5 (Likert шкала, от "Very difficult" до "Very easy"):
"How would you rate the difficulty you experience with the following aspects of aviation English?"
- Understanding native English speakers over the radio
- Understanding non-native English speakers over the radio
- Using standard phraseology correctly
- Switching between standard phraseology and plain English
- Communicating during high workload or stress
- Discussing technical issues in English
- Writing technical reports or documentation in English

Вопрос 6 (открытый вопрос):
"Describe a recent situation where you found aviation English communication challenging or stressful. What specific difficulties did you encounter?"
[Большое текстовое поле]

Страница 3: Учебные предпочтения и цели

Вопрос 7 (множественный выбор, несколько ответов):
"Which learning activities do you find most effective for improving your aviation English? (Select all that apply)"
- Listening to authentic ATC communications
- Role-playing scenarios
- Vocabulary drilling and exercises
- Grammar practice
- Discussion of aviation topics
- Reading technical materials
- Watching videos of procedures and operations
- Simulator-based communication practice
- Other (please specify): [текстовое поле]

Вопрос 8 (открытый вопрос):
"What are your specific goals for this aviation English course? What would you like to be able to do better by the end of the course?"
[Большое текстовое поле]

Завершающий экран:
"Thank you for completing this pre-course assessment. Your responses will help us customize the course content to address your specific needs and learning preferences. We look forward to working with you to enhance your aviation English proficiency in ways that directly support your professional goals and challenges."
```

### Пример 5: Рефлексивный опрос по сценарию коммуникации в аварийной ситуации

```
Заголовок: Emergency Communication Scenario Reflection
Введение: "This questionnaire presents an emergency scenario that requires effective communication between all parties involved. After reviewing the scenario, you will be asked to reflect on the communication challenges and strategies that would be most effective. This exercise will help develop your ability to communicate clearly and effectively under pressure."

Страница 1: Сценарий и начальная рефлексия

[Текст сценария: Подробное описание аварийной ситуации, например, отказ двигателя над густонаселенным районом, требующий координации между экипажем, диспетчерами и наземными службами]

Вопрос 1 (множественный выбор, один ответ):
"In this emergency scenario, what should be the first communication priority for the flight crew?"
- Declaring an emergency to ATC
- Communicating the nature of the problem to ATC
- Briefing the cabin crew
- Communicating with company operations
- Making a passenger announcement

Вопрос 2 (открытый вопрос):
"What exact phraseology would you use for the initial communication with ATC in this situation? Write your complete transmission."
[Текстовое поле]

Страница 2: Анализ коммуникационных потребностей

Вопрос 3 (ранжирование):
"Rank the following information items in order of priority for communication to ATC in this scenario (1 = highest priority):"
- Nature of the emergency
- Number of persons on board
- Fuel endurance
- Intended actions
- Assistance required
- Weather conditions at your position
- Aircraft configuration details

Вопрос 4 (Likert шкала, от "Not important" до "Essential"):
"Rate the importance of the following communication strategies in this emergency scenario:"
- Using standard phraseology wherever possible
- Speaking slowly and clearly
- Being concise and avoiding unnecessary information
- Repeating critical information
- Confirming understanding of instructions
- Managing tone of voice and emotional control
- Coordinating communication within the flight deck

Страница 3: Личная рефлексия и применение

Вопрос 5 (открытый вопрос):
"Based on your personal experience or training, what are the most common communication errors or difficulties that can occur during aviation emergencies?"
[Большое текстовое поле]

Вопрос 6 (множественный выбор, несколько ответов):
"Which personal strategies do you use or would you use to maintain effective communication during high-stress situations? (Select all that apply)"
- Practicing breathing techniques to remain calm
- Mentally rehearsing emergency phraseology regularly
- Using a communication checklist or framework
- Deliberately slowing speech rate under pressure
- Focusing on one communication task at a time
- Asking for readbacks to confirm understanding
- Other (please specify): [текстовое поле]

Вопрос 7 (открытый вопрос):
"How would you personally prepare to improve your ability to communicate effectively in emergency situations like the one described?"
[Большое текстовое поле]

Завершающий экран:
"Thank you for your thoughtful reflection on this emergency communication scenario. Effective communication during emergencies is a critical skill that requires both technical knowledge and psychological preparation. Your responses will be used as a starting point for our upcoming session on emergency communications, where we will discuss various approaches and best practices."
```

## Советы и лучшие практики

1. **Четкая цель и структура**: Определите конкретную цель анкеты и разработайте структуру, которая логически ведет к достижению этой цели. Каждый вопрос должен иметь явную связь с общей целью.

2. **Профессиональный контекст**: Формулируйте вопросы в контексте реальных авиационных ситуаций, используя соответствующую терминологию и сценарии, с которыми учащиеся могут столкнуться в профессиональной практике.

3. **Баланс типов вопросов**: Комбинируйте различные типы вопросов (множественный выбор, шкалы, открытые вопросы) для получения как количественных, так и качественных данных и поддержания интереса респондентов.

4. **Ясные формулировки**: Создавайте вопросы, которые невозможно интерпретировать неоднозначно. Избегайте двойных отрицаний, сложных конструкций и профессионального жаргона, если он не является предметом оценки.

5. **Логическая последовательность**: Организуйте вопросы в логической последовательности, начиная с простых и постепенно переходя к более сложным, группируя связанные темы вместе.

6. **Оптимальная длина**: Ограничивайте длину анкеты, чтобы удерживать внимание респондентов. Обычно рекомендуется не более 15-20 вопросов или 10-15 минут на заполнение.

7. **Проверка перед публикацией**: Тестируйте анкету с коллегами или небольшой группой учащихся, чтобы выявить любые проблемы с пониманием вопросов, техническими аспектами или временем заполнения.

8. **Уважение конфиденциальности**: Ясно объясняйте, как будут использоваться собранные данные, и соблюдайте конфиденциальность ответов, особенно когда речь идет о самооценке или личном опыте.

9. **Интеграция с обучением**: Разрабатывайте анкеты как интегральную часть учебного процесса, а не изолированные инструменты. Используйте результаты для адаптации последующего обучения.

10. **Возможность рефлексии**: Включайте вопросы, которые стимулируют рефлексию и самоанализ, помогая учащимся осознать свои сильные и слабые стороны в контексте авиационного английского.

11. **Культурная чувствительность**: Учитывайте культурные различия при формулировке вопросов, особенно в международной авиационной среде, где работают специалисты из разных культур и стран.

12. **Обратная связь по результатам**: Предусмотрите возможность предоставления респондентам обратной связи по результатам анкетирования, чтобы они могли извлечь пользу из своего участия.

---

H5P Questionnaire представляет собой мощный инструмент для преподавания авиационного английского, позволяющий собирать разнообразную информацию, стимулировать рефлексию и адаптировать обучение к специфическим потребностям и опыту учащихся. В отличие от традиционных тестов, анкеты создают безопасное пространство для самоанализа и профессиональных суждений, без страха "неправильного ответа".

Особенно ценным является использование анкет для диагностики начального уровня и потребностей учащихся, анализа сложных профессиональных ситуаций и развития критического мышления в контексте авиационной коммуникации. Хорошо разработанные анкеты способствуют более глубокому пониманию собственного уровня владения профессиональным языком и помогают учащимся осознать области, требующие дополнительного внимания и практики.

Следуя рекомендациям, представленным в этом руководстве, вы сможете создавать эффективные и информативные анкеты, которые не только соберут ценные данные для адаптации учебного процесса, но и сами по себе станут инструментом обучения, развивая у студентов навыки рефлексии и самооценки в контексте авиационного английского языка.
