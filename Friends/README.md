# Usage
`https://api.hypixel.net/friends?key=KEY&uuid=UUID`

|Parameter|Example|Description|
|:-|:-|:-|
|`KEY`|`37a52f7d-1123-4785-9354-323f777fe341`|Your Personal API Key| 
|`UUID`|`c7dd703c80274459b8854db90cd13edd`|The Player's UUID|

## Data
|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`cause`|Error Cause|String|The [error](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Friends/Errors.md) in a failed api request|
|`records`|Records|Array|Array of all [Friend Records](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Friends/Records.md)|
|`records[X]`|Record|Object|An individual [Friend Record](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Friends/Records.md)|
|`success`|Success|Boolean|Whether the api query was successful or not| 
|`uuid`|UUID|String|The queried player's UUID|

#### Resources
- [Key](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/GetAKey.md)
- [UUID](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/UUID.md)
- [Friend Record](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Friends/Records.md)
- [Error Causes](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Friends/Errors.md)