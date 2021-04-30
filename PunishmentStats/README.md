# Usage
`https://api.hypixel.net/punishmentstats?key=KEY`

|Parameter|Example|Description|
|:-|:-|:-|
|`KEY`|`37a52f7d-1123-4785-9354-323f777fe341`|Your Personal API Key| 

## Data
|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`cause`|Error Cause|String|The error in a failed api request|
|`staff_rollingDaily`|Daily Staff Bans|Integer|Staff bans in the past 24 hours|
|`staff_total`|Total Staff Bans|Integer|Lifetime staff bans|
|`success`|`Success`|Boolean|Whether the api query was successful or not|
|`watchdog_lastMinute`|Minutely Watchdog Bans|Integer|Watchdog bans in the past minute|
|`watchdog_rollingDaily`|Daily Watchdog Bans|Integer|Watchdog bans in the past 24 hours|
|`watchdog_total`|Total Watchdog Bans|Integer|Lifetime watchdog bans|




#### Resources
- [Key](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/API%20Usage/GetAKey.md)
- [Error Causes](https://github.com/HypixelCommunity/Hypixel-Api-Documentation/blob/main/PunishmentStats/Errors.md)