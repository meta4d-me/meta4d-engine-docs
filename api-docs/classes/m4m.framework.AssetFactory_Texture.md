# m4m.framework.AssetFactory\_Texture

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactory\_Texture

## Class: AssetFactory\_Texture

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactory\_Texture

### Implements

* [`IAssetFactory`](../interfaces/m4m.framework.IAssetFactory.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.AssetFactory\_Texture.md#constructor)

#### Methods

* [parse](m4m.framework.AssetFactory\_Texture.md#parse)

### Constructors

#### constructor

• **new AssetFactory\_Texture**()

### Methods

#### parse

▸ **parse**(`assetmgr`, `bundle`, `filename`, `txt`, `dwguid`): [`texture`](m4m.framework.texture.md)

**Parameters**

| Name       | Type                                          |
| ---------- | --------------------------------------------- |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md)       |
| `bundle`   | [`assetBundle`](m4m.framework.assetBundle.md) |
| `filename` | `string`                                      |
| `txt`      | `string`                                      |
| `dwguid`   | `number`                                      |

**Returns**

[`texture`](m4m.framework.texture.md)

**Implementation of**

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[parse](../interfaces/m4m.framework.IAssetFactory.md#parse)

**Defined in**

[framework/asset/factorys/assetfactory\_texture.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_texture.ts#L53)
