### SteamFriends for Rust

Use the steam api to retrieve a player's friend list.

The player's friend list must be public, and a steam api key is required.

## Configuration
```json
{
  "steamApiKey": null,
  "debug": false,
  "Version": {
    "Major": 1,
    "Minor": 0,
    "Patch": 0
  }
}
```
steamApiKey is required and can be obtained from https://steamcommunity.com/dev/apikey

## Developers
Hooks for developers (the only way to use this plugin)

	- private List<string> GetFriends(BasePlayer player)
        - Returns player friends as a list of steamids as strings

	- private List<string> GetFriends(string UserIDString)
        - Returns player friends as a list of steamids as strings

	- private List<string> GetFriends(int UserID)
        - Returns player friends as a list of steamids as strings

