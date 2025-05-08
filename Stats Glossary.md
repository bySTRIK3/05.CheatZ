**Baseball Savant**
Exit Velocity (EV)
How fast, in miles per hour, a ball was hit by a batter.
Launch Angle (LA)
How high/low, in degrees, a ball was hit by a batter.
Barrels
A batted ball with the perfect combination of exit velocity and launch angle
Hard Hit
Statcast defines a 'hard-hit ball' as one hit with an exit velocity of 95 mph or higher.
Launch Angle Sweet-Spot
A batted-ball event with a launch angle between eight and 32 degrees.
Batted Ball Event (BBE)
A Batted Ball Event represents any batted ball that produces a result.
Pitch Velocity
How hard, in miles per hour, a pitch is thrown.
Pitch Movement
The movement of a pitch is defined in inches, both in raw numbers and as a measurement against average.
Active Spin
Statcast refers to the spin that contributes to movement as Active Spin.
Spin Rate
How much spin, in revolutions per minute, a pitch was thrown with.
Extension
How far off the mound, in feet, a pitcher releases the pitch.
Pop Time
How quickly, in seconds, a catcher can get the ball out of his glove and to the base on a stolen base or pickoff attempt.
Arm Strength
How hard, in miles per hour, a fielder throws the ball.
Lead Distance
How far, in feet, a runner is ranging off the bag at the time of a pitcher's first movement or pitch release.
Jump
Jump is a Statcast metric that shows which players have the fastest reactions and most direct routes in the outfield.
Outs Above Average (OAA)
A range-based metric of skill that shows how many outs a player has saved over his peers.
Fielding Run Value
Statcast's overall metric for capturing a player’s measurable defensive performance onto a run-based scale, converting various metrics like OAA, blocking, framing, etc.
Catch Probability
The likelihood, in percent, that an outfielder will be able to make a catch on an individual batted ball.
Expected Batting Average (xBA)
xBA measures the likelihood that a batted ball will become a hit.
Expected Weighted On-base Average (xwOBA)
xwOBA is formulated using exit velocity, launch angle and, on certain types of batted balls, Sprint Speed.
Expected Earned Run Avg (xERA)
xERA is a simple 1:1 translation of xwOBA, converted to the ERA scale.
Sprint Speed
A measurement of a player's top running speed, expressed in "feet per second in a player's fastest one-second window."
Bolt
A Bolt is any run where the Sprint Speed (defined as "feet per second in a player's fastest one-second window") of the runner is at least 30 ft/sec.
EV50
For a batter, EV50 is an average of the hardest 50% of his batted balls. For a pitcher it is the average of his softest 50% of batted balls allowed.
Adjusted EV
Adjusted EV averages the maximum of 88 and the actual exit velocity of each batted ball event.
Blocks Above Average
A Statcast metric designed to express the demonstrated skill of catchers at preventing wild pitches or passed balls compared to their peers.
Bat Speed
Bat speed is measured at the sweet-spot of the bat. Average bat speed is the average of the top 90% of a player’s swings.
Fast Swing Rate
A fast swing is one that has 75 MPH or more of bat speed.
Swing Length
The total (sum) distance in feet traveled of the head of the bat in X/Y/Z space, from start of tracking data until impact point.
Squared-Up Rate
How much exit velocity was obtained compared to the maximum possible exit velocity available, given the speed of the swing and pitch.
Blasts
A more valuable subset of squared-up balls, defining batted balls that were both squared-up and with a fast swing.
Swords
A bat tracking metric that quantifies when a pitcher forces a batter to take a non-competitive, ugly-looking swing.

### Hitting

G (Games Played): Number of games in which the player has appeared.

PA (Plate Appearances): Number of times the player has come to the plate.

HR (Home Runs): Number of home runs.

R (Runs Scored): Number of runs scored.

RBI (Runs Batted In): Number of times a run scores as a result of a batter’s plate appearance, not counting situations in which an error caused the run to score or the batter hit into a double play.

SB (Stolen Bases): Number of stolen bases.

BB% (Walk Percentage): Frequency with which the batter has walked, calculated as walks divided by plate appearances.

K% (Strikeout Percentage): Frequency with which the batter has struck out, calculated as strikeouts divided by plate appearances.

ISO (Isolated Power): Average number of extra bases per at bat, calculated several ways such as SLG minus AVG.

BABIP (Batting Average on Balls in Play): The rate at which the batter gets a hit when he puts the ball in play, calculated as (H-HR)/(AB-K-HR+SF).

AVG (Batting Average): Rate of hits per at bat, calculated as H/AB.

OBP (On Base Percentage): Rate at which the batter reaches base, calculated as (H+BB+HBP)/(AB+BB+HBP+SF).

SLG (Slugging Percentage): Average number of total bases per at bat, calculated as Total Bases/AB.

