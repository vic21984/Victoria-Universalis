#Version 0.77 - 4/14/2023
## Bug fixes:
* Fixed some slave provinces having extra province size modifiers they shouldn't have at the start.
* Removed port from Telén province.
* Made the "X = { exists = yes }" event condition display "X DOES EXIST" instead of "X DOES NOT EXIST"

## Interface changes:
* Reformatted the province window to be compatible with smaller resolutions.

## Map changes:
* Created East Indies and Polynesia continents.
* Re-arranged province shapes in Poltava state.
* Merged Herat and Sistan states and re-arranged a few provinces in Afghanistan.

## Gameplay changes:
* Disabled mine expansion buildings in agricultural RGOs and disabled farmland expansion buildings in mining RGOs.
* Increase size of gold mines to 80,000 workers, increased output, and disabled mine expansion building.
* Reworked Player Grants events. Now the player that receives the grant request can decide how much to give instead of the player asking for the grant deciding ahead of time how much other players will give.
* Province selectors are no longer limited to one per state.
* Province selectors will be automatically reset whenever a player enforces a transfer state cb at the end of a war.

## Country changes:
###### United Kingdom:
* Reduced cost of the Help the Irish decision from 3,000,000 pounds to 2,000,000.

###### Central Asia:
* Mukriyan starts with 2 more provinces in 1836.
* Created the country of Hazaristan in central Afghanistan which starts out as a puppet of Afghanistan in 1836. Afghanistan gets an event to conquer them at 60% civilization progress.

###### South America:
* Added Basic Chemistry and Military Staff System techs to all South American countries in 1836

###### Argentina:
* Bahia Blance and Mar del Plata start uncolonized in 1836.


#Version 0.76 - 4/5/2023
## Bug fixes:
* Removed adjacency between Herat and Balkh.
* Fixed Trinidad & Tobago localization.
* Fixed ideologies sometimes taking too long to spawn.
* Fixed naval exercises and modern naval exercises inventions not having any effect.

## Map changes:
* Created 2 new provinces in North Zhili/Innger Mongolia
* Merged 2 provinces in the Caucasus.
* Re-arranged a few states in China.
* Created Biafra state out of the eastern half of Niger Delta state.

## Gameplay changes:
* Made all provinces start with a province size of 1. Farm RGOs have a a base of 40k workers and mining RGO have a base of 10k workers.
* Added Farmland Expansion and Mine Expansion buildings that increase the size of an RGO by 100% per level. Farmland Expansion has 50 levels and doesn't require any tech, Mine Expansion has 6 levels and requires Metallurgy tech. Deserts are capped at 1 Farm Expansion and Arctic cannot build any Farm Expansions.
* Made most countries start with enough Farmland Expansions to employ all of their workers while China, India, and most of Africa start with enough to employ only half their workers. Uncolonized land starts with 0 Farm Expansions.
* Added University building that gives +0.05% RP generation per level with a max of 3 levels and 1 per state.
* Created new inventions for several 1920s techs.
* Made steel, machine parts, and steamer shipyards use slightly less coal and slightly more iron and/or steel.
* Lowered increased factory maintenance cost of state capitalism and planned economy from 15% and 10% to 10% and 5%.
* Reduced base cement maintenance cost of factories by 20%.
* Buffed commerce tech bonus from Naval Tech School from 5% to 10%.
* Removed terrain RGO nerfs.
* Removed theocracy and tribal society government types to help with performance.
* Doubled prestige gain from Aesthetics techs from 5% to 10%.
* All shared prestige gain from techs now comes with a small amount of permanent prestige gain equal to 10% of the max shared prestige gain.
* Made national idea selection events trigger every 15 years via event instead of by researching techs. Replaced national idea techs with the original Economic Theory and Critique techs.
* Replaced Naval Build Speed national idea with Naval Experience national idea.
* Nerfed most military national ideas.
* Nerfed industrial and consumer goods output ideas.
* Buffed infamy decay and militancy reduction national ideas.
* Buffed expansionism invention from -0.02 to -0.05 and moved it from Revolution and Counterrevolution to Mass Politics.
* Made war reparations give 10% of income instead of 20% and last 10 years instead of 5.
* Disabled aristrocrat factory investments.

## Country changes:
###### United Kingdom:
* Added the Lexy Taxes on India decision that declares war on EIC for reparations and re-puppets EIC when enforced. All of EIC's provinces are instantly occupied in order to allow instantaneous forced peace. The reparations last for 10 years and this decision must be taken every 10 years in order to keep the taxes flowing.
* Increased tariff efficiency modifier from Unequal Chinese Treaty modifier from 5% to 10%.

###### British Raj:
* EIC will no longer disintegrate when released by the UK via the manage vassals decision.
* Replaced Embrace Nepalis decision with Expand Indian Army decision that adds both Nepali and Panjabi as accepted cultures.
* Created an event for the AI EIC that activates army techs that are 1 level below the current army tech of the UK, e.g. if UK has Breech-loaded Rifles and EIC does not have Muzzle-loaded Rifles then the event will activate Muzzle-loaded Rifles for EIC. This event fires whenever the UK researches a new army tech and EIC is a puppet of the UK. It will not fire when EIC is played by a player.

###### Japan:
* Countries can no longer use demand concession casus belli on Japan in the multiplayer bookmark and must use the regular acquire state cbs even when Japan is uncivilized.

###### Ottoman Empire:
* If the Egyptian Surrender event is accepted during the Oriental Crisis war, Syria will become a state after being transferred to Turkey instead of a colony.

###### Spain:
* Enabled Reconquista decisions for regular Spain in the multiplayer bookmark.

###### Canada:
* Annexed Rupert's Land in the multiplayer bookmark.

###### South America:
* Added a decision for North and South Andean culture countries to add the other Andean culture as accepted if they own all Venezulian, Colombian, Ecuadorian, Peruvian, and Bolivian cores.

###### Great War Bookmark:
* Improved economies of all central powers countries significantly. They should be able to afford to keep the war going for several more years than in previous versions.
* Made the effects of the October revolution event fire immediately instead of after the player chooses an option.


#Version 0.75 - 12/20/2022
## Bug fixes:
* Converted Ukrainian POPs in Przemysl to Russian in the multiplayer bookmark.
* Added Sweden-Norwegian cores to Finland and starting OOB in multiplayer bookmark. 
* Disabled The Great Trek Boer migration in 1913 and WW1 bookmarks.
* Fixed the East India Company instantly peacing out of scripted wars due to it breaking its alliance with the UK while it was still a puppet.

## Map changes:
* Merged Southeast England and London states.
* Merged Bohemia and Moravia states.
* Added new provinces in Ethiopia.
* Merged District of Columbia and Maryland states.
* Renamed North Carolina to North & South Carolina and transferred two provinces from Georgia to North & South Carolina.
* Reverted most Chinese states back to vanilla borders. Treaty ports are still separate states.
* Introduced Middle East continental region.
* Imported GFM shapes for provinces in Texas.

## Gameplay changes:
* Reworked Literacy Campaigns by halving the cost of the decision, reduced the province modifier from 15 years to 10, and removing the instant literacy gain. Now POPs located in a province with an active Literacy Campaign modifier will gain 1 - (POP Literacy Rate/100) at the beginning of every year, so a POP with 0% literacy will gain 1% per year for 10 years and a POP with 80% literacy will gain 0.2% per year.
* Renamed Horse Artillery to Light Artillery, reduced manuever from 2 to 1, and reduced stats to 66% of regular artillery and supply cost to 50% of regular artillery.
* All demand state cbs now have a fixed warscore cost that won't increase for the rest of the game.
* Removed factory input bonus from free trade and replaced it with a 5% buff to craftsmen and clerk promotion chance.
* Reduced max tax from laissez faire from 100% to 80% and introduced a 5% buff to craftsmen and clerk promotion chance.
* Increased bonus to building specified goods when using the encourage industry national focuses and added new Encourage Beverage Industry category.
* Increased minimum naval upkeep from 30% to 40%.
* All countries start with compulsory school reform in the multiplayer bookmark.
* Increased base supply of empty coastal provinces from 2 to 40 due to some nations with a small coast still having limited naval capacity in 1836.
* Merged Add and Remove Cores province selector decision into Integrate State decision and added local +0.1 militancy modifier to the target state for the duration of the integration.
* Reduced base cost of all uncivilized Military Reforms from 4000 to 3000 and increased cost of all uncivilized Economic Reforms from 4500 to 5000.
* Constructing a canal now costs 2M pounds.
* Added -30% ruling party support to the Reform Recently Passed modifier.
* Reduced militancy from political reform desire by 25%.
* Made pops in reform movements slightly less likely to become radical.
* Liberal and conservative POPs can now vote for social reforms if they are part of a social reform movement.
* Social Thought techs make POPs more likely to join school reform movements.
* Added missing parameters for pops to support political rights reform.
* Combined all the African desert decisions into one decision. Prerequisites and land transfers are still the same.

## Country changes:
###### USA:
* Added "Revoke Homestead Act" decision.
* Westward Migration province modifier now gives -90% migration attraction instead of -100%.
* Increased liferating of all Midwest and West coast provinces by 5.
* Gave AI buff to craftsmen promotion chance.

###### Russia:
* Milytun's Army Reforms decision now adds a -20% supply consumption modifier for 20 years.

###### Germany:
* Re-introduced South German culture in multiplayer bookmark.
* Nerfed AI craftsmen promotion chance.
* AI won't fire EMS dispatch decision until it either has more brigades than France or France is at war with another country, in order to increase the likelihood of a German victory.

###### Italy:
* Italian minors can use the unification restore order cb on other Italian minors after researching nationalism and imperialism.

###### United Kingdom:
* AI English Channel Crossing, Hong Kong Island, and Bombay will get a special modifier that increases movement speed when all are owned by the same AI country. Previously it would take over a year for troops to move between the AI English Channel land bridge and Hong Kong Island or Bombay and this would result in massive attrition for any troops making the year long trip.

###### India:
* Civilized British Raj will split up into India and Pakistan instead of Indian minor nations if the Raj gains independence without becoming a GP first. Uncivilized East India Company will still break up into various Indian minor nations if it becomes independent.

###### Egypt:
* Added decision for the nation that fired the Give Loan to Egypt decision to annex Egypt if Egypt is it's puppet.

###### Korea:
* Added Tonghak Reforms and Claim Greater Korea decisions.

###### Persia:
* Created an event to release starting puppets if Persia no longer shares a border with them.

###### Algeria:
* Changed starting Jihad modifier (+20% mobilization) to General Mobilization modifier (+10% mobilization).

###### Ethiopia:
* Added two new Ethiopian kingdoms.
* Claim Imperial Throne decision now adds Amhara, Oromo, and Cushitic as accepted cultures.
* Created Complete the Agar Maqnat decision that cedes uncolonized land in Somali and Gambela to Ethiopia.
* Increased starting civilization level of East African countries.

###### Sub-Saharan Africa:
* Found the Tukulor Empire decision adds Mossi as an accepted culture.

###### South America:
* Forming Rio Plata now adds South Andean and Platinean as an accepted cultures.

###### Austria:
* Annexed Hungary in multiplayer bookmark.

###### Netherlands:
* Annexed Indonesian puppets in multiplayer bookmark.

###### Spain:
* Annexed Carlist Spain in multiplayer bookmark.

###### Turkey:
* Annexed Bohtan in multiplayer bookmark.


#Version 0.74 - 7/29/2022
## Bug fixes:
* Fixed bugged liberate nation and free peoples cb in crises.
* Province RGO Expansion Flag will be added to mines that the AI expands.
* Replaced South Italian POPs in Rome with North Italian POPs in the multiplayer bookmark.
* Banker POPs no longer work in gold mines and now get their income from a decision whenever their bank savings reaches 0. In earlier versions sometimes Banker POP's savings would get so large that it would interger overflow and become negative. This new system ensures that they will never have a high enough savings account to interger overflow while also always giving them enough money to spend on their needs.

## Interface changes:
* Swapped positions of the Tutorial and Exit buttons in the main menu screen. This allows 1028x768 resolution players to exit from the main menu instead of having to exit from within the game.
* Added a brief explanation of how Torpedo Attacks work in the Build Navy section of the Military Tab.
* All ships will have their ship type listed next to their name.
* Replaced red country border lines with black lines.

## Map changes:
* Added 8 new provinces in Japan and merged 8 island provinces in the ROTW.
* Created Seto Inland Sea strait between the coasts of Chugoku and Shikoku states with Sea Crossing Tiles in Yamaguchi, Matsuyama, and Tokushima. Seto Inland Sea cannot be entered from South Korean Sea unless Yamaguchi is captured and Seto Inland Sea cannot be entered from Shikoku Coast unless both Matsuyama and Tokushima are captured.
* Added a crossing between Matsuyama and Hiroshima.
* Added Strait of Bonifacio sea tile between Corsica and Sardinia with a Sea Crossing Tile in Sassari.
* Merged Colmar and Mullhouse provinces in Germany and Epinal and Luneville provinces in France.
* Combined several states in Germany, Austria, Persia, Turkey, and Japan, and Scandinavia.
* Moved Parana province to Corrientes state.
* Combined several provinces in Eastern Turkey and added extra provinces in Afghanistan and Pakistan.
* The provinces of Telen, Postojna, Karlovac, and Mostar are no longer coastal.

## Gameplay changes:
* Re-enabled firing of RGO workers. This shouldn't change much due to the world bank buying up all excess RGO goods which should result in little to no RGO unemployment anyway.
* Set supply cost of all ships to 1. The only limiting factor for the size of your navy is how much you can afford.
* Heavily reduced stats of all naval units in order to nerf military score gain from late game navies. The balance between ships was kept - later tech units will beat earlier tech units of the same cost and submarines beat big ships but lose to small ships.
* Raised minimum naval spending requirement from 20% to 30%.
* Clipper and Steamer Transports require a level 1 port to build.
* Modern Naval Doctrine now gives -50% naval attrition instead of +1 port level.
* Reduced Artillery maximum support value to 200, increased stats, and made its attack and defense values equal at all levels of tech.
* Replaced Cuirassiers with Horse Artillery that has 80% of the stats of normal Artillery but with 1 extra speed, 2 maneuver, and 25% less supply costs.
* Rebalanced Dragoon stats to always have 1 higher or equal attack to infantry but about half as much defense.
* Hussar attack and defense values changed to always be equal.
* Reduced Airplane maximum support value to 200, rebalanced stats, removed "accepted culture only" build clause.
* Increased Guard attack by 1 and removed "accepted culture only" build clause.
* Removed Armor "accepted culture only" build clause and removed +25% support bonus from "Medium Tanks" invention.
* Increased all promotion and demotion rates by 20%.
* Created new Acquire medium state cb. Works on provinces <300K population before 1860, <400k between 1860-1885, <600k between 1885-1910, <900k after 1910.
* Small State CB flag color changed to white background with red circular province in the middle and Medium State CB flag color is a white background with a green circular province in the middle.
* Lowered Negotiated Transfer cb justification time to 3 days.
* Reduced cost of Good Healthcare and Universal Healthcare by 10%.
* Buffed monthly leadership gain from Leadership Idea from 2 to 3.
* Every country has a truce with the World Bank and Ghostland until the end of the game in order to prevent GPs from wasting influence trying to sphere them.
* Reduced Scorched Earth maximum attrition from +10% to +3%. With all of the minus attrition techs researched, the maximum attrition in a mild climate farmland or plains province with Scorched Earth will be reduced from 15% in previous versions to 8%.
* Reduced max attrition from Combat Medicine invention from -10% to -5% and added -5% attrition to Basic Chemistry tech.
* Change RGO province selector decision can now change the RGO of forest and woods tiles to timber and coastal tiles to fish.

## Country changes:
###### Scandinavia:
* Increased liferating to 40 and merged Sweden and Norway into Kingdom of Sweden-Norway in multiplayer bookmark. Scandinavia will have 35 liferating and remain separate in the Grand Campaign, 1913, and WW1 bookmarks.

###### United Kingdom:
* Lowered infamy gain from Annex India decision from 30 to 20.
* Great Irish Famine event won't affect Ulster state.

###### Japan:
* All Japanese cores are owned by Imperial Japan at the start of the multiplayer bookmark.
* Removed -100% malus to Research points bonus when conquering from Sakoku.
* Starts with 20% civilization progress.

###### Central Asia:
* Persia and Afghanistan start the multiplayer bookmark with all their cores under their control.
* Starts with 45% civilization progress in the multiplayer bookmark.

###### Egypt:
* Starts with 50% civilization progress in the multiplayer bookmark.

###### Portugal:
* Changed ownership of Flores from Netherlands to Portugal in 1836. Created a decision for the owner of Sumbawa to purchase Flores for 200,000 pounds.
* Angola and Mozambique are states in the multiplayer bookmark.

###### Indonesia:
* Imported GFM provinces and new Indonesian Sultanates in 1836 start date.

###### Greece:
* Owns Ionian Islands in the multiplayer bookmark.

###### South Africa:
* Transvaal and Orange no longer exist in the 1836 start date. South Africa gets an event to release them after they annex Xhosa.
* Matabele and Basotho are replaced by Transvaal and Orange in the multiplayer bookmark.

###### China:
* Imported GFM population in North and South Manchuria.


