# Global ragebot variables

Usage example: `config.ragebot.setRagebotMaster(true)`

`setRagebotMaster(bool bState)`

`getRagebotMaster()` returns bool

`setRagebotOnKey(bool bState)`

`getRagebotOnKey()` returns bool

`setRagebotSilent(bool bState)`

`getRagebotSilent()` returns bool

`setRagebotFov(int fov)`

`getRagebotFov()` returns int

`setRagebotAutoshoot(bool bState)`

`getRagebotAutoshoot()` returns bool

`setRagebotAutoscope(bool bState)`

`getRagebotAutoscope()` returns bool

`setRagebotResolver(bool bState)`

`getRagebotResolver()` returns bool

`setZeusbotEnable(bool bState)`

`getZeusbotEnable()` returns bool

`setZeuschance(int chance)`

`getZeuschance()` returns bool

`setKnifebot(bool bState)` 

`getKnifebot()` returns bool

`setDtTeleport(bool bState)`

`getDtTeleport()` returns bool

# Weapon group variables

`setRagebotWeaponMaster(bool bState, int weaponIdx)` enable weapon config: 0=Default 1=Autosniper 2=Scout 3=AWP 4=Rifles 5=Pistols 6=Heavy Pistols

Usage example: `config.ragebot.setRagebotWeaponMaster(true, 1)` enables ragebot config override for Autosnipers

`getRagebotWeaponMaster(int weaponIdx)` returns bool

`setRagebotWeaponHitchance(int hitchance, int weaponIdx)`

`getRagebotWeaponHitchance(int weaponIdx)` returns int

`setRagebotWeaponDTHitchance(int hitchance, int weaponIdx)`

`getRagebotWeaponDTHitchance(int weaponIdx)` returns int

`setRagebotWeaponMinDmg(int minDamage, int weaponIdx)`

`getRagebotWeaponMinDmg(int weaponIdx)` returns int

`setRagebotWeaponMinDmgOverride(int minDamage, int weaponIdx )`

`getRagebotWeaponMinDmgOverride(int weaponIdx )`

`setRagebotWeaponAutostopMode(int mode, int weaponIdx)` modes: 0 = off, 1 = normal, 2 = quickstop, 3 = predictive stop

`getRagebotWeaponAutostopMode(int weaponIdx)` returns int

`setRagebotWeaponHitboxEnabled(bool enable, int hitboxIdx, int weaponIdx)` hitboxes 0-11

`getRagebotWeaponHitboxEnabled(int hitboxIdx, int weaponIdx)` returns bool

`setRagebotWeaponStaticScale(bool scale, int weaponIdx)`

`getRagebotWeaponStaticScale(int weaponIdx)` return bool

`setRagebotWeaponBodyScale(int scale, int weaponIdx)`

`getRagebotWeaponBodyScale(int weaponIdx)`

`setRagebotWeaponHeadScale(int scale, int weaponIdx)`

`getRagebotWeaponHeadScale(int weaponIdx)` returns int

`setRagebotWeaponMaxMisses(int misses, int weaponIdx)`

`setRagebotWeaponMaxMisses(int weaponIdx)` returns int

`setRagebotWeaponPreferSafe(bool bState, int weaponIdx)`

`getRagebotWeaponPreferSafe(int weaponIdx)` return bool
