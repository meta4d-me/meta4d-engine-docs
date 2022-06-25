[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / StringUtil

# Class: StringUtil

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).StringUtil

**`language`** zh_CN

**`classdesc`**
正则表达式的工具类，提供一些引擎用到的正则表达式

**`version`** m4m 1.0

## Table of contents

### Constructors

- [constructor](m4m.framework.StringUtil.md#constructor)

### Properties

- [COMPONENT\_AUDIOPLAYER](m4m.framework.StringUtil.md#component_audioplayer)
- [COMPONENT\_BOXCOLLIDER](m4m.framework.StringUtil.md#component_boxcollider)
- [COMPONENT\_BUTTON](m4m.framework.StringUtil.md#component_button)
- [COMPONENT\_CAMERA](m4m.framework.StringUtil.md#component_camera)
- [COMPONENT\_CAMERACONTROLLER](m4m.framework.StringUtil.md#component_cameracontroller)
- [COMPONENT\_CANVASRENDER](m4m.framework.StringUtil.md#component_canvasrender)
- [COMPONENT\_EFFECTSYSTEM](m4m.framework.StringUtil.md#component_effectsystem)
- [COMPONENT\_IMAGE](m4m.framework.StringUtil.md#component_image)
- [COMPONENT\_LABEL](m4m.framework.StringUtil.md#component_label)
- [COMPONENT\_LIGHT](m4m.framework.StringUtil.md#component_light)
- [COMPONENT\_MESHFILTER](m4m.framework.StringUtil.md#component_meshfilter)
- [COMPONENT\_MESHRENDER](m4m.framework.StringUtil.md#component_meshrender)
- [COMPONENT\_RAWIMAGE](m4m.framework.StringUtil.md#component_rawimage)
- [COMPONENT\_SKINMESHRENDER](m4m.framework.StringUtil.md#component_skinmeshrender)
- [COMPONENT\_uirect](m4m.framework.StringUtil.md#component_uirect)
- [ENABLED](m4m.framework.StringUtil.md#enabled)
- [builtinTag\_EditorOnly](m4m.framework.StringUtil.md#builtintag_editoronly)
- [builtinTag\_MainCamera](m4m.framework.StringUtil.md#builtintag_maincamera)
- [builtinTag\_Player](m4m.framework.StringUtil.md#builtintag_player)
- [builtinTag\_Untagged](m4m.framework.StringUtil.md#builtintag_untagged)

### Methods

- [GetSuffix](m4m.framework.StringUtil.md#getsuffix)
- [isNullOrEmptyObject](m4m.framework.StringUtil.md#isnulloremptyobject)
- [replaceAll](m4m.framework.StringUtil.md#replaceall)
- [trimAll](m4m.framework.StringUtil.md#trimall)

## Constructors

### constructor

• **new StringUtil**()

## Properties

### COMPONENT\_AUDIOPLAYER

▪ `Static` `Readonly` **COMPONENT\_AUDIOPLAYER**: ``"AudioPlayer"``

**`language`** zh_CN

**`classdesc`**
获取AudioPlayer组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:157](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L157)

___

### COMPONENT\_BOXCOLLIDER

▪ `Static` `Readonly` **COMPONENT\_BOXCOLLIDER**: ``"boxcollider"``

**`language`** zh_CN

**`classdesc`**
获取boxcollider组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:67](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L67)

___

### COMPONENT\_BUTTON

▪ `Static` `Readonly` **COMPONENT\_BUTTON**: ``"button"``

**`language`** zh_CN

**`classdesc`**
获取button组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:139](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L139)

___

### COMPONENT\_CAMERA

▪ `Static` `Readonly` **COMPONENT\_CAMERA**: ``"camera"``

**`language`** zh_CN

**`classdesc`**
获取camera组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L58)

___

### COMPONENT\_CAMERACONTROLLER

▪ `Static` `Readonly` **COMPONENT\_CAMERACONTROLLER**: ``"cameraController"``

**`language`** zh_CN

**`classdesc`**
获取cameraController组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:166](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L166)

___

### COMPONENT\_CANVASRENDER

▪ `Static` `Readonly` **COMPONENT\_CANVASRENDER**: ``"canvasRenderer"``

**`language`** zh_CN

**`classdesc`**
获取canvasRenderer组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:175](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L175)

___

### COMPONENT\_EFFECTSYSTEM

▪ `Static` `Readonly` **COMPONENT\_EFFECTSYSTEM**: ``"effectSystem"``

**`language`** zh_CN

**`classdesc`**
获取effectSystem组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L103)

___

### COMPONENT\_IMAGE

▪ `Static` `Readonly` **COMPONENT\_IMAGE**: ``"image2D"``

**`language`** zh_CN

**`classdesc`**
获取image2D组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L121)

___

### COMPONENT\_LABEL

▪ `Static` `Readonly` **COMPONENT\_LABEL**: ``"label"``

**`language`** zh_CN

**`classdesc`**
获取label组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L112)

___

### COMPONENT\_LIGHT

▪ `Static` `Readonly` **COMPONENT\_LIGHT**: ``"light"``

**`language`** zh_CN

**`classdesc`**
获取light组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:76](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L76)

___

### COMPONENT\_MESHFILTER

▪ `Static` `Readonly` **COMPONENT\_MESHFILTER**: ``"meshFilter"``

**`language`** zh_CN

**`classdesc`**
获取meshFilter组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:85](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L85)

___

### COMPONENT\_MESHRENDER

▪ `Static` `Readonly` **COMPONENT\_MESHRENDER**: ``"meshRenderer"``

**`language`** zh_CN

**`classdesc`**
获取meshRenderer组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:94](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L94)

___

### COMPONENT\_RAWIMAGE

▪ `Static` `Readonly` **COMPONENT\_RAWIMAGE**: ``"rawImage2D"``

**`language`** zh_CN

**`classdesc`**
获取rawImage2D组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:130](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L130)

___

### COMPONENT\_SKINMESHRENDER

▪ `Static` `Readonly` **COMPONENT\_SKINMESHRENDER**: ``"skinnedMeshRenderer"``

**`language`** zh_CN

**`classdesc`**
获取skinnedMeshRenderer组件的名字

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:148](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L148)

___

### COMPONENT\_uirect

▪ `Static` `Readonly` **COMPONENT\_uirect**: ``"uirect"``

#### Defined in

[framework/util/stringutil.ts:113](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L113)

___

### ENABLED

▪ `Static` `Readonly` **ENABLED**: ``"enabled"``

启用标记

#### Defined in

[framework/util/stringutil.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L13)

___

### builtinTag\_EditorOnly

▪ `Static` `Readonly` **builtinTag\_EditorOnly**: ``"EditorOnly"``

**`language`** zh_CN

**`classdesc`**
内建TAG “EditorOnly”

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L40)

___

### builtinTag\_MainCamera

▪ `Static` `Readonly` **builtinTag\_MainCamera**: ``"MainCamera"``

**`language`** zh_CN

**`classdesc`**
内建TAG “MainCamera”

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L49)

___

### builtinTag\_Player

▪ `Static` `Readonly` **builtinTag\_Player**: ``"Player"``

**`language`** zh_CN

**`classdesc`**
内建TAG “Player”

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L31)

___

### builtinTag\_Untagged

▪ `Static` `Readonly` **builtinTag\_Untagged**: ``"Untagged"``

**`language`** zh_CN

**`classdesc`**
内建TAG “Untagged”

**`version`** m4m 1.0

#### Defined in

[framework/util/stringutil.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L22)

## Methods

### GetSuffix

▸ `Static` **GetSuffix**(`filePath`): `string`

获取文件的 后缀

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `filePath` | `string` | 文件字符串 |

#### Returns

`string`

#### Defined in

[framework/util/stringutil.ts:257](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L257)

___

### isNullOrEmptyObject

▸ `Static` **isNullOrEmptyObject**(`obj`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`boolean`

#### Defined in

[framework/util/stringutil.ts:242](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L242)

___

### replaceAll

▸ `Static` **replaceAll**(`srcStr`, `fromStr`, `toStr`): `string`

**`language`** zh_CN

**`classdesc`**
将一个字符串中的所有指定字符替换为指定字符

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `srcStr` | `string` | 要处理的字符串 |
| `fromStr` | `string` | 原字符串中的指定字符串 |
| `toStr` | `string` | 将被替换为的字符串 |

#### Returns

`string`

#### Defined in

[framework/util/stringutil.ts:205](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L205)

___

### trimAll

▸ `Static` **trimAll**(`str`): `string`

**`language`** zh_CN

**`classdesc`**
剔除掉字符串中所有的空格

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `str` | `string` | 要处理的字符串 |

#### Returns

`string`

#### Defined in

[framework/util/stringutil.ts:218](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/stringutil.ts#L218)
