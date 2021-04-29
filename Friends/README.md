# Usage
`https://api.hypixel.net/friends?key=KEY?uuid=UUID`

|Parameter|Example|More Info|Description|
|:-|:-|:-|:-|
|`KEY`|`37a52f7d-1123-4785-9354-323f777fe341`|[Info](https://github.com/Mysterium422/HypixelAPIWiki/tree/main/API%20Usage/GetAKey.md)|Your Personal API Key| 
|`UUID`|`c7dd703c80274459b8854db90cd13edd`|[Info](https://github.com/Mysterium422/HypixelAPIWiki/tree/main/API%20Usage/UUID.md)|The Player's UUID|

## Data
|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`success`|`Success`|Boolean|Whether the api query was successful or not| 
|`uuid`|`UUID`|String|The queried player's UUID|
|`records`|`Records`|Array|Array of all [Friend Records]()|
|`records[X]`|`Record`|Object|An individual [Friend Record]()|
|`cause`|`Error Cause`|String|[The error in a failed api request]()|

#### Resources
- [Key](https://github.com/Mysterium422/HypixelAPIWiki/tree/main/API%20Usage/GetAKey.md)
- [UUID](https://github.com/Mysterium422/HypixelAPIWiki/tree/main/API%20Usage/UUID.md)