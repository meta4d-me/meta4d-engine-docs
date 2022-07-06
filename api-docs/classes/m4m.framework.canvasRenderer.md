# m4m.framework.canvasRenderer

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / canvasRenderer

## Class: canvasRenderer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).canvasRenderer

**`language`** zh\_CN

**`classdesc`** 3DUI的容器类

3d组件与overlay(2DUI)相对应。

**`version`** m4m 1.0

### Implements

* [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)
* [`ICollider`](../interfaces/m4m.framework.ICollider.md)

### Table of contents

#### Methods

* [addChild](m4m.framework.canvasRenderer.md#addchild)
* [calCanvasPosToWorldPos](m4m.framework.canvasRenderer.md#calcanvaspostoworldpos)
* [calScreenPosToCanvasPos](m4m.framework.canvasRenderer.md#calscreenpostocanvaspos)
* [getChild](m4m.framework.canvasRenderer.md#getchild)
* [getChildCount](m4m.framework.canvasRenderer.md#getchildcount)
* [getChildren](m4m.framework.canvasRenderer.md#getchildren)
* [onPlay](m4m.framework.canvasRenderer.md#onplay)
* [pick2d](m4m.framework.canvasRenderer.md#pick2d)
* [pickAll2d](m4m.framework.canvasRenderer.md#pickall2d)
* [pickModelPos](m4m.framework.canvasRenderer.md#pickmodelpos)
* [removeChild](m4m.framework.canvasRenderer.md#removechild)

#### Properties

* [cameraTouch](m4m.framework.canvasRenderer.md#cameratouch)
* [canvas](m4m.framework.canvasRenderer.md#canvas)
* [gameObject](m4m.framework.canvasRenderer.md#gameobject)
* [inputmgr](m4m.framework.canvasRenderer.md#inputmgr)
* [layer](m4m.framework.canvasRenderer.md#layer)
* [ClassName](m4m.framework.canvasRenderer.md#classname)

#### Accessors

* [dontFrustumCulling](m4m.framework.canvasRenderer.md#dontfrustumculling)
* [renderLayer](m4m.framework.canvasRenderer.md#renderlayer)

### Methods

#### addChild

▸ **addChild**(`node`): `void`

**`language`** zh\_CN

**`classdesc`** 添加2d子节点

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                          |
| ------ | --------------------------------------------- |
| `node` | [`transform2D`](m4m.framework.transform2D.md) |

**Returns**

`void`

**Defined in**

[framework/2d/canvasrenderer.ts:126](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L126)

***

#### calCanvasPosToWorldPos

▸ **calCanvasPosToWorldPos**(`from`, `out`): `void`

**`language`** zh\_CN

**`classdesc`** canvas坐标 转到 世界空间坐标

**`version`** m4m 1.0

**Parameters**

| Name   | Type      | Description     |
| ------ | --------- | --------------- |
| `from` | `vector2` | Transform2D世界坐标 |
| `out`  | `vector3` | 返回结果v2          |

**Returns**

`void`

**Defined in**

[framework/2d/canvasrenderer.ts:341](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L341)

***

#### calScreenPosToCanvasPos

▸ **calScreenPosToCanvasPos**(`camera`, `screenPos`, `outCanvasPos`): `void`

**`language`** zh\_CN

**`classdesc`** 屏幕空间坐标 转到 canvas坐标

**`version`** m4m 1.0

**Parameters**

| Name           | Type                                |
| -------------- | ----------------------------------- |
| `camera`       | [`camera`](m4m.framework.camera.md) |
| `screenPos`    | `vector2`                           |
| `outCanvasPos` | `vector2`                           |

**Returns**

`void`

**Defined in**

[framework/2d/canvasrenderer.ts:321](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L321)

***

#### getChild

▸ **getChild**(`index`): [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh\_CN

**`classdesc`** 获取2d子节点

**`version`** m4m 1.0

**Parameters**

| Name    | Type     | Description |
| ------- | -------- | ----------- |
| `index` | `number` | 索引          |

**Returns**

[`transform2D`](m4m.framework.transform2D.md)

**Defined in**

[framework/2d/canvasrenderer.ts:175](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L175)

***

#### getChildCount

▸ **getChildCount**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取2d子节点的数量

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/2d/canvasrenderer.ts:162](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L162)

***

#### getChildren

▸ **getChildren**(): [`transform2D`](m4m.framework.transform2D.md)\[]

**`language`** zh\_CN

**`classdesc`** 获取所有2d子节点

**`version`** m4m 1.0

**Returns**

[`transform2D`](m4m.framework.transform2D.md)\[]

**Defined in**

[framework/2d/canvasrenderer.ts:150](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L150)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[onPlay](../interfaces/m4m.framework.IRenderer.md#onplay)

**Defined in**

[framework/2d/canvasrenderer.ts:114](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L114)

***

#### pick2d

▸ **pick2d**(`ray`): [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh\_CN

**`classdesc`** 射线拣选transform2D

**`version`** m4m 1.0

**Parameters**

| Name  | Type                          | Description |
| ----- | ----------------------------- | ----------- |
| `ray` | [`ray`](m4m.framework.ray.md) | 射线          |

**Returns**

[`transform2D`](m4m.framework.transform2D.md)

**Defined in**

[framework/2d/canvasrenderer.ts:279](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L279)

***

#### pickAll2d

▸ **pickAll2d**(`ray`): [`transform2D`](m4m.framework.transform2D.md)\[]

**`language`** zh\_CN

**`classdesc`** 射线拣选 全部 transform2D

**`version`** m4m 1.0

**Parameters**

| Name  | Type                          | Description |
| ----- | ----------------------------- | ----------- |
| `ray` | [`ray`](m4m.framework.ray.md) | 射线          |

**Returns**

[`transform2D`](m4m.framework.transform2D.md)\[]

**Defined in**

[framework/2d/canvasrenderer.ts:258](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L258)

***

#### pickModelPos

▸ **pickModelPos**(`ray`, `outModelPos`): `boolean`

**`language`** zh\_CN

**`classdesc`** 射线碰撞 获取 Model坐标点

**`version`** m4m 1.0

**Parameters**

| Name          | Type                          | Description |
| ------------- | ----------------------------- | ----------- |
| `ray`         | [`ray`](m4m.framework.ray.md) | 射线          |
| `outModelPos` | `vector2`                     | -           |

**Returns**

`boolean`

**Defined in**

[framework/2d/canvasrenderer.ts:227](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L227)

***

#### removeChild

▸ **removeChild**(`node`): `void`

**`language`** zh\_CN

**`classdesc`** 移除2d子节点

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                          |
| ------ | --------------------------------------------- |
| `node` | [`transform2D`](m4m.framework.transform2D.md) |

**Returns**

`void`

**Defined in**

[framework/2d/canvasrenderer.ts:138](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L138)

### Properties

#### cameraTouch

• **cameraTouch**: [`camera`](m4m.framework.camera.md)

**Defined in**

[framework/2d/canvasrenderer.ts:102](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L102)

***

#### canvas

• **canvas**: [`canvas`](m4m.framework.canvas.md)

**Defined in**

[framework/2d/canvasrenderer.ts:99](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L99)

***

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**Implementation of**

[ICollider](../interfaces/m4m.framework.ICollider.md).[gameObject](../interfaces/m4m.framework.ICollider.md#gameobject)

**Defined in**

[framework/2d/canvasrenderer.ts:97](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L97)

***

#### inputmgr

• **inputmgr**: [`inputMgr`](m4m.framework.inputMgr.md)

**Defined in**

[framework/2d/canvasrenderer.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L100)

***

#### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Common`

**`language`** zh\_CN

**`classdesc`** layer类型

**`version`** m4m 1.0

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[layer](../interfaces/m4m.framework.IRenderer.md#layer)

**Defined in**

[framework/2d/canvasrenderer.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L90)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"canvasRenderer"`

**Defined in**

[framework/2d/canvasrenderer.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L20)

### Accessors

#### dontFrustumCulling

• `get` **dontFrustumCulling**(): `boolean`

**`language`** zh\_CN

**`classdesc`** 不受视锥剔除

**`version`** m4m 1.0

**Returns**

`boolean`

**Defined in**

[framework/2d/canvasrenderer.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L45)

• `set` **dontFrustumCulling**(`val`): `void`

**`language`** zh\_CN

**`classdesc`** 不受视锥剔除

**`version`** m4m 1.0

**Parameters**

| Name  | Type      |
| ----- | --------- |
| `val` | `boolean` |

**Returns**

`void`

**Defined in**

[framework/2d/canvasrenderer.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L53)

***

#### renderLayer

• `get` **renderLayer**(): `number`

**Returns**

`number`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

**Defined in**

[framework/2d/canvasrenderer.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L32)

• `set` **renderLayer**(`layer`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `layer` | `number` |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

**Defined in**

[framework/2d/canvasrenderer.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvasrenderer.ts#L33)
