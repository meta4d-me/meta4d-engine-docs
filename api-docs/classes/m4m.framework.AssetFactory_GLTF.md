# m4m.framework.AssetFactory\_GLTF

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactory\_GLTF

## Class: AssetFactory\_GLTF

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactory\_GLTF

### Implements

* [`IAssetFactory`](../interfaces/m4m.framework.IAssetFactory.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.AssetFactory\_GLTF.md#constructor)

#### Methods

* [parse](m4m.framework.AssetFactory\_GLTF.md#parse)

### Constructors

#### constructor

• **new AssetFactory\_GLTF**()

### Methods

#### parse

▸ **parse**(`assetmgr`, `bundle`, `filename`, `txt`): [`gltf`](m4m.framework.gltf.md)

**Parameters**

| Name       | Type                                          |
| ---------- | --------------------------------------------- |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md)       |
| `bundle`   | [`assetBundle`](m4m.framework.assetBundle.md) |
| `filename` | `string`                                      |
| `txt`      | `string`                                      |

**Returns**

[`gltf`](m4m.framework.gltf.md)

**Implementation of**

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[parse](../interfaces/m4m.framework.IAssetFactory.md#parse)

**Defined in**

[framework/asset/factorys/assetfactory\_gltf.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_gltf.ts#L6)
