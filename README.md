## Краткое описание:

**Wakfu Mod Installer** - это проект, цель которого обеспечить простую и удобную установку пользовательских модификаций для игры **Wakfu**, например неофициальных локализаций, изменений интерфейса, добавление или изменение функционала и т.д. Данный проект рассчитан на официальную версию игры.

###### *Примечание:*
> Если вы хотите установить русификацию Wakfu, просто скачайте инсталлятор и запустите.

----------------------------------------

## Проект включает в себя три компонента:

1. **Wakfu Mod Installer** - Утилита автоматической установки модификаций. Создана исключительно для удобства установки модов. Не является обязательным компонентом, при желании вы всегда можете использовать метод установки вручную без инсталлятора.
2. **Wakfu Mod Loader Plugin** - Плагин для *апдейтера Wakfu*, который добавляет возможность загрузки пользовательских модификаций. **Обязателен для загрузки модов**
3. **Wakfu Mods** - Это сами моды, которые изменяют игру. На данный момент доступен только один мод: **Руссификация Wakfu**. Но при желании вы всегда можете создать свои.

----------------------------------------

## Возможности Wakfu Mod Installer:
* Широкая кроссплатформенная поддержка. Поддерживает основные операционные системы: Windows, Mac OS, Linux. Включая устаревшие версии.
* Автоматическое определение операционной системы и установка соответствующих версий плагина.
* Автоматическое определение местонахождения установки Wakfu.
* Автоматическое определение Steam версии.
* Автоматические определение необходимых путей для установки плагинов и модов. Проверка корректности установки.
* Установка всех модов и плагинов полностью происходит из веб репозитория. При установке скачиваются самые последние версии модов и плагинов.
* Простое добавление, удаление и обновление существующих модов.
* Создан для упрощения процесса установки, как говорится *в один клик*.

----------------------------------------

## Возможности Wakfu Mod Loader Plugin
* Реализован в виде плагина к *апдейтеру Wakfu*
* Не требует никаких админ и root прав для использования
* Плагин не изменяет оригинальные файлы игры
* Совместимость как с обычной версией, так и со Steam версией
* Работает в незаметном, прозрачном, *«безшумном»* режиме для апдейтера
* Не создаёт кофликтов с апдейтором. Не вмешивается в работу апдейтера, игровые файлы всегда остаются акутальными, так как плагин ничего не изменяет в файлах игры, все изменения происходят после обновления игры до последней версии.
* Позволяет изменять любые настройки и параметры игры (**\*.ici, \*.properties и др.**), в том числе и скрытые.
* Позволяет редактировать любые игровые архивы (**\*.jar и др.**) и файлы, используемые игрой.
* Не изменяет и не модифицирует реальные файлы игры, в результате реальный апдейтер не замечает никаких изменений.
* Все изменения происходят на лету перед запуском игры
* Автоматическая загрузка всех модов из пользовательской папки
* Возможность загрузки нескольких модов, последовательность загрузки в алфавитном порядке.
* Легкий **ini-подобный** синтаксис для конфигурации и настройки своих модов
* Быстрая высоко оптимизированная скорость работы
* **Кроссплатформенная поддержка** (Windows, Mac OS, Linux)
* Написан на С++ и Qt

----------------------------------------

## Wakfu Mods:
Пользовательские модификации, которые автоматически загружаются из папки при запуске. В данный момент доступен для скачивания только один мод русификации игры, созданный на основе проекта https://github.com/Valianton/Wakfu-Translate

----------------------------------------

## Установка:
Существует два способа установки:
1. Автоматический
2. Вручную

### *Автоматический способ установки:*
Просто скачиваете нужную версию инсталлятора в зависимости от вашей операционной системы и запускаете и следуете инструкциям. Больше ничего не нужно, инсталлятор всё сделает сам. Плагин и моды автоматически будут загружаться при запуске *стандартного аддейтера Wakfu*.

Ниже приведены ссылки на скачивание инсталлятора в зависимости от вашей операционной системы:

