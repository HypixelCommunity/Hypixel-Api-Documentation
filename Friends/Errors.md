# Possible Errors
Path: `https://api.hypixel.net/friends` --> `result.cause`


|Error|Issue|
|:-|:-|
|`Invalid API Key`|`Your API Key is not valid`|
|`Missing one or more fields [uuid]`|`You have not specificied neither a UUID nor a name`|
|`Malformed UUID`|`The UUID specified is either too short or too long`|

If the records key returns an empty array, the UUID does not exist or has no friends

#### Resources
- [Key](https://github.com/Mysterium422/HypixelAPIWiki/tree/main/API%20Usage/GetAKey.md)
- [UUID](https://github.com/Mysterium422/HypixelAPIWiki/tree/main/API%20Usage/UUID.md)