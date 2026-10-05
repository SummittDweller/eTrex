# Garmin eTrex (Recent Models) Practical Guide

This repository is a practical reference for using a **recent Garmin eTrex** model (for example: eTrex 22x/32x/SE/Solar generation) for geocaching trips.

> Menu labels differ slightly by model/firmware, but workflows below are the same.

## 1) First: identify your exact model and firmware

On the device:
- `Setup` -> `About` (or `System` -> `About`)
- Record:
  - Model name
  - Software version

Why this matters: USB mode names, geocache menu names, and sync options vary by model.

---

## 2) How to connect eTrex to a computer (for downloads/uploads)

1. Use a **data-capable USB cable** (many charge-only cables fail here).
2. Connect eTrex to your computer USB port.
3. Power on eTrex if needed.
4. If prompted on device, choose **Mass Storage** / **File Transfer** mode.
5. Wait for the device to appear as a removable drive (sometimes with a separate microSD volume).
6. Open the Garmin storage and use:
   - `/Garmin/GPX/` for geocache GPX files
   - `/Garmin/` for system folders (do not edit unknown files)

Safe disconnect:
- Eject/unmount from computer first, then unplug USB.

---

## 3) Load destination geocaches *before* a trip (published caches)

## Method A: GPX file workflow (works broadly)

1. On geocaching.com, create/export a GPX for your destination area (Pocket Query or list export).
2. Connect eTrex via USB.
3. Copy GPX file(s) into `/Garmin/GPX/`.
4. Safely eject device.
5. On eTrex, open geocache list/map and confirm caches are indexed.

Tips:
- Use smaller regional GPX files if indexing is slow.
- Keep file names date-based (example: `utah-trip-2026-10.gpx`).

## Method B: Garmin mobile sync models

For models that support Garmin Explore/Connect sync:
1. Build your collection/list in Garmin ecosystem.
2. Sync while on Wi-Fi/cellular *before travel*.
3. Confirm caches/maps are present on device in airplane/no-signal conditions.

---

## 4) Reviewer use case: unpublished/on-hold listings offline

Goal: carry reviewer-relevant listings on eTrex with no field data signal.

Typical approach:
1. Export reviewer-authorized listing data/GPX from reviewer tooling (where your role permits).
2. Connect eTrex by USB.
3. Copy reviewer GPX into `/Garmin/GPX/`.
4. Eject and verify the listings appear in geocache/search lists.

Important:
- Keep unpublished listing data private and policy-compliant.
- Do all sync/export work before departure so field use is fully offline.

---

## 5) Configuration options to set before geocaching trips

Create/adjust a geocaching profile (names vary by model):

- **Units/Format**
  - Position format and map datum (match your workflow)
  - Distance/elevation units
- **Routing**
  - Activity profile (hiking/walking)
  - Route recalculation behavior
- **Map**
  - Orientation (north up vs track up)
  - Detail level
  - Dashboard/data fields (distance to cache, bearing, ETA)
- **Geocaching options**
  - Filter by difficulty/terrain/size/type
  - Found/not found visibility
- **Power/display**
  - Backlight timeout
  - Battery type selection
  - Battery saver mode
- **Sensors (if available)**
  - Compass calibration
  - Altimeter/barometer calibration

Pre-trip checklist:
- Load caches and maps
- Confirm geocache details open correctly
- Verify coordinate format/datum
- Verify free storage space
- Carry spare batteries/power bank as applicable

---

## 6) Common key/menu sequences for field geocaching

Because some newer eTrex units are button-driven and others are touch-driven, use these common navigation patterns:

- Find loaded caches:
  - `Geocaching` -> `Search`/`Nearest`/`Filter`
- Start navigation to a cache:
  - Select cache -> `Go` / `Navigate`
- Log cache result:
  - Open cache -> `Log Attempt` / `Found` / `Did Not Find` / `Needs Maintenance`
- Stop current navigation:
  - Active route/navigation page -> `Stop Navigation`
- Mark current location quickly:
  - `Mark Waypoint` (button/menu shortcut varies by model)
- Recalibrate compass:
  - `Setup` -> `Heading` -> `Calibrate Compass`

If your model has programmable shortcuts, bind one to:
- Geocache list
- Mark waypoint
- Compass/map toggle

---

## 7) Troubleshooting

- Device not recognized by computer:
  - Try a different **data** cable.
  - Try another USB port.
  - Restart eTrex and reconnect.
- GPX copied but caches missing:
  - Confirm file extension is `.gpx`.
  - Place file in `/Garmin/GPX/` (not subfolders unless supported).
  - Split very large files and retry.
- Offline validation before trip:
  - Put phone in airplane mode.
  - Power-cycle eTrex.
  - Confirm target caches still open with full details.

---

## 8) Suggested folder hygiene on device

- Keep active trip GPX files only.
- Archive old GPX files off-device after each trip.
- Use clear file naming by destination + date.

This keeps indexing faster and avoids duplicate cache entries.
