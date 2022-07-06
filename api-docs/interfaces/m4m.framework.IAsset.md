# m4m.framework.IAsset

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IAsset

## Interface: IAsset

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IAsset

**`language`** zh\_CN

**`classdesc`** 资源接口 扩展资源需要继承此接口

**`version`** m4m 1.0

### Implemented by

* [`ParticleSystemData`](../classes/m4m.framework.ParticleSystemData.md)
* [`TrailRendererData`](../classes/m4m.framework.TrailRendererData.md)
* [`animationClip`](../classes/m4m.framework.animationClip.md)
* [`atlas`](../classes/m4m.framework.atlas.md)
* [`bin`](../classes/m4m.framework.bin.md)
* [`f14eff`](../classes/m4m.framework.f14eff.md)
* [`font`](../classes/m4m.framework.font.md)
* [`gltf`](../classes/m4m.framework.gltf.md)
* [`keyFrameAniClip`](../classes/m4m.framework.keyFrameAniClip.md)
* [`material`](../classes/m4m.framework.material.md)
* [`mesh`](../classes/m4m.framework.mesh.md)
* [`pathasset`](../classes/m4m.framework.pathasset.md)
* [`prefab`](../classes/m4m.framework.prefab.md)
* [`rawscene`](../classes/m4m.framework.rawscene.md)
* [`shader`](../classes/m4m.framework.shader.md)
* [`sprite`](../classes/m4m.framework.sprite.md)
* [`textasset`](../classes/m4m.framework.textasset.md)
* [`texture`](../classes/m4m.framework.texture.md)

### Table of contents

#### Properties

* [bundle](m4m.framework.IAsset.md#bundle)
* [defaultAsset](m4m.framework.IAsset.md#defaultasset)

#### Methods

* [caclByteLength](m4m.framework.IAsset.md#caclbytelength)
* [dispose](m4m.framework.IAsset.md#dispose)
* [getGUID](m4m.framework.IAsset.md#getguid)
* [getName](m4m.framework.IAsset.md#getname)
* [init](m4m.framework.IAsset.md#init)
* [unuse](m4m.framework.IAsset.md#unuse)
* [use](m4m.framework.IAsset.md#use)

### Properties

#### bundle

• `Optional` **bundle**: [`assetBundle`](../classes/m4m.framework.assetBundle.md)

**Defined in**

[framework/asset/asset.ts:60](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/asset.ts#L60)

***

#### defaultAsset

• **defaultAsset**: `boolean`

**Defined in**

[framework/asset/asset.ts:62](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/asset.ts#L62)

### Methods

#### caclByteLength

▸ **caclByteLength**(): `number`

**Returns**

`number`

**Defined in**

[framework/asset/asset.ts:70](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/asset.ts#L70)

***

#### dispose

▸ **dispose**(): `any`

**Returns**

`any`

**Defined in**

[framework/asset/asset.ts:69](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/asset.ts#L69)

***

#### getGUID

▸ **getGUID**(): `number`

**Returns**

`number`

**Defined in**

[framework/asset/asset.ts:65](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/asset.ts#L65)

***

#### getName

▸ **getName**(): `string`

**Returns**

`string`

**Defined in**

[framework/asset/asset.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/asset.ts#L64)

***

#### init

▸ `Optional` **init**(): `any`

**Returns**

`any`

**Defined in**

[framework/asset/asset.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/asset.ts#L71)

***

#### unuse

▸ **unuse**(`disposeNow?`): `void`

**Parameters**

| Name          | Type      |
| ------------- | --------- |
| `disposeNow?` | `boolean` |

**Returns**

`void`

**Defined in**

[framework/asset/asset.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/asset.ts#L68)

***

#### use

▸ **use**(): `void`

**Returns**

`void`

**Defined in**

[framework/asset/asset.ts:67](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/asset.ts#L67)
