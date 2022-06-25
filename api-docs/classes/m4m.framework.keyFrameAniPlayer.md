[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / keyFrameAniPlayer

# Class: keyFrameAniPlayer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).keyFrameAniPlayer

## Implements

- [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

## Table of contents

### Methods

- [addClip](m4m.framework.keyFrameAniPlayer.md#addclip)
- [clone](m4m.framework.keyFrameAniPlayer.md#clone)
- [getClip](m4m.framework.keyFrameAniPlayer.md#getclip)
- [isPlaying](m4m.framework.keyFrameAniPlayer.md#isplaying)
- [onPlay](m4m.framework.keyFrameAniPlayer.md#onplay)
- [play](m4m.framework.keyFrameAniPlayer.md#play)
- [remove](m4m.framework.keyFrameAniPlayer.md#remove)
- [rewind](m4m.framework.keyFrameAniPlayer.md#rewind)
- [start](m4m.framework.keyFrameAniPlayer.md#start)
- [stop](m4m.framework.keyFrameAniPlayer.md#stop)
- [update](m4m.framework.keyFrameAniPlayer.md#update)

### Accessors

- [animateOnlyIfVisible](m4m.framework.keyFrameAniPlayer.md#animateonlyifvisible)
- [cullingType](m4m.framework.keyFrameAniPlayer.md#cullingtype)
- [currClipName](m4m.framework.keyFrameAniPlayer.md#currclipname)
- [localBounds](m4m.framework.keyFrameAniPlayer.md#localbounds)
- [nowTime](m4m.framework.keyFrameAniPlayer.md#nowtime)
- [speed](m4m.framework.keyFrameAniPlayer.md#speed)

### Properties

- [clips](m4m.framework.keyFrameAniPlayer.md#clips)
- [gameObject](m4m.framework.keyFrameAniPlayer.md#gameobject)
- [ClassName](m4m.framework.keyFrameAniPlayer.md#classname)

### Constructors

- [constructor](m4m.framework.keyFrameAniPlayer.md#constructor)

## Methods

### addClip

▸ **addClip**(`clip`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `clip` | [`keyFrameAniClip`](m4m.framework.keyFrameAniClip.md) |

#### Returns

`void`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:422](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L422)

___

### clone

▸ **clone**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[clone](../interfaces/m4m.framework.INodeComponent.md#clone)

#### Defined in

[framework/component/keyFrameAniPlayer.ts:479](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L479)

___

### getClip

▸ **getClip**(`clipName`): [`keyFrameAniClip`](m4m.framework.keyFrameAniClip.md)

获取指定名称的clip 资源

#### Parameters

| Name | Type |
| :------ | :------ |
| `clipName` | `string` |

#### Returns

[`keyFrameAniClip`](m4m.framework.keyFrameAniClip.md)

#### Defined in

[framework/component/keyFrameAniPlayer.ts:102](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L102)

___

### isPlaying

▸ **isPlaying**(`ClipName?`): `boolean`

动画是否在播放

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `ClipName` | `string` | `""` | 指定片段名 ，不指定仅判断当前是否在执行 |

#### Returns

`boolean`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:335](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L335)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

#### Defined in

[framework/component/keyFrameAniPlayer.ts:77](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L77)

___

### play

▸ **play**(`ClipName?`, `onPlayEnd?`, `normalizedTime?`): `void`

播放动画

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `ClipName` | `string` | `""` | 指定播放的动画 片段名（为空状态播放队列第一个） |
| `onPlayEnd` | () => `void` | `null` | 播放结束后回调函数 |
| `normalizedTime` | `number` | `1` | 播放结束时间点归一化时间（范围：0~1） |

#### Returns

`void`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:360](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L360)

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[remove](../interfaces/m4m.framework.INodeComponent.md#remove)

#### Defined in

[framework/component/keyFrameAniPlayer.ts:483](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L483)

___

### rewind

▸ **rewind**(): `void`

**`language`** zh_CN

**`classdesc`**
倒带默认动画

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:416](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L416)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

#### Defined in

[framework/component/keyFrameAniPlayer.ts:73](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L73)

___

### stop

▸ **stop**(): `void`

**`language`** zh_CN

**`classdesc`**
停止默认动画

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:405](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L405)

___

### update

▸ **update**(`delta`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[update](../interfaces/m4m.framework.INodeComponent.md#update)

#### Defined in

[framework/component/keyFrameAniPlayer.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L81)

## Accessors

### animateOnlyIfVisible

• `get` **animateOnlyIfVisible**(): `boolean`

动画是否仅仅可显示时 有效播放

#### Returns

`boolean`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L58)

• `set` **animateOnlyIfVisible**(`v`): `void`

动画是否仅仅可显示时 有效播放

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `boolean` |

#### Returns

`void`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L59)

___

### cullingType

• `get` **cullingType**(): [`AnimationCullingType`](../enums/m4m.framework.AnimationCullingType.md)

动画的剔除类型

#### Returns

[`AnimationCullingType`](../enums/m4m.framework.AnimationCullingType.md)

#### Defined in

[framework/component/keyFrameAniPlayer.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L63)

• `set` **cullingType**(`v`): `void`

动画的剔除类型

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`AnimationCullingType`](../enums/m4m.framework.AnimationCullingType.md) |

#### Returns

`void`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L64)

___

### currClipName

• `get` **currClipName**(): `string`

获得当前片段的名字

#### Returns

`string`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L49)

___

### localBounds

• `get` **localBounds**(): [`aabb`](m4m.framework.aabb.md)

动画的剔除类型

#### Returns

[`aabb`](m4m.framework.aabb.md)

#### Defined in

[framework/component/keyFrameAniPlayer.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L68)

• `set` **localBounds**(`v`): `void`

动画的剔除类型

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | [`aabb`](m4m.framework.aabb.md) |

#### Returns

`void`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:69](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L69)

___

### nowTime

• `get` **nowTime**(): `number`

当前播放到的时间

#### Returns

`number`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L38)

___

### speed

• `get` **speed**(): `number`

播放速度

#### Returns

`number`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L53)

• `set` **speed**(`v`): `void`

播放速度

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L54)

## Properties

### clips

• **clips**: [`keyFrameAniClip`](m4m.framework.keyFrameAniClip.md)[]

**`language`** zh_CN

**`classdesc`**
关键帧动画数组

**`version`** m4m 1.0

#### Defined in

[framework/component/keyFrameAniPlayer.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L25)

___

### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[gameObject](../interfaces/m4m.framework.INodeComponent.md#gameobject)

#### Defined in

[framework/component/keyFrameAniPlayer.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L43)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"keyFrameAniPlayer"`

#### Defined in

[framework/component/keyFrameAniPlayer.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/keyFrameAniPlayer.ts#L15)

## Constructors

### constructor

• **new keyFrameAniPlayer**()
