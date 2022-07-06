# m4m.framework.F14RefElementBatch

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14RefElementBatch

## Class: F14RefElementBatch

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14RefElementBatch

### Implements

* [`F14Basebatch`](../interfaces/m4m.framework.F14Basebatch.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.F14RefElementBatch.md#constructor)

#### Methods

* [dispose](m4m.framework.F14RefElementBatch.md#dispose)
* [getElementCount](m4m.framework.F14RefElementBatch.md#getelementcount)
* [render](m4m.framework.F14RefElementBatch.md#render)
* [unRender](m4m.framework.F14RefElementBatch.md#unrender)

#### Properties

* [effect](m4m.framework.F14RefElementBatch.md#effect)
* [type](m4m.framework.F14RefElementBatch.md#type)

### Constructors

#### constructor

• **new F14RefElementBatch**(`effect`, `element`)

**Parameters**

| Name      | Type                                                  |
| --------- | ----------------------------------------------------- |
| `effect`  | [`f14EffectSystem`](m4m.framework.f14EffectSystem.md) |
| `element` | [`F14RefElement`](m4m.framework.F14RefElement.md)     |

**Defined in**

[framework/component/f14effectsystem/refelement/f14refbatch.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refbatch.ts#L8)

### Methods

#### dispose

▸ **dispose**(): `void`

**Returns**

`void`

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[dispose](../interfaces/m4m.framework.F14Basebatch.md#dispose)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refbatch.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refbatch.ts#L34)

***

#### getElementCount

▸ **getElementCount**(): `number`

**Returns**

`number`

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[getElementCount](../interfaces/m4m.framework.F14Basebatch.md#getelementcount)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refbatch.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refbatch.ts#L18)

***

#### render

▸ **render**(`context`, `assetmgr`, `camera`, `Effqueue`): `void`

**Parameters**

| Name       | Type                                    |
| ---------- | --------------------------------------- |
| `context`  | `renderContext`                         |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `camera`   | [`camera`](m4m.framework.camera.md)     |
| `Effqueue` | `number`                                |

**Returns**

`void`

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[render](../interfaces/m4m.framework.F14Basebatch.md#render)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refbatch.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refbatch.ts#L22)

***

#### unRender

▸ **unRender**(): `void`

**Returns**

`void`

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[unRender](../interfaces/m4m.framework.F14Basebatch.md#unrender)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refbatch.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refbatch.ts#L14)

### Properties

#### effect

• **effect**: [`f14EffectSystem`](m4m.framework.f14EffectSystem.md)

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[effect](../interfaces/m4m.framework.F14Basebatch.md#effect)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refbatch.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refbatch.ts#L6)

***

#### type

• **type**: [`F14TypeEnum`](../enums/m4m.framework.F14TypeEnum.md)

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[type](../interfaces/m4m.framework.F14Basebatch.md#type)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refbatch.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refbatch.ts#L5)
