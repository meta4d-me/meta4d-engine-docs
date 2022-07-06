# m4m.framework.F14RefBaseData

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14RefBaseData

## Class: F14RefBaseData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14RefBaseData

### Implements

* [`F14ElementData`](../interfaces/m4m.framework.F14ElementData.md)

### Table of contents

#### Properties

* [beLoop](m4m.framework.F14RefBaseData.md#beloop)
* [localEuler](m4m.framework.F14RefBaseData.md#localeuler)
* [localPos](m4m.framework.F14RefBaseData.md#localpos)
* [localScale](m4m.framework.F14RefBaseData.md#localscale)
* [refData](m4m.framework.F14RefBaseData.md#refdata)
* [refdataName](m4m.framework.F14RefBaseData.md#refdataname)

#### Constructors

* [constructor](m4m.framework.F14RefBaseData.md#constructor)

#### Methods

* [parse](m4m.framework.F14RefBaseData.md#parse)

### Properties

#### beLoop

• **beLoop**: `boolean` = `false`

**Defined in**

[framework/component/f14effectsystem/refelement/f14refdata.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refdata.ts#L6)

***

#### localEuler

• **localEuler**: `vector3`

**Defined in**

[framework/component/f14effectsystem/refelement/f14refdata.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refdata.ts#L11)

***

#### localPos

• **localPos**: `vector3`

**Defined in**

[framework/component/f14effectsystem/refelement/f14refdata.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refdata.ts#L10)

***

#### localScale

• **localScale**: `vector3`

**Defined in**

[framework/component/f14effectsystem/refelement/f14refdata.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refdata.ts#L12)

***

#### refData

• **refData**: [`F14EffectData`](m4m.framework.F14EffectData.md)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refdata.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refdata.ts#L8)

***

#### refdataName

• **refdataName**: `string`

**Defined in**

[framework/component/f14effectsystem/refelement/f14refdata.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refdata.ts#L7)

### Constructors

#### constructor

• **new F14RefBaseData**()

### Methods

#### parse

▸ **parse**(`json`, `assetmgr`, `assetbundle`): `void`

**Parameters**

| Name          | Type                                    |
| ------------- | --------------------------------------- |
| `json`        | `any`                                   |
| `assetmgr`    | [`assetMgr`](m4m.framework.assetMgr.md) |
| `assetbundle` | `string`                                |

**Returns**

`void`

**Implementation of**

[F14ElementData](../interfaces/m4m.framework.F14ElementData.md).[parse](../interfaces/m4m.framework.F14ElementData.md#parse)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refdata.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refdata.ts#L14)
