### 3.6.1
- Removed the assymetric corner pixel in regular arrow cursors (`arrow`, `help` and `working`)
- Fixed some visual inconsitencies in the `working_tail_detached` cursor
- Renamed some cursors for better clarity: 
    -- `vertical_line` to `vertical_v2`
    -- `horizontal_line` to `horizontal_v2`
    -- `move_alt` to `move_v2`

### 3.6.0

Added new "tail detached" cursors (design proposed by **_aicraglednay**): 
- `arrow_tail_detached` <br> <img src="./screenshots/cursors_single/arrow_tail_detached.png">
- `working_tail_detached` <br> <img src="./screenshots/cursors_single/working_tail_detached.gif">
- `working_tail_detached_v2` <br> <img src="./screenshots/cursors_single/working_tail_detached_v2.gif">

Added another new cursor:  
- `unavailable_v3` <br> <img src="./screenshots/cursors_single/unavailable_v3.png">

New table with all available cursors is available in the [Showcase](https://github.com/emvaized/modern_inverted_mouse_cursors?tab=readme-ov-file#showcase)!

### 3.5
- Added new fancy loading cursors (`busy` and 2 `working` variants) — only 32px versions for now. Original loading cursors (with clock) moved to the "old" folder
- All cursors were converted to 1-bit color depth for better compatibility with apps. They also weight much less now (~2kbs instead of ~22kbs per cursor)
- Updated `beam` cursor for slightly sharper tips
- Updated `unavailable_v2` cursor — it's now centered and a little bit bolder
- All move/resize cursors received slightly rounded tips
- Removed original `link` cursor — `link_v2` now became the new `link`, and `link_v3` became `link_v2`
- Swapped `diagonal_1` and `diagonal_2` cursors to be consistent with their naming in the Control panel

### 3.0
- Added new cursors:
    -- `unavailable_v2` (default now)
    -- `pen`
    -- `special`
    -- `help_no_tail`
    -- `link_v3` with sharper bottom-right corner (default in "no-tail" theme)

- Updated `beam` cursor for slightly sharper tips
- Updated `move` and all "resize" cursors to have consistent center dot size
- Renamed "no_tail" to "no_tail_smaller", and "no_tail_v2" cursors to just "no_tail" (default in "no-tail" theme)
- Added 2 `install.inf` installers (for regular and no-tail themes)

### 2.0
- `busy` cursor now has slightly bolder outline in smaller sizes
- added `link_v2` cursor - it has a slightly more refined shape and no finger lines on top
- `arrow_no_tail_bigger` replaced with `arrow_no_tail_v2`. It has slightly more rounded corners and bolder outline compared to regular cursor 

### 1.0
Initial release
