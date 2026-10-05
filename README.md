# Garmin eTrex SE Practical Guide

This repository is a practical reference for using **your Garmin eTrex SE** for geocaching trips.

> This guide is intentionally tuned to eTrex SE behavior and menus.

## 1) Device Identity and Firmware Baseline

On the device, open:
- `Setup` -> `About` (or `System` -> `About`)

Record:
- Software version
- Any visible hardware or unit identifiers

Why this matters: firmware version affects menu labels and what is shown on the About screen.

### Confirmed Device Record (2026-10-05)

- Model: eTrex SE (confirmed by Garmin iPhone app over Bluetooth)
- Serial number: 82P048706
- Firmware observed: 5.11
- Note: About screen may omit model information on this firmware; app-side identification confirms device identity.

---

## 2) How to Connect eTrex to a Computer (for Downloads/Uploads)

For eTrex SE, phone sync over Bluetooth is usually the primary workflow, with USB as a file-management fallback.

1. Use a **data-capable USB cable** (many charge-only cables fail here).
2. Connect eTrex to your computer USB port.
3. Power on eTrex if needed.
4. If prompted on device, choose **Mass Storage** / **File Transfer** mode.
5. Wait for the device to appear as a removable drive.
6. Open the Garmin storage and use:
   - `/Garmin/GPX/` for geocache GPX files
   - `/Garmin/` for system folders (do not edit unknown files)

Safe disconnect:
- Eject/unmount from computer first, then unplug USB.

---

## 3) Load Destination Geocaches *Before* a Trip (Published Caches)

## Method A: Bluetooth App Sync (Recommended for eTrex SE)

1. In the Garmin iPhone app/ecosystem, build the geocache list or collection you want for the trip.
2. Keep phone + eTrex SE connected over Bluetooth.
3. Run a sync before leaving home.
4. On the eTrex SE, open geocache lists and confirm target caches are present.
5. Repeat one final sync after any last-minute list edits.

Why this is preferred on eTrex SE: app sync is the most direct way to confirm device identity and keep trip content aligned with your phone.

## Method B: GPX File Workflow (USB Fallback)

1. On geocaching.com, create/export a GPX for your destination area (Pocket Query or list export).
2. Connect eTrex via USB.
3. Copy GPX file(s) into `/Garmin/GPX/`.
4. Safely eject device.
5. On eTrex, open geocache list/map and confirm caches are indexed.

Tips:
- Use smaller regional GPX files if indexing is slow.
- Keep file names date-based (example: `utah-trip-2026-10.gpx`).

---

## 4) Reviewer Use Case: Unpublished/On-Hold Listings Offline

Goal: carry reviewer-relevant listings on eTrex SE with no field data signal.

Typical approach:
1. Export reviewer-authorized listing data/GPX from reviewer tooling (where your role permits).
2. Connect eTrex by USB.
3. Copy reviewer GPX into `/Garmin/GPX/`.
4. Eject and verify the listings appear in geocache/search lists.

Important:
- Keep unpublished listing data private and policy-compliant.
- Do all sync/export work before departure so field use is fully offline.

---

## 5) Configuration Options to Set Before Geocaching Trips

Create or adjust a geocaching profile on eTrex SE:

- **Units/Format**
  - Position format and map datum (match your workflow)
  - Distance/elevation units
- **Routing**
  - Activity profile (hiking/walking)
  - Route recalculation behavior
- **Map/Navigation View**
  - Orientation (north up vs track up)
  - Detail level
  - Dashboard/data fields (distance to cache, bearing, ETA)
- **Geocaching Options**
  - Filter by difficulty/terrain/size/type
  - Found/not found visibility
- **Power/Display**
  - Backlight timeout
  - Battery type selection
  - Battery saver mode
- **Sensors (if Available)**
  - Compass calibration
  - Altimeter/barometer calibration

Pre-trip checklist:
- Load caches and maps
- Confirm geocache details open correctly
- Verify coordinate format/datum
- Verify free storage space
- Carry spare batteries/power bank as applicable

---

## 6) Common Key/Menu Sequences for Field Geocaching

eTrex SE is button-driven, so these are optimized for button navigation patterns:

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
- About Screen Missing Model Name:
  - If firmware is 5.11, this can be a UI issue.
  - Confirm identity in the Garmin iPhone app over Bluetooth.
  - Keep firmware version + serial in the service history table.

---

## 8) Suggested Folder Hygiene on Device

- Keep active trip GPX files only.
- Archive old GPX files off-device after each trip.
- Use clear file naming by destination + date.
- Keep one "current trip" list in the mobile app to reduce sync confusion.

This keeps indexing faster and avoids duplicate cache entries.

---

## 9) Service History

Use this log to track firmware updates, resets, and notable behavior changes.

| Date | Firmware | Model shown in About | App-detected model | Notes |
|---|---|---|---|---|
| 2026-10-05 | 5.11 | Missing/blank on About screen | eTrex SE | Garmin iPhone app over Bluetooth confirms model; serial 82P048706. |

---

## 10) Clear Previously Loaded Geocaches Before Adding More

Use one of these methods depending on how caches were loaded.

## Method A: Clear Through Bluetooth App Sync (Preferred)

1. In the Garmin iPhone app/ecosystem, remove old geocache lists or collections from the sync set.
2. Keep phone + eTrex SE connected over Bluetooth.
3. Run sync.
4. On eTrex SE, open geocache list and confirm old entries are gone.

This is the safest first option because it keeps phone and device aligned.

## Method B: USB GPX Deep-Clean (When Old Caches Persist)

1. Connect eTrex SE to computer in file transfer mode.
2. Open `/Garmin/GPX/`.
3. Back up the folder to your computer before deleting anything.
4. Delete previously copied trip GPX files from `/Garmin/GPX/`.
5. Eject/unmount safely, then reboot eTrex SE.
6. Recheck geocache list to confirm it is cleared.

Safety notes:
- Do not delete unknown files outside `/Garmin/GPX/`.
- If unsure about a GPX file, move it to a backup folder on computer instead of permanent deletion.

## Reload Workflow After Clearing

1. Confirm geocache list is empty or only contains entries you want to keep.
2. Load the new trip set using app sync or fresh GPX files.
3. Verify sample caches open with full details before heading out.
