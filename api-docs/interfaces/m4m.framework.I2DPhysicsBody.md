[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / I2DPhysicsBody

# Interface: I2DPhysicsBody

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).I2DPhysicsBody

## Implemented by

- [`physics2DBody`](../classes/m4m.framework.physics2DBody.md)

## Table of contents

### Methods

- [addForce](m4m.framework.I2DPhysicsBody.md#addforce)
- [afterStep](m4m.framework.I2DPhysicsBody.md#afterstep)
- [beforeStep](m4m.framework.I2DPhysicsBody.md#beforestep)
- [isSensor](m4m.framework.I2DPhysicsBody.md#issensor)
- [isSleeping](m4m.framework.I2DPhysicsBody.md#issleeping)
- [isStatic](m4m.framework.I2DPhysicsBody.md#isstatic)
- [onInit](m4m.framework.I2DPhysicsBody.md#oninit)
- [setAngle](m4m.framework.I2DPhysicsBody.md#setangle)
- [setAngularVelocity](m4m.framework.I2DPhysicsBody.md#setangularvelocity)
- [setDensity](m4m.framework.I2DPhysicsBody.md#setdensity)
- [setFriction](m4m.framework.I2DPhysicsBody.md#setfriction)
- [setFrictionAir](m4m.framework.I2DPhysicsBody.md#setfrictionair)
- [setFrictionStatic](m4m.framework.I2DPhysicsBody.md#setfrictionstatic)
- [setInertia](m4m.framework.I2DPhysicsBody.md#setinertia)
- [setMass](m4m.framework.I2DPhysicsBody.md#setmass)
- [setParts](m4m.framework.I2DPhysicsBody.md#setparts)
- [setPosition](m4m.framework.I2DPhysicsBody.md#setposition)
- [setRestitution](m4m.framework.I2DPhysicsBody.md#setrestitution)
- [setVelocity](m4m.framework.I2DPhysicsBody.md#setvelocity)
- [setVertices](m4m.framework.I2DPhysicsBody.md#setvertices)

### Properties

- [body](m4m.framework.I2DPhysicsBody.md#body)
- [options](m4m.framework.I2DPhysicsBody.md#options)
- [physicsEngine](m4m.framework.I2DPhysicsBody.md#physicsengine)
- [transform](m4m.framework.I2DPhysicsBody.md#transform)

## Methods

### addForce

▸ **addForce**(`Force`): `any`

施加力

#### Parameters

| Name | Type |
| :------ | :------ |
| `Force` | [`Ivec2`](m4m.math.Ivec2.md) |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L16)

___

### afterStep

▸ **afterStep**(): `any`

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L51)

___

### beforeStep

▸ **beforeStep**(): `any`

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L50)

___

### isSensor

▸ **isSensor**(): `boolean`

是否是传感器

#### Returns

`boolean`

#### Defined in

[framework/2d/physicEngine/basebody.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L46)

___

### isSleeping

▸ **isSleeping**(): `boolean`

是否睡眠

#### Returns

`boolean`

#### Defined in

[framework/2d/physicEngine/basebody.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L44)

___

### isStatic

▸ **isStatic**(): `boolean`

是否是静态

#### Returns

`boolean`

#### Defined in

[framework/2d/physicEngine/basebody.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L48)

___

### onInit

▸ **onInit**(`phy2dBody`): `any`

初始化完成回调

#### Parameters

| Name | Type |
| :------ | :------ |
| `phy2dBody` | [`I2DPhysicsBody`](m4m.framework.I2DPhysicsBody.md) |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L6)

___

### setAngle

▸ **setAngle**(`angle`): `any`

设置旋转角度

#### Parameters

| Name | Type |
| :------ | :------ |
| `angle` | `number` |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L34)

___

### setAngularVelocity

▸ **setAngularVelocity**(`velocity`): `any`

设置角速度

#### Parameters

| Name | Type |
| :------ | :------ |
| `velocity` | `number` |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L42)

___

### setDensity

▸ **setDensity**(`Desity`): `any`

设置 密度

#### Parameters

| Name | Type |
| :------ | :------ |
| `Desity` | `number` |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L20)

___

### setFriction

▸ **setFriction**(`friction`): `any`

设置 摩擦系数

#### Parameters

| Name | Type |
| :------ | :------ |
| `friction` | `number` |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L24)

___

### setFrictionAir

▸ **setFrictionAir**(`frictionAir`): `any`

设置 空气摩擦系数

#### Parameters

| Name | Type |
| :------ | :------ |
| `frictionAir` | `number` |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L22)

___

### setFrictionStatic

▸ **setFrictionStatic**(`frictionStatic`): `any`

设置 静态摩擦系数

#### Parameters

| Name | Type |
| :------ | :------ |
| `frictionStatic` | `number` |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L26)

___

### setInertia

▸ **setInertia**(`Inertia`): `any`

设置惯性值

#### Parameters

| Name | Type |
| :------ | :------ |
| `Inertia` | `number` |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L40)

___

### setMass

▸ **setMass**(`mass`): `any`

设置质量

#### Parameters

| Name | Type |
| :------ | :------ |
| `mass` | `number` |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L30)

___

### setParts

▸ **setParts**(`parts`, `autoHull`): `any`

设置成员

#### Parameters

| Name | Type |
| :------ | :------ |
| `parts` | [`Ibody`](m4m.framework.Ibody.md)[] |
| `autoHull` | `boolean` |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L36)

___

### setPosition

▸ **setPosition**(`pos`): `any`

设置位置

#### Parameters

| Name | Type |
| :------ | :------ |
| `pos` | [`Ivec2`](m4m.math.Ivec2.md) |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L32)

___

### setRestitution

▸ **setRestitution**(`restitution`): `any`

设置 恢复系数

#### Parameters

| Name | Type |
| :------ | :------ |
| `restitution` | `number` |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L28)

___

### setVelocity

▸ **setVelocity**(`velocity`): `any`

设置 速度

#### Parameters

| Name | Type |
| :------ | :------ |
| `velocity` | [`Ivec2`](m4m.math.Ivec2.md) |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L18)

___

### setVertices

▸ **setVertices**(`vertices`): `any`

设置顶点

#### Parameters

| Name | Type |
| :------ | :------ |
| `vertices` | [`Ivec2`](m4m.math.Ivec2.md)[] |

#### Returns

`any`

#### Defined in

[framework/2d/physicEngine/basebody.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L38)

## Properties

### body

• **body**: [`Ibody`](m4m.framework.Ibody.md)

物理世界body

#### Defined in

[framework/2d/physicEngine/basebody.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L14)

___

### options

• **options**: [`I2dPhyBodyData`](m4m.framework.I2dPhyBodyData.md)

body 选项数据

#### Defined in

[framework/2d/physicEngine/basebody.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L10)

___

### physicsEngine

• **physicsEngine**: [`physicEngine2D`](../classes/m4m.framework.physicEngine2D.md)

引擎对象

#### Defined in

[framework/2d/physicEngine/basebody.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L8)

___

### transform

• **transform**: [`transform2D`](../classes/m4m.framework.transform2D.md)

绑定的UI

#### Defined in

[framework/2d/physicEngine/basebody.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L12)
