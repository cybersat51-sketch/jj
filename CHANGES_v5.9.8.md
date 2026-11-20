# v5.9.8 — Navigation performance only

- In-memory bounded LRU cache (12 responses, 3 minute TTL) for category, catalogue and series navigation.
- Returning to recently visited lists uses cached JSON immediately, without network wait or loading indicator.
- No player, streaming, buffering, login or UI appearance changes.
- Android build and runtime behavior require verification on GitHub/device.
