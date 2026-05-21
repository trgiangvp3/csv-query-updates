# csv-query-updates

Public update manifest for the (private) **CSV Query** app.

`version.json` holds the latest released version. The app polls this file to
notify users when a newer build is available; the actual download stays in the
private release page linked by `url`.

| Field | Meaning |
|-------|---------|
| `version` | Latest released semantic version (e.g. `1.0.2`) |
| `url` | Where the user goes to download it (private release page) |
| `notes` | Short changelog shown in the notification |
| `publishedAt` | Release date (YYYY-MM-DD) |