#Version 0.73 - 7/13/2022
## Bug fixes:
* Made soldiers middle class and disabled assimilation of middle classes. There is an assimilation glitch that can make POPs go past their limit, e.g. soldiers going above 5% and clergy going above 4%. Grouping soldiers with bureaucrats, clergy, and officers and then disabling middle class assimilation should completely stop this glitch from occuring.
* Changed the event that force peaces AI nations with the Neutral flag into a decision instead. If all conditions are met for an event, the earliest it can fire is the beginning of the next month. This created a delay where players could call in Neutral flagged AI nations into wars for a month, then instantly call them in again because ending wars via event doesn't give a truce. Decisions can be fired the same day conditions are met, so players cannot abuse Neutral flagged AI nations this way anymore.
* Death of Ranjit Singh event won't fire unless UK has no truce with Punjab. This prevents a bug that made UK unable to join the Anglo-Sikh war which would result in an immediate white peace.
* Added missing naval invasion penalty to several coastal provinces.
* Added missing ports to Calvinia, Nikolaev, and Narva.
* Reduced Province Size modifier in Mosul sulphur mine to 3x.
* Fixed broken Form Indonesia decision.

## Interface changes:
* Added a Strait Crossing Tile icon to the provinces of Copenhagen, Gibraltar, Messina, Gallipoli, Istanbul, and Kerch.

## Map changes:
* Added a strait across the Straits of Messina through the province of Messina and the Sea of Azov through the province of Kerch.
* Re-arranged some sea tiles in the Mediterranean.
* Added 3 extra provinces in Bohemia and Moravia, removed 3 provinces in Croatia and Romania.
* Re-arranged Rovne and Kovel province borders.
* Merged West Sahara and Sahara states.
* Merged Mauritania and Inner Mauritania states.
* Reduced mountain defense bonus from 3 to 2 and marsh defense bonus from 2 to 1.
* Combined Apulia and Brasilicata states.

## Gameplay changes:
* Added Request Cease Fire decision for use in multiplayer games. This triggers an event for all human countries the player is at war with that gives them the option to return occupied (not owned) territory back to the player's control. This was added to speed up adding wargoals on nations after one side has surrendered.
* Added "Remove Cores" and "Add Cores" province selector decisions. These allow the player to remove all other countries' cores or add their own cores to a state. Has a cooldown of 15 years and takes 15 years for the cores to be added or removed. If a province in the state is occupied or changes ownership before the 15 year timer is up then the addition and removal of cores will be cancelled for that province. Players will vote to enable these decisions or stick with the old RNG based event system of coring provinces at the start of a new game; the two are mutually exclusive.
* Added an option to allow all economic policies to manually build factories. This feature will be voted on at the start of a new game.
* Enable or Disable Crises event changed to be based on majority vote instead of automatically being disabled if a single player voted no.
* China and East India Company start with mechanized mining researched in 1836. This allows their artisans to make military goods and greatly increases early military game supply.
* Lowered base factory worker's paychecks from 98% to 80%. This lowers craftsmen and clerks income by almost 20% but it helps to display more green numbers in the factory menu and is less confusing to most players.
* Rebalanced artisan goods so that they are all roughly equal in profitability if the artisan has access to inputs.
* Canal decisions are no longer restricted to great powers.
* Doubled province migration bonus from Migration Attraction province selector decision.
* Made farmers, labourers, and artisans more likely to migrate to mining RGOs.
* All countries that start at war in the WW1 scenario have health care set to No Healthcare.
* Increased cooldown for Scorced Earth province selector decision from 6 months to 1 year and restricted use to states that have provinces neighbouring foreign occupied provinces.
* Lowered upkeep cost of Man'o' Wars, Frigates, and Ironclads.
* In 1900, all provinces with liferating of 35 will be lowered to 33 and all provinces above 35 will be lowered to 35.
* Lowered cost of Large Mine Expansion decision from 1.5M to 750K and Mine Expansion from 500K to 250K.
* Added 1 per port limit to Battleships, Dreadnoughts, and Carriers.
* Increased pop limit for Declare Neutrality decision from 2M, 3M, and 4M for the years of 1860, 1885, and 1910 to 3M, 4M, and 6M.
* Increased iron and coal rgo sizes in several provinces across the world.
* Lowered warscore cost of acquire state and take capital by 20%.

## Country changes:
###### Austria:
* Imported GFM starting populatoins for Czechia, Croatia, and Slovenia.

###### Hungary:
* Imported GFM starting population.

###### Germany:
* Forming the North German Confederation changes centralization level to federalism.

###### Texas:
* Added Texan Manifest Destiny decision.

###### Africa:
* Removed Adrar from 1836 start date.


#Version 0.72 - 6/22/2022
## Bug fixes:
* Fixed a bug in the base game that resulted in AI countries spamming only one type of factory when they had State Capitalism or Planned Economy economic policies. An unintended consequence of fixing this bug is that player countries having to wait until the start of the next month in order to manually build factories upon switching to State Capitalism or Planned Economy.
* Fixed a bug that caused the game to crash when AI France or UK unlocked colonial negotiations and declared war on Sokoto.
* Disabled construction of 0 infamy Liberate Country cb.
* Restored prerequisites for Megali Idea and Form Byzantine Empire decisions.
* Set infrastructure of urban capital provinces to the appropriate level based on tech in the 1913 and WW1 bookmarks.
* Removed leftover Ukrainian and Tatar pops in 1836 multiplayer bookmark.
* Renamed starting Sikh Empire general "Ranjit Singh" to "Maharaja Ranjit Singh". The decision to begin the Anglo-Sikh war requires Ranjit Singh to have died, however Sikh Empire would sometimes roll another general named Ranjit Singh while the first was still alive which would result in the Anglo-Sikh war never being able to fire.
* Fixed Congo Orientale going to Congo Free State if the Congo Conference event is successful.

## Interface changes:
* Added a Small State CB province flag to all provinces within the small state population threshold. Now players can see which states they are allowed to use the Acquire small state cb on by clicking on a province and looking for the Small State CB flag. This CB still cannot be used against capital states or Sub Saharan African uncivilized nations.

## Map changes:
* Imported GFM provinces for France, Italy, and Belgium.
* Created Voronets state in between Kursk and Tartaria states.
* Created Tobolsk state from eastern half of Ural state.
* Created Okhotsk state from eastern half of Trans-Baikal and western half of Kamchatka states.
* Created Celebes state from western half of Moluccas state.
* Absorbed Vindhya Pradesh into Madhya Pradesh and Eastern Uttar Pradesh.
* Absorbed East Bengal into Bangladesh.

## Gameplay changes:
* Nerfed artillery defense to always only be twice as high as artillery attack.
* Increased tank base attack to 22, increased tank exploit invention attack bonus from 4 to 10, added +25% support to medium tank invention.
* Screw-Propelled Steamer tech unlock date changed from 1860 to 1855.
* Ticking warscore now ticks up or down every 2 days instead of every 10 days.
* Added ticking battle warscore to Opium War and Demand Reparations cb.
* Removed AI admin and education efficiency buffs.
* Increased chance of AI promoting clergy and soldiers.
* Made AI more likely to pick important techs.
* AI nations cannot use national foci on states below 10,000 population and AI nations with a national population over 1,000,000 cannot use national foci on states below 150,000 population. This should help the AI choose better states to use it's national foci on.
* Removed acquire Siberian state cb. The number of provinces in Siberian states was cut in half since the Siberian state cb was introduced, so it is no longer necessary to have a seperate cb with different warscore calculations for them.
* Set max stockpile of goods from 3000 to 2000.
* Added decisions for GPs to annex Lagos via decision before Colonial Negations is invented.
* All provinces with liferating above 40 will be lowered to 35 in 1900.

## Country changes:
###### Austria:
* Disabled the 1848 Hungarian Revolution and added an Annex Hungary decision for the multiplayer start date. The Annex Hungary decision can be enacted in 1848 and annexes Hungary without having to fight a war.

###### North Africa:
* Increased 1836 population of Morocco from 1.6M (400k pops) to 2.8M (700k pops). According to the source that lists Morocco's population in this wiki page: https://en.wikipedia.org/wiki/List_of_countries_by_population_in_1900#cite_note-10
the population of Morocco in 1905 was 5M (1.25M pops). It is impossible for Morocco to reach it's historical 1905 population with its vanilla starting population.
* Added decisions for Great Powers to go to war with and annex Tunis and Morocco.
* Added decisions for Morocco, Algeria, and Tunis to increase school reform by 1 level and gain 2 years of research points.
* Algeria starts with the Jihad modifier for one year.
* Tripoli starts with the Full Mobilization modifier for one year.
* Added generals for Morocco, Algeria, Tunis, and Tripoli.

###### France:
* Set all provinces to 31 liferating except Paris.
* Starts at war with Algeria. An event fires that gives the option to continue to war or end the war with a mean time of 15 days.
* Added decision chain to annex Algeria and take the province of Béchar from Morocco.
* Added steamer shipyard in Normandie and replaced starting clipper transports with steamer transports. This was done because the AI kept deleting it's starting wooden transports which would cause it to lose it's 1839 war against Algeria.

###### Italy:
* Allowed the War of Unification cb to be used by Italian nations against other Italian nations. This CB requires nationalism and imperialism to unlock and normally it can't be used against nations in the same culture group.
* Removed Form North Italy and Form South Italy decisions. These are redundant now that Italian countries can use the free War of Unification cb against each other. North Italian countries still have the Unite Northern Italy decision that annexes all the North Italian minors.
* Added First Italian War of Independence event chain that triggers after the Hungarian Revolution happens in the normal 1836 bookmark and after Austria uses the Annex Hungary decision in the multiplayer bookmark.
* The Expedition of the Thousand decision now starts a war against the country that owns Naples. If this war is won, Italy will be automatically formed by the country that fired the decision.
* Imported GFM populations and increased starting soldier pops in Sardinia.
* Sardinia starts with battleship column researched in 1836.

###### Balkans:
* If Russia agrees to the Treaty of Berlin in the Russo-Turkish war, the territory exchanged now matches historical borders.
* Added decision for the puppet master of Bosnia to annex it if the Treaty of Berlin event fired.
* Added First Balkan war decision chain. This decision is enabled for Bulgaria, Serbia, Montenegro, and Greece if Russia wins the Russo-Turkish war but agrees to limit it's demands in the Treaty of Berlin.
* Turkish Population Exchange event only affects Turkey and Greece instead of all Balkan countries.

###### United Kingdom
* British Raj will leave it's sphere leader's sphere of influence upon civilizing. UK will still keep the Crown Rule modifier so long as the Raj is it's puppet. This will improve the income of both the UK and Raj.

###### Russia:
* Agreeing to limit demands in the Treaty of Berlin will reduce infamy by 5.

###### Belgium:
* Imported GFM starting population.

###### Sweden:
* Made it easier to form Sweden-Norway via reforms.

###### Ottoman Empire:
* Rise of the Bedr Khan event removes all other country's diplomatic influence in Bohtan before declaring war in order to not drag other great powers into the conflict.

###### Ethiopia:
* Disabled Scramble for Africa cb on Ethiopia. Can still use Scramble for Africa on Ethiopian minor nations that aren't Ethiopia, such as Gonder and Shewa.
* Claim the Imperial Throne decision changes centralization level to Unitary.
* Created a decision for great powers bordering uncivilized Ethiopia to annex it in one war at the cost of 10 infamy. If they enact this decision, Ethiopia gets +30% mobilization for the duration of the war.


#Version 0.71 - 6/4/2022
## Bug fixes:
* Fixed bugged naval ports in Messina, Rügen, and Swinemünde.
* Fixed Strait of Gibraltar name and unit placement.
* Fixed several economic modifiers not being applied in the 1913 and WW1 scenario.
* Choosing to liberate Herat via the Anglo-Persian War event no longer gives infamy to the UK.
* The White Raja event for Brunei will only fire once now.

## Map changes:
* Imported GFM map for Germany, Balkans, Turkey, Iran, Poland, and Africa.
* Combined several states in Germany
* Split up a few states in Turkey, Persia, Syria, and Caucasus.

## Gameplay changes:
* Increased cap on non-cored soldier POPs from 2.5% to 5%.
* Nerfed soldier promotion rate of Indian and Chinese POPs.
* Converted Albanians to Turks, Walloons to French, Swiss to Germans/French/Italian, Norwegians to Danes, and Finns to Swedes in the multiplayer bookmark.
* Converted all Shiite POPs and Shiite state religions to Sunni in the multiplayer bookmark.
* Created Kurdistan formable nation.
* Added decision for GPs to annex southern Yemen if all the southern Yemeni provinces are in their sphere.

## Country changes:
###### Balkans:
* Liferating reduction from 40 to 35 happens in 1860 instead of 1880.
* Imported GFM populations.

###### West Africa:
* Added extra cores for all Western African nations.
* Created decisions to form Toucouleur Empire and Mali.
* Created Adamawa as a puppet nation of Sokoto in 1836 and added a decision for Sokoto to annex it.
* Lowered Congo starting population by about 20%.

###### Ottoman Empire:
* Imported GFM populations.
* Most Kurdish populated provinces start under the control of the new Ottoman vassal Bohtan.
* Added the Badir Massacre event which kills a potion of the Christian population under Bohtani rule and begins an annexation war against Bohtan.

###### Mexico:
* Created a decision to refute American Manifest Destiny which removes USA cores from the West Coast if Mexico beats USA in a war while having no unclaimed cores. A secondary decision called Fulfill Mexican Manifest Destiny gives Mexico cores on all land west of the Mississippi River and starts a war with USA.
* Can gain cores on Central America, Philippines, Cuba, and Puerto Rico if Mexico is victorious over USA.
* Added Adopt 1857 Constitution decision that grants several political reforms and increases education reform by 1.

###### Persia:
* Imported GFM populations.
* Created several vassal states in 1836 and decisions to annex them.
* Added an event for the Khorasan revolt.
* Esablish the Dar al Funun decision now increases school reform by 1 level and gives 1 year of research points intead of 5.

###### China:
* Added Lost Substate modifier which gives +0.005 militancy per month and -1% tax efficiency for each substate that is not under the control of China. This modifier is removed by retaking the substates or westernizing.

###### Prussia:
* No longer owns Brunswick in 1836 scenario but still owns Brunswick in Multiplayer start scenario.

###### United Kingdom:
* Increased cost of Annex East India Company decision from 4 million pounds to 6 million pounds and reduced infamy gain from 40 to 30.

###### Iberia:
* Imported GFM populations.

###### Scandinavia:
* Imported GFM populations.

###### Algeria:
* Imported GFM populations.


#Version 0.7 - 10/16/2021
## Bug fixes:
* Fixed AI exiled troops getting stuck after a war.
* Irish POPs will be no longer migrate to Europe during the Irish Famine event when USA has lost a blockade war.
* Fixed bugged naval port in Medan.
* Event and decision tooltips now properly display the correct amount of infamy gained from acquire state, demand concession, and conquest cbs in scripted wars.
* Universal healthcare reform now properly gives +0.05% pop growth instead of +0.01%.

## Interface changes:
* Increased zoom distance threshold for the political map to be displayed.

## Map changes:
* Imported HPM terrain map.
* Reverted river thickness to normal levels so they look less ugly.
* Created Hong Kong Island off the coast of Hong Kong province.
* AI English Channel Crossing now connected to Hong Kong Island and Bombay. This helps the UK AI not be so useless in its Asian wars. Reminder that only AI can use this crossing and it is disabled for the player.
* Split Baltic States back into Estonia and Latvia states.
* Split Upper Egypt back into Middle and Upper Egypt states.
* Added dozens of new provinces in the Middle East and Central Asia.
* Split Arabia into Nejd, Trucial Coast, and Hedjaz states.
* Split Arabian Coast into Oman and Yemen states.
* Split West Afghanistan state into Herat and Kandahar states and split Eastern Afghanistan state into Qonduz and Pashtunistan states.
* Created Sarhad state from upper half of Baluchistan state.
* Created Tajikstan state from lower half of Kirghizia state.
* Created Akmolinsk state from upper half of Semirechye state.
* Removed strait from Jask to Dubai.
* Created Orkey and Shetland Islands province off the coast of Scotland.
* Changed trade goods in Zanzibar to market goods.
* Partitioned Champagne state between Amiens, Picardie, and Franche-Comte. Renamed Alsace-Lorraine into Alsace and created new separate Lorraine State.

## Gameplay changes:
* Redid starting army stacks for all major Great War participants in 1913 and WW1 scenarios to follow the 4 infantry, 1 cavalry, 5 artillery template.
* Added Declare Neutrality decision for small population non colonial nations. This sets a neutral country flag for the nation which prevents all wars and cbs to be used by and against the neutral nation. Except for Switzerland, AI nations will not enact this decision. A neutral country can cancel neutrality by enacting the Cancel Neutrality decision at the cost of 15 infamy.
* Added new Violate Neutrality cb that can only be used against neutral nations. If war is declared against a neutral nation using this cb, the target nation's neutral status is instantly removed and wars and other cbs will function normally against them. This cb does not have to be enforced in a peace deal in order to take effect.
* Made the bonus to internal migration attraction from the Migration Attraction province selector decision apply to an entire state instead of a singular province. This is a nerf as it makes it harder to move a mass amount of POPs to singular high liferating and gold provinces.
* New Great Game cb is unlocked after manifest destiny is invented. It lets great powers acquire states in Central Asia at the cost of 2 infamy.
* Lowered base supply cost of infantry by about 20%.
* Military logistics is a prerequisite for enacting four year draft and mass politics is a prerequisite for enacting mandatory service.
* Increased airplane base attack by 1.
* Moved Haber-Bosch process invention to Organic Chemistry. Has starting base chance of 0, Electricity and Synthetic Polymers give +1 and +4 discovery chance respectively.
* All government types can now use the Scorch Earth province selector decision when at war.
* Caucasian POPs can now migrate to Ottoman Empire, Persia, and Egypt if they are civilized during the Circassian Genocide event instead of just Ottoman Empire.
* Added new "Militancy Reduction" national idea that gives global -0.03 POP militancy.
* Migration Attraction province selector decision no longer needs to be unlocked from the national idea list. All countries start with the ability to use this decision.
* Removed -3% tax efficiency modifier from European Military Advisors modifier.


