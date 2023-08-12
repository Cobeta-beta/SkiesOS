Оригинальный проект [заморожен](https://github.com/AshiVered/SkyOS/issues/6)
# Оригинальное лого

![logo](https://raw.githubusercontent.com/Cobeta-beta/SkiesOS/main/res/logo.png)

# SkiesOS

SkiesOS - это порт SkyOS для Nokia 2720 Flip (Beatles). Сейчас проект находится в первой публичной бета-версии! (0.5)
На данный момент, я не думаю продолжать работу автора, и добавлять что он хотел.

# Original description

SkyOS - это кастомная прошивка для Nokia 800 Tough. Данная прошивка предназначена для повышения скорости работы и улучшения пользовательского опыта. Она основана на прошивке v40 и
сейчас проект находится в стадии публичной альфа-версии (0.1).


# Скриншоты

![screenshot1](https://raw.githubusercontent.com/Cobeta-beta/SkiesOS/main/res/2022-12-26-08-00-15.png)
![screenshot2](https://raw.githubusercontent.com/Cobeta-beta/SkiesOS/main/res/2022-12-26-08-00-24.png)


Изменения по сравнению с оригинальной прошивкой (KaiOS):
- Удалён весь мусор (debloated)
- заменено стоковое приложение "Контакты" на [SkyOS контакты](https://gitlab.com/AshiVered/skyos-contacts)
- заменено стоковое приложение "Камера" на [SkyOS камера](https://gitlab.com/AshiVered/SkyOS-Camera)
- заменено стоковое приложение "Музыка" на [K-music](https://github.com/arma7x/kaimusic)
- заменено стоковое приложение "Файлы" на [GerdaOS файлы](https://gitlab.com/project-pris/system/-/tree/master/src/system/b2g/webapps/files.gerda.tech/src)
- ADblock
- Тема LineageOS
- Отключён lowmemorykiller deamon (LMK)
- Root права (если вы поставите boot из releases)
- Патчи для быстродействия

Что хотел сделать автор в следующей версии:

- Заменить стоковых приложений на более быстрые альтернативные приложения.
- добавить некоторые функции (например, диспетчер задач, как в Android или GerdaOS).
- добавить виртуальную RAM-память (файл подкачки/swap file)
- замена загрзочный экран (boot анимацию)

# Известные баги на данный момент (0.5)

Оригианльного проекта : 
- Некоторое время после загрузки ОС нельзя изменить настройки в "быстрых настройках"
- Не открываються некоторые приложение если их "забиндить" на горячую кнопку. (Заметки, Music/Музыка, Browser/Браузер, E-Mail, Camera/Камера. Всё остальное работает)
Порта на момент беты (0.5)
- Не работает фонарик
- При загрузке телефон греется

Установка:
- загрузить boot.img&system.img со страницы realeses
- прошейте с помощью [edl](https://wiki.bananahackers.net/development/edl)

# Мои благодарности

@minhduc-bui1 за помощь, а так-же помощи мне лучше понимать kaios
[Сообществу Bananahackers](https://discord.com/channels/472006912846594048/472144586295345153)
[форумчанам](https://4pda.to/forum/index.php?showtopic=965321)
И всем остальным! За поддержку а так-же за мотивацию!
