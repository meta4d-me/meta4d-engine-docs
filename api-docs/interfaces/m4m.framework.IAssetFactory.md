[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IAssetFactory

# Interface: IAssetFactory

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IAssetFactory

## Implemented by

- [`AssetFactory_ASTC`](../classes/m4m.framework.AssetFactory_ASTC.md)
- [`AssetFactory_Aniclip`](../classes/m4m.framework.AssetFactory_Aniclip.md)
- [`AssetFactory_Atlas`](../classes/m4m.framework.AssetFactory_Atlas.md)
- [`AssetFactory_BIN`](../classes/m4m.framework.AssetFactory_BIN.md)
- [`AssetFactory_DDS`](../classes/m4m.framework.AssetFactory_DDS.md)
- [`AssetFactory_ETC1`](../classes/m4m.framework.AssetFactory_ETC1.md)
- [`AssetFactory_Font`](../classes/m4m.framework.AssetFactory_Font.md)
- [`AssetFactory_GLFragmentShader`](../classes/m4m.framework.AssetFactory_GLFragmentShader.md)
- [`AssetFactory_GLTF`](../classes/m4m.framework.AssetFactory_GLTF.md)
- [`AssetFactory_GLVertexShader`](../classes/m4m.framework.AssetFactory_GLVertexShader.md)
- [`AssetFactory_HDR`](../classes/m4m.framework.AssetFactory_HDR.md)
- [`AssetFactory_Material`](../classes/m4m.framework.AssetFactory_Material.md)
- [`AssetFactory_Mesh`](../classes/m4m.framework.AssetFactory_Mesh.md)
- [`AssetFactory_PVR`](../classes/m4m.framework.AssetFactory_PVR.md)
- [`AssetFactory_ParticleSystem`](../classes/m4m.framework.AssetFactory_ParticleSystem.md)
- [`AssetFactory_PathAsset`](../classes/m4m.framework.AssetFactory_PathAsset.md)
- [`AssetFactory_RAW`](../classes/m4m.framework.AssetFactory_RAW.md)
- [`AssetFactory_Scene`](../classes/m4m.framework.AssetFactory_Scene.md)
- [`AssetFactory_Shader`](../classes/m4m.framework.AssetFactory_Shader.md)
- [`AssetFactory_TextAsset`](../classes/m4m.framework.AssetFactory_TextAsset.md)
- [`AssetFactory_Texture`](../classes/m4m.framework.AssetFactory_Texture.md)
- [`AssetFactory_TextureDesc`](../classes/m4m.framework.AssetFactory_TextureDesc.md)
- [`AssetFactory_TrailRenderer`](../classes/m4m.framework.AssetFactory_TrailRenderer.md)
- [`AssetFactory_cPrefab`](../classes/m4m.framework.AssetFactory_cPrefab.md)
- [`AssetFactory_f14eff`](../classes/m4m.framework.AssetFactory_f14eff.md)
- [`assetfactory_keyFrameAniClip`](../classes/m4m.framework.assetfactory_keyFrameAniClip.md)

## Table of contents

### Methods

- [load](m4m.framework.IAssetFactory.md#load)
- [loadByPack](m4m.framework.IAssetFactory.md#loadbypack)
- [needDownload](m4m.framework.IAssetFactory.md#needdownload)
- [newAsset](m4m.framework.IAssetFactory.md#newasset)
- [parse](m4m.framework.IAssetFactory.md#parse)

## Methods

### load

▸ `Optional` **load**(`url`, `onstate`, `state`, `assetMgr`, `asset`, `call`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |
| `onstate` | (`state`: [`stateLoad`](../classes/m4m.framework.stateLoad.md)) => `void` |
| `state` | [`stateLoad`](../classes/m4m.framework.stateLoad.md) |
| `assetMgr` | [`assetMgr`](../classes/m4m.framework.assetMgr.md) |
| `asset` | [`IAsset`](m4m.framework.IAsset.md) |
| `call` | (`handle`: () => `void`) => `void` |

#### Returns

`void`

#### Defined in

[framework/asset/factorys/assetfactory_interface.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory_interface.ts#L6)

___

### loadByPack

▸ `Optional` **loadByPack**(`respack`, `url`, `onstate`, `state`, `assetMgr`, `asset`, `call`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `respack` | `any` |
| `url` | `string` |
| `onstate` | (`state`: [`stateLoad`](../classes/m4m.framework.stateLoad.md)) => `void` |
| `state` | [`stateLoad`](../classes/m4m.framework.stateLoad.md) |
| `assetMgr` | [`assetMgr`](../classes/m4m.framework.assetMgr.md) |
| `asset` | [`IAsset`](m4m.framework.IAsset.md) |
| `call` | (`handle`: () => `void`) => `void` |

#### Returns

`void`

#### Defined in

[framework/asset/factorys/assetfactory_interface.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory_interface.ts#L7)

___

### needDownload

▸ `Optional` **needDownload**(`textJSON`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `textJSON` | `string` |

#### Returns

`string`

#### Defined in

[framework/asset/factorys/assetfactory_interface.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory_interface.ts#L9)

___

### newAsset

▸ `Optional` **newAsset**(`assetName?`): [`IAsset`](m4m.framework.IAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `assetName?` | `string` |

#### Returns

[`IAsset`](m4m.framework.IAsset.md)

#### Defined in

[framework/asset/factorys/assetfactory_interface.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory_interface.ts#L5)

___

### parse

▸ **parse**(`assetMgr`, `bundle`, `name`, `data`, `dwguid?`): `void` \| [`IAsset`](m4m.framework.IAsset.md) \| `Promise`<[`IAsset`](m4m.framework.IAsset.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `assetMgr` | [`assetMgr`](../classes/m4m.framework.assetMgr.md) |
| `bundle` | [`assetBundle`](../classes/m4m.framework.assetBundle.md) |
| `name` | `string` |
| `data` | `string` \| `ArrayBuffer` |
| `dwguid?` | `number` |

#### Returns

`void` \| [`IAsset`](m4m.framework.IAsset.md) \| `Promise`<[`IAsset`](m4m.framework.IAsset.md)\>

#### Defined in

[framework/asset/factorys/assetfactory_interface.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory_interface.ts#L8)