## Country changes:
###### Poland:
* Austria, Prussia, and Russia will get a Polish Uprising event sometime between 1846-1849 that will add the Polish Nationalism modifier to Polish core provinces and increase the militancy and consciousness of all Poles by 5.
* Neighbouring GPs can annex AI Krakow via decision after they get the Polish Uprising event.

###### United Kingdom:
* Irish Potato Famine modifier lasts 6 years instead of 5.
* Created a decision to end the Irish Famine up to 4 years early at the cost of 3 million pounds. AI is scripted to not enact this decision.
* Increased costs to annex Commonwealth nations.

###### Russia:
* Pyatigorsk, Vladikavkaz, and Åland provinces start under Russian control in 1836.
* Pacification of Circassia and Integrate Transcaucasia decisions no longer give cores on the annexed land.
* Provinces of Qaratal and Alma Ata start under the control of Xinjiang in 1836.
* Added decision to annex provinces of Qaratal and Alma Ata from Xinjiang.

###### Germany:
* German nations can now benefit from tiny, small, and medium nation triggered modifier bonuses. They were prevoiusly excluded from these bonuses.
* Sigmaringen province is its own seperate country under the sphere of influence and vassalage of Prussia in 1836. This allows AI Austria to instantly form the SGF if it wins the Brother's War against Prussia.

###### Scandinavia:
* Decision to form Scandinavia no longer requires owning Schleswig, Iceland, Greenland, or Faroe Islands.
* Iceland & Greenland are states in 1836.
* Created a decision that allows Sweden and Sweden-Norway to add Estonian as an accepted culture.

###### Italy:
* Added decision for Tuscany to annex Lucca in 1847.

###### Ottoman Empire:
* Added Mashriqi as an accepted culture in 1913 and WW1 scenarios in order to increase mobilization size.

###### Chile:
* Chile is now included in the list of countries that can form United Provinces of Río de la Plata.

###### Middle East:
* Redrew starting borders of Oman and Nejd.
* Split Yemen up into several nations and added a decision to re-form Yemen.
* Added a decision for GPs to annex Aden if it's owner is uncivilized and a vassal or sphereling of said GP.
* Hedjaz exists as a puppet of Egypt in 1836.
* Jabal Shammar and Annazah exist as new independent countries in 1836.
* Added decisions for Egypt and Turkey to annex Hedjaz, Annazah, and Sana province.
* Changed prerequisites for the Form Arabia decision to include owning all Arab culture group cores in the Middle East.
* Oman and Trucial States own a few Persian provinces along the coast of the Straits of Hormuz in 1836.
* Added Voyage to America decision for Oman that gives one year worth of research points.
* Added decision to let Oman accepted Swahili if they win the succession war with Zanzibar.
* Added extra 5% western civilization progress to most middle eastern nations.

###### Persia:
* Added decision to add cores on North Caucasus and Transcaucasia.
* Added decision to add cores on and conquer Herat. UK will get an event to go to war to free Herat if Persia uses this decision and conquers Herat.
* Provinces of Zahedan and Chabahar belong to Kalat in 1836.

###### Afghanistan:
* Split up western Afghanistan into the countries of Kandahar and Herat. Herat is independent and Kandahar is a puppet of Afghanistan.
* Created decisions to annex Herat and Kandahar.
* Added extra 10% civilization progress to Afghanistan.

###### Central Asia:
* New nations Kazakh Khanate and Akhal-Tekke exist in 1836.
* Redrew borders of Khiva, Bukhara, Kokand, and Badakshan.
* Changed prerequisites for Form Turkestan decision to include owning most states in Central Asia.

###### Egypt:
* Winning the 2nd Oriental War will remove Turkish cores from the Levant.

###### Netherlands:
* Batavia Reborn decision now turns West Java into a state.

###### Switzerland:
* Added Sonderbund civil war event.

###### Baltics:
* Increased liferating of Riga and Reval from 35 to 40.

###### China:
* Sichuan and Inner Mongolia are Chinese substates in 1836 instead of directly controlled by China.
* Retaking a treaty port will convert the trade goods in that province from market goods into fish.


#Version 0.65 - 10/16/2021
## Bug fixes:
* Fixed major immigration bug where a new world nation would be unable to receive any immigrants if a single province was blockaded.
* Lend to Egypt decision will no longer appear if Egypt doesn't exist.
* AI allies can no longer use the decision to end fake wars on behalf of the player.
* Hungarian Revolution event will now re-trigger for Austria if the player doesn't choose an option while a save game is being created and rehosted.
* Revolution and Counterrevolution technology flag event now triggers for all nations after researching Revolution and Counterrevolution.
* Liberate Balkans cb will now correctly release Serbia, Montenegro, and Greece after the Ottomans have been defeated.

## Interface changes:
* New models for aircraft carriers and province selectors courtesy of Panzerfaust1 from https://www.moddb.com.

## Gameplay changes:
* Added Expansionism invention to Revolution and Counterrevolution tech. This invention gives -0.02 monthly infamy decay.
* New World nations now get a small amount of base internal migration. This causes newly conquered provinces to fill with accepted culture POPs quickly so assimilation can occur.
* Middle class will no longer internally migrate. This was changed to prevent weird cases where some low population provinces would become majority clerks, clergy, or officers.
* Totalitarianism mobilization modifier lowered from +3% to +2%.
* Moved Submarine invention from Steel Steamers tech to Screw-propelled Steamers tech and added a -10% discovery chance before 1870.

## Country changes:
###### Italy:
* Added Italian cores to Venice in 1836.
* Italia Irredenta decision requires Italy to own Milan and Venice to enact.

###### Balkans:
* Countries will now have a choice to become Russian puppets after Russia wins the Russo-Turkish war instead of being forced to. AI Serbia, Romania, Bulgaria, and Montenegro will always say yes.

###### Danubian Confederation:
* Changed country color to burgundy.


#Version 0.64 - 10/16/2021
## Bug fixes:
* End of Reconquista event will no longer trigger for Portugal if the "Restore Order to Brazil" decision was used on a Brazilian nation that wasn't already a puppet.
* Japan can no longer enact multiple Meiji Restoration decisions.
* Dreadnoughts canned good cost increased to 120 from 12.
* Moved 10 infamy gain from accepting Egyptian surrender to refusing Egyptian surrender during the Oriental War.
* Mahdist Sudan will spawn as civilized if Kordofan is a state or uncivilized if Kordofan is a colony.
* Converted South German and South Italian POPs in Vienna and Rome in 1836 multiplayer start to German and Italian.

## Gameplay changes:
* Modern Divisional Structure tech increases combat width by 5.
* Consolidated several coal and iron RGOs across the world by increasing some mines and removing others. Total global and country production of coal and iron remains the same.
* AI uncivilized nations will no longer use promote clergymen national focus until after 1870. This was changed to prevent African AI uncivs from civilizing before colonial negotiations are unlocked.
* Increased base chance of discovering Wright & Langley's Aeroplanes invention.

## Country changes:
###### United Kingdom:
* Sarawak no longer has to be uncivilized in order for the UK to enact the North Borneo Protectorate decision. Sarawak still has to be AI controlled to use the decision.
* Indian states now start as vassals of the UK instead of the East India Company in 1836.

###### China:
* "Middle Kingdom" event will now annex both substates and Chinese culture vassal states instead of just substates.
* Added new "Unequal Treaty" negative modifier. Every time a treaty port is lost, this modifier increases global pop militancy by +0.005 and reduces max tariffs by 1%. Westernizing will completely remove this modifier and prevent more Unequal Treaties from being signed even if additional treaty ports are lost.

###### Scandinavia:
* Removed "has no unclaimed cores" prerequisite for forming Scandinavia.

###### Sarawak:
* Reduced starting civilization progress to 20%.


#Version 0.63b - 9/11/2021
## Bug fixes:
* Fixed Request Grants decision causing players to crash.

#Version 0.63 - 8/30/2021
## Bug fixes:
* Fall of Punjab/Sind/Burma events won't fire anymore unless the East India Company has started their respective annexation wars.
* Great War Reparations cannot be added onto a country that already has a Great War Reparations cb targeting them.
* Fixed bugged mine expansion decision in Yazrd province.
* Fixed bugged RGO in Harare province.
* End of Reconquista event will no longer fire for Portugal if it enacts the Restore Portugal-Brazil decision.
* Enacting the 1861 Consitution decision as Argentina will no longer cause Buenos Aires to secede. The secession will still occur if the decision is enacted by Argentine Confederation or any other Argentine minor.
* Fixed bug where a player couldn't receive anymore grant requests if they kept a previous grant request event popup open while a save was taken and a rehost occured.

## Map changes:
* Re-enabled Aden strait.
* Moved Curacao province from Zulia state to Lesser Antilles state.
* Moved Nice province from Provence state to Savoie state.
* Created new Rügen island province in Germany and added it to the Baltic Islands region.

## General gameplay changes:
* Removed trade deals. Most people did not know how to use trade deals, and in reality the only resource that would ever need to be directly traded between nations was iron, so it was decided that this system was unecessary.
* Removed "Allow POPs to buy from stockpile" button from the trade screen. Without trade deals, this button isn't needed anymore.
* When Great Wars are invented, all human players will get an event to vote to enable or disable the Dismantle Nation cb. If yes gets more votes than no, the Dismantle Nation cb will be unlocked. If no wins or the vote is tied, then the cb will be disabled.
* Changed healthcare reform to be decision based. It can be raised or lowered at any time if prerequisites are met, and the reform level fixes social spending at a set amount.
* Reduced max province size of London, Vienna, Paris, Tokyo, Rome, Turin, Istanbul, Alexandria, and Cairo.
* Added new Urban terrain type.
* Added -2% tax penalty for every 5 infamy over 25, capped at -12% when above 50 infamy.
* Increased peacetime infamy decay from -0.033 to -0.05.
* Acquire small state and tiny conquest population threshold changed to <150k before 1860, <200k between 1860 and 1885, <300k between 1885 and 1910, and <450k after 1910.
* Minor conquest population threshold changed to <400k before 1860, <550k between 1860 and 1885, <800k between 1885 and 1910, and <1.2M after 1910.
* Chinese and Indian farmers are more likely to remain farmers when not targeted by a promotion national focus.
* Converted all French, British, German, Italian, and Hungarian Jews into Ashkenazi Jews in regular 1836 start date.
* Torpedo Boat gun and torpedo attack buffs from Main Armament inventions reduced from +3/+4 to +0/+2.
* Slightly reduced consumption of Torpedo Boats.
* All uncivilized nations except for China, India, and Japan get a +0.005 global population growth modifier for 5 years after civilizing.
* Added sulphur RGO buffs to chemistry technology line.
* Increased base iron rgo output from 2.2 to 2.5
* Reduced base coal rgo output from 2.5 to 2
* Buffed farming and mining idea RGO outputs from +20% to +30%.
* Annexing a cultural union sphereling via event now gives all cores of the sphereling to the spherelord.
* Install Communism cb can now be used against GPs.
* Reduced New World RGO size bonus from 10x to 6x
* Totalitarianism mobilization size modifier increased from +1% to 3% and added -30% mobilization economy impact buff.

## Country changes:
###### United Kingdom:
* Annexing Commonwealth nations now costs money.
* Refusing to fight the Opium War gives -20% prestige, choosing to fight and losing the war results in -30% prestige.
* Added tax efficiency buff to Unequal Chinese Treaty modifier.
* Reduced starting 1836 craftsmen POPs in London.

###### Germany:
* Bismarck's Reforms event now costs 500,000 to enact, also added a option to refuse the reforms.

###### Egypt:
* Removed 2 army reforms and added 1 economic reform to 1836 start.
* Made Muhammad Ali's Reforms decision cost 500k, reduced years of RP gain from 5 to 1, increased +RP modifier from 30% to 60%, and increased duration from 20 years to 30 years.
* Added decision to request 500k loan from human and ai civilized nations. Once a nation accepts the loan offer, a new decision called Repay Foreign Loans and a 30 year event modifier called Debt Timer will be added to Egypt. If Repay Foreign Debt isn't enacted before the Debt Timer modifier runs out, the nation that gave the loan gets an event to go to war and puppet Egypt.
* If Egypt is a puppet when the Mahdist Revolt event happens, Egypt's overlord will get the event to go to war with and annex Mahdist Sudan instead of Egypt.
* Added decision to add Sudanese as accepted culture.

###### Austria:
* Removed owns all cores requirement for Danubian Confederation decision.
* Austrian Form South German Confederation decision now changes Austria's tag to SGF and annexes all the South German minors. Becoming the SGF this way makes Austria/SGF lose all cores on non-German/Czech land and disables the Form Austria-Hungary and Danubian Confederation decisions.

###### Spain:
* Added Battleship Column Doctrine tech to 1836 start.
* Absolute monarchy requirement for reconquista decisions changed to absolute, semi-constitutional, or constitutional monarchy.

###### Portugal:
* Added Battleship Column Doctrine tech to 1836 start.

###### Ottoman Empire:
* Refusing the Egyptian Surrender event now gives +10 infamy.

###### Peru-Bolivia:
* Peru-Bolivia will become a democracy if it wins the War of the Confederation.

###### Sweden:
* Buffed Stockholm coal mine size.


#Version 0.62b - 6/15/2021
## Bug fixes:
* Fixed infinite money glitch for one of the province selector decisions.
* Fixed Russia not starting with the "Serfdom not abolished" flag in the regular 1836 grand campaign.


#Version 0.62 - 6/14/2021
## Bug fixes:
* Removed extra naval base in New Brunswick state that prevented ports from being upgraded.
* Claim Innger Angola decision will only transfer uncolonized land.
* Turkish Population Exchange event will not cause Bulgarians or Greeks to migrate if their respective countries don't exist.
* The Aceh Question decision no longer transfers Sekondi province to UK if it is not owned by Netherlands.
* Ottoman Empire starts as a GP before game starts in 1836 bookmarks and Tunis, Moldovia, and Wallachia are in it's sphere of influence.

## Map changes:
* Merged Macaronesia state with Estremadura, Western Sahara, and Senegal states.
* Created Eirunepé province in Amazonas state, in-between the border of Bolivia and Brazil. The province is owned by Bolivia in 1836 bookmarks.

## General gameplay changes:
* Buffed Martial Law negative militancy modifier from -0.07 to -0.1 per month.

## Country balance changes:
###### South America:
* Created Treaty of Ayacucho decision that transfers cores and ownership of newly created Eirunepé province to the owner of Tefe province.
* Reworked Treaty of Petrópolis and Vásquez Cobo–Martins Treaty decisions. Brazil does not start with cores on Taraucá or Marabitanas provinces and will gain cores on them only after enacting these decisions.

###### Africa:
* End Gaza Kingdom decision now requires inorganic chemistry instead of colonial negotiations.


#Version 0.61 - 6/9/2021
## Bug fixes:
* Fixed Guangzhouwan and Tientsin not appearing in acquire chinese concession cb.
* Fixed broken encourage craftsmen national focus bug for certain minor nations.
* Fixed starting wallonian literacy in 1836 multiplayer bookmark.
* Fixed a bugged condition in the form Rio Plata decision.
* Fixed bugged condition in the Annex Cape Colony decision.
* Fixed potetial exploit in the ask for grant decision that allowed the lender to hold multiple instances of the grant event and then pay more than they have in their treasury.

## Interface changes:
* Both naval mapmode and build naval base now use the "e" shortcut.
* Listed the buffs next to each national idea in the choosing national idea event.

## Map changes:
* Changed province shapes around in Anatolia.
* Moved a few provinces from Aydin state to Hudavendigar state.

## General gameplay changes:
* Removed truces from Scramble for Africa cbs.
* Taking chinese treaty ports will increase population of provinces below 30k to 20-30k.
* Halved bonus to attract immigrants province selector decision to new world nations.
* Reduced ask military access diplomatic cost from 5 to 2.
* All of North Angola reduced to 15 liferating, added a decision to colonize North Angola after mission to civilize is invented.
* Added 0.04 assimilation chance to assimilation national idea.
* Created cheat events 1-5. In order to use them, open the console and type "event x" replacing the x with the corresponding number. Event 1 increases literacy by 10%, 2 decreases MIL and CON by 5, 3 increases MIL and CON by 5, 4 assimilates all POPs, and 5 reduces infamy by 25.
* Removed regular clothes and luxury clothes from infantry and guards upkeep respectively.

## Country balance changes:
###### Egypt:
* Changed orient crisis surrender events to a decision which can be enacted at any time during the oriental crisis. AI is scripted to not enact this decision until 33% of it's national provinces are occupied.

###### Arabia:
* Forming Arabia will no longer give cores on sub saharan african nations.

###### USA:
* Increased starting literacy

###### France:
* Decreased starting literacy.

###### United Kingdom:
* Increased starting literacy.

###### Mexico:
* Removed CSA must exist condition from the Mexican Empire decision, it can now be done anytime after 1861.

###### Japan:
* Can trigger Boshin War at 40% civilization progress now, also removed the must be at peace condition. AI is scripted to not enact it until 50% civilization progress.

###### Sweden:
* Made it easier to form Sweden-Norway.

