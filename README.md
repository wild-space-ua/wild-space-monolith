<p align="center"> <img alt="Frontier Station 14" width="880" height="300" src="https://raw.githubusercontent.com/Monolith-Station/Monolith/89d435f0d2c54c4b0e6c3b1bf4493c9c908a6ac7/Resources/Textures/_Mono/Logo/logo.png?raw=true" /></p>

Дикий Космос це форк [Monolith Station](https://github.com/Monolith-Station/Monolith) який використовує двигун [Robust Toolbox](https://github.com/space-wizards/RobustToolbox), написаний на C#.

<!-- ## Links

//[Discord](https://discord.gg/mxY4h2JuUw) | [Steam](https://store.steampowered.com/app/1255460/Space_Station_14/) -->

## Долучитися до розробки

Ми з радістю готові приймати нові правки до коду від будь-кого. Приєднайтеся до нас у Діскорді, якщо ви хочете отримати допомоги. Не бійтеся питати про допомогу!

Також, ми приймаємо переклади гри у наш форк, і наразі працюємо над тим аби зробити репозиторій доступний на Weblate.

## Збірка

Загальну інформацію щодо налаштування середовища розробки дивіться у [посібнику Space Wizards](https://docs.spacestation14.com/en/general-development/setup/setting-up-a-development-environment.html), але майте на увазі, що Einstein Engine відрізняється від Wizden, і багато рекомендацій можуть бути неактуальними.
Щоб полегшити вам роботу, ми пропонуємо кілька скриптів, наведених нижче.

### Залежності збірки

> - Git
> - .NET SDK 10.0


### Windows

> 1. Клонуйте цей репозиторій
> 2. Запустіть `Scripts/bat/updateEngine.bat` у терміналі, аби завантажити двигун
> 3. Запустіть `Scripts/bat/buildAllDebug.bat` після внесення будь-яких змін у код
> 4. Запустіть `Scripts/bat/runQuickAll.bat` аби запустити клієнт та сервер
> 5. Connect to localhost in the client and play

### Linux

> 1. Клонуйте цей репозитоій
> 2. Запустіть `Scripts/sh/updateEngine.sh` у терміналі, аби завантажити двигун
> 3. Запустіть `Scripts/sh/buildAllDebug.sh` після внесення будь-яких змін у код
> 4. Запустіть `Scripts/sh/runQuickAll.sh` аби запустити клієнт та сервер
> 5. У клієнті, підключайтеся до localhost та грайте

## Ліцензія

See the REUSE headers for detailed licensing information for each file for the specific licenses contributions are made under. The work as a whole is licensed under GNU Affero General Public License version 3.0.

By default, original code contributed to the Monolith codebase after 04d8ce483f638320d1b85a7aaacdf01442757363 is under Mozilla Public License version 2.0 with Exhibit B removed. See `LICENSE-MPL.txt`.

Content contributed to this repository after commit 2fca06eaba205ae6fe3aceb8ae2a0594f0effee0 is licensed under the GNU Affero General Public License version 3.0, unless otherwise stated. See `LICENSE-AGPLv3.txt`.

Content contributed to this repository before commit 2fca06eaba205ae6fe3aceb8ae2a0594f0effee0 is licensed under the MIT license, unless otherwise stated. See `LICENSE-MIT.txt`.


[2fca06eaba205ae6fe3aceb8ae2a0594f0effee0](https://github.com/new-frontiers-14/frontier-station-14/commit/2fca06eaba205ae6fe3aceb8ae2a0594f0effee0) was pushed on July 1, 2024 at 16:04 UTC

Most assets are licensed under [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) unless stated otherwise. Assets have their license and the copyright in the metadata file. [Example](https://github.com/space-wizards/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).

Note that some assets are licensed under the non-commercial [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) or similar non-commercial licenses and will need to be removed if you wish to use this project commercially.
