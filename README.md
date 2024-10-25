# Smart-home-system-on-Arduino-
Проект «Умный дом на базе Arduino» предназначен для автоматизации управления основными устройствами в доме, используя микроконтроллер Arduino Uno. Система управляет освещением и поддерживает комфортный микроклимат в помещении с использованием минимального набора компонентов, таких как датчики движения и температуры. Управление освещением и микроклиматом осуществляется при помощи кнопок, обеспечивая удобство использования без сложных сценариев и расписаний.

### Основные компоненты проекта
1. **Микроконтроллер Arduino Uno**: Управляет всеми подключенными датчиками и кнопками, выполняя обработку данных и управление устройствами.
2. **Датчики**:
   - *Датчик движения* (PIR-сенсор): Фиксирует присутствие людей в помещении, позволяя автоматически включать освещение.
   - *Датчик температуры и влажности* (DHT11/DHT22): Определяет температуру и влажность в комнате, позволяя контролировать микроклимат.
3. **Исполнительные устройства**:
   - *Кнопки*: Управляют включением и выключением освещения, вентилятора или обогревателя. Кнопки позволяют вручную управлять устройствами, включая или отключая их по необходимости.
   - *Светодиоды и лампы*: Индикация работы системы и освещение помещения.

### Основные функции системы
- **Автоматическое управление освещением**: При обнаружении движения в комнате срабатывает автоматическое включение света. Освещение отключается автоматически, когда движение не фиксируется.
- **Контроль температуры и влажности**: Система следит за микроклиматом в помещении, включая обогреватель или вентилятор при изменении температуры или влажности.
- **Локальное управление с помощью кнопок**: Пользователь может управлять освещением и другими устройствами с помощью кнопок, подключенных к системе, без необходимости в удаленном управлении или использовании сложных сценариев.

### Пример работы системы
1. **Автоматизация освещения**: Когда PIR-сенсор обнаруживает движение, Arduino включает свет. Свет автоматически выключается, если движение не фиксируется в течение заданного времени.
2. **Поддержание микроклимата**: Если температура в помещении превышает установленный уровень, система включает вентилятор. В случае низкой температуры — активирует обогреватель. Параметры контролируются через датчик температуры и влажности.

### Реализация проекта
Для сборки проекта потребуется написать код на Arduino IDE, который позволит контролировать работу датчиков и кнопок, а также обрабатывать сигналы для управления устройствами. Подключение кнопок к системе сделает управление более удобным и доступным для пользователя.

Проект отлично подойдет для создания базовой системы автоматизации, обеспечивающей комфорт и удобство управления в помещении.
