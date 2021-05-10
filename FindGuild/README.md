# Usage
`https://api.hypixel.net/findguild?key=KEY&byUuid=UUID`

**Deprecated. Use: `https://api.hypixel.net/guild?key=KEY&player=UUID`**

|Parameter|Example|Description|
|:-|:-|:-|
|`KEY`|`37a52f7d-1123-4785-9354-323f777fe341`|Your Personal API Key| 
|`UUID`|`c7dd703c80274459b8854db90cd13edd`|The Player's UUID|

## Data
|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`cause`|Error Cause|String|The [error](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/FindGuild/Errors.md) in a failed api request|
|`guild`|Guild|String|The Unique Guild ID for the player's guild|
|`success`|Success|Boolean|Whether the api query was successful or not| 

#### Resources
- [Key](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/GetAKey.md)
- [UUID](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/UUID.md)
- [Error Causes](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/FindGuild/Errors.md)