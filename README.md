# TIDAL Nightfall

A minimalist, true-black theme for TIDAL via TidaLuna, featuring sharp edges, sunset accents and customizable player animations.
Made for AMOLED screens: black stays black, colour only shows up where it matters.


## Features

- **True black** surfaces everywhere, no frosted glass, no cover-coloured page backgrounds
- **Square, clean design** without rounded boxes
- **Sunset fullscreen view**: a black night sky with a warm glow on the horizon
- **Animated progress bar** with seven styles to choose from
- **Search in the sidebar** with a spotlight that dims the rest of the app while results are open
- **Docked player** across the full window width with a clear seek line
- **Midnight-blue hover** in menus, lists and on cover buttons instead of TIDAL's grey
- **Thin outlines** on context menus (sunset gradient) and on the Luna settings groups


## Installation

Requires [TidaLuna](https://github.com/Inrixia/TidaLuna) and the TIDAL desktop app (not the Microsoft Store version).

1. Open TIDAL, click the profile icon and choose **Luna settings**.
2. Go to the **Themes** tab and paste this URL:

   ```
   https://raw.githubusercontent.com/mathisschaefer2000/Tidal-Nightfall/main/tidal-nightfall.css
   ```

This link always loads the latest version. To stay on a fixed version, replace `main` with a version tag, for example `v1.0.0`.

## Choosing an animation

The default animation is `notes`. To use another one, install the **Themer** plugin by Nick Oates from the Plugin Store in Luna settings. Open its CSS editor and add this line, replacing `moon` with the name you want:

```css
:root { --theme-progress-effect: moon !important; }
```

## Available progress bar animations

| Name | What you see |
| --- | --- |
| `notes` (default) | Music notes rise from the playhead, sway from side to side and fade out at the top. Two streams run at different speeds: eighth notes and beamed notes. The notes take the colours of the sunset: amber at the bottom, rose in the middle, indigo at the top. |
| `tide` | A wave rolls along the edge of the played part. A bright crest line runs in front, a fainter ripple moves the other way behind it. |
| `stardust` | Small stars light up and fade out one by one behind the playhead. They are densest right at the playhead and thin out further back. |
| `moon` | A little moon with craters and an eye sits at the playhead and keeps opening and closing its mouth. A row of dots glides into the mouth, one dot per bite. |
| `aurora` | Soft northern lights in rose, amber and lavender drift across the played part. Two blurred bands move in opposite directions and slowly change shape. |
| `bubbles` | Bubbles of different sizes rise through the played part. Each one is a ring with a small highlight; two layers move at different speeds. |
| `none` | No animation: a plain tinted fill with a thin line at the playhead. |


## Compatibility

TIDAL changes its layout from time to time. If something looks off after a TIDAL update, please [open an issue](../../issues).