# m4m.framework.IAssetFactory

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IAssetFactory

## Interface: IAssetFactory

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IAssetFactory

### Implemented by

* [`AssetFactory_ASTC`](../classes/m4m.framework.AssetFactory\_ASTC.md)
* [`AssetFactory_Aniclip`](../classes/m4m.framework.AssetFactory\_Aniclip.md)
* [`AssetFactory_Atlas`](../classes/m4m.framework.AssetFactory\_Atlas.md)
* [`AssetFactory_BIN`](../classes/m4m.framework.AssetFactory\_BIN.md)
* [`AssetFactory_DDS`](../classes/m4m.framework.AssetFactory\_DDS.md)
* [`AssetFactory_ETC1`](../classes/m4m.framework.AssetFactory\_ETC1.md)
* [`AssetFactory_Font`](../classes/m4m.framework.AssetFactory\_Font.md)
* [`AssetFactory_GLFragmentShader`](../classes/m4m.framework.AssetFactory\_GLFragmentShader.md)
* [`AssetFactory_GLTF`](../classes/m4m.framework.AssetFactory\_GLTF.md)
* [`AssetFactory_GLVertexShader`](../classes/m4m.framework.AssetFactory\_GLVertexShader.md)
* [`AssetFactory_HDR`](../classes/m4m.framework.AssetFactory\_HDR.md)
* [`AssetFactory_Material`](../classes/m4m.framework.AssetFactory\_Material.md)
* [`AssetFactory_Mesh`](../classes/m4m.framework.AssetFactory\_Mesh.md)
* [`AssetFactory_PVR`](../classes/m4m.framework.AssetFactory\_PVR.md)
* [`AssetFactory_ParticleSystem`](../classes/m4m.framework.AssetFactory\_ParticleSystem.md)
* [`AssetFactory_PathAsset`](../classes/m4m.framework.AssetFactory\_PathAsset.md)
* [`AssetFactory_RAW`](../classes/m4m.framework.AssetFactory\_RAW.md)
* [`AssetFactory_Scene`](../classes/m4m.framework.AssetFactory\_Scene.md)
* [`AssetFactory_Shader`](../classes/m4m.framework.AssetFactory\_Shader.md)
* [`AssetFactory_TextAsset`](../classes/m4m.framework.AssetFactory\_TextAsset.md)
* [`AssetFactory_Texture`](../classes/m4m.framework.AssetFactory\_Texture.md)
* [`AssetFactory_TextureDesc`](../classes/m4m.framework.AssetFactory\_TextureDesc.md)
* [`AssetFactory_TrailRenderer`](../classes/m4m.framework.AssetFactory\_TrailRenderer.md)
* [`AssetFactory_cPrefab`](../classes/m4m.framework.AssetFactory\_cPrefab.md)
* [`AssetFactory_f14eff`](../classes/m4m.framework.AssetFactory\_f14eff.md)
* [`assetfactory_keyFrameAniClip`](../classes/m4m.framework.assetfactory\_keyFrameAniClip.md)

### Table of contents

#### Methods

* [load](m4m.framework.IAssetFactory.md#load)
* [loadByPack](m4m.framework.IAssetFactory.md#loadbypack)
* [needDownload](m4m.framework.IAssetFactory.md#needdownload)
* [newAsset](m4m.framework.IAssetFactory.md#newasset)
* [parse](m4m.framework.IAssetFactory.md#parse)

### Methods

#### load

▸ `Optional` **load**(`url`, `onstate`, `state`, `assetMgr`, `asset`, `call`): `void`

**Parameters**

| Name       | Type                                                                      |
| ---------- | ------------------------------------------------------------------------- |
| `url`      | `string`                                                                  |
| `onstate`  | (`state`: [`stateLoad`](../classes/m4m.framework.stateLoad.md)) => `void` |
| `state`    | [`stateLoad`](../classes/m4m.framework.stateLoad.md)                      |
| `assetMgr` | [`assetMgr`](../classes/m4m.framework.assetMgr.md)                        |
| `asset`    | [`IAsset`](m4m.framework.IAsset.md)                                       |
| `call`     | (`handle`: () => `void`) => `void`                                        |

**Returns**

`void`

**Defined in**

[framework/asset/factorys/assetfactory\_interface.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_interface.ts#L6)

***

#### loadByPack

▸ `Optional` **loadByPack**(`respack`, `url`, `onstate`, `state`, `assetMgr`, `asset`, `call`): `void`

**Parameters**

| Name       | Type                                                                      |
| ---------- | ------------------------------------------------------------------------- |
| `respack`  | `any`                                                                     |
| `url`      | `string`                                                                  |
| `onstate`  | (`state`: [`stateLoad`](../classes/m4m.framework.stateLoad.md)) => `void` |
| `state`    | [`stateLoad`](../classes/m4m.framework.stateLoad.md)                      |
| `assetMgr` | [`assetMgr`](../classes/m4m.framework.assetMgr.md)                        |
| `asset`    | [`IAsset`](m4m.framework.IAsset.md)                                       |
| `call`     | (`handle`: () => `void`) => `void`                                        |

**Returns**

`void`

**Defined in**

[framework/asset/factorys/assetfactory\_interface.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_interface.ts#L7)

***

#### needDownload

▸ `Optional` **needDownload**(`textJSON`): `string`

**Parameters**

| Name       | Type     |
| ---------- | -------- |
| `textJSON` | `string` |

**Returns**

`string`

**Defined in**

[framework/asset/factorys/assetfactory\_interface.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_interface.ts#L9)

***

#### newAsset

▸ `Optional` **newAsset**(`assetName?`): [`IAsset`](m4m.framework.IAsset.md)

**Parameters**

| Name         | Type     |
| ------------ | -------- |
| `assetName?` | `string` |

**Returns**

[`IAsset`](m4m.framework.IAsset.md)

**Defined in**

[framework/asset/factorys/assetfactory\_interface.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_interface.ts#L5)

***

#### parse

▸ **parse**(`assetMgr`, `bundle`, `name`, `data`, `dwguid?`): `void` | [`IAsset`](m4m.framework.IAsset.md) | `Promise`<[`IAsset`](m4m.framework.IAsset.md)>

**Parameters**

| Name       | Type                                                     |
| ---------- | -------------------------------------------------------- |
| `assetMgr` | [`assetMgr`](../classes/m4m.framework.assetMgr.md)       |
| `bundle`   | [`assetBundle`](../classes/m4m.framework.assetBundle.md) |
| `name`     | `string`                                                 |
| `data`     | `string` \| `ArrayBuffer`                                |
| `dwguid?`  | `number`                                                 |

**Returns**

`void` | [`IAsset`](m4m.framework.IAsset.md) | `Promise`<[`IAsset`](m4m.framework.IAsset.md)>

**Defined in**

[framework/asset/factorys/assetfactory\_interface.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory\_interface.ts#L8)
