# m4m.framework.ParticleSystemShapeEdge

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystemShapeEdge

## Class: ParticleSystemShapeEdge

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystemShapeEdge

粒子系统 发射边

**`author`** feng3d

### Hierarchy

*   [`ParticleSystemShapeBase`](m4m.framework.ParticleSystemShapeBase.md)

    ↳ **`ParticleSystemShapeEdge`**

### Table of contents

#### Properties

* [\_module](m4m.framework.ParticleSystemShapeEdge.md#\_module)

#### Methods

* [calcParticlePosDir](m4m.framework.ParticleSystemShapeEdge.md#calcparticleposdir)

#### Constructors

* [constructor](m4m.framework.ParticleSystemShapeEdge.md#constructor)

#### Accessors

* [radius](m4m.framework.ParticleSystemShapeEdge.md#radius)
* [radiusMode](m4m.framework.ParticleSystemShapeEdge.md#radiusmode)
* [radiusSpeed](m4m.framework.ParticleSystemShapeEdge.md#radiusspeed)
* [radiusSpread](m4m.framework.ParticleSystemShapeEdge.md#radiusspread)

### Properties

#### \_module

• `Protected` **\_module**: [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md)

**Inherited from**

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[\_module](m4m.framework.ParticleSystemShapeBase.md#\_module)

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L10)

### Methods

#### calcParticlePosDir

▸ **calcParticlePosDir**(`particle`, `position`, `dir`): `void`

计算粒子的发射位置与方向

**Parameters**

| Name       | Type                                      |
| ---------- | ----------------------------------------- |
| `particle` | [`Particle1`](m4m.framework.Particle1.md) |
| `position` | `vector3`                                 |
| `dir`      | `vector3`                                 |

**Returns**

`void`

**Overrides**

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[calcParticlePosDir](m4m.framework.ParticleSystemShapeBase.md#calcparticleposdir)

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeEdge.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeEdge.ts#L75)

### Constructors

#### constructor

• **new ParticleSystemShapeEdge**(`module`)

**Parameters**

| Name     | Type                                                          |
| -------- | ------------------------------------------------------------- |
| `module` | [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md) |

**Inherited from**

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[constructor](m4m.framework.ParticleSystemShapeBase.md#constructor)

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L12)

### Accessors

#### radius

• `get` **radius**(): `number`

边长的一半。

**Returns**

`number`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeEdge.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeEdge.ts#L13)

• `set` **radius**(`v`): `void`

边长的一半。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeEdge.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeEdge.ts#L18)

***

#### radiusMode

• `get` **radiusMode**(): [`ParticleSystemShapeMultiModeValue`](../enums/m4m.framework.ParticleSystemShapeMultiModeValue.md)

The mode used for generating particles around the radius.

在弧线周围产生粒子的模式。

**Returns**

[`ParticleSystemShapeMultiModeValue`](../enums/m4m.framework.ParticleSystemShapeMultiModeValue.md)

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeEdge.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeEdge.ts#L28)

• `set` **radiusMode**(`v`): `void`

The mode used for generating particles around the radius.

在弧线周围产生粒子的模式。

**Parameters**

| Name | Type                                                                                               |
| ---- | -------------------------------------------------------------------------------------------------- |
| `v`  | [`ParticleSystemShapeMultiModeValue`](../enums/m4m.framework.ParticleSystemShapeMultiModeValue.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeEdge.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeEdge.ts#L33)

***

#### radiusSpeed

• `get` **radiusSpeed**(): [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

When using one of the animated modes, how quickly to move the emission position around the radius.

当使用一个动画模式时，如何快速移动发射位置周围的弧。

**Returns**

[`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeEdge.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeEdge.ts#L58)

• `set` **radiusSpeed**(`v`): `void`

When using one of the animated modes, how quickly to move the emission position around the radius.

当使用一个动画模式时，如何快速移动发射位置周围的弧。

**Parameters**

| Name | Type                                          |
| ---- | --------------------------------------------- |
| `v`  | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md) |

**Returns**

`void`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeEdge.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeEdge.ts#L63)

***

#### radiusSpread

• `get` **radiusSpread**(): `number`

Control the gap between emission points around the radius.

控制弧线周围发射点之间的间隙。

**Returns**

`number`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeEdge.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeEdge.ts#L43)

• `set` **radiusSpread**(`v`): `void`

Control the gap between emission points around the radius.

控制弧线周围发射点之间的间隙。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeEdge.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeEdge.ts#L48)
