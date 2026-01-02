# HEXAGONA v1.0.0

## Parameters

### Board Settings

- **Board Size:** Defines the size of the board. Caution when using large numbers.
- **Tile Type:** There are four tile types to choose from. A standard hexagon, a slightly beveled hexagon, a round hexagon, and a chiseled hexagon.
- **Tile Size:** There are three tile sizes to choose from.
- **Flat Board:** Flattens the tiles of the board.

### Landscape Settings

- **Landscape Scale:** Drives the scale of the landscape based on a noise pattern. Height Scale:** Multiplies the height of the board tiles.
- **Horizontal Offset:** Drives the horizontal offset of the landscape based on a noise pattern.
- **Vertical Offset:** Drives the vertical offset of the landscape based on a noise pattern.
- **Flat Sea:** Removes the individual tiles of the sea, and flattens it into a seamless unified mesh. Use with caution, as it generates a mesh with a higher polycount.
- **Sea Level:** Drives the height level of the sea.
- **Sea Offset:** Drives the sea level offset from the ground tiles.

### Color Settings

- **Color Palette:** There are six color palettes to choose from. Each palette colors the board and changes the foliage stylization based on the Foliage Type.

#### Board Colors / Sea Colors

- **Min Position:** Sets the minimum height position the color palette is applied to.
- **Min Value:** Sets the minimum color value of the color ramp that is applied.
- **Max Position:** Sets the maximum height position the color palette is applied to.
- **Max Value:** Sets the maximum color value of the color ramp that is applied.

### Set Dressing

#### Foliage Settings / Rocks Settings

- **Use Foliage (only in Foliage Settings):** Enables the generation of foliage.
- **Use Rocks (only in Rocks Settings):** Enables the generation of rocks.
- **Foliage Type (only in Foliage Settings):** There are three foliage types to choose from and generate. There are mesh variations that depend on the Color Palette.
- **Minimum Scale:** Drives the minimum scale of the mesh that is generated.
- **Maximum Scale:** Drives the maximum scale of the mesh that is generated.
- **Height Range Min:** Sets the minimum position of the height range where the meshes are being generated.
- **Height Range Max:** Sets the maximum position of the height range where the meshes are being generated.
- **Density Scale:** Drives the density of the generated meshes. Use with caution.
- **Relax Iterations:** Drives the relax value of the generated meshes. Lower values create non-uniform scattering while higher values create more uniform scattering.
- **Use Noise Scatter:** Enable this toggle to drive the scatter from a noise instead of a uniform way.
- **Frequency:** The scale of the noise. Lower values create more large scaled scattering while higher values create more dense scattering.
- **Horizontal Offset:** Drives the horizontal offset of the scatter.
- **Vertical Offset:** Drives the vertical offset of the scatter.
- **Amplitude:** Drives the density of the noise.

### Utilities

- **Tile High Quality:** Enable this toggle to bevel and smooth the set dressing assets. Use with caution as it can slow down the performance.
- **Set Dressing High Quality:** Enable this toggle to bevel and smooth the set dressing assets. Use with caution as it can slow down the performance.
- **Generate UVs:** Enable this toggle to generate uv for all the elements. Use with caution as it can slow down the performance.
- **Layout Tile UVs:** Enable this toggle to layout the uv sets from the top polygons of the tiles. This allows you to apply textures in a more uniform way. Use with caution as it can slow down the performance.

### Custom Settings

#### Custom Maps

- **Use Custom Height Map:** Enable this to use a custom height map.
- **Heightmap Image:** Assign an image to use as a heightmap.
- **Use Custom Color Map:** Enable this to use a custom color map.
- **Colormap Image:** Assign an image to use as a colormap.

#### Custom Colors: Board Colors

- **Use Custom Board Colors:** Enable this to use custom colors for the board.
- **Use Custom Base Colors:** Enable this to use custom colors for the base.
- **Board Colors:** Assign custom colors for the board. The colors are applied in a ramp manner, from bottom totop, based on the height range of the board.
- **Board Base Color:** Assign a custom color for the base.

#### Custom Colors: Sea Colors

- **Use Custom Sea Colors:** Enable this to use custom colors for the sea.
- **Sea Colors:** Assign custom colors for the board. The colors are applied in a ramp manner, from deep to shallow, based on the height range of the board.

#### Custom Colors: Set Dress Colors

- **Use Custom Foliage Colors:** Enable this to use custom colors for the foliage.
- **Foliage Colors:** Assign custom colors for the foliage. The colors are applied in a ramp manner, from low to high, based on the height of the foliage.
- **Trunk Colors:** Assign custom colors for the trunk. The colors are applied in a ramp manner, from low to high, based on the height of the trunk.
- **Use Custom Rocks Colors:** Enable this to use custom colors for the rocks.
- **Rock Colors:** Assign custom colors for the rocks. The colors are applied in a ramp manner, from low to high, based on the height of the rock.

#### Custom Set Dressing

- **Use Custom Mesh (Foliage/Rocks):** Enable this to use a custom mesh.
- **Custom Mesh (Foliage/Rocks):** Assign a mesh to use for foliage/rocks.
- **Scale (Foliage/Rocks):** Scales the imported mesh within a range of 0.1 to 10.