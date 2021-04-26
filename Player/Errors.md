# Possible Errors

The error type can be found when the success is false. In that case, there will be a cause key-value as well. Read that value and match it here.

|Error|Issue|Fix|
|:-|:-|:-|
|`You have already looked up this name recently`|`You are querying the API with a name and not a UUID`|[Fix]()|
|`Invalid API Key`|`Your API Key is not valid`|[Fix]()|
|`Missing one or more fields [uuid]`|`You have not specificied neither a UUID nor a name`|[Fix]()|
|`Malformed UUID`|`The UUID specified is an invalid UUID`|[Fix]()|

If the player key returns null, the UUID or Name was not found in the Hypixel database