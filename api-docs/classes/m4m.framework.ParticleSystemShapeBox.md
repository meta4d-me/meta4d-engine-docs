# m4m.framework.ParticleSystemShapeBox

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystemShapeBox

## Class: ParticleSystemShapeBox

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystemShapeBox

粒子系统 发射盒子

**`author`** feng3d

### Hierarchy

*   [`ParticleSystemShapeBase`](m4m.framework.ParticleSystemShapeBase.md)

    ↳ **`ParticleSystemShapeBox`**

### Table of contents

#### Properties

* [\_module](m4m.framework.ParticleSystemShapeBox.md#\_module)
* [emitFrom](m4m.framework.ParticleSystemShapeBox.md#emitfrom)

#### Accessors

* [boxX](m4m.framework.ParticleSystemShapeBox.md#boxx)
* [boxY](m4m.framework.ParticleSystemShapeBox.md#boxy)
* [boxZ](m4m.framework.ParticleSystemShapeBox.md#boxz)

#### Methods

* [calcParticlePosDir](m4m.framework.ParticleSystemShapeBox.md#calcparticleposdir)

#### Constructors

* [constructor](m4m.framework.ParticleSystemShapeBox.md#constructor)

### Properties

#### \_module

• `Protected` **\_module**: [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md)

**Inherited from**

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[\_module](m4m.framework.ParticleSystemShapeBase.md#\_module)

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L10)

***

#### emitFrom

• **emitFrom**: [`ParticleSystemShapeBoxEmitFrom`](../enums/m4m.framework.ParticleSystemShapeBoxEmitFrom.md) = `ParticleSystemShapeBoxEmitFrom.Volume`

粒子系统盒子发射类型。

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBox.ts:73](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBox.ts#L73)

### Accessors

#### boxX

• `get` **boxX**(): `number`

盒子X方向缩放。

**Returns**

`number`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBox.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBox.ts#L34)

• `set` **boxX**(`v`): `void`

盒子X方向缩放。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBox.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBox.ts#L39)

***

#### boxY

• `get` **boxY**(): `number`

盒子Y方向缩放。

**Returns**

`number`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBox.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBox.ts#L47)

• `set` **boxY**(`v`): `void`

盒子Y方向缩放。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBox.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBox.ts#L52)

***

#### boxZ

• `get` **boxZ**(): `number`

盒子Z方向缩放。

**Returns**

`number`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBox.ts:60](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBox.ts#L60)

• `set` **boxZ**(`v`): `void`

盒子Z方向缩放。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBox.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBox.ts#L65)

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

[framework/particlesystem/shapes/ParticleSystemShapeBox.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBox.ts#L82)

### Constructors

#### constructor

• **new ParticleSystemShapeBox**(`module`)

**Parameters**

| Name     | Type                                                          |
| -------- | ------------------------------------------------------------- |
| `module` | [`ParticleShapeModule`](m4m.framework.ParticleShapeModule.md) |

**Inherited from**

[ParticleSystemShapeBase](m4m.framework.ParticleSystemShapeBase.md).[constructor](m4m.framework.ParticleSystemShapeBase.md#constructor)

**Defined in**

[framework/particlesystem/shapes/ParticleSystemShapeBase.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/shapes/ParticleSystemShapeBase.ts#L12)
