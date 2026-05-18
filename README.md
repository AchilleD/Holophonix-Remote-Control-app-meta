# Holophonix Remote Control — App Metadata

Public metadata for the Holophonix Remote Control app.

This repository contains **only metadata** (text JSONs) and is auto-updated
from the private source repo at each release.

## Files

- **`whats_new.json`** — user-facing release highlights (EN + FR per version)
  consumed by the in-app "What's New" popup
- **`versions.json`** — version manifest (latest version, supported channels,
  store URLs) consumed by the in-app "Check For Update" feature

## URLs (served via GitHub Pages)

- https://achilled.github.io/Holophonix-Remote-Control-app-meta/whats_new.json
- https://achilled.github.io/Holophonix-Remote-Control-app-meta/versions.json

## Do not edit directly

These files are generated from the source repo via the release workflow.
Editing here will be overwritten at the next release.

For typo fixes / translation tweaks in `whats_new.json`, edit the source
in the main repo (`flutter_app/lib/data/whats_new.dart`), regenerate, and
push back here through the release procedure.
