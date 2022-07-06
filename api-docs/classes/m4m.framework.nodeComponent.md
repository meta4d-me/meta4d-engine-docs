# m4m.framework.nodeComponent

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / nodeComponent

## Class: nodeComponent

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).nodeComponent

**`language`** zh\_CN

**`classdesc`** 组件接口

**`version`** m4m 1.0

### Table of contents

#### Properties

* [OnPlayed](m4m.framework.nodeComponent.md#onplayed)
* [comp](m4m.framework.nodeComponent.md#comp)
* [init](m4m.framework.nodeComponent.md#init)
* [ClassName](m4m.framework.nodeComponent.md#classname)

#### Constructors

* [constructor](m4m.framework.nodeComponent.md#constructor)

### Properties

#### OnPlayed

• **OnPlayed**: `boolean` = `false`

onPlay是否调用过了

**Defined in**

[framework/scene/gameobject.ts:84](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L84)

***

#### comp

• **comp**: [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

**`language`** zh\_CN

**`classdesc`** 组件实例

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L71)

***

#### init

• **init**: `boolean`

**`language`** zh\_CN

**`classdesc`** 是否初始化过

**`version`** m4m 1.0

**Defined in**

[framework/scene/gameobject.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L79)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"nodeComponent"`

**Defined in**

[framework/scene/gameobject.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L61)

### Constructors

#### constructor

• **new nodeComponent**(`comp`, `init?`)

**Parameters**

| Name   | Type                                                              | Default value |
| ------ | ----------------------------------------------------------------- | ------------- |
| `comp` | [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md) | `undefined`   |
| `init` | `boolean`                                                         | `false`       |

**Defined in**

[framework/scene/gameobject.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/gameobject.ts#L86)
