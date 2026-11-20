# The Last Warden — integrated world

This build uses the supplied `the_last_warden_ascii_bestiary_world.html` as its world. Terrain, roads, water, village buildings, lairs, landmarks, minimap, and world map remain in the original coordinate system. The original wilderness demo background is no longer used.

## Run

Requires Node.js. In this folder, run `node server.js`, then open `http://127.0.0.1:4173/`. To use another port in PowerShell, set `$env:PORT=4174` before starting the server.

## Play

- WASD or arrow keys: move. Hold Shift to sprint or gallop.
- E: interact, mount or dismount the nearby horse, and open chests.
- Space: directional sword strike. R: radial knockback.
- Tab: landmark labels. M: world map. `?`: help. Use the SOUND button to toggle music.

The world clock starts when you enter Eldoria. Day lasts 30 seconds, followed by 30 seconds of night, repeating continuously. At night, a ring of goblins, spiders, and another hostile creature spawns around the Warden and chases. Other creatures patrol near their mapped lairs. Soldiers defend the village; attacks on villagers reduce village health. Day restores some village health, and defeated enemies return from their lairs with the next night. The Sentinel ally has been removed.

## Supplied art status

The supplied Soldier frames animate the Warden and village soldiers. The Hobgoblin ZIP supplies outlined goblins and the enlarged dragon demon boss, plus unoutlined art for the marsh demon. The supplied Spider Sprite Sheet animates giant spiders. The Horse Pack supplies eight horse variants placed across the map. The ship sheet supplies boats on the existing water. The Orc sheet is preserved in the source ZIP but is not used as a goblin substitute.

The three supplied audio files play locally: Secunda ambience by day, Skyrim theme at night, and Song of the Dragonborn near the dragon demon. Audio begins after entering the game and can be toggled off.

Horse Pack art: loota9, licensed CC BY 4.0 (attribution: [loota9](http://linktr.ee/loota9)). The three music files were supplied by the user for this local build.

No network requests or third-party libraries are required.
