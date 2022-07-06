# m4m.framework.gameObject

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / gameObject

## Class: gameObject

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).gameObject

**`language`** zh\_CN

**`classdesc`** gameObject类 对应unity中gameObject概念

**`version`** m4m 1.0

### Table of contents

#### Methods

* [addComponent](m4m.framework.gameObject.md#addcomponent)
* [addComponentDirect](m4m.framework.gameObject.md#addcomponentdirect)
* [dispose](m4m.framework.gameObject.md#dispose)
* [getComponent](m4m.framework.gameObject.md#getcomponent)
* [getComponentInParent](m4m.framework.gameObject.md#getcomponentinparent)
* [getComponents](m4m.framework.gameObject.md#getcomponents)
* [getComponentsInChildren](m4m.framework.gameObject.md#getcomponentsinchildren)
* [getFirstComponentInChildren](m4m.framework.gameObject.md#getfirstcomponentinchildren)
* [getName](m4m.framework.gameObject.md#getname)
* [getScene](m4m.framework.gameObject.md#getscene)
* [init](m4m.framework.gameObject.md#init)
* [removeAllComponents](m4m.framework.gameObject.md#removeallcomponents)
* [removeComponent](m4m.framework.gameObject.md#removecomponent)
* [removeComponentByTypeName](m4m.framework.gameObject.md#removecomponentbytypename)
* [update](m4m.framework.gameObject.md#update)

#### Properties

* [camera](m4m.framework.gameObject.md#camera)
* [collider](m4m.framework.gameObject.md#collider)
* [componentTypes](m4m.framework.gameObject.md#componenttypes)
* [components](m4m.framework.gameObject.md#components)
* [hideFlags](m4m.framework.gameObject.md#hideflags)
* [isStatic](m4m.framework.gameObject.md#isstatic)
* [layer](m4m.framework.gameObject.md#layer)
* [light](m4m.framework.gameObject.md#light)
* [renderer](m4m.framework.gameObject.md#renderer)
* [tag](m4m.framework.gameObject.md#tag)
* [transform](m4m.framework.gameObject.md#transform)
* [ClassName](m4m.framework.gameObject.md#classname)

#### Constructors

* [constructor](m4m.framework.gameObject.md#constructor)

#### Accessors

* [visible](m4m.framework.gameObject.md#visible)
* [visibleInScene](m4m.framework.gameObject.md#visibleinscene)

### Methods

#### addComponent

▸ **addComponent**(`type`): [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**`language`** zh\_CN

**`classdesc`** 根据组件类型添加一个组件

**`version`** m4m 1.0

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `type` | `string` | 组件类型        |

**Returns**

[`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**Defined in**

[framework/scene/gameobject.ts:601](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L601)

***

#### addComponentDirect

▸ **addComponentDirect**(`comp`): [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**`language`** zh\_CN

**`classdesc`** 添加组件实例

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                                              | Description |
| ------ | ----------------------------------------------------------------- | ----------- |
| `comp` | [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md) | 组件实例        |

**Returns**

[`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**Defined in**

[framework/scene/gameobject.ts:344](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L344)

***

#### dispose

▸ **dispose**(): `void`

**`language`** zh\_CN

**`classdesc`** 释放gameObject

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/scene/gameobject.ts:756](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L756)

***

#### getComponent

▸ **getComponent**(`type`): [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**`language`** zh\_CN

**`classdesc`** 根据类型获取组件 只是自己身上找到的第一个

**`version`** m4m 1.0

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `type` | `string` | 组件类型        |

**Returns**

[`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**Defined in**

[framework/scene/gameobject.ts:467](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L467)

***

#### getComponentInParent

▸ **getComponentInParent**(`type`): [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**`language`** zh\_CN

**`classdesc`** 根据组件类型获取自己这条分支上父物体中该类型的组件 一直上溯到根节点

**`version`** m4m 1.0

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `type` | `string` | 组件类型        |

**Returns**

[`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**Defined in**

[framework/scene/gameobject.ts:582](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L582)

***

#### getComponents

▸ **getComponents**(): [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)\[]

**`language`** zh\_CN

**`classdesc`** 获取身上所有的组件

**`version`** m4m 1.0

**Returns**

[`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)\[]

**Defined in**

[framework/scene/gameobject.ts:488](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L488)

***

#### getComponentsInChildren

▸ **getComponentsInChildren**(`type`): [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)\[]

**`language`** zh\_CN

**`classdesc`** 获取自己和所有子物体中 所有该类型的组件

**`version`** m4m 1.0

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `type` | `string` | 组件类型        |

**Returns**

[`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)\[]

**Defined in**

[framework/scene/gameobject.ts:505](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L505)

***

#### getFirstComponentInChildren

▸ **getFirstComponentInChildren**(`type`): [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

获取当前节点下及子节点第一个能找到的组件

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `type` | `string` | 组件名称        |

**Returns**

[`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**Defined in**

[framework/scene/gameobject.ts:539](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L539)

***

#### getName

▸ **getName**(): `string`

**`language`** zh\_CN

**`classdesc`** 获取对应transform的name

**`version`** m4m 1.0

**Returns**

`string`

**Defined in**

[framework/scene/gameobject.ts:270](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L270)

***

#### getScene

▸ **getScene**(): [`scene`](m4m.framework.scene.md)

**`language`** zh\_CN

**`classdesc`** 获取物体所在场景实例

**`version`** m4m 1.0

**Returns**

[`scene`](m4m.framework.scene.md)

**Defined in**

[framework/scene/gameobject.ts:111](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L111)

***

#### init

▸ **init**(`bePlay?`): `void`

**`language`** zh\_CN

**`classdesc`** 初始化 主要是组件的初始化

**`version`** m4m 1.0

**Parameters**

| Name     | Type      | Default value |
| -------- | --------- | ------------- |
| `bePlay` | `boolean` | `false`       |

**Returns**

`void`

**Defined in**

[framework/scene/gameobject.ts:283](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L283)

***

#### removeAllComponents

▸ **removeAllComponents**(): `void`

**`language`** zh\_CN

**`classdesc`** 移出所有组件

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/scene/gameobject.ts:703](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L703)

***

#### removeComponent

▸ **removeComponent**(`comp`): `void`

**`language`** zh\_CN

**`classdesc`** 根据组件实例移出组件

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                                              | Description |
| ------ | ----------------------------------------------------------------- | ----------- |
| `comp` | [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md) | 组件实例        |

**Returns**

`void`

**Defined in**

[framework/scene/gameobject.ts:620](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L620)

***

#### removeComponentByTypeName

▸ **removeComponentByTypeName**(`type`): [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**`language`** zh\_CN

**`classdesc`** 根据组件类型移出组件

**`version`** m4m 1.0

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `type` | `string` | 组件类型        |

**Returns**

[`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**Defined in**

[framework/scene/gameobject.ts:661](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L661)

***

#### update

▸ **update**(`delta`): `void`

**`language`** zh\_CN

**`classdesc`** 主update

**`version`** m4m 1.0

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Defined in**

[framework/scene/gameobject.ts:312](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L312)

### Properties

#### camera

• **camera**: [`camera`](m4m.framework.camera.md)

**`language`** zh\_CN

**`classdesc`** 相机组件 可为空

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:195](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L195)

***

#### collider

• **collider**: [`ICollider`](../interfaces/m4m.framework.ICollider.md)

**`language`** zh\_CN

**`classdesc`** 碰撞盒组件 可为空

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:214](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L214)

***

#### componentTypes

• **componentTypes**: `Object` = `{}`

**Index signature**

▪ \[key: `string`]: `boolean`

**Defined in**

[framework/scene/gameobject.ts:177](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L177)

***

#### components

• **components**: [`nodeComponent`](m4m.framework.nodeComponent.md)\[] = `[]`

**`language`** zh\_CN

**`classdesc`** 组件列表

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:176](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L176)

***

#### hideFlags

• **hideFlags**: [`HideFlags`](../enums/m4m.framework.HideFlags.md) = `HideFlags.None`

**`language`** zh\_CN

**`classdesc`** 隐匿标记

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:144](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L144)

***

#### isStatic

• **isStatic**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 对象是静态

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:154](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L154)

***

#### layer

• **layer**: `number`

**`language`** zh\_CN

**`classdesc`** 对象layer (取值范围0\~31)

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:125](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L125)

***

#### light

• **light**: [`light`](m4m.framework.light.md)

**`language`** zh\_CN

**`classdesc`** 灯光组件 可为空

**`param`**

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:205](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L205)

***

#### renderer

• **renderer**: [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)

**`language`** zh\_CN

**`classdesc`** 渲染组件 可为空

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:187](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L187)

***

#### tag

• **tag**: `string` = `StringUtil.builtinTag_Untagged`

**`language`** zh\_CN

**`classdesc`** 对象字符标签

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L134)

***

#### transform

• **transform**: [`transform`](m4m.framework.transform.md)

**`language`** zh\_CN

**`classdesc`** gameObject必须依赖transform存在

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:164](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L164)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"gameObject"`

**Defined in**

[framework/scene/gameobject.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L103)

### Constructors

#### constructor

• **new gameObject**()

### Accessors

#### visible

• `get` **visible**(): `boolean`

**`language`** zh\_CN

**`classdesc`** 获取自身的可见状态

**`version`** m4m 1.0

**Returns**

`boolean`

**Defined in**

[framework/scene/gameobject.ts:241](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L241)

• `set` **visible**(`val`): `void`

**`language`** zh\_CN

**`classdesc`** 设置自身的可见状态

**`version`** m4m 1.0

**Parameters**

| Name  | Type      |
| ----- | --------- |
| `val` | `boolean` |

**Returns**

`void`

**Defined in**

[framework/scene/gameobject.ts:254](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L254)

***

#### visibleInScene

• `get` **visibleInScene**(): `boolean`

**`language`** zh\_CN

**`classdesc`** 获取在场景中的可见状态

**`version`** m4m 1.0

**Returns**

`boolean`

**Defined in**

[framework/scene/gameobject.ts:225](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L225)
