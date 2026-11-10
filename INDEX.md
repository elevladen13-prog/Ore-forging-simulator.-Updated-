# Ore Sword Simulator - Index

_Updated every time something is added. Game file: ore-sword-simulator-v2.html_

## Version log
- **v1** - First playable: 4 worlds, forge, skills, tower, training stations, rebirth, Ore Tyrant boss.
- **v2** - Walk animation, particles, baked detailed maps, 12 weapon shapes, 200 weapons, 10 rarities/ores, 6 worlds, strength multiplier from owned weapons, bosses every 7 stages (summon 2 mobs), knockback away from player, autosave.
- **v3** - Mobs and bosses 2x HP and 2x damage; stage 20 world boss unlocks the next world; unlock prices 5x cheaper (must beat boss AND pay); portals replaced by a World Teleporter; glass-style transparent menus; this index file.
- **v4** - Celestial+ enchant (counts as one level of every other enchant; rare Tower drop, best from boss floors); 7th world Celestial Realm (unlocks after defeating the Ore Tyrant); Market (potions + sell ores); new skills Guard and Greed.
- **v5** - Celestial+ now boosts every enchant (including new ones: Swiftness, Fortify, Slayer) and stacks with itself (2 copies = 2.5 levels, 3 = 4.5); cleaner chip HUD with HP bar; new block textures per world; redesigned forge, shrine, rebirth altar, tower, market and teleporter models; performance fixes (HUD redraw throttled, frozen canvas while menus open, no per-frame allocations); hold Space to auto-attack.

## Worlds (base values; mobs get x2 HP and x2 damage in game)
| # | World | Unlock cost | Mob HP | Mob dmg | Coins/kill | Ores dropped |
|---|---|---|---|---|---|---|
| 1 | Verdant Meadow | 0 | 30 | 3 | 2 | Stone, Copper |
| 2 | Crystal Caves | 100 | 400 | 15 | 15 | Copper, Iron, Gold |
| 3 | Frozen Tundra | 1,000 | 3,000 | 40 | 80 | Iron, Gold, Crystal |
| 4 | Magma Depths | 10,000 | 20,000 | 120 | 400 | Gold, Crystal, Ruby, Voidstone |
| 5 | Sunken Ruins | 100,000 | 150,000 | 400 | 2,500 | Ruby, Voidstone, Mythril, Celestite |
| 6 | Void Citadel | 1,000,000 | 1,000,000 | 1200 | 15,000 | Voidstone, Mythril, Celestite, Starcore |
| 7 | Celestial Realm | 10,000,000 | 10,000,000 | 4000 | 100,000 | Mythril, Celestite, Starcore, Starcore |

Celestial Realm (world 7) needs the Ore Tyrant defeated first.
Unlock rule: beat the stage 20 boss of the previous world, then pay the cost at the Teleporter.
Bosses: mini-boss every 7th stage/floor, world boss at stage 20, final Ore Tyrant in the Void Citadel after all world bosses.

## Ores and rarities
| Tier | Ore | Rarity | Weapons |
|---|---|---|---|
| 0 | Stone | Common | 26 |
| 1 | Copper | Uncommon | 26 |
| 2 | Iron | Rare | 26 |
| 3 | Gold | Epic | 24 |
| 4 | Crystal | Legendary | 22 |
| 5 | Ruby | Elite | 20 |
| 6 | Voidstone | Defying | 18 |
| 7 | Mythril | Mythic | 14 |
| 8 | Celestite | Celestial | 10 |
| 9 | Starcore | Special | 14 |

