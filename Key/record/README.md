# Player counts by game
Path: `https://api.hypixel.net/key` --> `result.record`

## Data
Format: An Object of game containers

|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`key`|Key|String|The key used for the query|
|`limit`|Query Limit|Integer|The API query limit per minute (Defaults to 120)|
|`owner`|Owner UUID|String|The MC UUID of the key owner|
|`queriesInPastMin`|Recent Queries|Integer|Queries made in the past minute. Cannot go higher than the limit|
|`totalQueries`|Total Queries|Integer|Total queries made by the key owner|

#### Resources
- None