wOBA (Weighted On Base Average): Combines all the different aspects of hitting into one metric, weighting each of them in proportion to their actual run value. While batting average, on-base percentage, and slugging percentage fall short in accuracy and scope, wOBA measures and captures offensive value more accurately and comprehensively.

wRC+ (Weighted Runs Created Plus): The most comprehensive rate statistic used to measure hitting performance because it takes into account the varying weights of each offensive action (like wOBA) and then adjusts them for the park and league context in which they took place.

BsR (Base Running Runs Above Average): Number of runs above or below average a player has been worth on the bases, based on stolen bases, caught stealing, extra bases taken, outs on the bases, and avoiding double plays. It is the combination of wSB, UBR, and wGDP.

Off (Offensive Runs Above Average): Number of runs above or below average a player has been worth offensively, combining Batting Runs and BsR.

Def (Defensive Runs Above Average): Number of runs above or below average a player has been worth on defense, combining Fielding Runs (Total Zone before 2002, UZR after) and the positional adjustment.

WAR (Wins Above Replacement): A comprehensive statistic that estimates the number of wins a player has been worth to his team compared to a freely available player such as a minor league free agent. You can learn exactly how we calculated it here.

Standard:
G (Games Played): Number of games in which the player has appeared.

AB (At Bats): Number of trips to the plate in which the batter does not walk, get hit by a pitch, sacrifice (fly or bunt), or reach on interference.

PA (Plate Appearances): Number of times the player has come to the plate.

H (Hits): Number of hits.

1B (Singles): Number of singles.

2B (Doubles): Number of doubles.

3B (Triples): Number of triples.

HR (Home Runs): Number of home runs.

R (Runs Scored): Number of runs scored.

RBI (Runs Batted In): Number of times a run scores as a result of a batter’s plate appearance, not counting situations in which an error caused the run to score or the batter hit into a double play.

BB (Walks): Total number of walks (includes IBB).

IBB (Intentional Walks): Number of times the batter was intentionally walked.

SO (Strikeouts): Number of strikeouts.

HBP (Hit By Pitches): Number of times the batter reached after being hit by a pitch.

SF (Sacrifice Flies): Number of times a batter’s fly out allowed a runner to tag up and score.

SH (Sacrifice Bunts): Any bunt in which there was a runner on base and less than two outs in which the batter was put out and at least one runner advanced.

GDP (Grounded into Double Play): Number of times the batter hit into a double play.

SB (Stolen Bases): Number of stolen bases.

CS (Caught Stealing): Number of times caught stealing.

AVG (Batting Average): Rate of hits per at bat, calculated as H/AB.

Advanced:
PA (Plate Appearances): Number of times the player has come to the plate.

BB% (Walk Percentage): Frequency with which the batter has walked, calculated as walks divided by plate appearances.

K% (Strikeout Percentage): Frequency with which the batter has struck out, calculated as strikeouts divided by plate appearances.

BB/K (Walk to Strikeout Rate): Ratio of walks to strikeouts, calculated as Walks/Strikeouts.

AVG (Batting Average): Rate of hits per at bat, calculated as H/AB.

OBP (On Base Percentage): Rate at which the batter reaches base, calculated as (H+BB+HBP)/(AB+BB+HBP+SF).

SLG (Slugging Percentage): Average number of total bases per at bat, calculated as Total Bases/AB.

OPS (On Base Plus Slugging): Combination of OBP and SLG, calculated as OBP+SLG.

ISO (Isolated Power): Average number of extra bases per at bat, calculated several ways such as SLG minus AVG.

Spd (Speed Score): A slightly outdated statistic that attempts to measure a player’s running ability.

BABIP (Batting Average on Balls in Play): The rate at which the batter gets a hit when he puts the ball in play, calculated as (H-HR)/(AB-K-HR+SF).

UBR (Ultimate Base Running): The number of runs above or below average added by a player on all non-SB/CS base running players.

wGDP (Weighted Grounded Into Double Play Runs): The number of runs above or below average added by a player by staying out of double plays.

wSB (Weighted Stolen Base Runs Above Average): Number of runs above or below average added by a player on stolen base attempts.

wRC (Weighted Runs Created): Number of runs a player has generated for his team as a result of his wOBA and playing time.

wRAA (Weighted Runs Above Average): Number of runs above or below average a player has added as a hitter.

wOBA (Weighted On Base Average): Combines all the different aspects of hitting into one metric, weighting each of them in proportion to their actual run value. While batting average, on-base percentage, and slugging percentage fall short in accuracy and scope, wOBA measures and captures offensive value more accurately and comprehensively.

wRC+ (Weighted Runs Created Plus): The most comprehensive rate statistic used to measure hitting performance because it takes into account the varying weights of each offensive action (like wOBA) and then adjusts them for the park and league context in which they took place.

