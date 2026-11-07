# ProceduralnoModeliranjeProjekt

A procedural, voxelized 3D environment inspired by Minecraft, created in **Houdini**.

## Project Overview

VoxelizedWorld focuses on generating a single voxel chunk that represents a vertical section of a world—from clouds and a surface landscape, through underground caves and rock formations, down to a bottom region filled with lava.

The chunk will be constructed primarily from cubic, voxel-like elements. Procedural modeling techniques will generate terrain, vegetation, clouds, cave systems, and underground features within a predefined volume.

A set of exposed parameters will allow different variations of the chunk to be generated without manually modifying its geometry.

## Objective

Develop a flexible procedural system that demonstrates how a complex voxel environment can be generated and customized using Houdini.

## Development Milestones

### Milestone 1 — Basic Voxel Terrain

Establish the basic voxel structure and the underlying procedural generation system.

The chunk will have predefined dimensions and consist of a surface layer and an underground rock layer, with an optional lava core at the bottom. Parameters will control the chunk dimensions and voxel size. Terrain height variation and layer thickness controls may also be introduced.

At this stage, the environment will remain relatively simple, without clouds, trees, or cave systems.

#### Minimum Requirements

- [ ] Generate a voxel chunk with predefined dimensions, a surface layer, and an underground rock layer.
- [ ] Implement parameters for chunk dimensions and voxel size.

#### Optional Requirements

- [ ] Add a bottom layer with a lava core.
- [ ] Implement procedural terrain height variation and parameters for terrain height and layer thickness.

### Milestone 2 — Procedural Environment Generation

Create a complete voxel chunk containing all major environmental features, controlled through exposed parameters.

Trees and clouds will be added above ground, while cave systems will be generated within the underground rock layers. Additional decorative elements, such as mineral deposits, may also be introduced.

Parameters will control the quantity, size, and distribution of these features, including tree count, tree size, cave dimensions, and cloud density.

#### Minimum Requirements

- [ ] Generate trees and clouds, along with at least one underground cave system.
- [ ] Implement parameters controlling the size, quantity, or distribution of generated features.

#### Optional Requirements

- [ ] Generate multiple caves and add variations in tree shapes and sizes.
- [ ] Add decorative underground features, such as mineral deposits or crystals.

### Milestone 3 — Biome Generation

Create a more diverse and visually interesting procedural environment that supports multiple biome types within a single voxel chunk.

The system will support a small selection of overworld biomes and cave sub-biomes inspired by Minecraft, with a maximum of two to three biomes in scope. Each biome will have distinct materials, colors, vegetation, environmental features, and procedural rules governing their distribution and appearance.

Possible biome types include:

- **Overworld biomes:** forests, plains, or snowy terrain.
- **Cave sub-biomes:** Lush Caves with moss, vegetation, and glowing plants; crystal-filled caves; or other unique underground environments.

A seed-based randomization system may also be implemented to generate different chunk variations while maintaining the same parameter settings.

#### Minimum Requirements

- [ ] Implement at least two distinct biomes, including an overworld biome and a cave sub-biome.
- [ ] Give each biome distinct visual characteristics and procedural generation rules.

#### Optional Requirements

- [ ] Implement a third biome and additional cave sub-biomes.
- [ ] Add seed-based randomization for generating different chunk variations.
