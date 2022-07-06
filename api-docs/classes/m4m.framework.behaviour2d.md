# m4m.framework.behaviour2d

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / behaviour2d

## Class: behaviour2d

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).behaviour2d

### Hierarchy

*   **`behaviour2d`**

    ↳ [`physics2DBody`](m4m.framework.physics2DBody.md)

### Implements

* [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)
* [`IEnabled`](../interfaces/m4m.framework.IEnabled.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.behaviour2d.md#constructor)

#### Properties

* [enabled](m4m.framework.behaviour2d.md#enabled)
* [transform](m4m.framework.behaviour2d.md#transform)

#### Methods

* [onPlay](m4m.framework.behaviour2d.md#onplay)
* [remove](m4m.framework.behaviour2d.md#remove)
* [start](m4m.framework.behaviour2d.md#start)
* [update](m4m.framework.behaviour2d.md#update)

### Constructors

#### constructor

• **new behaviour2d**()

### Properties

#### enabled

• **enabled**: `boolean` = `true`

**`language`** zh\_CN

**`classdesc`** 组件启用

**`version`** m4m 1.0

**Implementation of**

[IEnabled](../interfaces/m4m.framework.IEnabled.md).[enabled](../interfaces/m4m.framework.IEnabled.md#enabled)

**Defined in**

[framework/2d/component/behaviour2d.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/behaviour2d.ts#L16)

***

#### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh\_CN

**`classdesc`** 挂载的transform

**`version`** m4m 1.0

**Implementation of**

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[transform](../interfaces/m4m.framework.I2DComponent.md#transform)

**Defined in**

[framework/2d/component/behaviour2d.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/behaviour2d.ts#L25)

### Methods

#### onPlay

▸ **onPlay**(): `void`

初始化使用 在start 之后

**Returns**

`void`

**Implementation of**

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[onPlay](../interfaces/m4m.framework.I2DComponent.md#onplay)

**Defined in**

[framework/2d/component/behaviour2d.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/behaviour2d.ts#L33)

***

#### remove

▸ **remove**(): `void`

**Returns**

`void`

**Implementation of**

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[remove](../interfaces/m4m.framework.I2DComponent.md#remove)

**Defined in**

[framework/2d/component/behaviour2d.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/behaviour2d.ts#L40)

***

#### start

▸ **start**(): `void`

初始化使用

**Returns**

`void`

**Implementation of**

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[start](../interfaces/m4m.framework.I2DComponent.md#start)

**Defined in**

[framework/2d/component/behaviour2d.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/behaviour2d.ts#L28)

***

#### update

▸ **update**(`delta`): `void`

每帧调用一次

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Implementation of**

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[update](../interfaces/m4m.framework.I2DComponent.md#update)

**Defined in**

[framework/2d/component/behaviour2d.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/behaviour2d.ts#L37)
