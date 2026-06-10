Medieval Fast Burglars

XML-only prototype for fast medieval burglar raids using Medieval Overhaul.

Adds:
- Three burglar pawn kinds for the Medieval Overhaul brigand faction.
- Three custom dark apparel pieces using Medieval Overhaul visuals and dark color generators.
- Biotech xenotype weighting for burglar roles when Biotech is active.
- Optional xenotype weighting for Big and Small, Joe's DnD Xenotypes, Roo's fantasy xenotypes, Alpha Genes, and House Van Illa when those mods are active.
- A brigand-only "Night burglars" raid strategy with edge-walk arrival.
- A patch that adds burglar-heavy combat groups to Medieval Overhaul brigands.
- A baseChance 0 test incident for dev-mode triggering.
- Burglar gear tags for light blades, clubs, bows, crossbows, thrown weapons, and elite thief gear.
- Optional gear patches for Tools of the Trade, VFE Medieval 2, Shard Dagger, House Van Illa, and House Ignivar.
- Optional Simple Sidearms tag maps so ranged burglars can roll light melee sidearms and melee burglars can roll light ranged/thrown sidearms when Simple Sidearms allows sidearm spawning.
- A neutral shady map seller trader kind that can appear in Medieval Overhaul noble-house caravans.
- Placeholder black-market intel items: bandit cache maps and stolen ledgers.

Gear direction:
- Common burglars favor daggers, cleavers, hatchets, falchions, clubs, hunting bows, crossbows, and thrown weapons.
- Better burglars can rarely pull rapiers, fencing swords, arming swords, stronger crossbows, war bows, and small fantasy-flavored weapons.
- Plate and heavy soldier gear are intentionally avoided so they still read as fast thieves, not line infantry.

Shady trader direction:
- The shady map seller is not hostile bandit faction content. It represents fences, brokers, and informants traveling under neutral caravan protection.
- Current stock includes cache maps, stolen ledgers, worn medieval gear, armor, textiles, medicine, drugs, food, silver, gold, and loot-tagged valuables.
- The cache map is currently a trade item and future quest hook. It does not yet open a treasure site by itself.

Texture notes:
- The apparel reuses Medieval Overhaul texture paths rather than shipping copied art.
- This keeps the mod light and avoids redistributing another mod's textures.
- Dedicated original textures can be added later under Textures/Things/Pawn/Humanlike/Apparel if desired.

XML limitation:
- This does not add real stealth, perception checks, or reliable steal-and-flee AI.
- It makes the event play as fast, lightly armed brigand raids with thief flavor.
- The test incident uses RimWorld's vanilla raid worker. XML cannot force a specific faction, raid strategy, or pawn group through the incident alone.

Testing:
- Enable dev mode.
- Open the debug actions menu.
- Use the incident/raid debug action and choose SBR_TestNightBurglars or "test night burglars".
- If the debug dialog allows choosing a faction, choose Medieval Overhaul brigands.
- If it allows points, use a small value first, around 150-300.
- To inspect individual pawn kinds, use the spawn pawn tool and search for SBR_NightCutpurse, SBR_RoofRunner, or SBR_NightFence.

Requires:
- RimWorld 1.6
- Medieval Overhaul
