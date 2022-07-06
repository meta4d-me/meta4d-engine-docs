# m4m.framework.aniplayer

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / aniplayer

## Class: aniplayer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).aniplayer

**`language`** zh\_CN

**`classdesc`** 动画播放器

**`version`** m4m 1.0

### Implements

* [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

### Table of contents

#### Accessors

* [PlayFrameID](m4m.framework.aniplayer.md#playframeid)
* [currentAniclip](m4m.framework.aniplayer.md#currentaniclip)
* [currentAniclipName](m4m.framework.aniplayer.md#currentaniclipname)
* [playCount](m4m.framework.aniplayer.md#playcount)

#### Methods

* [addClip](m4m.framework.aniplayer.md#addclip)
* [addClipByNameLoad](m4m.framework.aniplayer.md#addclipbynameload)
* [addToCareList](m4m.framework.aniplayer.md#addtocarelist)
* [allAsboneToCareList](m4m.framework.aniplayer.md#allasbonetocarelist)
* [allClipNames](m4m.framework.aniplayer.md#allclipnames)
* [awaitLoadClipNames](m4m.framework.aniplayer.md#awaitloadclipnames)
* [fillPoseData](m4m.framework.aniplayer.md#fillposedata)
* [getClip](m4m.framework.aniplayer.md#getclip)
* [haveClip](m4m.framework.aniplayer.md#haveclip)
* [isPlay](m4m.framework.aniplayer.md#isplay)
* [isStop](m4m.framework.aniplayer.md#isstop)
* [onPlay](m4m.framework.aniplayer.md#onplay)
* [pause](m4m.framework.aniplayer.md#pause)
* [play](m4m.framework.aniplayer.md#play)
* [playCross](m4m.framework.aniplayer.md#playcross)
* [playToXFrame](m4m.framework.aniplayer.md#playtoxframe)
* [start](m4m.framework.aniplayer.md#start)
* [stop](m4m.framework.aniplayer.md#stop)
* [update](m4m.framework.aniplayer.md#update)

#### Properties

* [autoplay](m4m.framework.aniplayer.md#autoplay)
* [bones](m4m.framework.aniplayer.md#bones)
* [clips](m4m.framework.aniplayer.md#clips)
* [frameDirty](m4m.framework.aniplayer.md#framedirty)
* [gameObject](m4m.framework.aniplayer.md#gameobject)
* [speed](m4m.framework.aniplayer.md#speed)
* [startPos](m4m.framework.aniplayer.md#startpos)
* [ClassName](m4m.framework.aniplayer.md#classname)

#### Constructors

* [constructor](m4m.framework.aniplayer.md#constructor)

### Accessors

#### PlayFrameID

• `get` **PlayFrameID**(): `number`

**Returns**

`number`

**Defined in**

[framework/component/aniplayer.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L68)

***

#### currentAniclip

• `get` **currentAniclip**(): [`animationClip`](m4m.framework.animationClip.md)

**Returns**

[`animationClip`](m4m.framework.animationClip.md)

**Defined in**

[framework/component/aniplayer.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L79)

***

#### currentAniclipName

• `get` **currentAniclipName**(): `string`

**Returns**

`string`

**Defined in**

[framework/component/aniplayer.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L72)

***

#### playCount

• `get` **playCount**(): `number`

动画循环播放次数

**Returns**

`number`

**Defined in**

[framework/component/aniplayer.ts:85](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L85)

### Methods

#### addClip

▸ **addClip**(`clip`): `void`

添加动画片段

**Parameters**

| Name   | Type                                              |
| ------ | ------------------------------------------------- |
| `clip` | [`animationClip`](m4m.framework.animationClip.md) |

**Returns**

`void`

**Defined in**

[framework/component/aniplayer.ts:193](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L193)

***

#### addClipByNameLoad

▸ **addClipByNameLoad**(`_assetMgr`, `resPath`, `clipName`, `callback?`): `void`

添加动画片段 通过名字加载

**Parameters**

| Name        | Type                                                                                |
| ----------- | ----------------------------------------------------------------------------------- |
| `_assetMgr` | [`assetMgr`](m4m.framework.assetMgr.md)                                             |
| `resPath`   | `string`                                                                            |
| `clipName`  | `string`                                                                            |
| `callback?` | (`state`: [`stateLoad`](m4m.framework.stateLoad.md), `clipName`: `string`) => `any` |

**Returns**

`void`

**Defined in**

[framework/component/aniplayer.ts:179](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L179)

***

#### addToCareList

▸ **addToCareList**(`bone`): `void`

添加 到 更新骨骼节点列表

**Parameters**

| Name   | Type                                      | Description |
| ------ | ----------------------------------------- | ----------- |
| `bone` | [`transform`](m4m.framework.transform.md) | 骨骼节点        |

**Returns**

`void`

**Defined in**

[framework/component/aniplayer.ts:133](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L133)

***

#### allAsboneToCareList

▸ **allAsboneToCareList**(): `void`

收集所有的 asbone 到 更新列表

**Returns**

`void`

**Defined in**

[framework/component/aniplayer.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L121)

***

#### allClipNames

▸ **allClipNames**(): `string`\[]

所有的动画片段名列表，包含待加载的列表

**Returns**

`string`\[]

**Defined in**

[framework/component/aniplayer.ts:156](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L156)

***

#### awaitLoadClipNames

▸ **awaitLoadClipNames**(): `string`\[]

获取待加载的 动画片段名 列表

**Returns**

`string`\[]

**Defined in**

[framework/component/aniplayer.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L149)

***

#### fillPoseData

▸ **fillPoseData**(`data`, `bones`): `void`

**Parameters**

| Name    | Type                                         |
| ------- | -------------------------------------------- |
| `data`  | `Float32Array`                               |
| `bones` | [`transform`](m4m.framework.transform.md)\[] |

**Returns**

`void`

**Defined in**

[framework/component/aniplayer.ts:529](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L529)

***

#### getClip

▸ **getClip**(`name`): [`animationClip`](m4m.framework.animationClip.md)

获取动画片段

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

[`animationClip`](m4m.framework.animationClip.md)

**Defined in**

[framework/component/aniplayer.ts:203](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L203)

***

#### haveClip

▸ **haveClip**(`name`): `boolean`

是否有装载指定动画判断

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

`boolean`

**Defined in**

[framework/component/aniplayer.ts:199](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L199)

***

#### isPlay

▸ **isPlay**(): `boolean`

是否在播放动画

**Returns**

`boolean`

**Defined in**

[framework/component/aniplayer.ts:434](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L434)

***

#### isStop

▸ **isStop**(): `boolean`

是否在停止动画

**Returns**

`boolean`

**Defined in**

[framework/component/aniplayer.ts:440](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L440)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

**Defined in**

[framework/component/aniplayer.ts:221](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L221)

***

#### pause

▸ **pause**(): `void`

**Returns**

`void`

**Defined in**

[framework/component/aniplayer.ts:423](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L423)

***

#### play

▸ **play**(`animName`, `onPlayEnd?`, `speed?`, `beRevert?`): `void`

**`language`** zh\_CN

**`classdesc`** 根据动画片段名字播放动画

**`version`** m4m 1.0

**Parameters**

| Name        | Type         | Default value | Description |
| ----------- | ------------ | ------------- | ----------- |
| `animName`  | `string`     | `undefined`   | 动画片段名字      |
| `onPlayEnd` | () => `void` | `null`        | -           |
| `speed`     | `number`     | `1.0`         | 播放速度        |
| `beRevert`  | `boolean`    | `false`       | 是否倒播        |

**Returns**

`void`

**Defined in**

[framework/component/aniplayer.ts:310](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L310)

***

#### playCross

▸ **playCross**(`animName`, `crosstimer`, `onPlayEnd?`, `speed?`, `beRevert?`): `void`

**`language`** zh\_CN

**`classdesc`** 根据动画片段名字播放动画

**`version`** m4m 1.0

**Parameters**

| Name         | Type         | Default value | Description |
| ------------ | ------------ | ------------- | ----------- |
| `animName`   | `string`     | `undefined`   | 动画片段名字      |
| `crosstimer` | `number`     | `undefined`   | 融合时间        |
| `onPlayEnd`  | () => `void` | `null`        | -           |
| `speed`      | `number`     | `1.0`         | 播放速度        |
| `beRevert`   | `boolean`    | `false`       | 是否倒播        |

**Returns**

`void`

**Defined in**

[framework/component/aniplayer.ts:334](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L334)

***

#### playToXFrame

▸ **playToXFrame**(`animName`, `endframe`, `crosstimer?`, `onPlayEnd?`, `speed?`): `void`

**Parameters**

| Name         | Type         | Default value |
| ------------ | ------------ | ------------- |
| `animName`   | `string`     | `undefined`   |
| `endframe`   | `number`     | `undefined`   |
| `crosstimer` | `number`     | `0`           |
| `onPlayEnd`  | () => `void` | `null`        |
| `speed`      | `number`     | `1.0`         |

**Returns**

`void`

**Defined in**

[framework/component/aniplayer.ts:357](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L357)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

**Defined in**

[framework/component/aniplayer.ts:206](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L206)

***

#### stop

▸ **stop**(): `void`

**`language`** zh\_CN

**`classdesc`** 停止播放动画

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/component/aniplayer.ts:417](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L417)

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

[framework/component/aniplayer.ts:226](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L226)

### Properties

#### autoplay

• **autoplay**: `boolean` = `true`

**Defined in**

[framework/component/aniplayer.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L20)

***

#### bones

• **bones**: `tPoseInfo`\[]

**Defined in**

[framework/component/aniplayer.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L23)

***

#### clips

• **clips**: [`animationClip`](m4m.framework.animationClip.md)\[] = `[]`

**Defined in**

[framework/component/aniplayer.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L18)

***

#### frameDirty

• **frameDirty**: `boolean` = `true`

**Defined in**

[framework/component/aniplayer.ts:225](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L225)

***

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[gameObject](../interfaces/m4m.framework.INodeComponent.md#gameobject)

**Defined in**

[framework/component/aniplayer.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L15)

***

#### speed

• **speed**: `number` = `1.0`

**Defined in**

[framework/component/aniplayer.ts:33](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L33)

***

#### startPos

• **startPos**: `PoseBoneMatrix`\[]

**Defined in**

[framework/component/aniplayer.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L25)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"aniplayer"`

**Defined in**

[framework/component/aniplayer.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/aniplayer.ts#L13)

### Constructors

#### constructor

• **new aniplayer**()
