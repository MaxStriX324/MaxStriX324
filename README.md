# Максим Стародуб · MaxStriX324

**Hardware Engineer · Embedded Systems · Power Electronics · Electric Drives · Automation**

Привет! Я Максим, инженер-схемотехник из Саратова. Занимаюсь электроникой, микроконтроллерами, силовой преобразовательной техникой, электроприводом и автоматизацией.

Мне интересен **полный цикл разработки**: от идеи и расчётов до схемы, печатной платы, прошивки, измерений, поиска неисправностей и проверки устройства в реальных условиях. Если какую-то операцию приходится повторять много раз, стараюсь написать инструмент, который сделает её автоматически.

**[Персональный сайт](https://maxstrix324.github.io/)** · **[Все проекты](https://maxstrix324.github.io/projects/)** · **[Автоматизация лаборатории](https://maxstrix324.github.io/projects/lab-automation/)** · **[Habr](https://habr.com/ru/users/MaxStriX324/)** · **[DRIVE2](https://www.drive2.ru/users/maxstrix324/)**

## Инженерные направления

- **Embedded и управление:** STM32F103/F405, C, ADC, DMA, таймеры, ШИМ, UART, SPI, I²C, CAN, RS-485.
- **Силовая электроника:** IGBT/MOSFET, драйверы, DC-link, импульсные источники питания, гальваническая развязка, измерение токов и напряжений.
- **Электропривод:** трёхфазные инверторы, управление электродвигателями, защиты, рекуперация.
- **Автомобильная и EV-электроника:** высоковольтные батареи, зарядка, CAN, диагностика и интеграция оборудования.
- **Схемотехника и PCB:** KiCad, аналоговые измерительные тракты, прототипирование, пайка, работа с осциллографами и логическими анализаторами.
- **Программная автоматизация:** Python, Linux, Docker, базы данных, веб-сервисы, боты и локальные инструменты для инженерной работы.

`C` · `Python` · `Kotlin` · `STM32` · `KiCad` · `Git` · `Linux` · `Docker` · `PostgreSQL` · `CAN` · `RS-485`

## Автоматизация лаборатории — open source

Три утилиты для повседневной работы с печатными платами, станком и измерениями. Каждая опубликована с исходным кодом и инструкцией по запуску.

| Проект | Задача | Результат |
| --- | --- | --- |
| **[KiCad SVG → LaserGRBL](https://github.com/MaxStriX324/kicad-svg-lasergrbl)** | Пакетная подготовка слоёв плат из KiCad для лазерной обработки | Монохромные PNG, размеры и настройки импорта из SVG |
| **[KiCad DRL → CNC3018](https://github.com/MaxStriX324/kicad-drl-cnc3018)** | Преобразование сверловки Excellon для GRBL-станка | G-code `.tap` отдельно по диаметрам сверла |
| **[Rigol Oscilloscope Sorter](https://github.com/MaxStriX324/rigol-oscilloscope-sorter)** | Автоматическая организация измерений с DHO814 и DHO924S | Архив PNG, CSV/BIN, STP; экспорт поддерживаемых сигналов в XLSX |

**Как они используются:** проектирую плату в KiCad → готовлю лазерные изображения и программы сверловки → после сборки сохраняю измерения с Rigol в упорядоченный архив.

Утилита CNC генерирует траектории, которые необходимо проверить перед работой на станке; продолговатые пазы она пока не фрезерует. Сортировщик Rigol сохраняет оригиналы, но не заявляет преобразование всех 16 цифровых каналов PLA2216 в Excel.

[Описание лабораторной автоматизации на моём сайте →](https://maxstrix324.github.io/projects/lab-automation/)

## Инженерные и аппаратные проекты

### [Тяговый инвертор](https://maxstrix324.github.io/projects/traction-inverter/)

Разработка трёхфазного инвертора для электропривода: IGBT, изолированные драйверы затворов, измерение фазных токов и напряжений, аппаратные защиты и управление на STM32.

`Power Electronics` · `STM32` · `IGBT` · `CAN` · `High Voltage`

### [Nissan Leaf HV Lab](https://www.drive2.ru/b/741266551264528987/)

Эксперименты с высоковольтной батареей Nissan Leaf AZE0, PDM, CAN-обменом и зарядкой. Изучаю, как можно применять автомобильные компоненты в других энергетических и электротранспортных системах.

`EV` · `CAN` · `Battery` · `High Voltage`

### [ПАЗ-3206 4×4 «Черепаха»](https://www.drive2.ru/r/other/725506426469878483/)

Полноприводный автобус как основа для будущего автодома. Постепенно занимаюсь восстановлением, компоновкой систем автономного жизнеобеспечения и проработкой электрической части. Гибридный привод и солнечная энергетика — направления исследования, а не готовая окончательная конструкция.

[Бортжурнал и автомобильные проекты на DRIVE2 →](https://www.drive2.ru/users/maxstrix324/)

## Программные проекты

### [900 рук — афиша Саратова и Саратовской области](https://900pyk.club/)

Собственный веб-проект для поиска мероприятий и площадок. Вокруг сайта строится автоматизированный процесс сбора, обработки, проверки и публикации информации из различных источников, а также инфраструктура развёртывания на домашнем Linux-сервере.

`Django` · `PostgreSQL` · `Docker` · `Caddy` · `Python` · `Self-hosting`

### [WorkBalance для Android](https://github.com/MaxStriX324/WorkBalance-Android)

Локальное Android-приложение для учёта рабочего времени: приход, уход, перерывы, баланс часов, календарь и прогноз времени завершения рабочего дня. Поддерживает русский и английский интерфейсы.

`Kotlin` · `Android` · `Offline-first`

### Ранние проекты автоматизации

- **[telegram_vk_chat_bot](https://github.com/MaxStriX324/telegram_vk_chat_bot)** — общая логика чат-бота для Telegram и ВКонтакте.
- **[poster_vk](https://github.com/MaxStriX324/poster_vk)** — отложенная публикация записей ВКонтакте через сообщения.

## Обо мне

Первое высшее образование — **материаловедение и технологии материалов**; также обучаюсь в магистратуре по направлению **электроэнергетики и электротехники**. Мне близка работа на пересечении механики, материалов, программирования и электроники.

Часть профессиональных разработок не может быть опубликована полностью. Здесь собираю личные проекты, открытые инструменты и технические материалы, которыми могу поделиться.

## English / About me

I'm **Maksim Starodub (MaxStriX324)**, a hardware and embedded systems engineer based in Saratov. My work and personal projects span **STM32, power electronics, motor drives, EV systems, CAN, PCB design, measurement and automation**.

I enjoy end-to-end engineering, from schematics and firmware to prototypes, oscilloscope measurements and testing on real hardware. I also publish small open-source tools that streamline PCB manufacturing and laboratory workflows.

**Portfolio:** [maxstrix324.github.io](https://maxstrix324.github.io/) · **Open-source lab tools:** [Lab Automation](https://maxstrix324.github.io/projects/lab-automation/)

## Связь и публикации

[Персональный сайт](https://maxstrix324.github.io/) · [GitHub](https://github.com/MaxStriX324) · [Habr](https://habr.com/ru/users/MaxStriX324/) · [DRIVE2](https://www.drive2.ru/users/maxstrix324/) · [Telegram](https://t.me/MaxStriX324) · [VK](https://vk.ru/maxstrix324) · [YouTube](https://www.youtube.com/@MaxStriX324) · [RUTUBE](https://rutube.ru/channel/6327951/) · [Дзен](https://dzen.ru/maxstrix324) · [Пикабу](https://pikabu.ru/@MaxStriX324)

---

*Интереснее всего не просто придумать устройство, а понять, как оно работает, собрать и довести до результата.*
