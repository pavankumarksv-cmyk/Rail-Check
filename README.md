# RailCheck

Indian Railway train search and booking planning website.

## Deploy on GitHub Pages

1. Create a new repository on GitHub (e.g. `railcheck`).
2. Upload all files from this folder:
   - `index.html` (main page, logo embedded)
   - `data/` folder with all JSON data and `routes/` subfolder
3. Go to **Settings → Pages**.
4. Source: **Deploy from a branch**.
5. Branch: `main`, Folder: `/ (root)`.
6. Save. Your site will be live at:
   `https://<your-username>.github.io/railcheck/`

## Files

- `index.html` - the entire website (HTML + CSS + JS + embedded logo)
- `data/stations.json` - 8,587 stations
- `data/trains.json` - 10,596 trains
- `data/running_days.json` - running days per train
- `data/schedule_validity.json` - schedule validity dates per train
- `data/station_index.json` - station to trains mapping (for mid-station search)
- `data/rules.json` - booking rules (ARP, Tatkal timings)
- `data/metadata.json` - dataset metadata
- `data/popular_routes.json` - curated popular routes
- `data/routes/{train_number}.json` - per-train route details (10,596 files)

No external dependencies. Works offline once loaded.
