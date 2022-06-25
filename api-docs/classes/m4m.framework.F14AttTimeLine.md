[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14AttTimeLine

# Class: F14AttTimeLine

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14AttTimeLine

## Table of contents

### Methods

- [addNode](m4m.framework.F14AttTimeLine.md#addnode)
- [getValue](m4m.framework.F14AttTimeLine.md#getvalue)
- [remove](m4m.framework.F14AttTimeLine.md#remove)

### Properties

- [cloneFunc](m4m.framework.F14AttTimeLine.md#clonefunc)
- [frameList](m4m.framework.F14AttTimeLine.md#framelist)
- [lerpFunc](m4m.framework.F14AttTimeLine.md#lerpfunc)
- [line](m4m.framework.F14AttTimeLine.md#line)
- [name](m4m.framework.F14AttTimeLine.md#name)

### Constructors

- [constructor](m4m.framework.F14AttTimeLine.md#constructor)

## Methods

### addNode

▸ **addNode**(`frame`, `value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `frame` | `number` |
| `value` | `any` |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:157](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L157)

___

### getValue

▸ **getValue**(`frame`, `basedate`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `frame` | `number` |
| `basedate` | [`F14SingleMeshBaseData`](m4m.framework.F14SingleMeshBaseData.md) |
| `out` | `any` |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:178](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L178)

___

### remove

▸ **remove**(`frame`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `frame` | `number` |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:167](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L167)

## Properties

### cloneFunc

• **cloneFunc**: (`from`: `any`, `to`: `any`) => `void`

#### Type declaration

▸ (`from`, `to`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `any` |
| `to` | `any` |

##### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:145](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L145)

___

### frameList

• **frameList**: `number`[] = `[]`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:153](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L153)

___

### lerpFunc

• **lerpFunc**: (`from`: `any`, `to`: `any`, `lerp`: `any`, `out`: `any`) => `void`

#### Type declaration

▸ (`from`, `to`, `lerp`, `out`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `any` |
| `to` | `any` |
| `lerp` | `any` |
| `out` | `any` |

##### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:144](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L144)

___

### line

• **line**: `Object` = `{}`

#### Index signature

▪ [index: `number`]: `any`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:154](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L154)

___

### name

• **name**: `string`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:143](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L143)

## Constructors

### constructor

• **new F14AttTimeLine**(`name`, `lerpfunc`, `clonefunc`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `lerpfunc` | (`from`: `any`, `to`: `any`, `lerp`: `any`, `out`: `any`) => `void` |
| `clonefunc` | (`from`: `any`, `to`: `any`) => `void` |

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:146](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L146)
