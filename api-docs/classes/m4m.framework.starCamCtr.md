# m4m.framework.starCamCtr

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / starCamCtr

## Class: starCamCtr

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).starCamCtr

### Implements

* [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

### Table of contents

#### Methods

* [clone](m4m.framework.starCamCtr.md#clone)
* [moveTo](m4m.framework.starCamCtr.md#moveto)
* [onPlay](m4m.framework.starCamCtr.md#onplay)
* [remove](m4m.framework.starCamCtr.md#remove)
* [start](m4m.framework.starCamCtr.md#start)
* [update](m4m.framework.starCamCtr.md#update)

#### Constructors

* [constructor](m4m.framework.starCamCtr.md#constructor)

#### Properties

* [gameObject](m4m.framework.starCamCtr.md#gameobject)
* [minSpeed](m4m.framework.starCamCtr.md#minspeed)
* [moveDuration](m4m.framework.starCamCtr.md#moveduration)
* [relativeEuler](m4m.framework.starCamCtr.md#relativeeuler)
* [relativelocation](m4m.framework.starCamCtr.md#relativelocation)
* [ClassName](m4m.framework.starCamCtr.md#classname)

### Methods

#### clone

▸ **clone**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[clone](../interfaces/m4m.framework.INodeComponent.md#clone)

**Defined in**

[framework/component/project/starCamCtr.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L62)

***

#### moveTo

▸ **moveTo**(`to`): `void`

**Parameters**

| Name | Type                                      |
| ---- | ----------------------------------------- |
| `to` | [`transform`](m4m.framework.transform.md) |

**Returns**

`void`

**Defined in**

[framework/component/project/starCamCtr.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L66)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

**Defined in**

[framework/component/project/starCamCtr.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L29)

***

#### remove

▸ **remove**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[remove](../interfaces/m4m.framework.INodeComponent.md#remove)

**Defined in**

[framework/component/project/starCamCtr.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L58)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

**Defined in**

[framework/component/project/starCamCtr.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L25)

***

#### update

▸ **update**(`delta`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[update](../interfaces/m4m.framework.INodeComponent.md#update)

**Defined in**

[framework/component/project/starCamCtr.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L35)

### Constructors

#### constructor

• **new starCamCtr**()

### Properties

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[gameObject](../interfaces/m4m.framework.INodeComponent.md#gameobject)

**Defined in**

[framework/component/project/starCamCtr.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L56)

***

#### minSpeed

• **minSpeed**: `number` = `5`

**Defined in**

[framework/component/project/starCamCtr.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L8)

***

#### moveDuration

• **moveDuration**: `number` = `1`

**Defined in**

[framework/component/project/starCamCtr.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L7)

***

#### relativeEuler

• **relativeEuler**: `vector3`

**Defined in**

[framework/component/project/starCamCtr.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L11)

***

#### relativelocation

• **relativelocation**: `vector3`

**Defined in**

[framework/component/project/starCamCtr.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L10)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"starCamCtr"`

**Defined in**

[framework/component/project/starCamCtr.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/project/starCamCtr.ts#L5)
