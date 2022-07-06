# m4m.framework.physicEngine2D

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / physicEngine2D

## Class: physicEngine2D

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).physicEngine2D

### Table of contents

#### Methods

* [ConvexHullByPBody](m4m.framework.physicEngine2D.md#convexhullbypbody)
* [addBody](m4m.framework.physicEngine2D.md#addbody)
* [addEventListener](m4m.framework.physicEngine2D.md#addeventlistener)
* [applyForce](m4m.framework.physicEngine2D.md#applyforce)
* [applyForceAtCenter](m4m.framework.physicEngine2D.md#applyforceatcenter)
* [clearWorld](m4m.framework.physicEngine2D.md#clearworld)
* [compositeScale](m4m.framework.physicEngine2D.md#compositescale)
* [createBody](m4m.framework.physicEngine2D.md#createbody)
* [createCapsule](m4m.framework.physicEngine2D.md#createcapsule)
* [createCapsuleByPBody](m4m.framework.physicEngine2D.md#createcapsulebypbody)
* [createCircle](m4m.framework.physicEngine2D.md#createcircle)
* [createCircleByPBody](m4m.framework.physicEngine2D.md#createcirclebypbody)
* [createFromVertices](m4m.framework.physicEngine2D.md#createfromvertices)
* [createPolygon](m4m.framework.physicEngine2D.md#createpolygon)
* [createRectByPBody](m4m.framework.physicEngine2D.md#createrectbypbody)
* [createRectangle](m4m.framework.physicEngine2D.md#createrectangle)
* [createTrapezoid](m4m.framework.physicEngine2D.md#createtrapezoid)
* [getBody](m4m.framework.physicEngine2D.md#getbody)
* [removeBody](m4m.framework.physicEngine2D.md#removebody)
* [removeEventListener](m4m.framework.physicEngine2D.md#removeeventlistener)
* [setAngle](m4m.framework.physicEngine2D.md#setangle)
* [setAngularVelocity](m4m.framework.physicEngine2D.md#setangularvelocity)
* [setCentre](m4m.framework.physicEngine2D.md#setcentre)
* [setDensity](m4m.framework.physicEngine2D.md#setdensity)
* [setGravity](m4m.framework.physicEngine2D.md#setgravity)
* [setInertia](m4m.framework.physicEngine2D.md#setinertia)
* [setMass](m4m.framework.physicEngine2D.md#setmass)
* [setParts](m4m.framework.physicEngine2D.md#setparts)
* [setPosition](m4m.framework.physicEngine2D.md#setposition)
* [setScale](m4m.framework.physicEngine2D.md#setscale)
* [setSleeping](m4m.framework.physicEngine2D.md#setsleeping)
* [setStatic](m4m.framework.physicEngine2D.md#setstatic)
* [setVelocity](m4m.framework.physicEngine2D.md#setvelocity)
* [setVertices](m4m.framework.physicEngine2D.md#setvertices)
* [update](m4m.framework.physicEngine2D.md#update)

#### Accessors

* [Matter](m4m.framework.physicEngine2D.md#matter)
* [enableSleeping](m4m.framework.physicEngine2D.md#enablesleeping)

#### Constructors

* [constructor](m4m.framework.physicEngine2D.md#constructor)

#### Properties

* [engineRunner](m4m.framework.physicEngine2D.md#enginerunner)
* [engineWorld](m4m.framework.physicEngine2D.md#engineworld)
* [matterEngine](m4m.framework.physicEngine2D.md#matterengine)

### Methods

#### ConvexHullByPBody

▸ **ConvexHullByPBody**(`pBody`, `vertexSets`, `flagInternal?`, `removeCollinear?`, `minimumArea?`): [`Ibody`](../interfaces/m4m.framework.Ibody.md)

使用提供的顶点（或包含多组顶点的数组）创建一个新的物理实体 详细参考： createFromVertices（）

**Parameters**

| Name              | Type                                                              | Default value | Description       |
| ----------------- | ----------------------------------------------------------------- | ------------- | ----------------- |
| `pBody`           | [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md) | `undefined`   | I2DPhysicsBody 实例 |
| `vertexSets`      | `any`                                                             | `undefined`   | 顶点集合              |
| `flagInternal`    | `boolean`                                                         | `false`       | 内部模式标记            |
| `removeCollinear` | `number`                                                          | `0.01`        | 共线移除参考值           |
| `minimumArea`     | `number`                                                          | `10`          | 最小面积              |

**Returns**

[`Ibody`](../interfaces/m4m.framework.Ibody.md)

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:279](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L279)

***

#### addBody

▸ **addBody**(`_Pbody`): `void`

添加 I2DPhysicsBody 实例到 2d物理世界

**Parameters**

| Name     | Type                                                              |
| -------- | ----------------------------------------------------------------- |
| `_Pbody` | [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md) |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:473](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L473)

***

#### addEventListener

▸ **addEventListener**(`eventEnum`, `func`, `thisArg`): `void`

添加事件监听

**Parameters**

| Name        | Type                                                           | Description |
| ----------- | -------------------------------------------------------------- | ----------- |
| `eventEnum` | [`Physic2dEventEnum`](../enums/m4m.event.Physic2dEventEnum.md) | 事件类型        |
| `func`      | (...`args`: `any`\[]) => `void`                                | 事件回调函数      |
| `thisArg`   | `any`                                                          | 函数持有对象      |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:223](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L223)

***

#### applyForce

▸ **applyForce**(`body`, `positon`, `force`): `void`

**Parameters**

| Name      | Type                                            |
| --------- | ----------------------------------------------- |
| `body`    | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `positon` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md)      |
| `force`   | [`Ivec2`](../interfaces/m4m.math.Ivec2.md)      |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:496](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L496)

***

#### applyForceAtCenter

▸ **applyForceAtCenter**(`body`, `force`): `void`

**Parameters**

| Name    | Type                                            |
| ------- | ----------------------------------------------- |
| `body`  | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `force` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md)      |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:500](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L500)

***

#### clearWorld

▸ **clearWorld**(`keepStatic?`): `void`

清理世界

**Parameters**

| Name         | Type      | Default value |
| ------------ | --------- | ------------- |
| `keepStatic` | `boolean` | `false`       |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:492](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L492)

***

#### compositeScale

▸ **compositeScale**(`composite`, `scaleX`, `scaleY`, `point`, `recursive?`): `void`

复合体缩放 Scales all children in the composite, including updating physical properties (mass, area, axes, inertia), from a world-space point.

**Parameters**

| Name        | Type                                       | Default value |
| ----------- | ------------------------------------------ | ------------- |
| `composite` | `any`                                      | `undefined`   |
| `scaleX`    | `number`                                   | `undefined`   |
| `scaleY`    | `number`                                   | `undefined`   |
| `point`     | [`Ivec2`](../interfaces/m4m.math.Ivec2.md) | `undefined`   |
| `recursive` | `boolean`                                  | `false`       |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:627](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L627)

***

#### createBody

▸ **createBody**(`options`): [`Ibody`](../interfaces/m4m.framework.Ibody.md)

Creates a new rigid body model. The options parameter is an object that specifies any properties you wish to override the defaults. All properties have default values, and many are pre-calculated automatically based on other properties. Vertices must be specified in clockwise order. See the properties section below for detailed information on what you can pass via the `options` object.

**Parameters**

| Name      | Type                                                              |
| --------- | ----------------------------------------------------------------- |
| `options` | [`I2dPhyBodyData`](../interfaces/m4m.framework.I2dPhyBodyData.md) |

**Returns**

[`Ibody`](../interfaces/m4m.framework.Ibody.md)

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:318](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L318)

***

#### createCapsule

▸ **createCapsule**(`x`, `y`, `radius`, `height`, `options`, `rotation?`, `maxSides?`): `any`

Creates a new rigid body model with a capsule hull. The options parameter is an object that specifies any properties you wish to override the defaults. See the properties section of the `Matter.Body` module for detailed information on what you can pass via the `options` object.

**`method`** createCapsule

**Parameters**

| Name       | Type                                                              | Default value | Description             |
| ---------- | ----------------------------------------------------------------- | ------------- | ----------------------- |
| `x`        | `number`                                                          | `undefined`   |                         |
| `y`        | `number`                                                          | `undefined`   |                         |
| `radius`   | `number`                                                          | `undefined`   |                         |
| `height`   | `number`                                                          | `undefined`   |                         |
| `options`  | [`I2dPhyBodyData`](../interfaces/m4m.framework.I2dPhyBodyData.md) | `undefined`   | -                       |
| `rotation` | `number`                                                          | `0`           | vertices roate of angle |
| `maxSides` | `number`                                                          | `25`          | -                       |

**Returns**

`any`

A new capsule body

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:425](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L425)

***

#### createCapsuleByPBody

▸ **createCapsuleByPBody**(`pBody`, `maxSides?`): `any`

创建一个新的胶囊体Body

**Parameters**

| Name       | Type                                                              | Default value |
| ---------- | ----------------------------------------------------------------- | ------------- |
| `pBody`    | [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md) | `undefined`   |
| `maxSides` | `number`                                                          | `25`          |

**Returns**

`any`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:296](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L296)

***

#### createCircle

▸ **createCircle**(`x`, `y`, `radius`, `options`, `maxSides`): [`Ibody`](../interfaces/m4m.framework.Ibody.md)

Creates a new rigid body model with a circle hull. The options parameter is an object that specifies any properties you wish to override the defaults. See the properties section of the `Matter.Body` module for detailed information on what you can pass via the `options` object.

**`method`** circle

**Parameters**

| Name       | Type                                                              |
| ---------- | ----------------------------------------------------------------- |
| `x`        | `number`                                                          |
| `y`        | `number`                                                          |
| `radius`   | `number`                                                          |
| `options`  | [`I2dPhyBodyData`](../interfaces/m4m.framework.I2dPhyBodyData.md) |
| `maxSides` | `number`                                                          |

**Returns**

[`Ibody`](../interfaces/m4m.framework.Ibody.md)

A new circle body

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:334](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L334)

***

#### createCircleByPBody

▸ **createCircleByPBody**(`pBody`, `maxSides?`): [`Ibody`](../interfaces/m4m.framework.Ibody.md)

创建一个新的圆形Body

**Parameters**

| Name       | Type                                                              | Default value | Description       |
| ---------- | ----------------------------------------------------------------- | ------------- | ----------------- |
| `pBody`    | [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md) | `undefined`   | I2DPhysicsBody 实例 |
| `maxSides` | `number`                                                          | `25`          | 最大边               |

**Returns**

[`Ibody`](../interfaces/m4m.framework.Ibody.md)

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:259](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L259)

***

#### createFromVertices

▸ **createFromVertices**(`x`, `y`, `vertexSets`, `options`, `flagInternal?`, `removeCollinear?`, `minimumArea?`): [`Ibody`](../interfaces/m4m.framework.Ibody.md)

Creates a body using the supplied vertices (or an array containing multiple sets of vertices). If the vertices are convex, they will pass through as supplied. Otherwise if the vertices are concave, they will be decomposed if [poly-decomp.js](https://github.com/schteppe/poly-decomp.js) is available. Note that this process is not guaranteed to support complex sets of vertices (e.g. those with holes may fail). By default the decomposition will discard collinear edges (to improve performance). It can also optionally discard any parts that have an area less than `minimumArea`. If the vertices can not be decomposed, the result will fall back to using the convex hull. The options parameter is an object that specifies any `Matter.Body` properties you wish to override the defaults. See the properties section of the `Matter.Body` module for detailed information on what you can pass via the `options` object.

**`method`** fromVertices

**Parameters**

| Name              | Type                                                              | Default value |
| ----------------- | ----------------------------------------------------------------- | ------------- |
| `x`               | `number`                                                          | `undefined`   |
| `y`               | `number`                                                          | `undefined`   |
| `vertexSets`      | [`Ivec2`](../interfaces/m4m.math.Ivec2.md)\[]                     | `undefined`   |
| `options`         | [`I2dPhyBodyData`](../interfaces/m4m.framework.I2dPhyBodyData.md) | `undefined`   |
| `flagInternal`    | `boolean`                                                         | `false`       |
| `removeCollinear` | `number`                                                          | `0.01`        |
| `minimumArea`     | `number`                                                          | `10`          |

**Returns**

[`Ibody`](../interfaces/m4m.framework.Ibody.md)

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:407](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L407)

***

#### createPolygon

▸ **createPolygon**(`x`, `y`, `sides`, `radius`, `options`): [`Ibody`](../interfaces/m4m.framework.Ibody.md)

Creates a new rigid body model with a regular polygon hull with the given number of sides. The options parameter is an object that specifies any properties you wish to override the defaults. See the properties section of the `Matter.Body` module for detailed information on what you can pass via the `options` object.

**`method`** polygon

**Parameters**

| Name      | Type                                                              |
| --------- | ----------------------------------------------------------------- |
| `x`       | `number`                                                          |
| `y`       | `number`                                                          |
| `sides`   | `number`                                                          |
| `radius`  | `number`                                                          |
| `options` | [`I2dPhyBodyData`](../interfaces/m4m.framework.I2dPhyBodyData.md) |

**Returns**

[`Ibody`](../interfaces/m4m.framework.Ibody.md)

A new regular polygon body

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:383](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L383)

***

#### createRectByPBody

▸ **createRectByPBody**(`pBody`): [`Ibody`](../interfaces/m4m.framework.Ibody.md)

创建一个新的矩形Body

**Parameters**

| Name    | Type                                                              | Description       |
| ------- | ----------------------------------------------------------------- | ----------------- |
| `pBody` | [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md) | I2DPhysicsBody 实例 |

**Returns**

[`Ibody`](../interfaces/m4m.framework.Ibody.md)

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:241](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L241)

***

#### createRectangle

▸ **createRectangle**(`x`, `y`, `width`, `height`, `options`): [`Ibody`](../interfaces/m4m.framework.Ibody.md)

Creates a new rigid body model with a rectangle hull. The options parameter is an object that specifies any properties you wish to override the defaults. See the properties section of the `Matter.Body` module for detailed information on what you can pass via the `options` object.

**`method`** rectangle

**Parameters**

| Name      | Type                                                              |
| --------- | ----------------------------------------------------------------- |
| `x`       | `number`                                                          |
| `y`       | `number`                                                          |
| `width`   | `number`                                                          |
| `height`  | `number`                                                          |
| `options` | [`I2dPhyBodyData`](../interfaces/m4m.framework.I2dPhyBodyData.md) |

**Returns**

[`Ibody`](../interfaces/m4m.framework.Ibody.md)

A new rectangle body

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:350](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L350)

***

#### createTrapezoid

▸ **createTrapezoid**(`x`, `y`, `width`, `height`, `slope`, `options`): [`Ibody`](../interfaces/m4m.framework.Ibody.md)

Creates a new rigid body model with a trapezoid hull. The options parameter is an object that specifies any properties you wish to override the defaults. See the properties section of the `Matter.Body` module for detailed information on what you can pass via the `options` object.

**`method`** trapezoid

**Parameters**

| Name      | Type                                                              |
| --------- | ----------------------------------------------------------------- |
| `x`       | `number`                                                          |
| `y`       | `number`                                                          |
| `width`   | `number`                                                          |
| `height`  | `number`                                                          |
| `slope`   | `number`                                                          |
| `options` | [`I2dPhyBodyData`](../interfaces/m4m.framework.I2dPhyBodyData.md) |

**Returns**

[`Ibody`](../interfaces/m4m.framework.Ibody.md)

A new trapezoid body

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:367](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L367)

***

#### getBody

▸ **getBody**(`bodyId`): [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md)

获取 I2DPhysicsBody 对象通过 Ibody.id

**Parameters**

| Name     | Type     |
| -------- | -------- |
| `bodyId` | `number` |

**Returns**

[`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md)

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:487](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L487)

***

#### removeBody

▸ **removeBody**(`_Pbody`): `void`

移除 指定 I2DPhysicsBody 实例

**Parameters**

| Name     | Type                                                              |
| -------- | ----------------------------------------------------------------- |
| `_Pbody` | [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md) |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:480](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L480)

***

#### removeEventListener

▸ **removeEventListener**(`eventEnum`, `func`, `thisArg`): `void`

移除事件监听

**Parameters**

| Name        | Type                                                           | Description |
| ----------- | -------------------------------------------------------------- | ----------- |
| `eventEnum` | [`Physic2dEventEnum`](../enums/m4m.event.Physic2dEventEnum.md) | 事件类型        |
| `func`      | (...`args`: `any`\[]) => `void`                                | 事件回调函数      |
| `thisArg`   | `any`                                                          | 函数持有对象      |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:233](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L233)

***

#### setAngle

▸ **setAngle**(`body`, `angle`): `void`

Sets the angle of the body instantly. Angular velocity, position, force etc. are unchanged.

**Parameters**

| Name    | Type                                            | Description |
| ------- | ----------------------------------------------- | ----------- |
| `body`  | [`Ibody`](../interfaces/m4m.framework.Ibody.md) | body        |
| `angle` | `number`                                        | 旋转角度        |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:536](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L536)

***

#### setAngularVelocity

▸ **setAngularVelocity**(`body`, `angularVelocity`): `void`

设置角速度 Sets the angular velocity of the body instantly. Position, angle, force etc. are unchanged. See also `Body.applyForce`.

**Parameters**

| Name              | Type                                            |
| ----------------- | ----------------------------------------------- |
| `body`            | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `angularVelocity` | `number`                                        |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:557](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L557)

***

#### setCentre

▸ **setCentre**(`body`, `centre`, `relative?`): `void`

设置中心点 Set the centre of mass of the body. The `centre` is a vector in world-space unless `relative` is set, in which case it is a translation. The centre of mass is the point the body rotates about and can be used to simulate non-uniform density. This is equal to moving `body.position` but not the `body.vertices`. Invalid if the `centre` falls outside the body's convex hull.

**Parameters**

| Name       | Type                                            | Default value |
| ---------- | ----------------------------------------------- | ------------- |
| `body`     | [`Ibody`](../interfaces/m4m.framework.Ibody.md) | `undefined`   |
| `centre`   | [`Ivec2`](../interfaces/m4m.math.Ivec2.md)      | `undefined`   |
| `relative` | `boolean`                                       | `false`       |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:611](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L611)

***

#### setDensity

▸ **setDensity**(`body`, `Desity`): `void`

设置密度 Sets the density of the body. Mass and inertia are automatically updated to reflect the change.

**Parameters**

| Name     | Type                                            |
| -------- | ----------------------------------------------- |
| `body`   | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `Desity` | `number`                                        |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:549](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L549)

***

#### setGravity

▸ **setGravity**(`x`, `y`): `void`

**Parameters**

| Name | Type     |
| ---- | -------- |
| `x`  | `number` |
| `y`  | `number` |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:504](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L504)

***

#### setInertia

▸ **setInertia**(`body`, `Inertia`): `void`

设置惯性值 Sets the moment of inertia (i.e. second moment of area) of the body. Inverse inertia is automatically updated to reflect the change. Mass is not changed.

**Parameters**

| Name      | Type                                            |
| --------- | ----------------------------------------------- |
| `body`    | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `Inertia` | `number`                                        |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:578](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L578)

***

#### setMass

▸ **setMass**(`body`, `mass`): `void`

设置质量 Sets the mass of the body. Inverse mass, density and inertia are automatically updated to reflect the change.

**Parameters**

| Name   | Type                                            |
| ------ | ----------------------------------------------- |
| `body` | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `mass` | `number`                                        |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:542](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L542)

***

#### setParts

▸ **setParts**(`body`, `parts`, `autoHull?`): `void`

设置成员 Sets the parts of the `body` and updates mass, inertia and centroid. Each part will have its parent set to `body`. By default the convex hull will be automatically computed and set on `body`, unless `autoHull` is set to `false.` Note that this method will ensure that the first part in `body.parts` will always be the `body`.

**Parameters**

| Name       | Type                                               | Default value |
| ---------- | -------------------------------------------------- | ------------- |
| `body`     | [`Ibody`](../interfaces/m4m.framework.Ibody.md)    | `undefined`   |
| `parts`    | [`Ibody`](../interfaces/m4m.framework.Ibody.md)\[] | `undefined`   |
| `autoHull` | `boolean`                                          | `true`        |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:600](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L600)

***

#### setPosition

▸ **setPosition**(`body`, `pos`): `void`

设置位置 Moves a body by a given vector relative to its current position, without imparting any velocity.

**Parameters**

| Name   | Type                                            |
| ------ | ----------------------------------------------- |
| `body` | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `pos`  | [`Ivec2`](../interfaces/m4m.math.Ivec2.md)      |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:527](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L527)

***

#### setScale

▸ **setScale**(`body`, `scaleX`, `scaleY`, `point?`): `void`

设置缩放 Scales the body, including updating physical properties (mass, area, axes, inertia), from a world-space point (default is body centre).

**Parameters**

| Name     | Type                                            | Default value |
| -------- | ----------------------------------------------- | ------------- |
| `body`   | [`Ibody`](../interfaces/m4m.framework.Ibody.md) | `undefined`   |
| `scaleX` | `number`                                        | `undefined`   |
| `scaleY` | `number`                                        | `undefined`   |
| `point`  | [`Ivec2`](../interfaces/m4m.math.Ivec2.md)      | `null`        |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:619](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L619)

***

#### setSleeping

▸ **setSleeping**(`body`, `isSleeping`): `void`

设置休眠状态

**Parameters**

| Name         | Type                                            |
| ------------ | ----------------------------------------------- |
| `body`       | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `isSleeping` | `boolean`                                       |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:570](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L570)

***

#### setStatic

▸ **setStatic**(`body`, `isStatic`): `void`

设置静态状态 Sets the body as static, including isStatic flag and setting mass and inertia to Infinity.

**Parameters**

| Name       | Type                                            |
| ---------- | ----------------------------------------------- |
| `body`     | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `isStatic` | `boolean`                                       |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:564](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L564)

***

#### setVelocity

▸ **setVelocity**(`body`, `velocity`): `void`

设置速度 Sets the linear velocity of the body instantly. Position, angle, force etc. are unchanged. See also `Body.applyForce`.

**Parameters**

| Name       | Type                                            |
| ---------- | ----------------------------------------------- |
| `body`     | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `velocity` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md)      |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:521](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L521)

***

#### setVertices

▸ **setVertices**(`body`, `vertices`): `void`

设置顶点 Sets the body's vertices and updates body properties accordingly, including inertia, area and mass (with respect to `body.density`). Vertices will be automatically transformed to be orientated around their centre of mass as the origin. They are then automatically translated to world space based on `body.position`.

The `vertices` argument should be passed as an array of `Matter.Vector` points (or a `Matter.Vertices` array). Vertices must form a convex hull, concave hulls are not supported.

**Parameters**

| Name       | Type                                            |
| ---------- | ----------------------------------------------- |
| `body`     | [`Ibody`](../interfaces/m4m.framework.Ibody.md) |
| `vertices` | [`Ivec2`](../interfaces/m4m.math.Ivec2.md)\[]   |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:590](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L590)

***

#### update

▸ **update**(`delta`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:187](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L187)

### Accessors

#### Matter

• `get` **Matter**(): `any`

**Returns**

`any`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L46)

***

#### enableSleeping

• `get` **enableSleeping**(): `boolean`

**Returns**

`boolean`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:513](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L513)

• `set` **enableSleeping**(`val`): `void`

**Parameters**

| Name  | Type      |
| ----- | --------- |
| `val` | `boolean` |

**Returns**

`void`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:509](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L509)

### Constructors

#### constructor

• **new physicEngine2D**(`op?`)

**Parameters**

| Name | Type                                                        | Default value |
| ---- | ----------------------------------------------------------- | ------------- |
| `op` | [`IEngine2DOP`](../interfaces/m4m.framework.IEngine2DOP.md) | `null`        |

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L52)

### Properties

#### engineRunner

• **engineRunner**: [`IRunner`](../interfaces/m4m.framework.IRunner.md)

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L49)

***

#### engineWorld

• **engineWorld**: [`IWorld`](../interfaces/m4m.framework.IWorld.md)

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L48)

***

#### matterEngine

• **matterEngine**: `any`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L47)