## Weapons (200)
| # | Name | Rarity | Damage | Strength gain bonus |
|---|---|---|---|---|
| 1 | Rusty Sword | Common | 5 | +3% |
| 2 | Wooden Blade | Common | 5 | +3% |
| 3 | Plain Axe | Common | 6 | +3% |
| 4 | Dull Spear | Common | 6 | +3% |
| 5 | Simple Dagger | Common | 6 | +3% |
| 6 | Rusty Mace | Common | 6 | +3% |
| 7 | Wooden Katana | Common | 7 | +3% |
| 8 | Plain Hammer | Common | 7 | +3% |
| 9 | Dull Scythe | Common | 7 | +4% |
| 10 | Simple Trident | Common | 7 | +4% |
| 11 | Rusty Staff | Common | 8 | +4% |
| 12 | Wooden Rapier | Common | 8 | +4% |
| 13 | Plain Sword | Common | 8 | +4% |
| 14 | Dull Blade | Common | 8 | +4% |
| 15 | Simple Axe | Common | 9 | +4% |
| 16 | Rusty Spear | Common | 9 | +4% |
| 17 | Wooden Dagger | Common | 9 | +4% |
| 18 | Plain Mace | Common | 9 | +4% |
| 19 | Dull Katana | Common | 10 | +4% |
| 20 | Simple Hammer | Common | 10 | +4% |
| 21 | Rusty Scythe | Common | 10 | +4% |
| 22 | Wooden Trident | Common | 10 | +4% |
| 23 | Plain Staff | Common | 11 | +4% |
| 24 | Dull Rapier | Common | 11 | +4% |
| 25 | Simple Sword | Common | 11 | +4% |
| 26 | Rusty Blade | Common | 11 | +5% |
| 27 | Bronze Sword | Uncommon | 15 | +6% |
| 28 | Sturdy Blade | Uncommon | 16 | +6% |
| 29 | Keen Axe | Uncommon | 17 | +6% |
| 30 | Hardened Spear | Uncommon | 17 | +6% |
| 31 | Forged Dagger | Uncommon | 18 | +7% |
| 32 | Bronze Mace | Uncommon | 19 | +7% |
| 33 | Sturdy Katana | Uncommon | 20 | +7% |
| 34 | Keen Hammer | Uncommon | 20 | +7% |
| 35 | Hardened Scythe | Uncommon | 21 | +7% |
| 36 | Forged Trident | Uncommon | 22 | +7% |
| 37 | Bronze Staff | Uncommon | 23 | +7% |
| 38 | Sturdy Rapier | Uncommon | 23 | +7% |
| 39 | Keen Sword | Uncommon | 24 | +7% |
| 40 | Hardened Blade | Uncommon | 25 | +8% |
| 41 | Forged Axe | Uncommon | 26 | +8% |
| 42 | Bronze Spear | Uncommon | 26 | +8% |
| 43 | Sturdy Dagger | Uncommon | 27 | +8% |
| 44 | Keen Mace | Uncommon | 28 | +8% |
| 45 | Hardened Katana | Uncommon | 29 | +8% |
| 46 | Forged Hammer | Uncommon | 29 | +8% |
| 47 | Bronze Scythe | Uncommon | 30 | +8% |
| 48 | Sturdy Trident | Uncommon | 31 | +9% |
| 49 | Keen Staff | Uncommon | 32 | +9% |
| 50 | Hardened Rapier | Uncommon | 32 | +9% |
| 51 | Forged Sword | Uncommon | 33 | +9% |
| 52 | Bronze Blade | Uncommon | 34 | +9% |
| 53 | Steel Sword | Rare | 40 | +9% |
| 54 | Silver Blade | Rare | 42 | +9% |
| 55 | Azure Axe | Rare | 44 | +9% |
| 56 | Jade Spear | Rare | 46 | +10% |
| 57 | Gilded Dagger | Rare | 48 | +10% |
| 58 | Steel Mace | Rare | 50 | +10% |
| 59 | Silver Katana | Rare | 52 | +10% |
| 60 | Azure Hammer | Rare | 54 | +10% |
| 61 | Jade Scythe | Rare | 56 | +10% |
| 62 | Gilded Trident | Rare | 58 | +11% |
| 63 | Steel Staff | Rare | 60 | +11% |
| 64 | Silver Rapier | Rare | 62 | +11% |
| 65 | Azure Sword | Rare | 64 | +11% |
| 66 | Jade Blade | Rare | 66 | +11% |
| 67 | Gilded Axe | Rare | 68 | +12% |
| 68 | Steel Spear | Rare | 70 | +12% |
| 69 | Silver Dagger | Rare | 72 | +12% |
| 70 | Azure Mace | Rare | 74 | +12% |
| 71 | Jade Katana | Rare | 76 | +12% |
| 72 | Gilded Hammer | Rare | 78 | +12% |
| 73 | Steel Scythe | Rare | 80 | +13% |
| 74 | Silver Trident | Rare | 82 | +13% |
| 75 | Azure Staff | Rare | 84 | +13% |
| 76 | Jade Rapier | Rare | 86 | +13% |
| 77 | Gilded Sword | Rare | 88 | +13% |
| 78 | Steel Blade | Rare | 90 | +14% |
| 79 | Arcane Sword | Epic | 100 | +12% |
| 80 | Frost Blade | Epic | 105 | +12% |
| 81 | Ember Axe | Epic | 110 | +13% |
| 82 | Storm Spear | Epic | 115 | +13% |
| 83 | Shadow Dagger | Epic | 120 | +13% |
| 84 | Arcane Mace | Epic | 125 | +13% |
| 85 | Frost Katana | Epic | 130 | +13% |
| 86 | Ember Hammer | Epic | 135 | +14% |
| 87 | Storm Scythe | Epic | 140 | +14% |
| 88 | Shadow Trident | Epic | 145 | +14% |
| 89 | Arcane Staff | Epic | 150 | +14% |
| 90 | Frost Rapier | Epic | 155 | +15% |
| 91 | Ember Sword | Epic | 160 | +15% |
| 92 | Storm Blade | Epic | 165 | +15% |
| 93 | Shadow Axe | Epic | 170 | +15% |
| 94 | Arcane Spear | Epic | 175 | +16% |
| 95 | Frost Dagger | Epic | 180 | +16% |
| 96 | Ember Mace | Epic | 185 | +16% |
| 97 | Storm Katana | Epic | 190 | +16% |
| 98 | Shadow Hammer | Epic | 195 | +17% |
| 99 | Arcane Scythe | Epic | 200 | +17% |
| 100 | Frost Trident | Epic | 205 | +17% |
| 101 | Ember Staff | Epic | 210 | +17% |
| 102 | Storm Rapier | Epic | 215 | +18% |
| 103 | Radiant Sword | Legendary | 250 | +15% |
| 104 | Dragon Blade | Legendary | 263 | +15% |
| 105 | Titan Axe | Legendary | 275 | +16% |
| 106 | Phoenix Spear | Legendary | 288 | +16% |
| 107 | Solar Dagger | Legendary | 300 | +16% |
| 108 | Radiant Mace | Legendary | 313 | +17% |
| 109 | Dragon Katana | Legendary | 325 | +17% |
| 110 | Titan Hammer | Legendary | 338 | +17% |
| 111 | Phoenix Scythe | Legendary | 350 | +17% |
| 112 | Solar Trident | Legendary | 363 | +18% |
| 113 | Radiant Staff | Legendary | 375 | +18% |
| 114 | Dragon Rapier | Legendary | 388 | +18% |
| 115 | Titan Sword | Legendary | 400 | +19% |
| 116 | Phoenix Blade | Legendary | 413 | +19% |
| 117 | Solar Axe | Legendary | 425 | +19% |
| 118 | Radiant Spear | Legendary | 438 | +20% |
| 119 | Dragon Dagger | Legendary | 450 | +20% |
| 120 | Titan Mace | Legendary | 463 | +20% |
| 121 | Phoenix Katana | Legendary | 475 | +20% |
| 122 | Solar Hammer | Legendary | 488 | +21% |
| 123 | Radiant Scythe | Legendary | 500 | +21% |
| 124 | Dragon Trident | Legendary | 513 | +21% |
| 125 | Brutal Sword | Elite | 600 | +18% |
| 126 | Crimson Blade | Elite | 630 | +18% |
| 127 | Warlord Axe | Elite | 660 | +19% |
| 128 | Cursed Spear | Elite | 690 | +19% |
| 129 | Obsidian Dagger | Elite | 720 | +19% |
| 130 | Brutal Mace | Elite | 750 | +20% |
| 131 | Crimson Katana | Elite | 780 | +20% |
| 132 | Warlord Hammer | Elite | 810 | +21% |
| 133 | Cursed Scythe | Elite | 840 | +21% |
| 134 | Obsidian Trident | Elite | 870 | +21% |
| 135 | Brutal Staff | Elite | 900 | +22% |
| 136 | Crimson Rapier | Elite | 930 | +22% |
| 137 | Warlord Sword | Elite | 960 | +22% |
| 138 | Cursed Blade | Elite | 990 | +23% |
| 139 | Obsidian Axe | Elite | 1,020 | +23% |
| 140 | Brutal Spear | Elite | 1,050 | +23% |
| 141 | Crimson Dagger | Elite | 1,080 | +24% |
| 142 | Warlord Mace | Elite | 1,110 | +24% |
| 143 | Cursed Katana | Elite | 1,140 | +25% |
| 144 | Obsidian Hammer | Elite | 1,170 | +25% |
| 145 | Defiant Sword | Defying | 1,500 | +21% |
| 146 | Abyssal Blade | Defying | 1,575 | +21% |
| 147 | Rift Axe | Defying | 1,650 | +22% |
| 148 | Fatebreak Spear | Defying | 1,725 | +22% |
| 149 | Oblivion Dagger | Defying | 1,800 | +23% |
| 150 | Defiant Mace | Defying | 1,875 | +23% |
| 151 | Abyssal Katana | Defying | 1,950 | +24% |
| 152 | Rift Hammer | Defying | 2,025 | +24% |
| 153 | Fatebreak Scythe | Defying | 2,100 | +24% |
| 154 | Oblivion Trident | Defying | 2,175 | +25% |
| 155 | Defiant Staff | Defying | 2,250 | +25% |
| 156 | Abyssal Rapier | Defying | 2,325 | +26% |
| 157 | Rift Sword | Defying | 2,400 | +26% |
| 158 | Fatebreak Blade | Defying | 2,475 | +27% |
| 159 | Oblivion Axe | Defying | 2,550 | +27% |
| 160 | Defiant Spear | Defying | 2,625 | +27% |
| 161 | Abyssal Dagger | Defying | 2,700 | +28% |
| 162 | Rift Mace | Defying | 2,775 | +28% |
| 163 | Mythic Sword | Mythic | 3,500 | +24% |
| 164 | Ancient Blade | Mythic | 3,675 | +25% |
| 165 | Eternal Axe | Mythic | 3,850 | +25% |
| 166 | Sovereign Spear | Mythic | 4,025 | +25% |
| 167 | Primal Dagger | Mythic | 4,200 | +26% |
| 168 | Mythic Mace | Mythic | 4,375 | +26% |
| 169 | Ancient Katana | Mythic | 4,550 | +27% |
| 170 | Eternal Hammer | Mythic | 4,725 | +27% |
| 171 | Sovereign Scythe | Mythic | 4,900 | +28% |
| 172 | Primal Trident | Mythic | 5,075 | +28% |
| 173 | Mythic Staff | Mythic | 5,250 | +29% |
| 174 | Ancient Rapier | Mythic | 5,425 | +29% |
| 175 | Eternal Sword | Mythic | 5,600 | +30% |
| 176 | Sovereign Blade | Mythic | 5,775 | +30% |
| 177 | Celestial Sword | Celestial | 8,000 | +27% |
| 178 | Astral Blade | Celestial | 8,400 | +28% |
| 179 | Lunar Axe | Celestial | 8,800 | +28% |
| 180 | Seraph Spear | Celestial | 9,200 | +29% |
| 181 | Zenith Dagger | Celestial | 9,600 | +29% |
| 182 | Celestial Mace | Celestial | 10,000 | +30% |
| 183 | Astral Katana | Celestial | 10,400 | +30% |
| 184 | Lunar Hammer | Celestial | 10,800 | +31% |
| 185 | Seraph Scythe | Celestial | 11,200 | +31% |
| 186 | Zenith Trident | Celestial | 11,600 | +32% |
| 187 | Starfall Sword | Special | 20,000 | +50% |
| 188 | Eclipse Mace | Special | 22,000 | +55% |
| 189 | Aether Staff | Special | 24,000 | +60% |
| 190 | Worldbreaker Spear | Special | 26,000 | +65% |
| 191 | Cosmic Scythe | Special | 28,000 | +70% |
| 192 | Nebula Blade | Special | 30,000 | +75% |
| 193 | Quasar Katana | Special | 32,000 | +80% |
| 194 | Supernova Rapier | Special | 34,000 | +85% |
| 195 | Singularity Dagger | Special | 36,000 | +90% |
| 196 | Pulsar Trident | Special | 38,000 | +95% |
| 197 | Galaxy Axe | Special | 40,000 | +100% |
| 198 | Doom-Slayer | Special | 160,000 | +400% |
| 199 | Divine Sinister | Special | 140,000 | +300% |
| 200 | Gravity Hammer | Special | 150,000 | +350% |

