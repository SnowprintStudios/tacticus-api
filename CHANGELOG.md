# __2025-02-21__
- ### Features
    - Added field lastUpdatedOn to player metaData, unix timestamp in seconds stating when the playerstate was fetched from the server
- ### Bugfixes
    - Token staminaRegenerationTime fixed
    - Token data refreshed correctly
- ### Changes
    - update lastUpdatedThreshold in player metaData to seconds (from milliseconds). Made it nullable to support apiKeys that don't expire
    - removed lastUpdatedThreshold from token data