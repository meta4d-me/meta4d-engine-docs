# m4m.framework.keyFrameAniClip

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / keyFrameAniClip

## Class: keyFrameAniClip

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).keyFrameAniClip

**`language`** zh\_CN

**`classdesc`** 关键帧动画片段资源

**`version`** m4m 1.0

### Implements

* [`IAsset`](../interfaces/m4m.framework.IAsset.md)

### Table of contents

#### Methods

* [Parse](m4m.framework.keyFrameAniClip.md#parse)
* [caclByteLength](m4m.framework.keyFrameAniClip.md#caclbytelength)
* [dispose](m4m.framework.keyFrameAniClip.md#dispose)
* [getGUID](m4m.framework.keyFrameAniClip.md#getguid)
* [getName](m4m.framework.keyFrameAniClip.md#getname)
* [unuse](m4m.framework.keyFrameAniClip.md#unuse)
* [use](m4m.framework.keyFrameAniClip.md#use)

#### Properties

* [\_wrapMode](m4m.framework.keyFrameAniClip.md#\_wrapmode)
* [curves](m4m.framework.keyFrameAniClip.md#curves)
* [defaultAsset](m4m.framework.keyFrameAniClip.md#defaultasset)
* [ClassName](m4m.framework.keyFrameAniClip.md#classname)

#### Constructors

* [constructor](m4m.framework.keyFrameAniClip.md#constructor)

#### Accessors

* [fps](m4m.framework.keyFrameAniClip.md#fps)
* [frameCount](m4m.framework.keyFrameAniClip.md#framecount)
* [interpolation](m4m.framework.keyFrameAniClip.md#interpolation)
* [time](m4m.framework.keyFrameAniClip.md#time)
* [wrapMode](m4m.framework.keyFrameAniClip.md#wrapmode)

### Methods

#### Parse

▸ **Parse**(`jsonStr`): [`keyFrameAniClip`](m4m.framework.keyFrameAniClip.md)

**`language`** zh\_CN

**`classdesc`** 解析资源

**`version`** m4m 1.0

**Parameters**

| Name      | Type     | Description |
| --------- | -------- | ----------- |
| `jsonStr` | `string` | 动画json数据    |

**Returns**

[`keyFrameAniClip`](m4m.framework.keyFrameAniClip.md)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:139](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L139)

***

#### caclByteLength

▸ **caclByteLength**(): `number`

**`language`** zh\_CN

**`classdesc`** 计算资源字节大小

**`version`** m4m 1.0

**Returns**

`number`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[caclByteLength](../interfaces/m4m.framework.IAsset.md#caclbytelength)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L112)

***

#### dispose

▸ **dispose**(): `void`

**`language`** zh\_CN

**`classdesc`** 释放资源

**`version`** m4m 1.0

**Returns**

`void`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[dispose](../interfaces/m4m.framework.IAsset.md#dispose)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:101](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L101)

***

#### getGUID

▸ **getGUID**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取资源唯一id

**`version`** m4m 1.0

**Returns**

`number`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[getGUID](../interfaces/m4m.framework.IAsset.md#getguid)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L71)

***

#### getName

▸ **getName**(): `string`

**`language`** zh\_CN

**`classdesc`** 获取资源名称

**`version`** m4m 1.0

**Returns**

`string`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[getName](../interfaces/m4m.framework.IAsset.md#getname)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L61)

***

#### unuse

▸ **unuse**(`disposeNow?`): `void`

**`language`** zh\_CN

**`classdesc`** 引用计数减一

**`version`** m4m 1.0

**Parameters**

| Name         | Type      | Default value |
| ------------ | --------- | ------------- |
| `disposeNow` | `boolean` | `false`       |

**Returns**

`void`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[unuse](../interfaces/m4m.framework.IAsset.md#unuse)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:91](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L91)

***

#### use

▸ **use**(): `void`

**`language`** zh\_CN

**`classdesc`** 引用计数加一

**`version`** m4m 1.0

**Returns**

`void`

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[use](../interfaces/m4m.framework.IAsset.md#use)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:81](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L81)

### Properties

#### \_wrapMode

• **\_wrapMode**: [`WrapMode`](../enums/m4m.framework.WrapMode.md)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:189](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L189)

***

#### curves

• **curves**: [`AnimationCurve`](m4m.framework.AnimationCurve.md)\[] = `[]`

**`language`** zh\_CN

**`classdesc`** 属性变化曲线数组

**`version`** m4m 1.0

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:228](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L228)

***

#### defaultAsset

• **defaultAsset**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 是否为默认资源

**`version`** m4m 1.0

**Implementation of**

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L47)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"keyFrameAniClip"`

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L35)

### Constructors

#### constructor

• **new keyFrameAniClip**(`assetName?`)

**Parameters**

| Name        | Type     | Default value |
| ----------- | -------- | ------------- |
| `assetName` | `string` | `null`        |

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L48)

### Accessors

#### fps

• `get` **fps**(): `number`

**`language`** zh\_CN 动画片段的帧率

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:197](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L197)

***

#### frameCount

• `get` **frameCount**(): `number`

**`language`** zh\_CN

**`classdesc`** 最大帧数

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:220](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L220)

***

#### interpolation

• `get` **interpolation**(): [`Interpolation`](../enums/m4m.framework.Interpolation.md)

**Returns**

[`Interpolation`](../enums/m4m.framework.Interpolation.md)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:231](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L231)

***

#### time

• `get` **time**(): `number`

**`language`** zh\_CN

**`classdesc`** 播放时长

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:209](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L209)

***

#### wrapMode

• `get` **wrapMode**(): [`WrapMode`](../enums/m4m.framework.WrapMode.md)

**`language`** zh\_CN 循环模式

**`version`** m4m 1.0

**Returns**

[`WrapMode`](../enums/m4m.framework.WrapMode.md)

**Defined in**

[framework/asset/resource/keyFrameAniClip.ts:188](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/keyFrameAniClip.ts#L188)
