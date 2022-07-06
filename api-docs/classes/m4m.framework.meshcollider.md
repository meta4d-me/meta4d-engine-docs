# m4m.framework.meshcollider

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / meshcollider

## Class: meshcollider

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).meshcollider

**`language`** zh\_CN

**`classdesc`** 碰撞组件

**`version`** m4m 1.0

### Implements

* [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)
* [`ICollider`](../interfaces/m4m.framework.ICollider.md)

### Table of contents

#### Accessors

* [colliderVisible](m4m.framework.meshcollider.md#collidervisible)

#### Constructors

* [constructor](m4m.framework.meshcollider.md#constructor)

#### Properties

* [gameObject](m4m.framework.meshcollider.md#gameobject)
* [ClassName](m4m.framework.meshcollider.md#classname)

#### Methods

* [onPlay](m4m.framework.meshcollider.md#onplay)
* [start](m4m.framework.meshcollider.md#start)
* [update](m4m.framework.meshcollider.md#update)

### Accessors

#### colliderVisible

• `get` **colliderVisible**(): `boolean`

**`language`** zh\_CN

**`classdesc`** 碰撞体的可见性

**`version`** m4m 1.0

**Returns**

`boolean`

**Defined in**

[framework/component/meshcollider.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshcollider.ts#L68)

• `set` **colliderVisible**(`value`): `void`

**`language`** zh\_CN

**`classdesc`** 碰撞体的可见性

**`version`** m4m 1.0

**Parameters**

| Name    | Type      | Description |
| ------- | --------- | ----------- |
| `value` | `boolean` | boolbean    |

**Returns**

`void`

**Defined in**

[framework/component/meshcollider.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshcollider.ts#L80)

### Constructors

#### constructor

• **new meshcollider**()

### Properties

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh\_CN

**`classdesc`** 挂载的gameobject

**`version`** m4m 1.0

**Implementation of**

[ICollider](../interfaces/m4m.framework.ICollider.md).[gameObject](../interfaces/m4m.framework.ICollider.md#gameobject)

**Defined in**

[framework/component/meshcollider.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshcollider.ts#L23)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"meshcollider"`

**Defined in**

[framework/component/meshcollider.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshcollider.ts#L14)

### Methods

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

**Defined in**

[framework/component/meshcollider.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshcollider.ts#L47)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

**Defined in**

[framework/component/meshcollider.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshcollider.ts#L41)

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

[framework/component/meshcollider.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/meshcollider.ts#L52)
