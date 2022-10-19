Cda's Copper Add-on brings blocks from the 20w45a snapshot over to Bedrock Edition

You must enable "Holiday Creator Features" and "Creation of Custom Biomes" in the experimental gameplay for the pack to work

IDs/PNGs explained:
ci - Copper Ingot
cb - Copper Block
cc - Cut Copper
co - Copper Ore
lwcb - Lightly Weathered Copper Block
lwcc - Lightly Weathered Cut Copper
swcb - Semi-Weathered Copper Block
swcc - Semi-Weathered Cut Copper
wcb - Weathered Copper Block
wcc - Weathered Cut Copper
("w" after id - Waxed)
("sl" after id - Slab)
("st" after id - Stair)
("w" will be found before "sl" or "st")
("d" before id - Double)
(If is a waxed regular block, there is no "b")
("u" at the end - Upper, only stairs and slabs)
("n/e/s/w", north, east, south, west, found before "u", only for stairs)

Known Issues:
- Stair textures are off
- Way too many block files
	The stairs require 8 blocks per a single block, and the slabs require 2. There is currently no way to hide blocks from the /give menu
- Stair collision is a solid block
	There is currently no way for non-rectangular hitboxes
- Mining does not use durability
- Anything will mine the block in a second
	Mining without the proper tools will still result in it not dropping, but everything will mine it in a second. Better tools cannot mine it in less
- Pick block doesn't work for some stairs/slabs
	As each stair and slab need multiple blocks, the pick block will only work for certain varients, eg, north facing stair, lower slab
- Shadows
	Appears to be much better after 1.16.200

Do not redistribute. Link all pack downloads back to https://sites.google.com/view/cda94581/downloads/packs/behavior-packsaddons

Changelog
v1.0.1 - 12/11/2020 (MM/DD/YYYY)
Updated with new 1.16.200 features to be a bit more optimized
Updated manifest descriptions with a bit more branding
Distributed as Cda's Copper v1.0.1
---
v1.0.0 - 11/24/2020 (MM/DD/YYYY)
Added Cut Copper Stairs and weathered variants
	Stair textures are currently off a bit
Added Cut Copper Slabs and weathered variants
Distributed as Cda's Copper v1.0.0
---
v0.0.3 - 11/12/2020 (MM/DD/YYYY)
Updated changelog format to include date, added credits
Copper Ingot texture will now load
Distributed as Cda's Copper v0.0.3
---
v0.0.2 - 11/11/2020 (MM/DD/YYYY)
Updated to coincide with the Java Edition 20w46a snapshot
Changed the crafting recipe of the Copper Block to coincide with the Java Edition 20w46a snapshot
Changed the textures of Cut Copper, and the Copper Ingot Item to coincide with the Java Edition 20w46a snapshot
	Ingot one is irrelevant if it cannot load
Added support for people using the English (UK) language
Distributed as Cda's Copper v0.0.2
---
v0.0.1 - 11/10/2020 (MM/DD/YYYY)
Added Copper Ore
Added Copper Ore Generation
Added Copper Ingot
Added Copper Block
Added Copper Block Weathered Variants
Added Waxed Copper Block and Variants
Added Cut Copper
Added Cut Copper Weathered Variants
Added Waxed Cut Copper and Variants
Added recipes
Added extra files for the purpose of future updates
Distributed as Cda's Copper v0.0.1

Credits:
Thanks to https://bedrock.dev for its documentation on add-on making
Thanks to Exploration Craft (https://mcpedl.com/exploration-craft-addon/) and Concrete Slabs (https://mcpedl.com/concrete-slabs-addon/) for providing examples and pre-made block models so as to complete the pack
Thanks to the bedrock.dev Discord for the help and knowledge provided in making this add-on