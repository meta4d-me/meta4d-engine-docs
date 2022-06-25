[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14Layer

# Class: F14Layer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14Layer

## Table of contents

### Properties

- [Attlines](m4m.framework.F14Layer.md#attlines)
- [active](m4m.framework.F14Layer.md#active)
- [batch](m4m.framework.F14Layer.md#batch)
- [data](m4m.framework.F14Layer.md#data)
- [effect](m4m.framework.F14Layer.md#effect)
- [element](m4m.framework.F14Layer.md#element)
- [frameList](m4m.framework.F14Layer.md#framelist)
- [frames](m4m.framework.F14Layer.md#frames)
- [type](m4m.framework.F14Layer.md#type)

### Methods

- [addFrame](m4m.framework.F14Layer.md#addframe)
- [dispose](m4m.framework.F14Layer.md#dispose)
- [removeFrame](m4m.framework.F14Layer.md#removeframe)

### Constructors

- [constructor](m4m.framework.F14Layer.md#constructor)

## Properties

### Attlines

• **Attlines**: `Object` = `{}`

#### Index signature

▪ [name: `string`]: [`F14AttTimeLine`](m4m.framework.F14AttTimeLine.md)

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L14)

___

### active

• **active**: `boolean` = `true`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L5)

___

### batch

• **batch**: [`F14Basebatch`](../interfaces/m4m.framework.F14Basebatch.md)

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L17)

___

### data

• **data**: [`F14LayerData`](m4m.framework.F14LayerData.md)

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L8)

___

### effect

• **effect**: [`f14EffectSystem`](m4m.framework.f14EffectSystem.md)

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L6)

___

### element

• **element**: [`F14Element`](../interfaces/m4m.framework.F14Element.md)

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L16)

___

### frameList

• **frameList**: `number`[] = `[]`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L11)

___

### frames

• **frames**: `Object` = `{}`

#### Index signature

▪ [index: `number`]: [`F14Frame`](m4m.framework.F14Frame.md)

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L12)

___

### type

• **type**: [`F14TypeEnum`](../enums/m4m.framework.F14TypeEnum.md)

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L9)

## Methods

### addFrame

▸ **addFrame**(`index`, `framedata`): [`F14Frame`](m4m.framework.F14Frame.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |
| `framedata` | [`F14FrameData`](m4m.framework.F14FrameData.md) |

#### Returns

[`F14Frame`](m4m.framework.F14Frame.md)

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L40)

___

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:78](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L78)

___

### removeFrame

▸ **removeFrame**(`frame`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `frame` | `number` |

#### Returns

`void`

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L59)

## Constructors

### constructor

• **new F14Layer**(`effect`, `data`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `effect` | [`f14EffectSystem`](m4m.framework.f14EffectSystem.md) |
| `data` | [`F14LayerData`](m4m.framework.F14LayerData.md) |

#### Defined in

[framework/component/f14effectsystem/f14layer.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14layer.ts#L18)
