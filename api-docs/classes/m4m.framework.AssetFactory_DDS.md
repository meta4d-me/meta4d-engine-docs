# m4m.framework.AssetFactory\_DDS

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactory\_DDS

## Class: AssetFactory\_DDS

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactory\_DDS

### Implements

* [`IAssetFactory`](../interfaces/m4m.framework.IAssetFactory.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.AssetFactory\_DDS.md#constructor)

#### Methods

* [parse](m4m.framework.AssetFactory\_DDS.md#parse)

### Constructors

#### constructor

• **new AssetFactory\_DDS**()

### Methods

#### parse

▸ **parse**(`assetmgr`, `bundle`, `filename`, `bytes`): `void`

**Parameters**

| Name       | Type                                          |
| ---------- | --------------------------------------------- |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md)       |
| `bundle`   | [`assetBundle`](m4m.framework.assetBundle.md) |
| `filename` | `string`                                      |
| `bytes`    | `ArrayBuffer`                                 |

**Returns**

`void`

**Implementation of**

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[parse](../interfaces/m4m.framework.IAssetFactory.md#parse)

**Defined in**

[framework/asset/factorys/assetfactory\_dds.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_dds.ts#L68)
