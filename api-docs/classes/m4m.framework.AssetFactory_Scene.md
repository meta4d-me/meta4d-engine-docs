# m4m.framework.AssetFactory\_Scene

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactory\_Scene

## Class: AssetFactory\_Scene

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactory\_Scene

### Implements

* [`IAssetFactory`](../interfaces/m4m.framework.IAssetFactory.md)

### Table of contents

#### Constructors

* [constructor](m4m.framework.AssetFactory\_Scene.md#constructor)

#### Methods

* [parse](m4m.framework.AssetFactory\_Scene.md#parse)

### Constructors

#### constructor

• **new AssetFactory\_Scene**()

### Methods

#### parse

▸ **parse**(`assetmgr`, `bundle`, `name`, `txt`): `Promise`<[`rawscene`](m4m.framework.rawscene.md)>

**Parameters**

| Name       | Type                                          |
| ---------- | --------------------------------------------- |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md)       |
| `bundle`   | [`assetBundle`](m4m.framework.assetBundle.md) |
| `name`     | `string`                                      |
| `txt`      | `string`                                      |

**Returns**

`Promise`<[`rawscene`](m4m.framework.rawscene.md)>

**Implementation of**

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[parse](../interfaces/m4m.framework.IAssetFactory.md#parse)

**Defined in**

[framework/asset/factorys/assetfactory\_scene.ts:71](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_scene.ts#L71)
