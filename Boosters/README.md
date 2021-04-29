# Usage
`https://api.hypixel.net/punishmentstats?key=KEY`

|Parameter|Example|Description|
|:-|:-|:-|
|`KEY`|`37a52f7d-1123-4785-9354-323f777fe341`|Your Personal API Key| 

## Data
|Key|Name|Data Type|Description|
|:-|:-|:-|:-|
|`success`|`Success`|Boolean|Whether the api query was successful or not|
|`watchdog_lastMinute`|`Minutely Watchdog Bans`|Integer|Watchdog bans in the past minute|
|`staff_rollingDaily`|`Daily Staff Bans`|Integer|Staff bans in the past 24 hours|
|`watchdog_total`|`Total Watchdog Bans`|Integer|Lifetime watchdog bans|
|`watchdog_rollingDaily`|`Daily Watchdog Bans`|Integer|Watchdog bans in the past 24 hours|
|`staff_total`|`Total Staff Bans`|Integer|Lifetime staff bans|
|`cause`|`Error Cause`|String|The error in a failed api request|

#### Resources
- [Key](https://github.com/Mysterium422/HypixelAPIWiki/blob/main/API%20Usage/GetAKey.md)
- [UUID](https://github.com/Mysterium422/HypixelAPIWiki/blob/main/API%20Usage/UUID.md)
- [Error Causes](https://github.com/Mysterium422/HypixelAPIWiki/blob/main/Boosters/Errors.md)