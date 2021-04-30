# Usage
`https://api.hypixel.net/boosters?key=KEY`

|Parameter|Example|Description|
|:-|:-|:-|
|`KEY`|`37a52f7d-1123-4785-9354-323f777fe341`|Your Personal API Key| 

## Data
|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`boosters`|Boosters|Array|Array of all [Booster Data](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Boosters/Boosters.md)|
|`boosters[X]`|Booster|Object|An individual [Booster's Data](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Boosters/Boosters.md)|
|`boosterState`|Booster State|Object|Current [Booster State](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/tree/main/Boosters/boosterState)
|`cause`|Error Cause|String|The [error](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Boosters/Errors.md) in a failed api request|
|`success`|Success|Boolean|Whether the api query was successful or not| 

#### Resources
- [Key](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/GetAKey.md)
- [UUID](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/UUID.md)
- [Error Causes](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Boosters/Errors.md)