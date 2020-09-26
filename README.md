# kolmafia-scripts
Various scripts for KoLMafia. 

## AcquireBuff
Automatically get a buff from a Kingdom of Loathing buffbot.

`svn checkout https://github.com/Rinn/kolmafia-scripts/trunk/AcquireBuff/`

### zlib Settings
* `FamiliarDrops_Enabled`: If this script is enabled. Ignored if you import the script and call familiar_swap().
* `FamiliarDrops_MinMpa`: The minimum mpa required to swap to a familiar.
* `FamiliarDrops_MinMpaItem`: Use the mall price of this item for minmpa, overrides FamiliarDrops_MinMpa if not none.
* `FamiliarDrops_AssumeWorst`: Assume the worst turn count instead of the median, not recommended.
* `FamiliarDrops_Banned`: Comma separated list of familiars to never switch to.
* `FamiliarDrops_DefaultFam`: If no familiars are found, switch to this familiar by default.

[Thread](https://kolmafia.us/showthread.php?4048-acquireBuff-Get-a-buff-from-a-buffbot])

## CreationCost
Estimate optimized creation cost for an item, similiar to internal KoLMafia acquire logic.

`svn checkout https://github.com/Rinn/kolmafia-scripts/trunk/CreationCost/`

## FamiliarDrops
Automatically get profitable drops from familiars. A script for KoLMafia.

`svn checkout https://github.com/Rinn/kolmafia-scripts/trunk/FamiliarDrops/`

### zlib Settings
* `acquireBuff_last_update`: Last time buffbot data was parsed. Internal use only do not modify.
* `acquireBuff_max_price`: Maximum meat to spend on a buff. Default 1000.
* `acquireBuff_wait_time`: Time to wait for a buffbot to respond in seconds. Default 30.
* `acquireBuff_ignore_philanthropic`: Whether to requires philanthropic (extremely low cost) buffs. Default false.

[Thread](https://kolmafia.us/showthread.php?18051-FamiliarDrops-Get-profitable-drops-from-familiars])
