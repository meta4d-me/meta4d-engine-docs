[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AssetFactoryTools

# Class: AssetFactoryTools

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AssetFactoryTools

## Table of contents

### Constructors

- [constructor](m4m.framework.AssetFactoryTools.md#constructor)

### Methods

- [catchError](m4m.framework.AssetFactoryTools.md#catcherror)
- [onProgress](m4m.framework.AssetFactoryTools.md#onprogress)
- [onRefProgress](m4m.framework.AssetFactoryTools.md#onrefprogress)
- [useAsset](m4m.framework.AssetFactoryTools.md#useasset)

## Constructors

### constructor

• **new AssetFactoryTools**()

## Methods

### catchError

▸ `Static` **catchError**(`err`, `onstate`, `state`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `Error` |
| `onstate` | (`state`: [`stateLoad`](m4m.framework.stateLoad.md)) => `void` |
| `state` | [`stateLoad`](m4m.framework.stateLoad.md) |

#### Returns

`boolean`

#### Defined in

[framework/asset/factorys/assetfactory_interface.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory_interface.ts#L14)

___

### onProgress

▸ `Static` **onProgress**(`loadedLength`, `totalLength`, `onstate`, `state`, `filename`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `loadedLength` | `number` |
| `totalLength` | `number` |
| `onstate` | (`state`: [`stateLoad`](m4m.framework.stateLoad.md)) => `void` |
| `state` | [`stateLoad`](m4m.framework.stateLoad.md) |
| `filename` | `string` |

#### Returns

`void`

#### Defined in

[framework/asset/factorys/assetfactory_interface.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory_interface.ts#L39)

___

### onRefProgress

▸ `Static` **onRefProgress**(`loadedLength`, `totalLength`, `onstate`, `state`, `filename`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `loadedLength` | `number` |
| `totalLength` | `number` |
| `onstate` | (`state`: [`stateLoad`](m4m.framework.stateLoad.md)) => `void` |
| `state` | [`stateLoad`](m4m.framework.stateLoad.md) |
| `filename` | `string` |

#### Returns

`void`

#### Defined in

[framework/asset/factorys/assetfactory_interface.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory_interface.ts#L47)

___

### useAsset

▸ `Static` **useAsset**(`assetMgr`, `onstate`, `state`, `asset`, `url`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `assetMgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `onstate` | (`state`: [`stateLoad`](m4m.framework.stateLoad.md)) => `void` |
| `state` | [`stateLoad`](m4m.framework.stateLoad.md) |
| `asset` | [`IAsset`](../interfaces/m4m.framework.IAsset.md) |
| `url` | `string` |

#### Returns

`void`

#### Defined in

[framework/asset/factorys/assetfactory_interface.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/factorys/assetfactory_interface.ts#L26)
