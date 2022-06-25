[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystemEvent

# Class: ParticleSystemEvent

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystemEvent

**`language`** zh_CN

**`classdesc`**
ui事件

**`version`** m4m 1.0

## Hierarchy

- [`AEvent`](m4m.AEvent.md)

  ↳ **`ParticleSystemEvent`**

## Table of contents

### Methods

- [Emit](m4m.framework.ParticleSystemEvent.md#emit)
- [Off](m4m.framework.ParticleSystemEvent.md#off)
- [On](m4m.framework.ParticleSystemEvent.md#on)
- [RemoveListener](m4m.framework.ParticleSystemEvent.md#removelistener)
- [RemoveListenerAll](m4m.framework.ParticleSystemEvent.md#removelistenerall)
- [listenerCount](m4m.framework.ParticleSystemEvent.md#listenercount)

### Constructors

- [constructor](m4m.framework.ParticleSystemEvent.md#constructor)

## Methods

### Emit

▸ **Emit**<`K`\>(`event`, `args`): `void`

发出事件

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"particleCompleted"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `K` |
| `args` | [`GameObjectEventMap`](../interfaces/m4m.framework.GameObjectEventMap.md)[`K`] |

#### Returns

`void`

#### Overrides

[AEvent](m4m.AEvent.md).[Emit](m4m.AEvent.md#emit)

#### Defined in

[framework/particlesystem/ParticleSystem.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L32)

___

### Off

▸ **Off**<`K`\>(`event`, `func`, `thisArg`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"particleCompleted"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `K` |
| `func` | (`args`: [`GameObjectEventMap`](../interfaces/m4m.framework.GameObjectEventMap.md)[`K`]) => `void` |
| `thisArg` | `any` |

#### Returns

`void`

#### Defined in

[framework/particlesystem/ParticleSystem.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L27)

___

### On

▸ **On**<`K`\>(`event`, `func`, `thisArg`): `void`

监听事件添加

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"particleCompleted"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `K` |
| `func` | (`args`: [`GameObjectEventMap`](../interfaces/m4m.framework.GameObjectEventMap.md)[`K`]) => `void` |
| `thisArg` | `any` |

#### Returns

`void`

#### Overrides

[AEvent](m4m.AEvent.md).[On](m4m.AEvent.md#on)

#### Defined in

[framework/particlesystem/ParticleSystem.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/ParticleSystem.ts#L22)

___

### RemoveListener

▸ **RemoveListener**(`event`, `func`, `thisArg`): `void`

移除事件监听者

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | `string` | 事件类型 |
| `func` | `Function` | 事件触发回调方法 |
| `thisArg` | `any` | 回调方法执行者 |

#### Returns

`void`

#### Inherited from

[AEvent](m4m.AEvent.md).[RemoveListener](m4m.AEvent.md#removelistener)

#### Defined in

[framework/event/AEvent.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L58)

___

### RemoveListenerAll

▸ **RemoveListenerAll**(): `void`

移除所有监听者

#### Returns

`void`

#### Inherited from

[AEvent](m4m.AEvent.md).[RemoveListenerAll](m4m.AEvent.md#removelistenerall)

#### Defined in

[framework/event/AEvent.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L83)

___

### listenerCount

▸ **listenerCount**(`event`): `number`

指定事件监听者的数量

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `string` |

#### Returns

`number`

#### Inherited from

[AEvent](m4m.AEvent.md).[listenerCount](m4m.AEvent.md#listenercount)

#### Defined in

[framework/event/AEvent.ts:91](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/event/AEvent.ts#L91)

## Constructors

### constructor

• **new ParticleSystemEvent**()

#### Inherited from

[AEvent](m4m.AEvent.md).[constructor](m4m.AEvent.md#constructor)
