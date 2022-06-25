[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / physics2DBody

# Class: physics2DBody

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).physics2DBody

2d 物理引擎Body 组件父对象
（本组件不会创建具体物理对象，需要使用子类对象 或者 自行在onInit回调中创建）

## Hierarchy

- [`behaviour2d`](m4m.framework.behaviour2d.md)

  ↳ **`physics2DBody`**

  ↳↳ [`capsuleBody2d`](m4m.framework.capsuleBody2d.md)

  ↳↳ [`circleBody2d`](m4m.framework.circleBody2d.md)

  ↳↳ [`compoundBody2d`](m4m.framework.compoundBody2d.md)

  ↳↳ [`convexHullBody2d`](m4m.framework.convexHullBody2d.md)

  ↳↳ [`rectBody2d`](m4m.framework.rectBody2d.md)

## Implements

- [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md)

## Table of contents

### Properties

- [\_physicsEngine](m4m.framework.physics2DBody.md#_physicsengine)
- [body](m4m.framework.physics2DBody.md#body)
- [enabled](m4m.framework.physics2DBody.md#enabled)
- [onInit](m4m.framework.physics2DBody.md#oninit)
- [options](m4m.framework.physics2DBody.md#options)
- [transform](m4m.framework.physics2DBody.md#transform)

### Methods

- [addForce](m4m.framework.physics2DBody.md#addforce)
- [afterStep](m4m.framework.physics2DBody.md#afterstep)
- [beforeStep](m4m.framework.physics2DBody.md#beforestep)
- [isSensor](m4m.framework.physics2DBody.md#issensor)
- [isSleeping](m4m.framework.physics2DBody.md#issleeping)
- [isStatic](m4m.framework.physics2DBody.md#isstatic)
- [onPlay](m4m.framework.physics2DBody.md#onplay)
- [remove](m4m.framework.physics2DBody.md#remove)
- [setAngle](m4m.framework.physics2DBody.md#setangle)
- [setAngularVelocity](m4m.framework.physics2DBody.md#setangularvelocity)
- [setCentre](m4m.framework.physics2DBody.md#setcentre)
- [setDensity](m4m.framework.physics2DBody.md#setdensity)
- [setFriction](m4m.framework.physics2DBody.md#setfriction)
- [setFrictionAir](m4m.framework.physics2DBody.md#setfrictionair)
- [setFrictionStatic](m4m.framework.physics2DBody.md#setfrictionstatic)
- [setInertia](m4m.framework.physics2DBody.md#setinertia)
- [setInitData](m4m.framework.physics2DBody.md#setinitdata)
- [setMass](m4m.framework.physics2DBody.md#setmass)
- [setParts](m4m.framework.physics2DBody.md#setparts)
- [setPosition](m4m.framework.physics2DBody.md#setposition)
- [setRestitution](m4m.framework.physics2DBody.md#setrestitution)
- [setScale](m4m.framework.physics2DBody.md#setscale)
- [setSleeping](m4m.framework.physics2DBody.md#setsleeping)
- [setStatic](m4m.framework.physics2DBody.md#setstatic)
- [setVelocity](m4m.framework.physics2DBody.md#setvelocity)
- [setVertices](m4m.framework.physics2DBody.md#setvertices)
- [start](m4m.framework.physics2DBody.md#start)
- [update](m4m.framework.physics2DBody.md#update)

### Constructors

- [constructor](m4m.framework.physics2DBody.md#constructor)

### Accessors

- [physicsEngine](m4m.framework.physics2DBody.md#physicsengine)
- [positionOffset](m4m.framework.physics2DBody.md#positionoffset)

## Properties

### \_physicsEngine

• `Protected` **\_physicsEngine**: [`physicEngine2D`](m4m.framework.physicEngine2D.md)

#### Defined in

[framework/2d/physicEngine/basebody.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L116)

___

### body

• **body**: [`Ibody`](../interfaces/m4m.framework.Ibody.md)

物理世界body

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[body](../interfaces/m4m.framework.I2DPhysicsBody.md#body)

#### Defined in

[framework/2d/physicEngine/basebody.ts:132](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L132)

___

### enabled

• **enabled**: `boolean` = `true`

**`language`** zh_CN

**`classdesc`**
组件启用

**`version`** m4m 1.0

#### Inherited from

[behaviour2d](m4m.framework.behaviour2d.md).[enabled](m4m.framework.behaviour2d.md#enabled)

#### Defined in

[framework/2d/component/behaviour2d.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/behaviour2d.ts#L16)

___

### onInit

• **onInit**: (`phy2dBody`: [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md)) => `any`

#### Type declaration

▸ (`phy2dBody`): `any`

物理对象初始化完成回调

##### Parameters

| Name | Type |
| :------ | :------ |
| `phy2dBody` | [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md) |

##### Returns

`any`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[onInit](../interfaces/m4m.framework.I2DPhysicsBody.md#oninit)

#### Defined in

[framework/2d/physicEngine/basebody.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L134)

___

### options

• **options**: [`I2dPhyBodyData`](../interfaces/m4m.framework.I2dPhyBodyData.md) = `{}`

body 选项数据

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[options](../interfaces/m4m.framework.I2DPhysicsBody.md#options)

#### Defined in

[framework/2d/physicEngine/basebody.ts:251](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L251)

___

### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

绑定的UI

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[transform](../interfaces/m4m.framework.I2DPhysicsBody.md#transform)

#### Overrides

[behaviour2d](m4m.framework.behaviour2d.md).[transform](m4m.framework.behaviour2d.md#transform)

#### Defined in

[framework/2d/physicEngine/basebody.ts:131](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L131)

## Methods

### addForce

▸ **addForce**(`Force`): `void`

施加作用力

#### Parameters

| Name | Type |
| :------ | :------ |
| `Force` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md) |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[addForce](../interfaces/m4m.framework.I2DPhysicsBody.md#addforce)

#### Defined in

[framework/2d/physicEngine/basebody.ts:187](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L187)

___

### afterStep

▸ **afterStep**(): `void`

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[afterStep](../interfaces/m4m.framework.I2DPhysicsBody.md#afterstep)

#### Defined in

[framework/2d/physicEngine/basebody.ts:387](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L387)

___

### beforeStep

▸ **beforeStep**(): `void`

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[beforeStep](../interfaces/m4m.framework.I2DPhysicsBody.md#beforestep)

#### Defined in

[framework/2d/physicEngine/basebody.ts:371](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L371)

___

### isSensor

▸ **isSensor**(): `boolean`

是否是传感器
A flag that indicates whether a body is a sensor. Sensor triggers collision events, but doesn't react with colliding body physically.

#### Returns

`boolean`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[isSensor](../interfaces/m4m.framework.I2DPhysicsBody.md#issensor)

#### Defined in

[framework/2d/physicEngine/basebody.ts:179](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L179)

___

### isSleeping

▸ **isSleeping**(): `boolean`

是否已休眠
A flag that indicates whether the body is considered sleeping. A sleeping body acts similar to a static body, except it is only temporary and can be awoken.
If you need to set a body as sleeping, you should use `Sleeping.set` as this requires more than just setting this flag.

#### Returns

`boolean`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[isSleeping](../interfaces/m4m.framework.I2DPhysicsBody.md#issleeping)

#### Defined in

[framework/2d/physicEngine/basebody.ts:164](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L164)

___

### isStatic

▸ **isStatic**(): `boolean`

是否是静态
A flag that indicates whether a body is considered static. A static body can never change position or angle and is completely fixed.
If you need to set a body as static after its creation, you should use `Body.setStatic` as this requires more than just setting this flag.

#### Returns

`boolean`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[isStatic](../interfaces/m4m.framework.I2DPhysicsBody.md#isstatic)

#### Defined in

[framework/2d/physicEngine/basebody.ts:172](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L172)

___

### onPlay

▸ **onPlay**(): `void`

初始化使用  在start 之后

#### Returns

`void`

#### Inherited from

[behaviour2d](m4m.framework.behaviour2d.md).[onPlay](m4m.framework.behaviour2d.md#onplay)

#### Defined in

[framework/2d/component/behaviour2d.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/behaviour2d.ts#L33)

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Overrides

[behaviour2d](m4m.framework.behaviour2d.md).[remove](m4m.framework.behaviour2d.md#remove)

#### Defined in

[framework/2d/physicEngine/basebody.ts:452](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L452)

___

### setAngle

▸ **setAngle**(`angle`): `void`

设置旋转角度

#### Parameters

| Name | Type |
| :------ | :------ |
| `angle` | `number` |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setAngle](../interfaces/m4m.framework.I2DPhysicsBody.md#setangle)

#### Defined in

[framework/2d/physicEngine/basebody.ts:285](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L285)

___

### setAngularVelocity

▸ **setAngularVelocity**(`velocity`): `void`

设置角速度

#### Parameters

| Name | Type |
| :------ | :------ |
| `velocity` | `number` |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setAngularVelocity](../interfaces/m4m.framework.I2DPhysicsBody.md#setangularvelocity)

#### Defined in

[framework/2d/physicEngine/basebody.ts:202](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L202)

___

### setCentre

▸ **setCentre**(`centre`, `relative?`): `void`

设置中心点
Set the centre of mass of the body.
The `centre` is a vector in world-space unless `relative` is set, in which case it is a translation.
The centre of mass is the point the body rotates about and can be used to simulate non-uniform density.
This is equal to moving `body.position` but not the `body.vertices`.
Invalid if the `centre` falls outside the body's convex hull.

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `centre` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md) | `undefined` |
| `relative` | `boolean` | `false` |

#### Returns

`void`

#### Defined in

[framework/2d/physicEngine/basebody.ts:359](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L359)

___

### setDensity

▸ **setDensity**(`Desity`): `void`

设置密度

#### Parameters

| Name | Type |
| :------ | :------ |
| `Desity` | `number` |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setDensity](../interfaces/m4m.framework.I2DPhysicsBody.md#setdensity)

#### Defined in

[framework/2d/physicEngine/basebody.ts:210](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L210)

___

### setFriction

▸ **setFriction**(`friction`): `void`

设置摩擦力

#### Parameters

| Name | Type |
| :------ | :------ |
| `friction` | `number` |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setFriction](../interfaces/m4m.framework.I2DPhysicsBody.md#setfriction)

#### Defined in

[framework/2d/physicEngine/basebody.ts:225](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L225)

___

### setFrictionAir

▸ **setFrictionAir**(`frictionAir`): `void`

设置空气摩擦力

#### Parameters

| Name | Type |
| :------ | :------ |
| `frictionAir` | `number` |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setFrictionAir](../interfaces/m4m.framework.I2DPhysicsBody.md#setfrictionair)

#### Defined in

[framework/2d/physicEngine/basebody.ts:218](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L218)

___

### setFrictionStatic

▸ **setFrictionStatic**(`frictionStatic`): `void`

设置静态摩擦力

#### Parameters

| Name | Type |
| :------ | :------ |
| `frictionStatic` | `number` |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setFrictionStatic](../interfaces/m4m.framework.I2DPhysicsBody.md#setfrictionstatic)

#### Defined in

[framework/2d/physicEngine/basebody.ts:232](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L232)

___

### setInertia

▸ **setInertia**(`Inertia`): `void`

设置惯性值
Sets the moment of inertia (i.e. second moment of area) of the body.
Inverse inertia is automatically updated to reflect the change. Mass is not changed.

#### Parameters

| Name | Type |
| :------ | :------ |
| `Inertia` | `number` |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setInertia](../interfaces/m4m.framework.I2DPhysicsBody.md#setinertia)

#### Defined in

[framework/2d/physicEngine/basebody.ts:326](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L326)

___

### setInitData

▸ **setInitData**(`options`): `void`

设置选项数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `options` | [`I2dPhyBodyData`](../interfaces/m4m.framework.I2dPhyBodyData.md) | 选项数据 |

#### Returns

`void`

#### Defined in

[framework/2d/physicEngine/basebody.ts:256](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L256)

___

### setMass

▸ **setMass**(`mass`): `void`

设置质量

#### Parameters

| Name | Type |
| :------ | :------ |
| `mass` | `number` |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setMass](../interfaces/m4m.framework.I2DPhysicsBody.md#setmass)

#### Defined in

[framework/2d/physicEngine/basebody.ts:247](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L247)

___

### setParts

▸ **setParts**(`parts`, `autoHull?`): `void`

设置成员
Sets the parts of the `body` and updates mass, inertia and centroid.
Each part will have its parent set to `body`.
By default the convex hull will be automatically computed and set on `body`, unless `autoHull` is set to `false.`
Note that this method will ensure that the first part in `body.parts` will always be the `body`.

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `parts` | [`Ibody`](../interfaces/m4m.framework.Ibody.md)[] | `undefined` |
| `autoHull` | `boolean` | `true` |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setParts](../interfaces/m4m.framework.I2DPhysicsBody.md#setparts)

#### Defined in

[framework/2d/physicEngine/basebody.ts:348](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L348)

___

### setPosition

▸ **setPosition**(`pos`): `void`

设置位置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pos` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md) | 位置vec2 |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setPosition](../interfaces/m4m.framework.I2DPhysicsBody.md#setposition)

#### Defined in

[framework/2d/physicEngine/basebody.ts:264](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L264)

___

### setRestitution

▸ **setRestitution**(`restitution`): `void`

设置还原张力

#### Parameters

| Name | Type |
| :------ | :------ |
| `restitution` | `number` |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setRestitution](../interfaces/m4m.framework.I2DPhysicsBody.md#setrestitution)

#### Defined in

[framework/2d/physicEngine/basebody.ts:239](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L239)

___

### setScale

▸ **setScale**(`scale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `scale` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md) |

#### Returns

`void`

#### Defined in

[framework/2d/physicEngine/basebody.ts:301](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L301)

___

### setSleeping

▸ **setSleeping**(`isSleeping`): `void`

设置休眠状态

#### Parameters

| Name | Type |
| :------ | :------ |
| `isSleeping` | `boolean` |

#### Returns

`void`

#### Defined in

[framework/2d/physicEngine/basebody.ts:318](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L318)

___

### setStatic

▸ **setStatic**(`isStatic`): `void`

设置静态状态
Sets the body as static, including isStatic flag and setting mass and inertia to Infinity.

#### Parameters

| Name | Type |
| :------ | :------ |
| `isStatic` | `boolean` |

#### Returns

`void`

#### Defined in

[framework/2d/physicEngine/basebody.ts:312](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L312)

___

### setVelocity

▸ **setVelocity**(`velocity`): `void`

设置速度

#### Parameters

| Name | Type |
| :------ | :------ |
| `velocity` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md) |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setVelocity](../interfaces/m4m.framework.I2DPhysicsBody.md#setvelocity)

#### Defined in

[framework/2d/physicEngine/basebody.ts:194](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L194)

___

### setVertices

▸ **setVertices**(`vertices`): `void`

设置顶点
Sets the body's vertices and updates body properties accordingly, including inertia, area and mass (with respect to `body.density`).
Vertices will be automatically transformed to be orientated around their centre of mass as the origin.
They are then automatically translated to world space based on `body.position`.

The `vertices` argument should be passed as an array of `Matter.Vector` points (or a `Matter.Vertices` array).
Vertices must form a convex hull, concave hulls are not supported.

#### Parameters

| Name | Type |
| :------ | :------ |
| `vertices` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md)[] |

#### Returns

`void`

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[setVertices](../interfaces/m4m.framework.I2DPhysicsBody.md#setvertices)

#### Defined in

[framework/2d/physicEngine/basebody.ts:338](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L338)

___

### start

▸ **start**(): `void`

初始化使用

#### Returns

`void`

#### Overrides

[behaviour2d](m4m.framework.behaviour2d.md).[start](m4m.framework.behaviour2d.md#start)

#### Defined in

[framework/2d/physicEngine/basebody.ts:363](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L363)

___

### update

▸ **update**(`delta`): `void`

每帧调用一次

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`void`

#### Overrides

[behaviour2d](m4m.framework.behaviour2d.md).[update](m4m.framework.behaviour2d.md#update)

#### Defined in

[framework/2d/physicEngine/basebody.ts:367](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L367)

## Constructors

### constructor

• **new physics2DBody**()

#### Overrides

[behaviour2d](m4m.framework.behaviour2d.md).[constructor](m4m.framework.behaviour2d.md#constructor)

#### Defined in

[framework/2d/physicEngine/basebody.ts:118](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L118)

## Accessors

### physicsEngine

• `get` **physicsEngine**(): [`physicEngine2D`](m4m.framework.physicEngine2D.md)

2d物理引擎实例对象

#### Returns

[`physicEngine2D`](m4m.framework.physicEngine2D.md)

#### Implementation of

[I2DPhysicsBody](../interfaces/m4m.framework.I2DPhysicsBody.md).[physicsEngine](../interfaces/m4m.framework.I2DPhysicsBody.md#physicsengine)

#### Defined in

[framework/2d/physicEngine/basebody.ts:109](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L109)

___

### positionOffset

• `get` **positionOffset**(): `vector2`

物理对象 碰撞体位置偏移量

#### Returns

`vector2`

#### Defined in

[framework/2d/physicEngine/basebody.ts:138](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L138)

• `set` **positionOffset**(`pos`): `void`

物理对象 碰撞体位置偏移量

#### Parameters

| Name | Type |
| :------ | :------ |
| `pos` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/2d/physicEngine/basebody.ts:139](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L139)
