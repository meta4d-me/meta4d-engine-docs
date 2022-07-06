# m4m.framework.LineRenderer

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / LineRenderer

## Class: LineRenderer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).LineRenderer

The line renderer is used to draw free-floating lines in 3D space.

线渲染器用于在三维空间中绘制自由浮动的线。

### Implements

* [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)

### Table of contents

#### Methods

* [BakeMesh](m4m.framework.LineRenderer.md#bakemesh)
* [GetPosition](m4m.framework.LineRenderer.md#getposition)
* [GetPositions](m4m.framework.LineRenderer.md#getpositions)
* [SetPositions](m4m.framework.LineRenderer.md#setpositions)
* [Simplify](m4m.framework.LineRenderer.md#simplify)
* [clone](m4m.framework.LineRenderer.md#clone)
* [onPlay](m4m.framework.LineRenderer.md#onplay)
* [remove](m4m.framework.LineRenderer.md#remove)
* [render](m4m.framework.LineRenderer.md#render)
* [setPosition](m4m.framework.LineRenderer.md#setposition)
* [start](m4m.framework.LineRenderer.md#start)
* [update](m4m.framework.LineRenderer.md#update)
* [calcMesh](m4m.framework.LineRenderer.md#calcmesh)
* [calcPositionVectex](m4m.framework.LineRenderer.md#calcpositionvectex)
* [calcRateAtLines](m4m.framework.LineRenderer.md#calcrateatlines)
* [calcTotalLength](m4m.framework.LineRenderer.md#calctotallength)
* [clearMesh](m4m.framework.LineRenderer.md#clearmesh)
* [draw](m4m.framework.LineRenderer.md#draw)
* [uploadMesh](m4m.framework.LineRenderer.md#uploadmesh)

#### Properties

* [alignment](m4m.framework.LineRenderer.md#alignment)
* [gameObject](m4m.framework.LineRenderer.md#gameobject)
* [generateLightingData](m4m.framework.LineRenderer.md#generatelightingdata)
* [layer](m4m.framework.LineRenderer.md#layer)
* [lineColor](m4m.framework.LineRenderer.md#linecolor)
* [lineWidth](m4m.framework.LineRenderer.md#linewidth)
* [loop](m4m.framework.LineRenderer.md#loop)
* [material](m4m.framework.LineRenderer.md#material)
* [numCapVertices](m4m.framework.LineRenderer.md#numcapvertices)
* [numCornerVertices](m4m.framework.LineRenderer.md#numcornervertices)
* [positions](m4m.framework.LineRenderer.md#positions)
* [queue](m4m.framework.LineRenderer.md#queue)
* [shadowBias](m4m.framework.LineRenderer.md#shadowbias)
* [textureMode](m4m.framework.LineRenderer.md#texturemode)
* [useWorldSpace](m4m.framework.LineRenderer.md#useworldspace)
* [ClassName](m4m.framework.LineRenderer.md#classname)

#### Accessors

* [colorGradient](m4m.framework.LineRenderer.md#colorgradient)
* [endColor](m4m.framework.LineRenderer.md#endcolor)
* [endWidth](m4m.framework.LineRenderer.md#endwidth)
* [positionCount](m4m.framework.LineRenderer.md#positioncount)
* [renderLayer](m4m.framework.LineRenderer.md#renderlayer)
* [startColor](m4m.framework.LineRenderer.md#startcolor)
* [startWidth](m4m.framework.LineRenderer.md#startwidth)
* [transform](m4m.framework.LineRenderer.md#transform)
* [widthCurve](m4m.framework.LineRenderer.md#widthcurve)
* [widthMultiplier](m4m.framework.LineRenderer.md#widthmultiplier)

#### Constructors

* [constructor](m4m.framework.LineRenderer.md#constructor)

### Methods

#### BakeMesh

▸ **BakeMesh**(`mesh`, `camera`, `useTransform`): `void`

Creates a snapshot of LineRenderer and stores it in mesh.

创建LineRenderer的快照并将其存储在网格中。

**Parameters**

| Name           | Type                                | Description                                                             |
| -------------- | ----------------------------------- | ----------------------------------------------------------------------- |
| `mesh`         | [`mesh`](m4m.framework.mesh.md)     | A static mesh that will receive the snapshot of the line.               |
| `camera`       | [`camera`](m4m.framework.camera.md) | The camera used for determining which way camera-space lines will face. |
| `useTransform` | `boolean`                           | Include the rotation and scale of the Transform in the baked mesh.      |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:329](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L329)

***

#### GetPosition

▸ **GetPosition**(`index`): `vector3`

Get the position of a vertex in the line.

获取直线在顶点的位置。

**Parameters**

| Name    | Type     | Description                            |
| ------- | -------- | -------------------------------------- |
| `index` | `number` | The index of the position to retrieve. |

**Returns**

`vector3`

**Defined in**

[framework/effects/LineRenderer.ts:365](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L365)

***

#### GetPositions

▸ **GetPositions**(`positions?`): `vector3`\[]

Get the positions of all vertices in the line.

获取行中所有顶点的位置。

**Parameters**

| Name        | Type         | Default value | Description                                                                                       |
| ----------- | ------------ | ------------- | ------------------------------------------------------------------------------------------------- |
| `positions` | `vector3`\[] | `[]`          | The array of positions to retrieve. The array passed should be of at least positionCount in size. |

**Returns**

`vector3`\[]

How many positions were actually stored in the output array.

**Defined in**

[framework/effects/LineRenderer.ts:379](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L379)

***

#### SetPositions

▸ **SetPositions**(`positions`): `void`

Set the positions of all vertices in the line.

设置线中所有顶点的位置。

**Parameters**

| Name        | Type         | Description                    |
| ----------- | ------------ | ------------------------------ |
| `positions` | `vector3`\[] | The array of positions to set. |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:414](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L414)

***

#### Simplify

▸ **Simplify**(`tolerance`): `void`

Generates a simplified version of the original line by removing points that fall within the specified tolerance.

通过删除落在指定公差范围内的点，生成原始线的简化版本。

**`todo`**

**Parameters**

| Name        | Type     | Description                                                                                                                                                                                                                                               |
| ----------- | -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `tolerance` | `number` | This value is used to evaluate which points should be removed from the line. A higher value results in a simpler line (less points). A positive value close to zero results in a line with little to no reduction. A value of zero or less has no effect. |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:435](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L435)

***

#### clone

▸ **clone**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[clone](../interfaces/m4m.framework.IRenderer.md#clone)

**Defined in**

[framework/effects/LineRenderer.ts:314](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L314)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[onPlay](../interfaces/m4m.framework.IRenderer.md#onplay)

**Defined in**

[framework/effects/LineRenderer.ts:290](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L290)

***

#### remove

▸ **remove**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[remove](../interfaces/m4m.framework.IRenderer.md#remove)

**Defined in**

[framework/effects/LineRenderer.ts:308](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L308)

***

#### render

▸ **render**(`context`, `assetmgr`, `camera`): `void`

**Parameters**

| Name       | Type                                    |
| ---------- | --------------------------------------- |
| `context`  | `renderContext`                         |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `camera`   | [`camera`](m4m.framework.camera.md)     |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[render](../interfaces/m4m.framework.IRenderer.md#render)

**Defined in**

[framework/effects/LineRenderer.ts:265](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L265)

***

#### setPosition

▸ **setPosition**(`index`, `position`): `void`

Set the position of a vertex in the line.

设置顶点在直线中的位置。

**Parameters**

| Name       | Type      | Description            |
| ---------- | --------- | ---------------------- |
| `index`    | `number`  | Which position to set. |
| `position` | `vector3` | The new position.      |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:400](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L400)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[start](../interfaces/m4m.framework.IRenderer.md#start)

**Defined in**

[framework/effects/LineRenderer.ts:295](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L295)

***

#### update

▸ **update**(`interval?`): `void`

每帧执行

**Parameters**

| Name        | Type     |
| ----------- | -------- |
| `interval?` | `number` |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[update](../interfaces/m4m.framework.IRenderer.md#update)

**Defined in**

[framework/effects/LineRenderer.ts:303](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L303)

***

#### calcMesh

▸ `Static` **calcMesh**(`positionVectex`, `textureMode`, `colorGradient`, `totalLength`, `mesh`): `void`

计算网格

**Parameters**

| Name             | Type                                                                                                 | Description |
| ---------------- | ---------------------------------------------------------------------------------------------------- | ----------- |
| `positionVectex` | { `normal`: `vector3` ; `rateAtLine`: `number` ; `tangent`: `vector3` ; `vertexs`: `vector3`\[] }\[] | 顶点列表        |
| `textureMode`    | [`LineTextureMode`](../enums/m4m.framework.LineTextureMode.md)                                       | 纹理模式        |
| `colorGradient`  | [`Gradient`](m4m.framework.Gradient.md)                                                              | -           |
| `totalLength`    | `number`                                                                                             | 线条总长度       |
| `mesh`           | [`mesh`](m4m.framework.mesh.md)                                                                      | 保存网格数据的对象   |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:524](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L524)

***

#### calcPositionVectex

▸ `Static` **calcPositionVectex**(`positions`, `loop`, `rateAtLines`, `lineWidth`, `alignment`, `cameraPosition`): { `normal`: `vector3` ; `rateAtLine`: `number` ; `tangent`: `vector3` ; `vertexs`: `vector3`\[] }\[]

计算结点的三角形顶点列表

**Parameters**

| Name             | Type                                                       | Description |
| ---------------- | ---------------------------------------------------------- | ----------- |
| `positions`      | `vector3`\[]                                               | 结点列表        |
| `loop`           | `boolean`                                                  | 是否成换线       |
| `rateAtLines`    | `number`\[]                                                | 结点所在线条位置    |
| `lineWidth`      | [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)              | 线条宽度曲线      |
| `alignment`      | [`LineAlignment`](../enums/m4m.framework.LineAlignment.md) | 朝向方式        |
| `cameraPosition` | `vector3`                                                  | 摄像机局部坐标     |

**Returns**

{ `normal`: `vector3` ; `rateAtLine`: `number` ; `tangent`: `vector3` ; `vertexs`: `vector3`\[] }\[]

**Defined in**

[framework/effects/LineRenderer.ts:607](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L607)

***

#### calcRateAtLines

▸ `Static` **calcRateAtLines**(`positions`, `loop`, `textureMode`): `number`\[]

计算结点所在线段位置

**Parameters**

| Name          | Type                                                           | Description |
| ------------- | -------------------------------------------------------------- | ----------- |
| `positions`   | `vector3`\[]                                                   | 顶点列表        |
| `loop`        | `boolean`                                                      | 是否循环        |
| `textureMode` | [`LineTextureMode`](../enums/m4m.framework.LineTextureMode.md) | -           |

**Returns**

`number`\[]

**Defined in**

[framework/effects/LineRenderer.ts:746](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L746)

***

#### calcTotalLength

▸ `Static` **calcTotalLength**(`positions`, `loop`): `number`

计算线条总长度

**Parameters**

| Name        | Type         | Description |
| ----------- | ------------ | ----------- |
| `positions` | `vector3`\[] | 顶点列表        |
| `loop`      | `boolean`    | 是否循环        |

**Returns**

`number`

**Defined in**

[framework/effects/LineRenderer.ts:725](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L725)

***

#### clearMesh

▸ `Static` **clearMesh**(`mesh`): `void`

清理网格

**Parameters**

| Name   | Type                            |
| ------ | ------------------------------- |
| `mesh` | [`mesh`](m4m.framework.mesh.md) |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:474](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L474)

***

#### draw

▸ `Static` **draw**(`context`, `go`, `mesh`, `material`): `void`

绘制

**Parameters**

| Name       | Type                                        | Description |
| ---------- | ------------------------------------------- | ----------- |
| `context`  | `renderContext`                             |             |
| `go`       | [`gameObject`](m4m.framework.gameObject.md) | 游戏对象        |
| `mesh`     | [`mesh`](m4m.framework.mesh.md)             | 网格          |
| `material` | [`material`](m4m.framework.material.md)     | 材质          |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:452](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L452)

***

#### uploadMesh

▸ `Static` **uploadMesh**(`_mesh`, `webgl`): `void`

**Parameters**

| Name    | Type                            |
| ------- | ------------------------------- |
| `_mesh` | [`mesh`](m4m.framework.mesh.md) |
| `webgl` | `WebGLRenderingContext`         |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:489](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L489)

### Properties

#### alignment

• **alignment**: [`LineAlignment`](../enums/m4m.framework.LineAlignment.md) = `LineAlignment.TransformZ`

Select whether the line will face the camera, or the orientation of the Transform Component.

选择线是否将面对摄像机，或转换组件的方向。

**Defined in**

[framework/effects/LineRenderer.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L101)

***

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[gameObject](../interfaces/m4m.framework.IRenderer.md#gameobject)

**Defined in**

[framework/effects/LineRenderer.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L56)

***

#### generateLightingData

• **generateLightingData**: `boolean` = `false`

Configures a line to generate Normals and Tangents. With this data, Scene lighting can affect the line via Normal Maps and the Unity Standard Shader, or your own custom-built Shaders.

是否自动生成灯光所需的法线与切线。

**Defined in**

[framework/effects/LineRenderer.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L122)

***

#### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Transparent`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[layer](../interfaces/m4m.framework.IRenderer.md#layer)

**Defined in**

[framework/effects/LineRenderer.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L26)

***

#### lineColor

• **lineColor**: [`MinMaxGradient`](m4m.framework.MinMaxGradient.md)

线条颜色。

**Defined in**

[framework/effects/LineRenderer.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L79)

***

#### lineWidth

• **lineWidth**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

曲线宽度。

**Defined in**

[framework/effects/LineRenderer.ts:73](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L73)

***

#### loop

• **loop**: `boolean` = `false`

Connect the start and end positions of the line together to form a continuous loop.

将直线的起点和终点连接在一起，形成一个连续的回路。

**Defined in**

[framework/effects/LineRenderer.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L63)

***

#### material

• **material**: [`material`](m4m.framework.material.md)

**`language`** zh\_CN

**`classdesc`** mesh的材质数组

**`version`** m4m 1.0

**Defined in**

[framework/effects/LineRenderer.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L24)

***

#### numCapVertices

• **numCapVertices**: `number` = `0`

Set this to a value greater than 0, to get rounded corners on each end of the line.

将此值设置为大于0的值，以在行的两端获得圆角。

**Defined in**

[framework/effects/LineRenderer.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L93)

***

#### numCornerVertices

• **numCornerVertices**: `number` = `0`

Set this to a value greater than 0, to get rounded corners between each segment of the line.

将此值设置为大于0的值，以在直线的每个线段之间获取圆角。

**Defined in**

[framework/effects/LineRenderer.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L86)

***

#### positions

• **positions**: `vector3`\[] = `[]`

顶点列表。

**Defined in**

[framework/effects/LineRenderer.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L68)

***

#### queue

• **queue**: `number` = `0`

**`language`** zh\_CN

**`classdesc`** 同场景渲染层级时候先后排序依据

**`version`** m4m 1.0

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[queue](../interfaces/m4m.framework.IRenderer.md#queue)

**Defined in**

[framework/effects/LineRenderer.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L49)

***

#### shadowBias

• **shadowBias**: `number` = `0.5`

Apply a shadow bias to prevent self-shadowing artifacts. The specified value is the proportion of the line width at each segment.

应用阴影偏差以防止自阴影伪影。指定的值是每段线宽的比例。

**Defined in**

[framework/effects/LineRenderer.ts:115](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L115)

***

#### textureMode

• **textureMode**: [`LineTextureMode`](../enums/m4m.framework.LineTextureMode.md) = `LineTextureMode.Stretch`

Choose whether the U coordinate of the line texture is tiled or stretched.

选择是平铺还是拉伸线纹理的U坐标。

**Defined in**

[framework/effects/LineRenderer.ts:108](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L108)

***

#### useWorldSpace

• **useWorldSpace**: `boolean` = `false`

If enabled, the lines are defined in world space.

如果启用，则在世界空间中定义线。

**Defined in**

[framework/effects/LineRenderer.ts:129](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L129)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"LineRenderer"`

**Defined in**

[framework/effects/LineRenderer.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L12)

### Accessors

#### colorGradient

• `get` **colorGradient**(): [`Gradient`](m4m.framework.Gradient.md)

Set the color gradient describing the color of the line at various points along its length.

设置颜色渐变，以描述线条沿其长度的各个点的颜色。

**Returns**

[`Gradient`](m4m.framework.Gradient.md)

**Defined in**

[framework/effects/LineRenderer.ts:161](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L161)

***

#### endColor

• `get` **endColor**(): `color`

Set the color at the end of the line.

设置线尾颜色。

**Returns**

`color`

**Defined in**

[framework/effects/LineRenderer.ts:171](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L171)

• `set` **endColor**(`v`): `void`

Set the color at the end of the line.

设置线尾颜色。

**Parameters**

| Name | Type    |
| ---- | ------- |
| `v`  | `color` |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:184](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L184)

***

#### endWidth

• `get` **endWidth**(): `number`

Set the width at the end of the line.

设置线尾宽度。

**Returns**

`number`

**Defined in**

[framework/effects/LineRenderer.ts:199](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L199)

• `set` **endWidth**(`v`): `void`

Set the width at the end of the line.

设置线尾宽度。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:204](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L204)

***

#### positionCount

• `get` **positionCount**(): `number`

Set/get the number of vertices.

设置/获取顶点数。

**Returns**

`number`

**Defined in**

[framework/effects/LineRenderer.ts:214](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L214)

• `set` **positionCount**(`v`): `void`

Set/get the number of vertices.

设置/获取顶点数。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:219](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L219)

***

#### renderLayer

• `get` **renderLayer**(): `number`

**`language`** zh\_CN

**`classdesc`** 渲染层级

**`version`** m4m 1.0

**Returns**

`number`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

**Defined in**

[framework/effects/LineRenderer.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L36)

• `set` **renderLayer**(`layer`): `void`

**`language`** zh\_CN

**`classdesc`** 渲染层级

**`version`** m4m 1.0

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `layer` | `number` |

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[renderLayer](../interfaces/m4m.framework.IRenderer.md#renderlayer)

**Defined in**

[framework/effects/LineRenderer.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L37)

***

#### startColor

• `get` **startColor**(): `color`

Set the color at the start of the line.

设置行线头颜色。

**Returns**

`color`

**Defined in**

[framework/effects/LineRenderer.ts:229](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L229)

• `set` **startColor**(`v`): `void`

Set the color at the start of the line.

设置行线头颜色。

**Parameters**

| Name | Type    |
| ---- | ------- |
| `v`  | `color` |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:241](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L241)

***

#### startWidth

• `get` **startWidth**(): `number`

Set the width at the start of the line.

设置线头宽度

**Returns**

`number`

**Defined in**

[framework/effects/LineRenderer.ts:255](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L255)

• `set` **startWidth**(`v`): `void`

Set the width at the start of the line.

设置线头宽度

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:260](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L260)

***

#### transform

• `get` **transform**(): [`transform`](m4m.framework.transform.md)

**Returns**

[`transform`](m4m.framework.transform.md)

**Defined in**

[framework/effects/LineRenderer.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L51)

***

#### widthCurve

• `get` **widthCurve**(): [`AnimationCurve1`](m4m.framework.AnimationCurve1.md)

Set the curve describing the width of the line at various points along its length.

设置曲线，以描述沿线长度在各个点处的线宽。

**Returns**

[`AnimationCurve1`](m4m.framework.AnimationCurve1.md)

**Defined in**

[framework/effects/LineRenderer.ts:136](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L136)

***

#### widthMultiplier

• `get` **widthMultiplier**(): `number`

Set an overall multiplier that is applied to the LineRenderer.widthCurve to get the final width of the line.

设置一个应用于LineRenderer.widthCurve的总乘数，以获取线的最终宽度。

**Returns**

`number`

**Defined in**

[framework/effects/LineRenderer.ts:146](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L146)

• `set` **widthMultiplier**(`v`): `void`

Set an overall multiplier that is applied to the LineRenderer.widthCurve to get the final width of the line.

设置一个应用于LineRenderer.widthCurve的总乘数，以获取线的最终宽度。

**Parameters**

| Name | Type     |
| ---- | -------- |
| `v`  | `number` |

**Returns**

`void`

**Defined in**

[framework/effects/LineRenderer.ts:151](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/LineRenderer.ts#L151)

### Constructors

#### constructor

• **new LineRenderer**()
