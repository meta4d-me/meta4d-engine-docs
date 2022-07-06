# m4m.framework.camera

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / camera

## Class: camera

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).camera

**`language`** zh\_CN

**`classdesc`** 视锥剔除组件，作为标记存在

**`version`** m4m 1.0

### Implements

* [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

### Table of contents

#### Properties

* [CullingMask](m4m.framework.camera.md#cullingmask)
* [\_size](m4m.framework.camera.md#\_size)
* [backgroundColor](m4m.framework.camera.md#backgroundcolor)
* [clearOption\_Color](m4m.framework.camera.md#clearoption\_color)
* [clearOption\_Depth](m4m.framework.camera.md#clearoption\_depth)
* [cullZPlane](m4m.framework.camera.md#cullzplane)
* [currViewPixelASP](m4m.framework.camera.md#currviewpixelasp)
* [currViewPixelRect](m4m.framework.camera.md#currviewpixelrect)
* [gameObject](m4m.framework.camera.md#gameobject)
* [isEditorCam](m4m.framework.camera.md#iseditorcam)
* [isLastCamera](m4m.framework.camera.md#islastcamera)
* [order](m4m.framework.camera.md#order)
* [renderTarget](m4m.framework.camera.md#rendertarget)
* [viewport](m4m.framework.camera.md#viewport)
* [ClassName](m4m.framework.camera.md#classname)

#### Accessors

* [CurrContextIndex](m4m.framework.camera.md#currcontextindex)
* [far](m4m.framework.camera.md#far)
* [fov](m4m.framework.camera.md#fov)
* [near](m4m.framework.camera.md#near)
* [opvalue](m4m.framework.camera.md#opvalue)
* [size](m4m.framework.camera.md#size)

#### Methods

* [addOverLay](m4m.framework.camera.md#addoverlay)
* [calcClipPosFromWorldPos](m4m.framework.camera.md#calcclipposfromworldpos)
* [calcModelPosFromScreenPos](m4m.framework.camera.md#calcmodelposfromscreenpos)
* [calcProjectMatrix](m4m.framework.camera.md#calcprojectmatrix)
* [calcScreenPosFromWorldPos](m4m.framework.camera.md#calcscreenposfromworldpos)
* [calcViewMatrix](m4m.framework.camera.md#calcviewmatrix)
* [calcViewPortPixel](m4m.framework.camera.md#calcviewportpixel)
* [calcViewProjectMatrix](m4m.framework.camera.md#calcviewprojectmatrix)
* [creatRayByScreen](m4m.framework.camera.md#creatraybyscreen)
* [cullTest](m4m.framework.camera.md#culltest)
* [getOverLays](m4m.framework.camera.md#getoverlays)
* [isCulling](m4m.framework.camera.md#isculling)
* [onPlay](m4m.framework.camera.md#onplay)
* [removeOverLay](m4m.framework.camera.md#removeoverlay)
* [start](m4m.framework.camera.md#start)
* [update](m4m.framework.camera.md#update)

#### Constructors

* [constructor](m4m.framework.camera.md#constructor)

### Properties

#### CullingMask

• **CullingMask**: [`CullingMask`](../enums/m4m.framework.CullingMask.md)

**`language`** zh\_CN

**`classdesc`** 相机渲染剔除mask

**`version`** m4m 1.0

**Defined in**

[framework/component/camera.ts:218](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L218)

***

#### \_size

• **\_size**: `number` = `2`

**Defined in**

[framework/component/camera.ts:780](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L780)

***

#### backgroundColor

• **backgroundColor**: `color`

**`language`** zh\_CN

**`classdesc`** 背景色

**`version`** m4m 1.0

**Defined in**

[framework/component/camera.ts:306](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L306)

***

#### clearOption\_Color

• **clearOption\_Color**: `boolean` = `true`

**`language`** zh\_CN

**`classdesc`** 是否清除颜色缓冲区

**`version`** m4m 1.0

**Defined in**

[framework/component/camera.ts:289](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L289)

***

#### clearOption\_Depth

• **clearOption\_Depth**: `boolean` = `true`

**`language`** zh\_CN

**`classdesc`** 是否清除深度缓冲区

**`version`** m4m 1.0

**Defined in**

[framework/component/camera.ts:297](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L297)

***

#### cullZPlane

• **cullZPlane**: `boolean` = `true`

相机剔除时，计算 z 轴上的平面 （far & near plane）

**Defined in**

[framework/component/camera.ts:141](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L141)

***

#### currViewPixelASP

• **currViewPixelASP**: `number` = `1`

当前相机视口像素asp

**Defined in**

[framework/component/camera.ts:430](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L430)

***

#### currViewPixelRect

• `Readonly` **currViewPixelRect**: `rect`

当前的相机视口像素rect

**Defined in**

[framework/component/camera.ts:425](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L425)

***

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh\_CN

**`classdesc`** 挂载的gameobject

**`version`** m4m 1.0

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[gameObject](../interfaces/m4m.framework.INodeComponent.md#gameobject)

**Defined in**

[framework/component/camera.ts:150](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L150)

***

#### isEditorCam

• **isEditorCam**: `boolean` = `false`

**Defined in**

[framework/component/camera.ts:234](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L234)

***

#### isLastCamera

• **isLastCamera**: `boolean` = `false`

**Defined in**

[framework/component/camera.ts:851](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L851)

***

#### order

• **order**: `number` = `0`

**`language`** zh\_CN

**`classdesc`** camera 渲染排序标记

**`version`** m4m 1.0

**Defined in**

[framework/component/camera.ts:331](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L331)

***

#### renderTarget

• **renderTarget**: `glRenderTarget` = `null`

**`language`** zh\_CN

**`classdesc`** 渲染目标

**`version`** m4m 1.0

**Defined in**

[framework/component/camera.ts:323](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L323)

***

#### viewport

• **viewport**: `rect`

**`language`** zh\_CN

**`classdesc`** 相机视窗

**`version`** m4m 1.0

**Defined in**

[framework/component/camera.ts:315](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L315)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"camera"`

**Defined in**

[framework/component/camera.ts:110](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L110)

### Accessors

#### CurrContextIndex

• `get` **CurrContextIndex**(): `number`

当前RenderContext 的 Index

**Returns**

`number`

**Defined in**

[framework/component/camera.ts:223](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L223)

***

#### far

• `get` **far**(): `number`

**`language`** zh\_CN

**`classdesc`** 相机到远裁剪面距离

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/component/camera.ts:193](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L193)

• `set` **far**(`val`): `void`

**`language`** zh\_CN

**`classdesc`** 设置相机到远裁剪面距离

**`version`** m4m 1.0

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:204](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L204)

***

#### fov

• `get` **fov**(): `number`

**`language`** zh\_CN

**`classdesc`** 透视投影的fov

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/component/camera.ts:775](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L775)

• `set` **fov**(`val`): `void`

**`language`** zh\_CN

**`classdesc`** 透视投影的fov

**`version`** m4m 1.0

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:770](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L770)

***

#### near

• `get` **near**(): `number`

**`language`** zh\_CN

**`classdesc`** 相机到近裁剪面距离

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/component/camera.ts:162](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L162)

• `set` **near**(`val`): `void`

**`language`** zh\_CN

**`classdesc`** 设置相机到近裁剪面距离

**`version`** m4m 1.0

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:173](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L173)

***

#### opvalue

• `get` **opvalue**(): `number`

**`language`** zh\_CN

**`classdesc`** 0=正交， 1=透视 中间值可以在两种相机间过度

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/component/camera.ts:819](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L819)

• `set` **opvalue**(`val`): `void`

**`language`** zh\_CN

**`classdesc`** 0=正交， 1=透视 中间值可以在两种相机间过度

**`version`** m4m 1.0

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:808](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L808)

***

#### size

• `get` **size**(): `number`

**`language`** zh\_CN

**`classdesc`** 正交投影的竖向size

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/component/camera.ts:794](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L794)

• `set` **size**(`val`): `void`

**`language`** zh\_CN

**`classdesc`** 正交投影的竖向size

**`version`** m4m 1.0

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:789](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L789)

### Methods

#### addOverLay

▸ **addOverLay**(`overLay`): `void`

**`language`** zh\_CN

**`classdesc`** 添加2d渲染组件

**`version`** m4m 1.0

**Parameters**

| Name      | Type       |
| --------- | ---------- |
| `overLay` | `IOverLay` |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:342](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L342)

***

#### calcClipPosFromWorldPos

▸ **calcClipPosFromWorldPos**(`app`, `worldPos`, `outClipPos`): `void`

**`language`** zh\_CN

**`classdesc`** 由世界坐标得到裁剪空间坐标

**`version`** m4m 1.0

**Parameters**

| Name         | Type                                          | Description |
| ------------ | --------------------------------------------- | ----------- |
| `app`        | [`application`](m4m.framework.application.md) | application |
| `worldPos`   | `vector3`                                     | 世界空间坐标      |
| `outClipPos` | `vector3`                                     | 计算返回裁剪空间坐标  |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:659](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L659)

***

#### calcModelPosFromScreenPos

▸ **calcModelPosFromScreenPos**(`app`, `screenPos`, `outModelPos`): `void`

**`language`** zh\_CN

**`classdesc`** 由屏幕坐标得到model空间坐标

**`version`** m4m 1.0

**Parameters**

| Name          | Type                                          | Description |
| ------------- | --------------------------------------------- | ----------- |
| `app`         | [`application`](m4m.framework.application.md) | 主程序         |
| `screenPos`   | `vector3`                                     | -           |
| `outModelPos` | `vector3`                                     | -           |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:585](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L585)

***

#### calcProjectMatrix

▸ **calcProjectMatrix**(`asp`, `outMatrix`): `boolean`

**`language`** zh\_CN 计算投影矩阵, return 是否有变化

**`classdesc`** 计算相机投影矩阵

**`version`** m4m 1.0

**Parameters**

| Name        | Type     | Description         |
| ----------- | -------- | ------------------- |
| `asp`       | `number` |                     |
| `outMatrix` | `matrix` | projectmatrix（投影矩阵） |

**Returns**

`boolean`

**Defined in**

[framework/component/camera.ts:481](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L481)

***

#### calcScreenPosFromWorldPos

▸ **calcScreenPosFromWorldPos**(`app`, `worldPos`, `outScreenPos`): `void`

**`language`** zh\_CN

**`classdesc`** 由世界坐标得到屏幕坐标

**`version`** m4m 1.0

**Parameters**

| Name           | Type                                          | Description |
| -------------- | --------------------------------------------- | ----------- |
| `app`          | [`application`](m4m.framework.application.md) | 主程序         |
| `worldPos`     | `vector3`                                     | 世界坐标        |
| `outScreenPos` | `vector2`                                     | 屏幕坐标        |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:615](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L615)

***

#### calcViewMatrix

▸ **calcViewMatrix**(`outMatrix?`): `boolean`

**`language`** zh\_CN 计算视矩阵, return 是否有变化

**`classdesc`** 计算相机的viewmatrix（视矩阵）

**`version`** m4m 1.0

**Parameters**

| Name         | Type     | Description |
| ------------ | -------- | ----------- |
| `outMatrix?` | `matrix` | 返回的视矩阵      |

**Returns**

`boolean`

**Defined in**

[framework/component/camera.ts:404](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L404)

***

#### calcViewPortPixel

▸ **calcViewPortPixel**(`app`, `viewPortPixel?`): `void`

**`language`** zh\_CN

**`classdesc`** 计算相机视口像素rect

**`version`** m4m 1.0

**Parameters**

| Name             | Type                                          | Description |
| ---------------- | --------------------------------------------- | ----------- |
| `app`            | [`application`](m4m.framework.application.md) | 主程序         |
| `viewPortPixel?` | `rect`                                        | -           |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:441](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L441)

***

#### calcViewProjectMatrix

▸ **calcViewProjectMatrix**(`app`, `outViewProjectMatrix?`, `outViewMatrix?`, `outProjectMatrix?`): `boolean`

计算视窗投影矩阵,return 是否有变化

**Parameters**

| Name                    | Type                                          |
| ----------------------- | --------------------------------------------- |
| `app`                   | [`application`](m4m.framework.application.md) |
| `outViewProjectMatrix?` | `matrix`                                      |
| `outViewMatrix?`        | `matrix`                                      |
| `outProjectMatrix?`     | `matrix`                                      |

**Returns**

`boolean`

**Defined in**

[framework/component/camera.ts:514](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L514)

***

#### creatRayByScreen

▸ **creatRayByScreen**(`screenpos`, `app`, `shareRayCache?`): [`ray`](m4m.framework.ray.md)

**`language`** zh\_CN

**`classdesc`** 由屏幕坐标发射射线

**`version`** m4m 1.0

**Parameters**

| Name            | Type                                          | Default value | Description               |
| --------------- | --------------------------------------------- | ------------- | ------------------------- |
| `screenpos`     | `vector2`                                     | `undefined`   | 屏幕坐标                      |
| `app`           | [`application`](m4m.framework.application.md) | `undefined`   | 主程序                       |
| `shareRayCache` | `boolean`                                     | `true`        | 返回ray 实例 共用一个缓存射线对象 ，默认开启 |

**Returns**

[`ray`](m4m.framework.ray.md)

**Defined in**

[framework/component/camera.ts:543](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L543)

***

#### cullTest

▸ **cullTest**(`radius`, `center`): `boolean`

剔除测试 ，返回 ture 确认为剔除

**Parameters**

| Name     | Type      |
| -------- | --------- |
| `radius` | `number`  |
| `center` | `vector3` |

**Returns**

`boolean`

**Defined in**

[framework/component/camera.ts:967](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L967)

***

#### getOverLays

▸ **getOverLays**(): `IOverLay`\[]

**`language`** zh\_CN

**`classdesc`** 返回此相机上的overlays数组

**`version`** m4m 1.0

**Returns**

`IOverLay`\[]

**Defined in**

[framework/component/camera.ts:362](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L362)

***

#### isCulling

▸ **isCulling**(`node`): `boolean`

**Parameters**

| Name   | Type                                      |
| ------ | ----------------------------------------- |
| `node` | [`transform`](m4m.framework.transform.md) |

**Returns**

`boolean`

**Defined in**

[framework/component/camera.ts:941](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L941)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

**Defined in**

[framework/component/camera.ts:241](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L241)

***

#### removeOverLay

▸ **removeOverLay**(`overLay`): `void`

**`language`** zh\_CN

**`classdesc`** 移除相机上的所有overly

**`version`** m4m 1.0

**Parameters**

| Name      | Type       |
| --------- | ---------- |
| `overLay` | `IOverLay` |

**Returns**

`void`

**Defined in**

[framework/component/camera.ts:373](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L373)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

**Defined in**

[framework/component/camera.ts:236](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L236)

***

#### update

▸ **update**(`delta`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[update](../interfaces/m4m.framework.INodeComponent.md#update)

**Defined in**

[framework/component/camera.ts:246](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L246)

### Constructors

#### constructor

• **new camera**()

**Defined in**

[framework/component/camera.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/camera.ts#L112)
