# The Wholesome Hacienda Haul

![Thumbnail](https://user-images.githubusercontent.com/64583643/167893634-35b83fe1-ad75-4c35-acf5-541b7804e98d.png)

This is a modular overhaul of the DLC10 Seeds of Change which touches nearly every aspect of newly introduced gameplay into the sandbox mod. Pick and choose which changes you like the most!

Für die deutsche Version des readmes, bitte [hier](readme_german.md) klicken.

If you like this mod and want to support me, feel free to share it with your friends. You can also buy me a coffee at Ko-Fi (yes, I want to raise my coffee consume to Investor's height!)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W8L558T)

## How to use

- Automatic install using the Anno Mod Browser, available from the main menu of your Anno 1800 game.
- Either use [iModYourAnno](https://github.com/anno-mods/iModYourAnno/releases) mod manager or know [how to install mods manually](https://github.com/jakobharder/anno1800-mod-loader#mods).
- If you download the mod manually, use the archive from [GitHub releases](https://github.com/Taludas/WholesomeHaciendaHaul/releases). Don't download the whole repo!

**If you change from versions 1.x.x to version 2.0, it is extremely important to remove all older versions of this mod. The Mod is now a single mod folder and modules are disabled through editing assets.xml file or through IModYourAnno Mod Manager! If you use iModYourAnno, please notice, that you have to turn on all toggles in the Tweaking tab to get the intended 'Full Experience'!**

## Mod Images
You can find a gallery of images from my mod [here](docs/).

## Changelog
<details>
    <summary>Patch Notes Version 2.4.0</summary>

* Updates:
  - add Hacienda Mezcal Brewery
  - add Hacienda Animal Farms: Alpaca, Cattle, Nandu, Sheep, Goat, Bees
  - Policy 3 now gives extra Cherry Wood +1/7 and extra Resin +1/10 instead of Wanza Wood and Cherry Wood
  - Winery and Violin manufactory can now access "regular" Cherry Wood from the Old World before having Tier 3 skyscrapers. A new build menu for OW orchards has been added to the Investor build menu and unlocks at 2500 Obreros along with the Cherry Wood Orchard
  - add automatic translations

</details>
<details>
    <summary>Patch Notes Version 2.3.0</summary>

* Updates:
  * rework Taludas Shared Products mods into individual sub-mods
  * rebalance Hacienda Storage Room to have 2 loading ramps by default

* Fixes:
  * fix missing electricity boost on hacienda winery
</details>

<details>
    <summary>Patch Notes Version 2.2.4</summary>

* Updates:
  * update required shared mod "[Shared] Pools and Definitions" to the latest version.
  * make compatible with Jakobs gapless Artista residences & skyscrapers from "New World Cities":  New Hacienda Policy no.5 also effects gapless Artista residences & skyscrapers

* Fixes:
  * fix an issue where you could still build the Obrero and Artista Residences directly from the build menu (only on "Category" sorting) instead of needing to upgrade Jornaleros and Obreros when using the module "Residences must be upgraded"
  * fix a typo with the New ItemEffectTargetPool "All Artista Residences"
</details>

<details>
    <summary>Patch Notes Version 2.2.2</summary>

* Fixes:
  * Fixed an issue, where the Hacienda Orchid Farm had a see-through invisible wall from the inside of the main house.
  * Fixed an issue with missing Hacienda Street Modules in the buildmenu after deactivating the module "True Hacienda Streets".
  * Added a "locked warning" when trying to copy old Hacienda Street modules in a save, when using the module "True Hacienda Streets". made by @Qurila.
</details>

<details>
    <summary>Patch Notes Version 2.2.1</summary>

* Fixes:
  * Fixed an issue, where the Hacienda Herb Farm would not unlock in Sandbox mode as intended (1 Artista).

</details>

<details>
    <summary>Patch Notes Version 2.2.0</summary>

![image](https://github.com/Taludas/WholesomeHaciendaHaul/assets/64583643/422a3cf1-2463-413c-9da3-bb5005e14364)

* Additions:
  * New Hacienda Farms for Herbs and Orchids!
  * Adjustments for all mods to the new features of iModYourAnno v0.5 (new images, default options are toggled automatically in the tweaking tab). ***WARNING***: Adjust your Tweaking options in iMYA before you continue playing, because those will be lost after update to v0.5!

* Fixes:
  * Fixed an issue, where on deactivation of the "Residences must be upgraded" mod module, you had no option to build the Obrero and Artista Hacienda residences from the new build menu.

</details>

<details>
    <summary>Patch Notes Version 2.1.0</summary>

* New Features:
    - relocated the Free Farmfield Placement Mod to [Gameplay Mods Collection](https://github.com/Taludas/GameplayModsCollection). It is a standalone mod and will be handled as such in future.
    - made whole mod even more customizable. With iMYA it is now possible to disable whole parts of the mod. Each module is now completely independent from one another (but I still suggest to enable all features, it will grant you with the best synergy, f.e. Policies mod and Hacienda Winery.) You will always get the basics, like the separate buildmenu.
    - added Russion Translation, provided by @DrD_AVEL
* Bugfixes:
    - Removed some customization options, that are no longer required, like the toggle to switch on electricity in the Hacienda Breweries.
</details>

<details>
    <summary>Patch Notes Version 2.0.1</summary>

* New Feature:
    - made Hacienda Fertilizer Works electrifiable with toggle in iMYA
* Bugfixes:
    - English Description for Policy 4 fixed
    - fixed displayed and active buff for Hacienda Policy 4 (missing 2x3 Artista Houses and generell mess-up with the grape farm and winery)
    - fixed Chewing Gum and Violins needs to appear after Sewing Machines in Needs Tab
    - Fix Bug with invisible Hacienda ground decal for Hacienda Hospital
    - Fix costume maker and bombin weaver missing in Hacienda Policy 2
</details>

<details>
    <summary>Patch Notes Version 2.0</summary>

* New features:
    - Major overhaul of the mod structure. The mod now consists of a single mod folder to be installed manually or via iModYourAnno. Please make sure to remove all older mod folders of this mod. This process should be savegame compatible.
    - Modularity: If you remove certain features of this mod, you can open the included asset.xml file and remove single modules via deleting single <include>-Commands. There is a little description in the assets file to tell you what the module does.
    - Tweaking: This mod now supports tweaking via iModYourAnno Mod Manager. No need to tinker with the assets files yourself. Just open the 'Tweaking' tab and see what can be changed. You can tweak many number values to your liking, f.e. the Hacienda radius or the production time of certain production buildings. You can also disable whole mod features through the 'Tweaking' tab toggles. If you use iModYourAnno, please notice, that you have to turn on all toggles in the Tweaking tab to get the intended 'Full Experience'!

* Update for GU16:
    - Made the whole mod compatible with GU16. Added Artista 2x3 Residences and updated Hacienda Quarters for new Lifestyle needs and RequiredtobeBuilding change:
        - Base Version: 2x3 Jornalero Residences are updated to 8 Jornaleros + 16 from Lifestyle Needs (24 total).
        - Base Version: 2x3 Obrero Residences are updated to 16 Obreros + 28 from Lifestyle Needs (44 total).
        - Base Version: 2x3 Artista Residences: 32 Artistas + 36 from Lifestyle Needs (68 total).
        - Extended Gameplaychanges: 4x4 Jornalero Residences are updated to 30 Jornaleros + 35 from Lifestyle Needs (65 total).
        - Extended Gameplaychanges: 4x4 Obrero Residences are updated to 70 Obreros + 65 from Lifestyle Needs (135 total).
        - Extended Gameplaychanges: 4x4 Artista Residences are updated to 140 Artistas + 75 from Lifestyle Needs (215 total).
        - Extended Gameplaychanges: 2x3 Jornalero Residences are updated to 13 Jornaleros + 17 from Lifestyle Needs (30 total).
        - Extended Gameplaychanges: 2x3 Obrero Residences are updated to 26 Obreros + 29 from Lifestyle Needs (55 total).
        - Extended Gameplaychanges: 2x3 Artista Residences up to 52 Artistas + 33 from Lifestyle Needs (85 total).
    - Added Hacienda, Hot Sauce and Atole need to Artista Hacienda Residences.
    - Added new public buildings with Hacienda Ground Decals.
    - Adjusted all Hacienda Policies to the new needs and possibilities of GU16. Policy 1 and 2 have been updated where Policy 5 has been removed completely and was outsourced as a separate module. It was replaced with a new policy.
</details>

<details>
    <summary>Patch Notes Version 1.5.1</summary>

* Minor Bugfixes:
    - Fixed an Issue with the trade values of certain goods (i.e. Hot sauce) due to missing <IsMainFactory> values.

* New features:
    - Adjusted the item effect target pools of the OW and NW charcoal kilns to be replaced by one united "all charcoal kilns" effect target pool.
</details>

<details>
    <summary>Patch Notes Version 1.5.0</summary>

* New features:
    ![Banner](https://user-images.githubusercontent.com/64583643/192605638-41616a81-7f59-4ff6-8bc6-28d2a02306ed.png)
    - Added Module 2 - Sounds of Stradivari. This mod enables you to produce Violins in the New World utilising Hacienda Overhaul features. Lacquer can now be produced from Quartz (Sand Mine on Clay Slots), Caoutchouc, and Ethanol. Cherry wood is obtainable by using the Hacienda policy 3: Woodcutter Training as a byproduct form lumberjacks and orchards. Steel can be produced in the furnace from Iron ore, mined on Gold slots.

    Thank you to [Jakob](https://github.com/jakobharder/anno-1800-jakobs-mods) for providing the basic graphics of the sand mine and the fixed steel furnace as well as some code to get compatibility between his mod ["New World Construction"](https://github.com/jakobharder/anno-1800-jakobs-mods/tree/main/mods/production-nw-construction) and mine. Just a little heads up, my shared buildings with Jakob's Mod might differ slightly in workforce requirements, build costs and maintenance costs.
</details>

<details>
    <summary>Patch Notes Version 1.4.0</summary>

* Update for GU15:
    - Updated Hacienda Quarters for new Lifestyle needs and RequiredtobeBuilding change:
        - Base Version: 2x3 Jornalero Residences are updated to 8 Jornaleros + 12 from Lifestyle Needs (20 total).
        - Base Version: 2x3 Obrero Residences are updated to 16 Obreros + 24 from Lifestyle Needs (40 total).
        - Extended Gameplaychanges: 4x4 Jornalero Residences are updated to 30 Jornaleros + 30 from Lifestyle Needs (60 total).
        - Extended Gameplaychanges: 4x4 Obrero Residences are updated to 70 Obreros + 60 from Lifestyle Needs (130 total).
        - Extended Gameplaychanges: 2x3 Jornalero Residences are updated to 13 Jornaleros + 12 from Lifestyle Needs (25 total).
        - Extended Gameplaychanges: 2x3 Obrero Residences are updated to 26 Obreros + 24 from Lifestyle Needs (50 total).

* Minor Bugfixes:
    - Found the cause of the crash when switching recipies between the Hacienda Farms: I forgot to change the relevant asset entry for the Blank Hacienda Farm in my Policies Overhaul which gives the tractor boost to the farms. Though the blank farm never produces anything, the game doesn't like the missmatch between the blank farm and the respective recipe farm. Blank Farm is now back into the modules of the Hacienda menu.
    - Removed some Bugfixes silently introduced with GU15.

* New features:
    ![Banner](https://user-images.githubusercontent.com/64583643/192149310-8fcbf8b6-b878-48c3-9269-0a2a9c9fdfa7.png)
    - Added the Hacienda Streets from Muggenstürmer's [CityOrnaments Mod](https://www.nexusmods.com/anno1800/mods/93) as an optional and separate mod to replace my Hacienda streets. The streets now feature bridges and railway crossings. Thanks to Muggen for letting me use his fantastic work!
</details>

<details>
    <summary>Patch Notes Version 1.3.3</summary>

* Minor Bugfixes:
    - Found the cause of the crash when switching recipes between the Hacienda Farms: I forgot to change the relevant asset entry for the Blank Hacienda Farm in my Policies Overhaul which gives the tractor boost to the farms. Though the blank farm never produces anything, the game doesn't like the mismatch between the blank farm and the respective recipe farm. Blank Farm is now back into the modules of the Hacienda menu.
    - For whatever reason the Hacienda Breweries had their attractiveness impact shown in the city tab where only positive attractiveness values are presented by default. I changed it to Factory. (Maybe the devs once planned to give them an attractiveness boost to the city and just had an typo with the minus???)
    - Cleared an issue where the Hacienda Tab in the Build Menu with the Hacienda Church was visible and buildable too early in the game, because I added the Church to the AssetPool Chapel, which is by default unhidden/unlocked with Jornaleros.
    - If you use my Production Chain Overhaul or the Shared Goods Mod, the Hacienda Winery and its recipe now show the correct icon for Wine instead of Champagne.
    - Cleaned up the buildmenu of the Hacienda Overhaul, somehow the Hacienda was still in the Obreros Tab, but inside the Hacienda Ornaments Tab (that shouldn't be there in the first place). It should be very clear now, that the Hacienda and its Ornaments can only be found in the Hacienda Build Menu Tab, as intended.
</details>

<details>
    <summary>Patch Notes Version 1.3.2</summary>

* Added the Hacienda Vineyard to the ItemEffectTargetPool "All alcohol production chains", so that it will be buffed by various festivals.
</details>

<details>
    <summary>Patch Notes Version 1.3.1</summary>

* Set SecondPartyRelevant to 0 for the Hacienda Winery, so that AIs won't get messed up while using it.
</details>

<details>
    <summary>Patch Notes Version 1.3</summary>

![banner](https://user-images.githubusercontent.com/64583643/170326244-da7a2b35-e93e-43f5-9f70-928a5a4571c3.png)
* Module 1: Hacienda Winery added. Available from 1 investor skyscraper level 3. Requires grapes, cinnamon and cherry wood. Produces "Champagne" (for now...).

</details>

<details>
    <summary>Patch Notes Version 1.2</summary>

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
    - Hacienda Main Buidling added to the Influence Investment "Optimization" AssetPool
</details>

<details>
    <summary>Patch Notes Version 1.1.2</summary>

* Hotfix for all Localizations except English. Sorry for the inconvenience, I accidentally zipped up older texts files for the other languages.
</details>

<details>
    <summary>Patch Notes Version 1.1.1</summary>

* Just some small bugfixes:
    - Obrero Residences can't be copied any longer. If selected with the Copy Tool, corresponding Jornalero residences will be used.
    - Fixed a Typo in the German Localisation: Banenen -> Bananen
</details>

<details>
    <summary>Patch Notes Version 1.1</summary>

Upon popular demand, I decided to split the mod into modules. **ALL** Modules require the Base Module to be inside your mod folder. All other modules are optional. Following is a brief overview about each modules features:

Pick and choose what ever combination is your favorite :D

* Base:
    ![banner](https://user-images.githubusercontent.com/64583643/170326044-14f16f0a-9854-40e2-af8c-aba3b4ea021d.png)
    - New separate build menu for all Hacienda buildings
    - New Icons for all Hacienda Modules for easier identification and accessibility
    - Hacienda Streets now unlimited and working like normal streets
    - Hacienda Farms with Plantains, Cotton, Tobacco (no fertility required) and split recipe book for NW and OW farms
    - Obrero Residences must be upgraded from Jornalero ones
    - Public buildings with Hacienda Grounddecal variation
    - Bugfixes

* BasicGameplay changes:
    ![banner](https://user-images.githubusercontent.com/64583643/170326070-ad4251a2-c6fc-45eb-a529-dd5c7961f0f0.png)
    - Radius of the Hacienda now up to 80
    - Fertilizer Factory got buffed and hasn’t to be build inside the Hacienda Radius

* ExtendedHacienda by Lordys:
    ![banner](https://user-images.githubusercontent.com/64583643/170326118-9b8d5fd9-ba7a-412e-b45b-fe8ec3c32edd.png)
    Thanks to Lordys we now have a variety of new Hacienda specific buildings:
    - Small Marketstands → Satisfy need of Hacienda for Residences in its range
    - Small Jornalero and Obrero Residences (2x3) → 8/\[12\] and 13/\[20\] pop
    - Hacienda Chapel → Satisfies Chapel Need
    - Hacienda Fire Station, Hacienda Police Station → Two resolver units each and slightly higher coverage
    - Hacienda Trade Union → Radius 20! Costs 50 Obrero Workforce though
    - Hacienda Border Wall Semi-Automatic and manual → read below!
    - One quick word on the topic of the semi-automatic outer wall. Since the Anno Code only allows for ornaments to be in the middle of the decal to snap automatically into the right place, I had to use a trick. You have to build a two tile wide corridor of wall first. Afterwards you can safely delete the inner circle and the outer one will stay connected the right way!

* ExtendedGameplay changes:
    ![banner](https://user-images.githubusercontent.com/64583643/170326142-cfb81268-9a48-4a72-80e2-e8713faf38c6.png)
    - Hacienda Warehouse now up to 100 tons of storage and TWO transporter
    - Hacienda residences have been overhauled completely (see below)
    - Fertilities mater again (see below)
    - Hacienda Breweries: checked and adjusted (see below)

* PolicyOverhaul:
    ![banner](https://user-images.githubusercontent.com/64583643/170326173-21795d8f-869d-4086-adf1-56fa7d664698.png)
    - Hacienda Policies completely replaced and rebalanced (see below)
</details>

## Mod Description with main feature overview
**Please remember to always check the Changelog to see the new or changed features.**

Dear Ubi Team, dear Annoholic community.

This is my version of DLC10 Seeds of Change as I have envisioned it to be from the first moment I saw gameplay. Unfortunately the initial release left me and many other members of the community behind their expectations. I conducted a research of the most wanted changes and modded it into the game. This is the list of features:

### New separate build menu for all Hacienda buildings
I created a separate build menu entry dedicated to only Hacienda buildings. Everything can be build from their.

- Hacienda street tiles are now directly accessible
- New building categories for OW and NW farms
- New building category for the Hacienda Breweries

### New Icons for all Hacienda Modules for easier identification and accessibility
The Icons of the Hacienda Modules lack distinctive features and contrast, it is really hard to tell them apart. So everyone got a new and distinct looking icon.

### Hacienda Streets now unlimited and working like normal streets
The Hacienda Streets have been limited to 999 tiles combined for an unknown reason. No longer! Each module is now separate and works like a normal street. They can now be built over Rivers and Train Tracks as well. (Thank you to Muggenstuermer's ["City Ornaments"](https://www.nexusmods.com/anno1800/mods/93?tab=description)).

### Radius of the Hacienda now up to 80
I increased the maximum range to 80 starting at 15. To give an extra incentive to build population inside the Hacienda radius, the last two steps are reserved for hitting 7500 and 10000 population (+5 on the radius each time). To accommodate the new radius, the distance over which the Hacienda provides its Public Service to houses has been increased as well. You should be able to easily fit residences at the outer parts of the radius if using paved streets (or Hacienda Plaza). This feature is fully tweakable through iModYourAnno.

### Hacienda Warehouse now up to 100 tons of storage and one transporter
The vanilla Hacienda Warehouse hasn’t a real value over the normal Depots inside the harbour area, as they even use up precious land space. So I gave them a new task with adding one transporter ramp to them and increasing the storage space to 100 tons. This comes at a cost though. The can only be build inside the Hacienda radius and they’ll cost you 50 Obrero Workforce each! They should only act as a support to regular warehouses. This feature is fully tweakable through iModYourAnno.

### Hacienda residences have been overhauled completely
- Jornalero residences now take up to 85 Population each with lifestyle needs. Their needs have been left unchanged, but an extra incentive has been given to the two new goods Schnaps and Hot Sauce by increasing the amount of gained inhabitants.
- The next big change is that Obrero residences can’t be build separately any longer. You’ll need to upgrade your Jornalero residences.
- For the Obrero Residences, they now get 3 points of attractiveness by default to help you reach the required amounts of it to unlock the Hacienda policies. Their inhabitant count has been lifted to 165. An extra incentive was given to the new products Hot Sauce and Atole as well as the newly introduced needs: Chewing Gum and Violins unlocked at 1500 and 2000 Obreros respectively to further strengthen the incentive to build those production lines in later game.
- To accommodate the changed needs, population boosting items like Saint D’Artois and Papal Paper now give extra residents from Hot Sauce as well as Chewing gums and Violins to promote not only NW usage of these goods but also the supply of Violins and Chewing gum to Engineer and Investor Skyscrapers, as those productions are not really space efficient for the amount of inhabitants they give.

### Fertilizer Factory got buffed and hasn’t to be build inside the Hacienda Radius
Production time of the Fertilizer Factory has been lifted to 90 seconds. At the same time, the buff for the animal farms has been reduced to 1/10 instead of 1/3. Now you have to build 3 Animal farms at 110% to supply one unboosted Fertilizer Factory instead of a one to three ratio as before. The Fertilizer Factory also doesn’t need to be build inside the Hacienda radius any more, because I think most of us don’t wanna wake to the smell of poop every day, would we?

### Hacienda Farms: 4 new crop types and fertilities mater again
Why exactly is it that the Devs left out the three crops Bananas, Cotton and Tobacco? Well, I theorize that the recipe book has no more space than to fit 8 recipes at the current scale of each item on the list. So they told their art team to design all crop farms for the New World fertilities and then dumped the ones nobody likes - because of balancing and item game - overboard. But the graphics did survive the drip into the final game files! I spent an hour creating the Tobacco plantation until I noticed at export that there already is on! I mean wtf. I paid full price but due to a really simple UI design problem, so much content was stolen from me. Especially since the Tobacco Plantation was one of the most unused Farm in the entire game, a Hacienda version in vanilla could have made a really good opportunity to actually plant it instead of getting it as a by-product from bananas.

- So, I fixed that issue myself with a split of hacienda crop farms into two buildings, New World Hacienda Crop Farms including the long lost Banana, Cotton and Tobacco Plantations and OW Hacienda Crop Farms plus spices and *drum role please* a Vineyard! More on that later. With update 2.2.0 we also have the missing Farms from DLC12: Herbs and Orchids!

- The recipe books are now split as well, so watch out for that. All farms have been checked for their production time to fit vanilla. Since the importance of the Hot Sauce is increased drastically, Spice Farm production cycle was set to 120 seconds, so that supply becomes a bit more of a challenge. Another big change is that all New World Crop Farms and the Vineyard now require the corresponding fertility on the island. I don’t get it why such an old feature of the Anno series should now be dropped entirely.

- Farms and recipes are now locked to begin with. Now more Cocoa or Coffee Plantations if your residents don’t require the appropriate finished Product. This should ease the new player starting with a new savegame to have a little bit of visible progress.

- Hacienda Breweries: checked and adjusted. I adjusted the negative impact on Attractiveness by Hacienda Breweries to +5 to help with the unlock of all Hacienda policies. The building costs were raised to 10 Timber and 15 Bricks. The production time of the Hot Sauce Brewery was lowered to 60 seconds for above stated reasons of balancing the newly popular need vs the amount of pop you get from it. Breweries and their recipes are now locked to begin with. Now more Atole or Coffee if your residents don’t require the appropriate Product. This should ease the new player starting with a new savegame to have a little bit of visible progress.

### Support for most important Public Buildings to use the Hacienda Plaza ground decal
This one is for the beauty builders in the Community. I took every major public building and gave them a new variation with the Hacienda Plaza ground decal, so that you can build magnificent Hacienda Compounds with fitting Public Buildings.

Included are: Firestation, Police Station, Hospital, Chapel, Boxing Arena and all Warehouses as well as the DLC12 public buildings.

### Hacienda Policies completely replaced and rebalanced
To be honest the vanilla Policies are like playing with the small scoops in Kindergarden while the bigger kids got the nice Tractors and Earthmovers. In comparison to the Palace buffs, they look nearly useless. For the fourth one you have to pay nearly the same amount into Attractiveness enhancement to break even. That’s no good game design. The Buffs from the Scenario Hacienda are way more powerful and would have fitted as well.

But as I’m more creative than that, I created 5 totally new and potentially game changing buffs for you to play around with. Now you’ll definitely consider every one of them.

- Decree 1: Clean Environment Regulation (required Attractiveness: 450)
    * Effects All Heavy Industries, all Mines, all Quarries, all NW Chemical Plants and all Breweries:
        * Productivity +20%
        * Chance of Fire -50%
        * Chance of Explosion -100%
        * Negative Infliction on Attractiveness -80%
        * Workforce needed +25%
        * Maintenance Costs +75%

- Decree 2: Local Factory Outlet Regulation (required Attractiveness: 700)
    * Effects All New World Residences:
        - Reduced Consumption of:
            - Ponchos -25%
            - Bombins-15%
            - Coffee -10%
            - Cigars -10%
            - Fans -10%
            - Scooters -10%
        - Extra happiness from Market/Hacienda +5
        - Income -10%

    * Effects All Clothing Factories, all Intermediate Good Producers, Coffee Roaster, Cigar Factory, Fan Factory and Scooter Factory:
        * Extra Goods every third Cycle (1/3)
        * Attractiveness +5%
        * Workforce needed +15%
        * Maintenance Costs -50%

- Decree 3: Lumberjack Educational Decree (required Attractiveness: 1000)
    * Effects All Lumberjacks and all NW Orchards
        * Productivity +15%
        * Attractiveness +10
        * Workforce needed -50%
        * Forest Density -25%
        * Extra Goods: Wanza Wood 1/7 and Cherry Wood 1/10

- Decree 4: Vineyard Promotion Act (required Attractiveness: 1750)
    * Effects Hacienda Vineyards
        * Extra Grapes every second cycle (+50%)
        * Grape fertility provided
        * +25 Attractiveness

    * Effects Hacienda Winery
        * Extra Champagne every second cycle (+50%)
        * +25 Attractiveness

    * Effects all Artista residences:
        * +58 extra Money , +5 Happiness and +5 Inhabitants from the Champagne lifestyle need as well as a -25% reduction of said need.

- Decree 5: Cultural Conservation Act (required Attractiveness: 2200)
    * Effects all Obrero and all Artista Residences
        * Income per House -25%
        * Bonus Happiness +5 and Bonus Inhabitants +5 from Samba School and Lanterns
        * Reduced consumption of Light Bulbs (-25%), Fans (-50%) and Scooters (-75%)
        * Increased consumption of Typewriters (+25%), Soccer Balls (+50%) and Sewing Machines (+75%)
        * If the Boxing Arena need is fullfiled, the residences gain Cinema need fullfiled
        * If Lantern need is fullfiled, the residences gain Electricity need fullfiled

### Extended Hacienda by Lordys and Taludas
In cooperation with Lordys, I developed an extension to the Hacienda DLC with new public buildings, new 2x3 Hacienda residences and a outer Hacienda wall ornament to further customize your Gameplay experience.
* Small Marketstands → Satisfy need of Hacienda for Residences in its range
* Small Jornalero, Obrero Residences and Artista Residences (2x3) → 24/\[30\], 44/\[55\] and 68/\[85\] pop
* Hacienda Chapel → Satisfies Chapel Need
* Hacienda Fire Station, Hacienda Police Station (both with advanced Versions as well) → Two resolver units each and slightly higher coverage
* Hacienda Trade Union → Radius 20! Costs 50 Obrero Workforce though
* Hacienda Townhall
* Hacienda Border Wall Semi-Automatic and manual → read below!
* One quick word on the topic of the semi-automatic outer wall. Since the Anno Code only allows for ornaments to be in the middle of the decal to snap automatically into the right place, I had to use a trick. You have to build a two tile wide corridor of wall first. Afterwards you can safely delete the inner circle and the outer one will stay connected the right way!

### Mod Tweaks through iModYourAnno

If you use the [iModYourAnno Anno Mod Manager](https://github.com/anno-mods/iModYourAnno) you will find a tweaking tab in it. There are several options to tweak some gameplay elements of this mod. For example you can toggle whether the Hacienda Farms require a fertility. Or what recipe the winery uses. With regards to the policies you can decide to either use the vanilla ones or my modded ones and you can specify the required Attractiveness amount needed to unlock these. If you want the full experience, I suggest you switch every toggle option to 'on'. The value tweaking is up to your own liking. Feel free to experiment with your own numbers. Always remember to save you changes and delete the Cache Folder inside your mods folder afterwards.

### Bugfixes
- Hacienda Main Building removed from the ItemEffectTargetPool “All Hacienda Buildings” so that it can’t be boosted by Items which affect “All Production Buildings”.
- Hacienda Warehouse removed from the ItemEffectTargetPool “All Hacienda Buildings” so that it can’t be boosted by Items which affect “All Production Buildings”.
- Fixed a LOD issue with two of three Obrero Hacienda Residences: On one building side,suddenly windows appeared where none were visible before (LOD levels 2 and up)

### Acknowledgements
All that is left now, is to say thank you Ubisoft Mainz for a great game which I learned to love over the last 3 Years, that got me into some programming territory and self education about 3D Modelling as well as some amazing people on the Anno Mod Corner International Discord without whom this mod would have not been possible.

Special thanks to:
* Taubenangriff: For being a walking Lexikon for Anno Game Code knowledge and feedback and development of the IModYourAnno Mod Manager
* Jakob: For helping me with my very first modding attempts and developing the VSCode Plugin Anno Modding Tools as well as a Texture Converter and development of the IModYourAnno Mod Manager
* Lordys: Without whom I wouldn’t have ever been able to wrap my head around the function of the 3D game files and his amazing [Blender cfg Import/Export Addon](https://github.com/xormenter/Blender-Anno-.cfg-Import-Addon), he contributed all the buildings for the Hacienda Extended Module! THANK YOU :)
* JJE1000, Hackner and Pine: For feedback and constructive talks about features
* Meow for the amazing Mod Loader without this nothing of this would be possible
* lukts30: rdm4 converter
* VladiwSokow: for the idea of boosted transporters in the Arctic and how to do it

If you've read up to this point: What'll come next you ask... I plan on having a modular setup ontop of this base mod. For now only the working titles will be spoiled though:
* Module 1: The Burrito Boom -WIP-
* Module 2: The Formidable Faulproof Fertiliser -WIP-
* Module 3: Willis Wine World-Tour (Done! -> Hacienda Winery)
* Module 4: The Mutile Mine Makeover (Done! -> Small Mods collection 'Mine Slot Unification')
* Module 5: Sweet, salty, sour or spicy? -TBD-
* Module 6: The Sounds  of Stradivari (Done!)
* Module 7: The Cinematic Century Dawns -TBD-

That’s all! Hope you enjoy and happy city building!