Batted Ball
BABIP (Batting Average on Balls in Play): The rate at which the batter gets a hit when he puts the ball in play, calculated as (H-HR)/(AB-K-HR+SF).

GB/FB (Ground Ball to Fly Ball Ratio): The ratio of ground balls a batter hits to fly balls, calculated as GB/FB.

LD% (Line Drive Percentage): The percentage of a batter’s balls in play that are line drives, calculated as LD/BIP.

GB% (Ground Ball Percentage): The percentage of a batter’s balls in play that are ground balls, calculated as GB/BIP.

FB% (Fly Ball Percentage): The percentage of a batter’s balls in play that are fly balls, calculated as FB/BIP.

IFFB% (Infield Fly Ball Percentage): Percentage of a batter’s fly balls that were infield fly balls, calculated as IFFB/FB.

HR/FB (Home Run to Fly Ball Rate): Percentage of a batter’s fly balls that go for home runs, calculated as HB/FB (even though some HR are line drives).

IFH (Infield Hits): Number of infield hits.

IFH% (Infield Hit Percentage): Percentage of ground balls that are infield hits, calculated as IFH/GB.

BUH (Bunt Hits): Number of bunt hits.

BUH% (Bunt Hit Percentage): Percentage of bunts that go for hits, calculated as Bunt Hits/Bunts.

Pull% (Pull Percentage): Percentage of batted balls hit to the pull field.

Cent% (Center Percentage): Percentage of batted balls hit to the middle of the field.

Oppo% (Opposite Field Percentage): Percentage of batted balls hit to the opposite field.

Soft% (Soft Contact Percentage): Percentage of soft-hit batted balls.

Med% (Medium Contact Percentage): Percentage of medium-hit batted balls.

Hard% (Hard Contact Percentage): Percentage of hard-hit batted balls.

Win Probability
WPA (Win Probability Added): The total impact a batter’s plate appearances (or SB/CS) have on his team’s win expectancy relative to league average.

-WPA (Negative Win Probability Added): The sum of a batter’s negative WPA events.

+WPA (Positive Win Probability Added): The sum of a batters positive WPA events.

RE24 (Run Expectancy 24 Base Out State): The total impact a batter’s plate appearances (or SB/CS) have on his team’s run expectancy relative to league average.

REW (Run Expectancy Wins): RE24 converted from runs to wins.

pLI (Average Leverage Index): The average leverage index of each batter’s plate appearances.

phLI (Average Leverage Index while Pinch Hitting): The average leverage index of each batter’s plate appearances while pinch hitting.

PH (Pinch Hits): Number of hits while serving as a pinch hitter.

WPA/LI (Situational Wins): A player’s WPA controlling for leverage index, calculated as the sum of each event’s WPA/LI, not total WPA/LI.

Clutch (Clutch Score): The difference between a player’s totalWPA/pLI and their WPA/LI defined above.

Pitch Type
This section refers to data from Baseball Info Solutions. Raw PITCHf/x data is found in the PITCHf/x section. The % numbers refer to percentage and the “v” numbers refer to average velocity.

FB% (Fastball Percentage)

FBv (Average Fastball Velocity)

SL% (Slider Percentage)

SLv (Average Slider Velocity)

CT% (Cutter Percentage)

CTv (Average Cutter Velocity)

CB% (Curveball Percentage)

CBv (Average Curveball Velocity)

CH% (Changeup Percentage)

CHv (Average Changeup Velocity)

SF% (Split-Finger Percentage)

SFv (Average Split-Finger Velocity)

KN% (Knuckleball Percentage)

KNv (Average Knuckleball Velocity)

XX% (Unidentified Pitch Percentage)

Pitch Value
This section refers to pitch data from Baseball Info Solutions and denotes the number of runs above average a batter was against a specific pitch type (or that type per 100 pitches). Learn more about them here.

wFB (Weighted Fastball Runs)

wSL (Weighted Slider Runs)

wCT (Weighted Cutter Runs)

wCH (Weighted Changeup Runs)

wSF (Weighted Split Finger Runs)

wKN (Weighted Knuckleball Runs)

wFB/C (Weighted Fastball Runs per 100 pitches)

wSL/C (Weighted Slider Runs per 100 pitches)

wCT/C (Weighted Cutter Runs per 100 pitches)

wCH/C (Weighted Changeup Runs per 100 pitches)

wSF/C (Weighted Split Finger per 100 pitches)

wKN/C (Weighted Knuckleball Runs per 100 pitches)

Plate Discipline
These statistics are based on data from Baseball Info Solutions. Learn more about them here.

O-Swing% (Outside the Zone Swing Percentage): Swings at pitches outside the zone divided by pitches outside the zone.

Z-Swing% (Inside the Zone Swing Percentage): Swings at pitches inside the zone divided by pitches inside the zone.

Swing% (Swing Percentage): Swings divided by total pitches.

