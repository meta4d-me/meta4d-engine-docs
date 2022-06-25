[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / compoundBody2d

# Class: compoundBody2d

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).compoundBody2d

**`language`** zh_CN

**`classdesc`**
复合 2d 刚体

**`version`** m4m 1.0

## Hierarchy

- [`physics2DBody`](m4m.framework.physics2DBody.md)

  ↳ **`compoundBody2d`**

## Table of contents

### Properties

- [\_physicsEngine](m4m.framework.compoundBody2d.md#_physicsengine)
- [body](m4m.framework.compoundBody2d.md#body)
- [enabled](m4m.framework.compoundBody2d.md#enabled)
- [onInit](m4m.framework.compoundBody2d.md#oninit)
- [options](m4m.framework.compoundBody2d.md#options)
- [transform](m4m.framework.compoundBody2d.md#transform)
- [ClassName](m4m.framework.compoundBody2d.md#classname)

### Methods

- [addForce](m4m.framework.compoundBody2d.md#addforce)
- [addPart](m4m.framework.compoundBody2d.md#addpart)
- [afterStep](m4m.framework.compoundBody2d.md#afterstep)
- [beforeStep](m4m.framework.compoundBody2d.md#beforestep)
- [isSensor](m4m.framework.compoundBody2d.md#issensor)
- [isSleeping](m4m.framework.compoundBody2d.md#issleeping)
- [isStatic](m4m.framework.compoundBody2d.md#isstatic)
- [onPlay](m4m.framework.compoundBody2d.md#onplay)
- [remove](m4m.framework.compoundBody2d.md#remove)
- [setAngle](m4m.framework.compoundBody2d.md#setangle)
- [setAngularVelocity](m4m.framework.compoundBody2d.md#setangularvelocity)
- [setCentre](m4m.framework.compoundBody2d.md#setcentre)
- [setDensity](m4m.framework.compoundBody2d.md#setdensity)
- [setFriction](m4m.framework.compoundBody2d.md#setfriction)
- [setFrictionAir](m4m.framework.compoundBody2d.md#setfrictionair)
- [setFrictionStatic](m4m.framework.compoundBody2d.md#setfrictionstatic)
- [setInertia](m4m.framework.compoundBody2d.md#setinertia)
- [setInitData](m4m.framework.compoundBody2d.md#setinitdata)
- [setMass](m4m.framework.compoundBody2d.md#setmass)
- [setParts](m4m.framework.compoundBody2d.md#setparts)
- [setPosition](m4m.framework.compoundBody2d.md#setposition)
- [setRestitution](m4m.framework.compoundBody2d.md#setrestitution)
- [setScale](m4m.framework.compoundBody2d.md#setscale)
- [setSleeping](m4m.framework.compoundBody2d.md#setsleeping)
- [setStatic](m4m.framework.compoundBody2d.md#setstatic)
- [setVelocity](m4m.framework.compoundBody2d.md#setvelocity)
- [setVertices](m4m.framework.compoundBody2d.md#setvertices)
- [start](m4m.framework.compoundBody2d.md#start)
- [update](m4m.framework.compoundBody2d.md#update)

### Constructors

- [constructor](m4m.framework.compoundBody2d.md#constructor)

### Accessors

- [physicsEngine](m4m.framework.compoundBody2d.md#physicsengine)
- [positionOffset](m4m.framework.compoundBody2d.md#positionoffset)

## Properties

### \_physicsEngine

• `Protected` **\_physicsEngine**: [`physicEngine2D`](m4m.framework.physicEngine2D.md)

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[_physicsEngine](m4m.framework.physics2DBody.md#_physicsengine)

#### Defined in

[framework/2d/physicEngine/basebody.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L116)

___

### body

• **body**: [`Ibody`](../interfaces/m4m.framework.Ibody.md)

物理世界body

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[body](m4m.framework.physics2DBody.md#body)

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

[physics2DBody](m4m.framework.physics2DBody.md).[enabled](m4m.framework.physics2DBody.md#enabled)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[onInit](m4m.framework.physics2DBody.md#oninit)

#### Defined in

[framework/2d/physicEngine/basebody.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L134)

___

### options

• **options**: [`I2dPhyBodyData`](../interfaces/m4m.framework.I2dPhyBodyData.md) = `{}`

body 选项数据

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[options](m4m.framework.physics2DBody.md#options)

#### Defined in

[framework/2d/physicEngine/basebody.ts:251](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L251)

___

### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

绑定的UI

#### Overrides

[physics2DBody](m4m.framework.physics2DBody.md).[transform](m4m.framework.physics2DBody.md#transform)

#### Defined in

[framework/2d/physicEngine/compoundBody.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/compoundBody.ts#L17)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"compoundBody2d"`

#### Defined in

[framework/2d/physicEngine/compoundBody.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/compoundBody.ts#L16)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[addForce](m4m.framework.physics2DBody.md#addforce)

#### Defined in

[framework/2d/physicEngine/basebody.ts:187](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L187)

___

### addPart

▸ **addPart**(`body`): `void`

添加部分 body

#### Parameters

| Name | Type |
| :------ | :------ |
| `body` | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |

#### Returns

`void`

#### Defined in

[framework/2d/physicEngine/compoundBody.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/compoundBody.ts#L49)

___

### afterStep

▸ **afterStep**(): `void`

#### Returns

`void`

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[afterStep](m4m.framework.physics2DBody.md#afterstep)

#### Defined in

[framework/2d/physicEngine/basebody.ts:387](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L387)

___

### beforeStep

▸ **beforeStep**(): `void`

#### Returns

`void`

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[beforeStep](m4m.framework.physics2DBody.md#beforestep)

#### Defined in

[framework/2d/physicEngine/basebody.ts:371](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L371)

___

### isSensor

▸ **isSensor**(): `boolean`

是否是传感器
A flag that indicates whether a body is a sensor. Sensor triggers collision events, but doesn't react with colliding body physically.

#### Returns

`boolean`

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[isSensor](m4m.framework.physics2DBody.md#issensor)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[isSleeping](m4m.framework.physics2DBody.md#issleeping)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[isStatic](m4m.framework.physics2DBody.md#isstatic)

#### Defined in

[framework/2d/physicEngine/basebody.ts:172](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L172)

___

### onPlay

▸ **onPlay**(): `void`

初始化使用  在start 之后

#### Returns

`void`

#### Overrides

[physics2DBody](m4m.framework.physics2DBody.md).[onPlay](m4m.framework.physics2DBody.md#onplay)

#### Defined in

[framework/2d/physicEngine/compoundBody.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/compoundBody.ts#L54)

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[remove](m4m.framework.physics2DBody.md#remove)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setAngle](m4m.framework.physics2DBody.md#setangle)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setAngularVelocity](m4m.framework.physics2DBody.md#setangularvelocity)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setCentre](m4m.framework.physics2DBody.md#setcentre)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setDensity](m4m.framework.physics2DBody.md#setdensity)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setFriction](m4m.framework.physics2DBody.md#setfriction)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setFrictionAir](m4m.framework.physics2DBody.md#setfrictionair)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setFrictionStatic](m4m.framework.physics2DBody.md#setfrictionstatic)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setInertia](m4m.framework.physics2DBody.md#setinertia)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setInitData](m4m.framework.physics2DBody.md#setinitdata)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setMass](m4m.framework.physics2DBody.md#setmass)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setParts](m4m.framework.physics2DBody.md#setparts)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setPosition](m4m.framework.physics2DBody.md#setposition)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setRestitution](m4m.framework.physics2DBody.md#setrestitution)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setScale](m4m.framework.physics2DBody.md#setscale)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setSleeping](m4m.framework.physics2DBody.md#setsleeping)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setStatic](m4m.framework.physics2DBody.md#setstatic)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setVelocity](m4m.framework.physics2DBody.md#setvelocity)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[setVertices](m4m.framework.physics2DBody.md#setvertices)

#### Defined in

[framework/2d/physicEngine/basebody.ts:338](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L338)

___

### start

▸ **start**(): `void`

初始化使用

#### Returns

`void`

#### Overrides

[physics2DBody](m4m.framework.physics2DBody.md).[start](m4m.framework.physics2DBody.md#start)

#### Defined in

[framework/2d/physicEngine/compoundBody.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/compoundBody.ts#L21)

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

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[update](m4m.framework.physics2DBody.md#update)

#### Defined in

[framework/2d/physicEngine/basebody.ts:367](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L367)

## Constructors

### constructor

• **new compoundBody2d**()

#### Inherited from

[physics2DBody](m4m.framework.physics2DBody.md).[constructor](m4m.framework.physics2DBody.md#constructor)

#### Defined in

[framework/2d/physicEngine/basebody.ts:118](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L118)

## Accessors

### physicsEngine

• `get` **physicsEngine**(): [`physicEngine2D`](m4m.framework.physicEngine2D.md)

2d物理引擎实例对象

#### Returns

[`physicEngine2D`](m4m.framework.physicEngine2D.md)

#### Inherited from

physics2DBody.physicsEngine

#### Defined in

[framework/2d/physicEngine/basebody.ts:109](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L109)

___

### positionOffset

• `get` **positionOffset**(): `vector2`

物理对象 碰撞体位置偏移量

#### Returns

`vector2`

#### Inherited from

physics2DBody.positionOffset

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

#### Inherited from

physics2DBody.positionOffset

#### Defined in

[framework/2d/physicEngine/basebody.ts:139](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/basebody.ts#L139)
