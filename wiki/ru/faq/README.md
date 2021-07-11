# Часто задаваемые вопросы (FAQ)

## Я только что приобрел игру, что мне делать дальше?
Прочитайте наше [руководство для начинающих](/beginners-guide.md)!

## Как получить больше песен?
> [BeatSaver](https://beatsaver.com) - это хранилище пользовательских песен, созданных сообществом. Существуют и другие сайты, которые позволяют загружать песни или предоставляют другие интерфейсы для этого, но именно этот является первоначальным источником песен для всех остальных сайтов.

Если вы хотите загрузить карты вручную из BeatSaver, создайте новую папку, распакуйте в нее архив с песней и перенесите эту папку в `Beat Saber/Beat Saber_Data/CustomLevels`. Из этой папки игра изначально читает пользовательские карты.

### BeastSaber
[Beast Saber](https://www.bsaber.com) это сайт с рецензиями, цель которого - более удобная организация всех песен с BeatSaver. Также вы можете скачать плейлисты, подписываться на определенных создателей карт, находить карты с помощью расширенных методов сортировки и многое другое.

### Внешние программы для загрузки и организации карт

Сейчас нет работающих приложений для управления песнями.

## Как установить плейлисты?

### ПК
Вам нужно установить модификацию [PlaylistManage](https://github.com/rithik-b/PlaylistManager/releases/latest).

Потом вы сможете:

* Использовать инструмент`Установка Плейлистов` в программе Mod Assistant, перейдя во вкладку Настройки.
* Поместить файл с плейлистом в `Beat Saber/Playlists`, выбрать название плейлиста в игре и нажать «скачать все песни».

Теперь вы увидите плейлист после кнопки с альбомом пользовательских песен в игре. Модификация также поддерживает управление плейлистами в игре.

### Quest
Вы можете использовать [Playlist Editor Pro](https://beatsaberquest.com/bmbf/my-tools/playlist-editor-pro/) для управления плейлистами на вашем Quest. Обратите внимание, что пользовательские песни могут появиться в игре только единожды из-за ограничений BMBF.

::warning ПРЕДУПРЕЖДЕНИЕ для пользователей Oculus Quest Перезагрузка папки пользовательских песен сбрасывает все плейлисты. :::

## Как создать свою собственную карту?
Смотрите [руководство по созданию карт](/mapping/)!

## Как установить модификации на ПК, которых нет в Mod Assistant?
Посмотрите [этот раздел](/pc-modding.md#manual-installation) в руководстве для начинающих.

## Поддерживает ли мультиплеер возможность играть с пользователями других платформ?
Официально, мультиплеер позволяет играть только с теми пользователями, которые приобрели игру в том же магазине, что и вы (Oculus/Steam). Кроме того, модификация игры на Oculus Quest отключает официальный мультиплеер совсем.

Мод BeatTogether - это нынешнее решение для кроссплатформенного мультиплеера между модифицированными версиями игры. Присоединяйтесь к [серверу Discord](https://discord.com/invite/gezGrFG4tz) и посетите канал `#install-instructions` для получения дополнительной информации.

## Моя игра обновилась, и теперь никакие модификации не работают
Каждое игровое обновление с *очень высокой вероятностью* ломает модификации, которые необходимо обновить. Чтобы убедиться, что установка модификаций не сломается, когда игра будет запускаться впервые на новой версии, всё содержимое папки `Plugins` будет автоматически перемещено в новую папку `Old 1.xx.x Plugins`. **Не переносите эти плагины/модификации обратно!**

Чтобы вернуть модификации обратно, просто **запустите установщик заново.**  
Репозиторий BeatMods включает в себя только те модификации, которые проверены для работы на последней версии игры!

Если вы запутались с чем-либо, посетите [Руководство для начинающих](/beginners-guide.md).

## Как работает система начисления очков в Beat Saber? Как работает мировой рейтинг?
У нас есть раздел о [хватах и советах](/grips-and-tricks.md), посвященный системе подсчёта очков и рейтинга, рекомендуем ознакомиться!

## Меню игры пустое, и я не могу ни на что нажать
Если главное меню игры пустое, ваш файл сохранения похоже был поврежден.

Чтобы исправить это, перейдите в: `%AppData%\..\LocalLow\Hyperbolic Magnetism`

Удалите или переименуйте папку Beat Saber в любое другое название. При повторном входе в игру, игра пересоздаст файл сохранения и загрузит главное меню правильно.