

β3.2.3 PORTRAIT TILE CENTER FIX
- Portrait map now uses a true dynamic 7x7 tile grid.
- KAMADOYA is centered inside the exact center tile, not on a tile boundary.
- Map scrolling distance now equals one mobile tile exactly.
- Portrait field tap uses pointer events to avoid duplicate touch/click movement.


β3.3 TRAVIAN FIELD
- Rebuilt field terrain toward a Travian-style illustrated world map.
- Added seamless grassy base, clustered forests, rocky mountains, lakes, palm oases and village art.
- Added Y-coordinate meter on left edge and X-coordinate meter on bottom edge.
- Center coordinate is highlighted and meters follow movement.
- Existing 100x100 logical map, one-square movement, centered KAMADOYA, battles and rewards retained.


β3.3.1 MOBILE CONSISTENCY FIX
- Rechecked portrait 7x7 field against the new Travian-style terrain.
- X/Y coordinate rails align exactly with the seven visible mobile columns/rows.
- Coordinate rails cannot block field taps.
- KAMADOYA remains inside the exact center tile and above coordinate overlays.
- Rotation/resize triggers a field re-render to keep tile geometry synchronized.
- Large portrait enemy art and enlarged ATTACK touch target retained.
