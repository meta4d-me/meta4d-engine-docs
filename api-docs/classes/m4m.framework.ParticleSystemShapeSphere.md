# m4m.framework.ParticleSystemShapeSphere

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystemShapeSphere

## Class: ParticleSystemShapeSphere

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystemShapeSphere

从球体的体积中发射。

**`author`** feng3d

### Hierarchy

*   [`ParticleSystemShapeBase`](m4m.framework.ParticleSystemShapeBase.md)

    ↳ **`ParticleSystemShapeSphere`**

### Table of contents

#### Properties

* [\_module](m4m.framework.ParticleSystemShapeSphere.md#\_module)
* [emitFromShell](m4m.framework.ParticleSystemShapeSphere.md#emitfromshell)

#### Methods

* [calcParticlePosDir](m4m.framework.ParticleSystemShapeSphere.md#calcparticleposdir)

#### Constructors

* [constructor](m4m.framework.ParticleSystemShapeSphere.md#constructor)

#### Accessors

* [radius](m4m.framework.ParticleSystemShapeSphere.md#radius)

### Properties

#### \_module

• `Protected` **\_module**: [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md)

**Inherited from**

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[\_module](m4m.framework.ParticleSystemShapeBase.md#\_module)

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L10)

***

#### emitFromShell

• **emitFromShell**: `boolean` = `false`

是否从球面发射

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeSphere.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeSphere.ts#L26)

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

[framework/particlesystem/shapes/ParticleSystemShapeSphere.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeSphere.ts#L35)

### Constructors

#### constructor

• **new ParticleSystemShapeSphere**(`module`)

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

球体半径

**Returns**

`number`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeSphere.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeSphere.ts#L13)

• `set` **radius**(`v`): `void`

球体半径

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeSphere.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeSphere.ts#L18)
