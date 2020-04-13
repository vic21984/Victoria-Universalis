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
