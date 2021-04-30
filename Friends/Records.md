# Records
Path: `https://api.hypixel.net/friends` --> `result.records`

## Data
Format: An Array of Friend Records

### Friend Record
Format: JSON Object

|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`__id`|Mongo DB ID|String|A unique Mongo ID|
|`uuidSender`|Sender UUID|String|Friend request sender's UUID|
|`uuidReceiver`|Receiver UUID|String|Friend request receiver's UUID|
|`started`|Date Started|Unix Timestamp|Friendship's start date|

#### Resources
- [Mongo ID](https://www.navicat.com/en/company/aboutus/blog/1010-all-about-mongodb-s-_id-field)
- [UUID](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/UUID.md)
https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/UUID.md
- [Unix Timestamp](https://www.unixtimestamp.com)