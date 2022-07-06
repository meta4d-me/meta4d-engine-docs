# m4m.framework.TrailRenderer

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / TrailRenderer

## Class: TrailRenderer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).TrailRenderer

The trail renderer is used to make trails behind objects in the Scene as they move about.

拖尾染器

### Implements

* [`IRenderer`](../interfaces/m4m.framework.IRenderer.md)

### Table of contents

#### Methods

* [AddPosition](m4m.framework.TrailRenderer.md#addposition)
* [AddPositions](m4m.framework.TrailRenderer.md#addpositions)
* [BakeMesh](m4m.framework.TrailRenderer.md#bakemesh)
* [Clear](m4m.framework.TrailRenderer.md#clear)
* [GetPosition](m4m.framework.TrailRenderer.md#getposition)
* [GetPositions](m4m.framework.TrailRenderer.md#getpositions)
* [SetPositions](m4m.framework.TrailRenderer.md#setpositions)
* [clone](m4m.framework.TrailRenderer.md#clone)
* [onPlay](m4m.framework.TrailRenderer.md#onplay)
* [remove](m4m.framework.TrailRenderer.md#remove)
* [render](m4m.framework.TrailRenderer.md#render)
* [setPosition](m4m.framework.TrailRenderer.md#setposition)
* [start](m4m.framework.TrailRenderer.md#start)
* [update](m4m.framework.TrailRenderer.md#update)

#### Properties

* [alignment](m4m.framework.TrailRenderer.md#alignment)
* [autodestruct](m4m.framework.TrailRenderer.md#autodestruct)
* [emitting](m4m.framework.TrailRenderer.md#emitting)
* [gameObject](m4m.framework.TrailRenderer.md#gameobject)
* [generateLightingData](m4m.framework.TrailRenderer.md#generatelightingdata)
* [layer](m4m.framework.TrailRenderer.md#layer)
* [lineColor](m4m.framework.TrailRenderer.md#linecolor)
* [lineWidth](m4m.framework.TrailRenderer.md#linewidth)
* [material](m4m.framework.TrailRenderer.md#material)
* [minVertexDistance](m4m.framework.TrailRenderer.md#minvertexdistance)
* [numCapVertices](m4m.framework.TrailRenderer.md#numcapvertices)
* [numCornerVertices](m4m.framework.TrailRenderer.md#numcornervertices)
* [queue](m4m.framework.TrailRenderer.md#queue)
* [shadowBias](m4m.framework.TrailRenderer.md#shadowbias)
* [textureMode](m4m.framework.TrailRenderer.md#texturemode)
* [time](m4m.framework.TrailRenderer.md#time)
* [ClassName](m4m.framework.TrailRenderer.md#classname)

#### Accessors

* [colorGradient](m4m.framework.TrailRenderer.md#colorgradient)
* [endColor](m4m.framework.TrailRenderer.md#endcolor)
* [endWidth](m4m.framework.TrailRenderer.md#endwidth)
* [positionCount](m4m.framework.TrailRenderer.md#positioncount)
* [renderLayer](m4m.framework.TrailRenderer.md#renderlayer)
* [startColor](m4m.framework.TrailRenderer.md#startcolor)
* [startWidth](m4m.framework.TrailRenderer.md#startwidth)
* [trailRendererData](m4m.framework.TrailRenderer.md#trailrendererdata)
* [transform](m4m.framework.TrailRenderer.md#transform)
* [widthCurve](m4m.framework.TrailRenderer.md#widthcurve)
* [widthMultiplier](m4m.framework.TrailRenderer.md#widthmultiplier)

#### Constructors

* [constructor](m4m.framework.TrailRenderer.md#constructor)

### Methods

#### AddPosition

▸ **AddPosition**(`position`): `void`

Adds a position to the trail.

**Parameters**

| Name       | Type      | Description                       |
| ---------- | --------- | --------------------------------- |
| `position` | `vector3` | The position to add to the trail. |

**Returns**

`void`

**Defined in**

[framework/effects/TrailRenderer.ts:435](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L435)

***

#### AddPositions

▸ **AddPositions**(`positions`): `void`

Add an array of positions to the trail.

All points inside a TrailRenderer store a timestamp when they are born. This, together with the TrailRenderer.time property, is used to determine when they will be removed. For trails to disappear smoothly, each position must have a unique, increasing timestamp. When positions are supplied from script and the current time is identical for multiple points, position timestamps are adjusted to interpolate smoothly between the timestamp of the newest existing point in the trail and the current time.

**Parameters**

| Name        | Type         | Description                        |
| ----------- | ------------ | ---------------------------------- |
| `positions` | `vector3`\[] | The positions to add to the trail. |

**Returns**

`void`

**Defined in**

[framework/effects/TrailRenderer.ts:447](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L447)

***

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

[framework/effects/TrailRenderer.ts:393](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L393)

***

#### Clear

▸ **Clear**(): `void`

Removes all points from the TrailRenderer. Useful for restarting a trail from a new position.

**Returns**

`void`

**Defined in**

[framework/effects/TrailRenderer.ts:464](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L464)

***

#### GetPosition

▸ **GetPosition**(`index`): `Object`

Get the position of a vertex in the line.

获取直线在顶点的位置。

**Parameters**

| Name    | Type     | Description                            |
| ------- | -------- | -------------------------------------- |
| `index` | `number` | The index of the position to retrieve. |

**Returns**

`Object`

| Name        | Type      |
| ----------- | --------- |
| `birthTime` | `number`  |
| `position`  | `vector3` |

**Defined in**

[framework/effects/TrailRenderer.ts:477](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L477)

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

[framework/effects/TrailRenderer.ts:491](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L491)

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

[framework/effects/TrailRenderer.ts:526](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L526)

***

#### clone

▸ **clone**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[clone](../interfaces/m4m.framework.IRenderer.md#clone)

**Defined in**

[framework/effects/TrailRenderer.ts:342](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L342)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[onPlay](../interfaces/m4m.framework.IRenderer.md#onplay)

**Defined in**

[framework/effects/TrailRenderer.ts:326](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L326)

***

#### remove

▸ **remove**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[remove](../interfaces/m4m.framework.IRenderer.md#remove)

**Defined in**

[framework/effects/TrailRenderer.ts:336](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L336)

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

[framework/effects/TrailRenderer.ts:301](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L301)

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

[framework/effects/TrailRenderer.ts:512](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L512)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[start](../interfaces/m4m.framework.IRenderer.md#start)

**Defined in**

[framework/effects/TrailRenderer.ts:331](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L331)

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

[framework/effects/TrailRenderer.ts:351](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L351)

### Properties

#### alignment

• **alignment**: [`LineAlignment`](../enums/m4m.framework.LineAlignment.md) = `LineAlignment.TransformZ`

Select whether the line will face the camera, or the orientation of the Transform Component.

选择线是否将面对摄像机，或转换组件的方向。

**Defined in**

[framework/effects/TrailRenderer.ts:94](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L94)

***

#### autodestruct

• **autodestruct**: `boolean` = `false`

Does the GameObject of this Trail Renderer auto destruct?

**Defined in**

[framework/effects/TrailRenderer.ts:99](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L99)

***

#### emitting

• **emitting**: `boolean` = `true`

Creates trails when the GameObject moves.

**Defined in**

[framework/effects/TrailRenderer.ts:104](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L104)

***

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[gameObject](../interfaces/m4m.framework.IRenderer.md#gameobject)

**Defined in**

[framework/effects/TrailRenderer.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L56)

***

#### generateLightingData

• **generateLightingData**: `boolean` = `false`

Configures a line to generate Normals and Tangents. With this data, Scene lighting can affect the line via Normal Maps and the Unity Standard Shader, or your own custom-built Shaders.

是否自动生成灯光所需的法线与切线。

**Defined in**

[framework/effects/TrailRenderer.ts:135](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L135)

***

#### layer

• **layer**: [`RenderLayerEnum`](../enums/m4m.framework.RenderLayerEnum.md) = `RenderLayerEnum.Transparent`

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[layer](../interfaces/m4m.framework.IRenderer.md#layer)

**Defined in**

[framework/effects/TrailRenderer.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L26)

***

#### lineColor

• **lineColor**: [`MinMaxGradient`](m4m.framework.MinMaxGradient.md)

线条颜色。

**Defined in**

[framework/effects/TrailRenderer.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L72)

***

#### lineWidth

• **lineWidth**: [`MinMaxCurve`](m4m.framework.MinMaxCurve.md)

曲线宽度。

**Defined in**

[framework/effects/TrailRenderer.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L66)

***

#### material

• **material**: [`material`](m4m.framework.material.md)

**`language`** zh\_CN

**`classdesc`** mesh的材质数组

**`version`** m4m 1.0

**Defined in**

[framework/effects/TrailRenderer.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L24)

***

#### minVertexDistance

• **minVertexDistance**: `number` = `0.1`

Set the minimum distance the trail can travel before a new vertex is added to it.

**Defined in**

[framework/effects/TrailRenderer.ts:109](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L109)

***

#### numCapVertices

• **numCapVertices**: `number` = `0`

Set this to a value greater than 0, to get rounded corners on each end of the line.

将此值设置为大于0的值，以在行的两端获得圆角。

**Defined in**

[framework/effects/TrailRenderer.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L86)

***

#### numCornerVertices

• **numCornerVertices**: `number` = `0`

Set this to a value greater than 0, to get rounded corners between each segment of the line.

将此值设置为大于0的值，以在直线的每个线段之间获取圆角。

**Defined in**

[framework/effects/TrailRenderer.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L79)

***

#### queue

• **queue**: `number` = `0`

**`language`** zh\_CN

**`classdesc`** 同场景渲染层级时候先后排序依据

**`version`** m4m 1.0

**Implementation of**

[IRenderer](../interfaces/m4m.framework.IRenderer.md).[queue](../interfaces/m4m.framework.IRenderer.md#queue)

**Defined in**

[framework/effects/TrailRenderer.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L49)

***

#### shadowBias

• **shadowBias**: `number` = `0.5`

Apply a shadow bias to prevent self-shadowing artifacts. The specified value is the proportion of the line width at each segment.

应用阴影偏差以防止自阴影伪影。指定的值是每段线宽的比例。

**Defined in**

[framework/effects/TrailRenderer.ts:128](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L128)

***

#### textureMode

• **textureMode**: [`LineTextureMode`](../enums/m4m.framework.LineTextureMode.md) = `LineTextureMode.Stretch`

Choose whether the U coordinate of the line texture is tiled or stretched.

选择是平铺还是拉伸线纹理的U坐标。

**Defined in**

[framework/effects/TrailRenderer.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L121)

***

#### time

• **time**: `number` = `5`

How long does the trail take to fade out.

**Defined in**

[framework/effects/TrailRenderer.ts:114](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L114)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"trailrenderer"`

**Defined in**

[framework/effects/TrailRenderer.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L12)

### Accessors

#### colorGradient

• `get` **colorGradient**(): [`Gradient`](m4m.framework.Gradient.md)

Set the color gradient describing the color of the line at various points along its length.

设置颜色渐变，以描述线条沿其长度的各个点的颜色。

**Returns**

[`Gradient`](m4m.framework.Gradient.md)

**Defined in**

[framework/effects/TrailRenderer.ts:172](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L172)

• `set` **colorGradient**(`v`): `void`

Set the color gradient describing the color of the line at various points along its length.

设置颜色渐变，以描述线条沿其长度的各个点的颜色。

**Parameters**

| Name | Type                                    |
| ---- | --------------------------------------- |
| `v`  | [`Gradient`](m4m.framework.Gradient.md) |

**Returns**

`void`

**Defined in**

[framework/effects/TrailRenderer.ts:177](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L177)

***

#### endColor

• `get` **endColor**(): `color`

Set the color at the end of the line.

设置线尾颜色。

**Returns**

`color`

**Defined in**

[framework/effects/TrailRenderer.ts:187](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L187)

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

[framework/effects/TrailRenderer.ts:200](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L200)

***

#### endWidth

• `get` **endWidth**(): `number`

Set the width at the end of the line.

设置线尾宽度。

**Returns**

`number`

**Defined in**

[framework/effects/TrailRenderer.ts:215](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L215)

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

[framework/effects/TrailRenderer.ts:220](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L220)

***

#### positionCount

• `get` **positionCount**(): `number`

Set/get the number of vertices.

设置/获取顶点数。

**Returns**

`number`

**Defined in**

[framework/effects/TrailRenderer.ts:230](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L230)

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

[framework/effects/TrailRenderer.ts:235](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L235)

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

[framework/effects/TrailRenderer.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L36)

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

[framework/effects/TrailRenderer.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L37)

***

#### startColor

• `get` **startColor**(): `color`

Set the color at the start of the line.

设置行线头颜色。

**Returns**

`color`

**Defined in**

[framework/effects/TrailRenderer.ts:245](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L245)

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

[framework/effects/TrailRenderer.ts:257](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L257)

***

#### startWidth

• `get` **startWidth**(): `number`

Set the width at the start of the line.

设置线头宽度

**Returns**

`number`

**Defined in**

[framework/effects/TrailRenderer.ts:271](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L271)

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

[framework/effects/TrailRenderer.ts:276](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L276)

***

#### trailRendererData

• `get` **trailRendererData**(): [`TrailRendererData`](m4m.framework.TrailRendererData.md)

**Returns**

[`TrailRendererData`](m4m.framework.TrailRendererData.md)

**Defined in**

[framework/effects/TrailRenderer.ts:282](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L282)

• `set` **trailRendererData**(`v`): `void`

**Parameters**

| Name | Type                                                      |
| ---- | --------------------------------------------------------- |
| `v`  | [`TrailRendererData`](m4m.framework.TrailRendererData.md) |

**Returns**

`void`

**Defined in**

[framework/effects/TrailRenderer.ts:287](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L287)

***

#### transform

• `get` **transform**(): [`transform`](m4m.framework.transform.md)

**Returns**

[`transform`](m4m.framework.transform.md)

**Defined in**

[framework/effects/TrailRenderer.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L51)

***

#### widthCurve

• `get` **widthCurve**(): [`AnimationCurve1`](m4m.framework.AnimationCurve1.md)

Set the curve describing the width of the line at various points along its length.

设置曲线，以描述沿线长度在各个点处的线宽。

**Returns**

[`AnimationCurve1`](m4m.framework.AnimationCurve1.md)

**Defined in**

[framework/effects/TrailRenderer.ts:142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L142)

• `set` **widthCurve**(`v`): `void`

Set the curve describing the width of the line at various points along its length.

设置曲线，以描述沿线长度在各个点处的线宽。

**Parameters**

| Name | Type                                                  |
| ---- | ----------------------------------------------------- |
| `v`  | [`AnimationCurve1`](m4m.framework.AnimationCurve1.md) |

**Returns**

`void`

**Defined in**

[framework/effects/TrailRenderer.ts:147](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L147)

***

#### widthMultiplier

• `get` **widthMultiplier**(): `number`

Set an overall multiplier that is applied to the LineRenderer.widthCurve to get the final width of the line.

设置一个应用于LineRenderer.widthCurve的总乘数，以获取线的最终宽度。

**Returns**

`number`

**Defined in**

[framework/effects/TrailRenderer.ts:157](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L157)

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

[framework/effects/TrailRenderer.ts:162](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/effects/TrailRenderer.ts#L162)

### Constructors

#### constructor

• **new TrailRenderer**()
