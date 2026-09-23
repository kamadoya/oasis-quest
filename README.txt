

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


β3.3.2 FIELD COORDINATES ONLY
- X/Y coordinate meters are now field-screen UI only.
- Coordinate meters are explicitly hidden during battle, level-up/party overlays, rewards and reward history.
- Added JavaScript fallback in addition to CSS so mobile browsers stay consistent.


β3.3.3 OASIS MARKER FIX
- Reduced the cyan diamond oasis marker to 40% of its previous linear size (60% smaller).
- Field coordinates, mobile layout, battle UI, rewards and gameplay retained.


β3.3.4 BATTLE SPRITE REFRESH
- Approved new KAMADOYA and Uma-chan battle art installed.
- Transparent-background battle sprites; other systems unchanged.


β3.3.5 ALL PARTY BATTLE ART
- KAMADOYA: approved Roman sword + scutum battle art.
- Uma-chan: approved clean transparent pony battle art.
- Doowee: approved Gaul/Celtic green battle art.
- Naughty: approved Roman cavalry art riding Equites Caesaris.
- Existing party progression, battle logic, mobile fixes, field coordinates and rewards retained.


β3.4 OPENING TITLE
- Added the approved KAMADOYA + Uma-chan OASIS QUEST title artwork as the opening screen.
- NEW GAME starts the existing field game; tapping the title art or Enter/Space also starts.
- Desktop and mobile opening layouts included.
- β3.3.5 party battle art and all existing gameplay retained.


β3.4.1 MOBILE BATTLE SYSTEM FIX
- Simplified battle background so animal silhouettes are easier to read.
- Added a light dedicated enemy stage and stronger enemy drop shadows.
- Field map, coordinate rails and field KAMADOYA are forcibly hidden during battle.
- Mobile battle layout rebalanced: larger enemy area and all four commands stay visible.
- Existing opening screen, party art, progression and rewards retained.


β3.4.2 MOBILE OK BUTTON FIX
- Slightly enlarged mobile OK/confirmation buttons for easier tapping.
- Desktop button sizing unchanged.
- β3.4.1 mobile battle fixes retained.
