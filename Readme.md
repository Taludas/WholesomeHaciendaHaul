# The Wholesome Hacienda Haul 

This is a modular overhaul of the DLC10 Seeds of Change which touches nearly every aspect of newly introduced gameplay into the sandbox mod. Pick and choose which changes you like the most!

## German Description/Deutsche Beschreibung: 
[Hier](https://drive.google.com/file/d/1XuLAhn64quZtXhRGoY9ycfVPHxAzi_4x/view?usp=sharing) findet Ihr die deutsche Beschreibung der Mod mit allen Inhalten und Changelogs.

**I HIGHLY SUGGEST TO LOAD THE GAME UPWITH A PRE-DLC10 SAVE FOR COMPATIBILITY!**

**Remove all older versions of this mod. If you remove modules mid play through you might get funny results.**

## Changelog: 

### Patch-Notes Version 1.2

* Adjustments for compatibility with Burrito Boom
* New Hacienda Town Hall added to Extended Hacienda module
* Vanilla Guildhouse and Town Hall with Hacienda Decal added (variations)
* Production time of fertilizer left at 1:30 after GU14.1, internal storage reduced to 2 tons to limit the range of the carts
      
* Bugfixes:
 - Hacienda farms Banana, Cotton and Tobacco no longer need fertilities on the island in the Basic Gameplay Changes variant.
 - Chewing gum buildings (cinnamon orchard and chemical factory) now unlock at 2000 Obreros, not only the production chain. (Before you had to build the skyscrapers first to unlock these buildings.)
 - Visual bugs at the Extended Hacienda Guildhouse fixed: Foreman no longer bugs through the floor and a flag is rotated.
 - Chewing gum is now only demanded from 2000 Obreros. Previously 1500, the problem here was that the production chain was  uncovered at 1500 and unlocked at 2000.
 - Reset all changes to the internal stock to vanilla value, as the calculation of the transporter range depends proportionally on this. As a result, the Hacienda spice farm, for example, had a range of 125 tiles on stone roads in the extended version, which effectively covered the entire island, so that the hot sauce breweries were almost always approached directly, even if they were at the other end of the island. Now all farms have a range on stone roads of 25 tiles, as in Vanilla.
 - Positions of the Hacienda banana, cotton and tobacco farms in the Workforce Boost menu adjusted.
 - InfoDescription for various ConstructionCategories added and fixed for Hacienda Warehouse
 - Default decal skin for public buildings set to vanilla, so you always have to press Ctrl+V (or your hotkey for that) to switch the decal to Hacienda Ground
 - police and church as well as guildhouse now cause Mercier to react accordingly when they are built
 - locked all new relevant buildings for AI to prevent them from getting stuck
 - Hacienda Main Buidling added to the Influence Investment "Optimisation" AssetPool

### Patch Notes Version 1.1.2

* Hotfix for all Localisations except English. Sorry for the inconvienence, I accidentally zipped up older texts files for the other languages.

### Patch Notes Version 1.1.1

* Just some small bugfixes:
 - Obrero Residences can't be copied any longer. If selected with the Copy Tool, corresponding Jornalero residences will be used.
 - Fixed a Typo in the German Localisation: Banenen -> Bananen 

### Patch Notes Version 1.1

Upon popular demand, I decided to split the mod into modules. **ALL** Modules require the Base Module to be inside your mod folder. All other modules are optional. Following is a brief overview about each modules features:

Pick and choose what ever combination is your favourite :D

* Base:

 - New separate build menu for all Hacienda buildings
 - New Icons for all Hacienda Modules for easier identification and accessibility
 - Hacienda Streets now unlimited and working like normal streets
 - Hacienda Farms with Plantains, Cotton, Tobacco (no fertility required) and split recipe book for NW and OW farms
 - Obrero Residences must be upgraded from Jornalero ones
 - Public buildings with Hacienda Grounddecal variation
 - Bugfixes

* BasicGameplay changes:

 - Radius of the Hacienda now up to 80
 - Fertiliser Factory got buffed and hasn’t to be build inside the Hacienda Radius

* ExtendedHacienda by Lordys:
Thanks to Lordys we now have a variety of new Hacienda specific buildings:

 - Small Marketstands → Satisfy need of Hacienda for Residences in its range
 - Small Jornalero and Obrero Residences (2x3) → 8/\[12\] and 13/\[20\] pop
 - Hacienda Chapel → Satisfies Chapel Need
 - Hacienda Fire Station, Hacienda Police Station → Two resolver units each and slightly higher coverage
 - Hacienda Trade Union → Radius 20! Costs 50 Obrero Worforce though
 - Hacienda Border Wall Semi-Automatic and manual → read below!
 - One quick word on the topic of the semi-automatic outer wall. Since the Anno Code only allows for ornaments to be in the middle of the decal to snap automatically into the right place, I had to use a trick. You have to build a two tile wide corridor of wall first. Afterwards you can safely delete the inner circle and the outer one will stay connected the right way!

* ExtendedGameplay changes:
 - Hacienda Warehouse now up to 100 tons of storage and TWO transporter
 - Hacienda residences have been overhauled completely (see below)
 - Fertilities mater again (see below)
 - Hacienda Breweries: checked and adjusted (see below)

* PolicyOverhaul:
 - Hacienda Policies completely replaced and rebalanced (see below)


## Initial Mod Description with feature overview.
**Please remember to always check the Changelog to see the new or changed features.**

Dear Ubi Team, dear Annoholic community.

This is my version of DLC10 Seeds of Change as I have envisioned it to be from the first moment I saw gameplay. Unfortunately the initial release left me and many other members of the community behind their expectations. I conducted a research of the most wanted changes and modded it into the game. This is the list of features:

### New separate build menu for all Hacienda buildings
Why exactly do we need to build every Hacienda building from within the Hacienda menu. This means most of the time, scrolling, then one click for the main building, one click on the modules icon, one click on the desired building. Or using the pipette for recipe buildings and then change the recipe afterwards. That’s really complicated. So, to solve this issue I created a separate build menu entry dedicated to only Hacienda buildings. Everything can be build from their.

- Hacienda street tiles are now directly accessible
- New building categories for OW and NW farms
- New building category for the Hacienda Breweries
- New building category for all Hacienda Ornaments.

### New Icons for all Hacienda Modules for easier identification and accessibility
The Icons of the Hacienda Modules lack distinctive features and contrast, it is really hard to tell them apart. So everyone got a new and distinct looking icon.

### Hacienda Streets now unlimited and working like normal streets
The Hacienda Streets have been limited to 250 tiles combined for an unknown reason. No longer! Each module is now separate and works like a normal street. Unfortunately they can’t be build over Train Tracks or Rivers, so please use a normal paved street instead (Or use Muggenstuermer's ["City Ornaments"](https://www.nexusmods.com/anno1800/mods/93?tab=description)). To balance this, I increased the building costs to 1 Brick per tile.

### Radius of the Hacienda now up to 80
The vanilla radius of the Hacienda was just to small to effectively use them for houses and breweries and farms and fertiliser factories. I increased the maximum range to 80 starting at 15. To give an extra incentive to build population inside the Hacienda radius, the last two steps are reserved for hitting 7500 and 10000 population (+5 on the radius each time). To accommodate the new radius, the distance over which the Hacienda provides its Public Service to houses has been increased as well. You should be able to easily fit residences at the outer parts of the radius if using paved streets (or Hacienda Plaza).

### Hacienda Warehouse now up to 100 tons of storage and two transporter
The vanilla Hacienda Warehouse hasn’t a real value over the normal Depots inside the harbour area, as they even use up precious land space. So I gave them a new task with adding two transporter ramps to them and increasing the storage space to 100 tons. This comes at a cost though. The can only be build inside the Hacienda radius and they’ll cost you 50 Obrero Workforce each! They should only act as a support to regular warehouses.

### Hacienda residences have been overhauled completely
- Jornalero residences now take up to 30 Population each. Their needs have been left unchanged, but an extra incentive has been given to the two new goods Schnaps and Hot Sauce by increasing the amount of gained inhabitants.
- The next big change is that Obrero residences can’t be build separately any longer. You’ll need to upgrade your Jornalero residences for 5 Timber and 10 Bricks. 
- For the Obrero Residences, they now get 3 points of attractiveness by default to help you reach the required amounts of it to unlock the Hacienda policies. Their inhabitant count has been lifted to 55. An extra incentive was given to the new products Hot Sauce and Atole as well as the newly introduced needs to get from 45 to 55 Obreros: Chewing Gum and Violins unlocked at 1500 and 2000 Obreros respectively to further strengthen the role incentive to build those production lines in later game. 
- To accommodate the changed needs, population boosting items like Saint D’Artois and Papal Paper now give extra residents from Hot Sauce as well as Chewing gums and Violins to promote not only NW usage of these goods but also the supply of Violins and Chewing gum to Engineer and Investor Skyscrapers, as those productions are not really space efficient for the amount of inhabitants they give.

### Fertiliser Factory got buffed and hasn’t to be build inside the Hacienda Radius
The vanilla fertiliser production chain didn’t really convince me. I mean 5 min for 1 t of fertiliser so that you can supply one farm with it? Seriously? Not any more:
- Production time of the Fertiliser Factory has been lifted to 90 seconds. At the same time, the buff for the animal farms has been reduced to 1/10 instead of 1/3. Now you have to build 3 Animal farms at 110% to supply one unboosted Fertiliser Factory instead of a one to three ratio as before. The Fertiliser Factory also doesn’t need to be build inside the Hacienda radius any more, because I think most of us don’t wanna wake to the smell of poop every day, would we?
- A bugfix for the Fertiliser Silo in Enbesa not using the Wanza Wood and Mud Bricks is included as well.

### Hacienda Farms: 4 new crop types and fertilities mater again
Why exactly is it that the Devs left out the three crops Bananas, Cotton and Tobacco? Well, I theorize that the recipe book has no more space than to fit 8 recipes at the current scale of each item on the list. So they told their art team to design all crop farms for the New World fertilities and then dumped the ones nobody likes - because of balancing and item game - overboard. But the graphics did survive the drip into the final game files! I spent an hour creating the Tobacco plantation until I noticed at export that there already is on! I mean wtf. I paid full price but due to a really simple UI design problem, so much content was stolen from me. Especially since the Tobacco Plantation was one of the most unused Farm in the entire game, a Hacienda version in vanilla could have made a really good opportunity to actually plant it instead of getting it as a by-product from bananas.

- So, I fixed that issue myself with a split of hacienda crop farms into two buildings, New World Hacienda Crop Farms including the long lost Banana, Cotton and Tobacco Plantations and OW Hacienda Crop Farms plus spices and *drum role please* a Vineyard! More on that later.

- The recipe books are now split as well, so watch out for that. All farms have been checked for their production time to fit vanilla ~~and got their internal storage increased to 5 to ease out logistic problems from to many farms being crammed together inside the Hacienda radius~~. Since the importance of the Hot Sauce is increased drastically, Spice Farm production cycle was set to 120 seconds, so that supply becomes a bit more of a challenge. Another big change is that all New World Crop Farms and the Vineyard now require the corresponding fertility on the island. I don’t get it why such an old feature of the Anno series should now be dropped entirely.

- Farms and recipes are now locked to begin with. Now more Cocoa or Coffee Plantations if your residents don’t require the appropriate finished Product. This should ease the new player starting with a new savegame to have a little bit of visible progress.

- Hacienda Breweries: checked and adjusted. I adjusted the negative impact on Attractiveness by Hacienda Breweries to -5 to help with the unlock of all Hacienda policies ~~as well as adjusting all their internal storage to 5 as well~~. The building costs were raised to 10 Timber and 15 Bricks. The production time of the Hot Sauce Brewery was lowered to 60 seconds for above stated reasons of balancing the newly popular need vs the amount of pop you get from it. Breweries and their recipes are now locked to begin with. Now more Atole or Coffee if your residents don’t require the appropriate Product. This should ease the new player starting with a new savegame to have a little bit of visible progress.

### Support for most important Public Buildings to use the Hacienda Plaza ground decal
This one is for the beauty builders in the Community. I took every major public building and gave them a new variation with the Hacienda Plaza ground decal, so that you can build magnificent Hacienda Compounds with fitting Public Buildings.

Included are: Firestation, Police Station, Hospital, Chapel, Boxing Arena and all Warehouses.

### Hacienda Policies completely replaced and rebalanced
To be honest the vanilla Policies are like playing with the small scoops in Kindergarden while the bigger kids got the nice Tractors and Earthmovers. In comparison to the Palace buffs, they look nearly useless. For the fourth one you have to pay nearly the same amount into Attractiveness enhancement to break even. That’s no good game design. The Buffs from the Scenario Hacienda are way more powerful and would have fitted as well.

But as I’m more creative than that, I created 5 totally new and potentially game changing buffs for you to play around with. Now you’ll definitely consider every one of them.

- Decree 1: Clean Environment Regulation (required Attractiveness: 450)
Effects All Heavy Industries, all Mines, all Quarries, all NW Chemical Plants and all Breweries:
 * Productivity +20%
 * Chance of Fire -50%
 * Chance of Explosion -100%
 * Negative Infliction on Attractiveness -80%
 * Workforce needed +25%
 * Maintenance Costs +75%

- Decree 2: Local Factory Outlet Regulation (required Attractiveness: 700)
Effects All New World Residences:
  - Reduced Consumption of:
   * Ponchos -25%
   * Bombins-15%
   * Coffee -10%
   * Cigars -10%
   * Extra happiness from Market/Hacienda +5
   * Income -10%

Effects All Clothing Factories, all Intermediate Good Producers, Coffee Roaster and Cigar Factory:
 * Extra Goods every third Cycle (1/3)
 * Attractiveness +5%
 * Workforce needed +15%
 * Maintenance Costs -50%

- Decree 3: Lumberjack Educational Decree (required Attractiveness: 1000)
Effects All Lumberjacks and all NW Orchards
 * Productivity +15%
 * Attractiveness +10
 * Workforce needed -50%
 * Forest Density -25%
 * Extra Goods: Wanza Wood 1/7 and Cherry Wood 1/10

- Decree 4: Vineyard Promotion Act (required Attractiveness: 1750)
Effects Hacienda Vineyards
 * Extra Grapes every second cycle (+50%)
 * Grape fertility provided

- Decree 5: Transporter Modernisation Act (required Attractiveness: 2200)
Effects All NW Crop Farms and all NW Orchards
 * Replaces the standard horse drawn carriage with a modern tractor which allows for faster unloading at warehouses (5 seconds) and faster movement speed (+40%)

### Bugfixes:
- Hacienda Main Building removed from the ItemEffectTargetPool “All Hacienda Buildings” so that it can’t be boosted by Items which affect “All Production Buildings”.
- Hacienda Warehouse removed from the ItemEffectTargetPool “All Hacienda Buildings” so that it can’t be boosted by Items which affect “All Production Buildings”.
- Jornalero Hacienda Residences are now affected by the boost of the Cordillera Set in the Zoo.
- Jornalero Hacienda Residences have been removed from the ItemEffectTargetPool “All Obreros/Investors” and “All Hacienda Buildings” to not receive buffs from items like Feras or Arek.
- Obrero Hacienda Residences have been removed from the ItemEffectTargetPool “AllHacienda Buildings” to not receive buffs from items like Feras.
- Fixed a LOD issue with two of three Obrero Hacienda Residences: On one building side,suddenly windows appeared where none were visible before (LOD levels 2 and up)

### Acknowledgements
All that is left now, is to say thank you Ubisoft Mainz for a great game which I learned to love over the last 3 Years, that got me into some programming territory and self education about 3D Modelling as well as some amazing people on the Anno Mod Corner International Discord without whom this mod would have not been possible.

Special thanks to:
* Taubenangriff: For being a walking Lexikon for Anno Game Code knowledge and feedback
* Jakob: For helping me with my very first modding attempts and developing the VSCode Plugin Anno Modding Tools as well as a Texture Converter
* Lordys: Without whom I wouldn’t have ever been able to wrap my head around the function of the 3D game files and his amazing [Blender cfg Import/Export Addon](https://github.com/xormenter/Blender-Anno-.cfg-Import-Addon), he contributed all the buildings for the Hacienda Extended Module! THANK YOU :)
* JJE1000, Hackner and Pine: For feedback and constructive talks about features
* Meow for the amazing Mod Loader without this nothing of this would be possible
* lukts30: rdm4 converter
* VladiwSokow: for the idea of boosted transporters in the Arctic and how to do it

If you've read up to this point: What'll come next you ask... I plan on having a modular setup ontop of this base mod. For now only the working titles will be spoiled though:
* Module 1: The Burrito Boom
* Module 2: The Formidable Faulproof Fertiliser
* Module 3: Willis Wine World-Tour
* Module 4: The Mutile Mine Makeover
* Module 5: Sweet, salty, sour or spicy?
* Module 6: The Sounds  of Stradivari
* Module 7: The Cinematic Century Dawns

That’s all! Hope you enjoy and happy city building!