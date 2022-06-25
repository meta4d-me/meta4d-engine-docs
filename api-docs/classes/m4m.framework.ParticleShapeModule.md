[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleShapeModule

# Class: ParticleShapeModule

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleShapeModule

Shape of the emitter volume, which controls where particles are emitted and their initial direction.
发射体体积的形状，它控制粒子发射的位置和初始方向。

**`author`** feng3d

## Hierarchy

- [`ParticleModule`](m4m.framework.ParticleModule.md)

  ↳ **`ParticleShapeModule`**

## Table of contents

### Properties

- [\_\_class\_\_](m4m.framework.ParticleShapeModule.md#__class__)
- [activeShape](m4m.framework.ParticleShapeModule.md#activeshape)
- [alignToDirection](m4m.framework.ParticleShapeModule.md#aligntodirection)
- [angle](m4m.framework.ParticleShapeModule.md#angle)
- [arc](m4m.framework.ParticleShapeModule.md#arc)
- [arcMode](m4m.framework.ParticleShapeModule.md#arcmode)
- [arcSpeed](m4m.framework.ParticleShapeModule.md#arcspeed)
- [arcSpread](m4m.framework.ParticleShapeModule.md#arcspread)
- [box](m4m.framework.ParticleShapeModule.md#box)
- [enabled](m4m.framework.ParticleShapeModule.md#enabled)
- [length](m4m.framework.ParticleShapeModule.md#length)
- [mesh](m4m.framework.ParticleShapeModule.md#mesh)
- [meshMaterialIndex](m4m.framework.ParticleShapeModule.md#meshmaterialindex)
- [meshRenderer](m4m.framework.ParticleShapeModule.md#meshrenderer)
- [meshScale](m4m.framework.ParticleShapeModule.md#meshscale)
- [meshShapeType](m4m.framework.ParticleShapeModule.md#meshshapetype)
- [normalOffset](m4m.framework.ParticleShapeModule.md#normaloffset)
- [particleSystem](m4m.framework.ParticleShapeModule.md#particlesystem)
- [radius](m4m.framework.ParticleShapeModule.md#radius)
- [radiusMode](m4m.framework.ParticleShapeModule.md#radiusmode)
- [radiusSpeed](m4m.framework.ParticleShapeModule.md#radiusspeed)
- [radiusSpread](m4m.framework.ParticleShapeModule.md#radiusspread)
- [randomDirectionAmount](m4m.framework.ParticleShapeModule.md#randomdirectionamount)
- [skinnedMeshRenderer](m4m.framework.ParticleShapeModule.md#skinnedmeshrenderer)
- [sphericalDirectionAmount](m4m.framework.ParticleShapeModule.md#sphericaldirectionamount)
- [useMeshColors](m4m.framework.ParticleShapeModule.md#usemeshcolors)
- [useMeshMaterialIndex](m4m.framework.ParticleShapeModule.md#usemeshmaterialindex)

### Accessors

- [arcSpeedMultiplier](m4m.framework.ParticleShapeModule.md#arcspeedmultiplier)
- [radiusSpeedMultiplier](m4m.framework.ParticleShapeModule.md#radiusspeedmultiplier)
- [shape](m4m.framework.ParticleShapeModule.md#shape)
- [shapeType](m4m.framework.ParticleShapeModule.md#shapetype)

### Constructors

- [constructor](m4m.framework.ParticleShapeModule.md#constructor)

### Methods

- [initParticleState](m4m.framework.ParticleShapeModule.md#initparticlestate)
- [updateParticleState](m4m.framework.ParticleShapeModule.md#updateparticlestate)

## Properties

### \_\_class\_\_

• **\_\_class\_\_**: ``"m4m.framework.ParticleShapeModule"``

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L11)

___

### activeShape

• **activeShape**: [`ParticleSystemShapeBase`](m4m.framework.ParticleSystemShapeBase.md)

当前使用的发射形状

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L48)

___

### alignToDirection

• **alignToDirection**: `boolean` = `false`

Align particles based on their initial direction of travel.
根据粒子的初始运动方向排列粒子。

Using align to Direction in the Shape module forces the system to be rendered using Local Billboard Alignment.
在形状模块中使用align to Direction迫使系统使用本地看板对齐方式呈现。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L58)

___

### angle

• **angle**: `number` = `25`

Angle of the cone.

圆锥的角度。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L80)

___

### arc

• **arc**: `number` = `360`

Circle arc angle.

圆弧角。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L88)

___

### arcMode

• **arcMode**: [`ParticleSystemShapeMultiModeValue`](../enums/m4m.framework.ParticleSystemShapeMultiModeValue.md) = `ParticleSystemShapeMultiModeValue.Random`

The mode used for generating particles around the arc.

在弧线周围产生粒子的模式。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:96](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L96)

___

### arcSpeed

• **arcSpeed**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

When using one of the animated modes, how quickly to move the emission position around the arc.

当使用一个动画模式时，如何快速移动发射位置周围的弧。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:104](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L104)

___

### arcSpread

• **arcSpread**: `number` = `0`

Control the gap between emission points around the arc.

控制弧线周围发射点之间的间隙。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:127](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L127)

___

### box

• **box**: `vector3`

Scale of the box.

盒子的缩放。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:135](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L135)

___

### enabled

• **enabled**: `boolean` = `false`

是否开启

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[enabled](m4m.framework.ParticleModule.md#enabled)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L14)

___

### length

• **length**: `number` = `5`

Length of the cone.

圆锥的长度（高度）。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:143](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L143)

___

### mesh

• **mesh**: `any`

Mesh to emit particles from.

发射粒子的网格。

**`todo`**

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:152](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L152)

___

### meshMaterialIndex

• **meshMaterialIndex**: `number`

Emit particles from a single material of a mesh.

从一个网格的单一材料发射粒子。

**`todo`**

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:170](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L170)

___

### meshRenderer

• **meshRenderer**: `any`

MeshRenderer to emit particles from.

从 MeshRenderer 发射粒子。

**`todo`**

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:180](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L180)

___

### meshScale

• **meshScale**: `number` = `1`

Apply a scaling factor to the mesh used for generating source positions.

对用于生成源位置的网格应用缩放因子。

**`todo`**

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:198](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L198)

___

### meshShapeType

• **meshShapeType**: [`ParticleSystemMeshShapeType`](../enums/m4m.framework.ParticleSystemMeshShapeType.md) = `ParticleSystemMeshShapeType.Vertex`

Where on the mesh to emit particles from.

从网格的什么地方发射粒子。

**`todo`**

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:207](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L207)

___

### normalOffset

• **normalOffset**: `number` = `0`

Move particles away from the surface of the source mesh.

将粒子从源网格的表面移开。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:223](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L223)

___

### particleSystem

• **particleSystem**: [`ParticleSystem`](m4m.framework.ParticleSystem.md)

粒子系统

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[particleSystem](m4m.framework.ParticleModule.md#particlesystem)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L19)

___

### radius

• **radius**: `number` = `1`

Radius of the shape.

形状的半径。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:231](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L231)

___

### radiusMode

• **radiusMode**: [`ParticleSystemShapeMultiModeValue`](../enums/m4m.framework.ParticleSystemShapeMultiModeValue.md) = `ParticleSystemShapeMultiModeValue.Random`

The mode used for generating particles around the radius.

在弧线周围产生粒子的模式。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:239](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L239)

___

### radiusSpeed

• **radiusSpeed**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

When using one of the animated modes, how quickly to move the emission position along the radius.

当使用一个动画模式时，如何快速移动发射位置周围的弧。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:247](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L247)

___

### radiusSpread

• **radiusSpread**: `number` = `0`

Control the gap between emission points around the radius.

控制弧线周围发射点之间的间隙。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:270](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L270)

___

### randomDirectionAmount

• **randomDirectionAmount**: `number` = `0`

Randomizes the starting direction of particles.
随机化粒子的起始方向。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L65)

___

### skinnedMeshRenderer

• **skinnedMeshRenderer**: `any`

SkinnedMeshRenderer to emit particles from.

从 SkinnedMeshRenderer 发射粒子。

**`todo`**

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:189](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L189)

___

### sphericalDirectionAmount

• **sphericalDirectionAmount**: `number` = `0`

Spherizes the starting direction of particles.
使粒子的起始方向球面化。

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L72)

___

### useMeshColors

• **useMeshColors**: `boolean` = `true`

Modulate the particle colors with the vertex colors, or the material color if no vertex colors exist.

用顶点颜色调节粒子颜色，如果没有顶点颜色，则调节材质颜色。

**`todo`**

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:216](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L216)

___

### useMeshMaterialIndex

• **useMeshMaterialIndex**: `boolean`

Emit from a single material, or the whole mesh.

从一个单一的材料，或整个网格发射。

**`todo`**

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:161](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L161)

## Accessors

### arcSpeedMultiplier

• `get` **arcSpeedMultiplier**(): `number`

A multiplier of the arc speed of the emission shape.

发射形状的电弧速度的乘数。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:111](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L111)

• `set` **arcSpeedMultiplier**(`v`): `void`

A multiplier of the arc speed of the emission shape.

发射形状的电弧速度的乘数。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L116)

___

### radiusSpeedMultiplier

• `get` **radiusSpeedMultiplier**(): `number`

A multiplier of the radius speed of the emission shape.

发射形状的半径速度的乘法器。

#### Returns

`number`

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:254](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L254)

• `set` **radiusSpeedMultiplier**(`v`): `void`

A multiplier of the radius speed of the emission shape.

发射形状的半径速度的乘法器。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:259](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L259)

___

### shape

• `get` **shape**(): [`ParticleSystemShapeType1`](../enums/m4m.framework.ParticleSystemShapeType1.md)

Type of shape to emit particles from.
发射粒子的形状类型。

#### Returns

[`ParticleSystemShapeType1`](../enums/m4m.framework.ParticleSystemShapeType1.md)

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L33)

• `set` **shape**(`v`): `void`

Type of shape to emit particles from.
发射粒子的形状类型。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`ParticleSystemShapeType1`](../enums/m4m.framework.ParticleSystemShapeType1.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L37)

___

### shapeType

• `get` **shapeType**(): [`ParticleSystemShapeType`](../enums/m4m.framework.ParticleSystemShapeType.md)

Type of shape to emit particles from.
发射粒子的形状类型。

#### Returns

[`ParticleSystemShapeType`](../enums/m4m.framework.ParticleSystemShapeType.md)

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L17)

• `set` **shapeType**(`v`): `void`

Type of shape to emit particles from.
发射粒子的形状类型。

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`ParticleSystemShapeType`](../enums/m4m.framework.ParticleSystemShapeType.md) |

#### Returns

`void`

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L21)

## Constructors

### constructor

• **new ParticleShapeModule**()

#### Overrides

[ParticleModule](m4m.framework.ParticleModule.md).[constructor](m4m.framework.ParticleModule.md#constructor)

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:279](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L279)

## Methods

### initParticleState

▸ **initParticleState**(`particle`): `void`

初始化粒子状态

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) | 粒子 |

#### Returns

`void`

#### Overrides

[ParticleModule](m4m.framework.ParticleModule.md).[initParticleState](m4m.framework.ParticleModule.md#initparticlestate)

#### Defined in

[framework/particlesystem/modules/ParticleShapeModule.ts:289](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleShapeModule.ts#L289)

___

### updateParticleState

▸ **updateParticleState**(`particle`): `void`

更新粒子状态

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) | 粒子 |

#### Returns

`void`

#### Inherited from

[ParticleModule](m4m.framework.ParticleModule.md).[updateParticleState](m4m.framework.ParticleModule.md#updateparticlestate)

#### Defined in

[framework/particlesystem/modules/ParticleModule.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/modules/ParticleModule.ts#L34)
