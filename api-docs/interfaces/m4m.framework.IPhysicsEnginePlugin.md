# m4m.framework.IPhysicsEnginePlugin

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IPhysicsEnginePlugin

## Interface: IPhysicsEnginePlugin

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IPhysicsEnginePlugin

### Implemented by

* [`CannonJSPlugin`](../classes/m4m.framework.CannonJSPlugin.md)
* [`OimoJSPlugin`](../classes/m4m.framework.OimoJSPlugin.md)

### Table of contents

#### Methods

* [applyForce](m4m.framework.IPhysicsEnginePlugin.md#applyforce)
* [applyImpulse](m4m.framework.IPhysicsEnginePlugin.md#applyimpulse)
* [dispose](m4m.framework.IPhysicsEnginePlugin.md#dispose)
* [executeStep](m4m.framework.IPhysicsEnginePlugin.md#executestep)
* [generateJoint](m4m.framework.IPhysicsEnginePlugin.md#generatejoint)
* [generatePhysicsBody](m4m.framework.IPhysicsEnginePlugin.md#generatephysicsbody)
* [getAngularVelocity](m4m.framework.IPhysicsEnginePlugin.md#getangularvelocity)
* [getBodyFriction](m4m.framework.IPhysicsEnginePlugin.md#getbodyfriction)
* [getBodyMass](m4m.framework.IPhysicsEnginePlugin.md#getbodymass)
* [getBodyRestitution](m4m.framework.IPhysicsEnginePlugin.md#getbodyrestitution)
* [getBoxSizeToRef](m4m.framework.IPhysicsEnginePlugin.md#getboxsizetoref)
* [getLinearVelocity](m4m.framework.IPhysicsEnginePlugin.md#getlinearvelocity)
* [getRadius](m4m.framework.IPhysicsEnginePlugin.md#getradius)
* [getTimeStep](m4m.framework.IPhysicsEnginePlugin.md#gettimestep)
* [isSleeping](m4m.framework.IPhysicsEnginePlugin.md#issleeping)
* [isSupported](m4m.framework.IPhysicsEnginePlugin.md#issupported)
* [removeJoint](m4m.framework.IPhysicsEnginePlugin.md#removejoint)
* [removePhysicsBody](m4m.framework.IPhysicsEnginePlugin.md#removephysicsbody)
* [setAngularVelocity](m4m.framework.IPhysicsEnginePlugin.md#setangularvelocity)
* [setBodyFriction](m4m.framework.IPhysicsEnginePlugin.md#setbodyfriction)
* [setBodyMass](m4m.framework.IPhysicsEnginePlugin.md#setbodymass)
* [setBodyRestitution](m4m.framework.IPhysicsEnginePlugin.md#setbodyrestitution)
* [setGravity](m4m.framework.IPhysicsEnginePlugin.md#setgravity)
* [setLimit](m4m.framework.IPhysicsEnginePlugin.md#setlimit)
* [setLinearVelocity](m4m.framework.IPhysicsEnginePlugin.md#setlinearvelocity)
* [setMotor](m4m.framework.IPhysicsEnginePlugin.md#setmotor)
* [setPhysicsBodyTransformation](m4m.framework.IPhysicsEnginePlugin.md#setphysicsbodytransformation)
* [setTimeStep](m4m.framework.IPhysicsEnginePlugin.md#settimestep)
* [setTransformationFromPhysicsBody](m4m.framework.IPhysicsEnginePlugin.md#settransformationfromphysicsbody)
* [sleepBody](m4m.framework.IPhysicsEnginePlugin.md#sleepbody)
* [updateDistanceJoint](m4m.framework.IPhysicsEnginePlugin.md#updatedistancejoint)
* [wakeUpBody](m4m.framework.IPhysicsEnginePlugin.md#wakeupbody)

#### Properties

* [name](m4m.framework.IPhysicsEnginePlugin.md#name)
* [world](m4m.framework.IPhysicsEnginePlugin.md#world)

### Methods

#### applyForce

▸ **applyForce**(`impostor`, `force`, `contactPoint`): `void`

**Parameters**

| Name           | Type                                                             |
| -------------- | ---------------------------------------------------------------- |
| `impostor`     | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |
| `force`        | `vector3`                                                        |
| `contactPoint` | `vector3`                                                        |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:229](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L229)

***

#### applyImpulse

▸ **applyImpulse**(`impostor`, `force`, `contactPoint`): `void`

**Parameters**

| Name           | Type                                                             |
| -------------- | ---------------------------------------------------------------- |
| `impostor`     | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |
| `force`        | `vector3`                                                        |
| `contactPoint` | `vector3`                                                        |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:228](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L228)

***

#### dispose

▸ **dispose**(): `void`

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:257](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L257)

***

#### executeStep

▸ **executeStep**(`delta`, `impostors`): `void`

**Parameters**

| Name        | Type                                                                |
| ----------- | ------------------------------------------------------------------- |
| `delta`     | `number`                                                            |
| `impostors` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md)\[] |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:227](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L227)

***

#### generateJoint

▸ **generateJoint**(`joint`): `void`

**Parameters**

| Name    | Type                                                            |
| ------- | --------------------------------------------------------------- |
| `joint` | [`PhysicsImpostorJoint`](m4m.framework.PhysicsImpostorJoint.md) |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:232](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L232)

***

#### generatePhysicsBody

▸ **generatePhysicsBody**(`impostor`): `void`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:230](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L230)

***

#### getAngularVelocity

▸ **getAngularVelocity**(`impostor`): `vector3`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`vector3`

**Defined in**

[framework/physics3d/physicEngine.ts:240](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L240)

***

#### getBodyFriction

▸ **getBodyFriction**(`impostor`): `number`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`number`

**Defined in**

[framework/physics3d/physicEngine.ts:243](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L243)

***

#### getBodyMass

▸ **getBodyMass**(`impostor`): `number`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`number`

**Defined in**

[framework/physics3d/physicEngine.ts:242](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L242)

***

#### getBodyRestitution

▸ **getBodyRestitution**(`impostor`): `number`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`number`

**Defined in**

[framework/physics3d/physicEngine.ts:245](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L245)

***

#### getBoxSizeToRef

▸ **getBoxSizeToRef**(`impostor`, `result`): `void`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |
| `result`   | `vector3`                                                        |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:255](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L255)

***

#### getLinearVelocity

▸ **getLinearVelocity**(`impostor`): `vector3`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`vector3`

**Defined in**

[framework/physics3d/physicEngine.ts:239](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L239)

***

#### getRadius

▸ **getRadius**(`impostor`): `number`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`number`

**Defined in**

[framework/physics3d/physicEngine.ts:254](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L254)

***

#### getTimeStep

▸ **getTimeStep**(): `number`

**Returns**

`number`

**Defined in**

[framework/physics3d/physicEngine.ts:226](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L226)

***

#### isSleeping

▸ **isSleeping**(`impostor`): `boolean`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`boolean`

**Defined in**

[framework/physics3d/physicEngine.ts:248](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L248)

***

#### isSupported

▸ **isSupported**(): `boolean`

**Returns**

`boolean`

**Defined in**

[framework/physics3d/physicEngine.ts:234](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L234)

***

#### removeJoint

▸ **removeJoint**(`joint`): `void`

**Parameters**

| Name    | Type                                                            |
| ------- | --------------------------------------------------------------- |
| `joint` | [`PhysicsImpostorJoint`](m4m.framework.PhysicsImpostorJoint.md) |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:233](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L233)

***

#### removePhysicsBody

▸ **removePhysicsBody**(`impostor`): `void`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:231](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L231)

***

#### setAngularVelocity

▸ **setAngularVelocity**(`impostor`, `velocity`): `void`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |
| `velocity` | `vector3`                                                        |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:238](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L238)

***

#### setBodyFriction

▸ **setBodyFriction**(`impostor`, `friction`): `void`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |
| `friction` | `number`                                                         |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:244](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L244)

***

#### setBodyMass

▸ **setBodyMass**(`impostor`, `mass`): `void`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |
| `mass`     | `number`                                                         |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:241](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L241)

***

#### setBodyRestitution

▸ **setBodyRestitution**(`impostor`, `restitution`): `void`

**Parameters**

| Name          | Type                                                             |
| ------------- | ---------------------------------------------------------------- |
| `impostor`    | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |
| `restitution` | `number`                                                         |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:246](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L246)

***

#### setGravity

▸ **setGravity**(`gravity`): `void`

**Parameters**

| Name      | Type      |
| --------- | --------- |
| `gravity` | `vector3` |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:224](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L224)

***

#### setLimit

▸ **setLimit**(`joint`, `upperLimit`, `lowerLimit?`, `motorIndex?`): `void`

**Parameters**

| Name          | Type                                                        |
| ------------- | ----------------------------------------------------------- |
| `joint`       | [`IMotorEnabledJoint`](m4m.framework.IMotorEnabledJoint.md) |
| `upperLimit`  | `number`                                                    |
| `lowerLimit?` | `number`                                                    |
| `motorIndex?` | `number`                                                    |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:253](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L253)

***

#### setLinearVelocity

▸ **setLinearVelocity**(`impostor`, `velocity`): `void`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |
| `velocity` | `vector3`                                                        |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:237](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L237)

***

#### setMotor

▸ **setMotor**(`joint`, `speed`, `maxForce?`, `motorIndex?`): `void`

**Parameters**

| Name          | Type                                                        |
| ------------- | ----------------------------------------------------------- |
| `joint`       | [`IMotorEnabledJoint`](m4m.framework.IMotorEnabledJoint.md) |
| `speed`       | `number`                                                    |
| `maxForce?`   | `number`                                                    |
| `motorIndex?` | `number`                                                    |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:252](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L252)

***

#### setPhysicsBodyTransformation

▸ **setPhysicsBodyTransformation**(`impostor`, `newPosition`, `newRotation`): `void`

**Parameters**

| Name          | Type                                                             |
| ------------- | ---------------------------------------------------------------- |
| `impostor`    | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |
| `newPosition` | `vector3`                                                        |
| `newRotation` | `quaternion`                                                     |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:236](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L236)

***

#### setTimeStep

▸ **setTimeStep**(`timeStep`): `void`

**Parameters**

| Name       | Type     |
| ---------- | -------- |
| `timeStep` | `number` |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:225](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L225)

***

#### setTransformationFromPhysicsBody

▸ **setTransformationFromPhysicsBody**(`impostor`): `void`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:235](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L235)

***

#### sleepBody

▸ **sleepBody**(`impostor`): `void`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:247](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L247)

***

#### updateDistanceJoint

▸ **updateDistanceJoint**(`joint`, `maxDistance`, `minDistance?`): `void`

**Parameters**

| Name           | Type                                                       |
| -------------- | ---------------------------------------------------------- |
| `joint`        | [`PhysicsJoint`](../classes/m4m.framework.PhysicsJoint.md) |
| `maxDistance`  | `number`                                                   |
| `minDistance?` | `number`                                                   |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:251](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L251)

***

#### wakeUpBody

▸ **wakeUpBody**(`impostor`): `void`

**Parameters**

| Name       | Type                                                             |
| ---------- | ---------------------------------------------------------------- |
| `impostor` | [`PhysicsImpostor`](../classes/m4m.framework.PhysicsImpostor.md) |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:249](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L249)

### Properties

#### name

• **name**: `string`

**Defined in**

[framework/physics3d/physicEngine.ts:223](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L223)

***

#### world

• **world**: `any`

**Defined in**

[framework/physics3d/physicEngine.ts:222](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L222)
