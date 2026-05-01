# gajim-m3u-radio-menu
M3U internet radio plugin for Gajim
# M3U Radio Menu for Gajim

A small user plugin for Gajim that adds internet radio to the Gajim interface.

It was made for people who want to listen to online radio streams directly while using Gajim.

## Features

- Adds a compact radio panel to the left side of Gajim
- Plays M3U playlists and direct audio stream URLs
- Supports multiple radio stations
- Lets you switch stations from the plugin menu
- Adds a separate tray icon for quick control
- Supports the Ctrl + Alt + R shortcut
- Can show “Now Playing” information if the stream provides metadata
- Can optionally publish the currently playing track as your XMPP status message

## Tested with

- Gajim 2.4.5
- Windows 10
- GTK 4.22.2

Other systems and Gajim versions may work, but they have not been fully tested yet.

## Installation

1. Download `m3u-radio-menu-gajim-0.14.zip` from the Releases page.
2. Open Gajim.
3. Open the plugin manager.
4. Click **Install plugin from archive**.
5. Choose the downloaded ZIP file.
6. Enable **M3U Radio Menu**.
7. Open the plugin settings and add your stations if needed.

## Playlist format

Add one station per line:

```text
Station Name | Stream or M3U URL
SomaFM Groove Salad | https://somafm.com/m3u/groovesalad.m3u
SomaFM Secret Agent | https://somafm.com/m3u/secretagent.m3u
Both .m3u playlist URLs and direct stream URLs can be used.

Notes

“Now Playing” information depends on the radio stream. Some streams provide track metadata, some do not.

Publishing the current track as your XMPP status is disabled by default. If you enable it, your contacts may see what you are listening to.

This is a small community plugin, not an official Gajim feature.

Known limitations
Tested mainly on Windows.
Metadata support depends on the stream and playback backend.
The plugin uses UI integration that may need adjustments for other Gajim versions.


# M3U Radio Menu — интернет-радио для Gajim 2.4.5

Небольшой пользовательский модуль для Gajim, который добавляет радио-панель в левую область клиента.

## Что умеет

* воспроизводит M3U/stream-ссылки;
* поддерживает несколько радиостанций;
* позволяет переключать станции из меню;
* показывает текущую станцию в интерфейсе;
* может показывать Now Playing, если поток отдаёт метаданные;
* имеет отдельную иконку в трее;
* поддерживает горячую клавишу `Ctrl + Alt + R`;
* опционально может публиковать текущий трек в XMPP-статус.

## Проверено

* Gajim 2.4.5
* Windows 10
* GTK 4.22.2

На других версиях Gajim и других ОС модуль может работать, но пока не проверялся.

## Установка

1. Скачайте архив `m3u_radio_menu_v14.zip`.
2. Откройте Gajim.
3. Перейдите в меню модулей.
4. Выберите **Установить модуль из архива**.
5. Укажите скачанный ZIP-файл.
6. Включите модуль **M3U Radio Menu**.
7. При необходимости откройте настройки модуля и добавьте свои станции.

## Формат списка станций

В настройках станции добавляются по одной на строку:

```text
Название станции | https://example.com/radio.m3u
SomaFM Groove Salad | https://somafm.com/m3u/groovesalad.m3u
SomaFM Secret Agent | https://somafm.com/m3u/secretagent.m3u
```

Можно использовать как `.m3u`-ссылки, так и прямые ссылки на аудиопоток, если они поддерживаются системой.

## Важно

Функция публикации текущего трека в XMPP-статус выключена по умолчанию. Если её включить, название проигрываемой песни может быть видно вашим контактам.

Отображение Now Playing зависит от самой радиостанции: не все потоки передают метаданные о треке.

