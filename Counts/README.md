# Usage
`https://api.hypixel.net/counts?key=KEY`

|Parameter|Example|Description|
|:-|:-|:-|
|`KEY`|`37a52f7d-1123-4785-9354-323f777fe341`|Your Personal API Key|

## Data
|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`cause`|Error Cause|String|The [error](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Counts/Errors.md) in a failed api request|
|`games`|Games|Object|Container for all of the [playercounts by game](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/tree/main/Counts/games)|
|`playercount`|Total Player Count|Integer|Total current Hypixel player count|
|`success`|Success|Boolean|Whether the api query was successful or not|

#### Resources
- [Key](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/GetAKey.md)
- [Error Causes](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Counts/Errors.md)