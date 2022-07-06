# m4m.framework.label

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / label

## Class: label

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).label

**`language`** zh\_CN

**`classdesc`** 2d文本组件

**`version`** m4m 1.0

### Implements

* [`IRectRenderer`](../interfaces/m4m.framework.IRectRenderer.md)

### Table of contents

#### Properties

* [color](m4m.framework.label.md#color)
* [color2](m4m.framework.label.md#color2)
* [horizontalOverflow](m4m.framework.label.md#horizontaloverflow)
* [horizontalType](m4m.framework.label.md#horizontaltype)
* [isLabel](m4m.framework.label.md#islabel)
* [linespace](m4m.framework.label.md#linespace)
* [onAddRendererText](m4m.framework.label.md#onaddrenderertext)
* [outlineWidth](m4m.framework.label.md#outlinewidth)
* [transform](m4m.framework.label.md#transform)
* [verticalOverflow](m4m.framework.label.md#verticaloverflow)
* [verticalType](m4m.framework.label.md#verticaltype)
* [ClassName](m4m.framework.label.md#classname)
* [onTryExpandTexts](m4m.framework.label.md#ontryexpandtexts)

#### Constructors

* [constructor](m4m.framework.label.md#constructor)

#### Accessors

* [font](m4m.framework.label.md#font)
* [fontsize](m4m.framework.label.md#fontsize)
* [imageTextAtlas](m4m.framework.label.md#imagetextatlas)
* [richText](m4m.framework.label.md#richtext)
* [text](m4m.framework.label.md#text)

#### Methods

* [getDrawBounds](m4m.framework.label.md#getdrawbounds)
* [getMaterial](m4m.framework.label.md#getmaterial)
* [onPlay](m4m.framework.label.md#onplay)
* [setShaderByName](m4m.framework.label.md#setshaderbyname)

### Properties

#### color

• **color**: `color`

**`language`** zh\_CN

**`classdesc`** 填充颜色

**`version`** m4m 1.0

**Defined in**

[framework/2d/component/label.ts:772](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L772)

***

#### color2

• **color2**: `color`

**`language`** zh\_CN

**`classdesc`** 描边颜色

**`version`** m4m 1.0

**Defined in**

[framework/2d/component/label.ts:783](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L783)

***

#### horizontalOverflow

• **horizontalOverflow**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 是否横向溢出

**`version`** m4m 1.0

**Defined in**

[framework/2d/component/label.ts:163](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L163)

***

#### horizontalType

• **horizontalType**: [`HorizontalType`](../enums/m4m.framework.HorizontalType.md) = `HorizontalType.Left`

**`language`** zh\_CN

**`classdesc`** 水平排列方式

**`version`** m4m 1.0

**Defined in**

[framework/2d/component/label.ts:143](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L143)

***

#### isLabel

• `Readonly` **isLabel**: `true`

字段 用于快速判断实例是否是label

**Defined in**

[framework/2d/component/label.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L27)

***

#### linespace

• **linespace**: `number` = `1`

**`language`** zh\_CN

**`classdesc`** 行高

**`version`** m4m 1.0

**Defined in**

[framework/2d/component/label.ts:133](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L133)

***

#### onAddRendererText

• **onAddRendererText**: (`x`: `number`, `y`: `number`) => `void`

**Type declaration**

▸ (`x`, `y`): `void`

当需渲染字符被 加入排列时 的回调

**Parameters**

| Name | Type     |
| ---- | -------- |
| `x`  | `number` |
| `y`  | `number` |

**Returns**

`void`

**Defined in**

[framework/2d/component/label.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L30)

***

#### outlineWidth

• **outlineWidth**: `number` = `0.75`

描边宽度

**Defined in**

[framework/2d/component/label.ts:789](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L789)

***

#### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh\_CN

**`classdesc`** 当前组件的2d节点

**`version`** m4m 1.0

**Implementation of**

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[transform](../interfaces/m4m.framework.IRectRenderer.md#transform)

**Defined in**

[framework/2d/component/label.ts:1250](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L1250)

***

#### verticalOverflow

• **verticalOverflow**: `boolean` = `false`

**`language`** zh\_CN

**`classdesc`** 是否竖向溢出

**`version`** m4m 1.0

**Defined in**

[framework/2d/component/label.ts:173](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L173)

***

#### verticalType

• **verticalType**: [`VerticalType`](../enums/m4m.framework.VerticalType.md) = `VerticalType.Center`

**`language`** zh\_CN

**`classdesc`** 垂直排列方式

**`version`** m4m 1.0

**Defined in**

[framework/2d/component/label.ts:153](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L153)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"label"`

**Defined in**

[framework/2d/component/label.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L25)

***

#### onTryExpandTexts

▪ `Static` **onTryExpandTexts**: (`str`: `string`) => `void`

**Type declaration**

▸ (`str`): `void`

尝试 动态扩展 字体信息 函数接口

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `str` | `string` |

**Returns**

`void`

**Defined in**

[framework/2d/component/label.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L23)

### Constructors

#### constructor

• **new label**()

### Accessors

#### font

• `get` **font**(): [`font`](m4m.framework.font.md)

**`language`** zh\_CN

**`classdesc`** 字体

**`version`** m4m 1.0

**Returns**

[`font`](m4m.framework.font.md)

**Defined in**

[framework/2d/component/label.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L86)

• `set` **font**(`font`): `void`

**`language`** zh\_CN

**`classdesc`** 字体

**`version`** m4m 1.0

**Parameters**

| Name   | Type                            |
| ------ | ------------------------------- |
| `font` | [`font`](m4m.framework.font.md) |

**Returns**

`void`

**Defined in**

[framework/2d/component/label.ts:89](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L89)

***

#### fontsize

• `get` **fontsize**(): `number`

**`language`** zh\_CN

**`classdesc`** 字体大小

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/2d/component/label.ts:118](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L118)

• `set` **fontsize**(`size`): `void`

**`language`** zh\_CN

**`classdesc`** 字体大小

**`version`** m4m 1.0

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `size` | `number` |

**Returns**

`void`

**Defined in**

[framework/2d/component/label.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L121)

***

#### imageTextAtlas

• `get` **imageTextAtlas**(): [`atlas`](m4m.framework.atlas.md)

图像文字图集 (例如 表情)

**Returns**

[`atlas`](m4m.framework.atlas.md)

**Defined in**

[framework/2d/component/label.ts:814](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L814)

• `set` **imageTextAtlas**(`val`): `void`

图像文字图集 (例如 表情)

**Parameters**

| Name  | Type                              |
| ----- | --------------------------------- |
| `val` | [`atlas`](m4m.framework.atlas.md) |

**Returns**

`void`

**Defined in**

[framework/2d/component/label.ts:815](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L815)

***

#### richText

• `get` **richText**(): `boolean`

富文本模式 , 通过特定标签使用。

文字颜色 \<color=#ffffffff>文本 (已经支持); 文字斜体 \<i>文本\</i> (已经支持); 图片字符（表情） \[imgName] (已经支持); 文字加粗 \<b>文本\</b> (支持中); 文字加下划线 \<u>文本\</u> (支持中);

**Returns**

`boolean`

**Defined in**

[framework/2d/component/label.ts:802](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L802)

• `set` **richText**(`val`): `void`

富文本模式 , 通过特定标签使用。

文字颜色 \<color=#ffffffff>文本 (已经支持); 文字斜体 \<i>文本\</i> (已经支持); 图片字符（表情） \[imgName] (已经支持); 文字加粗 \<b>文本\</b> (支持中); 文字加下划线 \<u>文本\</u> (支持中);

**Parameters**

| Name  | Type      |
| ----- | --------- |
| `val` | `boolean` |

**Returns**

`void`

**Defined in**

[framework/2d/component/label.ts:803](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L803)

***

#### text

• `get` **text**(): `string`

**`language`** zh\_CN

**`classdesc`** 文字内容

**`version`** m4m 1.0

**Returns**

`string`

**Defined in**

[framework/2d/component/label.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L44)

• `set` **text**(`text`): `void`

**`language`** zh\_CN

**`classdesc`** 文字内容

**`version`** m4m 1.0

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `text` | `string` |

**Returns**

`void`

**Defined in**

[framework/2d/component/label.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L47)

### Methods

#### getDrawBounds

▸ **getDrawBounds**(): `rect`

**`language`** zh\_CN

**`classdesc`** 获取渲染绘制矩形边界

**`version`** m4m 1.0

**Returns**

`rect`

**Implementation of**

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[getDrawBounds](../interfaces/m4m.framework.IRectRenderer.md#getdrawbounds)

**Defined in**

[framework/2d/component/label.ts:867](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L867)

***

#### getMaterial

▸ **getMaterial**(): [`material`](m4m.framework.material.md)

**`language`** zh\_CN

**`classdesc`** 获取rander 的材质

**`version`** m4m 1.0

**Returns**

[`material`](m4m.framework.material.md)

**Implementation of**

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[getMaterial](../interfaces/m4m.framework.IRectRenderer.md#getmaterial)

**Defined in**

[framework/2d/component/label.ts:851](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L851)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[onPlay](../interfaces/m4m.framework.IRectRenderer.md#onplay)

**Defined in**

[framework/2d/component/label.ts:1232](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L1232)

***

#### setShaderByName

▸ **setShaderByName**(`shaderName`): `void`

**`language`** zh\_CN

**`classdesc`** 设置rander Shader名字

**`version`** m4m 1.0

**Parameters**

| Name         | Type     |
| ------------ | -------- |
| `shaderName` | `string` |

**Returns**

`void`

**Defined in**

[framework/2d/component/label.ts:840](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/label.ts#L840)
