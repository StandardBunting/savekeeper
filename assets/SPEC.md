# Assets to create for savekeeper

## logo.png вЂ” 256x256, transparent, dark theme
💾 Neon shield/gear motif matching $savekeeper$ brand color. See master prompt in _shared docs.

## banner.png вЂ” 1280x640, background #0d1117
Large bold title $savekeeper$, subtitle gray #8b949e, thin gradient line #00ff9dв†’#bc8cff.

## screenshots/main.png вЂ” 1280x800
Game list with backup status badges and last-snapshot time

## screenshots/settings.png вЂ” 1280x800
Backup settings — destination picker, schedule, retention

## screenshots/results.png вЂ” 1280x800
Restore wizard — snapshot timeline with size and game icon

## gifs/demo.gif вЂ” 800x500, 8s, 12fps, <8MB
1. Open app, 2. click main action, 3. status turns green, 4. toggle a feature, 5. return.
ffmpeg: -vf "fps=12,scale=800:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse"