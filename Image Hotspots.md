# H5P Image Hotspots в Moodle: Подробное руководство

## Содержание
- [Введение в H5P](#введение-в-h5p)
- [Что такое Image Hotspots](#что-такое-image-hotspots)
- [Установка H5P в Moodle](#установка-h5p-в-moodle)
- [Создание активности Image Hotspots](#создание-активности-image-hotspots)
- [Подробные настройки Image Hotspots](#подробные-настройки-image-hotspots)
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

## Что такое Image Hotspots

Image Hotspots (Интерактивные точки на изображении) — это тип активности в H5P, который позволяет добавлять интерактивные точки (хотспоты) к изображению. При нажатии на эти точки пользователю отображается дополнительная информация в виде текста, изображений, видео или ссылок. Этот формат особенно полезен для:

- Создания интерактивных диаграмм и схем
- Объяснения сложных систем и устройств
- Обозначения и детализации частей изображения
- Разработки виртуальных туров по помещениям, оборудованию или объектам
- Создания визуальных словарей с иллюстрациями

Image Hotspots превращает статичное изображение в интерактивный учебный ресурс, позволяя учащимся исследовать и изучать содержимое в своем собственном темпе.

## Установка H5P в Moodle

Прежде чем создавать активности Image Hotspots, необходимо установить H5P в вашей системе Moodle:

1. Войдите в Moodle как администратор
2. Перейдите в раздел "Администрирование сайта" > "Плагины" > "Установка плагинов"
3. Нажмите кнопку "Установить плагины из каталога плагинов Moodle"
4. Найдите "H5P" в списке плагинов и установите его
5. Следуйте инструкциям по установке
6. После завершения установки активируйте плагин

## Создание активности Image Hotspots

### Шаг 1: Добавление активности H5P в курс

1. Перейдите на страницу вашего курса в Moodle
2. Включите режим редактирования, нажав кнопку "Режим редактирования" в правом верхнем углу
3. В нужном разделе курса нажмите "Добавить элемент или ресурс"
4. В открывшемся окне выберите "H5P интерактивный контент" и нажмите "Добавить"

### Шаг 2: Настройка основных параметров

1. Введите название для вашей активности в поле "Название"
2. При необходимости добавьте описание в поле "Описание"
3. В разделе "Настройки H5P" нажмите кнопку "Создать" или "Загрузить контент"
4. Из списка доступных типов контента выберите "Image Hotspots"

### Шаг 3: Загрузка изображения и создание хотспотов

1. В поле "Заголовок" введите название для вашего интерактивного изображения
2. Загрузите базовое изображение, нажав кнопку "Добавить фоновое изображение"
   - Выберите файл с вашего компьютера или используйте URL-адрес изображения
   - Для наилучших результатов используйте изображение высокого качества и достаточного размера
   
3. После загрузки изображения нажмите кнопку "Добавить хотспот"
4. Для каждого хотспота настройте:
   - **Положение**: перетащите хотспот в нужное место на изображении
   - **Тип хотспота**: выберите форму (круг или прямоугольник)
   - **Размер**: настройте размер хотспота с помощью маркеров изменения размера
   - **Заголовок**: введите название, которое будет отображаться в всплывающем окне
   - **Содержимое**: добавьте текст, изображения, видео или другие медиа, которые будут отображаться при нажатии на хотспот

5. Повторите процесс для создания всех необходимых хотспотов на изображении

### Типы содержимого для хотспотов

Для каждого хотспота вы можете добавить различные типы содержимого:

- **Текст**: обычный или форматированный текст с возможностью использования HTML
- **Изображение**: дополнительное изображение, которое отобразится во всплывающем окне
- **Видео**: встроенное видео из YouTube, Vimeo или загруженное локально
- **Ссылка**: гиперссылка на внешний ресурс или другую страницу курса
- **Встроенный H5P контент**: другой H5P интерактивный элемент внутри всплывающего окна

## Подробные настройки Image Hotspots

### Настройки изображения

- **Размер изображения**: настройка отображаемых размеров базового изображения
- **Масштабирование**: настройки соотношения сторон и растяжения изображения
- **Альтернативный текст**: добавление описания для людей с нарушениями зрения

### Настройки хотспотов

- **Цвет хотспота**: выбор цвета для каждого хотспота
- **Прозрачность**: настройка прозрачности хотспотов
- **Эффект наведения**: изменение вида хотспота при наведении курсора
- **Легенда**: добавление подписей к хотспотам на изображении

### Настройки всплывающих окон

- **Размер окна**: настройка ширины и высоты всплывающих окон
- **Позиционирование**: настройка положения относительно хотспота
- **Вид закрытия**: настройка кнопки или способа закрытия окна
- **Эффекты анимации**: выбор эффектов появления и исчезновения

### Шаг 4: Сохранение и публикация

1. После завершения всех настроек нажмите "Сохранить и показать"
2. Проверьте, как работают ваши хотспоты с точки зрения студента
3. При необходимости вернитесь к редактированию и внесите изменения

## Примеры использования для авиационного английского

### Пример 1: Интерактивная схема самолета

```
Базовое изображение: Схематичное изображение самолета с внешней стороны

Хотспот 1: Кабина пилота (Cockpit)
Содержимое: 
<h3>Cockpit</h3>
<p>The cockpit is the area where pilots control the aircraft. It contains all essential flight instruments, controls, and systems needed to fly the aircraft safely.</p>
<p>Key components include:</p>
<ul>
<li>Control yoke or side stick</li>
<li>Rudder pedals</li>
<li>Engine throttles</li>
<li>Navigation systems</li>
<li>Communication equipment</li>
</ul>
<img src="cockpit_interior.jpg" alt="Inside view of an aircraft cockpit">

Хотспот 2: Крыло (Wing)
Содержимое:
<h3>Wing</h3>
<p>The wings are airfoils that create lift when the aircraft moves forward. They also house fuel tanks and support control surfaces.</p>
<p>Main parts of the wing include:</p>
<ul>
<li>Ailerons: Control roll movement</li>
<li>Flaps: Increase lift during takeoff and landing</li>
<li>Slats: Extend from the leading edge to improve low-speed performance</li>
<li>Spoilers: Reduce lift and increase drag</li>
</ul>
<video src="wing_operations.mp4" controls></video>

Хотспот 3: Шасси (Landing Gear)
Содержимое: 
...и так далее для каждой основной части самолета...
```

### Пример 2: Интерактивная панель приборов

```
Базовое изображение: Детальное изображение приборной панели в кабине пилота

Хотспот 1: Высотомер (Altimeter)
Содержимое:
<h3>Altimeter</h3>
<p>The altimeter is an instrument that measures the aircraft's altitude above mean sea level (MSL). It works by sensing changes in atmospheric pressure.</p>
<p>Reading an altimeter:</p>
<ul>
<li>The long pointer indicates hundreds of feet</li>
<li>The short pointer indicates thousands of feet</li>
<li>The altimeter setting window (Kollsman window) shows the barometric pressure setting</li>
</ul>
<p>Standard pressure setting is 29.92 inches of mercury (1013.2 hPa) when flying above the transition altitude.</p>
<img src="altimeter_reading.jpg" alt="How to read an altimeter">

Хотспот 2: Авиагоризонт (Attitude Indicator)
Содержимое:
<h3>Attitude Indicator</h3>
<p>Also known as an artificial horizon, this instrument shows the aircraft's orientation relative to the horizon. It indicates pitch (nose up or down) and bank (wing tilt).</p>
<p>The instrument has:</p>
<ul>
<li>A miniature aircraft symbol fixed in the center</li>
<li>A horizon line that moves to show the real horizon position</li>
<li>Pitch markings in degrees above and below the horizon</li>
<li>Bank angle markings at the top</li>
</ul>
<iframe width="560" height="315" src="https://www.youtube.com/embed/example?controls=1" frameborder="0" allowfullscreen></iframe>

Хотспот 3: Указатель воздушной скорости (Airspeed Indicator)
Содержимое:
...и так далее для каждого основного прибора...
```

### Пример 3: Интерактивная карта аэропорта

```
Базовое изображение: Схема аэропорта с видом сверху

Хотспот 1: Взлетно-посадочная полоса (Runway)
Содержимое:
<h3>Runway 09/27</h3>
<p>Runway 09/27 is 3,500 meters long and 45 meters wide, capable of handling wide-body aircraft.</p>
<p>Designation explanation:</p>
<ul>
<li>The numbers 09 and 27 indicate the magnetic heading of the runway in tens of degrees</li>
<li>Runway 09 is aligned at approximately 090° (east)</li>
<li>Runway 27 is the same runway used in the opposite direction at 270° (west)</li>
</ul>
<p>The runway has high-intensity runway lights (HIRL) and an instrument landing system (ILS) for approaches in low visibility conditions.</p>
<img src="runway_markings.jpg" alt="Runway markings explanation">

Хотспот 2: Перрон (Apron)
Содержимое: 
<h3>Main Apron</h3>
<p>The apron, also called the ramp, is the area where aircraft park for loading and unloading, refueling, and boarding.</p>
<p>This main apron contains:</p>
<ul>
<li>25 aircraft stands with jet bridges</li>
<li>Ground service equipment areas</li>
<li>Marked taxiways for aircraft movement</li>
<li>Service vehicle lanes</li>
</ul>
<p>Standard phraseology when operating on the apron: "Request taxi to stand number [X]" or "Request push-back from stand [X]"</p>

Хотспот 3: Диспетчерская вышка (Control Tower)
Содержимое:
...и так далее для каждой зоны аэропорта...
```

### Пример 4: Интерактивная схема навигационной карты

```
Базовое изображение: Аэронавигационная карта с маршрутами, навигационными средствами и зонами

Хотспот 1: VOR (VHF Omnidirectional Range)
Содержимое:
<h3>VOR Navigation Aid</h3>
<p>VOR (VHF Omnidirectional Range) is a short-range radio navigation system that enables aircraft to determine their position and stay on course by receiving radio signals transmitted by a network of fixed ground radio beacons.</p>
<p>On the chart, VORs are typically shown as a compass rose with the following information:</p>
<ul>
<li>Name and identifier (usually a three-letter code)</li>
<li>Frequency (in MHz, between 108.0 and 117.95)</li>
<li>Radials (straight lines emanating from the VOR)</li>
</ul>
<p>When flying with VOR navigation, pilots tune to the station's frequency and follow specific radials to navigate between points.</p>
<img src="vor_symbol.jpg" alt="VOR symbol on a navigation chart">

Хотспот 2: Воздушный коридор (Airway)
Содержимое:
<h3>Airways</h3>
<p>Airways are predetermined routes that connect navigation aids, intersections, or waypoints. They serve as highways in the sky for IFR (Instrument Flight Rules) traffic.</p>
<p>On this chart:</p>
<ul>
<li>Low-altitude airways (Victor airways) are shown in blue</li>
<li>High-altitude airways (Jet routes) are shown in red</li>
<li>The width of an airway is typically 8 nautical miles (4 NM on each side of centerline)</li>
<li>Each airway has a designated identifier (e.g., V16, J518)</li>
</ul>
<p>When filing a flight plan, pilots list the airways they plan to use as part of their route of flight.</p>

Хотспот 3: Зона ограничения полетов (Restricted Area)
Содержимое:
...и так далее для каждого элемента навигационной карты...
```

### Пример 5: Интерактивная схема метеорологической карты

```
Базовое изображение: Авиационная метеорологическая карта с различными символами и обозначениями

Хотспот 1: Фронт холодный (Cold Front)
Содержимое:
<h3>Cold Front</h3>
<p>A cold front is the leading edge of a cooler mass of air replacing a warmer mass of air. On a weather chart, it's depicted as a blue line with triangular points showing the direction of movement.</p>
<p>Flying conditions associated with cold fronts:</p>
<ul>
<li>Potentially severe weather including thunderstorms and turbulence</li>
<li>Abrupt changes in temperature, pressure, and wind direction</li>
<li>Line of convective activity along the front</li>
<li>Decreased visibility before and during passage</li>
<li>More stable conditions after passage</li>
</ul>
<p>As a pilot, you should consider delaying flight if a cold front is forecast to pass through your route during your flight time.</p>
<img src="cold_front_weather.jpg" alt="Weather associated with a cold front">

Хотспот 2: Область высокого давления (High Pressure Area)
Содержимое:
<h3>High Pressure Area</h3>
<p>A high pressure area (also called an anticyclone) is a region where atmospheric pressure is higher than the surrounding area. On a weather chart, it's labeled with the letter "H".</p>
<p>Typical weather associated with high pressure:</p>
<ul>
<li>Generally fair weather with clear skies</li>
<li>Light winds</li>
<li>Good visibility</li>
<li>Potential for morning fog or low stratus in humid conditions</li>
<li>Stable atmospheric conditions</li>
</ul>
<p>High pressure areas typically bring favorable flying conditions, but can sometimes create issues with fog, especially in morning hours.</p>

Хотспот 3: Символ грозы (Thunderstorm Symbol)
Содержимое:
...и так далее для каждого метеорологического элемента...
```

## Советы и лучшие практики

1. **Качественное базовое изображение**: Используйте четкие, высококачественные изображения с достаточным разрешением, чтобы детали были хорошо видны.

2. **Стратегическое размещение хотспотов**: Размещайте хотспоты логично и интуитивно понятно, избегая перекрытия или слишком плотного расположения.

3. **Заметные хотспоты**: Выбирайте цвета хотспотов, которые контрастируют с фоновым изображением, чтобы они были легко различимы.

4. **Информативные заголовки**: Давайте хотспотам четкие, содержательные названия, которые точно указывают на их содержимое.

5. **Разнообразное содержимое**: Комбинируйте различные типы медиа (текст, изображения, видео) для создания богатого обучающего опыта.

6. **Последовательная навигация**: Если вы предполагаете определенный порядок изучения хотспотов, пронумеруйте их или дайте четкие указания.

7. **Сбалансированный объем информации**: Избегайте перегрузки всплывающих окон слишком большим количеством информации; при необходимости разделите содержимое на несколько хотспотов.

8. **Образовательная ценность**: Убедитесь, что каждый хотспот предоставляет действительно полезную информацию, а не просто декоративные элементы.

9. **Мобильная совместимость**: Проверьте, как ваши хотспоты работают на мобильных устройствах, и при необходимости настройте их размер и расположение.

10. **Инструкции по использованию**: Включите краткое руководство или подсказку о том, как взаимодействовать с хотспотами, особенно для тех, кто не знаком с этим типом активности.

11. **Взаимосвязанное содержимое**: При необходимости включайте перекрестные ссылки между хотспотами для создания более комплексного понимания.

12. **Последовательное тестирование**: Обязательно проверьте работу всех хотспотов перед публикацией, убедившись, что все элементы корректно отображаются и функционируют.

---

H5P Image Hotspots — это мощный инструмент для создания визуально богатых и интерактивных учебных материалов. Позволяя учащимся исследовать изображения и получать дополнительную информацию по запросу, этот тип активности особенно эффективен для технических предметов с сильным визуальным компонентом, таких как авиационный английский. Следуя этому руководству, вы сможете создавать информативные и вовлекающие интерактивные изображения для вашего учебного курса.
