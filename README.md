# pixel-art-spritesheet-sandbox

Simple web game tool for testing spritesheet animations. Uses Phaser. Made mostly with the help of an LLM (GLM 4.7), so expect messy code.

## How to Use

Upload a 512x512 spritesheet generated from TODO, and the tool will downscale it to 128x128, try to remove the background, and then add the spritesheet to a list.

Then you can select a spritesheet and click Spawn to spawn a character from that spritesheet.

Character controls are at the bottom of the page. You can cycle through characters with the Prev and Next buttons, indicated by a yellow marker.

## Credits
- k-centroid downscale algorithm originally from https://github.com/M4cs/comfyui-workflows/blob/master/custom_nodes/k_centroid_downscale.py
- [Phaser](https://github.com/phaserjs/phaser) framework
