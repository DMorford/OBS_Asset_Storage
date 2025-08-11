# OBS_Asset_Storage

This repo contains OBS overlays and related assets in one place.

Contents:
- overlays/ — the original browser overlays (like the lower third)
- obs/ — wrapper files for OBS that can remap assets

Usage (recommended):
- In OBS Browser Source, use Local File and point to overlays/lower-third.html.
- Or host via an app and use http://localhost:3000/obs/lower-third.html.

Notes:
- overlays/assets contains example logo/guitar images; replace with your own.
- You can pass ?autoHide=1 to auto-hide after the animation.
