# DBS311
Seneca College DBS311 Final Project
Date: 2021-12-07

/* ERROR CODES */
--------------------------------------------------
--EXCEPTION (errcode)
-- -1 : NO_DATA_FOUND
-- -2 : TOO_MANY_ROWS
-- -3 : OTHERS
-- -4 : Not in condition
--------------------------------------------------

/* CRUD Operations by Tables */
--------------------------------------------------
Table: Games
Table: GoalScorers
Table: Players
Table: Teams
Table: Rosters
Table: slLocations
--------------------------------------------------

/* Stored Procedures */
--------------------------------------------------
spTeamRosterByID: Get Team Roster by Team ID
spTeamRosterByName: Get Team Roster by Team Name
spSchedUpcomingGames: Get Schedule for Upcoming Games
spSchedPastGames: Get Schedule for Past Games
--------------------------------------------------

/* Views */
--------------------------------------------------
vwPlayerRosters: Get Team Roster of Each Team
vwTeamsNumPlayers: Get List of Number of Players of Each Team
vwSchedule: Get Schedule for All Games
--------------------------------------------------

/* User Defined Functions */
--------------------------------------------------
fncNumPlayersByTeamID: Get Total Number of Players of Team by Team ID
fncWinningRateByTeam: Get Winnning Rate of all matches by Team Name
--------------------------------------------------
