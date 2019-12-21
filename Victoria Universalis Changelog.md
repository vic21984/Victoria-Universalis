#Version 0.10 - 12/21/2019

##All-new game mechanics:
*Province Selector buildings and their associated decisions have been added as a way to give players unprecented control over their POPs and provinces. When playing an uncivilized nation, you must restart your game after you civilize in order to build province selectors due to a bug in the way the game stores invention files.
*A new resource called Admin Points has been introduced as a cost to enact these new Province Selector decisions. You gain a base stipend of 100 AP per year plus extra for each level of economic thought researched. Each province selector decision costs anywhere from 250 to 1000 AP.
*The new decisions are  organized into three categories: country, state, and province level. The player can dynamically choose exactly what the target of each decision will be. Some examples of new decisions are increasing literacy, increasing draft laws, accelerated assimilation, encouraging soldiers, lowering militancy, changing ideology, switching RGOs, boosting RGO throughput, and more.
*Province Selector decisions and Admin Points can be permanently disabled for all players by enacting the "Disable Province Selector" decision at the start of the game. The decision is available only in the first month. If you are playing in a multiplayer game and you have a player on the UK, then only the UK player can enact the decision.

##General gameplay changes:
*HPM reforms have been ported over. Most have a similar effect.
*Almost all random events have been deleted. Most of their effects were included in the new Province Selector decisions.
*Non accepted culture POPs and overseas POPs cannot join a non nationalist rebel movement. Overseas is defined in game as not connected to the capital and on a different continent, so you can still get occasional ideological rebels in provinces that have no way to reach your capital, but this should be extremely rare now.
*Triggered country size modifiers come into effect at 1M, 3.5M, 7.5M, 17.5M, 30M, 60M, and 120M POPs. These mostly affect things like tax efficiency, tariffs, and admin efficiency. Smaller nations get a bonus to these while larger nations get a nerf.
*Assimilation has been reworked so that all POPs have a chance to assimilate that is based on lifeneeds, militancy, and literacy. It is now possible to assimilate a small amount of POPs in provinces with their culture core. POPs in provinces without a culture core will have 4x faster assimilation rate than POPs living in provinces with their culture core, and POPs in New World provinces have an additional 4x bonus on top of that. Your government's citizenship policy also has large modifiers on assimilation rate now. Assimilation rate and assimilation chance are two separate factors, if either one is 0 then no assimilation will take place. Note that if you look in the game files at the actual assimilation chances in the poptypes files, they will at first make no sense. This is because it discovered during the making of this mod that there are several hidden and hardcoded modifiers to assimilation depending on where the target POP is located, and new modifiers were created taking into account the effects of these hidden modifiers. POPs located in a culture core province outside the New World were found to have a hidden modifier that resulted in having 1/100th the listed assimilation chance as a POP located in a province without a culture core, and POPs in the New World have 1/10th and 1/1000th the listed assimilation chance for non culture core and culture core locations.
*Emigration rate has been changed to a more flat rate than in the base game. All Old World civilized countries start out bleeding a small amount of immigrants and that rate slowly increases as the game progresses without getting as extreme as vanilla levels. Chinese POPs will not emigrate so fully occupying China will not result in millions of Chinese immigrants. Non Chinese POPs in China will still emigrate.
*Immigration attraction changed so that war exhaustion gives a penalty. Being at war with a country also prevents immigrants from the country you're at war with from coming to your country.
*Being a sphereleader or sphereling gives a bonus to immigrant attraction between the two countries.
*There are seperate promotion factors for POPs in states below 2M population, between 2M*4M population, and 4M+ population. POPs in states under 2M have normal promotion, POPs in states between 2M*4M have roughly 1/2 the normal promotion rate, and POPs in states above 4M have roughly 1/4 the normal promotion rate. This means a POP in a state of 8M will only promote twice as many POPs as a POP in a state of 1M.
*Promotion national focus has been split into normal state, large state, and massive state national focuses. Normal promotion national focus can only be used on states below 2M POPs, large state national focus on states between 2M*4M POPs, and massive can only be used on states over 4M POPs. Large and extra large state promotion focuses give 2/3 and 1/3 the promotion bonus as normal state promotion focus.
*Disease events have been reworked to be more logical. In vanilla, most disease events have a % chance to fire for every country, and when a disease event fired it would then target one single province or state in that country. The % chance to fire similar for every country no matter the size. This meant that the chance of cholera breaking out in one particular province was lowered simply by conquering more provinces. This didn't make sense as the conditions to develop cholera should depend on the level of sanitation and public health in that specific province. All disease events now either affect the entire country, or have a % chance to fire in a particular province that is independent of the country's size. The influenza event now gives a country modifier called "immunity" that prevents you from catching the same influenza for the next 10 years. This will stop the influenza ping pong that sometimes happens when you border many smaller nations.
*Clergy and bureacrat costs have been increased. Base literacy gain decreased to make clergy more important. It is not uncommon to not be able to fully fund education, admin, and soldiers at the start of the game.
*Healthcare reform will be your main source of POP growth and it is funded by the social spending slider. Each level of healthcare reform must be funded a certain minimum % to receive any benefits at all, and the reforms are massively expensive. The money spent on healthcare reform goes directly into the pockets of POPs and this has the secondary effect of stabilizing the world economy. When POPs have more money they can afford to buy more goods, which means your POPs can also sell more of their goods, which means they make more money from their regular jobs. Even though it isn't historical, healthcare was designed to give POPs money in order to force players to give money back to their POPs if they want POP growth, otherwise there would be no incentive to fund the social spending slider.
*Pharmaceuticals and cigarettes introduced as new consumer goods. Pharmaceuticals require opium as an input good and is unlocked after researching medicine while cigarettes require tobacco and is available from the start.
*Fabric can now be made from either cotton or wool. Cotton fabric factories are the same as vanilla, and the new wool fabric factories require 1/4 as much input as cotton factories while producing 1/4 as much output. Wool factories are usually more profitable early game if you lack dye due to them using 1/4 as much dye as cotton factories.
*A few raw goods RGOs such as coal and iron have been increased for multiplayer balance. RGO spread events from tractors, electrical lighting, nitroglycerin, machine tools, and distribution channels now trigger immediately in all non colonial states. They also trigger if you have the invention and conquer a non colonial state that doesn't have the modifier yet.
*A new revanchism mechanic has been introduced. For every 5 revanchism your country has, your mobilisation pool and maximum soldier pop % in cored territory goes up by 0.5% each. The bonus is capped at 5% and is calculated by number of core provinces lost, not by population size lost. The formula for calculating revanchism is hard coded into the game unfortunately.
*Laissez faire no longer has a tax cap. It provides a 3% output bonus to factory production and cheaper factory startup costs.
*Liberate, free people, and crises cbs no longer remove cores from the losing country. Added acquire small state cb that lets you take a state with less than 150k POP for 5 infamy, minor conquest cb that lets you annex a country with less than 400k POP and 2 states for 10 infamy, take capital cb that lets you take a country's capital at any time, and acquire all core cb that lets you take all your cores in one war.
*Soldier caps at 4%, 3%, and 2% for cored states with 1M, 2M, and 4M population. Non cored states over 1M, 2M, and 4M population have 2%, 1.5%, and 1% max soldier caps.
*SOLDIER_TO_POP_DAMAGE ratio increased from 0.2 in vanilla to 0.25 which results in 4 to 1 casualty to death ratio compared to 5 to 1 in vanilla. POP deaths from soldier casualties is calculated as SOLDIER_TO_POP_DAMAGE/(1 + military_hospital modifier). Military hospitals and geneva convention now give up to a combined 20% military hospital modifier, so the final value for POP deaths from soldier casualties if all techs and the geneva convention are unlocked is 0.25/(1+0.2) = 0.208, or roughly 4.8 casualties to equal 1 pop death.
*Lategame artillery support and defense has been nerfed. Now artillery only has roughly 2x more defense than offense after all techs are researched.
*Guards are strictly better than infantry, but cost twice as much. Tanks now have 25% support which means they can attack at 25% effectiveness from the backline and can only be recruited from primary culture POPs.
*Battleships and dreadnoughts received buffs, cruiser torpedo attack was removed completely, commerce raiders normal gun attack almost completely removed and replaced with large bonuses to torpedo attack, and max wooden ship HP reduced. Torpedo attack is a special type of attack that only affects big ships and deals no damage to light ships, making commerce raiders almost useless versus cruisers but deadly in numbers against big ships. The meta is big ships > cruisers > commerce raiders > big ships and if you build too much of one type of ship you risk being countered by another.
*Spherelings receive a large tax efficiency boost to make being in a sphere not as crippling to your economy.
*States have been redrawn in various places to buff countries by either giving them more port provinces or combining states to make promotion go faster.
*Crises no longer give a prestige hit for not joining.
*Great War disarmament cb no longer automatically added to all countries in a great war. It costs 0 infamy and 0 warscore to demand, so you can still add it to all enemy participants. This is a multiplayer change to allow the prestige and reparations to be spread out amongst the alliance.
*Enabled adding cbs on puppet nations.
*Diplomat travel time reduced to 1 day.
*AI nations receive significant buffs. AI nations will have more population, bigger armies, bigger industry, and better tech than compared to vanilla.
*Added straits between West Indies islands and Lesser Antilles islands.
*Added strait from Cadiz to Tangier, from Balearic Islands to Barcelona, and from Canary Islands to Tarfaya.
*Added a strait between Nagasaki and Chebu, and from Chebu to Kwangju.


