# m4m.framework.AssetFactory\_BIN

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactory\_BIN

## Class: AssetFactory\_BIN

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactory\_BIN

### Implements

* [`IAssetFactory`](../interfaces/m4m.framework.IAssetFactory.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.AssetFactory\_BIN.md#constructor)

#### Methods

* [parse](m4m.framework.AssetFactory\_BIN.md#parse)

### Constructors

#### constructor

• **new AssetFactory\_BIN**()

### Methods

#### parse

▸ **parse**(`assetmgr`, `bundle`, `name`, `bytes`): [`bin`](m4m.framework.bin.md)

**Parameters**

| Name       | Type                                          |
| ---------- | --------------------------------------------- |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md)       |
| `bundle`   | [`assetBundle`](m4m.framework.assetBundle.md) |
| `name`     | `string`                                      |
| `bytes`    | `ArrayBuffer`                                 |

**Returns**

[`bin`](m4m.framework.bin.md)

**Implementation of**

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[parse](../interfaces/m4m.framework.IAssetFactory.md#parse)

**Defined in**

[framework/asset/factorys/assetfactory\_bin.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_bin.ts#L6)
