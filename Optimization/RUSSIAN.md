# Общие настройки <br> БУДЬТЕ ОСТОРОЖНЫ ВСЕ ДЕЙСТВИЯ СОВЕРШАЕТЕ НА СВОЙ СТРАХ И РИСК!

### Отключение контроля учётных записей

В поиске "Панель управления", выбрать мелкие значки. "Учётные записи пользователей", "Изменить параметры контроля учётных записей", изменить на "Не рекомендуется".
<br><br>

### Панель управления

UPD: Не забываем применять!
Выбрать мелкие значки, выбрать "Центр специальных возможностей":
Снять галочки с "Всегда читать вслух" и "Всегда пролистывать этот раздел".

- Оптимизация изображений на экране - отключить все галочки.
- Облегчение работы с клавиатурой:<br>
  / Настройка управления указателем - отключить все галочки и ниже NUM LOCK: отключить;<br>
  / Настройка залипания клавиш - отключить все галочки;<br>
  / Настройка фильтрации ввода - отключить все галочки.
- Использование текста или зрительных образов вместо звуков - ставим "Нет".
- Облегчение использования сенсорных панелей и планшетов - "Экранный диктор" меняем на "Нет" (Если нету планшета и нет ограничений по слуху и зрению).
  <br><br>

### Отключение индексирование диска.

UPD: ВНИМАНИЕ! Занимает продолжительное время.
Открываем "Этот компьютер" правой кнопкой по диску (C:) "Свойства", снять галочку с "Разрешить индексировать содержимое файлов" - "Применить" / "к диску и все вложенным файлам" / "пропустить всё".
<br><br>

### Список служб которые можно отключить в Windows (работаю в автоматическом режиме)

UPD: Службы собраны из Windows 10-11, некоторые из них могут не быть на 10 или 11 версии, учитывайте данный фактор.<br>
Обозначения:<br>
(•) - отключение только для опытных пользователей.<br>
(\*) - службы которые можно отключить.<br>

| #   | Название службы                                          | Свойство                                                                               |
| --- | :------------------------------------------------------- | :------------------------------------------------------------------------------------- |
| \*  | Microsoft Update Health Service                          | Если удалили программу Microsoft Update Health Service                                 |
| \*  | Superfetch или SysMain                                   | Можно отключить если используется SSD и объем оперативной памяти больше 8гб            |
| •   | Windows Remediation Service                              | Если не используете обновления Windows                                                 |
| •   | Windows Search                                           | Если не ищете файлы через поиск                                                        |
| •   | Биометрическая служба Windows                            | Если не используются пароли, PIN-коды, отпечатки пальцев, Windows Hello                |
| •   | Брокер мониторинга среды выполнения System Guard         | Если не используется проверка целостности системных файлов                             |
| \*  | Вспомогательная служба IP                                | Если не используется протокол IPv6                                                     |
| \*  | Диспетчер печати                                         | Если нет принтера, и не используется функции печати, в том числе в PDF                 |
| \*  | Диспетчер подключений удаленного доступа                 | Если не используется удалённый доступ по VPN                                           |
| \*  | Диспетчер скаченных карт                                 | Если не используются карты Windows                                                     |
| •   | Диспетчер учетных веб-записей                            | Если не используется Microsoft Store и скаченые из него приложения                     |
| •   | Изоляция ключей CNG                                      | Если не используются пароли, PIN-коды, отпечатки пальцев, Windows Hello                |
| \*  | Использование данных                                     | Если не используется информация о трафике                                              |
| •   | Клиент отслеживания изменившихся связей                  | Если не используется перемещение NTFS-файлов в локальной сети                          |
| •   | Модуль поддержки NetBIOS через TCP/IP                    | Если не используется локальная сеть                                                    |
| \*  | Оптимизация доставки                                     | Если не используются обновления Windows                                                |
| \*  | Помощник по входу в учетную запись Майкрософт            | Если вы не используются продукты Microsoft                                             |
| \*  | Синхронизация узла                                       | Если не используется Windows почта и не авторизированны под учётной записью Microsoft  |
| \*  | Служба данных датчиков                                   | Если не используются планшет под управление Windows                                    |
| \*  | Служба датчиков                                          | Если не используются планшет под управление Windows                                    |
| •   | Служба кэша шрифтов Windows                              | Если не обновляете Microsoft Office                                                    |
| \*  | Служба лицензий клиента (ClipSVC)                        | Если не используется Microsoft Store и скаченые из него приложения                     |
| \*  | Служба наблюдения за датчиками                           | Если не используются планшет под управление Windows                                    |
| •   | Служба платформы подключенных устройств                  | Если не используются: Виртуальные рабочие столы, Хронология, Ваш телефон и Ночной свет |
| •   | Служба пользователя платформы подключенных устройств     | Если не используются: Виртуальные рабочие столы, Хронология, Ваш телефон и Ночной свет |
| \*  | Служба хранилища                                         | Если не используется Microsoft Store и скаченые из него приложения                     |
| •   | Узел службы диагностики                                  | Если не используется диагностики компьютера на уровне операционной системы             |
| \*  | Функциональные возможности для подключения пользователей | Сбор и слежка данных компанией Microsoft                                               |
| \*  | Центр обновления Windows                                 | Если не используется обновления Windows, Microsoft Store                               |

