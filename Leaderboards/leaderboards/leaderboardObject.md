# Player counts by game
Path: `https://api.hypixel.net/leaderboards` --> `result.leaderboards.MODE[INDEX]`

## Data
Format: An Object of leaderboard info for a specific gamemode.

|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`path`|Path|String|Path to the stat used to sort the leaderboards in the player endpoint|
|`prefix`|Prefix|String|Leaderboard Type (Overall/Lifetime/Weekly/Monthly)|
|`title`|Title|String|Leaderboard Title|
|`location`|Location"|x,y,z (String)|Leaderboard Location (Incorrect/Unused)|
|`count`|Count|Integer|# of players on leaderboard|
|`leaders`|Leaders|Array|Array of Leaders' UUIDs|
|`leaders[X]`|Leader UUID|String|UUID of the player in the X+1 position|

#### Resources
- [UUID](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/UUID.md)