# Usage
`https://api.hypixel.net/key?key=KEY`

|Parameter|Example|Description|
|:-|:-|:-|
|`KEY`|`37a52f7d-1123-4785-9354-323f777fe341`|Your Personal API Key|

## Data
|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`cause`|Error Cause|String|The [error](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Key/Errors.md) in a failed api request|
|`record`|Games|Object|Container for all of the [key info](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/tree/main/Key/record)|
|`success`|Success|Boolean|Whether the api query was successful or not|

#### Resources
- [Key](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/GetAKey.md)
- [Error Causes](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/Key/Errors.md)