O-Contact% (Outside the Zone Contact Percentage): Contact made outside the zone divided by swings outside the zone.

Z-Contact% (Inside the Zone Contact Percentage): Contact made inside the zone divided by swings inside the zone.

Contact% (Contact Percentage): Contact made divided by swings.

Zone% (Zone Percentage): Pitches inside the zone divided by total pitches.

F-Strike% (First Pitch Strike Percentage): Percentage of PA that begin with a strike.

SwStr% (Swinging Strike Percentage): Swinging strikes divided by total pitches.

Value
To learn more about each of these statistics, visit our page on position player WAR.

Batting (Batting Runs Above Average): Number of runs above or below average added as a hitter.

Base Running (Base Running Runs Above Average): Number of runs above or below average added as a base runner.

Fielding (Fielding Runs Above Average): Number of runs above or below average added as a fielder.

Positional (Positional Runs Above Average): The number of runs above or below average allocated based on the number of innings at player at specific positions.

Offense (Offensive Runs Above Average): Number of runs above or below average added on offense (Batting + Base Running)

Defense (Defensive Runs Above Average): Number of runs above or below average added on defense (Fielding + Positional)

League (League Adjustment): An adjustment made per PA to make sure each league has exactly 0 runs above average.

Replacement (Replacement Runs): Number of runs an average player is worth compared to a freely available player, given their PA.

RAR (Runs Above Replacement): Sum of Off+Def+League+Replacement.

WAR (Wins Above Replacement): A comprehensive statistic that estimates the number of wins a player has been worth to his team compared to a freely available player such as a minor league free agent. You can learn exactly how we calculated it here.

Dollars (Dollar Value of Performance): The amount of money a player’s production would be worth on the free agent market in millions of dollars. This column uses $5.5MM/WAR, but that is a calculation from several years ago. The current number is between $6 million and $7 million.

PITCHf/x Pitch Type
The following represent pitch type percentages according to PITCHf/x data. The name of the pitch is next to each. 

FA% (Four Seam and Unclassified Fastballs)

FT% (Two Seam Fastballs)

FC% (Cutters)

FS% (Split Fingers)

FO% (Forkballs)

SI% (Sinkers)

SL% (Sliders)

CU% (Cuvreballs)

KC% (Knuckle-Curves)

EP% (Ephesuses)

CH% (Changeups)

SC% (Screwballs)

KN% (Knuckleballs)

UN% (Unknowns)

PITCHf/x Velocity
The following are the average velocities according to PITCHf/x data. The name of the pitch is next to each.

vFA (Four Seam and Unclassified Fastballs)

vFT (Two Seam Fastballs)

vFC (Cutters)

vFS (Split Fingers)

vFO (Forkballs)

vSI (Sinkers)

vSL (Sliders)

vCU (Cuvreballs)

vKC (Knuckle-Curves)

vEP (Ephesuses)

vCH (Changeups)

vSC (Screwballs)

vKN (Knuckleballs)

vUN (Unknowns)

PITCHf/x H-Movement
The following are the average horizontal movements of the pitches according to PITCHf/x. The name of the pitch is next to each. (Negative values move toward RHH, positive values move toward LHH)

FA-X (Four Seam and Unclassified Fastballs)

FT-X (Two Seam Fastballs)

FC-X (Cutters)

FS-X (Split Fingers)

FO-X (Forkballs)

SI-X (Sinkers)

SL-X (Sliders)

CU-X (Cuvreballs)

KC-X (Knuckle-Curves)

EP-X (Ephesuses)

CH-X (Changeups)

SC-X (Screwballs)

KN-X (Knuckleballs)

UN-X (Unknowns)

PITCHf/x V-Movement
The following are the average vertical movements of the pitches according to PITCHf/x. The name of the pitch is next to each. (Numbers are relative to a pitch with no spin, meaning gravity’s effect is removed)

FA-Z (Four Seam and Unclassified Fastballs)

FT-Z (Two Seam Fastballs)

FC-Z (Cutters)

FS-Z (Split Fingers)

FO-Z (Forkballs)

SI-Z (Sinkers)

SL-Z (Sliders)

CU-Z (Cuvreballs)

KC-Z (Knuckle-Curves)

EP-Z (Ephesuses)

CH-Z (Changeups)

SC-Z (Screwballs)

KN-Z (Knuckleballs)

UN-Z (Unknowns)

PITCHf/x Pitch Type Value
The following are runs above average against each pitch using PITCHf/x data. The name of the pitch is next to each. Learn about pitch values here.

wFA (Four Seam and Unclassified Fastballs)

wFT (Two Seam Fastballs)

wFC (Cutters)

wFS (Split Fingers)

wFO (Forkballs)

wSI (Sinkers)

wSL (Sliders)

wCU (Cuvreballs)

wKC (Knuckle-Curves)

wEP (Ephesuses)

wCH (Changeups)