###### Denmark:
* Added Norwegian to starting accepted cultures.

###### Spain:
* Does not need to own Falkland Islands to create Viceroyalty of Rio Plata anymore.
* Cannot create a Viceroyalty via sphereing anymore unless the sphered nations are AI controlled. It is still possible to force human South American nations to become Viceroyalties if they are your puppet or you own all their core territory.

###### Portugal:
* Cannot use the Restore Order decision via sphereing anymore unless the sphered nations are AI controlled. It is still possible to use Restore Order decision on human Brazilian nations if they are your puppet or you own all their core territory.

###### Iberia:
* Removed Abandon Iberian Union decision.
* Cannot use Iberian Union decision if more than one of the constituents is human controlled.

###### Ottoman Empire:
* Imported HPM populations for southern Balkans and Anatolia.


#Version 0.6 - 5/28/2021
## Bug Fixes:
* Fixed endless Russian Civil War in 1913 and WW1 scenarios.
* Fixed requirements on the acquire state and demand concession cbs which allow it to only target coastal states, neighbouring states, or states that neighbour a neighbouring state.
* Added missing cultures for Belgium in 1836 multiplayer start.
* Fixed missing setup decisions for China and India in regular 1836 start. The lack of these decisions caused extremely fast Chinese and Indian westernization in v0.55 and v0.54.
* Existing Balkan countries no longer get Russian tech after Russia wins the Russo-Turkish War.
* Fixed Austrian cores not being removed from Hungary after Austria loses Hungarian War of Independence.

## Map Changes:
* A country has to either control or not be at war with the owner of Gallipoli in order to send navies through the Aegean Sea and Sea of Marmara. Enemies armies can land in Gallipoli from the Aegean Sea.
* A country has to either control or not be at war with the owner of Istanbul in order to send navies through the Gulf of Varna and Sea of Marmara. Enemy armies can land in a province adjacent to Istanbul from the Gulf of Varna and occupy Istanbul from land.

## General gameplay changes:
* New dismantle nation cb is unlocked after great wars are invented.
* Removed restrictions on acquire state and conquest cbs on west african countries at the start of the game. Colonial inventions still gives free no infamy conquest cbs on uncivilized african nations.
* Disabled all historical disaster, botanical expedition, nobel prize, olypmic, sporting, suffragete, and political random events for nations at war during the 1913 and WW1 bookmarks.
* Removed acquire massive state cb and allowed regular acquire state cb to target states over 4M pop.
* Conquest and establish protectorate wargoals can only be used on coastal nations or neighbouring nations.
* Total POP cap for make puppet cb increased from 2M to 5M after revolution and counterrevolution is researched.
* AI will not use the acquire core cb unless it has more brigades than or is already at war with the target nation. This should help prevent some of the endless loops of AI nations deccing for cores and losing every 5 years.

## Country balance changes:
###### USA:
* USA AI will now take all of its manifest destiny cores in one war instead of declaring separate wars.

###### China:
* Removed event that makes China instantly civilize if one of its substates civilizes.
* Added nerf to tariff/tax efficiency.

###### Japan:
* AI won't end sakoku on its own until 1860. USA can still force Japan to end sakoku through the Mathew Perry Expedition event.
* Boshin War decision now requires 50% civilization progress and can be enacted before and after civilizing.
* Imperial and Shogunate Japan don't start with cores on each other and only get the cores via the Boshin War decision.

###### Africa:
* Added new West and Central African kingdoms to 1836 start date.

###### Italy:
* Made Italian minors less likely to war each other at the start.

###### Austria
* Added decision to give up cores on Italian land if Italy owns Lombardia, Venice, and either South Tirol or Fruili.

###### Germany:
* Prussian AI won't fire ems decision until it has formed NGF.


# Version 0.55b - 5/11/2021
## Bug Fixes:
* Fixed countries starting with incorrect starting cultures in the Multiplayer Grand Campaign bookmark.


# Version 0.55 - 5/9/2021
## Bug Fixes:
* Fixed a few broken surrender events in WW1 scenario.

## Interface changes:
* Moved the normal Grand Campaign bookmark to the top of the scenario list.

## Map Changes:
* Merged Oldenburg state with East Frisia state.
* Changed shapes of Undine and Belluno provinces in Italy.
* Added province named "AI English Channel Bridge" next to Cantebury. This province has a strait crossing with Dunkirk and allows the AI to move troops across the channel without transports. If a human player owns Cantebury or Dunkirk, the province will automatically flip over to the World Bank and the land bridge will be closed. If Cantebury and Dunkirk become owned by the AI, then the new province will flip to the owner of Cantebury.

## General gameplay changes:
* Added decision that allows players that own vassals to declare a fake war on a non-existant country tag so they can command their puppet's troops when not in a real war. The fake war can be ended at any time via decision.
* Provinces with RGO expansion modifiers will now keep their modifiers if the province changes ownership or changes colonial status by the addition of a new province core mechanic. Provinces are hard coded in Vic2 to lose all province modifiers when they change owners or colonial status. The new mechanic works around this by adding a utility country core to any provinces that have received an RGO expansion, then a decision is enacted by the world bank which re-adds the relevant RGO expansion modifier to any provinces that have the new utility core tag and have lost their RGO expansions.
* Tweaked army composition and locations for most major nations in the 1913 and WW1 scenarios to be even more historically accurate. Engineers were removed from most armies to keep their infantry to support ratio closer to even because of game mechanics.
* Nerfed starting colonial soldier pops and colonial soldier pop promotion in 1913 and WW1 bookmarks because they were used much more rarely in real the real war than they are in game. Colonial soldier promotion remains the same in the 1836 starting bookmarks.

## Country balance changes:
###### West Africa:
* Increased starting pop by 33%.

###### South Africa:
* Increased starting pop of Xhosa by 100% and Matabele by 200%.


# Version 0.54 - 4/30/2021
## Bug Fixes:
* The Platine War and War of the Triple Alliance should no longer fire if Brazil is a puppet.
* Fixed bugged Conquest of Sindh decision for East India Company.
* Added status quo wargoal to both sides in the Great War scenario that prevents additional wargoals being added. This prevents some bugs that occur from non-scripted territory being transferred before the scripted surrender events fire.

## Interface changes:
* Added new settler province modifier icons for new colonial policy mechanic.

## Map Changes:
* Agadir province transferred from Western Sahara to Morocco state.
* Split up Nevada-Utah states into Nevada and Utah. The AI in Vic2 prefers to take states have the most number of its own provinces bordering it, so splitting Nevada-Utah makes the US AI prioritize taking Texas.
* Merged several provinces in Siberia.

## General gameplay changes:
* Added new 1836 Multiplayer Grand Campaign bookmark which features half as many cultures and 26% less individual POPs for increased stability.
* Changed Colonial Policy reforms to Colonial Migration reforms. Each level adds a bonus to colonial migration at the cost of tax efficiency. Colonial Migration reform level can be raised or lowered at any time via decision.
* Added a province selector decision that allows players to choose one of two colonial policies for individual colonial states. Indirect Rule prevents colonists from migrating to the chosen state while Settlement allows colonial migration but gives +0.05 militancy modifier and lowers the non-accepted population of the state by 1% annually. The colonial policy of a state can be changed at any time.
* Added new tutorial section for colonial migration and colonial policy.
* Lowered supply consumption of submarines, cruisers, and ironclads.
* Autonomous dependencies, tribal societies, and theocracies can flip to other governments if they are broken by rebels of that type.
* Made draft law reforms require the "Force through Reform" modifier to pass.
* Increase R&D decision automatically raises R&D reform to the highest possible level based on literacy instead of step by step.
* Added Yucatan tag and gave it cores on Yucatan state in Mexico.
* Human controlled nations receive 2000 ammunition, canned food, small arms, and artillery at the start of the 1913 and WW1 bookmarks.
* Merged Greek Civil War into The Great War in WW1 bookmark.
* Moved around a few French and Italian armies closer to the front in 1914 scenario.

## Country balance changes:
###### CSA:
* CSA Manifest destiny can't be enacted until the Civil War is over.

###### Mexico:
* Added an event that gives the option to end the war with Texas if Mexico has 3 war exhaustion. AI will always choose to end the war.
* Added Yucatan revolt event.

###### Brazil
* Brazil will lose cores on countries that successfully win their independence wars against it.

###### UCA:
* Gained cores on Tapachula and Tuxtla provinces in Mexico.

###### Austria:
* Increased starting soldier POPs.

###### Germany:
* Added XVIII Army to the 1913 and WW1 oobs.

###### Ottoman Empire:
* Senussi Order is a vassal of OE in the 1914 bookmark.


# Version 0.53 - 4/9/2021
## Bug Fixes:
* Fixed a bug that allowed clergymen in AI nations to go over 4%.
* Fixed the event that is supposed to release all vassals from the Raj when the End of British India happens.
* Removed missing -0.01 infamy decay modifier from manifest destiny due to infamy decay not working with inventions.
* Removed port requirement for unciv naval reforms due to AI landlocked nations getting stuck on naval reforms because they are hardcoded to not switch to a different category of reforms until the current one is finished.
* Carlist Victory decision moves capital of Carlist Spain to Madrid.

## Map Changes:
* Moved Cabinada province from Bas-Congo state to North Angola state.
* Absorbed East Angola state into North Angola and South Angola states.
* Cabinda, Boma, and Mocamedes provinces are uncolonized in 1836.

## General gameplay changes:
* Changed the name of Pax Britannica country modifier to Hegemon and added +20% leadership on top of the other bonuses. Any Hegemon can lose hegemony by dropping out of #1 rank for 2 years and any country can become the Hegemon by being rank #1 while no other country holds the Hegemon modifier.
* Added Congo Conference decision for secondary powers which allows all GPs to vote yes or no for the creation of the Congo Free State. If yes gets 5 or more votes, the Congo Free State will inherit all of the Congo and become a puppet of the country that fired the decision. Every province in the new Congo Free State will receive the Force Publique modifier which lowers pop growth rate until either the Heart of Darkness event fires in the Free State's overlord or the Free state gains independence.
* Reworked the Heart of Darkness event to only trigger for the overlord of Congo Free State and give the option of either +6 infamy or -20% prestige.
* Added decision for the overlord of the Congo Free State to annex it if the overlord has triggered the Heart of Darkness event and researched government interventionism.
* Added -0.05 Min. liferating colonization modifier to Prophylaxis against Malaria invention and moved +0.01 pop growth from Prophylaxis against Malaria to Aerial Bacteria and Antiseptic Principle.
* Lowered starting liferating of the Congo basin to 10.
* Lowered all positive discovery chance modifiers in Colonial Negotiations invention to 5 and added more potential bonuses.
* Buffed infamy decay from expansion national idea from -0.02 to -0.03 per month.
* The coring province event now requires nationalism and imperialism as a prerequisite and that a province is either coastal or adjacent to a cored province.
* Added Acquire core state for puppet cb that allows a nation to transfer a core state from the target nation to a puppet of the attacking nation. This cb costs 5 infamy compared to the 10 infamy of regular Demand for ally cb.
* Reverted Pan Nationalist rebels to vanilla properties and effects. The Crown from the Gutter event no longer triggers in the country that gets broken by pan nationalist rebels and only triggers for a great power of the same cultural union.
* Removed province specific New World Farm modifier that gave new world provinces +200% farm size and re-added the 10x farm size modifier to all new world provinces from the base game.

## Country balance changes:
###### United Kingdom:
* Changed the prestige loss from losing control of the Raj from -100 prestige to -25% prestige.
* Lowered starting draft law to no draft.
* Lowered infamy gain for annex Raj decision to 40.

###### United States:
* Lowered starting draft law to no draft.
* Slightly reduced 1913 and WW1 scenario soldier pops.

###### Austria-Hungary:
* Added an event that reverts Austria-Hungary back to Austria and removes Hungarian as an accepted culture if it doesn't own any Hungarian cores.

###### Congo Free State:
* Increased 1836 starting population by 15%.

###### Kongo:
* Lost Cabinda and Boma provinces, gained Mbanza province from Portugal.
* Added a decision to regain Cabinda and Boma provinces.

###### Portugal:
* Changed the Restore Order in Brazil decision to be able to be enacted once for each country that has Brazilian as a primary culture. The effects on each country remains the same, they will become an autonomous dependency of Portugal and their POPs will migrate to Portugal and vice versa.
* Changed prerequisites for Reform Portugal-Brazil decision.
* Removed free Restore Order in Brazil cb.
* Added a decision to retake Mbanza.
* Lost Mocamedes province in 1836 start.
* Added a decision to colonize Mocamedes.

###### South Asia:
* Muslim Indian nations can now form Pakistan via decision. Pakistan can no longer form India. Sikh Empire is not a muslim nation.

###### Egypt:
* Mahdist revolt no longer triggers if slavery is outlawed and citizens rights is not primary culture only

###### Balkans:
* Added an event that triggers in 1880 that lowers liferating of all Balkan provinces down to 35 except for the provinces of Sarajevo, Belgrade, Athens, Bucharest, and Istanbul.


# Version 0.52c - 3/30/2021
## Interface Changes:
* Removed background from the menu tabs.

## Bug Fixes:
* Fixed South German Confederation not having a primary culture.
* Fixed Romania and Serbia not getting annexed by Austria-Hungary if the Allies lose WW1 and they surrendered previously and then Bulgaria surrendered after them.
* Cleaned up history files.

## General gameplay changes:
* Assigned some leaders and moved some units around in the WW1 OOBs.

# Version 0.52b - 3/30/2021
## Bug Fixes:
* Sphereling tax efficiency bonus lowered from 40% to 4%.
* Viceroyalty of Rio Plata will no longer break up into Argentina and Buenos Aires.
* Revolution and counterrevolution condition was re-added to the Iberian Union decision.
* Restored 1836 Manchuria oob.
* Fixed a few localization errors.
* Dominican independence event won't fire more than once anymore.
* Disabled crisis temperature events from triggering when player chooses to disable crises at the start of the game.

## Map Changes:
* Removed strait from Balearic Islands to Barcelona.
* Created Chinca Islands sulphur province in Ica state, Peru. It's population in 1836 is majority Yue labourers.
* Changed trade goods of Puno province from sulphur to wool.

## Country balance changes:
###### Spain:
* Chincha Islands war event no longer gives an option to puppet Peru, instead it gives an option to take Chincha Islands.

# Version 0.52 - 3/28/2021
## Interface changes:
* Expanded the country modifier icon space in the politics tab. Country modifier icons are less likely to overlap now.

## Bug Fixes:
* Fixed 1836 starting OOB for China so it doesn't start with understrength divisions.
* Coverted a few engineer brigades that were meant to be artillery to artillery brigades in the German WW1 OOB.
* Nenetsia state now flips to the Russian Republic in the October Revolution event of the WW1 scenario.
* Colonial Policy event will no longer fire multiple instances for the same nation in multiplayer games.
* Can no longer use demand for ally cb for the World Bank or Ghostland.
* Made Jan Mayen impassable terrain. Units should not be able to reach Jan Mayen even with military access.
* Gwailor starts in the sphere of United Kingdom.
* Cleaned up target country migration factors for the Great Trek and Turkish Population exchange events.
* Fixed a typo in the Paraguayan victory event in the War of the Triple Alliance. Winning the war now annexes the state of Uruguay.
* Fixed name of Gizab in Western Afghanistan.

## General gameplay changes:
* Enabled ability to grant independence to individual vassals again. When the "Manage Vassals" decision is enacted, it will trigger an event which then triggers another event in each vassal nation. Each of those vassals then triggers a separate event to the overlord, and each of those events gives the overlord the choice to free the vassal that sent the event.
* Colonial migration nerfed by 40%.
* Primary and accepted culture POPs only promote to bureaucrats or soldiers in colonial states.
* Increased nerfs to tax efficiency, pop militancy, and added an event that triggers in the background that kills 1% of non-accepted POPs in colonial states every year for Settlement colonial policy.
* Re-added the ability for non-core provinces that are bordering a core to get the coring event.
* Increased MTTH for the coring event to 240 months and added a 60% reduction in time if the province has a plurality of accepted culture POPs. MTTH is increased by 200% if the province has 2 militancy, 400% for 5 militancy, and 1000% for 9 militancy.
* Provinces below 1.5k POP will increase their pop by 1% every year until they hit 1.5k POP. In the base game, provinces with population below a certain threshold don't have enough POP growth from regular modifiers to equal 1 or greater.
* Rebalanced naval stats so that early game ships give slightly more mil score. The balance of capital ships > light ships > torpedo boats/submarines > capital ships still remains the same.
* Removed post 1900 population growth nerfs.
* Rebalanced national values. Each national value gives a 5% bonus to research to either one or two tech trees and a 5% nerf to one or two tech trees. Organisation bonus removed from Order and +0.01 non-accepted militancy added to Liberty.
* Removed several vanilla decisions whose only effect was to give small amounts of prestige.
* Nerfed Education national idea from 20% to 15% education efficiency.
* Changed Army Supply national idea to Military Supplies national idea. The old -50% additive army supply modifier was made into a -15% reduction to all military supply requirements. The way old modifier worked, if army supply cost was 250% from tech, it would reduce army supply costs to 200%. Now it would reduce 250% to 212.5% and also applies to naval supply as well.

## Map Changes:
* Re-split Alejento state into Alejento and Macaronesia states.
* Re-added Extremadura state in Spain.
* Moved Canary Islands province to Macaronesia state.
* Moved Albacete province from Valencia state to Castilla la Nueva state.

