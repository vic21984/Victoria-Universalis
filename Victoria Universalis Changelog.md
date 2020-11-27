# Version 0.47 - 11/27/2020
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
