# DBS311
<h3>Seneca College DBS311 Final Project</h3>
<p>Date: 2021-12-07</p></br>

<h5>/* ERROR CODES */</h5>
<p>
--------------------------------------------------</br>
--EXCEPTION (errcode)</br>
-- -1 : NO_DATA_FOUND</br>
-- -2 : TOO_MANY_ROWS</br>
-- -3 : OTHERS</br>
-- -4 : Not in condition</br>
--------------------------------------------------</br>


<h5>/* CRUD Operations by Tables */</h5>
<p>
--------------------------------------------------</br>
Table: Games</br>
Table: GoalScorers</br>
Table: Players</br>
Table: Teams</br>
Table: Rosters</br>
Table: slLocations</br>
--------------------------------------------------</br>
</p>

<h5>/* Stored Procedures */</h5>
<p>
--------------------------------------------------</br>
spTeamRosterByID: Get Team Roster by Team ID</br>
spTeamRosterByName: Get Team Roster by Team Name</br>
spSchedUpcomingGames: Get Schedule for Upcoming Games</br>
spSchedPastGames: Get Schedule for Past Games</br>
--------------------------------------------------</br>
</p>

<h5>/* Views */</h5>
<p>
--------------------------------------------------</br>
vwPlayerRosters: Get Team Roster of Each Team</br>
vwTeamsNumPlayers: Get List of Number of Players of Each Team</br>
vwSchedule: Get Schedule for All Games</br>
--------------------------------------------------</br>
</p>
  
<h5>/* User Defined Functions */</h5>
<p>
--------------------------------------------------</br>
fncNumPlayersByTeamID: Get Total Number of Players of Team by Team ID</br>
fncWinningRateByTeam: Get Winnning Rate of all matches by Team Name</br>
--------------------------------------------------</br>
</p>
