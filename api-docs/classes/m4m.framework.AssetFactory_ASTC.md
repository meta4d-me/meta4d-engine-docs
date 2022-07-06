# m4m.framework.AssetFactory\_ASTC

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactory\_ASTC

## Class: AssetFactory\_ASTC

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactory\_ASTC

### Implements

* [`IAssetFactory`](../interfaces/m4m.framework.IAssetFactory.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.AssetFactory\_ASTC.md#constructor)

#### Methods

* [parse](m4m.framework.AssetFactory\_ASTC.md#parse)

### Constructors

#### constructor

• **new AssetFactory\_ASTC**()

### Methods

#### parse

▸ **parse**(`assetmgr`, `bundle`, `name`, `bytes`, `dwguid`): [`texture`](m4m.framework.texture.md)

**Parameters**

| Name       | Type                                          |
| ---------- | --------------------------------------------- |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md)       |
| `bundle`   | [`assetBundle`](m4m.framework.assetBundle.md) |
| `name`     | `string`                                      |
| `bytes`    | `ArrayBuffer`                                 |
| `dwguid`   | `number`                                      |

**Returns**

[`texture`](m4m.framework.texture.md)

**Implementation of**

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[parse](../interfaces/m4m.framework.IAssetFactory.md#parse)

**Defined in**

[framework/asset/factorys/assetfactory\_astc.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_astc.ts#L6)
