[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / animationClip

# Class: animationClip

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).animationClip

**`language`** zh_CN

**`classdesc`**
动画片段资源

**`version`** m4m 1.0

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Methods

- [Parse](m4m.framework.animationClip.md#parse)
- [caclByteLength](m4m.framework.animationClip.md#caclbytelength)
- [dispose](m4m.framework.animationClip.md#dispose)
- [getGUID](m4m.framework.animationClip.md#getguid)
- [getName](m4m.framework.animationClip.md#getname)
- [unuse](m4m.framework.animationClip.md#unuse)
- [use](m4m.framework.animationClip.md#use)

### Properties

- [boneCount](m4m.framework.animationClip.md#bonecount)
- [defaultAsset](m4m.framework.animationClip.md#defaultasset)
- [fps](m4m.framework.animationClip.md#fps)
- [hasScaled](m4m.framework.animationClip.md#hasscaled)
- [indexDic](m4m.framework.animationClip.md#indexdic)
- [loop](m4m.framework.animationClip.md#loop)
- [ClassName](m4m.framework.animationClip.md#classname)

### Constructors

- [constructor](m4m.framework.animationClip.md#constructor)

### Accessors

- [time](m4m.framework.animationClip.md#time)

## Methods

### Parse

▸ **Parse**(`buf`): `Promise`<[`animationClip`](m4m.framework.animationClip.md)\>

**`language`** zh_CN

**`classdesc`**
解析资源

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `buf` | `ArrayBuffer` | buffer数组 |

#### Returns

`Promise`<[`animationClip`](m4m.framework.animationClip.md)\>

#### Defined in

[framework/asset/resource/animationclip.ts:129](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L129)

___

### caclByteLength

▸ **caclByteLength**(): `number`

**`language`** zh_CN

**`classdesc`**
计算资源字节大小

**`version`** m4m 1.0

#### Returns

`number`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[caclByteLength](../interfaces/m4m.framework.IAsset.md#caclbytelength)

#### Defined in

[framework/asset/resource/animationclip.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L101)

___

### dispose

▸ **dispose**(): `void`

**`language`** zh_CN

**`classdesc`**
释放资源

**`version`** m4m 1.0

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[dispose](../interfaces/m4m.framework.IAsset.md#dispose)

#### Defined in

[framework/asset/resource/animationclip.ts:87](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L87)

___

### getGUID

▸ **getGUID**(): `number`

**`language`** zh_CN

**`classdesc`**
获取资源唯一id

**`version`** m4m 1.0

#### Returns

`number`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[getGUID](../interfaces/m4m.framework.IAsset.md#getguid)

#### Defined in

[framework/asset/resource/animationclip.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L54)

___

### getName

▸ **getName**(): `string`

**`language`** zh_CN

**`classdesc`**
获取资源名称

**`version`** m4m 1.0

#### Returns

`string`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[getName](../interfaces/m4m.framework.IAsset.md#getname)

#### Defined in

[framework/asset/resource/animationclip.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L43)

___

### unuse

▸ **unuse**(`disposeNow?`): `void`

**`language`** zh_CN

**`classdesc`**
引用计数减一

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `disposeNow` | `boolean` | `false` |

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[unuse](../interfaces/m4m.framework.IAsset.md#unuse)

#### Defined in

[framework/asset/resource/animationclip.ts:76](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L76)

___

### use

▸ **use**(): `void`

**`language`** zh_CN

**`classdesc`**
引用计数加一

**`version`** m4m 1.0

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[use](../interfaces/m4m.framework.IAsset.md#use)

#### Defined in

[framework/asset/resource/animationclip.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L65)

## Properties

### boneCount

• **boneCount**: `number`

**`language`** zh_CN

**`classdesc`**
骨骼数量

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/animationclip.ts:356](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L356)

___

### defaultAsset

• **defaultAsset**: `boolean` = `false`

**`language`** zh_CN

**`classdesc`**
是否为默认资源

**`version`** m4m 1.0

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

#### Defined in

[framework/asset/resource/animationclip.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L27)

___

### fps

• **fps**: `number`

**`language`** zh_CN
动画片段的帧率

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/animationclip.ts:316](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L316)

___

### hasScaled

• **hasScaled**: `boolean`

**`language`** zh_CN

**`classdesc`**
是否含有缩放

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/animationclip.ts:334](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L334)

___

### indexDic

• **indexDic**: `Object` = `{}`

#### Index signature

▪ [boneName: `string`]: `number`

#### Defined in

[framework/asset/resource/animationclip.ts:362](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L362)

___

### loop

• **loop**: `boolean`

**`language`** zh_CN

**`classdesc`**
是否循环

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/animationclip.ts:325](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L325)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"animationClip"`

#### Defined in

[framework/asset/resource/animationclip.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L15)

## Constructors

### constructor

• **new animationClip**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/asset/resource/animationclip.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L28)

## Accessors

### time

• `get` **time**(): `number`

**`language`** zh_CN

**`classdesc`**
播放时长

**`version`** m4m 1.0

#### Returns

`number`

#### Defined in

[framework/asset/resource/animationclip.ts:343](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/animationclip.ts#L343)