## Armor (30)
| Name | Rarity | Defense |
|---|---|---|
| Rusty Tunic | Common | 2 |
| Wooden Plate | Common | 3 |
| Plain Aegis | Common | 3 |
| Bronze Tunic | Uncommon | 6 |
| Sturdy Plate | Uncommon | 8 |
| Keen Aegis | Uncommon | 9 |
| Steel Tunic | Rare | 15 |
| Silver Plate | Rare | 19 |
| Azure Aegis | Rare | 23 |
| Arcane Tunic | Epic | 35 |
| Frost Plate | Epic | 44 |
| Ember Aegis | Epic | 53 |
| Radiant Tunic | Legendary | 80 |
| Dragon Plate | Legendary | 100 |
| Titan Aegis | Legendary | 120 |
| Brutal Tunic | Elite | 180 |
| Crimson Plate | Elite | 225 |
| Warlord Aegis | Elite | 270 |
| Defiant Tunic | Defying | 400 |
| Abyssal Plate | Defying | 500 |
| Rift Aegis | Defying | 600 |
| Mythic Tunic | Mythic | 1000 |
| Ancient Plate | Mythic | 1250 |
| Eternal Aegis | Mythic | 1500 |
| Celestial Tunic | Celestial | 2500 |
| Astral Plate | Celestial | 3125 |
| Lunar Aegis | Celestial | 3750 |
| Starforged Tunic | Special | 6000 |
| Starforged Plate | Special | 7500 |
| Starforged Aegis | Special | 9000 |

## Systems
- **Skills (Shrine):** Power, Haste, Fortune, Vigor, Guard (defense), Greed (coins), tiers D, C, B, A, S, SS.
- **Enchants (Tower):** Sharpness, Haste, Plunder, Vampire, Giant, Might, Swiftness (move speed), Fortify (max HP), Slayer (boss damage), and **Celestial+** (adds a level of EVERY other enchant, including future ones; extra copies stack with themselves: 2 copies = 2.5 levels, 3 = 4.5; ~30% on Tower boss floors, 2% otherwise; max 5 per sword).
- **Market (hub):** Strength potion (2x training), Power potion (+50% dmg), Luck potion (2x luck), 90s each; sell ores 10 at a time.
- **Training stations:** 1.5x, 2x at rebirth 2, 4x at 5, 8x at 10, 16x at 20; also multiplied by owned-weapon strength bonuses.
- **Teleporter:** hub and every world; goes to Hub, Tower and unlocked worlds.
