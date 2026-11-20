# v5.10.3 — Player tap controls

- Intercept ACTION_DOWN at Activity dispatch level without consuming events, so tapping video (including Media3 PlayerView) reveals all player overlays.
- Show back, title, EPG, conditional Replay, favorites, fullscreen and live channel arrows together.
- Auto-hide overlays after 10 seconds of inactivity, reset timer on every touch.
- Update Replay visibility when switching live channels.
- Remove pending overlay callbacks on player release to avoid stale UI changes.
- No changes to network, login or navigation.

Build and device runtime not verified in this environment.
