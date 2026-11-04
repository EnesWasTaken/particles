# CS2 Weather & Visual Assets

Compiled CS2 assets used by the Fatality Lua script `custom_skybox.lua`.

## assets/v1/

Base64 text copies of the files the script downloads automatically on first use (no manual install needed):

- `particles/custom_weather/*.vpcf_c.b64`: weather (rain, snow, stars with light/heavy variants), bullet impact sparks, kill effects.
  The script writes them to `csgo\particles\custom_weather\`.
- `hud/js/*.js.b64`, `hud/png/*.png.b64`: CS:GO style HUD scripts and plates.
- `sounds/nsfw.mp3.b64`: sound played when an NSFW skybox is picked.

The script pins every file by size and SHA-256 of the decoded bytes and never writes a file that does not match.
Do not change files inside `v1/`; new versions go into a new folder (`v2/`) together with a new script build.

Skyboxes are not hosted here: everybody installs their own.

## custom_weather/, embedded/, emotes/

Older raw copies kept for reference. The script no longer reads them.
