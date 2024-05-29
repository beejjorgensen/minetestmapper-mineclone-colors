# MineClone2 for Minetest-Mapper

A `colors.txt` for
[minetest-mapper](https://github.com/mireq/minetest-mapper-cpp) to work
with [VoxeLibre (formerly
MineClone2)](https://content.minetest.net/packages/Wuzzy/mineclone2/).

If you find missing symbols (I've only mapped what I've seen), let me
know what they are in a bug report and I'll add them. You don't have to
supply the color values unless you want to—I can get those.

## Usage

Replace the `-i` path with the path your map file.

```
minetestmapper \
    -i ~/.minetest/worlds/MAPFILE \
    -o mcmap.png \
    --colors colors.mineclone.txt
```
