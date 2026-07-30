# Radarr Watch plugin repository

Jellyfin catalog for Radarr Watch releases.

Add this URL under **Dashboard → Plugins → Repositories**:

```text
https://raw.githubusercontent.com/skijk/jellyfin-plugin-radarrwatch-repository/main/manifest.json
```

## Dependencies and integrations

| Component | Status | Used for |
| --- | --- | --- |
| Jellyfin 10.11.11 | Required | Supported server and web client |
| File Transformation | Required | Loads the Radarr Watch web assets |
| Radarr v3 API | Required service | Supplies monitored movie and digital release data |
| Jellyfin Enhanced | Optional | Shows request/monitoring state in Enhanced search |
| JellySpotlight | Optional consumer | Displays confirmed future digital releases in **Coming soon** |

Radarr Watch does not require Jelana, Playback Reporting, JellyBulletin or JS Injector.
