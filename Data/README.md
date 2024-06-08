# Data

Data has been collected from here: https://figshare.com/collections/Soccer_match_event_dataset/4415000/2

The JSON files used are as follows:
* event_England.json (this one could not be uploaded to GitHub as it is too large)
  * An entry per event (eg. a pass, shot, tackle)
  * Contains PlayerID, TeamId and matchId
  * Provides coordinates of the pitch
* matches_England.json
  * An entry per match
  * Provides details of teams playing and their line ups
  * Also details the substitutions that are made
* players.json
  * An entry per player
  * Provides us with the preferred position or role of each player
* teams.json
  * An entry per team
  * Provides us with the full name of each team