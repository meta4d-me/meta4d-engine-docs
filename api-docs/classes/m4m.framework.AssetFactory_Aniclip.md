# m4m.framework.AssetFactory\_Aniclip

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactory\_Aniclip

## Class: AssetFactory\_Aniclip

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactory\_Aniclip

### Implements

* [`IAssetFactory`](../interfaces/m4m.framework.IAssetFactory.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.AssetFactory\_Aniclip.md#constructor)

#### Methods

* [parse](m4m.framework.AssetFactory\_Aniclip.md#parse)

### Constructors

#### constructor

• **new AssetFactory\_Aniclip**()

### Methods

#### parse

▸ **parse**(`assetmgr`, `bundle`, `filename`, `bytes`): `Promise`<[`animationClip`](m4m.framework.animationClip.md)>

**Parameters**

| Name       | Type                                          |
| ---------- | --------------------------------------------- |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md)       |
| `bundle`   | [`assetBundle`](m4m.framework.assetBundle.md) |
| `filename` | `string`                                      |
| `bytes`    | `ArrayBuffer`                                 |

**Returns**

`Promise`<[`animationClip`](m4m.framework.animationClip.md)>

**Implementation of**

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[parse](../interfaces/m4m.framework.IAssetFactory.md#parse)

**Defined in**

[framework/asset/factorys/assetfactory\_aniclip.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_aniclip.ts#L79)
