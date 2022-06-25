[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / progressbar

# Class: progressbar

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).progressbar

**`language`** zh_CN

**`classdesc`**
进度条

**`version`** m4m 1.0

## Implements

- [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)

## Table of contents

### Accessors

- [barBg](m4m.framework.progressbar.md#barbg)
- [barOverImg](m4m.framework.progressbar.md#baroverimg)
- [cutPanel](m4m.framework.progressbar.md#cutpanel)
- [value](m4m.framework.progressbar.md#value)

### Constructors

- [constructor](m4m.framework.progressbar.md#constructor)

### Methods

- [onPlay](m4m.framework.progressbar.md#onplay)

### Properties

- [transform](m4m.framework.progressbar.md#transform)
- [ClassName](m4m.framework.progressbar.md#classname)

## Accessors

### barBg

• `get` **barBg**(): [`image2D`](m4m.framework.image2D.md)

进度条 背景图

#### Returns

[`image2D`](m4m.framework.image2D.md)

#### Defined in

[framework/2d/component/progressbar.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L35)

• `set` **barBg**(`img`): `void`

进度条 背景图

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | [`image2D`](m4m.framework.image2D.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/progressbar.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L38)

___

### barOverImg

• `get` **barOverImg**(): [`image2D`](m4m.framework.image2D.md)

进度条 上层覆盖图

#### Returns

[`image2D`](m4m.framework.image2D.md)

#### Defined in

[framework/2d/component/progressbar.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L48)

• `set` **barOverImg**(`img`): `void`

进度条 上层覆盖图

#### Parameters

| Name | Type |
| :------ | :------ |
| `img` | [`image2D`](m4m.framework.image2D.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/progressbar.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L51)

___

### cutPanel

• `get` **cutPanel**(): [`transform2D`](m4m.framework.transform2D.md)

裁切容器

#### Returns

[`transform2D`](m4m.framework.transform2D.md)

#### Defined in

[framework/2d/component/progressbar.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L22)

• `set` **cutPanel**(`trans`): `void`

裁切容器

#### Parameters

| Name | Type |
| :------ | :------ |
| `trans` | [`transform2D`](m4m.framework.transform2D.md) |

#### Returns

`void`

#### Defined in

[framework/2d/component/progressbar.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L25)

___

### value

• `get` **value**(): `number`

进度值 0-1

#### Returns

`number`

#### Defined in

[framework/2d/component/progressbar.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L61)

• `set` **value**(`value`): `void`

进度值 0-1

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Defined in

[framework/2d/component/progressbar.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L64)

## Constructors

### constructor

• **new progressbar**()

## Methods

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[onPlay](../interfaces/m4m.framework.I2DComponent.md#onplay)

#### Defined in

[framework/2d/component/progressbar.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L79)

## Properties

### transform

• **transform**: [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh_CN

**`classdesc`**
当前组件的2d节点

**`version`** m4m 1.0

#### Implementation of

[I2DComponent](../interfaces/m4m.framework.I2DComponent.md).[transform](../interfaces/m4m.framework.I2DComponent.md#transform)

#### Defined in

[framework/2d/component/progressbar.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L116)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"progressbar"`

#### Defined in

[framework/2d/component/progressbar.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/component/progressbar.ts#L15)
