# m4m.framework.PhysicsEngine

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / PhysicsEngine

## Class: PhysicsEngine

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).PhysicsEngine

### Table of contents

#### Methods

* [\_step](m4m.framework.PhysicsEngine.md#\_step)
* [addImpostor](m4m.framework.PhysicsEngine.md#addimpostor)
* [addJoint](m4m.framework.PhysicsEngine.md#addjoint)
* [dispose](m4m.framework.PhysicsEngine.md#dispose)
* [getImpostorForPhysicsObject](m4m.framework.PhysicsEngine.md#getimpostorforphysicsobject)
* [getImpostorWithPhysicsBody](m4m.framework.PhysicsEngine.md#getimpostorwithphysicsbody)
* [getImpostors](m4m.framework.PhysicsEngine.md#getimpostors)
* [getPhysicsPlugin](m4m.framework.PhysicsEngine.md#getphysicsplugin)
* [getPhysicsPluginName](m4m.framework.PhysicsEngine.md#getphysicspluginname)
* [getTimeStep](m4m.framework.PhysicsEngine.md#gettimestep)
* [removeImpostor](m4m.framework.PhysicsEngine.md#removeimpostor)
* [removeJoint](m4m.framework.PhysicsEngine.md#removejoint)
* [setGravity](m4m.framework.PhysicsEngine.md#setgravity)
* [setTimeStep](m4m.framework.PhysicsEngine.md#settimestep)

#### Constructors

* [constructor](m4m.framework.PhysicsEngine.md#constructor)

#### Properties

* [gravity](m4m.framework.PhysicsEngine.md#gravity)
* [Epsilon](m4m.framework.PhysicsEngine.md#epsilon)

### Methods

#### \_step

▸ **\_step**(`delta`): `void`

Called by the scene. no need to call it.

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L149)

***

#### addImpostor

▸ **addImpostor**(`impostor`): `void`

Adding a new impostor for the impostor tracking. This will be done by the impostor itself.

**Parameters**

| Name       | Type                                                  | Description         |
| ---------- | ----------------------------------------------------- | ------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) | the impostor to add |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L83)

***

#### addJoint

▸ **addJoint**(`mainImpostor`, `connectedImpostor`, `joint`): `void`

Add a joint to the physics engine

**Parameters**

| Name                | Type                                                  | Description                                                          |
| ------------------- | ----------------------------------------------------- | -------------------------------------------------------------------- |
| `mainImpostor`      | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) | the main impostor to which the joint is added.                       |
| `connectedImpostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) | the impostor that is connected to the main impostor using this joint |
| `joint`             | [`PhysicsJoint`](m4m.framework.PhysicsJoint.md)       | -                                                                    |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L116)

***

#### dispose

▸ **dispose**(): `void`

dispose all impostor of the physics engine.

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L59)

***

#### getImpostorForPhysicsObject

▸ **getImpostorForPhysicsObject**(`object`): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

Gets the impostor for a physics enabled object

**Parameters**

| Name     | Type                                      | Description                                     |
| -------- | ----------------------------------------- | ----------------------------------------------- |
| `object` | [`transform`](m4m.framework.transform.md) | defines the object impersonated by the impostor |

**Returns**

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

the PhysicsImpostor or null if not found

**Defined in**

[framework/physics3d/physicEngine.ts:192](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L192)

***

#### getImpostorWithPhysicsBody

▸ **getImpostorWithPhysicsBody**(`body`): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

Gets the impostor for a physics body object

**Parameters**

| Name   | Type  | Description                               |
| ------ | ----- | ----------------------------------------- |
| `body` | `any` | defines physics body used by the impostor |

**Returns**

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

the PhysicsImpostor or null if not found

**Defined in**

[framework/physics3d/physicEngine.ts:207](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L207)

***

#### getImpostors

▸ **getImpostors**(): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)\[]

Gets the list of physic impostors

**Returns**

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)\[]

an array of PhysicsImpostor

**Defined in**

[framework/physics3d/physicEngine.ts:183](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L183)

***

#### getPhysicsPlugin

▸ **getPhysicsPlugin**(): [`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md)

Gets the current plugin used to run the simulation

**Returns**

[`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md)

current plugin

**Defined in**

[framework/physics3d/physicEngine.ts:176](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L176)

***

#### getPhysicsPluginName

▸ **getPhysicsPluginName**(): `string`

**Returns**

`string`

**Defined in**

[framework/physics3d/physicEngine.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L66)

***

#### getTimeStep

▸ **getTimeStep**(): `number`

Get the time step of the physics engine.

**Returns**

`number`

**Defined in**

[framework/physics3d/physicEngine.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L52)

***

#### removeImpostor

▸ **removeImpostor**(`impostor`): `void`

Remove an impostor from the engine. This impostor and its mesh will not longer be updated by the physics engine.

**Parameters**

| Name       | Type                                                  | Description            |
| ---------- | ----------------------------------------------------- | ---------------------- |
| `impostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) | the impostor to remove |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L98)

***

#### removeJoint

▸ **removeJoint**(`mainImpostor`, `connectedImpostor`, `joint`): `void`

Removes a joint from the simulation

**Parameters**

| Name                | Type                                                  | Description                                                       |
| ------------------- | ----------------------------------------------------- | ----------------------------------------------------------------- |
| `mainImpostor`      | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) | defines the impostor used with the joint                          |
| `connectedImpostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) | defines the other impostor connected to the main one by the joint |
| `joint`             | [`PhysicsJoint`](m4m.framework.PhysicsJoint.md)       | defines the joint to remove                                       |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:133](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L133)

***

#### setGravity

▸ **setGravity**(`gravity`): `void`

Sets the gravity vector used by the simulation

**Parameters**

| Name      | Type      | Description                       |
| --------- | --------- | --------------------------------- |
| `gravity` | `vector3` | defines the gravity vector to use |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L33)

***

#### setTimeStep

▸ **setTimeStep**(`newTimeStep?`): `void`

Set the time step of the physics engine. default is 1/60. To slow it down, enter 1/600 for example. To speed it up, 1/30

**Parameters**

| Name          | Type     | Description                              |
| ------------- | -------- | ---------------------------------------- |
| `newTimeStep` | `number` | the new timestep to apply to this world. |

**Returns**

`void`

**Defined in**

[framework/physics3d/physicEngine.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L45)

### Constructors

#### constructor

• **new PhysicsEngine**(`gravity?`, `_physicsPlugin?`)

Creates a new Physics Engine

**Parameters**

| Name             | Type                                                                          | Default value | Description                                       |
| ---------------- | ----------------------------------------------------------------------------- | ------------- | ------------------------------------------------- |
| `gravity`        | `vector3`                                                                     | `null`        | defines the gravity vector used by the simulation |
| `_physicsPlugin` | [`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md) | `undefined`   | defines the plugin to use (CannonJS by default)   |

**Defined in**

[framework/physics3d/physicEngine.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L19)

### Properties

#### gravity

• **gravity**: `vector3`

**Defined in**

[framework/physics3d/physicEngine.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L12)

***

#### Epsilon

▪ `Static` **Epsilon**: `number` = `0.001`

**Defined in**

[framework/physics3d/physicEngine.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicEngine.ts#L71)
