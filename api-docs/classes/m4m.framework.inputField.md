[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / inputField

# Class: inputField

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).inputField

**`language`** zh_CN

**`classdesc`**
2d文本输入框

**`version`** m4m 1.0

## Implements

- [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)
- [`I2DPointListener`](../interfaces/m4m.framework.I2DPointListener.md)

## Table of contents

### Accessors

- [ContentType](m4m.framework.inputField.md#contenttype)
- [LineType](m4m.framework.inputField.md#linetype)
- [PlaceholderLabel](m4m.framework.inputField.md#placeholderlabel)
- [TextLabel](m4m.framework.inputField.md#textlabel)
- [characterLimit](m4m.framework.inputField.md#characterlimit)
- [frameImage](m4m.framework.inputField.md#frameimage)
- [isFocus](m4m.framework.inputField.md#isfocus)
- [selectionDirection](m4m.framework.inputField.md#selectiondirection)
- [selectionEnd](m4m.framework.inputField.md#selectionend)
- [selectionStart](m4m.framework.inputField.md#selectionstart)
- [text](m4m.framework.inputField.md#text)

### Methods

- [clearText](m4m.framework.inputField.md#cleartext)
- [onPlay](m4m.framework.inputField.md#onplay)

### Constructors

- [constructor](m4m.framework.inputField.md#constructor)

### Properties

- [onTextSubmit](m4m.framework.inputField.md#ontextsubmit)
- [onblur](m4m.framework.inputField.md#onblur)
- [onfocus](m4m.framework.inputField.md#onfocus)
- [transform](m4m.framework.inputField.md#transform)
- [ClassName](m4m.framework.inputField.md#classname)

## Accessors

### ContentType

• `get` **ContentType**(): [`contentType`](../enums/m4m.framework.contentType.md)

**`language`** zh_CN

**`classdesc`**
文本内容格式

**`version`** m4m 1.0

#### Returns

[`contentType`](../enums/m4m.framework.contentType.md)

#### Defined in

[framework/2d/component/inputField.ts:155](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L155)

• `set` **ContentType**(`contentType`): `void`

**`language`** zh_CN

**`classdesc`**
文本内容格式

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `contentType` | [`contentType`](../enums/m4m.framework.contentType.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:156](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L156)

___

### LineType

• `get` **LineType**(): [`lineType`](../enums/m4m.framework.lineType.md)

**`language`** zh_CN

**`classdesc`**
文本行格式

**`version`** m4m 1.0

#### Returns

[`lineType`](../enums/m4m.framework.lineType.md)

#### Defined in

[framework/2d/component/inputField.ts:132](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L132)

• `set` **LineType**(`_lineType`): `void`

**`language`** zh_CN

**`classdesc`**
文本行格式

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `_lineType` | [`lineType`](../enums/m4m.framework.lineType.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:133](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L133)

___

### PlaceholderLabel

• `get` **PlaceholderLabel**(): [`label`](m4m.framework.label.md)

**`language`** zh_CN

**`classdesc`**
输入内容label

**`version`** m4m 1.0

#### Returns

[`label`](m4m.framework.label.md)

#### Defined in

[framework/2d/component/inputField.ts:187](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L187)

• `set` **PlaceholderLabel**(`placeholderLabel`): `void`

**`language`** zh_CN

**`classdesc`**
输入内容label

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `placeholderLabel` | [`label`](m4m.framework.label.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:190](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L190)

___

### TextLabel

• `get` **TextLabel**(): [`label`](m4m.framework.label.md)

**`language`** zh_CN

**`classdesc`**
输入内容label

**`version`** m4m 1.0

#### Returns

[`label`](m4m.framework.label.md)

#### Defined in

[framework/2d/component/inputField.ts:169](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L169)

• `set` **TextLabel**(`textLabel`): `void`

**`language`** zh_CN

**`classdesc`**
输入内容label

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `textLabel` | [`label`](m4m.framework.label.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:172](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L172)

___

### characterLimit

• `get` **characterLimit**(): `number`

**`language`** zh_CN

**`classdesc`**
限制输入字符数

**`version`** m4m 1.0

#### Returns

`number`

#### Defined in

[framework/2d/component/inputField.ts:117](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L117)

• `set` **characterLimit**(`charlimit`): `void`

**`language`** zh_CN

**`classdesc`**
限制输入字符数

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `charlimit` | `number` |

#### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:118](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L118)

___

### frameImage

• `get` **frameImage**(): [`image2D`](m4m.framework.image2D.md)

**`language`** zh_CN

**`classdesc`**
底框显示图像

**`version`** m4m 1.0

#### Returns

[`image2D`](m4m.framework.image2D.md)

#### Defined in

[framework/2d/component/inputField.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L35)

• `set` **frameImage**(`frameImg`): `void`

**`language`** zh_CN

**`classdesc`**
底框显示图像

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `frameImg` | [`image2D`](m4m.framework.image2D.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L38)

___

### isFocus

• `get` **isFocus**(): `boolean`

输入框是否是聚焦的

#### Returns

`boolean`

#### Defined in

[framework/2d/component/inputField.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L62)

___

### selectionDirection

• `get` **selectionDirection**(): ``"none"`` \| ``"forward"`` \| ``"backward"``

选择区域的方向 ， forward ：从前往后 backward ：从后往前

#### Returns

``"none"`` \| ``"forward"`` \| ``"backward"``

#### Defined in

[framework/2d/component/inputField.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L71)

___

### selectionEnd

• `get` **selectionEnd**(): `number`

选择区域的结束位置

#### Returns

`number`

#### Defined in

[framework/2d/component/inputField.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L65)

___

### selectionStart

• `get` **selectionStart**(): `number`

选择区域的开始位置

#### Returns

`number`

#### Defined in

[framework/2d/component/inputField.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L56)

___

### text

• `get` **text**(): `string`

**`language`** zh_CN

**`classdesc`**
文字内容

**`version`** m4m 1.0

#### Returns

`string`

#### Defined in

[framework/2d/component/inputField.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L83)

• `set` **text**(`val`): `void`

**`language`** zh_CN

**`classdesc`**
文字内容

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `string` |

#### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L86)

## Methods

### clearText

▸ **clearText**(): `void`

清除输入文本

#### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:102](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L102)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[onPlay](../interfaces/m4m.framework.I2DComponent.md#onplay)

#### Defined in

[framework/2d/component/inputField.ts:361](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L361)

## Constructors

### constructor

• **new inputField**()

## Properties

### onTextSubmit

• **onTextSubmit**: (`text`: `string`) => `void`

#### Type declaration

▸ (`text`): `void`

用户 按回车键时提交 回调函数

##### Parameters

| Name | Type |
| :------ | :------ |
| `text` | `string` |

##### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L49)

___

### onblur

• **onblur**: () => `void`

#### Type declaration

▸ (): `void`

用户 从输入框移出焦点 回调函数

##### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L53)

___

### onfocus

• **onfocus**: () => `void`

#### Type declaration

▸ (): `void`

用户 聚焦输入框 回调函数

##### Returns

`void`

#### Defined in

[framework/2d/component/inputField.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L51)

___

### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh_CN

**`classdesc`**
当前组件的2d节点

**`version`** m4m 1.0

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[transform](../interfaces/m4m.framework.I2DComponent.md#transform)

#### Defined in

[framework/2d/component/inputField.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L24)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"inputField"`

#### Defined in

[framework/2d/component/inputField.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/inputField.ts#L13)
