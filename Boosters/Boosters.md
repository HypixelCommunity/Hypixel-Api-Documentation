# Records
Path: `https://api.hypixel.net/boosters` --> `result.boosters`

## Data
Format: An Array of Booster Data

### Booster Data
Format: JSON Object

|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`__id`|Mongo DB ID|String|A unique Mongo ID|
|`amount`|Amount|Number|Booster Amount|
|`dateActivated`|Date Activated|Unix Timestamp|Date the booster was activated|
|`gameType`|Game Type|Integer [(Game Type)](###-game-types)|The Game it is boosting|
|`length`|Length|Integer|Booster Length in seconds [(??)](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/issues/7)|
|`originalLength`|Original Length|Integer|Original Booster Length in seconds [(??)](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/issues/7)
|`purchaserUuid`|Owner's UUID|String|Booster Owner's UUID|
|`stacked`|Stacked|Boolean|Whether the booster is stacked or not|

### Game Types
|ID|Game Name|
|:-|:-|
|`2`|Quake|
|`3`|Walls|
|`4`|Paintball|
|`5`|Blitz Survival Games|
|`6`|TNT Games|
|`7`|VampireZ|
|`13`|Mega Walls|
|`14`|Arcade|
|`17`|Arena|
|`20`|UHC Champions|
|`21`|Cops and Crims|
|`23`|Warlords|
|`24`|Smash Heroes|
|`25`|Turbo Kart Racers|
|`26`|Housing|
|`51`|SkyWars|
|`52`|Crazy Walls|
|`54`|Speed UHC|
|`55`|SkyClash|
|`56`|Classic Games|
|`57`|Prototype|
|`58`|Bed Wars|
|`59`|Murder Mystery|
|`60`|Build Battle|
|`61`|Duels|
|`63`|SkyBlock|
|`64`|Pit|

#### Resources
- [Mongo ID](https://www.navicat.com/en/company/aboutus/blog/1010-all-about-mongodb-s-_id-field)
- [UUID](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/UUID.md)
- [Unix Timestamp](https://www.unixtimestamp.com)