# m4m.framework.scene

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / scene

## Class: scene

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).scene

**`language`** zh\_CN

**`classdesc`** 场景是基础的功能，有场景图，相当于Unity的Level

**`version`** m4m 1.0

### Table of contents

#### Methods

* [addCamera](m4m.framework.scene.md#addcamera)
* [addChild](m4m.framework.scene.md#addchild)
* [addLight](m4m.framework.scene.md#addlight)
* [addScreenSpaceOverlay](m4m.framework.scene.md#addscreenspaceoverlay)
* [clearCameras](m4m.framework.scene.md#clearcameras)
* [clearLights](m4m.framework.scene.md#clearlights)
* [enable2DPhysics](m4m.framework.scene.md#enable2dphysics)
* [enablePhysics](m4m.framework.scene.md#enablephysics)
* [getChild](m4m.framework.scene.md#getchild)
* [getChildByName](m4m.framework.scene.md#getchildbyname)
* [getChildCount](m4m.framework.scene.md#getchildcount)
* [getChildren](m4m.framework.scene.md#getchildren)
* [getRoot](m4m.framework.scene.md#getroot)
* [pick](m4m.framework.scene.md#pick)
* [pickAll](m4m.framework.scene.md#pickall)
* [refreshGpuInstancBatcher](m4m.framework.scene.md#refreshgpuinstancbatcher)
* [removeChild](m4m.framework.scene.md#removechild)
* [removeScreenSpaceOverlay](m4m.framework.scene.md#removescreenspaceoverlay)
* [update](m4m.framework.scene.md#update)

#### Properties

* [app](m4m.framework.scene.md#app)
* [autoCollectlightCamera](m4m.framework.scene.md#autocollectlightcamera)
* [fog](m4m.framework.scene.md#fog)
* [lightmaps](m4m.framework.scene.md#lightmaps)
* [name](m4m.framework.scene.md#name)
* [onLateUpdate](m4m.framework.scene.md#onlateupdate)
* [renderCameras](m4m.framework.scene.md#rendercameras)
* [renderContext](m4m.framework.scene.md#rendercontext)
* [renderList](m4m.framework.scene.md#renderlist)
* [webgl](m4m.framework.scene.md#webgl)

#### Accessors

* [mainCamera](m4m.framework.scene.md#maincamera)

### Methods

#### addCamera

▸ **addCamera**(`cam`): `void`

添加相机到场景中（autoCollectlightCamera : false 时 有效 ）

**Parameters**

| Name  | Type                                |
| ----- | ----------------------------------- |
| `cam` | [`camera`](m4m.framework.camera.md) |

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:495](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L495)

***

#### addChild

▸ **addChild**(`node`): `void`

**`language`** zh\_CN

**`classdesc`** 场景根节点下添加物体

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                      | Description   |
| ------ | ----------------------------------------- | ------------- |
| `node` | [`transform`](m4m.framework.transform.md) | 要添加的transform |

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:516](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L516)

***

#### addLight

▸ **addLight**(`l`): `void`

添加灯光到场景中（autoCollectlightCamera : false 时 有效 ）

**Parameters**

| Name | Type                              | Description |
| ---- | --------------------------------- | ----------- |
| `l`  | [`light`](m4m.framework.light.md) | 灯光组件        |

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:480](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L480)

***

#### addScreenSpaceOverlay

▸ **addScreenSpaceOverlay**(`overlay`): `void`

**`language`** zh\_CN

**`classdesc`** 添加ScreenSpaceOverlay

**`version`** m4m 1.0

**Parameters**

| Name      | Type                                      |
| --------- | ----------------------------------------- |
| `overlay` | [`overlay2D`](m4m.framework.overlay2D.md) |

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:73](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L73)

***

#### clearCameras

▸ **clearCameras**(): `void`

清除场景中添加过的相机 （autoCollectlightCamera : false 时 有效 ）

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:503](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L503)

***

#### clearLights

▸ **clearLights**(): `void`

清除场景中添加过的灯光 （autoCollectlightCamera : false 时 有效 ）

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:487](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L487)

***

#### enable2DPhysics

▸ **enable2DPhysics**(`gravity`, `physicOption?`): `boolean`

**Parameters**

| Name           | Type                                                        | Default value |
| -------------- | ----------------------------------------------------------- | ------------- |
| `gravity`      | `vector2`                                                   | `undefined`   |
| `physicOption` | [`IEngine2DOP`](../interfaces/m4m.framework.IEngine2DOP.md) | `null`        |

**Returns**

`boolean`

**Defined in**

[framework/scene/scene.ts:805](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L805)

***

#### enablePhysics

▸ **enablePhysics**(`gravity`, `plugin?`): `boolean`

**`language`** zh\_CN

**`classdesc`** 启用物理到当前场景

**`version`** m4m 1.0

**Parameters**

| Name      | Type                                                                          | Description   |
| --------- | ----------------------------------------------------------------------------- | ------------- |
| `gravity` | `vector3`                                                                     | 定义场景物理世界的重力向量 |
| `plugin?` | [`IPhysicsEnginePlugin`](../interfaces/m4m.framework.IPhysicsEnginePlugin.md) | 定义场景物理世界引擎插件  |

**Returns**

`boolean`

**Defined in**

[framework/scene/scene.ts:782](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L782)

***

#### getChild

▸ **getChild**(`index`): [`transform`](m4m.framework.transform.md)

**`language`** zh\_CN

**`classdesc`** 根据索引获取child

**`version`** m4m 1.0

**Parameters**

| Name    | Type     | Description |
| ------- | -------- | ----------- |
| `index` | `number` | 索引          |

**Returns**

[`transform`](m4m.framework.transform.md)

**Defined in**

[framework/scene/scene.ts:567](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L567)

***

#### getChildByName

▸ **getChildByName**(`name`): [`transform`](m4m.framework.transform.md)

**`language`** zh\_CN

**`classdesc`** 根据name获取child

**`version`** m4m 1.0

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

[`transform`](m4m.framework.transform.md)

**Defined in**

[framework/scene/scene.ts:580](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L580)

***

#### getChildCount

▸ **getChildCount**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取children数量

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/scene/scene.ts:553](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L553)

***

#### getChildren

▸ **getChildren**(): [`transform`](m4m.framework.transform.md)\[]

**`language`** zh\_CN

**`classdesc`** 获取children列表

**`version`** m4m 1.0

**Returns**

[`transform`](m4m.framework.transform.md)\[]

**Defined in**

[framework/scene/scene.ts:541](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L541)

***

#### getRoot

▸ **getRoot**(): [`transform`](m4m.framework.transform.md)

**`language`** zh\_CN

**`classdesc`** 获取场景根节点

**`version`** m4m 1.0

**Returns**

[`transform`](m4m.framework.transform.md)

**Defined in**

[framework/scene/scene.ts:593](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L593)

***

#### pick

▸ **pick**(`ray`, `outInfo`, `isPickMesh?`, `root?`, `layermask?`): `boolean`

**`language`** zh\_CN

**`classdesc`** 获取射线拾取到的最近物体

**`version`** m4m 1.0

**Parameters**

| Name         | Type                                      | Default value | Description            |
| ------------ | ----------------------------------------- | ------------- | ---------------------- |
| `ray`        | [`ray`](m4m.framework.ray.md)             | `undefined`   | 射线实例                   |
| `outInfo`    | `pickinfo`                                | `undefined`   | -                      |
| `isPickMesh` | `boolean`                                 | `false`       | 是否为拾取mesh 否为拾取collider |
| `root`       | [`transform`](m4m.framework.transform.md) | `undefined`   | -                      |
| `layermask`  | `number`                                  | `NaN`         | -                      |

**Returns**

`boolean`

**Defined in**

[framework/scene/scene.ts:623](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L623)

***

#### pickAll

▸ **pickAll**(`ray`, `outInfos`, `isPickMesh?`, `root?`, `layermask?`): `boolean`

**`language`** zh\_CN

**`classdesc`** 获取射线路径上的所有物体

**`version`** m4m 1.0

**Parameters**

| Name         | Type                                      | Default value | Description            |
| ------------ | ----------------------------------------- | ------------- | ---------------------- |
| `ray`        | [`ray`](m4m.framework.ray.md)             | `undefined`   | 射线实例                   |
| `outInfos`   | `pickinfo`\[]                             | `undefined`   | -                      |
| `isPickMesh` | `boolean`                                 | `false`       | 是否为拾取mesh 否为拾取collider |
| `root`       | [`transform`](m4m.framework.transform.md) | `undefined`   | -                      |
| `layermask`  | `number`                                  | `NaN`         | -                      |

**Returns**

`boolean`

**Defined in**

[framework/scene/scene.ts:607](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L607)

***

#### refreshGpuInstancBatcher

▸ **refreshGpuInstancBatcher**(`rootNode?`): `void`

刷新 GpuInstancBatcher 被 batcher 条件\[isStatic= true , visible = true , needGpuInstancBatcher = true , isGpuInstancing() = true]

**Parameters**

| Name        | Type                                      | Description       |
| ----------- | ----------------------------------------- | ----------------- |
| `rootNode?` | [`transform`](m4m.framework.transform.md) | 指定刷新节点（默认为 场景根节点） |

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:833](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L833)

***

#### removeChild

▸ **removeChild**(`node`): `void`

**`language`** zh\_CN

**`classdesc`** 场景根节点下移出物体

**`version`** m4m 1.0

**Parameters**

| Name   | Type                                      | Description   |
| ------ | ----------------------------------------- | ------------- |
| `node` | [`transform`](m4m.framework.transform.md) | 要移出的transform |

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:529](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L529)

***

#### removeScreenSpaceOverlay

▸ **removeScreenSpaceOverlay**(`overlay`): `void`

**`language`** zh\_CN

**`classdesc`** 删除ScreenSpaceOverlay

**`version`** m4m 1.0

**Parameters**

| Name      | Type  |
| --------- | ----- |
| `overlay` | `any` |

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L90)

***

#### update

▸ **update**(`delta`): `void`

**`language`** zh\_CN

**`classdesc`** 场景的刷新函数

**`version`** m4m 1.0

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:169](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L169)

### Properties

#### app

• **app**: [`application`](m4m.framework.application.md)

**`language`** zh\_CN

**`classdesc`** 全局的application实例

**`version`** m4m 1.0

**Defined in**

[framework/scene/scene.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L21)

***

#### autoCollectlightCamera

• **autoCollectlightCamera**: `boolean` = `true`

自动收集场景中灯光 和 相机

**Defined in**

[framework/scene/scene.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L54)

***

#### fog

• **fog**: `Fog`

**`language`** zh\_CN

**`classdesc`** 雾效

**`version`** m4m 1.0

**Defined in**

[framework/scene/scene.ts:158](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L158)

***

#### lightmaps

• **lightmaps**: [`texture`](m4m.framework.texture.md)\[] = `[]`

**`language`** zh\_CN

**`classdesc`** lightmap列表

**`version`** m4m 1.0

**Defined in**

[framework/scene/scene.ts:150](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L150)

***

#### name

• **name**: `string`

**`language`** zh\_CN

**`classdesc`** 场景名称

**`version`** m4m 1.0

**Defined in**

[framework/scene/scene.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L51)

***

#### onLateUpdate

• **onLateUpdate**: (`delta`: `number`) => `any`

**Type declaration**

▸ (`delta`): `any`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`any`

**Defined in**

[framework/scene/scene.ts:160](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L160)

***

#### renderCameras

• **renderCameras**: [`camera`](m4m.framework.camera.md)\[] = `[]`

**`language`** zh\_CN

**`classdesc`** 参与渲染的相机

**`version`** m4m 1.0

**Defined in**

[framework/scene/scene.ts:105](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L105)

***

#### renderContext

• **renderContext**: `renderContext`\[] = `[]`

**Defined in**

[framework/scene/scene.ts:141](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L141)

***

#### renderList

• **renderList**: `renderList`

**`language`** zh\_CN

**`classdesc`** 渲染列表

**`version`** m4m 1.0

**Defined in**

[framework/scene/scene.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L63)

***

#### webgl

• **webgl**: `WebGLRenderingContext`

**`language`** zh\_CN

**`classdesc`** 全局的webgl实例

**`version`** m4m 1.0

**Defined in**

[framework/scene/scene.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L29)

### Accessors

#### mainCamera

• `get` **mainCamera**(): [`camera`](m4m.framework.camera.md)

**`language`** zh\_CN

**`classdesc`** 获取当前主相机

**`version`** m4m 1.0

**Returns**

[`camera`](m4m.framework.camera.md)

**Defined in**

[framework/scene/scene.ts:115](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L115)

• `set` **mainCamera**(`_camera`): `void`

**`language`** zh\_CN

**`classdesc`** 设置当前主相机

**`version`** m4m 1.0

**Parameters**

| Name      | Type                                | Description |
| --------- | ----------------------------------- | ----------- |
| `_camera` | [`camera`](m4m.framework.camera.md) | 相机组件实例      |

**Returns**

`void`

**Defined in**

[framework/scene/scene.ts:131](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/scene/scene.ts#L131)
