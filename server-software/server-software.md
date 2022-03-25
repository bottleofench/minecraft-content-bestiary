# Таблица серверных ядер на любой вкус

### [English Version](https://github.com/bottleofench/minecraft-content-bestiary/blob/main/mods/server-software_en.md)

#### Таблица начинается с самых древних и основных ядер, заканчивая их самыми новыми апстримами. Со временем таблица будет пополняться. Также я буду очень благодарен, если вы будете предлагать новые ядра в таблицу, либо находить ошибки и о них сообщать.

#### `Форк - ядро, созданное на основе другого ядра и включающее все улучшения этого ядра (Paper - форк Spigot)`

## Обычные Vanilla ядра.

| Название ядра | Описание | Версии игры |
| --- | --- | --- |
| [Vanilla](https://getbukkit.org/download/vanilla) | Основа основ. | **∞** |
| [CraftBukkit](https://getbukkit.org/download/craftbukkit) | Самое основное, уже давно устаревшее ядро. Является полностью переписанной заменой ванильного сервера. | 1.0+ |
| [Spigot](https://getbukkit.org/download/spigot) | Форк [CraftBukkit](https://getbukkit.org/download/craftbukkit). Более оптимизированная версия. Второе по популярности во всем мире (по данным [bStats](https://bstats.org/#!). | 1.4.6+ |
| [Paper](https://github.com/PaperMC/Paper) | Форк [Spigot](https://getbukkit.org/download/spigot). Имеет при себе около 900 патчей на безумную оптимизацию, множество новых функций, фиксов дюпов и багов. Самое популярное серверное ядро в мире (по данным [bStats](https://bstats.org/#!)). | 1.8.8+ |
| [Airplane](https://airplane.gg) | Форк [Paper](https://github.com/PaperMC/Paper). Данное ядро подарило миру хороший профайлер [Flare](https://github.com/TECHNOVE/FlarePlugin) и жесткий механизм оптимизации искусственного интеллекта мобов. Поддержка данного ядра закончилась, начиная с версии 1.18. | 1.16.5 - 1.17.1 |
| [Pufferfish](https://github.com/pufferfish-gg/Pufferfish) | Форк [Paper](https://github.com/PaperMC/Paper), имеющий при себе очень хорошую стабильность и безумные патчи на оптимизацию. | 1.18+ |
| [Purpur](https://github.com/PurpurMC/Purpur) | Форк [Paper](https://github.com/PaperMC/Paper), включающий патчи [Pufferfish](https://github.com/pufferfish-gg/Pufferfish) и [Airplane](https://airplane.gg). В ядро встроено бесчисленное количество новых функций. Фактически, вы можете настроить даже самую маленькую деталь в ядре. Оптимизацией ядро не обделено. Полностью почувствовать функционал ядра можно используя [PurpurClient](https://modrinth.com/mod/purpurclient) | 1.16.5+ |
| [Patina](https://github.com/PatinaMC/Patina) | Форк [Pufferfish](https://github.com/pufferfish-gg/Pufferfish) с малой частью патчей [Jettpack](https://gitlab.com/Titaniumtown/JettPack) (мертв), а также некоторыми патчами [Yatopia](https://github.com/YatopiaMC/Yatopia) (мертва). Использовать на свой страх и риск. | 1.16.5+ |
| [SSSpigot2](https://www.mc-market.org/resources/14122/) | Платный форк [Patina](https://github.com/PatinaMC/Patina) от того же создателя. Содержит мега экспериментальные патчи на многопоточность, которые хорошо оптимизирует сервер, однако которые ломают работу многих API. Использовать на свой страх и риск. | 1.16.5+ |
| [Matter](https://github.com/plasmoapp/matter) | Форк [Pufferfish](https://github.com/pufferfish-gg/Pufferfish) от создателей [Plasmo Voice](https://modrinth.com/mod/plasmo-voice). Снабжен единственным патчем на скрытие сида мира от посторонних глаз. Также присутствует отдельная версия ядра с патчами [Purpur](https://github.com/PurpurMC/Purpur) | 1.18+ |
| [Mirai](https://github.com/etil2jz/Mirai) | Форк [Pufferfish](https://github.com/pufferfish-gg/Pufferfish) с огромной кучей разных патчей, которые могут быть крайне не стабильны. Использовать на свой страх и риск. | 1.18+ |
| [Prismarine](https://github.com/PrismarineTeam/Prismarine) | Новое никому неизвестное ядро.  Крайне не рекомендуется к использованию. | 1.18+ |

## Модовые / гибридные ядра.

| Название ядра | Описание | Версии игры |
| --- | --- | --- |
| [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/) | Классический старенький загрузчик модов. На последние версии выходит не так быстро. | 1.1+ |
| [Fabric](https://fabricmc.net/use/installer/) | Новенькая замена [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/). | 1.14+ |
| [Magma](https://magmafoundation.org) | Первое гибридное ядро в нашем списке. Основано на [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/), однако включает в себя еще и [Paper API](https://github.com/PaperMC/Paper) | 1.12.2 / 1.16.5 |
| [Mohist](https://mohistmc.com) | Аналог [Magma](https://magmafoundation.org). | 1.12.2 / 1.16.5 / 1.18.2 |
| [Sponge](https://www.spongepowered.org) | Уникальное ядро из-за того, что у него абсолютно иной API для разработчиков. Ядро не поддерживает [Spigot](https://getbukkit.org/download/spigot) плагины, однако есть версия данного ядра с поддержкой [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/). | 1.8+ |

## Прокси

| Название ядра | Описание |
| --- | --- |
| [Bungeecord](https://www.spigotmc.org/wiki/bungeecord-installation/) | Прокси-сервер, позволяющий соединять несколько Spigot-серверов в один единый комплекс серверов. |
| [Waterfall](https://github.com/PaperMC/Waterfall) | Форк [Bungeecord](https://www.spigotmc.org/wiki/bungeecord-installation/), более оптимизированный. |
| [Velocity](https://github.com/PaperMC/Velocity) | Аналог [Waterfall](https://github.com/PaperMC/Waterfall), но полностью переписанный. Не поддерживает [Bungeecord](https://www.spigotmc.org/wiki/bungeecord-installation/) плагины. |
| [SSCord](https://www.mc-market.org/resources/14562/) | Платный форк [Bungeecord](https://www.spigotmc.org/wiki/bungeecord-installation/) (~ $10). |
| [FlameCord](https://github.com/2lstudios-mc/FlameCord) | Платный форк [Waterfall](https://www.spigotmc.org/wiki/bungeecord-installation/) (~ $2.5). |

<img src="https://raw.githubusercontent.com/saboooor/fork-graph/main/img.png">
