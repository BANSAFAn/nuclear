# ![nuclear](https://i.imgur.com/oT1006i.png)
[![nuclear](https://snapcraft.io//nuclear/badge.svg)](https://snapcraft.io/nuclear) [![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/JqPjKxE)

Десктопный музыкальный проигрыватель, ориентированный на потоковую передачу из бесплатных источников

![Showcase](https://i.imgur.com/8qHu66J.png)

# Посилання

[Офіційний сайт](https://nuclear.js.org)

[Завантажити](https://github.com/nukeop/nuclear/releases)

[Документація](https://nukeop.gitbook.io/nuclear/)

[Mastodon](https://fosstodon.org/@nuclearplayer)

[Twitter] (https://twitter.com/nuclear_player)

Канал підтримки (Matrix): `#nuclear:matrix.org`

Discord чат: https://discord.gg/JqPjKxE

Пропонуйте та голосуйте за нові функції тут: https://nuclear.featureupvote.com/

Переклад документації:

<kbd>[<img title="Deutsch" alt="Deutsch" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/de.svg" width="22">](docs/README-de.md)</kbd>
<kbd>[<img title="Português" alt="Português" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/br.svg" width="22">](docs/README-ptbr.md)</kbd>
<kbd>[<img title="Svenska" alt="Svenska" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/se.svg" width="22">](docs/README-se.md)</kbd>
<kbd>[<img title="English" alt="English" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/us.svg" width="22">](README.md)</kbd>
<kbd>[<img title="Hebrew" alt="Hebrew" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/il.svg" width="22">](docs/README-he.md)</kbd>
<kbd>[<img title="Italiano" alt="Italiano" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/it.svg" width="22">](docs/README-it.md)</kbd>
<kbd>[<img title="Türkçe" alt="Türkçe" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/tr.svg" width="22">](docs/README-tr.md)</kbd>
<kbd>[<img title="Español" alt="Español" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/es.svg" width="22">](docs/README-es.md)</kbd>
<kbd>[<img title="Indonesia" alt="Indonesia" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/id.svg" width="22">](docs/README-id.md)</kbd>
<kbd>[<img title="Français" alt="Français" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/fr.svg" width="22">](docs/README-fr.md)</kbd>
<kbd>[<img title="Chinese" alt="Chinese" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/cn.svg" width="22">](docs/README-zh-cn.md)</kbd>
<kbd>[<img title="Russian" alt="Russian" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/ru.svg" width="22">](docs/README-ru.md)</kbd>
<kbd>[<img title="Polski" alt="Polski" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/pl.svg" width="22">](docs/README-pl.md)</kbd>

## Що це?
Nuclear - це безкоштовна програма для потокової передачі музики, яка отримує контент з безкоштовних джерел по всьому Інтернету.

Якщо ви знайомі з [mps-youtube](https://github.com/mps-youtube/mps-youtube), це схожий музичний програвач, але з графічним інтерфейсом.
Він також більше спеціалізується на аудіо. Уявіть Spotify з великою бібліотекою за який не потрібно платити.

## Що якщо мені не подобається Electron?
Подивіться [тут](docs/electron-ru.md).

## Особливості

- Пошук та відтворення музики з YouTube (включаючи інтеграцію з плейлистами, а також [Sponsor Block](https://sponsor.ajay.app/), Jamendo, Audius та SoundCloud)
- Функція пошуку альбомів (на основі Last.fm та Discogs), перегляду альбомів, автоматичного пошуку пісень за виконавцем та назвою треку (у розробці, іноді може не працювати)
- Черговість пісень, можна експортувати у вигляді плейлиста
- Завантажувати збережені плейлисти (зберігаються у файлах формату json)
- Синхронізація з last.fm (також оновлює статус «Виконується»)
- Нові релізи з оглядами - треки та альбоми
- Пошук за жанрами
- режим радіо (автоматично підбирає схожі треки)
- Необмежену кількість завантажень (на основі YouTube)
- Відображення текстів пісень у реальному часі
- Пошук за популярністю
- Список улюблених треків
- Прослуховування пісень із локальної бібліотеки
- Немає необхідності в акаунті
- Без реклами
- Без CoC (Кодексу поведінки)
- Без CLA (Ліцензійної угоди з користувачем)

## Процес розробки

По-перше, переконайтеся, що ви прочитали [Contribution Guidelines](https://nukeop.gitbook.io/nuclear/contributing/contribution-guidelines).

Інструкцію із запуску Nuclear в режимі розробки можна знайти в документації [Development Process](https://nukeop.gitbook.io/nuclear/developer-resources/development-process).

## Пакети, що підтримуються спільнотою
Ниже приведен список пакетов, используемых в различных менеджерах пакетов, некоторые из которых поддерживаются сторонними мейнтейнерами и имеют открытый исходный код.
Мы бы хотели искренне поблагодарить их за вклад в развитие.

|   Тип пакета   |                            Посилання                               |                        Мейнтейнер                         |             Метод встановлення                 |
|:--------------:|:------------------------------------------------------------------:|:---------------------------------------------------------:|:----------------------------------------------:|
|   AUR (Arch)   |       https://aur.archlinux.org/packages/nuclear-player-bin/       |            [nukeop](https://github.com/nukeop)            |           yay -s nuclear-player-bin            |
|   AUR (Arch)   |       https://aur.archlinux.org/packages/nuclear-player-git        |            [nukeop](https://github.com/nukeop)            |           yay -s nuclear-player-git            |
|  Choco (Win)   |              https://chocolatey.org/packages/nuclear/              |       [JourneyOver](https://github.com/JourneyOver)       |             choco install nuclear              |
| GURU (Gentoo)  | https://github.com/gentoo/guru/tree/master/media-sound/nuclear-bin |                         Orphaned                          |               emerge nuclear-bin               |
| Homebrew (Mac) |               https://formulae.brew.sh/cask/nuclear                |                         Homebrew                          |          brew install --cask nuclear           |
|      Snap      |                    https://snapcraft.io/nuclear                    |            [nukeop](https://github.com/nukeop)            |           sudo snap install nuclear            |
|    Flatpak     |      https://flathub.org/apps/details/org.js.nuclear.Nuclear       |            [nukeop](https://github.com/nukeop)            | flatpak install flathub org.js.nuclear.Nuclear |
|   Void Linux   |       https://github.com/machadofguilherme/nuclear-template        | [machadofguilherme](https://github.com/machadofguilherme) |                   See readme                   


## Переводы от сообщества
Документация Nuclear и само приложение уже было переведено на некоторые языки, однако, мы всегда ищем людей готовых внести свой вклад и помочь нам с переводом.

Мы используем [Crowdin](https://crowdin.com/project/nuclear) для управления локализацией. Используя его, вы сможете проверить, поддерживается ли ваш язык, отслеживать прогресс локализации и сможете помогать нам переводить Nuclear на другие языки.

## Скриншоты
Скриншоты будут дополняться по мере развития проекта

![Поиск по альбому](https://i.imgur.com/idFVnAF.png)

![Отображение альбома](https://i.imgur.com/Kvzo3q7.png)

![Вид страницы исполнителя](https://i.imgur.com/imBLYl3.png)

![Раздел, показывающий лучшую новую музыку](https://i.imgur.com/bMDrR4M.png)

![Раздел с жанрами](https://i.imgur.com/g0aCmKx.png)

![Вид плейлиста](https://i.imgur.com/2VMXHDC.png)

![Просмотр текста песни](https://i.imgur.com/7e3DJKJ.png)

![Вид эквалайзера](https://i.imgur.com/WreRL0w.png)

## Лицензия

Эта программа является свободным программным обеспечением: вы можете распространять ее и / или изменять в соответствии с условиями GNU Affero General Public License, опубликованной Фондом свободного программного обеспечения, либо версией 3 Лицензии, либо (по вашему выбору) любой более поздней версии.

## Атрибуты
Использование данных SponsorBlock лицензировано в соответствии с [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) на https://sponsor.ajay.app/.