# LethalPresentsExperimental
Small tweak to the original mod LethalPresents. Even when opening a present outside now "inside" enemies can spawn from the gift also.

# Configuration
In your BepInEx/config/LethalPresents.cfg the following options are present:

`SpawnChance`, to configure the probability of enemies spawning;

`EnemyBlocklist`, list of enemies to remove from the spawn pool, see game logs for available options;

`IsAllowlist`, turns blocklist into allowlist, so that only enemies from that list can spawn. Spawned enemies are still filtered by map and inside/outside, so make sure to provide at least one entry for factory, mantion and outside;

`ShouldSpawnMines`, to enable/disable spawning of the mines;

`ShouldSpawnTurrets`, to enable/disable spawning of the turrets.

# Releases

### 1.0.0
* Initial release

## Credits to the original mod https://thunderstore.io/c/lethal-company/p/Azim/LethalPresents/