## Country balance changes:
###### British Raj:
* If the Raj or East India Company are not a puppet of the UK and not a Great Power, they will be dismantled and their land will be given away to the countries that have cores on it. If Raj or the EIC becomes a GP at any point, they will not be dismantled if they lose GP status.
* Added -30% supply consumption and -3% tax efficiency to the Crown Rule modifier, the former of which makes Raj armies cheaper to supply but also lowers their military score by 30%. This should make the Raj less likely to become a GP once it civilizes.

###### United Kingdom:
* Added +0.01% global pop growth to the Pax Britannica modifier.
* Introduced a 2 year grace period to the UK before it loses the Pax Britannica modifier if it isn't rank #1 anymore. During this time if the UK becomes #1 again, the timer is reset and doesn't start counting down until it loses the #1 spot again.
* The event that breaks up the Raj/East India Company makes the UK lose 100 prestige.
* Annex Raj decision removes crown rule modifier and gives 50 infamy instead of 40.

###### Portugal:
* Added decision chain to puppet and eventually annex Brazil. Brazilian POPs will begin migrating to Portugal and Portuguese POPs will migrate only to Brazil as long as Brazil is a puppet of Portugal. Brazilian will be added as an accepted culture upon annexation.
* Added free restore order cb that allows Portugal to transfer Brazilian cores from other countries back to Brazil if Brazil is a puppet.
* Increased starting colonial soldier POPs and added a few more starting brigades in the colonies.

###### Spain:
* Starts the 1836 scenario in a civil war with an independent Carlist Spain. Either side can automatically win the war via decision if they have a bigger army than the other side and they control the provinces of Madrid, Bilbao, Zaragoza, Barcelona, and Valencia.
* Added decisions for Carlist Spain to recreate the old Viceroyalties of New Spain, New Granada, Peru, and Rio de la Plata. POPs from the Viceroyalties will begin to migrate to Spain and vice versa.
* Removed Embrace Filippino decision.

###### Iberia:
* Any country in Iberia can enact the "Abandon Iberian Union" decision, which disables the Unite Iberia decision for all countries including the one enacting it. AI will not enact this decision.

###### Brazil:
* Changed starting national value to Liberty.

###### Russia:
* Tsar of All Slavs cb no longer gives parts of Thrace or West Macedonia to Bulgaria.

###### Israel:
* Added "The Right of Return" event that makes Ashkenazi and Sephardic POPs only migrate to Israel if Israel exists.

###### Italy:
* Reverted the Redshirt rebels to vanilla properties and effects. They can no longer spawn in Sardinia-Piedmont and countries can't let themselves be occupied by redshirts to trigger the Italian Unification for themselves.

###### Sub-Saharan Africa:
* Increased 1836 starting population by 50%.

# Version 0.51 - 3/11/2021
## Bug Fixes:
* Fixed broken missing build time localization in the build army screen.
* Added missing SAF core to Durban.
* Moved newly created provinces in France and Italy from previous versions to the continent of Europe instead of Asia.

## General gameplay changes:
* Created an event that cancels military access from AI nations to other AI nations that are not either part of its sphere or allied to it. This event does not fire for humans and does not prevent humans from gaining access to neutral AI nations.
* Asking for military access now costs 5 diplo points in order to prevent AI from spamming it and firing the above event.

## Country balance changes:
###### France:
* Corsica changed to majority North Italian POPs and a minority of French POPs.

# Version 0.50 - 2/13/2021
## Bug Fixes:
* Fixed a bug in the base game where several slave countries started the game with no slaves even if they had slavery allowed and slaves in the starting pop files.
* Fixed Modern Naval Doctrine missing naval base increase.
* Added Italian and German cores to the new provinces created in v0.49.

## General gameplay changes:
* Added the Request Trade Deal decision that creates a trade agreement between two human players. Players with an active trade agreement can automatically send goods to each other once their stockpile of the chosen goods reaches 2000. A player may only have one trading partner at a time.
* Enabled "Allow pops/factories to buy from stockpile" button in the trade screen. NEVER enable this feature while you are manually buying goods or it will glitch the world market. In order to utilize the goods received from the new Trade Agreement system, the nation receiving the goods must enable the "Allow pops/factories to buy from stockpile" button and NOT manually buy or sell anything. The nation sending the goods must manually buy the goods it is sending and must have this button turned OFF.
* Increased max stockpile from 2000 to 2925.
* The Request Grant decision can now also be used to request a one time shipment of ammunition, artillery, canned food, and small arms. The player giving the resources must have set their stockpile to manually buy more than the requested amount in order for the decision to work.
* Added penalties to going over 25 infamy. The malus is -10% admin efficiency and +0.04 non-accepted pop militancy for every 5 infamy above 25, with the penalties maxing out at -60% admin efficiency and +0.24 militancy at 50 infamy.
* Changed the way the release vassal decision works. Instead of being able to choose to release each vassal individually, you now can only release all vassals at once. This was changed in order to increase performance because the old system required a separate decision for each of the 300+ country tags.
* Buffed submarine regular attack from 4 to 8.
* Replaced lumber with machine parts as an input good for steamer factories.
* Moved Synthetic Oil factory invention from Government Intervetionism tech to Synthetic Polymers tech.
* Colonial migration from colonial policy now scales down with higher country population.

## Map Changes:
* Changed starting borders and terrain of Afghanistan.
* Created Dagestan state out of part of North Caucasus state.
* Added a sulphur province to India.

## Country balance changes:
###### United Kingdom:
* Added decisions to annex commonwealth members at the cost of infamy. Canada, South Africa, Australia, and New Zealand can only be annexed while their governments are autonomous dependencies. British Raj can be annexed only while they are still uncivilized and after the Sepoy Rebellion has fired.

###### Boer Republics:
* Added permanent "Kommandos" country modifier that gives +10% mobilization pool.
* Added decisions to instantly civilize the states of Zululand and Eastern Cape, and remove Matabele, Basotho, Zulu and Xhosa cores once they are annexed by a Boer Republic.
* Added a decision to gain cores on all of South Africa once the states of Transvaal, Vrystaat, and Zululand are owned.

###### CSA:
* The A House Divided event removes USA cores on CSA and triggers another event in 6 months that begins the actual civil war. USA can only regain cores on the CSA by winning the scripted civil war event and annexing all of the CSA.
* Raise the Bonnie Blue Flag decision now spawns several historical confederate generals.
* Kelly's Irish Brigade decision turns 5 random Irish farmer POPs into soldiers.
* Added Confederate Manifest Destiny decision that gives cores on Chihuahua and Sonora.
* Added Complete The Golden Circle decision that gives cores on all of Mexico, Central America, parts of Colombia and Venezuela, and all of the Caribbean. The conditions for enacting this decision require owning all of Mexico.

###### Texas:
* Increased stats of Sam Houston to +5 attack and +5 defense.
* Added "Remember the Alamo!" country modifier that lasts for 30 days and gives +100% mobilization pool.

###### Mexico:
* Added an event to change Mexico from a presidential dictatorship to a democracy if it does not control Dallas and San Francisco.

###### Central America:
* All of Central America except for Guatemala spawn nationalist rebels at the start.
* Added an event to convert Federal Republic of Central America to Guatemala if the various nationalist rebels win.
* Created a decision to reform the USCA if it breaks apart.

###### Brazil:
* Added Praieira Revolt event.

###### Afghanistan:
* Imported HPM pop history files.
* Changed starting borders.
* Added a decision to accept Baluchi.
* Added Jezail Gunsmiths decision that unlocks local firearm production economic reform.
* Added Claim Greater Afghanistan decision that gives cores on Pakistan and Western Persia.

###### British Raj:
* Added a decision to go to war with Afghanistan over Baluchistan.
* State of Ceylon given to the UK.
* Reduced starting farm size by 60%. This was done by reducing farmer pop size in the history file by 60% and then increasing them back to their starting population when the game starts.

###### China:
* Removed the chinese farm modifier that gives -60% farm size and instead reduced farmer pop size by 60% in the history files and increased them back to their starting population when the game starts. This has the same effect of reducing farm size by 60%.

###### Central Asia:
* Imported HPM pop history files.
* Added a decision for Turkic Central Asian nations to form Turkestan. All Turkic speaking cultures will be added as an accepted culture and Turkestan will gain cores on all of Central Asia.

###### Persia:
* Imported HPM pop history files.
* Removed Hazara and Baluchi as accepted cultures.
* Begins the 1836 bookmark with slavery allowed.

###### Japan:
* Reduced starting techs in 1913 and WW1 bookmarks.

###### Hawaii:
* Reduced starting literacy to 2%.


# Version 0.49 - 1/18/2021
## Interface changes:
* Assigned the hotkey "e" to the naval base construction button. The tooltip will incorrectly show "e" as the hotkey for all province building buttons, but it only works for naval bases.

## Bug fixes:
* Added naval invasion penalty to a few provinces in Persia that were missed in 0.48.
* Fixed naval icons erroneously showing fort icons and vice versa when looking at the province tab of another country.
* Added Champassak to the release vassal decision.

## General gameplay changes:
* Request grant decision will now only ask human players you are not war with.
* Lowered supply consumption from several army techs and inventions.
* Slightly increased output of automobile factories.

## Map Changes:
* Made London a naval province.

## Country balance changes:
###### United Kingdom:
* Can no longer regain the Pax Britannica event modifier if it is lost.
* Lowered draft law to no draft in 1913 and 1914 scenarios.

###### British Raj:
* Lowered starting soldier POPS by 50% in 1913 and 1914 bookmarks.
* Increased British bureaucrat sizes by 3000% in 1913 and 1914 bookmarks. Raj now has enough British pops to have 3 national focuses.

###### India:
* Uncivilized India gets a modifier that prevents it from gaining research points from conquest.
* Starts with Foreign Weapons and Pre-Industrialization reforms.

##### United States:
* Lowered Statue of Liberty assimilation bonus to 50% and monthly prestige gain to 0.2.

##### Japan:
*Shogunate Japan and Imperial Japan will lose all their cores if one of them exists and the other doesn't.

##### Ottoman Empire:
* Halved assimilation bonus from Embrace Ottomanism decision in provinces that have a culture core.


# Version 0.48 - 1/4/2021
## Bug Fixes:
* Fixed existing countries sometimes inheriting and keeping the ghost province.

## General gameplay changes:
* Added a -2 attack modifier to all naval invasions. The value was bugged in base Vic2 HOD expansion and only applied to canal and strait crossings instead of coastal invasions.
* Rebalanced 1913 and WW1 factories to be more profitable.
* Lowered prestige monthly gain from the prestige national idea from 0.5 to 0.3.
* All existing countries in 1913 and WW1 scenarios have been given pre-selected national ideas.
* Doubled war exhaustion from combat losses.

## Map Changes:
* Re-split Patagonia state back to Patagonia Septentrional and Patagonia Meridional.
* Combined Corsica and Sardegna states into new Thyrrenian Islands state.
* Created 2 new provinces in Alsace-Lorraine and 1 new province in Franche-Comte.
* Created 1 new province each in Lombardia, Veneto, Molise, and Toscana states.
* Combined several provinces in Northern Canada.

## Country Balance Changes:
###### Germany:
* Forming NGF or Germany via decision will remove Prussian cores in all German cored territory. Forming Germany via nationalist rebels does not remove Prussian cores.

###### Russia:
* Removed starting cores in Congress Poland, Moldavia, and Lithuania.
* The October Revolution event now triggers a civil war between the Soviet Union and Russian Republic.

###### Poland:
* Polish minor countries can now become Poland if Poland doesn't exist and they own Warsaw and Lublin.
* Removed starting cores for PLC and added a decision to reform the PLC and gain the old cores.

###### USA:
* Nerfed USA mobilization in 1913 and WW1.

###### Austria-Hungary:
* Added Slovak as an accepted culture in 1913 and WW1 bookmarks

###### Heavenly Kingdom:
* Added Middle Kingdom modifier that prevents RP gain from conquest.
* The event that causes all chinese cliques to civilize once the main China civilizes now fires if Taiping civilizes.
* Will no longer turn into Beiyang or Nationalist China after the warlord event fires.

###### Finland:
* Reduced starting pop in 1913 and WW1 by 45%.

###### Haiti:
* Reduced starting POP of Dominican Republic and changed liferating of all Hispaniola to 40.


# Version 0.471 - 12/4/2020
## Bug Fixes:
* Fixed possible crash occuring with ghost country events.


# Version 0.47 - 12/2/2020
## General gameplay changes:
* Removed 1 army speed bonus from the Army Leadership tech line.
* Added tank and plane speed bonuses to military science tech line.
* Decreased base cost of forts and railroads, but added a scaling cost that doubles every additional level. When your POPs build railroads or you fund railroad projects built by POPs, you will not pay the scaling cost and only pay the base cost.
* Absorbed several cultures in Africa and Southeast Asia with <200K POPs into their neighbouring cultures in the 1836 starting scenario.

## Map Changes:
* Increased  movement penalty for mountain, hills, desert, marsh, jungle, forest, and arctic terrain.
* Increased railroad penalty for mountain, desert, marsh, jungle, and arctic terrain.
* Increased defense bonus to mountain terrain from 2 to 3.
* Changed terrain of several provinces in Siberia from forest to arctic.
* Changed Alsace-Lorraine provinces from woods to forest.

## Country Balance Changes:
###### Serbia:
* Removed Organize Greater Serbia and Organize Yugoslavia decisions.
* Claim Greater Serbia decision adds bosniak as an accepted culture.
* Added Become Greater Serbia decision that changes tag to Great Serbia.

###### Siam:
* Added Shan as an accepted culture.

# Version 0.46 - 11/27/2020
## General gameplay changes:
* Changed the way increase state literacy decisions works. It now gives a bonus to each POP in a state that's based on that own POP's literacy level and not the average literacy level of the state.
* Added -0.01 infamy decay to manifest destiny invention.
* Demand concession cb can now target capital states.
* Lower R&D level decision now instantly lowers R&D to lowest possible level instead of one at a time. Raise R&D level decision still only raises R&D level by one at a time.
* Slightly lowered unciv military reform cost and slightly increased unciv economic reform cost.
* Uncivilized East African countries can now be targeted by the Scramble for Africa cb once colonial negotiations are invented.

## Map Changes:
* Added a strait between Straits of Gibraltar and Gulf of Almería through Gibraltar. Ships cannot pass from one seazone to the other if they are at war with the controller of Gibraltar.
* Re-added the adjacency between Gibraltar and Tetouan.
* Removed adjacency between Calais and Canterbury.
* Combined Bukovina and Moldavia into one state.
* Gave provinces of Kursten and Deutsch Krone to Stettin state.
* Combined Emilia and Romagna into one state. Gave back Ancona to Lazio state and Lucca to Toscana state.
* Created new Rzeszow province in Lodomeria state.
* Made Luneburg a coastal province and created new state of Oldenburg from provinces from Hannover state.

## Country Balance Changes:
###### Southeast Asia:
* Siam and Vietnam can annex Cambodia and the Laotian kingdoms via decision if they are puppets.
* Added an event for the Siamese-Vietnamese war for control over Cambodia.
* Siam can add Lao as an accepted culture via decision.
* Great and Secondary Powers can annex uncivilized Vietnamese/Cambodian/Loatian territory via decision if they are neighbours and have certain techs.

###### Indonesia:
* Added several new Indonesian countries to the 1836 start.
* Added events and decisions for Great and Secondary Powers to annex these new countries.

###### France:
* Added a decision to go to war over Cochinchina if it's controlled by an uncivilized Vietnam.

###### Netherlands:
* Gave Maastricht to Belgium in 1836, province gets ceded back to Netherlands if the Treaty of London decision is enacted.
* Starts with a truce with Belgium until 1839.

###### Prussia:
* Added an event for AI Prussia/NGF that causes Austria/Austria-Hungary to lose its GP alliances around the time the Brother's War starts.
* EMS Dispatch decision will make France break alliances with Russia and Austria when Prussia/NGF is AI controlled.

###### United Kingdom:
* Added a decision to annex North Borneo and Malaya if they are controlled by an AI unciv.

###### Romania:
* Increased starting pop in 1836 and lowered liferating from 40 to 35 in all provinces except Bucharest.

###### China:
* Yunnan and Qinghai start as puppets of China.
* Added events for Panthay rebellion and first and second Dungan revolts.

###### Japan:
* Added "Invest in Korea" decision that increases relations/influence in Korea by 400 and grants Korea 5000 research points.

###### Sardinia:
* Removed starting cores from Lombardia.


# Version 0.45 - 10/31/2020
## Bug Fixes:
* Moved all ghost country related events from the World Bank to the newly created Ghost Country tag. Also fixed a bug where civilized countries would become uncivilized when they got annexed and triggered the ghost country event.

## General gameplay changes:
* Reduced immigrant attraction malus from from conscription laws to 0/0/-0.01/-0.02/-0.03.

## Map Changes:
* Added a strait between Oresund and Southern Baltic sea through Copenhagen. Ships cannot pass from one seazone to the other if they are at war with the controller of Copenhagen.
* Re-arranged states in Brazil.

## Country Balance Changes:
###### Austria
* Hungary starts the 1836 scenario as a puppet of Austria.
* Events for Hungarian Revolution added.
* Added a decision to form Danubian Federation, which turns the country into a democracy and gives Romanian, Slovak, Croat, and Slovene as accepted cultures.

###### Brazil:
* Amazonas state transfered from Grão-Pará to Brazil in the 1836 scenario.
* Added an event that gives Brazil the modifier Dom Pedro II, which grants a research points modifier bonus and lowered militancy.