<br>

### Исправление автоматической смены яркости

Информация для ноутбуков на процессорах intel:
Если при отключении от зарядного кабеля у вас скачет яркость, то необходимо открыть "Центр управления графикой intel", выбрать пункт "Система", "Питание" и в графе "Энергосбережение дисплея" отключить тумблер.
<br><br><br><br><br><br><br><br><br><br>

# Windows 10 <br> БУДЬТЕ ОСТОРОЖНЫ ВСЕ ДЕЙСТВИЯ СОВЕРШАЕТЕ НА СВОЙ СТРАХ И РИСК!

### Отключение уведомления брандмауэра windows или защитника windows.

Win + R вписываем regedit и нажимаем Enter.<br>
В пути: Компьютер\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender Security Center\Notifications<br>
В пустом окне правой кнопкой, создать "Параметр DWORD (32 бита)" и назвать DisableNotifications<br>
После чего открыть параметр двойным нажатием и задать значение 1, применяем и перезагружаем ПК.
<br><br>

### Настройка свойств системы

UPD: Не забываем применять!<br>
Этот компьютер, правой кнопкой, свойства.<br>
В контекстном меню открываем "Дополнительные параметры системы"

- Имя компьютера / по желанию если хотите другое имя.
- Дополнительно / быстродействие можно отключить всё, но сильно не влияет на систему, можно использовать "Обеспечить наилучший вид" даже на слабых ПК.
- Защита системы / Локальный диск (С:)(Система) Защиту включить! Поставить на 7-12гб памяти.
- Удалённый доступ (Если не хотите никаких подключений к пк со стороны, то можно отключить.)
  <br><br>

### ПРОГРАММА "Параметры"

#### 1. Система

- Уведомления и действия (Можно отключить по желанию) / и там же пункт редактировать плитки быстрых действий, можно сделать так как необходимо.
- Фокусировка внимания (желательно быть опытным пользователем)
  Отключить все тумблеры и галочки. И в этом же меню "Настройте список приоритетов", Отключаем тумблеры и удаляем все приложения.
- Питание и спящий режим, выставляете значения которые необходимы вам / В этом же меню "Дополнительные параметры", откроется панель управления электропитанием - где можно поставить высокую производительность (на ноутбуке будет больше расход батареи).
- Память / Отключить "Функцию контроля памяти".
- Планшет или Режим планшета (Применять если экран не сенсорный) - никогда не использовать режим планшета / Запрашивать разрешение перед переключением режимов. Там же пункт "Изменить дополнительны параметры планшета" и там отключить все тумблеры.
- Многозадачность - временная шкала отключить.
- Общие возможности - Передача между устройствами отключить (Если не используется онлайн подключение между ПК и смартфоном).
- Буфер обмена - отключить все тумблеры и очистить данные. UPD: (Буфер будет также работать когда используете Ctrl + C).

#### 2. Персонализация

- Цвета / Отключить эффект прозрачность.
- Экран блокировки - отключить все тумблеры.
- Темы / Параметры значков рабочего стола можно включить Значки "Этот компьютер" и "Корзина".

#### 3. Приложения

- Приложения и возможности - удалить предустановленные программы которые не нужны.
- Приложения по умолчанию можно задать то что необходимо.
- Автономные карты - отключить все тумблеры и использовать "Удалить все карты".
- Автозагрузки - можно отключить программы, которые запускаются при включении ПК.

#### 4. Игры

