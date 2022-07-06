# m4m.framework.I2DComponent

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / I2DComponent

## Interface: I2DComponent

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).I2DComponent

**`language`** zh\_CN

**`classdesc`** 2d组件的接口

**`version`** m4m 1.0

### Hierarchy

*   **`I2DComponent`**

    ↳ [`IRectRenderer`](m4m.framework.IRectRenderer.md)

### Implemented by

* [`behaviour2d`](../classes/m4m.framework.behaviour2d.md)
* [`boxcollider2d`](../classes/m4m.framework.boxcollider2d.md)
* [`button`](../classes/m4m.framework.button.md)
* [`inputField`](../classes/m4m.framework.inputField.md)
* [`progressbar`](../classes/m4m.framework.progressbar.md)
* [`scrollRect`](../classes/m4m.framework.scrollRect.md)
* [`slideArea`](../classes/m4m.framework.slideArea.md)
* [`uirect`](../classes/m4m.framework.uirect.md)

### Table of contents

#### Methods

* [onPlay](m4m.framework.I2DComponent.md#onplay)
* [remove](m4m.framework.I2DComponent.md#remove)
* [start](m4m.framework.I2DComponent.md#start)
* [update](m4m.framework.I2DComponent.md#update)

#### Properties

* [transform](m4m.framework.I2DComponent.md#transform)

### Methods

#### onPlay

▸ **onPlay**(): `any`

**Returns**

`any`

**Defined in**

[framework/interfaces.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L32)

***

#### remove

▸ **remove**(): `any`

**Returns**

`any`

**Defined in**

[framework/interfaces.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L36)

***

#### start

▸ **start**(): `any`

**Returns**

`any`

**Defined in**

[framework/interfaces.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L33)

***

#### update

▸ **update**(`delta`): `any`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`any`

**Defined in**

[framework/interfaces.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L34)

### Properties

#### transform

• **transform**: [`transform2D`](../classes/m4m.framework.transform2D.md)

**Defined in**

[framework/interfaces.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L35)
