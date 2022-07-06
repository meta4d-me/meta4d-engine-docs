# m4m.framework.overlay2D

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / overlay2D

## Class: overlay2D

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).overlay2D

**`language`** zh\_CN

**`classdesc`** 2DUI的容器类，与canvasrender(3DUI)相对应。

**`version`** m4m 1.0

### Implements

* `IOverLay`
* [`IDisposable`](../interfaces/m4m.framework.IDisposable.md)

### Table of contents

#### Methods

* [addChild](m4m.framework.overlay2D.md#addchild)
* [calCanvasPosToScreenPos](m4m.framework.overlay2D.md#calcanvaspostoscreenpos)
* [calClipPosToScreenPos](m4m.framework.overlay2D.md#calclippostoscreenpos)
* [calModelPosToScreenPos](m4m.framework.overlay2D.md#calmodelpostoscreenpos)
* [calScreenPosToCanvasPos](m4m.framework.overlay2D.md#calscreenpostocanvaspos)
* [calScreenPosToClipPos](m4m.framework.overlay2D.md#calscreenpostoclippos)
* [calScreenPosToModelPos](m4m.framework.overlay2D.md#calscreenpostomodelpos)
* [dispose](m4m.framework.overlay2D.md#dispose)
* [getChild](m4m.framework.overlay2D.md#getchild)
* [getChildCount](m4m.framework.overlay2D.md#getchildcount)
* [getChildren](m4m.framework.overlay2D.md#getchildren)
* [pick2d](m4m.framework.overlay2D.md#pick2d)
* [removeChild](m4m.framework.overlay2D.md#removechild)

#### Constructors

* [constructor](m4m.framework.overlay2D.md#constructor)

#### Accessors

* [disposed](m4m.framework.overlay2D.md#disposed)

#### Properties

* [matchReference\_height](m4m.framework.overlay2D.md#matchreference\_height)
* [matchReference\_width](m4m.framework.overlay2D.md#matchreference\_width)
* [scaleMode](m4m.framework.overlay2D.md#scalemode)
* [screenMatchRate](m4m.framework.overlay2D.md#screenmatchrate)
* [sortOrder](m4m.framework.overlay2D.md#sortorder)
* [ClassName](m4m.framework.overlay2D.md#classname)
* [pointEventDirectMode](m4m.framework.overlay2D.md#pointeventdirectmode)

### Methods

#### addChild

▸ **addChild**(`node`): `void`

**`language`** zh\_CN

**`classdesc`** 添加2d子节点

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                          | Description |
| ------ | --------------------------------------------- | ----------- |
| `node` | [`transform2D`](m4m.framework.transform2D.md) | 2d节点实例      |

**Returns**

`void`

**Defined in**

[framework/2d/overlay2d.ts:180](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L180)

***

#### calCanvasPosToScreenPos

▸ **calCanvasPosToScreenPos**(`canvasPos`, `outScreenPos`): `void`

**`language`** zh\_CN

**`classdesc`** canvas坐标 转到 屏幕空间坐标

**`version`** m4m 1.0

**Parameters**

| Name           | Type      | Description |
| -------------- | --------- | ----------- |
| `canvasPos`    | `vector2` | canvas坐标    |
| `outScreenPos` | `vector2` | 输出的屏幕空间坐标   |

**Returns**

`void`

**Defined in**

[framework/2d/overlay2d.ts:424](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L424)

***

#### calClipPosToScreenPos

▸ **calClipPosToScreenPos**(`clipPos`, `outScreenPos`): `void`

**`language`** zh\_CN

**`classdesc`** Model坐标 转到 屏幕空间坐标

**`version`** m4m 1.0

**Parameters**

| Name           | Type      | Description |
| -------------- | --------- | ----------- |
| `clipPos`      | `vector2` | 裁剪空间坐标      |
| `outScreenPos` | `vector2` | 输出的屏幕空间坐标   |

**Returns**

`void`

**Defined in**

[framework/2d/overlay2d.ts:477](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L477)

***

#### calModelPosToScreenPos

▸ **calModelPosToScreenPos**(`clipPos`, `outScreenPos`): `void`

\[过时接口,完全弃用]

**`version`** m4m 1.0

**Parameters**

| Name           | Type      |
| -------------- | --------- |
| `clipPos`      | `vector2` |
| `outScreenPos` | `vector2` |

**Returns**

`void`

**Defined in**

[framework/2d/overlay2d.ts:464](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L464)

***

#### calScreenPosToCanvasPos

▸ **calScreenPosToCanvasPos**(`screenPos`, `outCanvasPos`): `void`

**`language`** zh\_CN

**`classdesc`** 屏幕空间坐标 转到 canvas坐标

**`version`** m4m 1.0

**Parameters**

| Name           | Type      |
| -------------- | --------- |
| `screenPos`    | `vector2` |
| `outCanvasPos` | `vector2` |

**Returns**

`void`

**Defined in**

[framework/2d/overlay2d.ts:400](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L400)

***

#### calScreenPosToClipPos

▸ **calScreenPosToClipPos**(`screenPos`, `outClipPos`): `void`

**`language`** zh\_CN

**`classdesc`** 屏幕空间坐标 转到 裁剪空间坐标

**`version`** m4m 1.0

**Parameters**

| Name         | Type      |
| ------------ | --------- |
| `screenPos`  | `vector2` |
| `outClipPos` | `vector2` |

**Returns**

`void`

**Defined in**

[framework/2d/overlay2d.ts:448](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L448)

***

#### calScreenPosToModelPos

▸ **calScreenPosToModelPos**(`screenPos`, `outClipPos`): `void`

\[过时接口,完全弃用]

**`version`** m4m 1.0

**Parameters**

| Name         | Type      |
| ------------ | --------- |
| `screenPos`  | `vector2` |
| `outClipPos` | `vector2` |

**Returns**

`void`

**Defined in**

[framework/2d/overlay2d.ts:435](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L435)

***

#### dispose

▸ **dispose**(): `void`

销毁

**Returns**

`void`

**Implementation of**

[IDisposable](../interfaces/m4m.framework.IDisposable.md).[dispose](../interfaces/m4m.framework.IDisposable.md#dispose)

**Defined in**

[framework/2d/overlay2d.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L43)

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

[framework/2d/overlay2d.ts:226](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L226)

***

#### getChildCount

▸ **getChildCount**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取2d子节点的数量

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/2d/overlay2d.ts:214](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L214)

***

#### getChildren

▸ **getChildren**(): [`transform2D`](m4m.framework.transform2D.md)\[]

**`language`** zh\_CN

**`classdesc`** 获取所有的2d子节点

**`version`** m4m 1.0

**Returns**

[`transform2D`](m4m.framework.transform2D.md)\[]

**Defined in**

[framework/2d/overlay2d.ts:203](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L203)

***

#### pick2d

▸ **pick2d**(`mx`, `my`, `tolerance?`): [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh\_CN

**`classdesc`** 投射拣选检测

**`version`** m4m 1.0

**Parameters**

| Name        | Type     | Default value | Description |
| ----------- | -------- | ------------- | ----------- |
| `mx`        | `number` | `undefined`   | x偏移         |
| `my`        | `number` | `undefined`   | y偏移         |
| `tolerance` | `number` | `0`           | -           |

**Returns**

[`transform2D`](m4m.framework.transform2D.md)

**Defined in**

[framework/2d/overlay2d.ts:357](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L357)

***

#### removeChild

▸ **removeChild**(`node`): `void`

**`language`** zh\_CN

**`classdesc`** 移除2d子节点

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                          | Description |
| ------ | --------------------------------------------- | ----------- |
| `node` | [`transform2D`](m4m.framework.transform2D.md) | 2d节点实例      |

**Returns**

`void`

**Defined in**

[framework/2d/overlay2d.ts:192](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L192)

### Constructors

#### constructor

• **new overlay2D**()

**`language`** zh\_CN

**`classdesc`** 构造函数

**`version`** m4m 1.0

**Defined in**

[framework/2d/overlay2d.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L35)

### Accessors

#### disposed

• `get` **disposed**(): `boolean`

是否已销毁

**Returns**

`boolean`

**Implementation of**

[IDisposable](../interfaces/m4m.framework.IDisposable.md).[disposed](../interfaces/m4m.framework.IDisposable.md#disposed)

**Defined in**

[framework/2d/overlay2d.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L42)

### Properties

#### matchReference\_height

• **matchReference\_height**: `number` = `600`

**`language`** zh\_CN

**`classdesc`** 屏幕匹配参考高度

**`version`** m4m 1.0

**Defined in**

[framework/2d/overlay2d.ts:145](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L145)

***

#### matchReference\_width

• **matchReference\_width**: `number` = `800`

**`language`** zh\_CN

**`classdesc`** 屏幕匹配参考宽度

**`version`** m4m 1.0

**Defined in**

[framework/2d/overlay2d.ts:135](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L135)

***

#### scaleMode

• **scaleMode**: [`UIScaleMode`](../enums/m4m.framework.UIScaleMode.md) = `UIScaleMode.CONSTANT_PIXEL_SIZE`

**`language`** zh\_CN

**`classdesc`** 缩放模式

配合参数 ： matchReference\_height matchReference\_width screenMatchRate

**`version`** m4m 1.0

**Defined in**

[framework/2d/overlay2d.ts:160](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L160)

***

#### screenMatchRate

• **screenMatchRate**: `number` = `0`

**`language`** zh\_CN

**`classdesc`** 屏幕宽高匹配模式 (range 0-1 =0:固定宽 =1:固定高)

**`version`** m4m 1.0

**Defined in**

[framework/2d/overlay2d.ts:125](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L125)

***

#### sortOrder

• **sortOrder**: `number` = `0`

**`language`** zh\_CN

**`classdesc`** 渲染排序

**`version`** m4m 1.0

**Implementation of**

IOverLay.sortOrder

**Defined in**

[framework/2d/overlay2d.ts:170](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L170)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"overlay2D"`

**Defined in**

[framework/2d/overlay2d.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L24)

***

#### pointEventDirectMode

▪ `Static` **pointEventDirectMode**: `boolean` = `true`

point事件 直接模式（默认True,在dom输入原生帧直接触发）

**Defined in**

[framework/2d/overlay2d.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/overlay2d.ts#L26)