##Country Balance Changes:
######China:
*Starts with Chinese Isolationism modifier that reduces research point gain and prevents the use of acquire state and conquer cbs. This modifier will only be removed once the Taiping Rebellion occurs.
*Gave a decision to allow early triggering of the Taiping Rebellion when played by a human.
*Yunnan, Guangxi, and Qinghai all start as part of China.
*Only gets 20% of the bonus from mobilization techs and reforms
######United Kingdom:
*Starting indian soldier POPs slightly nerfed
*The doctrine of lapse event to annex indian minors can still trigger even if the minor has more than 15 prestige
*Empress of India decision replaced with Establish the Raj decision. This decision triggers the Sepoy Rebellion, which causes all Indian puppets to be annexed into one country and a war to break out between the newly formed India and UK.  This allows the UK to annex all Indian minors at the time of their choosing. If this decision is not taken, the Sepoy Rebellion event will still occur once breech loaded rifles has been researched.
######Russia:
*Stuck with serfdom, which gives a large malus to education efficiency, until either the year 1870 or they become a hms government/democracy.
######Prussia:
*Gets an event in 1880 that reduces the liferating in Germany to 35.
*Forming NGF via decision or Germany via the crown from the gutter event locks the country into confederalism. Forming Germany via decision clears the confederalism flag and turns the country into a unitary state.
######Austria:
*Added decisions to accept Czech, Polish, Slovenian, and Croatian cultures.
*Starts with a bonus to mobilization pool to represent the various ethnicities that could be mobilized in the Austrian Empire but can't  be represented with the base game mechanics due to not being accepted POPs. As you add more ethnicities to your accepted POPs, this bonus to mobilization pool will shrink until it eventually disappears.
######Ottomans:
*Added decisions to accept Mashriqi, Kurdish, Bedouin, Misri, Albanian, and Bosnian cultures.
*Starts with Christian Subjugation modifier that gives benefits to taxes and mobilization pool, but also gives an education penalty and pop militancy.
*The Oriental Crisis can be triggered via decision, and it gives the Ottomans a CB to puppet Egypt. Once Egypt is a puppet, a new decision appears that lets the Ottomans civilize Egypt and then annex them.
*Many balkan states start with large population boom modifiers that substantially increases their population in the first few years of the game.
######United States:
*Removed all events relating to the civil war. The ACW has a chance to trigger starting in 1860 as long as slavery hasn't been abolished before then.
######Spain & Portugal:
*Moved the Carlist rebels at the start of the game to Madrid. All you have to do is not kill the rebels and you will switch over to Carlist Spain when they capture Madrid.
*Added a decision to form Iberian Union as any Iberian culture country.
######Italy:
*Italian Minors get an extra route to unify Italy. If a north Italian minor owns all of northern Italy plus Rome they can form Italy without needing the southern half, additionally if a north Italian minor owns Milan it gets a decision to automatically inherit most of northern Italy. If Papal States or Two Sicilies owns all cores of each other plus Tuscany and the island of Sardinia, they can form Italy as well.
######Scandinavia:
*Any Scandinavian culture country can form Scandinavia without having to be a GP if they own Christiana, Stockholm, and Copenhagen
######Low Countries:
*Gave Luxembourg to Belgium at the start.
*Gave the Netherlands Boer as an accepted culture.
######Greece, Serbia, Romanian Minors:
*Every balkan minor country starts with a large population boom modifier that will have increased their population by 50*75% in the first few years of the game. Additionaly, while not country specific, the new revanchism mechanic and small nation triggered modifiers give extremely large bonuses to max soldier % and mobilization pools to these countries.
*Wallachia and Moldavia have a decision to form Romania that can be activated at any time when played by a human, and 1854 when played by AI.
*Serbia can form Yugoslavia if it owns all of its Serbian cores instead of having to own all of Yugoslavia.
*If Greece reclaims its cores in both Greece and Anatolia, it gets an event to increase its Greek population by 100% while reducing its Turkish population by 80%.
######Mexico:
*Establishing the 2nd Mexican Empire turns the country into a hms government, gives a few reforms, and gives all POPs 10 militancy and 10 consciousness. The decision is available once the ACW begins and cannot be taken once the ACW is over.
######South America:
*All South American starting POPs replaced with HPM starting POPs. In most cases this equates to anywhere from a 10% to a 100% increase in starting population.
*Argentina given a decision to become a democracy and pass several reforms all at once.
######Uncivilized Nations:
*Reform costs were reduced
*Muhammad Ali's reforms, Dar al Funun, and Meiji Restoration decisions all buffed.