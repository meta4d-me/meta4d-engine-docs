# m4m.framework.assetMgr

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / assetMgr

## Class: assetMgr

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).assetMgr

### Table of contents

#### Methods

* [\_loadImg](m4m.framework.assetMgr.md#\_loadimg)
* [download](m4m.framework.assetMgr.md#download)
* [getAssetBundle](m4m.framework.assetMgr.md#getassetbundle)
* [getAssetByName](m4m.framework.assetMgr.md#getassetbyname)
* [getAssetUrl](m4m.framework.assetMgr.md#getasseturl)
* [getDefLineRendererMat](m4m.framework.assetMgr.md#getdeflinerenderermat)
* [getDefParticleMat](m4m.framework.assetMgr.md#getdefparticlemat)
* [getDefaultCubeTexture](m4m.framework.assetMgr.md#getdefaultcubetexture)
* [getDefaultMesh](m4m.framework.assetMgr.md#getdefaultmesh)
* [getDefaultSprite](m4m.framework.assetMgr.md#getdefaultsprite)
* [getDefaultTexture](m4m.framework.assetMgr.md#getdefaulttexture)
* [getMaterial](m4m.framework.assetMgr.md#getmaterial)
* [getShader](m4m.framework.assetMgr.md#getshader)
* [initDefAsset](m4m.framework.assetMgr.md#initdefasset)
* [load](m4m.framework.assetMgr.md#load)
* [loadCompressBundle](m4m.framework.assetMgr.md#loadcompressbundle)
* [loadImg](m4m.framework.assetMgr.md#loadimg)
* [loadImmediate](m4m.framework.assetMgr.md#loadimmediate)
* [loadScene](m4m.framework.assetMgr.md#loadscene)
* [parseRes](m4m.framework.assetMgr.md#parseres)
* [releaseUnuseAsset](m4m.framework.assetMgr.md#releaseunuseasset)
* [savePrefab](m4m.framework.assetMgr.md#saveprefab)
* [setAssetUrl](m4m.framework.assetMgr.md#setasseturl)
* [unload](m4m.framework.assetMgr.md#unload)
* [unuse](m4m.framework.assetMgr.md#unuse)
* [use](m4m.framework.assetMgr.md#use)
* [correctFileName](m4m.framework.assetMgr.md#correctfilename)
* [correctTxtFileName](m4m.framework.assetMgr.md#correcttxtfilename)
* [initGuidList](m4m.framework.assetMgr.md#initguidlist)
* [setLoading](m4m.framework.assetMgr.md#setloading)
* [setStateError](m4m.framework.assetMgr.md#setstateerror)

#### Properties

* [app](m4m.framework.assetMgr.md#app)
* [guid\_bundles](m4m.framework.assetMgr.md#guid\_bundles)
* [kurl\_bundles](m4m.framework.assetMgr.md#kurl\_bundles)
* [mapDefaultCubeTexture](m4m.framework.assetMgr.md#mapdefaultcubetexture)
* [mapDefaultMesh](m4m.framework.assetMgr.md#mapdefaultmesh)
* [mapDefaultSprite](m4m.framework.assetMgr.md#mapdefaultsprite)
* [mapDefaultTexture](m4m.framework.assetMgr.md#mapdefaulttexture)
* [mapMaterial](m4m.framework.assetMgr.md#mapmaterial)
* [mapRes](m4m.framework.assetMgr.md#mapres)
* [mapShader](m4m.framework.assetMgr.md#mapshader)
* [maploaded](m4m.framework.assetMgr.md#maploaded)
* [name\_bundles](m4m.framework.assetMgr.md#name\_bundles)
* [shaderPool](m4m.framework.assetMgr.md#shaderpool)
* [webgl](m4m.framework.assetMgr.md#webgl)
* [Instance](m4m.framework.assetMgr.md#instance)
* [atonceParse](m4m.framework.assetMgr.md#atonceparse)
* [cdnRoot](m4m.framework.assetMgr.md#cdnroot)
* [guidlistURL](m4m.framework.assetMgr.md#guidlisturl)
* [mapBundleNamed](m4m.framework.assetMgr.md#mapbundlenamed)
* [mapGuid](m4m.framework.assetMgr.md#mapguid)
* [mapImage](m4m.framework.assetMgr.md#mapimage)
* [mapLoading](m4m.framework.assetMgr.md#maploading)
* [mapNamed](m4m.framework.assetMgr.md#mapnamed)
* [noparseBundle](m4m.framework.assetMgr.md#noparsebundle)
* [onGuidInit](m4m.framework.assetMgr.md#onguidinit)
* [openGuid](m4m.framework.assetMgr.md#openguid)
* [txt](m4m.framework.assetMgr.md#txt)
* [urlmapGuid](m4m.framework.assetMgr.md#urlmapguid)
* [useBinJs](m4m.framework.assetMgr.md#usebinjs)

#### Constructors

* [constructor](m4m.framework.assetMgr.md#constructor)

### Methods

#### \_loadImg

▸ `Protected` **\_loadImg**(`url`, `cb`): `void`

**Parameters**

| Name  | Type                                    |
| ----- | --------------------------------------- |
| `url` | `string`                                |
| `cb`  | (`img`: `any`, `err?`: `any`) => `void` |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:392](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L392)

***

#### download

▸ **download**(`guid`, `url`, `type`, `finish`, `errcb?`, `bundle?`): `void`

**Parameters**

| Name      | Type                                                       |
| --------- | ---------------------------------------------------------- |
| `guid`    | `number`                                                   |
| `url`     | `string`                                                   |
| `type`    | [`AssetTypeEnum`](../enums/m4m.framework.AssetTypeEnum.md) |
| `finish`  | () => `void`                                               |
| `errcb?`  | (`err`: `Error`) => `void`                                 |
| `bundle?` | [`assetBundle`](m4m.framework.assetBundle.md)              |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:306](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L306)

***

#### getAssetBundle

▸ **getAssetBundle**(`url`): [`assetBundle`](m4m.framework.assetBundle.md)

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `url` | `string` |

**Returns**

[`assetBundle`](m4m.framework.assetBundle.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:646](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L646)

***

#### getAssetByName

▸ **getAssetByName**<`T`>(`name`, `bundlename?`): `T`

**Type parameters**

| Name | Type                                                      |
| ---- | --------------------------------------------------------- |
| `T`  | extends [`IAsset`](../interfaces/m4m.framework.IAsset.md) |

**Parameters**

| Name          | Type     |
| ------------- | -------- |
| `name`        | `string` |
| `bundlename?` | `string` |

**Returns**

`T`

**Defined in**

[framework/asset/a/nassetmgr.ts:519](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L519)

***

#### getAssetUrl

▸ **getAssetUrl**(`asset`): `string`

**Parameters**

| Name    | Type                                              |
| ------- | ------------------------------------------------- |
| `asset` | [`IAsset`](../interfaces/m4m.framework.IAsset.md) |

**Returns**

`string`

**Defined in**

[framework/asset/a/nassetmgr.ts:630](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L630)

***

#### getDefLineRendererMat

▸ **getDefLineRendererMat**(): [`material`](m4m.framework.material.md)

**Returns**

[`material`](m4m.framework.material.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:593](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L593)

***

#### getDefParticleMat

▸ **getDefParticleMat**(): [`material`](m4m.framework.material.md)

**Returns**

[`material`](m4m.framework.material.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:608](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L608)

***

#### getDefaultCubeTexture

▸ **getDefaultCubeTexture**(`name`): [`texture`](m4m.framework.texture.md)

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

[`texture`](m4m.framework.texture.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:542](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L542)

***

#### getDefaultMesh

▸ **getDefaultMesh**(`name`): [`mesh`](m4m.framework.mesh.md)

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

[`mesh`](m4m.framework.mesh.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:540](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L540)

***

#### getDefaultSprite

▸ **getDefaultSprite**(`name`): [`sprite`](m4m.framework.sprite.md)

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

[`sprite`](m4m.framework.sprite.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:543](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L543)

***

#### getDefaultTexture

▸ **getDefaultTexture**(`name`): [`texture`](m4m.framework.texture.md)

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

[`texture`](m4m.framework.texture.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:541](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L541)

***

#### getMaterial

▸ **getMaterial**(`name`): [`material`](m4m.framework.material.md)

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

[`material`](m4m.framework.material.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:544](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L544)

***

#### getShader

▸ **getShader**(`name`): [`shader`](m4m.framework.shader.md)

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

[`shader`](m4m.framework.shader.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:588](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L588)

***

#### initDefAsset

▸ **initDefAsset**(): `void`

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:653](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L653)

***

#### load

▸ **load**(`url`, `type?`, `onstate?`, `downloadFinish?`): `void`

**Parameters**

| Name             | Type                                                       | Default value        |
| ---------------- | ---------------------------------------------------------- | -------------------- |
| `url`            | `string`                                                   | `undefined`          |
| `type`           | [`AssetTypeEnum`](../enums/m4m.framework.AssetTypeEnum.md) | `AssetTypeEnum.Auto` |
| `onstate`        | `loadCallback`                                             | `null`               |
| `downloadFinish` | () => `void`                                               | `null`               |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:204](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L204)

***

#### loadCompressBundle

▸ **loadCompressBundle**(`url`, `a?`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `url` | `string` |
| `a?`  | `any`    |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:639](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L639)

***

#### loadImg

▸ **loadImg**(`guid`, `url`, `cb`, `bundle?`): `void`

**Parameters**

| Name      | Type                                          |
| --------- | --------------------------------------------- |
| `guid`    | `number`                                      |
| `url`     | `string`                                      |
| `cb`      | (`img`: `any`, `err?`: `any`) => `void`       |
| `bundle?` | [`assetBundle`](m4m.framework.assetBundle.md) |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:361](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L361)

***

#### loadImmediate

▸ **loadImmediate**(`url`): `any`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `url` | `string` |

**Returns**

`any`

**Defined in**

[framework/asset/a/nassetmgr.ts:642](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L642)

***

#### loadScene

▸ **loadScene**(`sceneName`, `onComplete`): `void`

**Parameters**

| Name         | Type                                                                    |
| ------------ | ----------------------------------------------------------------------- |
| `sceneName`  | `string`                                                                |
| `onComplete` | (`firstChilds`: [`transform`](m4m.framework.transform.md)\[]) => `void` |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:661](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L661)

***

#### parseRes

▸ **parseRes**(`asset`, `bundle?`): `Promise`<[`IAsset`](../interfaces/m4m.framework.IAsset.md)>

**Parameters**

| Name            | Type                                          |
| --------------- | --------------------------------------------- |
| `asset`         | `Object`                                      |
| `asset.dwguid?` | `number`                                      |
| `asset.guid`    | `number`                                      |
| `asset.name`    | `string`                                      |
| `asset.type`    | `number`                                      |
| `bundle?`       | [`assetBundle`](m4m.framework.assetBundle.md) |

**Returns**

`Promise`<[`IAsset`](../interfaces/m4m.framework.IAsset.md)>

**Defined in**

[framework/asset/a/nassetmgr.ts:452](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L452)

***

#### releaseUnuseAsset

▸ **releaseUnuseAsset**(): `void`

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:650](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L650)

***

#### savePrefab

▸ **savePrefab**(`trans`, `prefabName`, `fun`): `void`

**Parameters**

| Name         | Type                                                                                                          |
| ------------ | ------------------------------------------------------------------------------------------------------------- |
| `trans`      | [`transform`](m4m.framework.transform.md)                                                                     |
| `prefabName` | `string`                                                                                                      |
| `fun`        | (`data`: [`SaveInfo`](m4m.framework.SaveInfo.md), `resourses?`: `string`\[], `contents?`: `any`\[]) => `void` |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:636](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L636)

***

#### setAssetUrl

▸ **setAssetUrl**(`asset`, `url`): `void`

**Parameters**

| Name    | Type                                              |
| ------- | ------------------------------------------------- |
| `asset` | [`IAsset`](../interfaces/m4m.framework.IAsset.md) |
| `url`   | `string`                                          |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:626](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L626)

***

#### unload

▸ **unload**(`url`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `url` | `string` |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:697](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L697)

***

#### unuse

▸ **unuse**(`asset`, `disposeNow?`): `void`

**Parameters**

| Name         | Type                                              | Default value |
| ------------ | ------------------------------------------------- | ------------- |
| `asset`      | [`IAsset`](../interfaces/m4m.framework.IAsset.md) | `undefined`   |
| `disposeNow` | `boolean`                                         | `true`        |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:439](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L439)

***

#### use

▸ **use**(`asset`): `void`

**Parameters**

| Name    | Type                                              |
| ------- | ------------------------------------------------- |
| `asset` | [`IAsset`](../interfaces/m4m.framework.IAsset.md) |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:406](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L406)

***

#### correctFileName

▸ `Static` **correctFileName**(`name`): `string`

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

`string`

**Defined in**

[framework/asset/a/nassetmgr.ts:560](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L560)

***

#### correctTxtFileName

▸ `Static` **correctTxtFileName**(`name`): `string`

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `name` | `string` |

**Returns**

`string`

**Defined in**

[framework/asset/a/nassetmgr.ts:574](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L574)

***

#### initGuidList

▸ `Static` **initGuidList**(): `void`

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:184](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L184)

***

#### setLoading

▸ `Static` **setLoading**(`guid`, `data`): `void`

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `guid` | `number` |
| `data` | `any`    |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:196](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L196)

***

#### setStateError

▸ `Static` **setStateError**(`state`, `onstate`, `err`): `void`

**Parameters**

| Name      | Type                                                            |
| --------- | --------------------------------------------------------------- |
| `state`   | [`stateLoad`](m4m.framework.stateLoad.md)                       |
| `onstate` | (`state?`: [`stateLoad`](m4m.framework.stateLoad.md)) => `void` |
| `err`     | `Error`                                                         |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:300](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L300)

### Properties

#### app

• **app**: [`application`](m4m.framework.application.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:549](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L549)

***

#### guid\_bundles

• **guid\_bundles**: `Object` = `{}`

**Index signature**

▪ \[key: `string`]: [`assetBundle`](m4m.framework.assetBundle.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:177](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L177)

***

#### kurl\_bundles

• **kurl\_bundles**: `Object` = `{}`

**Index signature**

▪ \[key: `string`]: [`assetBundle`](m4m.framework.assetBundle.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:176](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L176)

***

#### mapDefaultCubeTexture

• **mapDefaultCubeTexture**: `Object` = `{}`

**Index signature**

▪ \[id: `string`]: [`texture`](m4m.framework.texture.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:537](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L537)

***

#### mapDefaultMesh

• **mapDefaultMesh**: `Object` = `{}`

**Index signature**

▪ \[id: `string`]: [`mesh`](m4m.framework.mesh.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:535](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L535)

***

#### mapDefaultSprite

• **mapDefaultSprite**: `Object` = `{}`

**Index signature**

▪ \[id: `string`]: [`sprite`](m4m.framework.sprite.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:538](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L538)

***

#### mapDefaultTexture

• **mapDefaultTexture**: `Object` = `{}`

**Index signature**

▪ \[id: `string`]: [`texture`](m4m.framework.texture.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:536](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L536)

***

#### mapMaterial

• **mapMaterial**: `Object` = `{}`

**Index signature**

▪ \[id: `string`]: [`material`](m4m.framework.material.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:539](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L539)

***

#### mapRes

• **mapRes**: `Object` = `{}`

**Index signature**

▪ \[id: `number`]: `any`

**Defined in**

[framework/asset/a/nassetmgr.ts:552](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L552)

***

#### mapShader

• **mapShader**: `Object` = `{}`

**Index signature**

▪ \[id: `string`]: [`shader`](m4m.framework.shader.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:179](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L179)

***

#### maploaded

• **maploaded**: `Object`

**Index signature**

▪ \[url: `string`]: [`IAsset`](../interfaces/m4m.framework.IAsset.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:634](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L634)

***

#### name\_bundles

• **name\_bundles**: `Object` = `{}`

**Index signature**

▪ \[key: `string`]: [`assetBundle`](m4m.framework.assetBundle.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:175](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L175)

***

#### shaderPool

• **shaderPool**: `shaderPool`

**Defined in**

[framework/asset/a/nassetmgr.ts:550](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L550)

***

#### webgl

• **webgl**: `WebGLRenderingContext`

**Defined in**

[framework/asset/a/nassetmgr.ts:551](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L551)

***

#### Instance

▪ `Static` **Instance**: [`assetMgr`](m4m.framework.assetMgr.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:163](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L163)

***

#### atonceParse

▪ `Static` **atonceParse**: `boolean` = `true`

**Defined in**

[framework/asset/a/nassetmgr.ts:173](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L173)

***

#### cdnRoot

▪ `Static` **cdnRoot**: `string`

**Defined in**

[framework/asset/a/nassetmgr.ts:160](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L160)

***

#### guidlistURL

▪ `Static` **guidlistURL**: `string`

**Defined in**

[framework/asset/a/nassetmgr.ts:161](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L161)

***

#### mapBundleNamed

▪ `Static` **mapBundleNamed**: `Object` = `{}`

**Index signature**

▪ \[key: `number`]: { `[name: string]`: [`assetRef`](m4m.framework.assetRef.md); }

**Defined in**

[framework/asset/a/nassetmgr.ts:169](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L169)

***

#### mapGuid

▪ `Static` **mapGuid**: `Object` = `{}`

**Index signature**

▪ \[key: `number`]: [`assetRef`](m4m.framework.assetRef.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:166](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L166)

***

#### mapImage

▪ `Static` **mapImage**: `Object` = `{}`

**Index signature**

▪ \[key: `number`]: `HTMLImageElement` | `ArrayBuffer`

**Defined in**

[framework/asset/a/nassetmgr.ts:167](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L167)

***

#### mapLoading

▪ `Static` **mapLoading**: `Object` = `{}`

**Index signature**

▪ \[key: `number`]: { `cbQueue?`: `loadCallback`\[] ; `data?`: `any` ; `readyok`: `boolean` ; `subRes?`: `number`\[] ; `url?`: `string` }

**Defined in**

[framework/asset/a/nassetmgr.ts:165](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L165)

***

#### mapNamed

▪ `Static` **mapNamed**: `Object` = `{}`

**Index signature**

▪ \[key: `string`]: [`IAsset`](../interfaces/m4m.framework.IAsset.md)

**Defined in**

[framework/asset/a/nassetmgr.ts:168](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L168)

***

#### noparseBundle

▪ `Static` **noparseBundle**: [`assetBundle`](m4m.framework.assetBundle.md)\[] = `[]`

**Defined in**

[framework/asset/a/nassetmgr.ts:171](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L171)

***

#### onGuidInit

▪ `Static` **onGuidInit**: () => `void`

**Type declaration**

▸ (): `void`

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetmgr.ts:162](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L162)

***

#### openGuid

▪ `Static` **openGuid**: `boolean` = `true`

**Defined in**

[framework/asset/a/nassetmgr.ts:174](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L174)

***

#### txt

▪ `Static` **txt**: `string` = `".txt"`

**Defined in**

[framework/asset/a/nassetmgr.ts:547](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L547)

***

#### urlmapGuid

▪ `Static` **urlmapGuid**: `Object` = `{}`

**Index signature**

▪ \[key: `string`]: `number`

**Defined in**

[framework/asset/a/nassetmgr.ts:159](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L159)

***

#### useBinJs

▪ `Static` **useBinJs**: `boolean` = `false`

**Defined in**

[framework/asset/a/nassetmgr.ts:546](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L546)

### Constructors

#### constructor

• **new assetMgr**(`app`)

**Parameters**

| Name  | Type                                          |
| ----- | --------------------------------------------- |
| `app` | [`application`](m4m.framework.application.md) |

**Defined in**

[framework/asset/a/nassetmgr.ts:553](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetmgr.ts#L553)
