# CORTNEYHELL.TV

## What This Is
A retro CRT TV-style website that plays Cortney Hale's YouTube videos (@cortneyhell) in shuffle mode inside a TV interface. Think 90s cable TV channel surfing experience.

## Live URL
https://mattmatheson.github.io/cortneyhell-tv/

## Repo
https://github.com/mattmatheson/cortneyhell-tv

## Tech
- Single index.html file, no build tools
- YouTube IFrame Player API (not raw iframes) for programmatic control
- GitHub Pages for hosting (deploys from `main` branch)
- v1.0 tag saved as the current working version

## Current Design (v1)
- Wood-grain CRT TV cabinet with black bezel
- Dark background with subtle pattern
- Knobs on the TV, remote-style buttons below
- Channel number overlay, now-playing bar on hover
- Shuffle mode on by default
- Categories: Music Videos, Live Sets, All
- 46 videos total (20 music, 26 live)

## Mobile/iOS Notes
- iOS blocks all YouTube autoplay (Apple WebKit restriction, affects ALL iOS browsers including Chrome)
- Solution: "TAP TO TUNE IN" play overlay appears on iOS, one tap starts playback
- Desktop/Android: muted autoplay works automatically

## Design Direction for v2 (TBD)
- Matt wants a 90s bedroom scene: wallpaper, hardwood floor, posters, silver Sony-style CRT on a stand with SNES underneath, messy grunge vibes
- v2 attempt was deleted — needs more work
- Key: keep the YouTube player functional, design is the wrapper around it

## Who Is Cortney Hale
- Matt's creative collaborator, does filming/production
- Her YouTube: https://youtube.com/@cortneyhell
- Her Instagram: https://instagram.com/cortneyhell
- Also in a band called METER (@meter.exe on Instagram) — Linkin Park/Evanescence vibes
- Separate hype page built at https://mattmatheson.github.io/meter-hype-page/

## Video Categories
- **Music videos:** Original music videos and official videos she filmed for Nashville bands
- **Live sets:** Full set recordings from Nashville venues (Arcane Workshop, The End, Tempo, drkmttr, Vinyl Lounge, etc.)
- All shot on camcorders, gritty aesthetic