wSC (Screwballs)

wKN (Knuckleballs)

wUN (Unknowns)

PITCHf/x Pitch Value/100
The following are runs above average against each pitch per 100 pitches using PITCHf/x data. The name of the pitch is next to each. Learn about pitch values here.

wFA/C (Four Seam and Unclassified Fastballs)

wFT/C (Two Seam Fastballs)

wFC/C (Cutters)

wFS/C (Split Fingers)

wFO/C (Forkballs)

wSI/C (Sinkers)

wSL/C (Sliders)

wCU/C (Cuvreballs)

wKC/C (Knuckle-Curves)

wEP/C (Ephesuses)

wCH/C (Changeups)

wSC/C (Screwballs)

wKN/C (Knuckleballs)

wUN/C (Unknowns)

PITCHf/x Plate Discipline
The following are plate discipline numbers using PITCHf/x data. Learn about plate discipline numbers here.

PA (Plate Appearances): Number of times the player has come to the plate.

O-Swing% (Outside the Zone Swing Percentage): Swings at pitches outside the zone divided by pitches outside the zone.

Z-Swing% (Inside the Zone Swing Percentage): Swings at pitches inside the zone divided by pitches inside the zone.

Swing% (Swing Percentage): Swings divided by total pitches.

O-Contact% (Outside the Zone Contact Percentage): Contact made outside the zone divided by swings outside the zone.

Z-Contact% (Inside the Zone Contact Percentage): Contact made inside the zone divided by swings inside the zone.

Contact% (Contact Percentage): Contact made divided by swings.

Zone% (Zone Percentage): Pitches inside the zone divided by total pitches.

Pace (Average Time Between Pitches): Average time between pitches seen by a batter, based on PITCHf/x timestamps.

## Pitching

Dashboard
W (Wins): Number of wins.

L (Losses): Number of losses.

SV (Saves): Number of saves.

G (Games): Number of games in which the pitcher appeared.

GS (Games Started): Number of games the pitcher started.

IP (Innings Pitched): Number of total innings pitched (.1 represents 1/3 of an inning, .2 represents 2/3 of an inning).

K/9 (Strikeouts per 9 innings): Average number of strikeouts per 9 innings.

BB/9 (Walks per 9 innings): Average number of walks per 9 innings.

HR/9 (Home Runs per 9 innings): Average number of home runs allowed per 9 innings.

BABIP (Batting Average on Balls in Play): The rate at which the pitcher allows a hit when the ball is put in play, calculated as (H-HR)/(AB-K-HR+SF).

LOB% (Left On-Base Percentage): Percentage of pitcher’s own base runners that they strand over the course of a season. Not equal to the LOB column in the box score.

GB% (Ground Ball Percentage): The percentage of a pitcher’s balls in play that are ground balls, calculated as GB/BIP.

HR/FB (Home Run to Fly Ball Rate): Percentage of a pitcher’s fly balls that go for home runs, calculated as HB/FB (even though some HR are line drives).

ERA (Earned Run Average): The average number of earned runs a pitcher allows per 9 innings. ((ER*9)/IP)

FIP (Fielding Independent Pitching): An estimate of a pitcher’s ERA based on strikeouts, walks/HBP, and home runs allowed, assuming league average results on balls in play.

xFIP (Expected Fielding Independent Pitching): An estimate of a pitcher’s ERA based on strikeouts, walks/HBP, and fly balls allowed, assuming league average results on balls in play and home run to fly ball ratio.

WAR (Wins Above Replacement): A comprehensive statistic that estimates the number of wins a player has been worth to his team compared to a freely available player such as a minor league free agent based on FIP.

Standard:
W (Wins): Number of wins.

L (Losses): Number of losses.

ERA (Earned Run Average): The average number of earned runs a pitcher allows per 9 innings. ((ER*9)/IP)

G (Games): Number of games in which the pitcher appeared.

GS (Games Started): Number of games the pitcher started.

CG (Complete Games): Number of starts in which the pitcher recorded every out of an official game.

ShO (Shutouts): Number of complete games in which the pitcher allowed no runs.

SV (Saves): Number of saves.

HLD (Holds): Number of holds.

BS (Blown Saves): Number of times the pitcher entered in a save situation as lost the lead.

IP (Innings Pitched): Number of total innings pitched (.1 represents 1/3 of an inning, .2 represents 2/3 of an inning).

TBF (Total Batters Faced): The number of batters a pitcher has faced, akin to plate appearances.

H (Hits Allowed): Number of hits allowed by the pitcher.

R (Runs Allowed): Number of runs allowed by the pitcher.

ER (Earned Runs Allowed): Number of earned runs allowed by the pitcher, determined by the official scorer.

BB (Walks): Number of walks allowed by the pitcher.

IBB (Intentional Walks): Number of intentional walks issue by the pitcher.

HBP (Hit By Pitches): Number of hit batters.

