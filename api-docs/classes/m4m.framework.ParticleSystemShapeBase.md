# m4m.framework.ParticleSystemShapeBase

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystemShapeBase

## Class: ParticleSystemShapeBase

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystemShapeBase

粒子系统 发射形状

**`author`** feng3d

### Hierarchy

*   **`ParticleSystemShapeBase`**

    ↳ [`ParticleSystemShapeBox`](m4m.framework.ParticleSystemShapeBox.md)

    ↳ [`ParticleSystemShapeCircle`](m4m.framework.ParticleSystemShapeCircle.md)

    ↳ [`ParticleSystemShapeCone`](m4m.framework.ParticleSystemShapeCone.md)

    ↳ [`ParticleSystemShapeEdge`](m4m.framework.ParticleSystemShapeEdge.md)

    ↳ [`ParticleSystemShapeSphere`](m4m.framework.ParticleSystemShapeSphere.md)

    ↳ [`ParticleSystemShapeHemisphere`](m4m.framework.ParticleSystemShapeHemisphere.md)

### Table of contents

#### Properties

* [\_module](m4m.framework.ParticleSystemShapeBase.md#\_module)

#### Methods

* [calcParticlePosDir](m4m.framework.ParticleSystemShapeBase.md#calcparticleposdir)

#### Constructors

* [constructor](m4m.framework.ParticleSystemShapeBase.md#constructor)

### Properties

#### \_module

• `Protected` **\_module**: [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md)

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

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L25)

### Constructors

#### constructor

• **new ParticleSystemShapeBase**(`module`)

**Parameters**

| Name     | Type                                                          |
| -------- | ------------------------------------------------------------- |
| `module` | [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md) |

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L12)
