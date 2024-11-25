# DB

### Leagues
* Id
* Name
* Description
* Created date

### Seasons
* Id
* Leagues id
* Name
* End date
* Start date

### Matches
* Id
* Season id
* Score
* Date
* TeamA (team id)
* TeamB (team id)
* TeamA goals
* TeamB goals
* TeamA red cards
* TeamB red cards
* TeamA yellow card

### Teams
* Id
* Name
* Icon
* Created date
* League id

### Players
* Id
* Name
* Icon
* Team id
* Created date

### Roles
* Admin - Basically god.
* League owner  - Can create, read, edit and delete seasons, matches, teams and players.
* Referee - Can edit matches
* Player - Can create, read, edit and delete a player.

**File version 0.0.1**