WP (Wild Pitches): Number of wild pitches.

BK (Balks): Number of balks.

SO (Strikeouts): Number of strikeouts.

Advanced:
K/9 (Strikeouts per 9 innings): Average number of strikeouts per 9 innings.

BB/9 (Walks per 9 innings): Average number of walks per 9 innings.

K/BB (Strikeout to Walk Ratio): Strikeouts divided by walks.

HR/9 (Home Runs per 9 innings): Average number of home runs allowed per 9 innings.

K% (Strikeout Percentage): Frequency with which the pitcher has struck out a batter, calculated as strikeouts divided by total batters faced.

BB% (Walk Percentage): Frequency with which the pitcher has issued a walk, calculated as walks divided by total batters faced.

K%-BB% (Strikeout Percentage minus Walk Percentage): The percentage differential between K% and BB%, often a better indicator of performance than K/BB, which can be skewed by very low walk rates.

AVG (Batting Average Against): Rate of hits allowed per at bat, calculated as H/AB.

WHIP (Walks Plus Hits per Inning Pitched): The average number of base runners allowed via hit or walk per inning.

BABIP (Batting Average on Balls in Play): The rate at which the pitcher allows a hit when the ball is put in play, calculated as (H-HR)/(AB-K-HR+SF).

LOB% (Left On-Base Percentage): Percentage of pitcher’s own base runners that they strand over the course of a season. Not equal to the LOB column in the box score.

ERA- (Earned Run Average minus): ERA adjusted for park effects and league average (set to 100 for each year).

FIP- (Fielding Independent Pitching minus): FIP adjusted for park effects and league average (set to 100 for each year).

xFIP (Expected Fielding Independent Pitching minus): xFIP adjusted for park effects and league average (set to 100 for each year).

ERA (Earned Run Average): The average number of earned runs a pitcher allows per 9 innings. ((ER*9)/IP)

FIP (Fielding Independent Pitching): An estimate of a pitcher’s ERA based on strikeouts, walks/HBP, and home runs allowed, assuming league average results on balls in play.

E-F (ERA-FIP Differential): The difference between the pitcher’s ERA and FIP.

xFIP (Expected Fielding Independent Pitching): An estimate of a pitcher’s ERA based on strikeouts, walks/HBP, and fly balls allowed, assuming league average results on balls in play and home run to fly ball ratio.

SIERA (Skill Interactive ERA): An ERA estimator that attempts to more accurately capture a pitcher’s performance based on strikeouts, walks/HBP, home runs, and batted ball data.

Batted Ball
BABIP (Batting Average on Balls in Play): The rate at which the pitcher allows a hit when the ball in put play, calculated as (H-HR)/(AB-K-HR+SF).

GB/FB (Ground Ball to Fly Ball Ratio): The ratio of ground balls a pitcher allows to fly balls, calculated as GB/FB.

LD% (Line Drive Percentage): The percentage of a pitchers’s balls in play that are line drives, calculated as LD/BIP.

GB% (Ground Ball Percentage): The percentage of a pitchers’s balls in play that are ground balls, calculated as GB/BIP.

FB% (Fly Ball Percentage): The percentage of a pitcherss balls in play that are fly balls, calculated as FB/BIP.

IFFB% (Infield Fly Ball Percentage): Percentage of a pitchers’s fly balls that were infield fly balls, calculated as IFFB/FB.

HR/FB (Home Run to Fly Ball Rate): Percentage of a pitcher’s fly balls that go for home runs, calculated as HB/FB (even though some HR are line drives).

RS (Run Support): Number of runs the pitcher’s team has scored during their appearances.

RS/9 (Run Support per 9 innings): Number of runs the pitcher’s team has scored during their appearances per 9 innings.

Balls (Balls): Number of total balls thrown.

Strikes (Strikes): Number of total strikes thrown.

Pitches (Pitches): Number of total pitches thrown.

Pull% (Pull Percentage): Percentage of batted balls hit to the pull field.

Cent% (Center Percentage): Percentage of batted balls hit to the middle of the field.

Oppo% (Opposite Field Percentage): Percentage of batted balls hit to the opposite field.

Soft% (Soft Contact Percentage): Percentage of soft-hit batted balls.

Med% (Medium Contact Percentage): Percentage of medium-hit batted balls.

Hard% (Hard Contact Percentage): Percentage of hard-hit batted balls.

 

Win Probability
WPA (Win Probability Added): The total impact a pitcher’s batters faced (or SB/CS) have on his team’s win expectancy relative to league average.

-WPA (Negative Win Probability Added): The sum of a pitcher’s negative WPA events.

+WPA (Positive Win Probability Added): The sum of a pitcher’s positive WPA events.

RE24 (Run Expectancy 24 Base Out State): The total impact a pitcher’s batters faced (or SB/CS) have on his team’s run expectancy relative to league average.

