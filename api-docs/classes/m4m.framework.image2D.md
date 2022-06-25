[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / image2D

# Class: image2D

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).image2D

**`language`** zh_CN

**`classdesc`**
2d图片组件

**`version`** m4m 1.0

## Implements

- [`IRectRenderer`](../interfaces/m4m.framework.IRectRenderer.md)

## Table of contents

### Properties

- [color](m4m.framework.image2D.md#color)
- [transform](m4m.framework.image2D.md#transform)
- [ClassName](m4m.framework.image2D.md#classname)

### Accessors

- [fillAmmount](m4m.framework.image2D.md#fillammount)
- [fillMethod](m4m.framework.image2D.md#fillmethod)
- [imageBorder](m4m.framework.image2D.md#imageborder)
- [imageType](m4m.framework.image2D.md#imagetype)
- [sprite](m4m.framework.image2D.md#sprite)

### Methods

- [getDrawBounds](m4m.framework.image2D.md#getdrawbounds)
- [getMaterial](m4m.framework.image2D.md#getmaterial)
- [onPlay](m4m.framework.image2D.md#onplay)
- [setShaderByName](m4m.framework.image2D.md#setshaderbyname)

## Properties

### color

• **color**: `color`

**`language`** zh_CN

**`classdesc`**
颜色

**`version`** m4m 1.0

#### Defined in

[framework/2d/component/image.ts:50](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L50)

___

### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[transform](../interfaces/m4m.framework.IRectRenderer.md#transform)

#### Defined in

[framework/2d/component/image.ts:203](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L203)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"image2D"`

#### Defined in

[framework/2d/component/image.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L16)

## Accessors

### fillAmmount

• `get` **fillAmmount**(): `number`

**`language`** zh_CN

**`classdesc`**
填充率

**`version`** m4m 1.0

#### Returns

`number`

#### Defined in

[framework/2d/component/image.ts:192](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L192)

• `set` **fillAmmount**(`ammount`): `void`

**`language`** zh_CN

**`classdesc`**
填充率

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `ammount` | `number` |

#### Returns

`void`

#### Defined in

[framework/2d/component/image.ts:196](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L196)

___

### fillMethod

• `get` **fillMethod**(): [`FillMethod`](../enums/m4m.framework.FillMethod.md)

**`language`** zh_CN

**`classdesc`**
图片填充方式

**`version`** m4m 1.0

#### Returns

[`FillMethod`](../enums/m4m.framework.FillMethod.md)

#### Defined in

[framework/2d/component/image.ts:171](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L171)

• `set` **fillMethod**(`method`): `void`

**`language`** zh_CN

**`classdesc`**
图片填充方式

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | [`FillMethod`](../enums/m4m.framework.FillMethod.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/image.ts:175](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L175)

___

### imageBorder

• `get` **imageBorder**(): `border`

**`language`** zh_CN

**`classdesc`**
9宫格边距

**`version`** m4m 1.0

#### Returns

`border`

#### Defined in

[framework/2d/component/image.ts:297](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L297)

___

### imageType

• `get` **imageType**(): [`ImageType`](../enums/m4m.framework.ImageType.md)

**`language`** zh_CN

**`classdesc`**
图片显示模式

**`version`** m4m 1.0

#### Returns

[`ImageType`](../enums/m4m.framework.ImageType.md)

#### Defined in

[framework/2d/component/image.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L149)

• `set` **imageType**(`type`): `void`

**`language`** zh_CN

**`classdesc`**
图片显示模式

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | [`ImageType`](../enums/m4m.framework.ImageType.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/image.ts:153](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L153)

___

### sprite

• `get` **sprite**(): [`sprite`](m4m.framework.sprite.md)

**`language`** zh_CN

**`classdesc`**
精灵

**`version`** m4m 1.0

#### Returns

[`sprite`](m4m.framework.sprite.md)

#### Defined in

[framework/2d/component/image.ts:279](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L279)

• `set` **sprite**(`sprite`): `void`

**`language`** zh_CN

**`classdesc`**
精灵

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `sprite` | [`sprite`](m4m.framework.sprite.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/image.ts:249](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L249)

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

[framework/2d/component/image.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L90)

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

[framework/2d/component/image.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L74)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[IRectRenderer](../interfaces/m4m.framework.IRectRenderer.md).[onPlay](../interfaces/m4m.framework.IRectRenderer.md#onplay)

#### Defined in

[framework/2d/component/image.ts:367](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L367)

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

[framework/2d/component/image.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/image.ts#L63)