- Xbox Game Bar - отключить все тумблеры и галочки.
- Клипы - если не используете запись экрана, отключить все тумблеры и галочки.
- Игровой режим - включить.

#### 5. Специальные возможности

- Экранный диктор - отключить все тумблеры и галочки (если диктор не используется).
- Голосовые функции - отключить все тумблеры и галочки.
- Клавиатура - отключить все тумблеры и галочки.
- Мышь - отключить все тумблеры и галочки.

#### 6. Конфиденциальность

UPD: Не забываем нажать на пункт "Изменить", и там тумблер включить или выключить от ситуации.

- Общие - отключить все тумблеры кроме "Разрешить Windows отслеживать запуски приложений".
- Голосовые функции - отключить все тумблеры.
- Персонализация рукописного ввода - отключить все тумблеры.
- Диагностика и отзывы - поставить отметку на "Обязательные диагностические данные". Далее все пункты отключить. Частота формирования отзывов (никогда). Удалить диагностические данные.
- Журнал действий - отключить все тумблеры и галочки. Очистить журнал действий.

<br>

ВКЛЮЧИТЬ ВСЕ ПУНКТЫ ИЛИ ОТКЛЮЧИТЬ ВСЕ ПУНКТЫ В ДАННЫХ РАЗРЕШЕНИЯХ:

| Название разрешения        | Действие   |
| :------------------------- | ---------- |
| Расположение               | ВКЛЮЧИТЬ   |
| Камера                     | ВКЛЮЧИТЬ   |
| Микрофон                   | ВКЛЮЧИТЬ   |
| Голосовая активация        | Отключить  |
| Сведения об учётной записи | Отключить  |
| Контакты                   | Отключить  |
| Календарь                  | Отключить  |
| Телефонные звонки          | Отключить  |
| Журнал вызовов             | Отключить  |
| Электронная почта          | Отключить  |
| Задачи                     | Отключить  |
| Обмен сообщениями          | Отключить  |
| Радио                      | Отключить  |
| Другие устройства          | Отключить  |
| Фоновые приложения         | Отключить  |
| Диагностика приложений     | Отключить  |
| Автоматическое скачивание  | ПРОПУСТИТЬ |
| Документы                  | ВКЛЮЧИТЬ   |
| Изображение                | ВКЛЮЧИТЬ   |
| Видео                      | ВКЛЮЧИТЬ   |
| Файловая система           | ВКЛЮЧИТЬ   |

<br>

#### 7. Обновление и безопасность

- Центр обновления Windows, внутри пункт "Дополнительные параметры" отключить все тумблеры. И внутри "Оптимизация доставки" отключить пункт загрузки с других компьютеров.
  <br><br>

### Отключение Microsoft Defender

Для отключения Microsoft Defender необходимо открыть "Параметры" / "Обновление и безопасность" / "Безопасность Windows" / "Открыть службу Безопасности Windows".
"Защита от вирусов и угроз" / "Управление настройками" и отключить все тумблеры.
UPD: после перезагрузки ПК, Defender снова включается.
<br><br><br><br><br><br><br><br><br><br>

# Windows 11 <br> БУДЬТЕ ОСТОРОЖНЫ ВСЕ ДЕЙСТВИЯ СОВЕРШАЕТЕ НА СВОЙ СТРАХ И РИСК!

### Настройка свойств системы

UPD: Не забываем применять!
Этот компьютер, правой кнопкой, свойства.
Откроются настройки, ищем "ссылки по теме" и открываем "Дополнительные параметры системы"

- Имя компьютера / по желанию если хотите другое имя.
- Дополнительно / быстродействие можно отключить всё, но сильно не влияет на систему, можно использовать "Обеспечить наилучший вид" даже на слабых ПК.
- Защита системы / Локальный диск (С:)(Система) Защиту включить! Поставить на 7-12гб памяти.
- Удалённый доступ (Если не хотите никаких подключений к пк со стороны, то можно отключить.)

---

### ПРОГРАММА "Параметры"

#### 1. Система

- Уведомления (Можно отключить по желанию), но лучше оставить.
- Питание и спящий режим, выставляете значения которые необходимы вам / В этом же меню "Режим питания", поставить на "Макс.производительность" (на ноутбуке будет больше расход батареи).
- Память / Отключить "Функцию контроля памяти".
- Обмен с устройствами поблизости - отключить (Если не используется онлайн подключение между ПК и смартфоном).
- Устранение неполадок - изменить на "Спрашивать меня перед запуском".
- Буфер обмена, "Журнал буфера обмена" отключить и очистить данные. UPD: (Буфер будет также работать когда используете Ctrl + C).