REW (Run Expectancy Wins): RE24 converted from runs to wins.

pLI (Average Leverage Index): The average leverage index of each pitcher’s batters faced.

inLI (Inning Leverage Index): The average leverage index at the beginning of the inning for the pitcher.

gmLI (Game Leverage Index): The average leverage index at the beginning of the game for the pitcher.

exLI (Exit Leverage Index): The average leverage index at the end of the appearance for the pitcher.

Pulls (Pulls): Number of times the pitcher has been removed from a game.

WPA/LI (Situational Wins): A player’s WPA controlling for leverage index, calculated as the sum of each event’s WPA/LI, not total WPA/LI.

Clutch (Clutch Score): The difference between a player’s totalWPA/pLI and their WPA/LI defined above.

SD (Shutdowns): Number of relief appearances worth 0.06 WPA or more.

MD (Meltdowns): Number of relief appearances worth -0.06 or less.

Pitch Type
This section refers to data from Baseball Info Solutions. Raw PITCHf/x data is found in the PITCHf/x section. The % numbers refer to percentage and the “v” numbers refer to average velocity.

FB% (Fastball Percentage)

FBv (Average Fastball Velocity)

SL% (Slider Percentage)

SLv (Average Slider Velocity)

CT% (Cutter Percentage)

CTv (Average Cutter Velocity)

CB% (Curveball Percentage)

CBv (Average Curveball Velocity)

CH% (Changeup Percentage)

CHv (Average Changeup Velocity)

SF% (Split-Finger Percentage)

SFv (Average Split-Finger Velocity)

KN% (Knuckleball Percentage)

KNv (Average Knuckleball Velocity)

XX% (Unidentified Pitch Percentage)

Pitch Value
This section refers to pitch data from Baseball Info Solutions and denotes the number of runs above average a batter was against a specific pitch type (or that type per 100 pitches). Learn more about them here.

wFB (Weighted Fastball Runs)

wSL (Weighted Slider Runs)

wCT (Weighted Cutter Runs)

wCH (Weighted Changeup Runs)

wSF (Weighted Split Finger Runs)

wKN (Weighted Knuckleball Runs)

wFB/C (Weighted Fastball Runs per 100 pitches)

wSL/C (Weighted Slider Runs per 100 pitches)

wCT/C (Weighted Cutter Runs per 100 pitches)

wCH/C (Weighted Changeup Runs per 100 pitches)

wSF/C (Weighted Split Finger per 100 pitches)

wKN/C (Weighted Knuckleball Runs per 100 pitches)

Plate Discipline
These statistics are based on data from Baseball Info Solutions. Learn more about them here.

O-Swing% (Outside the Zone Swing Percentage): Swings at pitches outside the zone divided by pitches outside the zone.

Z-Swing% (Inside the Zone Swing Percentage): Swings at pitches inside the zone divided by pitches inside the zone.

Swing% (Swing Percentage): Swings divided by total pitches.

O-Contact% (Outside the Zone Contact Percentage): Contact made outside the zone divided by swings outside the zone.

Z-Contact% (Inside the Zone Contact Percentage): Contact made inside the zone divided by swings inside the zone.

Contact% (Contact Percentage): Contact made divided by swings.

Zone% (Zone Percentage): Pitches inside the zone divided by total pitches.

F-Strike% (First Pitch Strike Percentage): Percentage of PA that begin with a strike.

SwStr% (Swinging Strike Percentage): Swinging strikes divided by total pitches.

Value
Note: The pitcher WAR section of the Library is still in need of revision!

RA9-WAR (Runs Allowed based WAR):  A comprehensive statistic that estimates the number of wins a player has been worth to his team compared to a freely available player such as a minor league free agent based on his runs allowed per 9.

BIP-Wins (BABIP Wins): An estimate of how many wins a pitcher has added by having a BABIP above or below league average. It adjusts for park and league.

LOB-Wins (Left On-Base Wins): An estimate of how many wins a pitcher has added as a result of stranding runners on base.

FDP-Wins (Fielding Dependent Wins): The sum of BIP-Wins and LOB-Wins. It is also the difference between RA9-Wins and FanGraphs’ standard FIP-based pitching WAR.

RAR (Runs Above Replacement): The number of runs a player has been worth to his team compared to a freely available player based on FIP.

WAR (Wins Above Replacement): A comprehensive statistic that estimates the number of wins a player has been worth to his team compared to a freely available player such as a minor league free agent based on his FIP.

Dollars (Dollar Value of Performance): The amount of money a player’s production would be worth on the free agent market in millions of dollars. This column uses $5.5MM/WAR, but that is a calculation from several years ago. The current number is between $6 million and $7 million.

PITCHf/x Pitch Type
The following represent pitch type percentages according to PITCHf/x data. The name of the pitch is next to each. 

