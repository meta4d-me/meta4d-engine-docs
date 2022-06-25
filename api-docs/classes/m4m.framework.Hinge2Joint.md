[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / Hinge2Joint

# Class: Hinge2Joint

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).Hinge2Joint

This class represents a dual hinge physics joint (same as wheel joint)

## Hierarchy

- [`MotorEnabledJoint`](m4m.framework.MotorEnabledJoint.md)

  ↳ **`Hinge2Joint`**

## Table of contents

### Properties

- [\_physicsPlugin](m4m.framework.Hinge2Joint.md#_physicsplugin)
- [jointData](m4m.framework.Hinge2Joint.md#jointdata)
- [type](m4m.framework.Hinge2Joint.md#type)
- [BallAndSocketJoint](m4m.framework.Hinge2Joint.md#ballandsocketjoint)
- [DistanceJoint](m4m.framework.Hinge2Joint.md#distancejoint)
- [Hinge2Joint](m4m.framework.Hinge2Joint.md#hinge2joint)
- [HingeJoint](m4m.framework.Hinge2Joint.md#hingejoint)
- [LockJoint](m4m.framework.Hinge2Joint.md#lockjoint)
- [PointToPointJoint](m4m.framework.Hinge2Joint.md#pointtopointjoint)
- [PrismaticJoint](m4m.framework.Hinge2Joint.md#prismaticjoint)
- [SliderJoint](m4m.framework.Hinge2Joint.md#sliderjoint)
- [SpringJoint](m4m.framework.Hinge2Joint.md#springjoint)
- [UniversalJoint](m4m.framework.Hinge2Joint.md#universaljoint)
- [WheelJoint](m4m.framework.Hinge2Joint.md#wheeljoint)

### Constructors

- [constructor](m4m.framework.Hinge2Joint.md#constructor)

### Methods

- [executeNativeFunction](m4m.framework.Hinge2Joint.md#executenativefunction)
- [setLimit](m4m.framework.Hinge2Joint.md#setlimit)
- [setMotor](m4m.framework.Hinge2Joint.md#setmotor)

### Accessors

- [physicsJoint](m4m.framework.Hinge2Joint.md#physicsjoint)
- [physicsPlugin](m4m.framework.Hinge2Joint.md#physicsplugin)

## Properties

### \_physicsPlugin

• `Protected` **\_physicsPlugin**: [`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md)

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[_physicsPlugin](m4m.framework.MotorEnabledJoint.md#_physicsplugin)

#### Defined in

[framework/physics3d/physicJoint.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L38)

___

### jointData

• **jointData**: [`PhysicsJointData`](../interfaces/m4m.framework.PhysicsJointData.md)

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[jointData](m4m.framework.MotorEnabledJoint.md#jointdata)

___

### type

• **type**: `number`

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[type](m4m.framework.MotorEnabledJoint.md#type)

___

### BallAndSocketJoint

▪ `Static` **BallAndSocketJoint**: `number` = `2`

Ball-and-Socket joint type

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[BallAndSocketJoint](m4m.framework.MotorEnabledJoint.md#ballandsocketjoint)

#### Defined in

[framework/physics3d/physicJoint.ts:85](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L85)

___

### DistanceJoint

▪ `Static` **DistanceJoint**: `number` = `0`

Distance-Joint type

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[DistanceJoint](m4m.framework.MotorEnabledJoint.md#distancejoint)

#### Defined in

[framework/physics3d/physicJoint.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L77)

___

### Hinge2Joint

▪ `Static` **Hinge2Joint**: `number` = `PhysicsJoint.WheelJoint`

Hinge-Joint 2 type

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[Hinge2Joint](m4m.framework.MotorEnabledJoint.md#hinge2joint)

#### Defined in

[framework/physics3d/physicJoint.ts:107](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L107)

___

### HingeJoint

▪ `Static` **HingeJoint**: `number` = `1`

Hinge-Joint type

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[HingeJoint](m4m.framework.MotorEnabledJoint.md#hingejoint)

#### Defined in

[framework/physics3d/physicJoint.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L81)

___

### LockJoint

▪ `Static` **LockJoint**: `number` = `10`

Lock-Joint type

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[LockJoint](m4m.framework.MotorEnabledJoint.md#lockjoint)

#### Defined in

[framework/physics3d/physicJoint.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L121)

___

### PointToPointJoint

▪ `Static` **PointToPointJoint**: `number` = `8`

Point to Point Joint type.  Similar to a Ball-Joint.  Different in parameters

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[PointToPointJoint](m4m.framework.MotorEnabledJoint.md#pointtopointjoint)

#### Defined in

[framework/physics3d/physicJoint.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L112)

___

### PrismaticJoint

▪ `Static` **PrismaticJoint**: `number` = `5`

Prismatic-Joint type

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[PrismaticJoint](m4m.framework.MotorEnabledJoint.md#prismaticjoint)

#### Defined in

[framework/physics3d/physicJoint.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L98)

___

### SliderJoint

▪ `Static` **SliderJoint**: `number` = `4`

Slider-Joint type

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[SliderJoint](m4m.framework.MotorEnabledJoint.md#sliderjoint)

#### Defined in

[framework/physics3d/physicJoint.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L93)

___

### SpringJoint

▪ `Static` **SpringJoint**: `number` = `9`

Spring-Joint type

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[SpringJoint](m4m.framework.MotorEnabledJoint.md#springjoint)

#### Defined in

[framework/physics3d/physicJoint.ts:117](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L117)

___

### UniversalJoint

▪ `Static` **UniversalJoint**: `number` = `6`

Universal-Joint type

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[UniversalJoint](m4m.framework.MotorEnabledJoint.md#universaljoint)

#### Defined in

[framework/physics3d/physicJoint.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L103)

___

### WheelJoint

▪ `Static` **WheelJoint**: `number` = `3`

Wheel-Joint type

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[WheelJoint](m4m.framework.MotorEnabledJoint.md#wheeljoint)

#### Defined in

[framework/physics3d/physicJoint.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L89)

## Constructors

### constructor

• **new Hinge2Joint**(`jointData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `jointData` | [`PhysicsJointData`](../interfaces/m4m.framework.PhysicsJointData.md) |

#### Overrides

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[constructor](m4m.framework.MotorEnabledJoint.md#constructor)

#### Defined in

[framework/physics3d/physicJoint.ts:201](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L201)

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

#### Inherited from

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[executeNativeFunction](m4m.framework.MotorEnabledJoint.md#executenativefunction)

#### Defined in

[framework/physics3d/physicJoint.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L66)

___

### setLimit

▸ **setLimit**(`upperLimit`, `lowerLimit?`, `motorIndex?`): `void`

Set the motor limits.
Attention, this function is plugin specific. Engines won't react 100% the same.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `upperLimit` | `number` | `undefined` | the upper limit |
| `lowerLimit?` | `number` | `undefined` | lower limit |
| `motorIndex` | `number` | `0` | - |

#### Returns

`void`

#### Overrides

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[setLimit](m4m.framework.MotorEnabledJoint.md#setlimit)

#### Defined in

[framework/physics3d/physicJoint.ts:223](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L223)

___

### setMotor

▸ **setMotor**(`force?`, `maxForce?`, `motorIndex?`): `void`

Set the motor values.
Attention, this function is plugin specific. Engines won't react 100% the same.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `force?` | `number` | `undefined` | the force to apply |
| `maxForce?` | `number` | `undefined` | max force for this motor. |
| `motorIndex` | `number` | `0` | - |

#### Returns

`void`

#### Overrides

[MotorEnabledJoint](m4m.framework.MotorEnabledJoint.md).[setMotor](m4m.framework.MotorEnabledJoint.md#setmotor)

#### Defined in

[framework/physics3d/physicJoint.ts:212](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L212)

## Accessors

### physicsJoint

• `get` **physicsJoint**(): `any`

#### Returns

`any`

#### Inherited from

MotorEnabledJoint.physicsJoint

#### Defined in

[framework/physics3d/physicJoint.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L44)

• `set` **physicsJoint**(`newJoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `newJoint` | `any` |

#### Returns

`void`

#### Inherited from

MotorEnabledJoint.physicsJoint

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

#### Inherited from

MotorEnabledJoint.physicsPlugin

#### Defined in

[framework/physics3d/physicJoint.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L57)
