# Конвертер раскладки клавиатуры

Этот инструмент автоматически конвертирует текст между русской и английской раскладками клавиатуры. Если вы случайно набрали текст в неправильной раскладке, скрипт поможет мгновенно исправить его.

## Возможности

- Конвертация текста из русской раскладки в английскую и наоборот
- Сохранение регистра букв (заглавные/строчные)
- Корректная обработка знаков препинания
- Возможность приостановки работы скрипта
- Работает с выделенным текстом в любом приложении

## Установка

1. Установите [AutoHotkey](https://www.autohotkey.com/) (если он ещё не установлен)
2. Скачайте файл `translator.ahk`
3. Запустите файл, дважды щёлкнув по нему

## Использование

### Основные команды

- **Ctrl+Q** — Конвертировать выделенный текст
- **F11** — Приостановить/возобновить работу скрипта

### Пошаговое руководство

1. Выделите текст, который нужно конвертировать (например, "ghbdtn" вместо "привет")
2. Нажмите **Ctrl+Q**
3. Текст будет автоматически преобразован в правильную раскладку ("ghbdtn" → "привет")

### Примеры

- **Русский → Английский**:  
  "Привет, мир!" → "Ghbdtn, vbh!"

- **Английский → Русский**:  
  "Ghbdtn, vbh!" → "Привет, мир!"

## Особенности работы

- Скрипт автоматически определяет, в какой раскладке был набран текст
- При конвертации с русского на английский знаки препинания сохраняются без изменений
- При конвертации с английского на русский все символы преобразуются согласно раскладке
- При активации/деактивации скрипта появляется уведомление в системном трее

## Решение проблем

- **Скрипт не работает**: Убедитесь, что AutoHotkey установлен и запущен
- **Неправильная конвертация**: Проверьте, что текст правильно выделен и не содержит смешанных раскладок
- **Конфликт с другими программами**: Используйте F11 для временной приостановки работы скрипта

## Настройка

Для изменения горячих клавиш откройте файл `translator.ahk` в любом текстовом редакторе:

- Для изменения клавиши конвертации измените строку `^q::` (где `^` означает Ctrl, а `q` — букву Q)
- Для изменения клавиши приостановки измените строку `F11::`

## Автозапуск

Для автоматического запуска скрипта при загрузке Windows:

1. Нажмите Win+R и введите `shell:startup`
2. Создайте ярлык для файла `translator.ahk` в открывшейся папке

## Лицензия

Этот скрипт распространяется по свободной лицензии. Вы можете использовать его, модифицировать и распространять без ограничений.

## Контакты

При возникновении вопросов или предложений по улучшению скрипта, пожалуйста, свяжитесь с автором.
