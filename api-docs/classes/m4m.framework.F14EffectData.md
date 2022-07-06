# m4m.framework.F14EffectData

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14EffectData

## Class: F14EffectData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14EffectData

### Table of contents

#### Properties

* [beloop](m4m.framework.F14EffectData.md#beloop)
* [layers](m4m.framework.F14EffectData.md#layers)
* [lifeTime](m4m.framework.F14EffectData.md#lifetime)

#### Constructors

* [constructor](m4m.framework.F14EffectData.md#constructor)

#### Methods

* [parsejson](m4m.framework.F14EffectData.md#parsejson)

### Properties

#### beloop

• **beloop**: `boolean` = `false`

**Defined in**

[framework/component/f14effectsystem/data/f14effectdata.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/f14effectdata.ts#L5)

***

#### layers

• **layers**: [`F14LayerData`](m4m.framework.F14LayerData.md)\[] = `[]`

**Defined in**

[framework/component/f14effectsystem/data/f14effectdata.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/f14effectdata.ts#L7)

***

#### lifeTime

• **lifeTime**: `number` = `100`

**Defined in**

[framework/component/f14effectsystem/data/f14effectdata.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/f14effectdata.ts#L6)

### Constructors

#### constructor

• **new F14EffectData**()

### Methods

#### parsejson

▸ **parsejson**(`json`, `assetmgr`, `assetbundle`): [`F14EffectData`](m4m.framework.F14EffectData.md)

**Parameters**

| Name          | Type                                    |
| ------------- | --------------------------------------- |
| `json`        | `any`                                   |
| `assetmgr`    | [`assetMgr`](m4m.framework.assetMgr.md) |
| `assetbundle` | `string`                                |

**Returns**

[`F14EffectData`](m4m.framework.F14EffectData.md)

**Defined in**

[framework/component/f14effectsystem/data/f14effectdata.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/data/f14effectdata.ts#L9)
