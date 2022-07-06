# m4m.framework.canvas

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / canvas

## Class: canvas

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).canvas

**`language`** zh\_CN

**`classdesc`** 2d节点的容器类

**`version`** m4m 1.0

### Table of contents

#### Methods

* [CanvasPosToModelPos](m4m.framework.canvas.md#canvaspostomodelpos)
* [ModelPosToCanvasPos](m4m.framework.canvas.md#modelpostocanvaspos)
* [addChild](m4m.framework.canvas.md#addchild)
* [burstPointEvent](m4m.framework.canvas.md#burstpointevent)
* [canvasPosToClipPos](m4m.framework.canvas.md#canvaspostoclippos)
* [clipPosToCanvasPos](m4m.framework.canvas.md#clippostocanvaspos)
* [drawScene](m4m.framework.canvas.md#drawscene)
* [getChild](m4m.framework.canvas.md#getchild)
* [getChildCount](m4m.framework.canvas.md#getchildcount)
* [getChildren](m4m.framework.canvas.md#getchildren)
* [getRoot](m4m.framework.canvas.md#getroot)
* [pushRawData](m4m.framework.canvas.md#pushrawdata)
* [removeChild](m4m.framework.canvas.md#removechild)
* [render](m4m.framework.canvas.md#render)
* [rootSizeAdjust](m4m.framework.canvas.md#rootsizeadjust)
* [update](m4m.framework.canvas.md#update)
* [updateNodeTree](m4m.framework.canvas.md#updatenodetree)

#### Properties

* [afterRender](m4m.framework.canvas.md#afterrender)
* [assetmgr](m4m.framework.canvas.md#assetmgr)
* [batcher](m4m.framework.canvas.md#batcher)
* [beforeRender](m4m.framework.canvas.md#beforerender)
* [enableOutsideRenderClip](m4m.framework.canvas.md#enableoutsiderenderclip)
* [enableUIEvent](m4m.framework.canvas.md#enableuievent)
* [is2dUI](m4m.framework.canvas.md#is2dui)
* [isDrawByDepth](m4m.framework.canvas.md#isdrawbydepth)
* [isForceLabelTopRender](m4m.framework.canvas.md#isforcelabeltoprender)
* [onLateUpdate](m4m.framework.canvas.md#onlateupdate)
* [onPreUpdate](m4m.framework.canvas.md#onpreupdate)
* [parentTrans](m4m.framework.canvas.md#parenttrans)
* [pixelHeight](m4m.framework.canvas.md#pixelheight)
* [pixelWidth](m4m.framework.canvas.md#pixelwidth)
* [scene](m4m.framework.canvas.md#scene)
* [webgl](m4m.framework.canvas.md#webgl)
* [ClassName](m4m.framework.canvas.md#classname)
* [depthTag](m4m.framework.canvas.md#depthtag)
* [flowIndexTag](m4m.framework.canvas.md#flowindextag)

#### Constructors

* [constructor](m4m.framework.canvas.md#constructor)

### Methods

#### CanvasPosToModelPos

▸ **CanvasPosToModelPos**(`canvasPos`, `outClipPos`): `void`

\[过时接口,完全弃用]

**`version`** m4m 1.0

**Parameters**

| Name         | Type      |
| ------------ | --------- |
| `canvasPos`  | `vector2` |
| `outClipPos` | `vector2` |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:948](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L948)

***

#### ModelPosToCanvasPos

▸ **ModelPosToCanvasPos**(`clipPos`, `outCanvasPos`): `void`

\[过时接口,完全弃用]

**`version`** m4m 1.0

**Parameters**

| Name           | Type      |
| -------------- | --------- |
| `clipPos`      | `vector2` |
| `outCanvasPos` | `vector2` |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:923](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L923)

***

#### addChild

▸ **addChild**(`node`): `void`

**`language`** zh\_CN

**`classdesc`** 添加2d节点

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                          | Description |
| ------ | --------------------------------------------- | ----------- |
| `node` | [`transform2D`](m4m.framework.transform2D.md) | 要添加的2d节点实例  |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:244](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L244)

***

#### burstPointEvent

▸ **burstPointEvent**(`touch`, `XOnModelSpace`, `YOnModelSpace`, `multiTouch?`): `void`

触发 point 事件流

**Parameters**

| Name            | Type      | Default value | Description |
| --------------- | --------- | ------------- | ----------- |
| `touch`         | `boolean` | `undefined`   | 是否有点        |
| `XOnModelSpace` | `number`  | `undefined`   | 坐标x         |
| `YOnModelSpace` | `number`  | `undefined`   | 坐标y         |
| `multiTouch`    | `boolean` | `false`       | 多点          |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:374](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L374)

***

#### canvasPosToClipPos

▸ **canvasPosToClipPos**(`canvasPos`, `outClipPos`): `void`

**`language`** zh\_CN

**`classdesc`** canvas坐标 转到 裁剪空间坐标

**`version`** m4m 1.0

**Parameters**

| Name         | Type      | Description |
| ------------ | --------- | ----------- |
| `canvasPos`  | `vector2` | canvas坐标    |
| `outClipPos` | `vector2` | model空间坐标   |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:961](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L961)

***

#### clipPosToCanvasPos

▸ **clipPosToCanvasPos**(`clipPos`, `outCanvasPos`): `void`

**`language`** zh\_CN

**`classdesc`** 裁剪空间坐标 转到 canvas 坐标

**`version`** m4m 1.0

**Parameters**

| Name           | Type      | Description |
| -------------- | --------- | ----------- |
| `clipPos`      | `vector2` | 屏幕空间坐标      |
| `outCanvasPos` | `vector2` | canvas 坐标   |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:936](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L936)

***

#### drawScene

▸ **drawScene**(`node`, `context`, `assetmgr`): `void`

**`language`** zh\_CN

**`classdesc`** 绘制2d节点

**`version`** m4m 1.0

**Parameters**

| Name       | Type                                          | Description |
| ---------- | --------------------------------------------- | ----------- |
| `node`     | [`transform2D`](m4m.framework.transform2D.md) | 要绘制的2d节点    |
| `context`  | `renderContext`                               | 渲染上下文       |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md)       | 资源管理类的实例    |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:677](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L677)

***

#### getChild

▸ **getChild**(`index`): [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh\_CN

**`classdesc`** 获取指定的孩子节点

**`version`** m4m 1.0

**Parameters**

| Name    | Type     | Description |
| ------- | -------- | ----------- |
| `index` | `number` | 位置索引        |

**Returns**

[`transform2D`](m4m.framework.transform2D.md)

**Defined in**

[framework/2d/canvas.ts:291](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L291)

***

#### getChildCount

▸ **getChildCount**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取孩子节点的数量

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/2d/canvas.ts:278](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L278)

***

#### getChildren

▸ **getChildren**(): [`transform2D`](m4m.framework.transform2D.md)\[]

**`language`** zh\_CN

**`classdesc`** 获取所有孩子节点

**`version`** m4m 1.0

**Returns**

[`transform2D`](m4m.framework.transform2D.md)\[]

**Defined in**

[framework/2d/canvas.ts:267](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L267)

***

#### getRoot

▸ **getRoot**(): [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh\_CN

**`classdesc`** 获取canvas的根节点

**`version`** m4m 1.0

**Returns**

[`transform2D`](m4m.framework.transform2D.md)

**Defined in**

[framework/2d/canvas.ts:910](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L910)

***

#### pushRawData

▸ **pushRawData**(`mat`, `data`): `void`

**`language`** zh\_CN

**`classdesc`** 提交原始数据

所有的2d渲染组件将数据提交到这里最后由批处理完成绘制

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                    | Description |
| ------ | --------------------------------------- | ----------- |
| `mat`  | [`material`](m4m.framework.material.md) | 材质          |
| `data` | `number`\[]                             | 2d渲染组件的顶点数据 |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:614](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L614)

***

#### removeChild

▸ **removeChild**(`node`): `void`

**`language`** zh\_CN

**`classdesc`** 移除2d节点

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                          | Description |
| ------ | --------------------------------------------- | ----------- |
| `node` | [`transform2D`](m4m.framework.transform2D.md) | 要移除的2d节点实例  |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:256](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L256)

***

#### render

▸ **render**(`context`, `assetmgr`): `void`

**`language`** zh\_CN

**`classdesc`** 渲染

**`version`** m4m 1.0

**Parameters**

| Name       | Type                                    | Description |
| ---------- | --------------------------------------- | ----------- |
| `context`  | `renderContext`                         | 渲染上下文       |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) | 资源管理类的实例    |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:558](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L558)

***

#### rootSizeAdjust

▸ **rootSizeAdjust**(): `void`

根节点 尺寸 调整

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:325](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L325)

***

#### update

▸ **update**(`delta`, `touch`, `XOnModelSpace`, `YOnModelSpace`, `multiTouch?`): `void`

**`language`** zh\_CN

**`classdesc`** 更新

**`version`** m4m 1.0

**Parameters**

| Name            | Type      | Default value | Description   |
| --------------- | --------- | ------------- | ------------- |
| `delta`         | `number`  | `undefined`   | 两次update的间隔时间 |
| `touch`         | `boolean` | `undefined`   | 是否接收到事件       |
| `XOnModelSpace` | `number`  | `undefined`   | 模型空间下的x偏移     |
| `YOnModelSpace` | `number`  | `undefined`   | 模型空间下的y偏移     |
| `multiTouch`    | `boolean` | `false`       | 是否多点中         |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:316](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L316)

***

#### updateNodeTree

▸ **updateNodeTree**(`delta`): `void`

刷新节点树

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Defined in**

[framework/2d/canvas.ts:353](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L353)

### Properties

#### afterRender

• **afterRender**: `Function`

**`language`** zh\_CN

**`classdesc`** 渲染完成后的回调

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:538](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L538)

***

#### assetmgr

• **assetmgr**: [`assetMgr`](m4m.framework.assetMgr.md)

**`language`** zh\_CN

**`classdesc`** 资源管理类的实例

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:663](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L663)

***

#### batcher

• **batcher**: [`batcher2D`](m4m.framework.batcher2D.md)

**`language`** zh\_CN

**`classdesc`** 2d批处理类，用来收集2d节点，完成绘制

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:211](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L211)

***

#### beforeRender

• **beforeRender**: `Function`

**`language`** zh\_CN

**`classdesc`** 渲染前回调

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:547](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L547)

***

#### enableOutsideRenderClip

• **enableOutsideRenderClip**: `boolean` = `true`

启用 剔除超出可视范围的渲染节点

**Defined in**

[framework/2d/canvas.ts:193](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L193)

***

#### enableUIEvent

• **enableUIEvent**: `boolean` = `true`

启用UI事件

**Defined in**

[framework/2d/canvas.ts:190](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L190)

***

#### is2dUI

• **is2dUI**: `boolean` = `true`

**`language`** zh\_CN

**`classdesc`** 用于区分当前容器是在overlay(2D)还是canvasrenderer(3D)下

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:166](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L166)

***

#### isDrawByDepth

• **isDrawByDepth**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** UI绘制使用深度排序规则 (可以降低drawcall , 但是会一定程度增加CPU计算量,视情况使用)

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:176](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L176)

***

#### isForceLabelTopRender

• **isForceLabelTopRender**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 强行lable置顶渲染（用于优化Drawcall）

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:185](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L185)

***

#### onLateUpdate

• **onLateUpdate**: (`dt`: `number`) => `any`

**Type declaration**

▸ (`dt`): `any`

canvas 更新后回调函数

**Parameters**

| Name | Type     |
| ---- | -------- |
| `dt` | `number` |

**Returns**

`any`

**Defined in**

[framework/2d/canvas.ts:234](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L234)

***

#### onPreUpdate

• **onPreUpdate**: (`dt`: `number`) => `any`

**Type declaration**

▸ (`dt`): `any`

canvas 更新前回调函数

**Parameters**

| Name | Type     |
| ---- | -------- |
| `dt` | `number` |

**Returns**

`any`

**Defined in**

[framework/2d/canvas.ts:232](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L232)

***

#### parentTrans

• **parentTrans**: [`transform`](m4m.framework.transform.md)

**`language`** zh\_CN

**`classdesc`** 如果是在canvasrenderer下，这里可以获取到canvasrenderer所在的transform节点

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:202](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L202)

***

#### pixelHeight

• **pixelHeight**: `number` = `480`

**`language`** zh\_CN

**`classdesc`** 画布使用的像素高度

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:898](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L898)

***

#### pixelWidth

• **pixelWidth**: `number` = `640`

**`language`** zh\_CN

**`classdesc`** 画布使用的像素宽度

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:888](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L888)

***

#### scene

• **scene**: [`scene`](m4m.framework.scene.md)

**`language`** zh\_CN

**`classdesc`** 当前所在场景

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:229](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L229)

***

#### webgl

• **webgl**: `WebGLRenderingContext`

**`language`** zh\_CN

**`classdesc`** webgl实例

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:220](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L220)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"canvas"`

**Defined in**

[framework/2d/canvas.ts:138](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L138)

***

#### depthTag

▪ `Static` `Readonly` **depthTag**: `"__depthTag__"`

**Defined in**

[framework/2d/canvas.ts:719](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L719)

***

#### flowIndexTag

▪ `Static` `Readonly` **flowIndexTag**: `"__flowIndexTag__"`

**Defined in**

[framework/2d/canvas.ts:720](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L720)

### Constructors

#### constructor

• **new canvas**()

**`language`** zh\_CN

**`classdesc`** 构造函数

**`version`** m4m 1.0

**Defined in**

[framework/2d/canvas.ts:150](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/canvas.ts#L150)
