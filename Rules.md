
# College Risk Rules

*As drafted by Mautamu ‘21 from CFBR2/AR3 rules; October 2021. Portions from “Rust Risk Guide” by Avocado ‘18 and TxAg70 ‘17*

This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed with this file, You can obtain one at https://mozilla.org/MPL/2.0/.

## Objective

To have as many territories as possible at the end of the regular season to make it to the playoffs season. The objective in the playoff season is to control all of the territories on your playoff map and therefore be the last team standing.

  

Side Quests:

-   Eliminate your rivals
    
-   Take over your state
    
-   Keep home territory all regular season
    

## Setup

1.  All 130 of the college football teams in the FBS are assigned their home territory as it would be on the map.
    
2.  A second map, with no teams, shall also be created. Eliminated teams shall be placed on the secondary map. Once a team has been eliminated from both maps, their players may join a new team active on either map.
    

  

## Gameplay

1.  **Turns.** Each team player shall be able to submit a single turn for each round. The player may attack any unowned territory immediately adjacent to a territory that the player's team owns. The player may also defend any attackable territory owned by the player’s team. For defending a territory, the player shall receive a 1.5x defense bonus.
    
2.  **Rolls.** At 22:00 U.S. Central Standard Time on every day but Sunday, a new round shall begin. This shall consist of the Rust Risk program deciding the owner of each territory according to the following plan:
    

	1.  If a territory is owned by a team, and that territory is not attacked by any other team, that territory shall remain owned by the defending team regardless of whether the defending team placed players on that territory.
	    
	2.  If a territory has both attacking and defending players, then the total amount of power (which is star power times bonuses) for each team will be calculated and mapped to a random number to determine the winner. See “Star Power Specifics by Map.”
    

3.  **MVPs.** Once a territory has been assigned to an owner, a player on that territory who played for the winning team shall be selected to serve as the MVP for that team and territory pair. That player shall have their MVP count incremented by one. In the case that no players were placed on a territory, no MVPs will be assigned (e.g. a territory and its surrounding territories all owned by the same team prior to the roll).
    
4.  **Triple or Nothing.** If a team controls only one territory, each player on that team may elect to triple-or-nothing their power if they are defending that territory. If that player is attacking or elects not to triple-or-nothing their power, then the multiplier will not be affected.
    
5.  **Region Multipliers.** A team who owns a whole region will get a 2x multiplier for each region. These multipliers shall be cumulative (2, 4, 6).
    
6.  **Elimination.** A team is eliminated when it no longer owns any territories. If a team is eliminated from the primary map, then that team shall spawn in a random location on the second map. Once a team is eliminated from the secondary map, that team's members may individually join a team on either map.
    
7.  **Star Power Specifics by Map.** On the primary map, star power shall not be limited by team or territory. On the secondary map, star power will be adjusted to 100 for each team. The team’s star power shall be distributed according to the proportion of star power assigned by that team’s players to each territory. For example, a team has ten players, with twenty star power to distribute, split across four different territories: A: 3, B: 12, C: 2, D: 3 star power. On the primary map, those would be the values assigned to each territory. On the secondary map, the distribution would instead be A: 15, B: 60, C: 10, D: 15 star power. In summary, on the first map, star power is a function of team size and experience, while on the second map, star power is set to 100 and distributed according to actual star power.
    
8.  **Ranking.** Rankings for the regular season shall be determined first by number of territories owned, then by number of days in the game.
    
9.  **Playoffs.** At the end of the regular season, teams will be grouped into fours by ranking on both the primary and secondary map and placed on identical smaller maps comprising 21 territories (one territory will not be occupied, all others will be split evenly). For example, the top two teams on the primary map will be paired with the top two teams on the secondary map. Each day, four territories will be removed from the playoff maps at random. These will be the same territories across all playoff maps. Each team will receive 100 star power to distribute according to the “secondary map” rules. The winner will be determined by the team with the last remaining territory on each map (the playoff ends when one team controls the entire map). The order of all other teams will be determined by the length of tenure on the playoff map, and then by number of territories on the day they were eliminated on the playoff map (backtracking until the tie is broken).
	1. All teams who are not eliminated on both primary and secondary maps shall be eligible for playoffs. The bottom teams without pairs shall be selected in groups of four until no longer feasible. If not divisible by four, the remainder teams shall be placed on a playoff map with extra unclaimed territories. 

10. **Eliminated Teams.** If a player made a move on a territory owned by a team that is eliminated that turn, that player shall be given an "Eliminated Teams" point. 
    
 
  

### Stars

A player’s stars shall again be determined by five different categories: eliminated teams, streak, total turns in all college football risk games, total turns in this season, total number of MVPs in all college football risk games. The user’s star number (for determining star power) shall be determined according to the median value of stars for each category, where the star values for each category are as follows:

-  Eliminated Teams
    
	A.  0 eliminated teams: 1 star
    
	B.  1 eliminated team: 2 stars
	    
	C.  2 eliminated teams: 3 stars
	    
	D.  3 eliminates teams: 4 stars
	    
	E.  4+ eliminated teams: 5 stars
    

-  Streak
    

	A.  0-2 turns: 1 star
	    
	B.  3-4 turns: 2 stars
	    
	C.  5-9 turns: 3 stars
	    
	D.  10-24 turns: 4 stars
	    
	E.  25+ turns: 5 stars
    

-  Total Turns
    

	A.  0 awards: 1 star
	    
	B.  1 award: 2 stars
	    
	C.  2 awards: 3 stars
	    
	D.  3 awards: 4 stars
	    
	E.  4 awards+: 4 stars
    

-  Season Turns
    
	
	A.  0-4 turns: 1 star
	    
	B.  5-9 turns: 2 stars
	    
	C.  10-24 turns: 3 stars
	    
	D.  25-39 turns: 4 stars
	    
	E.  40+ turns: 5 stars
    

-  Total MVPs
    

	A.  0 MVPs: 1 star
	    
	B.  1-4 MVPs: 2 stars
	    
	C.  5-9 MVPs: 3 stars
	    
	D.  10-24 MVPs: 4 stars
	    
	E.  25+ MVPs+: 5 stars
    

  

The total star power each player shall receive will be according to the star number (median for each of the above categories) and the assignments below:

-  1 star: 1 point
    
-  2 stars: 3 points
    
-  3 stars: 7 points
    
-  4 stars: 9 points
    
-  5 stars: 11 points
    

  

## Recruiting Guidelines

In order to win this game, you will need to have one of, if not the biggest player base in the game. That is why recruiting is essential. The easiest way to recruit is to ask your friends and classmates to play.

Do:

-   Get the word out to as many people as you can
    
-   Make joining a painless experience - it takes about two minutes to create a Reddit or Discord account!
    
-   Look at other subreddits, Discord servers, GroupMes, Facebook groups, and any other social media to find people
    
-   Text or drop a line to friends of yours.
    

Don’t:

-   Create alt accounts. That’s not recruiting, that’s cheating.
    
-   Break Reddit’s Terms of Service, or the TOS of any other website.
    
-   Spam or otherwise annoy people.
    
-   Shame anyone for not wanting to join.
    
-   Recruit people who like trolling others.
    
-   Offer bribes to people or otherwise act dishonestly.
    
-   Go recruit in person. Please cooperate with your city and state health officials in these uncertain times. Stay home and stay healthy.
