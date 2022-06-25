[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / PhysicsJoint

# Class: PhysicsJoint

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).PhysicsJoint

This is a holder class for the physics joint created by the physics plugin.
It holds a set of functions to control the underlying joint.

## Hierarchy

- **`PhysicsJoint`**

  ↳ [`DistanceJoint`](m4m.framework.DistanceJoint.md)

  ↳ [`MotorEnabledJoint`](m4m.framework.MotorEnabledJoint.md)

## Table of contents

### Properties

- [\_physicsPlugin](m4m.framework.PhysicsJoint.md#_physicsplugin)
- [jointData](m4m.framework.PhysicsJoint.md#jointdata)
- [type](m4m.framework.PhysicsJoint.md#type)
- [BallAndSocketJoint](m4m.framework.PhysicsJoint.md#ballandsocketjoint)
- [DistanceJoint](m4m.framework.PhysicsJoint.md#distancejoint)
- [Hinge2Joint](m4m.framework.PhysicsJoint.md#hinge2joint)
- [HingeJoint](m4m.framework.PhysicsJoint.md#hingejoint)
- [LockJoint](m4m.framework.PhysicsJoint.md#lockjoint)
- [PointToPointJoint](m4m.framework.PhysicsJoint.md#pointtopointjoint)
- [PrismaticJoint](m4m.framework.PhysicsJoint.md#prismaticjoint)
- [SliderJoint](m4m.framework.PhysicsJoint.md#sliderjoint)
- [SpringJoint](m4m.framework.PhysicsJoint.md#springjoint)
- [UniversalJoint](m4m.framework.PhysicsJoint.md#universaljoint)
- [WheelJoint](m4m.framework.PhysicsJoint.md#wheeljoint)

### Constructors

- [constructor](m4m.framework.PhysicsJoint.md#constructor)

### Methods

- [executeNativeFunction](m4m.framework.PhysicsJoint.md#executenativefunction)

### Accessors

- [physicsJoint](m4m.framework.PhysicsJoint.md#physicsjoint)
- [physicsPlugin](m4m.framework.PhysicsJoint.md#physicsplugin)

## Properties

### \_physicsPlugin

• `Protected` **\_physicsPlugin**: [`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md)

#### Defined in

[framework/physics3d/physicJoint.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L38)

___

### jointData

• **jointData**: [`PhysicsJointData`](../interfaces/m4m.framework.PhysicsJointData.md)

___

### type

• **type**: `number`

___

### BallAndSocketJoint

▪ `Static` **BallAndSocketJoint**: `number` = `2`

Ball-and-Socket joint type

#### Defined in

[framework/physics3d/physicJoint.ts:85](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L85)

___

### DistanceJoint

▪ `Static` **DistanceJoint**: `number` = `0`

Distance-Joint type

#### Defined in

[framework/physics3d/physicJoint.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L77)

___

### Hinge2Joint

▪ `Static` **Hinge2Joint**: `number` = `PhysicsJoint.WheelJoint`

Hinge-Joint 2 type

#### Defined in

[framework/physics3d/physicJoint.ts:107](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L107)

___

### HingeJoint

▪ `Static` **HingeJoint**: `number` = `1`

Hinge-Joint type

#### Defined in

[framework/physics3d/physicJoint.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L81)

___

### LockJoint

▪ `Static` **LockJoint**: `number` = `10`

Lock-Joint type

#### Defined in

[framework/physics3d/physicJoint.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L121)

___

### PointToPointJoint

▪ `Static` **PointToPointJoint**: `number` = `8`

Point to Point Joint type.  Similar to a Ball-Joint.  Different in parameters

#### Defined in

[framework/physics3d/physicJoint.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L112)

___

### PrismaticJoint

▪ `Static` **PrismaticJoint**: `number` = `5`

Prismatic-Joint type

#### Defined in

[framework/physics3d/physicJoint.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L98)

___

### SliderJoint

▪ `Static` **SliderJoint**: `number` = `4`

Slider-Joint type

#### Defined in

[framework/physics3d/physicJoint.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L93)

___

### SpringJoint

▪ `Static` **SpringJoint**: `number` = `9`

Spring-Joint type

#### Defined in

[framework/physics3d/physicJoint.ts:117](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L117)

___

### UniversalJoint

▪ `Static` **UniversalJoint**: `number` = `6`

Universal-Joint type

#### Defined in

[framework/physics3d/physicJoint.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L103)

___

### WheelJoint

▪ `Static` **WheelJoint**: `number` = `3`

Wheel-Joint type

#### Defined in

[framework/physics3d/physicJoint.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L89)

## Constructors

### constructor

• **new PhysicsJoint**(`type`, `jointData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `number` |
| `jointData` | [`PhysicsJointData`](../interfaces/m4m.framework.PhysicsJointData.md) |

#### Defined in

[framework/physics3d/physicJoint.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L40)

## Methods

### executeNativeFunction

▸ **executeNativeFunction**(`func`): `void`

Execute a function that is physics-plugin specific.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `func` | (`world`: `any`, `physicsJoint`: `any`) => `void` | the function that will be executed.                        It accepts two parameters: the physics world and the physics joint. |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicJoint.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L66)

## Accessors

### physicsJoint

• `get` **physicsJoint**(): `any`

#### Returns

`any`

#### Defined in

[framework/physics3d/physicJoint.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L44)

• `set` **physicsJoint**(`newJoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `newJoint` | `any` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicJoint.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L48)

___

### physicsPlugin

• `set` **physicsPlugin**(`physicsPlugin`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `physicsPlugin` | [`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md) |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicJoint.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L57)
