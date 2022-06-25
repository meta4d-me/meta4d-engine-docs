[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / CannonJSPlugin

# Class: CannonJSPlugin

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).CannonJSPlugin

## Implements

- [`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md)

## Table of contents

### Properties

- [BJSCANNON](m4m.framework.CannonJSPlugin.md#bjscannon)
- [name](m4m.framework.CannonJSPlugin.md#name)
- [world](m4m.framework.CannonJSPlugin.md#world)

### Methods

- [applyForce](m4m.framework.CannonJSPlugin.md#applyforce)
- [applyImpulse](m4m.framework.CannonJSPlugin.md#applyimpulse)
- [dispose](m4m.framework.CannonJSPlugin.md#dispose)
- [executeStep](m4m.framework.CannonJSPlugin.md#executestep)
- [generateJoint](m4m.framework.CannonJSPlugin.md#generatejoint)
- [generatePhysicsBody](m4m.framework.CannonJSPlugin.md#generatephysicsbody)
- [getAngularVelocity](m4m.framework.CannonJSPlugin.md#getangularvelocity)
- [getBodyFriction](m4m.framework.CannonJSPlugin.md#getbodyfriction)
- [getBodyMass](m4m.framework.CannonJSPlugin.md#getbodymass)
- [getBodyRestitution](m4m.framework.CannonJSPlugin.md#getbodyrestitution)
- [getBoxSizeToRef](m4m.framework.CannonJSPlugin.md#getboxsizetoref)
- [getLinearVelocity](m4m.framework.CannonJSPlugin.md#getlinearvelocity)
- [getRadius](m4m.framework.CannonJSPlugin.md#getradius)
- [getTimeStep](m4m.framework.CannonJSPlugin.md#gettimestep)
- [isSleeping](m4m.framework.CannonJSPlugin.md#issleeping)
- [isSupported](m4m.framework.CannonJSPlugin.md#issupported)
- [removeJoint](m4m.framework.CannonJSPlugin.md#removejoint)
- [removePhysicsBody](m4m.framework.CannonJSPlugin.md#removephysicsbody)
- [setAngularVelocity](m4m.framework.CannonJSPlugin.md#setangularvelocity)
- [setBodyFriction](m4m.framework.CannonJSPlugin.md#setbodyfriction)
- [setBodyMass](m4m.framework.CannonJSPlugin.md#setbodymass)
- [setBodyRestitution](m4m.framework.CannonJSPlugin.md#setbodyrestitution)
- [setGravity](m4m.framework.CannonJSPlugin.md#setgravity)
- [setLimit](m4m.framework.CannonJSPlugin.md#setlimit)
- [setLinearVelocity](m4m.framework.CannonJSPlugin.md#setlinearvelocity)
- [setMotor](m4m.framework.CannonJSPlugin.md#setmotor)
- [setPhysicsBodyTransformation](m4m.framework.CannonJSPlugin.md#setphysicsbodytransformation)
- [setTimeStep](m4m.framework.CannonJSPlugin.md#settimestep)
- [setTransformationFromPhysicsBody](m4m.framework.CannonJSPlugin.md#settransformationfromphysicsbody)
- [sleepBody](m4m.framework.CannonJSPlugin.md#sleepbody)
- [updateDistanceJoint](m4m.framework.CannonJSPlugin.md#updatedistancejoint)
- [wakeUpBody](m4m.framework.CannonJSPlugin.md#wakeupbody)

### Constructors

- [constructor](m4m.framework.CannonJSPlugin.md#constructor)

## Properties

### BJSCANNON

• **BJSCANNON**: `any`

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L9)

___

### name

• **name**: `string` = `"CannonJSPlugin"`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[name](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#name)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L11)

___

### world

• **world**: `any`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[world](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#world)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L10)

## Methods

### applyForce

▸ **applyForce**(`impostor`, `force`, `contactPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `force` | `vector3` |
| `contactPoint` | `vector3` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[applyForce](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#applyforce)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L64)

___

### applyImpulse

▸ **applyImpulse**(`impostor`, `force`, `contactPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `force` | `vector3` |
| `contactPoint` | `vector3` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[applyImpulse](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#applyimpulse)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L56)

___

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[dispose](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#dispose)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:708](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L708)

___

### executeStep

▸ **executeStep**(`delta`, `impostors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |
| `impostors` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)[] |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[executeStep](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#executestep)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L50)

___

### generateJoint

▸ **generateJoint**(`impostorJoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostorJoint` | [`PhysicsImpostorJoint`](../interfaces/m4m.framework.PhysicsImpostorJoint.md) |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[generateJoint](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#generatejoint)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:180](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L180)

___

### generatePhysicsBody

▸ **generatePhysicsBody**(`impostor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[generatePhysicsBody](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#generatephysicsbody)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L72)

___

### getAngularVelocity

▸ **getAngularVelocity**(`impostor`): `vector3`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`vector3`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getAngularVelocity](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getangularvelocity)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:586](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L586)

___

### getBodyFriction

▸ **getBodyFriction**(`impostor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`number`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getBodyFriction](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getbodyfriction)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:607](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L607)

___

### getBodyMass

▸ **getBodyMass**(`impostor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`number`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getBodyMass](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getbodymass)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:602](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L602)

___

### getBodyRestitution

▸ **getBodyRestitution**(`impostor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`number`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getBodyRestitution](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getbodyrestitution)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:617](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L617)

___

### getBoxSizeToRef

▸ **getBoxSizeToRef**(`impostor`, `result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `result` | `vector3` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getBoxSizeToRef](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getboxsizetoref)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:700](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L700)

___

### getLinearVelocity

▸ **getLinearVelocity**(`impostor`): `vector3`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`vector3`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getLinearVelocity](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getlinearvelocity)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:577](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L577)

___

### getRadius

▸ **getRadius**(`impostor`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`number`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getRadius](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getradius)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:694](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L694)

___

### getTimeStep

▸ **getTimeStep**(): `number`

#### Returns

`number`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getTimeStep](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#gettimestep)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L45)

___

### isSleeping

▸ **isSleeping**(`impostor`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`boolean`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[isSleeping](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#issleeping)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:632](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L632)

___

### isSupported

▸ **isSupported**(): `boolean`

#### Returns

`boolean`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[isSupported](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#issupported)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:562](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L562)

___

### removeJoint

▸ **removeJoint**(`impostorJoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostorJoint` | [`PhysicsImpostorJoint`](../interfaces/m4m.framework.PhysicsImpostorJoint.md) |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[removeJoint](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#removejoint)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:243](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L243)

___

### removePhysicsBody

▸ **removePhysicsBody**(`impostor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[removePhysicsBody](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#removephysicsbody)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:172](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L172)

___

### setAngularVelocity

▸ **setAngularVelocity**(`impostor`, `velocity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `velocity` | `vector3` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setAngularVelocity](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setangularvelocity)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:572](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L572)

___

### setBodyFriction

▸ **setBodyFriction**(`impostor`, `friction`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `friction` | `number` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setBodyFriction](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setbodyfriction)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:612](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L612)

___

### setBodyMass

▸ **setBodyMass**(`impostor`, `mass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `mass` | `number` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setBodyMass](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setbodymass)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:596](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L596)

___

### setBodyRestitution

▸ **setBodyRestitution**(`impostor`, `restitution`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `restitution` | `number` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setBodyRestitution](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setbodyrestitution)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:622](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L622)

___

### setGravity

▸ **setGravity**(`gravity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `gravity` | `vector3` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setGravity](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setgravity)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L35)

___

### setLimit

▸ **setLimit**(`joint`, `upperLimit`, `lowerLimit?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `joint` | [`IMotorEnabledJoint`](../interfaces/m4m.framework.IMotorEnabledJoint.md) |
| `upperLimit` | `number` |
| `lowerLimit?` | `number` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setLimit](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setlimit)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:673](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L673)

___

### setLinearVelocity

▸ **setLinearVelocity**(`impostor`, `velocity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `velocity` | `vector3` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setLinearVelocity](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setlinearvelocity)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:567](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L567)

___

### setMotor

▸ **setMotor**(`joint`, `speed?`, `maxForce?`, `motorIndex?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `joint` | [`IMotorEnabledJoint`](../interfaces/m4m.framework.IMotorEnabledJoint.md) |
| `speed?` | `number` |
| `maxForce?` | `number` |
| `motorIndex?` | `number` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setMotor](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setmotor)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:660](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L660)

___

### setPhysicsBodyTransformation

▸ **setPhysicsBodyTransformation**(`impostor`, `newPosition`, `newRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `newPosition` | `vector3` |
| `newRotation` | `vector3` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setPhysicsBodyTransformation](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setphysicsbodytransformation)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:556](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L556)

___

### setTimeStep

▸ **setTimeStep**(`timeStep`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `timeStep` | `number` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setTimeStep](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#settimestep)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L40)

___

### setTransformationFromPhysicsBody

▸ **setTransformationFromPhysicsBody**(`impostor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setTransformationFromPhysicsBody](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#settransformationfromphysicsbody)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:545](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L545)

___

### sleepBody

▸ **sleepBody**(`impostor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[sleepBody](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#sleepbody)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:627](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L627)

___

### updateDistanceJoint

▸ **updateDistanceJoint**(`joint`, `maxDistance`, `minDistance?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `joint` | [`PhysicsJoint`](m4m.framework.PhysicsJoint.md) |
| `maxDistance` | `number` |
| `minDistance?` | `number` |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[updateDistanceJoint](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#updatedistancejoint)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:643](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L643)

___

### wakeUpBody

▸ **wakeUpBody**(`impostor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`void`

#### Implementation of

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[wakeUpBody](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#wakeupbody)

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:638](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L638)

## Constructors

### constructor

• **new CannonJSPlugin**(`_useDeltaForWorldStep?`, `iterations?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `_useDeltaForWorldStep` | `boolean` | `true` |
| `iterations` | `number` | `10` |

#### Defined in

[framework/physics3d/cannonJSPlugin.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/cannonJSPlugin.ts#L20)
