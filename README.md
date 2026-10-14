# ROADSCAN Web Dashboard (Prototype)

Demonstration website for **ROADSCAN: Automated Highway Damage Detection and Reporting System**, a thesis proposal of BS Computer Engineering students at STI College Batangas.

This is a **prototype with sample data**. The records, photos, and map are for demonstration only and are not real DPWH data.

## Pages

| Page | What it shows |
|---|---|
| Sign in | Sign-in page for DPWH Mindoro Occidental DEO personnel |
| Damage Map | Detected road damage on a map of national roads in Occidental Mindoro, with a filter by damage type |
| Damage Records | All records with search, filters (type, municipality, date), and sorting |
| Damage Record | One record: photo with the detected damage, GPS location, estimated size, and the date and time it was detected |
| Reports | Report settings and a report preview that can be printed or exported |

Open a page directly by adding its name to the address: `#login`, `#map`, `#records`, `#details`, `#reports`.

## Put it online with GitHub Pages

1. Create a new **public** repository on GitHub, for example `roadscan-dashboard`.
2. Click **Add file → Upload files**, upload `index.html` and `README.md`, then click **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose **main** and **/ (root)**, then click **Save**.
4. Wait 1 to 2 minutes and refresh the Pages settings. The site address appears at the top, like `https://YOUR-USERNAME.github.io/roadscan-dashboard/`.

The whole site is one file (`index.html`), so it works without any other files or installs.
