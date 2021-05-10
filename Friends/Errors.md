# Possible Errors
Path: `https://api.hypixel.net/friends` --> `result.cause`


|Error|Issue|
|:-|:-|
|`Invalid API Key`|Your API Key is not valid|
|`Malformed UUID`|The UUID specified is either too short or too long|
|`Missing one or more fields [uuid]`|You have not specificied a UUID|
|`Missing one or more fields [key]`|You have not specificied an API Key|
|`Unknown endpoint`|The end point which was entered is not valid|

If the records key returns an empty array, the UUID does not exist or has no friends

#### Resources
- [Key](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/tree/main/API%20Usage/GetAKey.md)
- [UUID](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/tree/main/API%20Usage/UUID.md)