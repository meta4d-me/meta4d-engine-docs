# m4m.framework.application

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / application

## Class: application

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).application

**`language`** zh\_CN

**`classdesc`** 引擎的主入口

**`version`** m4m 1.0

### Table of contents

#### Properties

* [OffOrientationUpdate](m4m.framework.application.md#offorientationupdate)
* [bePlay](m4m.framework.application.md#beplay)
* [ccHeight](m4m.framework.application.md#ccheight)
* [ccWidth](m4m.framework.application.md#ccwidth)
* [container](m4m.framework.application.md#container)
* [curcameraindex](m4m.framework.application.md#curcameraindex)
* [edModel](m4m.framework.application.md#edmodel)
* [globalMacros](m4m.framework.application.md#globalmacros)
* [limitFrame](m4m.framework.application.md#limitframe)
* [notify](m4m.framework.application.md#notify)
* [orientation](m4m.framework.application.md#orientation)
* [outcontainer](m4m.framework.application.md#outcontainer)
* [screenAdaptiveType](m4m.framework.application.md#screenadaptivetype)
* [shouldRotate](m4m.framework.application.md#shouldrotate)
* [stats](m4m.framework.application.md#stats)
* [webgl](m4m.framework.application.md#webgl)

#### Methods

* [addEditorCode](m4m.framework.application.md#addeditorcode)
* [addEditorCodeDirect](m4m.framework.application.md#addeditorcodedirect)
* [addUserCode](m4m.framework.application.md#addusercode)
* [addUserCodeDirect](m4m.framework.application.md#addusercodedirect)
* [closeDrawCall](m4m.framework.application.md#closedrawcall)
* [closeFps](m4m.framework.application.md#closefps)
* [getAssetMgr](m4m.framework.application.md#getassetmgr)
* [getInputMgr](m4m.framework.application.md#getinputmgr)
* [getScene](m4m.framework.application.md#getscene)
* [markNotify](m4m.framework.application.md#marknotify)
* [refreshOrientationMode](m4m.framework.application.md#refreshorientationmode)
* [showDrawCall](m4m.framework.application.md#showdrawcall)
* [showFps](m4m.framework.application.md#showfps)
* [start](m4m.framework.application.md#start)
* [startForCanvas](m4m.framework.application.md#startforcanvas)

#### Accessors

* [beRendering](m4m.framework.application.md#berendering)
* [canvasClientHeight](m4m.framework.application.md#canvasclientheight)
* [canvasClientWidth](m4m.framework.application.md#canvasclientwidth)
* [canvasFixHeight](m4m.framework.application.md#canvasfixheight)
* [canvasFixWidth](m4m.framework.application.md#canvasfixwidth)
* [frameID](m4m.framework.application.md#frameid)
* [height](m4m.framework.application.md#height)
* [scaleFromPandding](m4m.framework.application.md#scalefrompandding)
* [targetFrame](m4m.framework.application.md#targetframe)
* [timeScale](m4m.framework.application.md#timescale)
* [width](m4m.framework.application.md#width)

#### Constructors

* [constructor](m4m.framework.application.md#constructor)

### Properties

#### OffOrientationUpdate

• **OffOrientationUpdate**: `boolean` = `false`

**Defined in**

[framework/application.ts:843](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L843)

***

#### bePlay

• **bePlay**: `boolean` = `false`

运行开关

**Defined in**

[framework/application.ts:659](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L659)

***

#### ccHeight

• **ccHeight**: `number`

**Defined in**

[framework/application.ts:150](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L150)

***

#### ccWidth

• **ccWidth**: `number`

**Defined in**

[framework/application.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L149)

***

#### container

• **container**: `HTMLDivElement`

**Defined in**

[framework/application.ts:55](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L55)

***

#### curcameraindex

• **curcameraindex**: `number` = `-1`

**Defined in**

[framework/application.ts:655](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L655)

***

#### edModel

• **edModel**: `boolean`

**Defined in**

[framework/application.ts:57](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L57)

***

#### globalMacros

• `Readonly` **globalMacros**: `string`\[] = `[]`

**`language`** zh\_CN

**`classdesc`** 全局宏定义

**`version`** m4m 1.0

**Defined in**

[framework/application.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L66)

***

#### limitFrame

• **limitFrame**: `boolean` = `true`

**Defined in**

[framework/application.ts:92](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L92)

***

#### notify

• **notify**: `INotify`

**Defined in**

[framework/application.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L93)

***

#### orientation

• **orientation**: `string` = `OrientationMode.AUTO`

旋转角度 OrientationMode.AUTO

**Defined in**

[framework/application.ts:839](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L839)

***

#### outcontainer

• **outcontainer**: `HTMLDivElement`

**Defined in**

[framework/application.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L56)

***

#### screenAdaptiveType

• **screenAdaptiveType**: `string`

**Defined in**

[framework/application.ts:143](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L143)

***

#### shouldRotate

• **shouldRotate**: `boolean` = `false`

**Defined in**

[framework/application.ts:840](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L840)

***

#### stats

• **stats**: `Stats`

**Defined in**

[framework/application.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L54)

***

#### webgl

• **webgl**: `WebGLRenderingContext`

**`language`** zh\_CN

**`classdesc`** 全局webgl实例

**`version`** m4m 1.0

**Defined in**

[framework/application.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L53)

### Methods

#### addEditorCode

▸ **addEditorCode**(`classname`): `void`

**`language`** zh\_CN

**`classdesc`** 根据classname添加editorcode

**`version`** m4m 1.0

**Parameters**

| Name        | Type     | Description  |
| ----------- | -------- | ------------ |
| `classname` | `string` | editorcode类名 |

**Returns**

`void`

**Defined in**

[framework/application.ts:818](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L818)

***

#### addEditorCodeDirect

▸ **addEditorCodeDirect**(`program`): `void`

**`language`** zh\_CN

**`classdesc`** 直接添加editorcode实例

**`version`** m4m 1.0

**Parameters**

| Name      | Type                                                        | Description  |
| --------- | ----------------------------------------------------------- | ------------ |
| `program` | [`IEditorCode`](../interfaces/m4m.framework.IEditorCode.md) | editorcode实例 |

**Returns**

`void`

**Defined in**

[framework/application.ts:834](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L834)

***

#### addUserCode

▸ **addUserCode**(`classname`): `void`

**`language`** zh\_CN

**`classdesc`** 根据classname添加usercode

**`version`** m4m 1.0

**Parameters**

| Name        | Type     | Description |
| ----------- | -------- | ----------- |
| `classname` | `string` | usercode类名  |

**Returns**

`void`

**Defined in**

[framework/application.ts:801](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L801)

***

#### addUserCodeDirect

▸ **addUserCodeDirect**(`program`): `void`

**`language`** zh\_CN

**`classdesc`** 直接添加usercode实例

**`version`** m4m 1.0

**Parameters**

| Name      | Type                                                    | Description |
| --------- | ------------------------------------------------------- | ----------- |
| `program` | [`IUserCode`](../interfaces/m4m.framework.IUserCode.md) | usercode实例  |

**Returns**

`void`

**Defined in**

[framework/application.ts:788](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L788)

***

#### closeDrawCall

▸ **closeDrawCall**(): `void`

**Returns**

`void`

**Defined in**

[framework/application.ts:395](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L395)

***

#### closeFps

▸ **closeFps**(): `void`

**`language`** zh\_CN

**`classdesc`** 关闭性能参数面板

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/application.ts:386](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L386)

***

#### getAssetMgr

▸ **getAssetMgr**(): [`assetMgr`](m4m.framework.assetMgr.md)

**`language`** zh\_CN

**`classdesc`** 获取资源管理器实例

**`version`** m4m 1.0

**Returns**

[`assetMgr`](m4m.framework.assetMgr.md)

**Defined in**

[framework/application.ts:622](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L622)

***

#### getInputMgr

▸ **getInputMgr**(): [`inputMgr`](m4m.framework.inputMgr.md)

**`language`** zh\_CN

**`classdesc`** 获取输入管理器实例

**`version`** m4m 1.0

**Returns**

[`inputMgr`](m4m.framework.inputMgr.md)

**Defined in**

[framework/application.ts:641](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L641)

***

#### getScene

▸ **getScene**(): [`scene`](m4m.framework.scene.md)

**`language`** zh\_CN

**`classdesc`** 获取场景实例

**`version`** m4m 1.0

**Returns**

[`scene`](m4m.framework.scene.md)

**Defined in**

[framework/application.ts:604](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L604)

***

#### markNotify

▸ **markNotify**(`trans`, `type`): `void`

**Parameters**

| Name    | Type         |
| ------- | ------------ |
| `trans` | `any`        |
| `type`  | `NotifyType` |

**Returns**

`void`

**Defined in**

[framework/application.ts:321](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L321)

***

#### refreshOrientationMode

▸ **refreshOrientationMode**(`rect?`, `screenWidth?`, `screenHeight?`): `void`

刷新 一次,视窗朝向数据。

**Parameters**

| Name            | Type      | Description |
| --------------- | --------- | ----------- |
| `rect?`         | `DOMRect` | 视窗矩形区域      |
| `screenWidth?`  | `number`  | 视窗宽度        |
| `screenHeight?` | `number`  | 视窗高度        |

**Returns**

`void`

**Defined in**

[framework/application.ts:904](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L904)

***

#### showDrawCall

▸ **showDrawCall**(): `void`

**Returns**

`void`

**Defined in**

[framework/application.ts:392](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L392)

***

#### showFps

▸ **showFps**(): `void`

**`language`** zh\_CN

**`classdesc`** 显示性能参数面板

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/application.ts:364](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L364)

***

#### start

▸ **start**(`div`, `type?`, `val?`, `webglDebug?`): `void`

**`language`** zh\_CN

**`classdesc`** 引擎的启动方法

**`version`** m4m 1.0

**Parameters**

| Name         | Type                                                           | Default value          | Description |
| ------------ | -------------------------------------------------------------- | ---------------------- | ----------- |
| `div`        | `HTMLDivElement`                                               | `undefined`            | 绘制区域的dom    |
| `type`       | [`CanvasFixedType`](../enums/m4m.framework.CanvasFixedType.md) | `CanvasFixedType.Free` | -           |
| `val`        | `number`                                                       | `1200`                 | -           |
| `webglDebug` | `boolean`                                                      | `false`                | -           |

**Returns**

`void`

**Defined in**

[framework/application.ts:178](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L178)

***

#### startForCanvas

▸ **startForCanvas**(`canvas`, `type?`, `val?`, `webglDebug?`): `void`

**Parameters**

| Name         | Type                                                           | Default value          |
| ------------ | -------------------------------------------------------------- | ---------------------- |
| `canvas`     | `HTMLCanvasElement`                                            | `undefined`            |
| `type`       | [`CanvasFixedType`](../enums/m4m.framework.CanvasFixedType.md) | `CanvasFixedType.Free` |
| `val`        | `number`                                                       | `1200`                 |
| `webglDebug` | `boolean`                                                      | `false`                |

**Returns**

`void`

**Defined in**

[framework/application.ts:237](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L237)

### Accessors

#### beRendering

• `get` **beRendering**(): `boolean`

渲染开关

**Returns**

`boolean`

**Defined in**

[framework/application.ts:777](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L777)

• `set` **beRendering**(`val`): `void`

渲染开关

**Parameters**

| Name  | Type      |
| ----- | --------- |
| `val` | `boolean` |

**Returns**

`void`

**Defined in**

[framework/application.ts:778](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L778)

***

#### canvasClientHeight

• `get` **canvasClientHeight**(): `number`

**Returns**

`number`

**Defined in**

[framework/application.ts:164](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L164)

***

#### canvasClientWidth

• `get` **canvasClientWidth**(): `number`

**Returns**

`number`

**Defined in**

[framework/application.ts:161](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L161)

***

#### canvasFixHeight

• `set` **canvasFixHeight**(`val`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[framework/application.ts:155](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L155)

***

#### canvasFixWidth

• `set` **canvasFixWidth**(`val`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[framework/application.ts:158](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L158)

***

#### frameID

• `get` **frameID**(): `number`

**Returns**

`number`

**Defined in**

[framework/application.ts:399](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L399)

***

#### height

• `get` **height**(): `number`

**Returns**

`number`

**Defined in**

[framework/application.ts:87](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L87)

***

#### scaleFromPandding

• `get` **scaleFromPandding**(): `number`

**Returns**

`number`

**Defined in**

[framework/application.ts:168](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L168)

***

#### targetFrame

• `get` **targetFrame**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取当前固定帧数

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/application.ts:140](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L140)

• `set` **targetFrame**(`val`): `void`

**`language`** zh\_CN

**`classdesc`** 设置固定帧数 不设置即为不限制帧数

**`version`** m4m 1.0

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[framework/application.ts:126](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L126)

***

#### timeScale

• `get` **timeScale**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取timescale

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/application.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L112)

• `set` **timeScale**(`val`): `void`

**`language`** zh\_CN

**`classdesc`** 设置timescale

**`version`** m4m 1.0

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[framework/application.ts:102](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L102)

***

#### width

• `get` **width**(): `number`

**`language`** zh\_CN

**`classdesc`** 绘制区域宽度 像素单位

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/application.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/application.ts#L75)

### Constructors

#### constructor

• **new application**()
