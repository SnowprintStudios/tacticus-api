# __2025-03-19__

- ### Features

    - Added guild and guild raid endpoints. To use these endpoints, the newly added scopes Guild + Guild Raid have been added. The current guild for the player is connected to the
      apiKey is fetched. The player needs to be either Leader or Co-leader in the guild to be allowed to fetch the data.
      Guild Raid historical data is not supported for previous seasons.
      Note: It's currently not possible to change the scope of an existing apiKey.

    - Campaign event data has been added to campaigns.
    - Release notes have been added to https://api.tacticusgame.com

# __2025-02-21__
- ### Features
    - Added field lastUpdatedOn to player metaData, unix timestamp in seconds stating when the playerstate was fetched from the server
- ### Bugfixes
    - Token staminaRegenerationTime fixed
    - Token data refreshed correctly
- ### Changes
    - update lastUpdatedThreshold in player metaData to seconds (from milliseconds). Made it nullable to support apiKeys that don't expire
    - removed lastUpdatedThreshold from token data