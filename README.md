<p align="center"> <img alt="Frontier Station 14" width="300" height="300" src="https://raw.githubusercontent.com/wild-space-ua/wild-space-monolith/5ea44484506122170e6d05b105fdbbe46b1cb0ed/Resources/Textures/_WildSpace/Logo/logo.png?raw=true" /></p>

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

Перегляньте хедери REUSE для отримання детальної інформації про ліцензії для кожного файлу та конкретні ліцензії, на умовах яких надаються матеріали. Загалом, репозиторій ліцензовано за GNU Affero General Public License version 3.0.

За замовчуванням оригінальний код, доданий до кодової бази Monolith після коміту 04d8ce483f638320d1b85a7aaacdf01442757363, розповсюджується за ліцензією Mozilla Public License версії 2.0 без Додатка B. Див. файл `LICENSE-MPL.txt`.

Матеріали, додані до цього репозиторію після коміту 2fca06eaba205ae6fe3aceb8ae2a0594f0effee0, ліцензовані за GNU Affero General Public License version 3.0, якщо не вказано інше. Див. файл `LICENSE-AGPLv3.txt`.

Матеріали, додані до цього репозиторію до коміту 2fca06eaba205ae6fe3aceb8ae2a0594f0effee0, розповсюджуються за ліцензією MIT, якщо не вказано інше. Див. файл `LICENSE-MIT.txt`.


[2fca06eaba205ae6fe3aceb8ae2a0594f0effee0](https://github.com/new-frontiers-14/frontier-station-14/commit/2fca06eaba205ae6fe3aceb8ae2a0594f0effee0) було опубліковано 1 липня 2024 року о 16:04 за UTC

Більшість матеріалів ліцензовано за ліцензією [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/), якщо не вказано інше. Інформація про ліцензію та авторські права на матеріали міститься у файлі метаданих. [Приклад](https://github.com/space-wizards/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).

Зверніть увагу, що деякі матеріали ліцензовані за некомерційною ліцензією [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) або аналогічними некомерційними ліцензіями, і їх необхідно буде видалити, якщо ви бажаєте використовувати цей проєкт у комерційних цілях.