FA% (Four Seam and Unclassified Fastballs)

FT% (Two Seam Fastballs)

FC% (Cutters)

FS% (Split Fingers)

FO% (Forkballs)

SI% (Sinkers)

SL% (Sliders)

CU% (Cuvreballs)

KC% (Knuckle-Curves)

EP% (Ephesuses)

CH% (Changeups)

SC% (Screwballs)

KN% (Knuckleballs)

UN% (Unknowns)

PITCHf/x Velocity
The following are the average velocities according to PITCHf/x data. The name of the pitch is next to each.

vFA (Four Seam and Unclassified Fastballs)

vFT (Two Seam Fastballs)

vFC (Cutters)

vFS (Split Fingers)

vFO (Forkballs)

vSI (Sinkers)

vSL (Sliders)

vCU (Cuvreballs)

vKC (Knuckle-Curves)

vEP (Ephesuses)

vCH (Changeups)

vSC (Screwballs)

vKN (Knuckleballs)

vUN (Unknowns)

PITCHf/x H-Movement
The following are the average horizontal movements of the pitches according to PITCHf/x. The name of the pitch is next to each. (Negative values move toward RHH, positive values move toward LHH)

FA-X (Four Seam and Unclassified Fastballs)

FT-X (Two Seam Fastballs)

FC-X (Cutters)

FS-X (Split Fingers)

FO-X (Forkballs)

SI-X (Sinkers)

SL-X (Sliders)

CU-X (Cuvreballs)

KC-X (Knuckle-Curves)

EP-X (Ephesuses)

CH-X (Changeups)

SC-X (Screwballs)

KN-X (Knuckleballs)

UN-X (Unknowns)

PITCHf/x V-Movement
The following are the average vertical movements of the pitches according to PITCHf/x. The name of the pitch is next to each. (Numbers are relative to a pitch with no spin, meaning gravity’s effect is removed)

FA-Z (Four Seam and Unclassified Fastballs)

FT-Z (Two Seam Fastballs)

FC-Z (Cutters)

FS-Z (Split Fingers)

FO-Z (Forkballs)

SI-Z (Sinkers)

SL-Z (Sliders)

CU-Z (Cuvreballs)

KC-Z (Knuckle-Curves)

EP-Z (Ephesuses)

CH-Z (Changeups)

SC-Z (Screwballs)

KN-Z (Knuckleballs)

UN-Z (Unknowns)

PITCHf/x Pitch Type Value
The following are runs above average against each pitch using PITCHf/x data. The name of the pitch is next to each. Learn about pitch values here.

wFA (Four Seam and Unclassified Fastballs)

wFT (Two Seam Fastballs)

wFC (Cutters)

wFS (Split Fingers)

wFO (Forkballs)

wSI (Sinkers)

wSL (Sliders)

wCU (Cuvreballs)

wKC (Knuckle-Curves)

wEP (Ephesuses)

wCH (Changeups)

wSC (Screwballs)

wKN (Knuckleballs)

wUN (Unknowns)

PITCHf/x Pitch Value/100
The following are runs above average against each pitch per 100 pitches using PITCHf/x data. The name of the pitch is next to each. Learn about pitch values here.

wFA/C (Four Seam and Unclassified Fastballs)

wFT/C (Two Seam Fastballs)

wFC/C (Cutters)

wFS/C (Split Fingers)

wFO/C (Forkballs)

wSI/C (Sinkers)

wSL/C (Sliders)

wCU/C (Cuvreballs)

wKC/C (Knuckle-Curves)

wEP/C (Ephesuses)

wCH/C (Changeups)

wSC/C (Screwballs)

wKN/C (Knuckleballs)

wUN/C (Unknowns)

PITCHf/x Plate Discipline
The following are plate discipline numbers using PITCHf/x data. Learn about plate discipline numbers here.

IP (Innings Pitched): Number of total innings pitched (.1 represents 1/3 of an inning, .2 represents 2/3 of an inning).

O-Swing% (Outside the Zone Swing Percentage): Swings at pitches outside the zone divided by pitches outside the zone.

Z-Swing% (Inside the Zone Swing Percentage): Swings at pitches inside the zone divided by pitches inside the zone.

Swing% (Swing Percentage): Swings divided by total pitches.

O-Contact% (Outside the Zone Contact Percentage): Contact made outside the zone divided by swings outside the zone.

Z-Contact% (Inside the Zone Contact Percentage): Contact made inside the zone divided by swings inside the zone.

Contact% (Contact Percentage): Contact made divided by swings.

Zone% (Zone Percentage): Pitches inside the zone divided by total pitches.

Pace (Average Time Between Pitches): Average time between pitches seen by a batter, based on PITCHf/x timestamps.

Other
GSv2 (Game Score Version 2.0): FanGraphs’ version of Game Score, which rates starts based on outs, strikeouts, walks, hits, and home runs.

