# m4m.framework.DistanceJoint

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / DistanceJoint

## Class: DistanceJoint

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).DistanceJoint

A class representing a physics distance joint.

### Hierarchy

*   [`PhysicsJoint`](m4m.framework.PhysicsJoint.md)

    ↳ **`DistanceJoint`**

### Table of contents

#### Properties

* [\_physicsPlugin](m4m.framework.DistanceJoint.md#\_physicsplugin)
* [jointData](m4m.framework.DistanceJoint.md#jointdata)
* [type](m4m.framework.DistanceJoint.md#type)
* [BallAndSocketJoint](m4m.framework.DistanceJoint.md#ballandsocketjoint)
* [DistanceJoint](m4m.framework.DistanceJoint.md#distancejoint)
* [Hinge2Joint](m4m.framework.DistanceJoint.md#hinge2joint)
* [HingeJoint](m4m.framework.DistanceJoint.md#hingejoint)
* [LockJoint](m4m.framework.DistanceJoint.md#lockjoint)
* [PointToPointJoint](m4m.framework.DistanceJoint.md#pointtopointjoint)
* [PrismaticJoint](m4m.framework.DistanceJoint.md#prismaticjoint)
* [SliderJoint](m4m.framework.DistanceJoint.md#sliderjoint)
* [SpringJoint](m4m.framework.DistanceJoint.md#springjoint)
* [UniversalJoint](m4m.framework.DistanceJoint.md#universaljoint)
* [WheelJoint](m4m.framework.DistanceJoint.md#wheeljoint)

#### Constructors

* [constructor](m4m.framework.DistanceJoint.md#constructor)

#### Methods

* [executeNativeFunction](m4m.framework.DistanceJoint.md#executenativefunction)
* [updateDistance](m4m.framework.DistanceJoint.md#updatedistance)

#### Accessors

* [physicsJoint](m4m.framework.DistanceJoint.md#physicsjoint)
* [physicsPlugin](m4m.framework.DistanceJoint.md#physicsplugin)

### Properties

#### \_physicsPlugin

• `Protected` **\_physicsPlugin**: [`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md)

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[\_physicsPlugin](m4m.framework.PhysicsJoint.md#\_physicsplugin)

**Defined in**

[framework/physics3d/physicJoint.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L38)

***

#### jointData

• **jointData**: [`PhysicsJointData`](../interfaces/m4m.framework.PhysicsJointData.md)

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[jointData](m4m.framework.PhysicsJoint.md#jointdata)

***

#### type

• **type**: `number`

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[type](m4m.framework.PhysicsJoint.md#type)

***

#### BallAndSocketJoint

▪ `Static` **BallAndSocketJoint**: `number` = `2`

Ball-and-Socket joint type

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[BallAndSocketJoint](m4m.framework.PhysicsJoint.md#ballandsocketjoint)

**Defined in**

[framework/physics3d/physicJoint.ts:85](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L85)

***

#### DistanceJoint

▪ `Static` **DistanceJoint**: `number` = `0`

Distance-Joint type

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[DistanceJoint](m4m.framework.PhysicsJoint.md#distancejoint)

**Defined in**

[framework/physics3d/physicJoint.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L77)

***

#### Hinge2Joint

▪ `Static` **Hinge2Joint**: `number` = `PhysicsJoint.WheelJoint`

Hinge-Joint 2 type

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[Hinge2Joint](m4m.framework.PhysicsJoint.md#hinge2joint)

**Defined in**

[framework/physics3d/physicJoint.ts:107](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L107)

***

#### HingeJoint

▪ `Static` **HingeJoint**: `number` = `1`

Hinge-Joint type

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[HingeJoint](m4m.framework.PhysicsJoint.md#hingejoint)

**Defined in**

[framework/physics3d/physicJoint.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L81)

***

#### LockJoint

▪ `Static` **LockJoint**: `number` = `10`

Lock-Joint type

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[LockJoint](m4m.framework.PhysicsJoint.md#lockjoint)

**Defined in**

[framework/physics3d/physicJoint.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L121)

***

#### PointToPointJoint

▪ `Static` **PointToPointJoint**: `number` = `8`

Point to Point Joint type. Similar to a Ball-Joint. Different in parameters

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[PointToPointJoint](m4m.framework.PhysicsJoint.md#pointtopointjoint)

**Defined in**

[framework/physics3d/physicJoint.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L112)

***

#### PrismaticJoint

▪ `Static` **PrismaticJoint**: `number` = `5`

Prismatic-Joint type

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[PrismaticJoint](m4m.framework.PhysicsJoint.md#prismaticjoint)

**Defined in**

[framework/physics3d/physicJoint.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L98)

***

#### SliderJoint

▪ `Static` **SliderJoint**: `number` = `4`

Slider-Joint type

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[SliderJoint](m4m.framework.PhysicsJoint.md#sliderjoint)

**Defined in**

[framework/physics3d/physicJoint.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L93)

***

#### SpringJoint

▪ `Static` **SpringJoint**: `number` = `9`

Spring-Joint type

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[SpringJoint](m4m.framework.PhysicsJoint.md#springjoint)

**Defined in**

[framework/physics3d/physicJoint.ts:117](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L117)

***

#### UniversalJoint

▪ `Static` **UniversalJoint**: `number` = `6`

Universal-Joint type

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[UniversalJoint](m4m.framework.PhysicsJoint.md#universaljoint)

**Defined in**

[framework/physics3d/physicJoint.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L103)

***

#### WheelJoint

▪ `Static` **WheelJoint**: `number` = `3`

Wheel-Joint type

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[WheelJoint](m4m.framework.PhysicsJoint.md#wheeljoint)

**Defined in**

[framework/physics3d/physicJoint.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L89)

### Constructors

#### constructor

• **new DistanceJoint**(`jointData`)

**Parameters**

| Name        | Type                                                                    |
| ----------- | ----------------------------------------------------------------------- |
| `jointData` | [`DistanceJointData`](../interfaces/m4m.framework.DistanceJointData.md) |

**Overrides**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[constructor](m4m.framework.PhysicsJoint.md#constructor)

**Defined in**

[framework/physics3d/physicJoint.ts:128](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L128)

### Methods

#### executeNativeFunction

▸ **executeNativeFunction**(`func`): `void`

Execute a function that is physics-plugin specific.

**Parameters**

| Name   | Type                                              | Description                                                                                             |
| ------ | ------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| `func` | (`world`: `any`, `physicsJoint`: `any`) => `void` | the function that will be executed. It accepts two parameters: the physics world and the physics joint. |

**Returns**

`void`

**Inherited from**

[PhysicsJoint](m4m.framework.PhysicsJoint.md).[executeNativeFunction](m4m.framework.PhysicsJoint.md#executenativefunction)

**Defined in**

[framework/physics3d/physicJoint.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L66)

***

#### updateDistance

▸ **updateDistance**(`maxDistance`, `minDistance?`): `void`

Update the predefined distance.

**Parameters**

| Name           | Type     |
| -------------- | -------- |
| `maxDistance`  | `number` |
| `minDistance?` | `number` |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicJoint.ts:135](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L135)

### Accessors

#### physicsJoint

• `get` **physicsJoint**(): `any`

**Returns**

`any`

**Inherited from**

PhysicsJoint.physicsJoint

**Defined in**

[framework/physics3d/physicJoint.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L44)

• `set` **physicsJoint**(`newJoint`): `void`

**Parameters**

| Name       | Type  |
| ---------- | ----- |
| `newJoint` | `any` |

**Returns**

`void`

**Inherited from**

PhysicsJoint.physicsJoint

**Defined in**

[framework/physics3d/physicJoint.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L48)

***

#### physicsPlugin

• `set` **physicsPlugin**(`physicsPlugin`): `void`

**Parameters**

| Name            | Type                                                                          |
| --------------- | ----------------------------------------------------------------------------- |
| `physicsPlugin` | [`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md) |

**Returns**

`void`

**Inherited from**

PhysicsJoint.physicsPlugin

**Defined in**

[framework/physics3d/physicJoint.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L57)
