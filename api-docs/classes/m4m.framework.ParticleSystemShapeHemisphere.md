# m4m.framework.ParticleSystemShapeHemisphere

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystemShapeHemisphere

## Class: ParticleSystemShapeHemisphere

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystemShapeHemisphere

从半球体的体积中发出。

### Hierarchy

*   [`ParticleSystemShapeBase`](m4m.framework.ParticleSystemShapeBase.md)

    ↳ **`ParticleSystemShapeHemisphere`**

### Table of contents

#### Properties

* [\_module](m4m.framework.ParticleSystemShapeHemisphere.md#\_module)
* [emitFromShell](m4m.framework.ParticleSystemShapeHemisphere.md#emitfromshell)
* [radius](m4m.framework.ParticleSystemShapeHemisphere.md#radius)

#### Methods

* [calcParticlePosDir](m4m.framework.ParticleSystemShapeHemisphere.md#calcparticleposdir)

#### Constructors

* [constructor](m4m.framework.ParticleSystemShapeHemisphere.md#constructor)

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

[framework/particlesystem/shapes/ParticleSystemShapeSphere.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeSphere.ts#L66)

***

#### radius

• **radius**: `number` = `1`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeSphere.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeSphere.ts#L61)

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

[framework/particlesystem/shapes/ParticleSystemShapeSphere.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeSphere.ts#L75)

### Constructors

#### constructor

• **new ParticleSystemShapeHemisphere**(`module`)

**Parameters**

| Name     | Type                                                          |
| -------- | ------------------------------------------------------------- |
| `module` | [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md) |

**Inherited from**

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[constructor](m4m.framework.ParticleSystemShapeBase.md#constructor)

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L12)
