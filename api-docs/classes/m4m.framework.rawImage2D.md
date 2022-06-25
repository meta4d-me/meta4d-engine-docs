[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / rawImage2D

# Class: rawImage2D

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).rawImage2D

**`language`** zh_CN

**`classdesc`**
2d图片组件</p>
参照UGUI的思路，rawImage只拿整个图片来显示，不关心Sprite、九宫、填充等。这些统一都在iamge中处理

**`version`** m4m 1.0

## Implements

- [`IRectRenderer`](../interfaces/m4m.framework.IRectRenderer.md)

## Table of contents

### Properties

- [color](m4m.framework.rawImage2D.md#color)
- [transform](m4m.framework.rawImage2D.md#transform)
- [ClassName](m4m.framework.rawImage2D.md#classname)

### Constructors

- [constructor](m4m.framework.rawImage2D.md#constructor)

### Methods

- [getDrawBounds](m4m.framework.rawImage2D.md#getdrawbounds)
- [getMaterial](m4m.framework.rawImage2D.md#getmaterial)
- [onPlay](m4m.framework.rawImage2D.md#onplay)
- [setShaderByName](m4m.framework.rawImage2D.md#setshaderbyname)

### Accessors

- [image](m4m.framework.rawImage2D.md#image)

## Properties

### color

• **color**: `color`

**`language`** zh_CN

**`classdesc`**
颜色

**`version`** m4m 1.0

#### Defined in

[framework/2d/component/rawimage.ts:67](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/rawimage.ts#L67)

___

### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh_CN

**`classdesc`**
当前组件的2d节点

**`version`** m4m 1.0

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[transform](../interfaces/m4m.framework.IRectRenderer.md#transform)

#### Defined in

[framework/2d/component/rawimage.ts:329](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/rawimage.ts#L329)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"rawImage2D"`

#### Defined in

[framework/2d/component/rawimage.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/rawimage.ts#L17)

## Constructors

### constructor

• **new rawImage2D**()

## Methods

### getDrawBounds

▸ **getDrawBounds**(): `rect`

**`language`** zh_CN

**`classdesc`**
获取渲染绘制矩形边界

**`version`** m4m 1.0

#### Returns

`rect`

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[getDrawBounds](../interfaces/m4m.framework.IRectRenderer.md#getdrawbounds)

#### Defined in

[framework/2d/component/rawimage.ts:109](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/rawimage.ts#L109)

___

### getMaterial

▸ **getMaterial**(): [`material`](m4m.framework.material.md)

**`language`** zh_CN

**`classdesc`**
获取rander 的材质

**`version`** m4m 1.0

#### Returns

[`material`](m4m.framework.material.md)

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[getMaterial](../interfaces/m4m.framework.IRectRenderer.md#getmaterial)

#### Defined in

[framework/2d/component/rawimage.ts:93](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/rawimage.ts#L93)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[onPlay](../interfaces/m4m.framework.IRectRenderer.md#onplay)

#### Defined in

[framework/2d/component/rawimage.ts:310](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/rawimage.ts#L310)

___

### setShaderByName

▸ **setShaderByName**(`shaderName`): `void`

**`language`** zh_CN

**`classdesc`**
设置rander Shader名字

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `shaderName` | `string` |

#### Returns

`void`

#### Defined in

[framework/2d/component/rawimage.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/rawimage.ts#L82)

## Accessors

### image

• `get` **image**(): [`texture`](m4m.framework.texture.md)

**`language`** zh_CN

**`classdesc`**
图片

**`version`** m4m 1.0

#### Returns

[`texture`](m4m.framework.texture.md)

#### Defined in

[framework/2d/component/rawimage.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/rawimage.ts#L40)

• `set` **image**(`_image`): `void`

**`language`** zh_CN

**`classdesc`**
图片

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `_image` | [`texture`](m4m.framework.texture.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/rawimage.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/rawimage.ts#L44)
