[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / LineTextureMode

# Enumeration: LineTextureMode

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).LineTextureMode

Choose how textures are applied to Lines and Trails.

选择如何将纹理应用于线和迹线。

## Table of contents

### Enumeration Members

- [DistributePerSegment](m4m.framework.LineTextureMode.md#distributepersegment)
- [RepeatPerSegment](m4m.framework.LineTextureMode.md#repeatpersegment)
- [Stretch](m4m.framework.LineTextureMode.md#stretch)
- [Tile](m4m.framework.LineTextureMode.md#tile)

## Enumeration Members

### DistributePerSegment

• **DistributePerSegment**

Map the texture once along the entire length of the line, assuming all vertices are evenly spaced.

假设所有顶点均等分布，则沿着线的整个长度映射一次纹理。

#### Defined in

[framework/effects/enums/LineTextureMode.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/enums/LineTextureMode.ts#L29)

___

### RepeatPerSegment

• **RepeatPerSegment**

Repeat the texture along the line, repeating at a rate of once per line segment. To adjust the tiling rate, use Material.SetTextureScale.

沿线重复纹理，每个线段重复一次。要调整平铺率，请使用Material.SetTextureScale。

#### Defined in

[framework/effects/enums/LineTextureMode.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/enums/LineTextureMode.ts#L36)

___

### Stretch

• **Stretch**

Map the texture once along the entire length of the line.

沿线的整个长度映射一次纹理。

#### Defined in

[framework/effects/enums/LineTextureMode.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/enums/LineTextureMode.ts#L15)

___

### Tile

• **Tile**

Repeat the texture along the line, based on its length in world units. To set the tiling rate, use Material.SetTextureScale.

根据纹理的长度（以世界单位为单位），沿线重复纹理。要设置平铺率，请使用Material.SetTextureScale。

#### Defined in

[framework/effects/enums/LineTextureMode.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/enums/LineTextureMode.ts#L22)
