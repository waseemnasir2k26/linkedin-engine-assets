# 2026.09 — Maintenance release

- Maintenance review of linkedin-engine-assets — the public image host for the LinkedIn campaign run out of the private `linkedin-engine` repo; the scheduling CSVs reference these files by raw URL because GHL needs publicly reachable image links.
- Contents: 28 files only — `day01/` and `day06/` carousel slide PNGs (8 and 10 slides), `day02/` and `day08/` single-image cards, `day04/` photo, and `week2/` with the seven week-2 post images (cafe/work photos, two DJI drone frames, an event portrait).
- Status: pure asset repo — no code, no build, no package manifest, no README. Last change August 2026 (week-2 post images).
- Reviewed September 2026: README added, CHANGELOG started, versioned as v2026.09. No images added, removed or re-encoded.
- Known gaps: no README before this release and no LICENSE; the repo is public and the filenames describe the photos (people, places, dates), so it is not suitable for anything that needs to stay unattributed; asset naming is campaign-day-based, so it does not survive being reused outside that one campaign.