# Version 0.44 - 10/28/2020
## Bug Fixes:
* Fixed broken Peru-Bolivian Confederation events.

## General gameplay changes:
* Added an event to enable or disable crises at the start of a campaign.


# Version 0.43 - 10/16/2020
## Bug Fixes:
* Fixed bugged ?s appearing in text where it shouldn't be.

## General gameplay changes:
* Redid a bunch of POPs and factories in the WW1 scenario to fix certain resource shortages.
* Lowered army and industry score requirements for tech school changes.
* Rebels will now get army techs via event 20 years after the the tech is unlocked.
* Lowered nerf to army experience from conscription laws.
* Slave POPs are set to be unemployed in all mining RGOs. This is necessary due to a bug in the base game which causes any province with a slave employed to be able to go over 100% RGO employment.
* Slave POPs now grow at a rate of 1% per year.

## Map Changes:
* Renamed Spa province to Eupen-Malmedy, changed its border, and moved it from Wallonie region to West Rhineland region.
* Created states out of the provinces of Danzig and Hamburg.
* Created Grão-Pará state out of provinces from Amazonas and Maranhão states.
* Split Santa Fe state into Córdoba and Chaco states.
* Added some more rivers around Paraguay.

## Country Balance Changes:
###### Latin America:
* Added Caudillos modifier to every latino country in the 1836 bookmark. Caudillos gives a malus to tech bonus and education efficiency and +0.02 mobilization pool. The modifier can be removed by decision once enough reforms are done or analytic philosophy is researched.
* Added Naval Arms Race events for Chile, Argentina, and Brazil.

###### Argentina:
* Argentina has been split up into Argentine Confederation, Entre Rios, and Corrientes in the 1836 start.
* Added platine war event that lets Argentine Confederation form Argentina.
* New alternative decision chain to fight Argentine civil wars and form Argentina.
* Patagonia and Chaco now start as uncolonized land. Decisions have been added to take them before colonial negotiations are unlocked.
* Can form United Provinces of La Plata via decision.
* Argentinian Constitution decision now gives temporary boost to immigration.

###### Brazil:
* Brazil starts the 1836 bookmark in a unification war with the newly created Piratini Republic in Rio Grande do Sul, and Grão-Pará in the states of Amazonas and Grão-Pará.
* New events for Bahia, Maranhão, Riograndense, and Canudas revolts.
* Added a decision to become a democracy and gain a temporary boost to immigration.

###### Bolivia:
* Peru starts as a puppet of Bolivia.
* A triggered war occurs between Bolivia and Chile in 1836, if Bolivia wins it annexes Peru and forms Peru-Bolivia, if Chile wins then Peru gains its independence.
* Alto Paraguay starts as uncolonized land. A decision has been added to claim it before colonial negotiations are unlocked.

###### Paraguay:
* Added events and decisions that give army tech bonuses, builds forts, and increases mobilization pool.
* Added Paraguayan War decision, which triggers the War of the Triple Alliance. If Paraguay wins, it annexes and gains cores on Rio Grande do Sul, Paraná, and Corrientes.

###### Chile:
* Most of Araucanía starts as uncolonized land. A decision has been added to claim it before colonial negotiations are unlocked.
* Added Found University of Santiago decision that increases school reform.
* Added Valparaiso harbour decision that gives temporary boost to immigration.
* Added Chilean Revolution event.

###### Colombia:
* Added Colombian civil war event.
* The Panama canal decision now triggers an event grants independence to Panama. Colombia can accept Panamanian independence or go to war.

###### Uruguay:
* Added Uruguayan civil war events.

###### Venezuela:
* Added Federal War event.

###### Ecuador:
* Added Ecuadorean civil war event.

###### Haiti:
* Added Dominican Republic independence event.

###### Spain:
* Added Chincha Islands War event.

###### Italy:
* Added Expedition of the Thousand decision for North Italian countries. The decision spawns a 4/4 Guiseppe Garibaldi general and gives high militancy to Sicilian cored provinces.

###### China:
* Increased draft law to two year draft in 1913 and WW1 bookmarks.

###### Japan:
* Decreased draft law to two year draft in 1913 and WW1 bookmarks.

###### Ottoman Empire:
* Starts with Kurdish accepted in 1913 and WW1 bookmarks.


# Version 0.42 - 10/16/2020
## Bug Fixes:
* Fixed a bug that allowed instant free building of ships.

## General gameplay changes:
* The World Bank will now buy excess military goods from the WM and ensure that military factories can remain profitable even during peacetime.
* Tripled the amount of military goods factories  and rebalanced consumer goods factories in 1913 and WW1 bookmarks.
* Tweaked techs and OOBS for some minor nations in 1913 and WW1 bookmarks.


# Version 0.41 - 10/1/2020
## Bug Fixes:
* Fixed a game breaking bug in the WW1 bookmark that resulted in Darfur annexing the UK.


# Version 0.4 - 10/1/2020
## General gameplay changes:
* Added new supply depot and scorched earth decisions province selector decisions. A province with a supply depot will never suffer attrition. You can have up to a max of 1 supply depot per country and if a battle occurs in a province with a supply depot or that province gets occupied, that supply depot will be destroyed. The scorched earth decision lowers supply and raises attrition in the targetted state. Scorched earth lasts for 1 year, has a 6 month cooldown and can only be done by absolute monarchies and dictatorships during war.
* National idea techs are now free to research and you no longer have to choose between 2 different ideas in a group.
* Reworked and rebalanced literacy, emigration, migration, and colonial migration.
* Rebalanced several techs and decisions.
* Lowered cost of mine expansion to 500K to 1.5M pounds per province.
* Cruiser and submarine activation inventions moved back to the ship construction tech line.
* Gold mines that are not located in the world bank will run out of gold in ~25 years and revert back to whatever RGO they were producing before gold was discovered.
* New market goods RGO added and placed in newly created treaty ports in Asia.
* 2nd Grand campaign scenario removed.
* Added theorcracy and autonomous dependency government types.
* Removed GP requirement for the crown from the gutter event when pan nationalists win and allowed the country that falls to pan nationalist rebels to form the culturial union country as well.
* Added Partisan Rebels from HPM. Partisans spawn in occupied provinces during war and they flip provinces back to the original owner.

## Map Changes:
* Added more states and consolidated some in Italy, Africa, Russia, India, and China.

## Country Balance Changes:
###### United Kingdom:
* Canada, South Africa, India, Australia, and New Zealand start as dominions of the UK in the grand campaign scenario.

###### Commonwealth:
* New decision trees for all commonwealth nations.

###### Russia:
* Finland, Baltic States, and several Caucasian states start out as puppets of Russia in the 1836 scenario, with new decisions to eventually re-annex all of them.
* Tsar of all Slavs cb will release all Ottoman held cores to Serbia, Romania, Bulgaria, Montengro, and Greece instead of only partial cores.
* Added Circassion genocide event that causes mass transfer of north caucasian POPs from Russia to the Ottoman Empire.

###### Japan:
* Split Japan into the Shogunate Japan and Imperial Japan in the 1836 scenario.
* Completely reworked decision trees for both, with a new unique path towards civilization in Japan.
* Added ability to diplo annex Korea via decisions.

###### Germany:
* Germany doesn't start with cores on Alsace Lorraine anymore, it can gain them via the Ems dispatch decision.

###### Sweden:
* Norway starts out as a puppet, with a decision added to annex them later.

###### Netherlands:
* Added several decisions related to colonizing the East Indies.

###### Mexico:
* Included 2nd Mexican Empire civil war events and rebels.

###### Egypt:
* Added Mashriqi as an accepted culture.
* Removed ability to become Arabia or add Sudanese as an accepted culture.
* Increased liferating in all provinces in Alexandria, Cairo, and Upper Egypt states to 40.
* Added Mahdist Uprising events.
* Darfur starts out as an independent kingdom and an event to create a South Sudanese kingdom in Equatoria will trigger in the 1850s.

###### Ottoman Empire:
* Added Population Exchange event when Ottomans lose control of the Balkans. A mass exchange of Greek, Turkish, and Bulgarian POPs will occur between Greece, Ottomans, and Bulgaria.

###### Ethiopia:
* Increased starting POP to 2M.
* Split Ethiopia into several tribal factions in the 1836 scenario.
* Added new formation of Ethiopia decisions to the new Ethiopian tribal factions.

###### Somalia:
* Added several playable Somali countries to the 1836 scenario.

###### South Africa:
* Three new South African tribal nations added to the 1836 scenario.
* Orange and Transvaal start out as OPMs with a new event/decision chain to gain their historical borders.
* Boer Trek decision causes mass migration of Boer POPs from South Africa to Orange and Trasnvaal.

###### East Africa:
* Two new East African tribal nations added to the 1836 scenario.

###### West Africa:
* Two new West African tribal nations added to the 1836 scenario.


# Version 0.3 - 8/2/2020
## Bug Fixes:
* Fixed South East England and Ile de France states starting with their 1914 factories in the 1836 scenario.
* Fixed incorrect graphics icon in healthcare, pension, and school system reforms.
* Fixed a bug that would sometimes cause the game to crash when a province was occupied.

## Interface changes:
* Made event title font easier to read.
* Made the enact decision button easier to see.
* Color coded the titles of decisions. Historical decisions are white, generic country decisions are yellow, and province or state specific decisions are green.
* Added pictures to most events.

## General gameplay changes:
* Changed base maximum sizes for coal, iron, precious metals, sulphur, and oil RGOs to anywhere from 5k-30k and greatly increased their output efficiency. Mine sizes should reflect reality more and small POP provinces that historically had large levels of production can now achieve their historical levels of output. The starting POPs in these provinces that don't work in the mines have been converted to artisans. This change, combined with the decision to stop promotion of select mining RGO labourers, should reflect more historical levels of employment in mines as well. Mining employment went up over time during this period but in vanilla Victoria 2 it was the opposite.
* Labourers won't promote into craftsmen unless their RGO is full.
* Literacy decay has been introduced at a rate of 0.1% for every 10% literacy per year. A POP with 50% literacy will lose 0.5% annually and a POP with 100% literacy will lose 1%. High starting literacy nations need to promote clergy, pass reforms, and research education techs if they want to maintain or grow their literacy.
* Renamed clergymen to teachers and and reworked school reform mechanics. The base cap on teachers is now 2% and each level of school reform raises the cap by 0.5% up to 4% max.
* Reduced average literacy research point bonus from 4 to 2.
* Added extra reform category called Research and Development. There are 10 levels of R&D and each level gives +0.2 research points and -1% tax efficiency. The reform level can be chosen via new decisions.
* Removed neglected education triggered modifier.
* Replaced all crime modifiers with corruption modifiers. Corruption lowers local RGO efficiency and factory output. You can lower the chance of a province getting corruption by keeping your administration slider fully funded and raising state admin efficiency.
* Lowered base crime fighting % to 0 and raised max to 100.
* Reduced RGO size modifiers from techs.
* Split the expand RGO size province selector decisions into separate mining and agriculture expansion decisions. Agriculture works the same way as before, but mining costs a flat 1 million pounds regardless of the population size of the province.
* Added new statewide expand agriculture rgo decision.
* Removed establish financial center decision.
* Removed blood and iron decision.
* Removed tariff nerf to nations with 7.5M POPs or more.
* Reduced protectionism max tariffs from 100% to 50% and free trade factory input bonus from 10% to 5%.
* Removed modifiers for POPs located in their core provinces to assimilate to the current owner of the province.
* Renamed some culture techs and removed consciousness modifiers from the social thought tech line.
* Rebalanced airplanes by buffing attack, nerfing defense, increasing supply cost, and requiring primary culture POPs to recruit.
* Tweaked global assimilation rate modifiers for party and political issues.
* Tax malus slightly increased for settlement colonial policy.
* Indirect rule colonial policy no longer gives reduced non-accepted militancy.
* Army tech bonus to non-colonial nation removed.
* Removed tax malus for the recently passed reform modifier.
* Removed great power requirement for unification cb.
* Rebalanced pop promotion factors.
* Rebalanced POP needs.
* Made craftsmen and clerks not migrate to countries below 40% literacy.
* Nerfed prestige national idea from +1 monlthy prestige to +0.5 monthly prestige.
* Halved research point gain from conquest.
* Removed tax and admin efficiency nerfs based on population size modifiers.
* Added acquire siberian state wargoal that requires half the warscore and infamy of normal acquire state wargoal. This wargoal can be used only on the states of Tomsk, Irkutsk, Trans-Baikal, and Kamchatka.
* Imported HPM neighbouring provinces clause to all demand state wargoals. A player can only take neighbouring states, states neighboring a neighboring state, and coastal states as long as the player owns a port.
* Moved battleships and dreadnoughts to the construction and propulsion tech line and cruisers and submarines to the naval engineering tech line.
* Changed healthcare reform unlock dates from 1855/1870/1895/1910 to 1855/1870/1885/1900/1915.

## Map changes:
* Removed straits from Busan to Kyushu, Granada and Gibraltar to al Rif, and Yemen to Eritrea.
* Split and combined several states across the world to be more balanced.
* Rebalanced goods across the world.

## Music changes:
* Replaced some HOI2 tracks with EU4 tracks.

## Country Balance Changes:
###### Civilized Nations:
* Increased starting school reform level of several countries in Europe/America.
* Set starting R&D level to match starting literacy levels.

###### Balkans:
* Removed Balkan pop growth and RGO size modifiers from starting Balkan provinces.
* Increased most balkan provinces' liferating to 40.
* Removed truces from 1836 scenario.

###### United Kingdom:
* The Indian provinces of Dehli, Meerut, and Agra now start under the control of the Mughal Empire, which is a puppet of the UK.

###### Germany:
* Added Bismarck's socialist reforms event.
* Removed starting cores on Alsace-Lorraine. The cores are re-added in the Ems Dispatch decision. 

###### Austria:
* Removed ashkenazi from accepted culture.

###### USA:
* The Homestead Act now gives negative migration attraction to provinces located in east/south USA and a migration buff to provinces in the midwest/west.

###### Netherlands:
* Created a decision that annexes Luxembourg if the Netherlands owns the state of Wallonie.

###### Sardinia-Piedmont:
* Created a decision that adds south italian as an accepted culture.

###### China:
* Gave Taiping more starting provinces and split up the taiping civil war into two events. The first event releases Taiping, and the second event triggers the civil war one year later.
* Added 60% farm size nerf to every core province in mainland China.

###### Ethiopia:
* Reduced starting pop from 2.05M to 1.23M.

###### Sub-Saharan Africa:
* Reduced starting population of Sub-Saharan African nations by 50% and increased liferating from 32 to 35.


# Version 0.21 - 6/18/2020
## General gameplay changes:
* Fixed some bugs in the Gathering Storm and Great War scenarios.

## Interface changes:
* New UI design.


# Version 0.2 - 6/16/2020
## General gameplay changes:
* Added two scenarios starting in Jan 1 1914 and July 28 1914. The 1914.1.1 bookmark is an open ended campaign and does not feature a WW1 event because it is impossible to add multiple countries to the same war via events, and the 1914.7.1 bookmark starts with WW1 already underway.
* Removed admin points from province selector decisions.  All previous province selector decisions have alternate costs or maluses associated with them now. Some decisions were removed entirely.
* Added province selector decision that allows you to pass one reform without the approval of the upper house every 10 years. Other prerequisites must still be met, e.g. trinket healthcare cannot be passed unless a country has medicine researched and it cannot be less than 6 months since another reform was passed.
* Added ability to toggle non-accepted culture POP promotion on and off.  If a province only has 1 culture type of craftsmen, all POPs that promote into craftsmen in that province will assimilate into that culture. This is called the craftsmen exploit and it is hardcoded into the game. Turning off non-accepted craftsmen promotion prevents the craftsmen exploit from turning your primary/accepted POPs into non accepted POPs if it is done before any non-accepted POPs have become craftsmen in a particular province. The best way to use this decision is to turn off non-accepted culture craftsmen promotion at the start of the game then turn it back on once you've filled enough provinces with accepted culture craftsmen POPs.
* Increased chance of a POP joining a movement based on CON.
* Removed CON reducing effect of clergy.
* Increased militancy gain from POPs wanting reforms back to vanilla levels.
* Changed ideology modifiers for POPs.
* Added ability for communist upper house to revoke social reforms.
* Fixed missing brackets that prevented the smallpox and cholera events from firing.
* Added a negative modifier for research points that triggers whenever education funding for a country above 50% literacy falls below the whatever their current literacy level is. So at 50% literacy you need to fund education at 50% or you will lose research points, 90% literacy needs 90% education spending, etc.
* Increased max daily research points spent on research from 100 to 200.
* Increased normal rate of internal migration and removed the immigrant push from the province migration decision. The province migration attraction modifier itself was also reduced so that it will not capture all internal migration.
* Added tiny conquest CB that lets you annex a country with less than 150k POP for 5 infamy.
* Changed tech requirement for establish financial center decision to modern central bank system instead of fiat monetary system. The province you place the financial center in must also now have at least 90% literacy rate.
* Added +25% iron/coal production to mechanized mining tech and deleted advanced ore smelting process and pit coal inventions.
* Added +25% supply limit to basic chemistry and removed 25% supply limit from electricity.
* Decreased organisation and morale bonuses from tech. Armies should run out of organisation before manpower until 1890 tech.
* Nerfed experience gain from pyschology techs to vanilla levels.
* Changed colonial transportation penal policy to punitive labour. Punitive labour does not give increased colonial migration anymore.
* Increased administrative multiplier for settlement and indirect rule colonial policies. This number raises the required bureaucrat % in order to get 100% admin efficiency.
* Removed the military hospital bonus and infamy growth from geneva convention. The modifier now gives -0.02 war exhaustion and +10% supply consumption.
* Replaced admin points techs with national idea techs. Each tech triggers an event that lets you choose an idea group from a list, which then triggers another event that let's you choose between 1 out of the 2 ideas in that group. Each idea grants a unique bonus and you can only have a total of 6 ideas.
* Decreased build time of forts.
* Buffed cuirassier stats from tech.
* Increased penalty from switched production to include a -50% throughput modifier for several years.
* Lowered minimum level naval port to build cruisers from 4 to 3.
* Lowered max infrastructure of deserts by 2.
* Lowered gas attack dice roll modifier from 3 to 2.
* Removed pop growth bonus to small and tiny nations.
* Lowered max battle warscore to 25 from 50.

