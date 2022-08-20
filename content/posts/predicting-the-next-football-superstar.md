---
title: "Predicting the Next Soccer Superstar"
date: 2020-11-18T18:37:18-08:00
draft: false
---

On July 27, 2011, a then 19-year-old Neymar nimbly dribbled past the Flamengo defense in the Campeonato Brasileiro and scored an extraordinary goal in the 25th minute of the game, bringing his hometown team, Santos, to a 3-0 lead. The unexpectedly brilliant goal won him the revered Puskas award that year and is widely regarded as Neymar’s arrival onto the international stage, poising him to be the next global superstar.

<!--more-->

{{< tweet 1287733149728899073 >}}

But as the world cheered on, the data team at EA Sport’s FIFA division was closely watching, trying its best to quantify Neymar’s impressive performance for his virtual counterpart in its hugely successful FIFA video game series. The game’s player scores and avatars, the results of its meticulous number-crunching, have transcended the in-game playing experience and into the real world of the soccer elite [^1] where players publicly discuss their scores with careful reflection, use the virtual pitch to evaluate real-life issues and opponents, and utilize game metrics for training and development.

As for Neymar, not only was it a surprise to see the mid-2011 FIFA scores reflect the stature of a player clearly still in development, but to also see his scores only gradually climb in the coming years despite the player’s exploding profile. Neymar’s steady ascent to a reliable pro in FIFA’s system was continuously reflected in his real world valuation, finally catching up to his massive global presence after reaching an all-time-high market value of $198 million in 2018. FIFA’s scoring system seemingly accomplished the difficult task of accurately capturing Neymar’s magic on the pitch in a numerical story that graphed closely with the real-world market value of the now enduring superstar.

{{< figure src="/images/cards.jpg" caption="FIFA 20 cards for Messi, Mbappé, and Mané" >}}


## The FIFA Scoring System

A natural question may follow: how does the data team generate such meaningful scores – an  already difficult task – for so many players? As described by Michael Mueller-Morning, the head of the data team at FIFA, the task becomes especially challenging when it comes to a myriad of new players from smaller leagues for whom there is little to no existing information. At scale, the process involves calculating scores for approximately 18,000 players across 700 clubs and 30 leagues [^2] . Since the data for the number of players doesn’t exist and therefore can’t be bought, FIFA relies on a network of 9,000 members – including professional-level scouts, agents, and season ticket holders – to closely watch and assess players in live and recorded matches. Their expertise is not only used to evaluate a player’s visible, physical performance traits, but also intangibles like their mental resilience, intelligence in positioning, and aggression. 

The 5.4 million data points provided by the network are collated and processed into scores that provide an astonishingly accurate reconstruction of the players in FIFA’s in-game experience. The richness of FIFA’s data suggests that it is ripe for promising insight – not only into the past and present of the game, but also its future.



## Superstars: The Story of Performance and Valuation

Arguably the biggest superstar of modern soccer, Lionel Messi has been at the pinnacle of the soccer world for almost the entirety of his 16-year career, topping every metric used to determine such things: market value, awards, wages, trophies, and even merchandising sales. But it all started when he stepped onto the pitch for Barcelona for the first time in the fall of 2004 and quickly proved to be a once-in-a-lifetime talent. As the world watched the phenom, other clubs realized that they had a problem - and potentially an opportunity - on their hands. Widespread recognition inevitably followed his astounding ability, the natural result of an unnatural talent.

As seen across sporting industries, superstardom sits precariously on top of both performance and valuation. Valuations themselves represent a measure of the player’s value in the marketplace, speaking directly to their utility on the pitch. But it often includes the effects of a player's star power, media presence, and international recognition. The variables, however, are catalyzed and sustained by performance and can be considered mediator variables between performance and valuation; ultimately pointing to performance as the main predictor of a player's valuation.

By tracking a player’s performance data, we may be able to construe a relationship between their performance and valuation that can help unearth the next set of high-value players in the game.

{{< figure src="/images/messi.jpg" caption="Lionel Messi at the 2020 Ballon D'or ceremony after winning his sixth Ballon D'or" >}}



## The Data

