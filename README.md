# WebGIS khảo sát sạt lở Lạng Sơn

Static Leaflet map for the Lạng Sơn field survey. The public GitHub Pages site is:

<https://quocdungnguyen0810-ux.github.io/langson.utc/>

Leaflet 1.9.4 is bundled for offline library loading; its BSD 2-Clause license is included in `THIRD_PARTY_LICENSES.txt`.

## Live behavior and limits

- Device GPS is requested only after the user selects **Bật định vị** and grants browser permission. The watch updates while the page is open; accuracy is reported by the device and is not guaranteed.
- GPS captures and interpretation notes are kept in that browser profile's `localStorage`. They are not encrypted, uploaded, or synchronized with other users. Export JSON backups before clearing browser data or using **Xóa tọa độ đã lưu**.
- NASA GPM imagery and Open-Meteo forecasts are refreshed periodically from their public services. GPM is delayed satellite precipitation estimation; Open-Meteo is a model forecast, not a local rain-gauge observation. NASA VIIRS image availability also has a delay. “Live” does not mean real-time field measurements.
- The NCHMF alert proxy runs only in the local Python server. GitHub Pages is static and cannot run that API; use the official NCHMF links on the map for current bulletins.
- Survey markers from the source records are approximate locations, not landslide boundaries. The public site does not include field GPS captures or source PDFs.

## Run locally

From the project directory, start the existing map server:

```powershell
python .\research_outputs\2026-11-03_2002\03_web_map\serve_live_map.py
```

Open <http://127.0.0.1:8765/research_outputs/2026-11-03_2002/03_web_map/ban-do-phan-tich-sat-lo.html>. The local server enables the NCHMF proxy; HTTPS or localhost is required for browser GPS.

To preview the GitHub Pages files without the NCHMF proxy, serve this repository directory using any static HTTP server. The published HTTPS site supports browser GPS.

## Publish

In the repository settings, choose **Pages → Deploy from a branch → `main` → `/(root)`**. GitHub Pages publishes the static files from the repository root after each push. No GitHub Actions workflow, secrets, or backend are required.
