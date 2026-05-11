# KARTE — Map Data

Public map layer data for the KOMPASS project.  
Base point: Charlottenburg Palace, Berlin (52.5208° N, 13.2957° E)

## Files

| File | Description | Felt Layer |
|---|---|---|
| `base_point.geojson` | Charlottenburg Palace pin | Base Point |
| `rings.geojson` | 30 / 60 / 120 km distance rings | Distance Rings |
| `exclusion.geojson` | Inner 30km exclusion zone | Exclusion |
| `zones_v01.geojson` | 4 directional hunt zones (N/E/S/W) | Hunt Zones |
| `roads.geojson` | Key Autobahn corridors | Roads |
| `discoveries.geojson` | Live discoveries & pins | Discoveries |

## Felt URLs

Add each file as a layer in Felt using the raw GitHub URL:
```
https://raw.githubusercontent.com/ubuntusharedrive/mapfun/main/karte/<filename>
```

Set refresh interval to auto-update when files change.

---
*Map data only — no project strategy or scoring.*
