# Assignment

There's a data dictionary for each of the necessary tables at the bottom of this document.
Note: Sometimes data dictionaries are not well kept.

--------------------------------------------------------------------------
player table

- playerID       A unique code assigned to each player. The playerID links the data in this file with records in the other files.
- birthYear      Year player was born
- birthMonth     Month player was born
- birthDay       Day player was born
- birthCountry   Country where player was born
- birthState     State where player was born
- birthCity      City where player was born
- deathYear      Year player died
- deathMonth     Month player died
- deathDay       Day player died
- deathCountry   Country where player died
- deathState     State where player died
- deathCity      City where player died
- nameFirst      Player's first name
- nameLast       Player's last name
- nameGiven      Player's given name (typically first and middle)
- weight         Player's weight in pounds
- height         Player's height in inches
- bats           Player's batting hand (left, right, or both)         
- throws         Player's throwing hand (left or right)
- debut          Date that player made first major league appearance
- finalGame      Date that player made first major league appearance (blank if still active)
- retroID        ID used by retrosheet
- bbrefID        ID used by Baseball Reference website


------------------------------------------------------------------------------
Batting Table

- playerID       Player ID code
- yearID         Year
- stint          player's stint (order of appearances within a season)
- teamID         Team
- lgID           League
- G              Games
- AB             At Bats
- R              Runs
- H              Hits
- 2B             Doubles
- 3B             Triples
- HR             Homeruns
- RBI            Runs Batted In
- SB             Stolen Bases
- CS             Caught Stealing
- BB             Base on Balls
- SO             Strikeouts
- IBB            Intentional walks
- HBP            Hit by pitch
- SH             Sacrifice hits
- SF             Sacrifice flies
- GIDP           Grounded into double plays

------------------------------------------------------------------------------

Teams table

- yearID         Year
- lgID           League
- teamID         Team
- franchID       Franchise (links to TeamsFranchise table)
- divID          Team's division
- Rank           Position in final standings
- G              Games played
- GHome          Games played at home
- W              Wins
- L              Losses
- DivWin         Division Winner (Y or N)
- WCWin          Wild Card Winner (Y or N)
- LgWin          League Champion(Y or N)
- WSWin          World Series Winner (Y or N)
- R              Runs scored
- AB             At bats
- H              Hits by batters
- 2B             Doubles
- 3B             Triples
- HR             Homeruns by batters
- BB             Walks by batters
- SO             Strikeouts by batters
- SB             Stolen bases
- CS             Caught stealing
- HBP            Batters hit by pitch
- SF             Sacrifice flies
- RA             Opponents runs scored
- ER             Earned runs allowed
- ERA            Earned run average
- CG             Complete games
- SHO            Shutouts
- SV             Saves
- IPOuts         Outs Pitched (innings pitched x 3)
- HA             Hits allowed
- HRA            Homeruns allowed
- BBA            Walks allowed
- SOA            Strikeouts by pitchers
- E              Errors
- DP             Double Plays
- FP             Fielding percentage
- name           Team's full name
- park           Name of team's home ballpark
- attendance     Home attendance total
- BPF            Three-year park factor for batters
- PPF            Three-year park factor for pitchers
- teamIDBR       Team ID used by Baseball Reference website
- teamIDlahman45 Team ID used in Lahman database version 4.5
- teamIDretro    Team ID used by Retrosheet


------------------------------------------------------------------------------

Salaries table

- teamID         Team
- yearID         Year
- lgID           League
- playerID       Player ID code
- salary         Salary