OS           | Version       | File
------------ | ------------- | -------------
Windows | Windows XP and later | [Wakfu Mod Installer for Windows](https://github.com/DreamSworK/Wakfu-Mod-Installer/files/952505/WakfuModInstaller.windows.zip)
Mac OS | Mac OS X 10.7 and later | [Wakfu Mod Installer for Mac OS](https://github.com/DreamSworK/Wakfu-Mod-Installer/files/952516/WakfuModInstaller.osx.zip)
Linux 32-bit | Ubuntu 11.10 and later | [Wakfu Mod Installer for Linux i386](https://github.com/DreamSworK/Wakfu-Mod-Installer/files/952517/WakfuModInstaller.linux.i386.zip)
Linux 64-bit | Ubuntu 11.10 and later | [Wakfu Mod Installer for Linux x86_64](https://github.com/DreamSworK/Wakfu-Mod-Installer/files/952518/WakfuModInstaller.linux.x86_64.zip)

### *Установка вручную:*

1. Скачиваем Wakfu Mod Loader Plugin для вашей операционной системы
2. Устанавливаем Wakfu Mod Loader Plugin
3. Устанавливаем моды

## 1. Скачиваем **Wakfu Mod Loader Plugin** для вашей операционной системы

OS                   | Version             | File
------------ | ------------- | -------------
Windows | Windows XP and later | [Loader Plugin for Windows](https://github.com/DreamSworK/Wakfu-Mod-Installer/raw/master/repository/wakfu.plugin.loader.windows/1.0.0content.7z)
Mac OS | Mac OS X 10.7 and later | [Loader Plugin for Mac OS](https://github.com/DreamSworK/Wakfu-Mod-Installer/raw/master/repository/wakfu.plugin.loader.osx/1.0.0content.7z)
Linux 32-bit | Ubuntu 11.10 and later | [Loader Plugin for Linux i386](https://github.com/DreamSworK/Wakfu-Mod-Installer/raw/master/repository/wakfu.plugin.loader.linux.i386/1.0.0content.7z)
Linux 64-bit | Ubuntu 11.10 and later | [Loader Plugin for Linux x86_64](https://github.com/DreamSworK/Wakfu-Mod-Installer/raw/master/repository/wakfu.plugin.loader.linux.x86_64/1.0.0content.7z)

## 2. Устанавливаем *Wakfu Mod Loader Plugin*

Просто распаковываем содержимое архива в нужную папку, в зависимости от того где находится **Wakfu** и какая версия используется.
Обратите внимание, что далее я укажу пути по умолчанию для каждой операционной системы, если у вас Wakfu установлена в каком-то другом месте, подкорректируйте путь самостоятельно.

### Windows:

Версия Wakfu | Путь установки плагина
------------ | ----------------------
Обычная | C:\Program Files (x86)\Ankama\Wakfu\transition\plugins\updater\
Steam | C:\Program Files (x86)\Steam\steamapps\common\Wakfu\transition\plugins\updater\

### Mac OS:

Версия Wakfu | Путь установки плагина
------------ | ----------------------
Обычная | /Applications/Wakfu.app/Contents/Data/Updater Wakfu.app/Contents/PlugIns/updater/
Steam | /Users/[Имя]/Library/Application Support/Steam/steamapps/common/Wakfu/Updater Wakfu.app/Contents/PlugIns/updater/

### Linux:

Версия Wakfu | Путь установки плагина
------------ | ----------------------
Обычная | [Ваш путь к Wakfu]/transition/plugins/updater/
Steam | /home/[Имя]/.local/share/Steam/steamapps/common/Wakfu/transition/plugins/updater/

## 3. Устанавливаем моды

Создаём папку **mods** в каталоге с данными игры и копируем туда свой мод.
Каждый мод это отдельная папка с **ini кофигурацией** и используемыми модом файлами для модификаций. Название **ini файла** должно соотвествовать названию папки. Название папки так же является названием мода.

### Windows:

Версия Wakfu | Путь для установки модов
------------ | ----------------------
Обычная | C:\Program Files (x86)\Ankama\Wakfu\game\mods\
Steam | C:\Program Files (x86)\Steam\steamapps\common\Wakfu\game\mods\

### Mac OS:

Версия Wakfu | Путь для установки модов
------------ | ----------------------
Обычная | /Applications/Wakfu.app/Contents/Data/Wakfu.app/Contents/Resources/mods/
Steam | /Users/[Имя]/Library/Application Support/Steam/steamapps/common/Wakfu/game/mods/

### Linux:

Версия Wakfu | Путь для установки модов
------------ | ----------------------
Обычная | [Ваш путь к Wakfu]/game/mods/
Steam | /home/[Имя]/.local/share/Steam/steamapps/common/Wakfu/game/mods/

Если плагин установлен корректно, то при запуске апдейтера вы увидете информацию о загруженном плагине и загруженных модификациях:

### Используемые файлы и пути установки на примере мода руссификаци:

----------------------------------------

### Описание синтаксиса настройки модов:

> Будет доступно в ближайшее время...

----------------------------------------

###### *Примечание:*
> Если у вас есть идеи по созданию новых модов для Wakfu, свяжитесь со мной любым удобным способом, если это окажется что-то интересное, я постараюсь реализовать. Так же вы можете отправить мне свои моды и я их добавлю в общий репозиторий доступных модов, которые устанавливаются инсталлятором.
