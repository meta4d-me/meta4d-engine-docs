# m4m.framework.OimoJSPlugin

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / OimoJSPlugin

## Class: OimoJSPlugin

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).OimoJSPlugin

OimoJS physic engine Plugin

### Implements

* [`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md)

### Table of contents

#### Properties

* [BJSOIMO](m4m.framework.OimoJSPlugin.md#bjsoimo)
* [name](m4m.framework.OimoJSPlugin.md#name)
* [world](m4m.framework.OimoJSPlugin.md#world)

#### Methods

* [applyForce](m4m.framework.OimoJSPlugin.md#applyforce)
* [applyImpulse](m4m.framework.OimoJSPlugin.md#applyimpulse)
* [dispose](m4m.framework.OimoJSPlugin.md#dispose)
* [executeStep](m4m.framework.OimoJSPlugin.md#executestep)
* [generateJoint](m4m.framework.OimoJSPlugin.md#generatejoint)
* [generatePhysicsBody](m4m.framework.OimoJSPlugin.md#generatephysicsbody)
* [getAngularVelocity](m4m.framework.OimoJSPlugin.md#getangularvelocity)
* [getBodyFriction](m4m.framework.OimoJSPlugin.md#getbodyfriction)
* [getBodyMass](m4m.framework.OimoJSPlugin.md#getbodymass)
* [getBodyRestitution](m4m.framework.OimoJSPlugin.md#getbodyrestitution)
* [getBoxSizeToRef](m4m.framework.OimoJSPlugin.md#getboxsizetoref)
* [getLinearVelocity](m4m.framework.OimoJSPlugin.md#getlinearvelocity)
* [getRadius](m4m.framework.OimoJSPlugin.md#getradius)
* [getTimeStep](m4m.framework.OimoJSPlugin.md#gettimestep)
* [isSleeping](m4m.framework.OimoJSPlugin.md#issleeping)
* [isSupported](m4m.framework.OimoJSPlugin.md#issupported)
* [removeJoint](m4m.framework.OimoJSPlugin.md#removejoint)
* [removePhysicsBody](m4m.framework.OimoJSPlugin.md#removephysicsbody)
* [setAngularVelocity](m4m.framework.OimoJSPlugin.md#setangularvelocity)
* [setBodyFriction](m4m.framework.OimoJSPlugin.md#setbodyfriction)
* [setBodyMass](m4m.framework.OimoJSPlugin.md#setbodymass)
* [setBodyRestitution](m4m.framework.OimoJSPlugin.md#setbodyrestitution)
* [setGravity](m4m.framework.OimoJSPlugin.md#setgravity)
* [setLimit](m4m.framework.OimoJSPlugin.md#setlimit)
* [setLinearVelocity](m4m.framework.OimoJSPlugin.md#setlinearvelocity)
* [setMotor](m4m.framework.OimoJSPlugin.md#setmotor)
* [setPhysicsBodyTransformation](m4m.framework.OimoJSPlugin.md#setphysicsbodytransformation)
* [setTimeStep](m4m.framework.OimoJSPlugin.md#settimestep)
* [setTransformationFromPhysicsBody](m4m.framework.OimoJSPlugin.md#settransformationfromphysicsbody)
* [sleepBody](m4m.framework.OimoJSPlugin.md#sleepbody)
* [updateDistanceJoint](m4m.framework.OimoJSPlugin.md#updatedistancejoint)
* [wakeUpBody](m4m.framework.OimoJSPlugin.md#wakeupbody)

#### Constructors

* [constructor](m4m.framework.OimoJSPlugin.md#constructor)

### Properties

#### BJSOIMO

• **BJSOIMO**: `any`

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L10)

***

#### name

• **name**: `string` = `"OIMOJSPlugin"`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[name](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#name)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L7)

***

#### world

• **world**: `any`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[world](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#world)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L6)

### Methods

#### applyForce

▸ **applyForce**(`impostor`, `force`, `contactPoint`): `void`

**Parameters**

| Name           | Type                                                  |
| -------------- | ----------------------------------------------------- |
| `impostor`     | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `force`        | `vector3`                                             |
| `contactPoint` | `vector3`                                             |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[applyForce](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#applyforce)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:107](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L107)

***

#### applyImpulse

▸ **applyImpulse**(`impostor`, `force`, `contactPoint`): `void`

申请 冲量

**Parameters**

| Name           | Type                                                  |
| -------------- | ----------------------------------------------------- |
| `impostor`     | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `force`        | `vector3`                                             |
| `contactPoint` | `vector3`                                             |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[applyImpulse](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#applyimpulse)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L98)

***

#### dispose

▸ **dispose**(): `void`

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[dispose](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#dispose)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:516](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L516)

***

#### executeStep

▸ **executeStep**(`delta`, `impostors`): `void`

**Parameters**

| Name        | Type                                                     |
| ----------- | -------------------------------------------------------- |
| `delta`     | `number`                                                 |
| `impostors` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)\[] |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[executeStep](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#executestep)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:60](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L60)

***

#### generateJoint

▸ **generateJoint**(`impostorJoint`): `void`

**Parameters**

| Name            | Type                                                                          |
| --------------- | ----------------------------------------------------------------------------- |
| `impostorJoint` | [`PhysicsImpostorJoint`](../interfaces/m4m.framework.PhysicsImpostorJoint.md) |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[generateJoint](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#generatejoint)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:303](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L303)

***

#### generatePhysicsBody

▸ **generatePhysicsBody**(`impostor`): `void`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[generatePhysicsBody](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#generatephysicsbody)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L116)

***

#### getAngularVelocity

▸ **getAngularVelocity**(`impostor`): `vector3`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`vector3`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getAngularVelocity](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getangularvelocity)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:413](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L413)

***

#### getBodyFriction

▸ **getBodyFriction**(`impostor`): `number`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`number`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getBodyFriction](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getbodyfriction)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:433](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L433)

***

#### getBodyMass

▸ **getBodyMass**(`impostor`): `number`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`number`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getBodyMass](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getbodymass)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:429](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L429)

***

#### getBodyRestitution

▸ **getBodyRestitution**(`impostor`): `number`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`number`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getBodyRestitution](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getbodyrestitution)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:441](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L441)

***

#### getBoxSizeToRef

▸ **getBoxSizeToRef**(`impostor`, `result`): `void`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `result`   | `vector3`                                             |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getBoxSizeToRef](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getboxsizetoref)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:509](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L509)

***

#### getLinearVelocity

▸ **getLinearVelocity**(`impostor`): `vector3`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`vector3`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getLinearVelocity](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getlinearvelocity)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:406](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L406)

***

#### getRadius

▸ **getRadius**(`impostor`): `number`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`number`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getRadius](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#getradius)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:505](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L505)

***

#### getTimeStep

▸ **getTimeStep**(): `number`

**Returns**

`number`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[getTimeStep](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#gettimestep)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L54)

***

#### isSleeping

▸ **isSleeping**(`impostor`): `any`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`any`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[isSleeping](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#issleeping)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:453](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L453)

***

#### isSupported

▸ **isSupported**(): `boolean`

**Returns**

`boolean`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[isSupported](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#issupported)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:394](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L394)

***

#### removeJoint

▸ **removeJoint**(`impostorJoint`): `void`

**Parameters**

| Name            | Type                                                                          |
| --------------- | ----------------------------------------------------------------------------- |
| `impostorJoint` | [`PhysicsImpostorJoint`](../interfaces/m4m.framework.PhysicsImpostorJoint.md) |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[removeJoint](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#removejoint)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:364](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L364)

***

#### removePhysicsBody

▸ **removePhysicsBody**(`impostor`): `void`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[removePhysicsBody](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#removephysicsbody)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:296](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L296)

***

#### setAngularVelocity

▸ **setAngularVelocity**(`impostor`, `velocity`): `void`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `velocity` | `vector3`                                             |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setAngularVelocity](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setangularvelocity)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:402](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L402)

***

#### setBodyFriction

▸ **setBodyFriction**(`impostor`, `friction`): `void`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `friction` | `number`                                              |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setBodyFriction](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setbodyfriction)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:437](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L437)

***

#### setBodyMass

▸ **setBodyMass**(`impostor`, `mass`): `void`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `mass`     | `number`                                              |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setBodyMass](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setbodymass)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:421](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L421)

***

#### setBodyRestitution

▸ **setBodyRestitution**(`impostor`, `restitution`): `void`

**Parameters**

| Name          | Type                                                  |
| ------------- | ----------------------------------------------------- |
| `impostor`    | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `restitution` | `number`                                              |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setBodyRestitution](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setbodyrestitution)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:445](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L445)

***

#### setGravity

▸ **setGravity**(`gravity`): `void`

**Parameters**

| Name      | Type      |
| --------- | --------- |
| `gravity` | `vector3` |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setGravity](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setgravity)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L46)

***

#### setLimit

▸ **setLimit**(`joint`, `upperLimit`, `lowerLimit?`, `motorIndex?`): `void`

**Parameters**

| Name          | Type                                                                      |
| ------------- | ------------------------------------------------------------------------- |
| `joint`       | [`IMotorEnabledJoint`](../interfaces/m4m.framework.IMotorEnabledJoint.md) |
| `upperLimit`  | `number`                                                                  |
| `lowerLimit?` | `number`                                                                  |
| `motorIndex?` | `number`                                                                  |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setLimit](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setlimit)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:483](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L483)

***

#### setLinearVelocity

▸ **setLinearVelocity**(`impostor`, `velocity`): `void`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `velocity` | `vector3`                                             |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setLinearVelocity](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setlinearvelocity)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:398](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L398)

***

#### setMotor

▸ **setMotor**(`joint`, `speed?`, `force?`, `motorIndex?`): `void`

**Parameters**

| Name          | Type                                                                      |
| ------------- | ------------------------------------------------------------------------- |
| `joint`       | [`IMotorEnabledJoint`](../interfaces/m4m.framework.IMotorEnabledJoint.md) |
| `speed?`      | `number`                                                                  |
| `force?`      | `number`                                                                  |
| `motorIndex?` | `number`                                                                  |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setMotor](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setmotor)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:468](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L468)

***

#### setPhysicsBodyTransformation

▸ **setPhysicsBodyTransformation**(`impostor`, `newPosition`, `newRotation`): `void`

**Parameters**

| Name          | Type                                                  |
| ------------- | ----------------------------------------------------- |
| `impostor`    | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `newPosition` | `vector3`                                             |
| `newRotation` | `quaternion`                                          |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setPhysicsBodyTransformation](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#setphysicsbodytransformation)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:387](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L387)

***

#### setTimeStep

▸ **setTimeStep**(`timeStep`): `void`

**Parameters**

| Name       | Type     |
| ---------- | -------- |
| `timeStep` | `number` |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setTimeStep](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#settimestep)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L50)

***

#### setTransformationFromPhysicsBody

▸ **setTransformationFromPhysicsBody**(`impostor`): `void`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[setTransformationFromPhysicsBody](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#settransformationfromphysicsbody)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:372](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L372)

***

#### sleepBody

▸ **sleepBody**(`impostor`): `void`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[sleepBody](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#sleepbody)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:449](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L449)

***

#### updateDistanceJoint

▸ **updateDistanceJoint**(`joint`, `maxDistance`, `minDistance?`): `void`

**Parameters**

| Name           | Type                                            |
| -------------- | ----------------------------------------------- |
| `joint`        | [`PhysicsJoint`](m4m.framework.PhysicsJoint.md) |
| `maxDistance`  | `number`                                        |
| `minDistance?` | `number`                                        |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[updateDistanceJoint](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#updatedistancejoint)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:461](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L461)

***

#### wakeUpBody

▸ **wakeUpBody**(`impostor`): `void`

**Parameters**

| Name       | Type                                                  |
| ---------- | ----------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

**Returns**

`void`

**Implementation of**

[IPhysicsEnginePlugin](../interfaces/m4m.framework.IPhysicsEnginePlugin.md).[wakeUpBody](../interfaces/m4m.framework.IPhysicsEnginePlugin.md#wakeupbody)

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:457](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L457)

### Constructors

#### constructor

• **new OimoJSPlugin**(`iterations?`, `oimoInjection?`)

**`language`** zh\_CN

**`classdesc`** OimoJS 物理引擎插件

**`version`** m4m 1.0

**Parameters**

| Name            | Type     | Default value | Description |
| --------------- | -------- | ------------- | ----------- |
| `iterations?`   | `number` | `undefined`   | -           |
| `oimoInjection` | `any`    | `OIMO`        | Omio对象      |

**Defined in**

[framework/physics3d/oimoJSPlugin.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/oimoJSPlugin.ts#L26)