## Map changes:
* Split up some provinces in Ukraine, Latvia, and Manchuria.

## Country Balance Changes:
###### Ottoman Empire:
* Removed the embrace minority decisions and replaced them with embrace ottomanism decision that gives increased assimilation chance.

###### Austria:
* Removed embrace polish minority decision.

# Version 0.15 - 5/6/2020
## General gameplay changes:
* Fixed a few missing culture provinces in Africa.
* Fixed a bug where if AI UK or France didn't annex the coastal African nations they would perpetually truce break and declare war over and over again.
* Fixed a bug with change ideology decision that gave unlimited admin points.
* Removed RGO size bonus from strategic goods event modifier.
* Removed cooldown from reduce infamy decision.
* Lowered cost of assimilation decision from 500 admin points to 400.
* Lowered infamy cost from take capital and acquire massive state casus bellis from 15 to 12.5.
* Added smokeless powder invention that reduces ammunition factory input costs.
* Added option to ask for £100,000 in the request grant decision and removed option to request £4M and £8M grants. Anytime a transfer of over £2,000,000 occurs in game, for some reason it glitches and goes negative.
* Reduced infamy gain from geneva convention modifier.
* Bureaucrats will no longer promote or demote into anything unless they make up more than 1% of a state's population.
* Revolution and counterrevolution tech will automatically set a country's centralization level to unitary if it was on regionalism.
* Lowered minimum naval supply slider from 30% to 20%.
* Lowered minimum naval supply before attrition kicks in from 25% to 15%
* Lowered education slider expenses by about 40%.
* All uncivs except China can now gain researchpoints by conquest at the start without needing to pass any military reforms.
* Halved total blockaded modifier.

## Map changes:
* Rebalanced some grain, fruit, fish, and cattle RGOs.
* Re-arranged states in Mongolia and Poland.
* Split Manchuria into 2 states and doubled the number of provinces in each.
* Added 2 more provinces to North Zhili state.

## Country Balance Changes:
###### China:
* Nerfed chinese emigration.
* Introduced a "soft" cap of 1%, 0.5%, and 0.3% to soldier POPs in states above 1M, 2M, and 4M population if a pop is chinese. This soft cap can be exceeded if a national focus is used to encourage soldiers in that province, this only affects the rate of soldier promotion if no national focus is used.
* Removed the ability for human players to trigger the taiping rebellion early. Now it always triggers in 1851. China still cannot declare wars for acquire state or conquest before the taiping rebellion occurs.
* Removed mandate of heaven modifier.
* Added imperial examinations modifier. Imperial examinations give +100% admin efficiency and -30% research points. It can be removed via decision.
* Added early and late qing reform decisions. They both give a modifier that gives +2 daily base research points, however the early one also gives +0.2 global militancy and the later one can only be enacted in 1895.
* Changed the way boxer rebels work. When they capture a province, they kill 50% of the clergy and 3% of the all POPs in the province. When they enforce their demands by occupying the capital they remove 2 economic reforms, 2 military reforms, and both early and late qing reforms. Boxer rebels only spawn after China reaches 50% civilization progress.
* Disabled ability for China to gain research points from conquest. Not even passing military reforms can enable this. You'll have to enact the early qing reforms decision if you want to civilize quickly.

# Version 0.144 - 4/13/2020
## General gameplay changes:
* Fixed admin point cost reduction for change agricultural RGO decision that was meant to be introduced in v0.142.
* Fixed localization for healthcare reform. It now correctly displays how much pop growth you get per level.
* Reduced cost of change population ideology decision to from 600 admin points to 500.
* Re-added grain to the list of options in the change province agriculture decision.
* Rebalanced needs for different poptypes.
* Coffee packaging factory inputs changed from coffee beans and iron to coffee beans and paper.
* Added input reduction techs for cement in the metallurgy tech column.
* Added craftsmen promotion buff techs in the market functionality tech column.
* Reduced max naval port level by 1. Early Modern Naval Doctrine is now a prerequisite tech to unlock carriers.
* Buffed carrier range and hull value.

## Map changes:
* Combined two states in Persia.

## Country Balance Changes:
###### Russia:
* Reduced conditions to the Tsar of all Slavs decisions to 7 average militancy instead of 9 in any Ottoman held balkan state.

# Version 0.143 - 3/30/2020
## General gameplay changes:
* Reduced minimum spending on healthcare reform from 25%, 50%, 75%, 100%, and 100% to 20%, 40%, 60%, 80%, and 100% for trinket, low, acceptable, good, and universal healthcare levels.
* Removed minimum spending military spending on all war policies and added a maximum military spending cap for anti military and pacifism.
* Reduced emigration rate from POPs not having lifeneeds met.
* Changed malus for non semi constitutional monarchy, constitutional monarchy, and democracy immigration attraction from -99% to -90%.
* Internal Migration decision now costs 250 instead of 400 and the duration was reduced from 1825 days to 730 days.
* Converted some farmers to artisans in the history files. This should help some military goods be produced.

## Map changes:
* Fixed a province goods flip event that would change some chinese RGOs to opium in 1836. Now the event correctly fires in 1880.

## Country Balance Changes:
###### USA & Mexico:
* Increased starting soldier POPs.

###### China:
* Starts with mechanized mining tech now. This allows chinese artisans to build military goods from the start.

# Version 0.142 - 3/28/2020
## General gameplay changes:
* Fixed missing culture POPs in the province of Usumbura.
* Fixed level two pre-industrialization and level two industrial construction unciv reforms not giving civilization progress. They now give an additional 10% instead of 0%.
* Reduced cost of later levels of healthcare reform.
* Nerfed pop growth from early levels of healthcare reform.
* Increased popgrowth from chemistry technology line.
* Added reduction to steel factory input to all techs in the metallurgy technology line.
* Reduced minimum military spending from all war policies by 10%.
* Reduced admin point cost to change province agricultural RGO decision for all province sizes.
* Made the admin point cost for state suppression decision based on the size of the state.
* Added blockade cb that can be used to prevent immigration to New World nations for 10 years.

## Map changes:
* Fixed a glitched strait that connected Kuching to Al-Ahsa

## Country Balance Changes:
###### China:
* Moved start date for communist party in China and Nationalist China from 1890 to 1870.

###### France:
* Fixed End the Medina Monarchy decision.


# Version 0.141 - 3/19/2020
## General gameplay changes:
* Changed the way internal migration works so that arctic, desert, mountain, and jungle provinces will get normal amount of migration from the internal migration focus. Previously they only got a fraction of the effect.
* Buffed internal migration modifier.
* Made the AI not research the AP bonus techs since it can't use them.


## Country Balance Changes:
###### Russia:
* Added Tsar of all Slavs decision that starts a war with the Ottoman Empire to liberate all Balkan provinces. An event fires once 30% of Ottomans have been occupied with an option to end the war immediately in exchange for allowing the Ottomans to keep some land in the Balkans.

###### Greece:
* Fixed Megali Idea decision requiring a missing invention. Now it requires nationalism and imperialism tech.


# Version 0.14 - 3/12/2020
## General gameplay changes:
* Increased lifeneeds for all POPs.
* Removed gold labourer pop type.
* Nerfed output from gold mines.
* Removed secondary power requirement in the leave sphere of influence decision.
* Removed rgo throughput bonus from free trade.
* Removed province selector change mining rgo decision.
* Each unciv reform's research point costs have been recalibrated and they all unlock new technologies. Technologies activated from unciv reforms also carry over after civilizing.
* Removed the second row of finance and currency reform from uncivilized reforms and added an extra row to early industrialization and industrial construction.
* Moved some farming and mining bonuses from later techs to the first row of the industry and commerce techs.
* Removed wool fabric factories.
* Added wool as an input good for fabric factories.
* Removed liquor and wine from unit construction costs.
* Added 40 leadership to every country at the start.
* Strategic goods modifier no longer goes away if a province is conquered.
* Fixed a bug where building a level 7 naval base or fort caused the game to crash.
* Added carrier naval sprite.

## Map changes:
* Removed gold RGOs in Japan, Prussia, and China.
* Removed a few coffee bean provinces around the world at the game start. They are re-introduced later via event.
* Added an event to flip some provinces in China to Opium in 1880.
* Made the island of Comoros part of the Indian Ocean Territory state instead of South Madagascar.
* Moved a province from the state of Adana to Ankara.


# Version 0.13 - 3/6/2020
## General gameplay changes:
* Expanded the tech tree and rebalanced techs.
* Rebalanced issues.
* Rebalanced factory goods.
* Rebalanced RGO outputs and prices.
* Fixed immigration to ghost countries bug.
* Fixed a bug where pops couldn't demote into labourers.
* Added a decision that allows you to stop promotion of labourers from specific RGOs into craftsmen or artisans.
* Added a decision that changes the RGO of one province to precious metal. Can only be used once, and it requires the "fiat based monetary system" tech and the province to be cored.
* Removed the ability for the AI to use normal sized promotion focuses on non normal size states.
* Introduced new poptype "bankers". They only spawn in Jan Mayen and cannot be obtained by other AI or player countries. They can only work in gold mines and they buy unsold goods in the WM when the rest of the world cannot afford to buy them. They don't have infinite money or demand and they mainly help to keep some unprofitable RGOs and factories employed until natural world demand catches up.
* Changed name of Jan Mayen to World Bank and set the country to be last place in the rankings in order to make sure they are the last to buy goods from the world market.
* Changed monitors to submarines.
* Added new aircraft carrier naval unit.
* Removed pop promotion bonus for having everyday needs met, replaced it with a pop promotion bonus for researching social alienation and modern sociology.
* Removed RGO unemployment fix event.
* Removed issue requirement for tech school changes.
* Rebalanced lategame unit stats.
* Moved RGO bonus from distribution channels, tractors, haber bosch process, machine tools, nitroglycerin, and electrical lighting events to the techs themselves. Colonies get a fraction of the bonus from these inventions, previously they didn't get any bonus.
* Disabled most crises.
* Removed payments from no healthcare level.
* Moved some tax efficiency bonus from later financial institutions and monetary systems techs to private banks and no standard. This will help countries in the early game make more money while keeping overall tax rate later in the game the same.

## Map changes:
* Changed RGOs to create a more balanced early game economy with less overproduction and underproduction
* Fixed a bugged province in Brazil.
* Re-arranged some states in Japan.

## Country Balance Changes:
###### China:
* Fixed bug that allowed taiping to outlaw opium after they stopped existing.
* Can only enact the outlaw opium decision once now, if China loses an opium war then the decision is permanently disabled.

###### Sikh Empire:
* Increased starting soldier POPs and added some artillery to the starting army.


# Version 0.121 - 2/22/2020
## Country Balance Changes:
###### China:
* Made the outlaw opium decision appear in 1840 instead of at game start.

###### Prussia:
* Nerfed von Moltke to a 4/4 instead of 5/5.

###### Egypt:
* Added decreased supply consumption to Muhammad Ali's Reforms.
* Fixed the starting OOB so that the Army of the Nile no longer spawns in West Africa.


# Version 0.12 - 2/21/2020
## General gameplay changes:
* Added synthetic rubber and sulphur factories. They are unlocked by the synthetic polymer tech.
* Rebalanced issues.
* Rebalanced some goods needs.
* Added an invite european military advisors decision for unciv nations. It gives a boost to military research but comes with several drawbacks.
* Added event that flips some RGOs to coffee in the lategame.
* Renamed commerce raiders to torpedo boats.
* Fixed music looping issue.

## Map changes:
* Re-arranged some states in China to more evenly distribute population.

## Country Balance Changes:
###### China:
* Added "opium addiction" modifier that gives several nerfs. Also added a decision to get rid of the modifier that also gives whoever controls the state of Bihar an event to start an opium war against China. The opium addiction modifier can also be permanently removed once the warlord era event chain is completed or the year is 1900.
* Lowered liferating to 30 in most chinese provinces

###### United Kingdom:
* Added unequal chinese treaty modifier that gives a bonus to tax efficiency and goods demand so long as you control the state of Bihar and China has the "opium addiction" modifier. Should China remove the opium addiction modifier, you have the option to start an opium war to force them to become addicted to opium again.

###### France:
* Added fall of the second empire event that triggers when core territory is lost and the current government is an absolute monarchy.

###### Prussia:
* Die wacht am rhein decision now gives +2% mobilization pool for one year.



# Version 0.111 - 2/15/2020

## General gameplay changes:
* Fixed the warlord era event for China.
* Fixed a missing clause with country migration targets.
* Set internal migration to provinces with over 10% unemployment to 0 unless you use the internal migration decision.



# Version 0.11 - 2/6/2020

## General gameplay changes:
* Added coffee beans and tea leaves as new RGO types. Coffee beans and tea leaves are raw goods that are used to make coffee and tea from factories or artisans.
* Removed fruit and grain options from change agricultural RGO decision and replaced them with coffee and tea.
* Added a new poptype "Gold Labourers". Only gold labourers can work in precious metal mines and all income earned from the gold mines goes directly to the labourers instead of the aristocrats that owns the province. Goods demand of gold labourers was also increased to be several times higher than normal labourers. This ensures that 100% of the money earned by gold mining POPs gets distributed to the world market instead of getting lost in national banks.
* Changed the way general traits work. They now only give + attack or defense, and the amount they give is color coded and listed in the name of the trait so you can see how much bonus you get without having to hover over the general. Black text is +1, blue is +2, green is +3, red is +4, and white is +5.
* Increased cost to create general and admiral to 40 leadership points.
* Soldier POPs that are in a brigade that is commanded by a general cannot rebel anymore.
* Added decision to free vassals under your control.
* Added a new selector decision that recruits a 4/4 general.
* Added new selector decision to raise healthcare reform level.
* Added internal migration selector decision that directs internal migration to the selected province.
* Lowered AP cost for most selector decisions except for baby boom.
* Changed the baby boom province selector decision duration and limit. You can now use it on any state below 1M population and the modifier lasts 300 days plus an additional 300 days for every -100K population below 0.99M e.g. an 850K state would get 600 days of baby boom and a 50K state would get 2700 days of baby boom. The amount of POPs gained from the baby boom event follows a bell curve based on state size which means you get the most POPs from using it on states with around 500K population.
* Imported Sub-Saharan African nations and their respective populations from HPM.
* Added a clause to all conquering cbs that prevent them from being used on uncivilized Sub-Saharan African nations before colonial negotiations are invented.
* Added 2 new acquire Sub-Saharan African state cbs. The first one can only be used by uncivilized Sub-Saharan African nations against each other and cost the normal amount of infamy. The second cb can only be used by civilized countries with the colonial negotiations invention against uncivilized Sub-Saharan African countries and it costs no infamy.
* Disabled loans due to the bugged nature of interest payments not being paid out to lenders. AI nations also don't seem to pay back debt even when they have enough money to repay it which results in more unnecessary money being taken out of the economy. May re-introduce loans to human players in a later update.
* Added a request grant decision that lets players receive grants from other human players. Only works in multiplayer games.
* Rolled back some of the bonus to assimilation in the new world compared to the old world. Also added a bonus to assimilation to Africa after it was discovered that African provinces suffer the same hidden hardcoded penalty to assimilation as new world provinces.
* Reduced malus to promotion for non accepted culture and wrong religion in large and massive states.
* Rebalanced goods inputs and outputs for several factories.
* Rebalanced goods needs for POPs to make some goods more profitable.
* Disabled artisan wool fabric production. They were using up the entire world's supply of wool and leaving none to POP or military needs.
* Added rubber provinces in Brazil and Bolivia at the start date.
* Gave a triggered modifier bonus to immigration attraction to GPs.
* Extended secondary power status by 8 more places.
* Added nerf to colonial railroads. They now only give half the bonus as non colonial railroads.
* Set starting colonial policy of all countries to non colonial. Countries with colonies at the start of the game now get an event to choose which colonial policy they want to enact.
* Released Jan Mayen at the game start in order to be a placeholder for behind the scenes decisions and events. Jan Mayen cannot manufacture or be the target of cbs that take land and it starts with 0 population.
* Added ghost unit cleanup event that fires every 6 months. Any country that is mobilized or has ships remaining after being annexed will inherit a province from Jan Mayen for a month to allow them to disband their ships and demobilize.
* Added event that fires once every 10 years to fix 100% RGO unemployment in some provinces. Normally, if supply for a RGO good is higher than demand, POPs in a province with the oversupplied good will never be hired until world market demand exceeds supply. If a province gets occupied or is recently colonized, all POPs are set to 100% unemployment and if the good in that province is a commonly overproduced good like grain or fruit, those POPs may never become employed for the rest of the game. This event reduces world wide throughput in all RGOs for a few days in order to get those POPs working again. Once the effect wears off some unemployment should come back, but it won't be 100% unless that province gets occupied again.
* Added strategic goods RGO modifier to a few low population oil/rubber provinces that historically produced much more resources than the game represents.
* Split new world migration into 2 pools: North America/Oceania and South America. Roughly half the worlds pops will migrate to NA/Oceania for the first 6 months of the game and the other half will migrate to South America. Then in July the POPs that would have migrated to NA/Oceania will now migrate to South America. This cycle repeats every year and ensures that at least 6 different countries in the new world can receive immigrants at any one time.

