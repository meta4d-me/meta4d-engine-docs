[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactory\_Texture

# Class: AssetFactory\_Texture

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactory_Texture

## Implements

- [`IAssetFactory`](../interfaces/m4m.framework.IAssetFactory.md)

## Table of contents

### Constructors

- [constructor](m4m.framework.AssetFactory_Texture.md#constructor)

### Methods

- [parse](m4m.framework.AssetFactory_Texture.md#parse)

## Constructors

### constructor

• **new AssetFactory_Texture**()

## Methods

### parse

▸ **parse**(`assetmgr`, `bundle`, `filename`, `txt`, `dwguid`): [`texture`](m4m.framework.texture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `bundle` | [`assetBundle`](m4m.framework.assetBundle.md) |
| `filename` | `string` |
| `txt` | `string` |
| `dwguid` | `number` |

#### Returns

[`texture`](m4m.framework.texture.md)

#### Implementation of

[IAssetFactory](../interfaces/m4m.framework.IAssetFactory.md).[parse](../interfaces/m4m.framework.IAssetFactory.md#parse)

#### Defined in

[framework/asset/factorys/assetfactory_texture.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory_texture.ts#L53)
