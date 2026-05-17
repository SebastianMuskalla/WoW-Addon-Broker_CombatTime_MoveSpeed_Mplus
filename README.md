WoW Addon: Broker_CombatTime_MoveSpeed_Mplus
============================

Broker_CombatTime_MoveSpeed_Mplus is a broker plugin (using LBD - Lib Data Broker) whose output can be displayed using a suitable addon like Bazooka (<https://www.curseforge.com/wow/addons/bazooka>).

While in combat, it shows the time you have been in combat.
After leaving a long combat (> 60 seconds, configurable via the LUA file), it reports the combat duration to your chat frame.

While out of combat, if you are not within a Mythic Plus dungeon it shows your current movement speed.
While in a Mythic Plus dungeon, it shows the current key level.

This fallback behavior was added as the current movement speed is a secret value (and hence cannot be processed by addons) if you are in combat or in a Mythic Plus dungeon.

Broker_CombatTime_MoveSpeed was written as a replacement for the deprecated addon CombatTime by oscarucb (<https://www.curseforge.com/wow/addons/combattime>).

The addon works out of the box, no configuration is needed, but if you want, some settings can be adjusted at the beginning of [Broker_CombatTime_MoveSpeed_Mplus.lua](Broker_CombatTime_MoveSpeed_Mplus.lua).

License
-------

Copyright 2019-2026 Sebastian Muskalla

This project contains free and open-source software licensed under the MIT License, see [LICENSE](LICENSE),
