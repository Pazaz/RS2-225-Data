## Cache Source

This repo has been populated with data from May 18, 2004.

Each archive's original timestamps:
- `config.jag`: 5/18/2004
- `interface.jag`: 5/18/2004
- `media.jag`: 5/18/2004
- `models.jag`: 5/18/2004
- `sounds.jag`: 5/18/2004
- `textures.jag`: 5/10/2004
- `title.jag`: 12/1/2003
- `wordenc.jag`: 3/30/2004

## Folder Structure

`animations/` - Animation frames  
Added to `models.jag` as `frame_*.dat`

`floors/` - Floor tile definitions (textures/colors)  
Added to `config.jag` as `flo.dat`/`flo.idx`

`interfaces/` - Interface definitions  
Added to `interface.jag` as `data`

`locs/` - Location definitions (objects in the world)  
Added to `config.jag` as `loc.dat`/`loc.idx` (Location)

`media/` - Interface sprites  
Added to `media.jag`

`models/` - 3D models  
Added to `models.jag` as `ob_*.dat`  
There is a model-names.json file in this folder that serves as a name lookup between ID <-> internal name because there are no definition files in this folder.

`npcs/` - NPC definitions  
Added to `config.jag` as `npc.dat`/`npc.idx`

`objs/` - Item definitions  
Added to `config.jag` as `obj.dat`/`obj.idx` (Object)

`players/` - Player model definitions  
Added to `config.jag` as `idk.dat`/`idk.idx` (IdentityKit)

`seqs/` - Animation definitions  
Added to `config.jag` as `seq.dat`/`seq.idx` (Sequence)

`skeletons/` - Animation skeletons  
Added to `models.jag` as `base_*.dat`

`sounds/` - Synth sound effects  
Added to `sounds.jag` as `sounds.dat`  
There is a sounds-names.json file in this folder that serves as a name lookup between ID <-> internal name because there are no definition files in this folder.

`spotanims/` - Graphics definitions (i.e. projectiles)  
Added to `config.jag` as `spotanim.dat`/`spotanim.idx` (Spot Animation)

`textures/` - Textures for 3D models/floor overlays  
Added to `textures.jag`

`title/` - Title screen sprites/images, fonts for game  
Added to `title.jag`

`varps/` - Variable parameter definitions used within interfaces  
Added to `config.jag` as `varp.dat`/`varp.idx`

`wordenc/` - Word filtering definitions, applied when encoding chat messages  
Added to `wordenc.jag`

## TODO

1) Convert fonts to a character atlas
2) Extract wordenc definitions
3) Give names to any files that are still identified by ID
