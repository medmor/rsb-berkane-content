# RSB Berkane Content

Static JSON data for the [RSB Berkane Hub](https://github.com/medmor/rsb-berkane-hub) website, served via GitHub Pages CDN.

## Files

| File | Description |
|------|-------------|
| `matches.json` | Match fixtures and results |
| `players.json` | Player roster and stats |
| `coaching-staff.json` | Coaching staff |
| `news.json` | Club news articles |
| `trophies.json` | Club trophies and achievements |
| `club-stats.json` | Club statistics (founded, stadium, etc.) |

## CDN URL

```
https://medmor.github.io/rsb-berkane-content/<file>
```

Example: `https://medmor.github.io/rsb-berkane-content/matches.json`

## Update Flow

1. Scraper runs and updates JSON files
2. Commit and push to `main` branch
3. GitHub Pages serves updated files within ~30 seconds
4. No app rebuild needed — the Next.js app fetches from CDN at runtime