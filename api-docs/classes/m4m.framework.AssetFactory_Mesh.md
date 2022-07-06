# m4m.framework.AssetFactory\_Mesh

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactory\_Mesh

## Class: AssetFactory\_Mesh

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactory\_Mesh

### Implements

* [`IAssetFactory`](../interfaces/m4m.framework.IAssetFactory.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.AssetFactory\_Mesh.md#constructor)

#### Methods

* [parse](m4m.framework.AssetFactory\_Mesh.md#parse)

### Constructors

#### constructor

• **new AssetFactory\_Mesh**()

### Methods

#### parse

▸ **parse**(`assetMgr`, `bundle`, `name`, `data`): `Promise`<[`IAsset`](../interfaces/m4m.framework.IAsset.md)>

**Parameters**

| Name       | Type                                          |
| ---------- | --------------------------------------------- |
| `assetMgr` | [`assetMgr`](m4m.framework.assetMgr.md)       |
| `bundle`   | [`assetBundle`](m4m.framework.assetBundle.md) |
| `name`     | `string`                                      |
| `data`     | `ArrayBuffer`                                 |

**Returns**

`Promise`<[`IAsset`](../interfaces/m4m.framework.IAsset.md)>

**Implementation of**

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[parse](../interfaces/m4m.framework.IAssetFactory.md#parse)

**Defined in**

[framework/asset/factorys/assetfactory\_mesh.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_mesh.ts#L106)
