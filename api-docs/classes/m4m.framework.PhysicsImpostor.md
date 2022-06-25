[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / PhysicsImpostor

# Class: PhysicsImpostor

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).PhysicsImpostor

## Table of contents

### Methods

- [\_init](m4m.framework.PhysicsImpostor.md#_init)
- [addJoint](m4m.framework.PhysicsImpostor.md#addjoint)
- [afterStep](m4m.framework.PhysicsImpostor.md#afterstep)
- [applyForce](m4m.framework.PhysicsImpostor.md#applyforce)
- [applyImpulse](m4m.framework.PhysicsImpostor.md#applyimpulse)
- [beforeStep](m4m.framework.PhysicsImpostor.md#beforestep)
- [clone](m4m.framework.PhysicsImpostor.md#clone)
- [createJoint](m4m.framework.PhysicsImpostor.md#createjoint)
- [dispose](m4m.framework.PhysicsImpostor.md#dispose)
- [executeNativeFunction](m4m.framework.PhysicsImpostor.md#executenativefunction)
- [forceUpdate](m4m.framework.PhysicsImpostor.md#forceupdate)
- [getAngularVelocity](m4m.framework.PhysicsImpostor.md#getangularvelocity)
- [getBoxSizeToRef](m4m.framework.PhysicsImpostor.md#getboxsizetoref)
- [getFreeze](m4m.framework.PhysicsImpostor.md#getfreeze)
- [getLinearVelocity](m4m.framework.PhysicsImpostor.md#getlinearvelocity)
- [getObjectCenter](m4m.framework.PhysicsImpostor.md#getobjectcenter)
- [getObjectExtendSize](m4m.framework.PhysicsImpostor.md#getobjectextendsize)
- [getParam](m4m.framework.PhysicsImpostor.md#getparam)
- [getRadius](m4m.framework.PhysicsImpostor.md#getradius)
- [isBodyInitRequired](m4m.framework.PhysicsImpostor.md#isbodyinitrequired)
- [kinematicSetPosition](m4m.framework.PhysicsImpostor.md#kinematicsetposition)
- [kinematicSetRotation](m4m.framework.PhysicsImpostor.md#kinematicsetrotation)
- [onCollide](m4m.framework.PhysicsImpostor.md#oncollide)
- [registerAfterPhysicsStep](m4m.framework.PhysicsImpostor.md#registerafterphysicsstep)
- [registerBeforePhysicsStep](m4m.framework.PhysicsImpostor.md#registerbeforephysicsstep)
- [registerOnPhysicsCollide](m4m.framework.PhysicsImpostor.md#registeronphysicscollide)
- [resetUpdateFlags](m4m.framework.PhysicsImpostor.md#resetupdateflags)
- [setAngularVelocity](m4m.framework.PhysicsImpostor.md#setangularvelocity)
- [setDeltaPosition](m4m.framework.PhysicsImpostor.md#setdeltaposition)
- [setDeltaRotation](m4m.framework.PhysicsImpostor.md#setdeltarotation)
- [setFreeze](m4m.framework.PhysicsImpostor.md#setfreeze)
- [setLinearVelocity](m4m.framework.PhysicsImpostor.md#setlinearvelocity)
- [setMass](m4m.framework.PhysicsImpostor.md#setmass)
- [setParam](m4m.framework.PhysicsImpostor.md#setparam)
- [setScalingUpdated](m4m.framework.PhysicsImpostor.md#setscalingupdated)
- [sleep](m4m.framework.PhysicsImpostor.md#sleep)
- [unregisterAfterPhysicsStep](m4m.framework.PhysicsImpostor.md#unregisterafterphysicsstep)
- [unregisterBeforePhysicsStep](m4m.framework.PhysicsImpostor.md#unregisterbeforephysicsstep)
- [unregisterOnPhysicsCollide](m4m.framework.PhysicsImpostor.md#unregisteronphysicscollide)
- [wakeUp](m4m.framework.PhysicsImpostor.md#wakeup)

### Properties

- [\_options](m4m.framework.PhysicsImpostor.md#_options)
- [object](m4m.framework.PhysicsImpostor.md#object)
- [onCollideEvent](m4m.framework.PhysicsImpostor.md#oncollideevent)
- [type](m4m.framework.PhysicsImpostor.md#type)
- [uniqueId](m4m.framework.PhysicsImpostor.md#uniqueid)
- [DEFAULT\_OBJECT\_SIZE](m4m.framework.PhysicsImpostor.md#default_object_size)
- [IDENTITY\_QUATERNION](m4m.framework.PhysicsImpostor.md#identity_quaternion)

### Constructors

- [constructor](m4m.framework.PhysicsImpostor.md#constructor)

### Accessors

- [friction](m4m.framework.PhysicsImpostor.md#friction)
- [isDisposed](m4m.framework.PhysicsImpostor.md#isdisposed)
- [isSleeping](m4m.framework.PhysicsImpostor.md#issleeping)
- [mass](m4m.framework.PhysicsImpostor.md#mass)
- [parent](m4m.framework.PhysicsImpostor.md#parent)
- [physicsBody](m4m.framework.PhysicsImpostor.md#physicsbody)
- [restitution](m4m.framework.PhysicsImpostor.md#restitution)

## Methods

### \_init

▸ **_init**(): `void`

This function will completly initialize this impostor.
It will create a new body - but only if this mesh has no parent.
If it has, this impostor will not be used other than to define the impostor
of the child mesh.

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:181](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L181)

___

### addJoint

▸ **addJoint**(`otherImpostor`, `joint`): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

Add a joint to this impostor with a different impostor.

#### Parameters

| Name | Type |
| :------ | :------ |
| `otherImpostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `joint` | [`PhysicsJoint`](m4m.framework.PhysicsJoint.md) |

#### Returns

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Defined in

[framework/physics3d/physicImpostor.ts:683](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L683)

___

### afterStep

▸ **afterStep**(): `void`

this function is executed by the physics engine

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:511](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L511)

___

### applyForce

▸ **applyForce**(`force`, `contactPoint`): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

Apply a force

#### Parameters

| Name | Type |
| :------ | :------ |
| `force` | `vector3` |
| `contactPoint` | `vector3` |

#### Returns

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Defined in

[framework/physics3d/physicImpostor.ts:652](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L652)

___

### applyImpulse

▸ **applyImpulse**(`force`, `contactPoint`): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

Apply an impulse

#### Parameters

| Name | Type |
| :------ | :------ |
| `force` | `vector3` |
| `contactPoint` | `vector3` |

#### Returns

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Defined in

[framework/physics3d/physicImpostor.ts:662](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L662)

___

### beforeStep

▸ **beforeStep**(): `void`

this function is executed by the physics engine.

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:443](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L443)

___

### clone

▸ **clone**(`newObject`): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `newObject` | [`transform`](m4m.framework.transform.md) |

#### Returns

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Defined in

[framework/physics3d/physicImpostor.ts:728](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L728)

___

### createJoint

▸ **createJoint**(`otherImpostor`, `jointType`, `jointData`): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

A help function to create a joint.

#### Parameters

| Name | Type |
| :------ | :------ |
| `otherImpostor` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `jointType` | `number` |
| `jointData` | [`PhysicsJointData`](../interfaces/m4m.framework.PhysicsJointData.md) |

#### Returns

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Defined in

[framework/physics3d/physicImpostor.ts:673](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L673)

___

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:733](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L733)

___

### executeNativeFunction

▸ **executeNativeFunction**(`func`): `void`

Execute a function with the physics plugin native code.
Provide a function the will have two variables - the world object and the physics body object.

#### Parameters

| Name | Type |
| :------ | :------ |
| `func` | (`world`: `any`, `physicsBody`: `any`) => `void` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:366](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L366)

___

### forceUpdate

▸ **forceUpdate**(): `void`

Force a regeneration of this or the parent's impostor's body.
Use under cautious - This will remove all joints already implemented.

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:216](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L216)

___

### getAngularVelocity

▸ **getAngularVelocity**(): `vector3`

#### Returns

`vector3`

#### Defined in

[framework/physics3d/physicImpostor.ts:354](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L354)

___

### getBoxSizeToRef

▸ **getBoxSizeToRef**(`result`): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `result` | `vector3` |

#### Returns

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Defined in

[framework/physics3d/physicImpostor.ts:777](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L777)

___

### getFreeze

▸ **getFreeze**(`option`): `number`

获取 位移、旋转 冻结选项

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `option` | [`FreezeType`](../enums/m4m.framework.FreezeType.md) | 冻结类型 |

#### Returns

`number`

#### Defined in

[framework/physics3d/physicImpostor.ts:500](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L500)

___

### getLinearVelocity

▸ **getLinearVelocity**(): `vector3`

#### Returns

`vector3`

#### Defined in

[framework/physics3d/physicImpostor.ts:346](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L346)

___

### getObjectCenter

▸ **getObjectCenter**(): `vector3`

Gets the object center

#### Returns

`vector3`

The object center

#### Defined in

[framework/physics3d/physicImpostor.ts:304](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L304)

___

### getObjectExtendSize

▸ **getObjectExtendSize**(): `vector3`

Gets the object extend size

#### Returns

`vector3`

the object extend size

#### Defined in

[framework/physics3d/physicImpostor.ts:292](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L292)

___

### getParam

▸ **getParam**(`paramName`): `any`

Get a specific parametes from the options parameter.

#### Parameters

| Name | Type |
| :------ | :------ |
| `paramName` | `string` |

#### Returns

`any`

#### Defined in

[framework/physics3d/physicImpostor.ts:322](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L322)

___

### getRadius

▸ **getRadius**(): `number`

#### Returns

`number`

#### Defined in

[framework/physics3d/physicImpostor.ts:783](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L783)

___

### isBodyInitRequired

▸ **isBodyInitRequired**(): `boolean`

Should a new body be generated.

#### Returns

`boolean`

#### Defined in

[framework/physics3d/physicImpostor.ts:204](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L204)

___

### kinematicSetPosition

▸ **kinematicSetPosition**(`position`): `void`

设置动力学的 位置

#### Parameters

| Name | Type |
| :------ | :------ |
| `position` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:790](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L790)

___

### kinematicSetRotation

▸ **kinematicSetRotation**(`rotation`): `void`

设置动力学的 旋转

#### Parameters

| Name | Type |
| :------ | :------ |
| `rotation` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:798](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L798)

___

### onCollide

▸ **onCollide**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `Object` |
| `e.body` | `any` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:626](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L626)

___

### registerAfterPhysicsStep

▸ **registerAfterPhysicsStep**(`func`): `void`

Register a function that will be executed after the physics step

#### Parameters

| Name | Type |
| :------ | :------ |
| `func` | (`impostor`: [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)) => `void` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:392](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L392)

___

### registerBeforePhysicsStep

▸ **registerBeforePhysicsStep**(`func`): `void`

Register a function that will be executed before the physics world is stepping forward.

#### Parameters

| Name | Type |
| :------ | :------ |
| `func` | (`impostor`: [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)) => `void` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:375](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L375)

___

### registerOnPhysicsCollide

▸ **registerOnPhysicsCollide**(`collideAgainst`, `func`): `void`

register a function that will be executed when this impostor collides against a different body.

#### Parameters

| Name | Type |
| :------ | :------ |
| `collideAgainst` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) \| [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)[] |
| `func` | (`collider`: [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md), `collidedAgainst`: [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)) => `void` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:409](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L409)

___

### resetUpdateFlags

▸ **resetUpdateFlags**(): `void`

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:260](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L260)

___

### setAngularVelocity

▸ **setAngularVelocity**(`velocity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `velocity` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:358](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L358)

___

### setDeltaPosition

▸ **setDeltaPosition**(`position`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `position` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:762](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L762)

___

### setDeltaRotation

▸ **setDeltaRotation**(`rotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `rotation` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:767](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L767)

___

### setFreeze

▸ **setFreeze**(`option`, `beSelect`): `void`

设置 位移、旋转 冻结选项

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `option` | [`FreezeType`](../enums/m4m.framework.FreezeType.md) | 冻结类型 |
| `beSelect` | `boolean` | 是否选上 |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:486](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L486)

___

### setLinearVelocity

▸ **setLinearVelocity**(`velocity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `velocity` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:350](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L350)

___

### setMass

▸ **setMass**(`mass`): `void`

Specifically change the body's mass option. Won't recreate the physics body object

#### Parameters

| Name | Type |
| :------ | :------ |
| `mass` | `number` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:337](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L337)

___

### setParam

▸ **setParam**(`paramName`, `value`): `void`

Sets a specific parameter in the options given to the physics plugin

#### Parameters

| Name | Type |
| :------ | :------ |
| `paramName` | `string` |
| `value` | `number` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:329](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L329)

___

### setScalingUpdated

▸ **setScalingUpdated**(`updated`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `updated` | `boolean` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:208](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L208)

___

### sleep

▸ **sleep**(): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

Will keep this body still, in a sleep mode.

#### Returns

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Defined in

[framework/physics3d/physicImpostor.ts:699](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L699)

___

### unregisterAfterPhysicsStep

▸ **unregisterAfterPhysicsStep**(`func`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `func` | (`impostor`: [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)) => `void` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:396](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L396)

___

### unregisterBeforePhysicsStep

▸ **unregisterBeforePhysicsStep**(`func`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `func` | (`impostor`: [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)) => `void` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:379](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L379)

___

### unregisterOnPhysicsCollide

▸ **unregisterOnPhysicsCollide**(`collideAgainst`, `func`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `collideAgainst` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) \| [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)[] |
| `func` | (`collider`: [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md), `collidedAgainst`: [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) \| [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)[]) => `void` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:414](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L414)

___

### wakeUp

▸ **wakeUp**(): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

Wake the body up.

#### Returns

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Defined in

[framework/physics3d/physicImpostor.ts:720](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L720)

## Properties

### \_options

• **\_options**: [`PhysicsImpostorParameters`](../interfaces/m4m.framework.PhysicsImpostorParameters.md)

___

### object

• **object**: [`transform`](m4m.framework.transform.md)

___

### onCollideEvent

• **onCollideEvent**: (`collider`: [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md), `collidedWith`: [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)) => `void` = `null`

#### Type declaration

▸ (`collider`, `collidedWith`): `void`

Legacy collision detection event support

##### Parameters

| Name | Type |
| :------ | :------ |
| `collider` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |
| `collidedWith` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

##### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:623](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L623)

___

### type

• **type**: [`ImpostorType`](../enums/m4m.framework.ImpostorType.md)

___

### uniqueId

• **uniqueId**: `number`

#### Defined in

[framework/physics3d/physicImpostor.ts:118](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L118)

___

### DEFAULT\_OBJECT\_SIZE

▪ `Static` **DEFAULT\_OBJECT\_SIZE**: `vector3`

#### Defined in

[framework/physics3d/physicImpostor.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L62)

___

### IDENTITY\_QUATERNION

▪ `Static` **IDENTITY\_QUATERNION**: `quaternion`

#### Defined in

[framework/physics3d/physicImpostor.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L64)

## Constructors

### constructor

• **new PhysicsImpostor**(`object`, `type`, `_options?`)

**`language`** zh_CN

**`classdesc`**
PhysicsImpostor

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `object` | [`transform`](m4m.framework.transform.md) | transform 对象 |
| `type` | [`ImpostorType`](../enums/m4m.framework.ImpostorType.md) | shape types. |
| `_options` | [`PhysicsImpostorParameters`](../interfaces/m4m.framework.PhysicsImpostorParameters.md) | Body Parameters |

#### Defined in

[framework/physics3d/physicImpostor.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L134)

## Accessors

### friction

• `get` **friction**(): `number`

#### Returns

`number`

#### Defined in

[framework/physics3d/physicImpostor.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L101)

• `set` **friction**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:105](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L105)

___

### isDisposed

• `get` **isDisposed**(): `boolean`

#### Returns

`boolean`

#### Defined in

[framework/physics3d/physicImpostor.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L89)

___

### isSleeping

• `get` **isSleeping**(): `boolean`

result body is sleeping

#### Returns

`boolean`

#### Defined in

[framework/physics3d/physicImpostor.ts:710](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L710)

___

### mass

• `get` **mass**(): `number`

#### Returns

`number`

#### Defined in

[framework/physics3d/physicImpostor.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L93)

• `set` **mass**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:97](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L97)

___

### parent

• `get` **parent**(): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

Get the parent of the physics imposter

#### Returns

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

Physics imposter or null

#### Defined in

[framework/physics3d/physicImpostor.ts:238](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L238)

• `set` **parent**(`value`): `void`

Sets the parent of the physics imposter

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`void`

Physics imposter or null

#### Defined in

[framework/physics3d/physicImpostor.ts:245](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L245)

___

### physicsBody

• `get` **physicsBody**(): `any`

Gets the body that holds this impostor. Either its own, or its parent.

#### Returns

`any`

#### Defined in

[framework/physics3d/physicImpostor.ts:230](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L230)

• `set` **physicsBody**(`physicsBody`): `void`

Set the physics body. Used mainly by the physics engine/plugin

#### Parameters

| Name | Type |
| :------ | :------ |
| `physicsBody` | `any` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:252](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L252)

___

### restitution

• `get` **restitution**(): `number`

#### Returns

`number`

#### Defined in

[framework/physics3d/physicImpostor.ts:109](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L109)

• `set` **restitution**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicImpostor.ts:113](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicImpostor.ts#L113)
