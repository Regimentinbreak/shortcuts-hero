# Assets to create for shortcuts-hero

## logo.png вЂ” 256x256, transparent, dark theme
🧭 Neon shield/gear motif matching $shortcuts-hero$ brand color. See master prompt in _shared docs.

## banner.png вЂ” 1280x640, background #0d1117
Large bold title $shortcuts-hero$, subtitle gray #8b949e, thin gradient line #00ff9dв†’#bc8cff.

## screenshots/main.png вЂ” 1280x800
Remap editor — keyboard diagram with drag-drop bindings

## screenshots/settings.png вЂ” 1280x800
Cheatsheet overlay — per-app shortcut list on screen

## screenshots/results.png вЂ” 1280x800
Text expansion settings — abbreviations table

## gifs/demo.gif вЂ” 800x500, 8s, 12fps, <8MB
1. Open app, 2. click main action, 3. status turns green, 4. toggle a feature, 5. return.
ffmpeg: -vf "fps=12,scale=800:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse"