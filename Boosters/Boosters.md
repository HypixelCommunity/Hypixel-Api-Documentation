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
|`gameType`|Game Type|Integer [(Game Type)]()|The Game it is boosting|
|`length`|Length|Integer|Booster Length in seconds [(??)](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/issues/7)|
|`originalLength`|Original Length|Integer|Original Booster Length in seconds [(??)](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/issues/7)
|`purchaserUuid`|Owner's UUID|String|Booster Owner's UUID|
|`stacked`|Stacked|Boolean|Whether the booster is stacked or not|

#### Resources
- [Mongo ID](https://www.navicat.com/en/company/aboutus/blog/1010-all-about-mongodb-s-_id-field)
- [UUID](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/UUID.md)
- [Unix Timestamp](https://www.unixtimestamp.com)