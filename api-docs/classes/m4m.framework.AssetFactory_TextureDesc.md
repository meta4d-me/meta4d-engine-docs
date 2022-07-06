# m4m.framework.AssetFactory\_TextureDesc

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactory\_TextureDesc

## Class: AssetFactory\_TextureDesc

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactory\_TextureDesc

### Implements

* [`IAssetFactory`](../interfaces/m4m.framework.IAssetFactory.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.AssetFactory\_TextureDesc.md#constructor)

#### Methods

* [needDownload](m4m.framework.AssetFactory\_TextureDesc.md#needdownload)
* [parse](m4m.framework.AssetFactory\_TextureDesc.md#parse)

### Constructors

#### constructor

• **new AssetFactory\_TextureDesc**()

### Methods

#### needDownload

▸ **needDownload**(`text`): `any`

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `text` | `string` |

**Returns**

`any`

**Implementation of**

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[needDownload](../interfaces/m4m.framework.IAssetFactory.md#needdownload)

**Defined in**

[framework/asset/factorys/assetfactory\_texturedesc.ts:232](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_texturedesc.ts#L232)

***

#### parse

▸ **parse**(`assetmgr`, `bundle`, `name`, `data`, `dwguid`): [`texture`](m4m.framework.texture.md)

**Parameters**

| Name       | Type                                          |
| ---------- | --------------------------------------------- |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md)       |
| `bundle`   | [`assetBundle`](m4m.framework.assetBundle.md) |
| `name`     | `string`                                      |
| `data`     | `string`                                      |
| `dwguid`   | `number`                                      |

**Returns**

[`texture`](m4m.framework.texture.md)

**Implementation of**

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[parse](../interfaces/m4m.framework.IAssetFactory.md#parse)

**Defined in**

[framework/asset/factorys/assetfactory\_texturedesc.ts:141](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_texturedesc.ts#L141)