## Map changes:
* Changed country borders from a thin dotted red line to a thick solid red line.
* Changed impassable borders from a thin dotted blue line to a thick solid blue line.
* Changed state borders from a thin grey line to a thick black line.
* Changed province borders from a thin grey line to a darker grey thin line.
* Increased thickness of most rivers. This is a cosmetic change that does not affect combat.
* Changed country colors for Japan, Austria, Spain, Ottoman Empire, Netherlands, Sweden, Portugal, Egypt, Yugoslavia, Argentina, India, and Persia.
* Re-arranged some states in the Baltics, Caucasus, Central Asia, Colombia, Anatolia, Germany, Italy, and France.
* Changed terrain types in a few provinces in Ethiopia and Sinai
* Added strait crossings in Indonesia, Malay, Guinea, Singapore, Philippines, Madagascar, Yemen, and Cameroon
* Changed the Bosphorus strait into a canal that is already built at the start of the game. Ships can pass through the canal as long as Istanbul is occupied by their controller or is friendly/neutral with the occupier of Istanbul. Tt is no longer possible to cut off the Balkans and Anatolia with ships, you must occupy Istanbul to separate them.

## Country balance changes:
###### China:
* Added Warlord Era event that splits China into several warlord cliques. If China civilizes and has either 4+ militancy or 1%+ revanchism, the event will trigger with a MTTH of 12 months. Becoming a democracy prevents the event from triggering.
* Added decision that allows China to become a democracy if it has enough political reforms passed.
###### Arabia:
* Removed GP requirement for forming Arabia.
###### Egypt:
* Added a decision to accept Sudanese culture.
* Added conquest of Darfur and Equatoria decision.
* Gave a mobilization pool boost to Muhammad Ali's reforms.
###### Ethiopia
* Added conquest of Southern Ethiopia decision.
###### Ottoman Empire
* Added conquest of Libyan Desert decision.
###### France:
* Added decision to form the 2nd French Empire.
###### Spain:
* Starts with culture tech school.
* Removed GP requirement from the Unite Iberia decision.
* Added a decision that disables the Unite Iberia decision and enables the Embrace Filipino minority decision. Can only be done in multiplayer games where both Portugal and Spain are played by humans.
###### Portugal:
* Starts with culture tech school.
* Changed economic policy of starting conservative party to protectionism instead of free trade.
###### Prussia:
* Buffed von Moltke's Reforms decision.
###### Romania:
* Wallachia and Moldavia are no longer puppets of the Ottoman Empire but they start under the Ottoman sphere. The form Romania decision available to human players at the start of the game no longer annexes Wallachia and Moldavia, it simply changes your country tag to Romania and releases you from your current spheremaster while giving you cores on the rest of Romania.



# Version 0.101 - 12/22/2019

## General gameplay changes:
* Lowered AP gain from tech. The max AP you can generate per year is now 300.
* Reduced emigration rate sightly.
* Increased effect of Change Ideology decision from 0.2 to 0.25.
* Nerfed badboy reduction from Reduce Infamy decision from 0.3 to 0.25 and increased cooldown from 2 years to 5 years
* Nerfed literacy gained from Increase Literacy decision from 0.25, 0.2, and 0.15 for small, medium, and big states to 0.2, 0.175, and 0.15.

## Country balance changes:
###### Germany:
* Made forming Germany via decision turn the government to federalism instead of unitary.



# Version 0.10 - 12/21/2019

## All-new game mechanics:
* Province Selector buildings and their associated decisions have been added as a way to give players unprecedented control over their POPs and provinces. When playing an uncivilized nation, you must restart your game after you civilize in order to build province selectors due to a bug in the way the game stores invention files.
* A new resource called Admin Points has been introduced as a cost to enact these new Province Selector decisions. You gain a base stipend of 100 AP per year plus extra for each level of economic thought researched. Each province selector decision costs anywhere from 250 to 1000 AP.
* The new decisions are  organized into three categories: country, state, and province level. The player can dynamically choose exactly what the target of each decision will be. Some examples of new decisions are increasing literacy, increasing draft laws, accelerated assimilation, encouraging soldiers, lowering militancy, changing ideology, switching RGOs, boosting RGO throughput, and more.
* Province Selector decisions and Admin Points can be permanently disabled for all players by enacting the "Disable Province Selector" decision at the start of the game. The decision is available only in the first month. If you are playing in a multiplayer game and you have a player on the UK, then only the UK player can enact the decision.

## General gameplay changes:
* HPM reforms have been ported over. Most have a similar effect.
* Almost all random events have been deleted. Most of their effects were included in the new Province Selector decisions.
* Non accepted culture POPs and overseas POPs cannot join a non nationalist rebel movement. Overseas is defined in game as not connected to the capital and on a different continent, so you can still get occasional ideological rebels in provinces that have no way to reach your capital, but this should be extremely rare now.
* Triggered country size modifiers come into effect at 1M, 3.5M, 7.5M, 17.5M, 30M, 60M, and 120M POPs. These mostly affect things like tax efficiency, tariffs, and admin efficiency. Smaller nations get a bonus to these while larger nations get a nerf.
* Assimilation has been reworked so that all POPs have a chance to assimilate that is based on lifeneeds, militancy, and literacy. It is now possible to assimilate a small amount of POPs in provinces with their culture core. POPs in provinces without a culture core will have 4x faster assimilation rate than POPs living in provinces with their culture core, and POPs in New World provinces have an additional 4x bonus on top of that. Your government's citizenship policy also has large modifiers on assimilation rate now. Assimilation rate and assimilation chance are two separate factors, if either one is 0 then no assimilation will take place. Note that if you look in the game files at the actual assimilation chances in the poptypes files, they will at first make no sense. This is because it discovered during the making of this mod that there are several hidden and hardcoded modifiers to assimilation depending on where the target POP is located, and new modifiers were created taking into account the effects of these hidden modifiers. POPs located in a culture core province outside the New World were found to have a hidden modifier that resulted in having 1/100th the listed assimilation chance as a POP located in a province without a culture core, and POPs in the New World have 1/10th and 1/1000th the listed assimilation chance for non culture core and culture core locations.
* Emigration rate has been changed to a more flat rate than in the base game. All Old World civilized countries start out bleeding a small amount of immigrants and that rate slowly increases as the game progresses without getting as extreme as vanilla levels. Chinese POPs will not emigrate so fully occupying China will not result in millions of Chinese immigrants. Non Chinese POPs in China will still emigrate.
* Immigration attraction changed so that war exhaustion gives a penalty. Being at war with a country also prevents immigrants from the country you're at war with from coming to your country.
* Being a sphereleader or sphereling gives a bonus to immigrant attraction between the two countries.
* There are seperate promotion factors for POPs in states below 2M population, between 2M-4M population, and 4M+ population. POPs in states under 2M have normal promotion, POPs in states between 2M-4M have roughly 1/2 the normal promotion rate, and POPs in states above 4M have roughly 1/4 the normal promotion rate. This means a POP in a state of 8M will only promote twice as many POPs as a POP in a state of 1M.
* Promotion national focus has been split into normal state, large state, and massive state national focuses. Normal promotion national focus can only be used on states below 2M POPs, large state national focus on states between 2M-4M POPs, and massive can only be used on states over 4M POPs. Large and extra large state promotion focuses give 2/3 and 1/3 the promotion bonus as normal state promotion focus.
* Disease events have been reworked to be more logical. In vanilla, most disease events have a % chance to fire for every country, and when a disease event fired it would then target one single province or state in that country. The % chance to fire similar for every country no matter the size. This meant that the chance of cholera breaking out in one particular province was lowered simply by conquering more provinces. This didn't make sense as the conditions to develop cholera should depend on the level of sanitation and public health in that specific province. All disease events now either affect the entire country, or have a % chance to fire in a particular province that is independent of the country's size. The influenza event now gives a country modifier called "immunity" that prevents you from catching the same influenza for the next 10 years. This will stop the influenza ping pong that sometimes happens when you border many smaller nations.
* Clergy and bureacrat costs have been increased. Base literacy gain decreased to make clergy more important. It is not uncommon to not be able to fully fund education, admin, and soldiers at the start of the game.
* Healthcare reform will be your main source of POP growth and it is funded by the social spending slider. Each level of healthcare reform must be funded a certain minimum % to receive any benefits at all, and the reforms are massively expensive. The money spent on healthcare reform goes directly into the pockets of POPs and this has the secondary effect of stabilizing the world economy. When POPs have more money they can afford to buy more goods, which means your POPs can also sell more of their goods, which means they make more money from their regular jobs. Even though it isn't historical, healthcare was designed to give POPs money in order to force players to give money back to their POPs if they want POP growth, otherwise there would be no incentive to fund the social spending slider.
* Pharmaceuticals and cigarettes introduced as new consumer goods. Pharmaceuticals require opium as an input good and is unlocked after researching medicine while cigarettes require tobacco and is available from the start.
* Fabric can now be made from either cotton or wool. Cotton fabric factories are the same as vanilla, and the new wool fabric factories require 1/4 as much input as cotton factories while producing 1/4 as much output. Wool factories are usually more profitable early game if you lack dye due to them using 1/4 as much dye as cotton factories.
* A few raw goods RGOs such as coal and iron have been increased for multiplayer balance. RGO spread events from tractors, electrical lighting, nitroglycerin, machine tools, and distribution channels now trigger immediately in all non colonial states. They also trigger if you have the invention and conquer a non colonial state that doesn't have the modifier yet.
* A new revanchism mechanic has been introduced. For every 5 revanchism your country has, your mobilisation pool and maximum soldier pop % in cored territory goes up by 0.5% each. The bonus is capped at 5% and is calculated by number of core provinces lost, not by population size lost. The formula for calculating revanchism is hard coded into the game unfortunately.
* Laissez faire no longer has a tax cap. It provides a 3% output bonus to factory production and cheaper factory startup costs.
* Liberate, free people, and crises cbs no longer remove cores from the losing country. Added acquire small state cb that lets you take a state with less than 150k POP for 5 infamy, minor conquest cb that lets you annex a country with less than 400k POP and 2 states for 10 infamy, take capital cb that lets you take a country's capital at any time, and acquire all core cb that lets you take all your cores in one war.
* Soldier caps at 4%, 3%, and 2% for cored states with 1M, 2M, and 4M population. Non cored states over 1M, 2M, and 4M population have 2%, 1.5%, and 1% max soldier caps.
* SOLDIER_TO_POP_DAMAGE ratio increased from 0.2 in vanilla to 0.25 which results in 4 to 1 casualty to death ratio compared to 5 to 1 in vanilla. POP deaths from soldier casualties is calculated as SOLDIER_TO_POP_DAMAGE/(1 + military_hospital modifier). Military hospitals and geneva convention now give up to a combined 20% military hospital modifier, so the final value for POP deaths from soldier casualties if all techs and the geneva convention are unlocked is 0.25/(1+0.2) = 0.208, or roughly 4.8 casualties to equal 1 pop death.
* Lategame artillery support and defense has been nerfed. Now artillery only has roughly 2x more defense than offense after all techs are researched.
* Guards are strictly better than infantry, but cost twice as much. Tanks now have 25% support which means they can attack at 25% effectiveness from the backline and can only be recruited from primary culture POPs.
* Battleships and dreadnoughts received buffs, cruiser torpedo attack was removed completely, commerce raiders normal gun attack almost completely removed and replaced with large bonuses to torpedo attack, and max wooden ship HP reduced. Torpedo attack is a special type of attack that only affects big ships and deals no damage to light ships, making commerce raiders almost useless versus cruisers but deadly in numbers against big ships. The meta is big ships > cruisers > commerce raiders > big ships and if you build too much of one type of ship you risk being countered by another.
* Spherelings receive a large tax efficiency boost to make being in a sphere not as crippling to your economy.
* States have been redrawn in various places to buff countries by either giving them more port provinces or combining states to make promotion go faster.
* Crises no longer give a prestige hit for not joining.
* Great War disarmament cb no longer automatically added to all countries in a great war. It costs 0 infamy and 0 warscore to demand, so you can still add it to all enemy participants. This is a multiplayer change to allow the prestige and reparations to be spread out amongst the alliance.
* Enabled adding cbs on puppet nations.
* Diplomat travel time reduced to 1 day.
* AI nations receive significant buffs. AI nations will have more population, bigger armies, bigger industry, and better tech than compared to vanilla.
* Added straits between West Indies islands and Lesser Antilles islands.
* Added strait from Cadiz to Tangier, from Balearic Islands to Barcelona, and from Canary Islands to Tarfaya.
* Added a strait between Nagasaki and Chebu, and from Chebu to Kwangju.


## Country Balance Changes:
###### China:
* Starts with Chinese Isolationism modifier that reduces research point gain and prevents the use of acquire state and conquer cbs. This modifier will only be removed once the Taiping Rebellion occurs.
* Gave a decision to allow early triggering of the Taiping Rebellion when played by a human.
* Yunnan, Guangxi, and Qinghai all start as part of China.
* Only gets 20% of the bonus from mobilization techs and reforms
###### United Kingdom:
* Starting indian soldier POPs slightly nerfed
* The doctrine of lapse event to annex indian minors can still trigger even if the minor has more than 15 prestige
* Empress of India decision replaced with Establish the Raj decision. This decision triggers the Sepoy Rebellion, which causes all Indian puppets to be annexed into one country and a war to break out between the newly formed India and UK.  This allows the UK to annex all Indian minors at the time of their choosing. If this decision is not taken, the Sepoy Rebellion event will still occur once breech loaded rifles has been researched.
###### Russia:
* Stuck with serfdom, which gives a large malus to education efficiency, until either the year 1870 or they become a hms government/democracy.
###### Prussia:
* Gets an event in 1880 that reduces the liferating in Germany to 35.
* Forming NGF via decision or Germany via the crown from the gutter event locks the country into confederalism. Forming Germany via decision clears the confederalism flag and turns the country into a unitary state.
###### Austria:
* Added decisions to accept Czech, Polish, Slovenian, and Croatian cultures.
* Starts with a bonus to mobilization pool to represent the various ethnicities that could be mobilized in the Austrian Empire but can't  be represented with the base game mechanics due to not being accepted POPs. As you add more ethnicities to your accepted POPs, this bonus to mobilization pool will shrink until it eventually disappears.
###### Ottoman Empire:
* Added decisions to accept Mashriqi, Kurdish, Bedouin, Misri, Albanian, and Bosnian cultures.
* Starts with Christian Subjugation modifier that gives benefits to taxes and mobilization pool, but also gives an education penalty and pop militancy.
* The Oriental Crisis can be triggered via decision, and it gives the Ottomans a CB to puppet Egypt. Once Egypt is a puppet, a new decision appears that lets the Ottomans civilize Egypt and then annex them.
* Many balkan states start with large population boom modifiers that substantially increases their population in the first few years of the game.
###### United States:
* Removed all events relating to the civil war. The ACW has a chance to trigger starting in 1860 as long as slavery hasn't been abolished before then.
###### Spain & Portugal:
* Moved the Carlist rebels at the start of the game to Madrid. All you have to do is not kill the rebels and you will switch over to Carlist Spain when they capture Madrid.
* Added a decision to form Iberian Union as any Iberian culture country.
###### Italy:
* Italian Minors get an extra route to unify Italy. If a north Italian minor owns all of northern Italy plus Rome they can form Italy without needing the southern half, additionally if a north Italian minor owns Milan it gets a decision to automatically inherit most of northern Italy. If Papal States or Two Sicilies owns all cores of each other plus Tuscany and the island of Sardinia, they can form Italy as well.
###### Scandinavia:
* Any Scandinavian culture country can form Scandinavia without having to be a GP if they own Christiana, Stockholm, and Copenhagen
###### Low Countries:
* Gave Luxembourg to Belgium at the start.
* Gave the Netherlands Boer as an accepted culture.
###### Greece, Serbia, Romanian Minors:
* Every balkan minor country starts with a large population boom modifier that will have increased their population by 50-75% in the first few years of the game. Additionaly, while not country specific, the new revanchism mechanic and small nation triggered modifiers give extremely large bonuses to max soldier % and mobilization pools to these countries.
* Wallachia and Moldavia have a decision to form Romania that can be activated at any time when played by a human, and 1859 when played by AI.
* Serbia can form Yugoslavia if it owns all of its Serbian cores instead of having to own all of Yugoslavia.
* If Greece reclaims its cores in both Greece and Anatolia, it gets an event to increase its Greek population by 100% while reducing its Turkish population by 80%.
###### Mexico:
* Establishing the 2nd Mexican Empire turns the country into a hms government, gives a few reforms, and gives all POPs 10 militancy and 10 consciousness. The decision is available once the ACW begins and cannot be taken once the ACW is over.
###### South America:
* All South American starting POPs replaced with HPM starting POPs. In most cases this equates to anywhere from a 10% to a 100% increase in starting population.
* Argentina given a decision to become a democracy and pass several reforms all at once.
###### Uncivilized Nations:
* Reform costs were reduced
* Muhammad Ali's reforms, Dar al Funun, and Meiji Restoration decisions all buffed.
