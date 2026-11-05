# Hellfire Gas — source + texture pack

Target: Minecraft Fabric 26.1.2, Java 25, Fabric Loader 0.19.5.

## Included assets
- 128×128 pixel-art Hellfire fruit texture
- Green hellfire particle textures (flame, ember, ring)
- Four-frame green aura sprite sheet
- Five 64×64 skill icons (Z, X, C, V, F)
- Item model, item definition, particle JSON, Indonesian and English language files

## Current implementation status
The source retains the known fruit activation and client-side orbiting flame aura behavior.
The resource textures are included as actual PNG files in the correct assets paths.
This package is a source foundation, not a claim that the complete Blox-Fruits-style system is finished:
M1 combo, keyboard skill networking, mastery persistence, energy HUD, full player-model transformation,
and multiplayer skill synchronization still require implementation and in-game validation.

## Build
Run `gradle build` with Java 25 and network access to the Fabric/Minecraft repositories.
If the 26.1.2 mappings/API have changed, use the first compiler error as the exact next correction.