#### 2. Персонализация

- Цвета / Эффект прозрачности - отключить.
- Темы / Параметры значков рабочего стола можно включить Значки "Этот компьютер" и "Корзина".
- Экран блокировки / Отключить все галочки и тумблеры. Состояние экрана блокировки - "Ничего".
- Пуск / Использовать "Больше закреплений". Отключить все тумблеры.
- Панель задач / Можно отключить все тумблеры по желанию.
- Использование устройства / Отключить все тумблеры.

#### 3. Приложения

- Установленные приложения - удалить предустановленные программы которые не нужны.
- Приложения по умолчанию можно задать то что необходимо.
- Автономные карты - отключить тумлеры. "Обновление карт" убрать галочку с "Автоматически обновляться".
- Автозагрузки - можно отключить программы, которые запускаются при включении ПК.

#### 4. Игры

- Xbox Game Bar - отключить.
- Записи - если не используете запись экрана, отключить все тумблеры.
- Игровой режим - включить.

#### 5. Специальные возможности

- Экранный диктор - отключить все тумблеры и галочки (если диктор не используется).
- Голосовые функции - отключить все тумблеры и галочки.
- Клавиатура - отключить все тумблеры и галочки. UPD: "Используйте клавишу PrtSc для открытия ножниц" по желанию можно оставить.
- Мышь - отключить все тумблеры и галочки.

#### 6. Конфиденциальность

- Общие - отключить все тумблеры кроме "Разрешить Windows отслеживать запуски приложений".
- Голосовые функции - отключить все тумблеры.
- Персонализация рукописного ввода - отключить все тумблеры. "Пользовательский словарь" - "Очистить пользовательский словарь.
- Диагностика и отзывы - отключить все тумблеры, и Удалить диагностические данные. Частота формирования отзывов (никогда).
- Журнал действий - отключить все тумблеры. Очистить журнал действий.

<br>

ВКЛЮЧИТЬ ВСЕ ПУНКТЫ ИЛИ ОТКЛЮЧИТЬ ВСЕ ПУНКТЫ В ДАННЫХ РАЗРЕШЕНИЯХ:

| Название разрешения        | Действие   |
| :------------------------- | ---------- |
| Расположение               | ВКЛЮЧИТЬ   |
| Камера                     | ВКЛЮЧИТЬ   |
| Микрофон                   | ВКЛЮЧИТЬ   |
| Голосовая активация        | Отключить  |
| Уведомления                | ВКЛЮЧИТЬ   |
| Сведения об учётной записи | Отключить  |
| Контакты                   | Отключить  |
| Календарь                  | Отключить  |
| Телефонные звонки          | Отключить  |
| Журнал вызовов             | Отключить  |
| Электронная почта          | Отключить  |
| Задачи                     | Отключить  |
| Обмен сообщениями          | Отключить  |
| Радио                      | Отключить  |
| Другие устройства          | Отключить  |
| Диагностика приложений     | Отключить  |
| Автоматическое скачивание  | ПРОПУСТИТЬ |
| Документы                  | ВКЛЮЧИТЬ   |
| Папка загрузок             | ВКЛЮЧИТЬ   |
| Фонотека                   | ВКЛЮЧИТЬ   |
| Изображения                | ВКЛЮЧИТЬ   |
| Видео                      | ВКЛЮЧИТЬ   |
| Файловая система           | ВКЛЮЧИТЬ   |
| Рамка снимка экрана        | ВКЛЮЧИТЬ   |
| Снимки экрана и приложения | ВКЛЮЧИТЬ   |

<br>

#### 7. Центр обновления Windows

- "Дополнительные параметры" отключить все тумблеры. И внутри "Оптимизация доставки" отключить пункт загрузки с других компьютеров.

---

### Отключение Microsoft Defender

Для отключения Microsoft Defender необходимо открыть "Параметры" / "Конфиденциальность и защита" / "Безопасность Windows" / "Открыть службу Безопасности Windows".
"Защита от вирусов и угроз" / "Управление настройками", отключить все тумблеры.
UPD: после перезагрузки ПК, Defender снова включается.
