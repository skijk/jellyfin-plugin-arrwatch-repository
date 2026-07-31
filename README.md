# Arr Watch plugin repository

Development catalog for Arr Watch releases.

Add this URL under **Dashboard → Plugins → Repositories**:

```text
https://raw.githubusercontent.com/skijk/jellyfin-plugin-arrwatch-repository/main/manifest.json
```

## Dependencies and integrations

| Component | Status | Used for |
| --- | --- | --- |
| Jellyfin 10.11.11 | Required | Supported server and web client |
| File Transformation | Required | Loads the Arr Watch web assets |
| Radarr v3 API | Optional | Movie monitoring state, digital release dates and artwork |
| Sonarr v3 API | Optional | Future season premieres and artwork |
| Jellyfin Enhanced | Optional | Shows Radarr monitoring state in Enhanced search |
| JellySpotlight | Optional consumer | Displays movies and season premieres in **Coming soon** |

Radarr and Sonarr are configured and cached independently. Arr Watch does not
require Jelana, Playback Reporting, JellyBulletin or JS Injector.
