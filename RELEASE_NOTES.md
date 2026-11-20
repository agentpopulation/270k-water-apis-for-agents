## Rivers and water API endpoints, snapshot 15 Nov 2026

- 279,947 endpoints passed a keyless data call, tested 10–15 Nov 2026 (IST)
- 12,045 services · 250 country codes · 226,036 keyless JSON rows

### Download

- `Water_API_Endpoints_AgentPopulation_Snapshot_2026-11-15.csv.gz`: the full list, 279,947 rows, 10.8 MB gzipped (89.1 MB as CSV), SHA-256 `4b8ce2b35ba71e69a4a05d6aabeae38a5adff85cf8da1ef372fc92447becf623`
- `SHA256SUMS.txt`: the checksum of that file

Check the download in the folder that holds both files:

```bash
sha256sum -c SHA256SUMS.txt          # Linux
shasum -a 256 -c SHA256SUMS.txt      # macOS
certutil -hashfile Water_API_Endpoints_AgentPopulation_Snapshot_2026-11-15.csv.gz SHA256   # Windows: compare with SHA256SUMS.txt
```

Then `gunzip Water_API_Endpoints_AgentPopulation_Snapshot_2026-11-15.csv.gz` and pass the CSV path to the examples or to `node tools/test-endpoints.mjs`. The repository itself holds a 1,000-row sample and the services list.

### What's in it for you

- 🤖 Agent tools: 42,576 · Wrap a gauge URL as a get_river_level tool: pass the site id, return the latest level and time.
- 📱 App features: 43,976 · Show flood warnings on a map and tide times on a card.
- 🧠 Grounding and data pipelines: 113,774 · Load ocean, tide and groundwater series on a schedule into your own store.
- 🧪 Evals and testing: 279,947 · Run your tool calls against a fixed set of URLs across formats and record which answer; last_tested is the baseline for your own re-tests.

### Changes

- New snapshot: 279,947 endpoints from 12,045 services, tested 10–15 Nov 2026 (IST), snapshot 15 Nov 2026; 93,799 more endpoints than the 14 Nov 2026 release (186,148 endpoints from 8,401 services).
- Left out: 1,023 rows whose URL carried a credential-looking parameter or a login.
- Left out: 1 row with an email-like address.
- Left out: 1,702 ArcGIS Survey123 layers (they can hold people's form answers).
- Left out: 2 camera or image URLs (webcam and camera feeds, picture and video files).
- Left out: 531 class-exercise copies of the same few ArcGIS Online layers (Miami Beach sea level rise, high-risk areas without shelter, flooded areas, sea level rise and storm surge maps) across many organisations, many with a person's name in the title.
- Left out: 11 layers marked editable in the title (they can hold entries that people added).
- Left out: 326 ArcGIS layers that keep a form's default service name (they can hold people's form answers).
- Left out: 2,170 ArcGIS class or coursework layers (lab, assignment, exam, quiz, lesson, exercise, tutorial and final-project layers, copies of class layers, layers named for a person or a person's home, and layers whose name ends in a person's name or holds a student number).
- Left out: 126 ArcGIS layers that hold reports, comments, submissions or form responses sent in by the public.
- Left out: 116 rows of server information from Mastodon, PeerTube, Lemmy, Nostr and other social network servers (instance documents name the server's contact person).
- Overlap: 17,630 of these URLs are also in 190k-weather-apis-for-agents.
- Overlap: 2,556 of these URLs are also in 270k-transit-apis-for-agents.
- Overlap: 1,084 of these URLs are also in 130k-finance-economy-apis-for-agents.
- Overlap: 1,810 of these URLs are also in 130k-india-apis-for-agents.
- Overlap: 2,525 of these URLs are also in 1.3m-government-open-data-apis.
- Overlap: 172 of these URLs are also in 290k-statistics-apis-for-agents.
- Overlap: 86,107 of these URLs are also in 86k-oceans-apis-for-agents.
- Overlap: 3,104 of these URLs are also in 24k-maritime-apis-for-agents.
- Overlap: 4,612 of these URLs are also in 170k-environment-apis-for-agents.
- Overlap: 400 of these URLs are also in 20k-air-quality-apis-for-agents.
- Overlap: 3,014 of these URLs are also in 380k-maps-gis-apis-for-agents.
- Overlap: 226,036 of these URLs are also in 2.5m-agent-ready-apis.
- Overlap: 156 of these URLs are also in 96k-health-apis-for-agents.
- Overlap: 6,521 of these URLs are also in 380k-science-apis-for-agents.
- Overlap: 6,148 of these URLs are also in 53k-hazards-apis-for-agents.
- Overlap: 80 of these URLs are also in 6.5k-wildfire-apis-for-agents.
- Overlap: 195 of these URLs are also in 72k-energy-apis-for-agents.
- Overlap: 254 of these URLs are also in 25k-aviation-apis-for-agents.
- Overlap: 1,129 of these URLs are also in 24k-traffic-apis-for-agents.
- Overlap: 114 of these URLs are also in 12k-parking-apis-for-agents.
- Overlap: 226 of these URLs are also in 10k-earthquake-apis-for-agents.
- Overlap: 166 of these URLs are also in 5.2k-volcano-tsunami-apis-for-agents.

On the date in last_tested (IST), one GET to the URL, sent with no key, returned HTTP 2xx and a non-empty data body. HTML pages and empty results did not pass. The format column records what came back. This is a test result for that date, not a promise that the URL answers today. Licences, terms, rate limits, accuracy and freshness were not reviewed. Endpoints are URLs, not separate APIs; many share one service. This pack was tested 10–15 Nov 2026; snapshot 15 Nov 2026.

For the latest tested endpoints, search agentpopulation.com/apis. This pack is a snapshot from 15 Nov 2026.

Credit: Rivers and water API endpoints by AgentPopulation (https://agentpopulation.com), CC BY 4.0, snapshot 15 Nov 2026.

Compiled by [AgentPopulation](https://agentpopulation.com) with [AP Desk](https://github.com/agentpopulation/apdesk) · corrections: [@agentpopulation](https://x.com/agentpopulation) on X