Using the last five years of historical performance data (from FIFA) for the top 500 players in 2019 by valuation (from [Transfermarkt](https://www.transfermarkt.us/)) we can see if there exists a relationship between the changes in high-value players’ performance scores and their valuations throughout the last five years. A pattern, that may, help us find the next generation of superstars.



## The Portraits of High-Value Players

The attributes that factor into assessing a player’s performance are dependent on the player’s position, as different positions require different skillsets. Attackers need to be quick and agile to create scoring opportunities, while defenders need to be strong and forceful in order to tackle (opposing) attackers trying to create those opportunities. 

Below are the non-performance attributes for high-value players across positions. ‘Subs’, a positional category comprising of bench players of all positions, has been omitted as positional profiles would vary across the group.


| | Attackers | Midfielders | Defenders | Goalkeepers
|-------|-------|-------|-----|------|
| Age (avg)| 25.3 yrs | 24.9 yrs |25.5 yrs  | 25.7 yrs |
| Height (avg) | 5’11.3” | 5’10.7”  | 6’0.6” | 6’2.6”|
| Weight  (avg) |  167.7 lb | 162.2 lb | 174.9 lb | 187.4 lb 
| Body Type (mode) | normal | normal, lean | normal | normal |
| Nationality (mode) | Spain | Spain, France | England | no mode
| Work Rate (mode) | high/medium | medium/medium| medium/high |n/a |
| Current League (mode) | EPL*** | EPL | EPL | EPL |


The average player profile for each position is as expected. High-value attackers are normally-built players whose profile allows them to be relentless and agile. Midfielders are the lightest of the bunch, which helps them occupy both offensive and defensive positions on the pitch in order to service both attackers and defenders. Defenders are bigger and weightier, lending well to tackling opponents and reclaiming position of the ball. And finally, goalkeepers are large and sturdy allowing them to cover as much of the goalpost as possible and helping them stay planted during offensive attacks.

What is interesting to note, however, is that the most common workrate [^3] among each positional category for these high-value players corresponds to their part of the pitch, indicating that positional focus is favorable to “all-roundedness”. Though players with high/high workrates can be thought of as versatile, among high-value players, staying in position and conserving energy for their respective roles is more common, lending credibility to the value of player specialization.

It is also worth noting that regardless of nationality, the most common home for high-value players is the English Premier League (EPL). Despite having the median number of players across the big five leagues, the EPL hosts the largest number of high-value players across all positions except goalkeepers (who are evenly distributed across the top leagues). This could be because the EPL has the largest market value of all the big five leagues – indicating that a player’s value is boosted by entering the EPL or, conversely, that the league attracts high-value players because of its prestige and market value. Another possibility is that the EPL is ”creating” high-value players by way of team resources and/or managerial leadership only found in the EPL, but that would require a finer look at transfer data along with performance data. It does seem, however, that finding a home in the Premier League bodes well for a player’s market value.

{{< figure src="/images/epl.jpg" caption="Liverpool players celebrating winning the 2020 EPL championship" >}}

And lastly, in regards to nationality, Spain and France’s presence at the top of the table across positions (including the omitted, but sizable ‘subs’ category) is conspicuous. Their positions as the top producers of soccer talent is an enigma that has been turned over by many soccer journalists across Europe for years, especially in light of France’s World Cup victory in 2018. Their prominence in this regard has since been theorized to be the result their respective national soccer federations’ dedicated efforts in detecting and nurturing promising young talent, making a compelling case study for well-organized investment in scouting and youth academies [^4] .



## Skills That Seem to Matter

A constellation of skills makes up an effective and valuable player, but there are certain skills that give players an advantage in their positions and elevate their overall performance.

It should be noted that they way skills are defined, categorized, and measured by a data aggregator shapes the way a player’s performance is viewed by providing the language and concepts by which to evaluate it. Using the idea of a metric like **‘positioning’** under a **‘mentality’** category is an attempt to quantify the fluid display that is a player’s performance - making FIFA, or any other soccer data aggregator, unique from each other.

 With that in consideration, below are the skills [^5] that have moderate to strong correlations to player valuation [^6] , indicating their importance in making a player’s performance pop.

{{< figure src="/images/graph1.jpg" >}}
{{< figure src="/images/graph2.jpg" >}}
{{< figure src="/images/graph4.jpg" >}}
	


A common skill that seems to matter among all positions is **movement reactions** – in other words – how well a player reacts to a situation as it occurs, suggesting that smart, quick decision-making is definitive in all positions. 

It's also worth noting that mentality scores for attackers have higher correlations to their valuations compared to other positions (with goalkeepers coming in second), implying mental makeup is critical for attackers and goalkeepers. **Ball control** is more strongly correlated to positions in the upper half of the field (attackers and midfielders), whereas positionally-specific attributes like **defending tackle** and **goalkeeping handling**, **positioning**, and **kicking** have stronger correlations for players in the lower half. Goalkeepers, who have a tight skillset, understandably have three out of their five goalkeeping skills correlating strongly with their valuations. 

These standout skills may warrant further exploration in regards to player training and development, having the potential to be consdiered strong delineators in the game.


## The Predictions

Given the historical FIFA and Transfermarkt data, a model can be created to predict future high-value players by tracking the current top 500 high-value players’ trajectories through the past five years. With a mixed-effects regression approach, we can get an idea of where young players not currently in the top 500 might end up in the future given their current FIFA scores. Since many players 23-years or younger (“U23s”) are considered the oldest group of developing talent, placing the age cut-off at 23 gives a greater chance of detecting high-value players that have yet gone unnoticed.

Another factor in the model is the inclusion of the aforementioned ‘subs’ position. Though ‘subs’ span all positions and can often change over a season, we can build a model on the umbrella position and see if there are players who fit the arc of high-value subs in 2020. 

So who are the players that may surprise us in the coming years? Below are the 10 players with the top predicted values for each position for 2020 (except for goalkeepers who, with a smaller population size, have a top 5).


{{< figure src="/images/tables.jpg" >}}



## *2020: A Quick Recon

As 2020 comes to a close we can take a look back at the predictions and see if there were any players whose valuations grew. Many of the players predicted have more or less maintained their valuations, with a number facing downward turns. Those whose valuations have gone up have been highlighted in the 'predicted values' tables above.

Several players, particularly attackers, midfielders, and subs, witnessed a growth in their value over the last year. **Jarrod Bowen** (midfielder) and **Angeliño** (sub – defender) had the biggest jumps in valuation with $8 million and $9 million respectively. The players with the overall biggest jumps in their valuations were midfielders and subs.

The model may be more tuned for up-field players rather than the backline given the fewer instances, and smaller magnitude, of valuation growth in defenders and goalkeepers in the small group of top predicted players discussed here. However, looking back at the players whose valuations and profiles have grown, we may have a talented graduating class with the likes of **Jarrod Bowen**, **Angeliño**, **Douglas Luiz**, **Ismaël Bennacer\*\***, **Daichi Kamada**, **Konrad Laimer**, **Diego Rossi**, and **Boubacar Kamara\*\***. 

It is yet to be seen if there will be another Neymar, Messi, or Ronaldo, but with the entire world watching, there is a good chance that a new, unexpected talent will burst onto the scene in the near future, giving soccer fans a new generation of superstars to follow.

{{< figure src="/images/ismael.jpg" caption="Ismaël Bennacer for AC Milan" >}}


## Footnotes:

[^1]: Smith, R. (2016, October 13). How Video Games Are Changing the Way Soccer Is Played. Retrieved December 3, 2019, from https://www.nytimes.com/2016/10/14/sports/soccer/the-scouting-tools-of-the-pros-a-controller-and-a-video.html?_r=0

[^2]: Lindberg, A. (2016, September 26). FIFA 17's player ratings system blends advanced stats and subjective scouting. Retrieved December 13, 2019, from https://www.espn.com/soccer/blog/espn-fc-united/68/post/2959703/fifa-17-player-ratings-system-blends-advanced-stats-and-subjective-scouting

[^3]: Workrate: a measure consisting of a numerator and denominator corresponding to a player's time spent in offensive and defensive roles, respectively (i.e. high/high, high/medium, etc.)

[^4]: Williams, T. (2019, July 09). How France became football's ultimate talent hotbed. Retrieved December 03, 2019, from https://www.espn.com/soccer/french-ligue-1/story/3897341/how-france-became-footballs-ultimate-talent-hotbed

[^5]: Lopes, R. (2018, September 01). FIFA 19 Attributes Guide - All Players Attributes Explained. Retrieved December 3, 2019, from https://www.fifauteam.com/fifa-19-attributes-guide/

[^6]: Statistically significant correlations of moderate (0.5<ρ<0.7) to high (ρ>=0.7) strength with a p-value<0.05

\* More commonly known as Angeliño 

\*\* Ismaël Bennacer and Boubacar Kamara are in the top 15 predicted values from the model, lying outside the top 10 examined in the tables

\*\*\* English Premier League (EPL)

