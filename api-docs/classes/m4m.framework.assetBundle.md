# m4m.framework.assetBundle

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / assetBundle

## Class: assetBundle

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).assetBundle

### Table of contents

#### Properties

* [baseUrl](m4m.framework.assetBundle.md#baseurl)
* [dw\_fileCount](m4m.framework.assetBundle.md#dw\_filecount)
* [dw\_imgCount](m4m.framework.assetBundle.md#dw\_imgcount)
* [files](m4m.framework.assetBundle.md#files)
* [guid](m4m.framework.assetBundle.md#guid)
* [isunload](m4m.framework.assetBundle.md#isunload)
* [keyUrl](m4m.framework.assetBundle.md#keyurl)
* [name](m4m.framework.assetBundle.md#name)
* [onDownloadFinish](m4m.framework.assetBundle.md#ondownloadfinish)
* [onReady](m4m.framework.assetBundle.md#onready)
* [parseReject](m4m.framework.assetBundle.md#parsereject)
* [parseResolve](m4m.framework.assetBundle.md#parseresolve)
* [pkgs](m4m.framework.assetBundle.md#pkgs)
* [pkgsGuid](m4m.framework.assetBundle.md#pkgsguid)
* [ready](m4m.framework.assetBundle.md#ready)
* [texs](m4m.framework.assetBundle.md#texs)
* [url](m4m.framework.assetBundle.md#url)
* [idNext](m4m.framework.assetBundle.md#idnext)
* [needClearLoadedRes](m4m.framework.assetBundle.md#needclearloadedres)
* [reTryTest](m4m.framework.assetBundle.md#retrytest)

#### Constructors

* [constructor](m4m.framework.assetBundle.md#constructor)

#### Methods

* [fail](m4m.framework.assetBundle.md#fail)
* [parseBundle](m4m.framework.assetBundle.md#parsebundle)
* [parseFile](m4m.framework.assetBundle.md#parsefile)
* [unload](m4m.framework.assetBundle.md#unload)
* [buildGuid](m4m.framework.assetBundle.md#buildguid)

### Properties

#### baseUrl

• **baseUrl**: `string`

**Defined in**

[framework/asset/a/nassetBundle.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L34)

***

#### dw\_fileCount

• **dw\_fileCount**: `number`

**Defined in**

[framework/asset/a/nassetBundle.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L44)

***

#### dw\_imgCount

• **dw\_imgCount**: `number`

**Defined in**

[framework/asset/a/nassetBundle.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L42)

***

#### files

• **files**: `fileIdMap` = `{}`

**Defined in**

[framework/asset/a/nassetBundle.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L24)

***

#### guid

• **guid**: `number`

**Defined in**

[framework/asset/a/nassetBundle.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L38)

***

#### isunload

• **isunload**: `boolean` = `false`

**Defined in**

[framework/asset/a/nassetBundle.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L49)

***

#### keyUrl

• **keyUrl**: `string`

**Defined in**

[framework/asset/a/nassetBundle.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L36)

***

#### name

• **name**: `string`

**Defined in**

[framework/asset/a/nassetBundle.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L40)

***

#### onDownloadFinish

• **onDownloadFinish**: () => `void`

**Type declaration**

▸ (): `void`

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetBundle.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L47)

***

#### onReady

• **onReady**: () => `void`

**Type declaration**

▸ (): `void`

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetBundle.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L46)

***

#### parseReject

• **parseReject**: (`o`: `Error`) => `void`

**Type declaration**

▸ (`o`): `void`

**Parameters**

| Name | Type    |
| ---- | ------- |
| `o`  | `Error` |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetBundle.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L52)

***

#### parseResolve

• **parseResolve**: (`o?`: `any`) => `void`

**Type declaration**

▸ (`o?`): `void`

**Parameters**

| Name | Type  |
| ---- | ----- |
| `o?` | `any` |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetBundle.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L51)

***

#### pkgs

• **pkgs**: `string`\[] = `[]`

**Defined in**

[framework/asset/a/nassetBundle.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L28)

***

#### pkgsGuid

• **pkgsGuid**: `number`\[] = `[]`

**Defined in**

[framework/asset/a/nassetBundle.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L30)

***

#### ready

• **ready**: `boolean`

**Defined in**

[framework/asset/a/nassetBundle.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L48)

***

#### texs

• **texs**: `fileIdMap` = `{}`

**Defined in**

[framework/asset/a/nassetBundle.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L26)

***

#### url

• **url**: `string`

**Defined in**

[framework/asset/a/nassetBundle.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L32)

***

#### idNext

▪ `Static` **idNext**: `number` = `-1`

**Defined in**

[framework/asset/a/nassetBundle.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L6)

***

#### needClearLoadedRes

▪ `Static` **needClearLoadedRes**: `boolean` = `false`

解析后清理 加载缓存资源数据

**Defined in**

[framework/asset/a/nassetBundle.ts:5](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L5)

***

#### reTryTest

▪ `Static` **reTryTest**: `Object` = `{}`

**Defined in**

[framework/asset/a/nassetBundle.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L53)

### Constructors

#### constructor

• **new assetBundle**(`url`, `assetmgr`, `guid?`)

**Parameters**

| Name       | Type                                    |
| ---------- | --------------------------------------- |
| `url`      | `string`                                |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `guid?`    | `number`                                |

**Defined in**

[framework/asset/a/nassetBundle.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L54)

### Methods

#### fail

▸ **fail**(`error`): `void`

**Parameters**

| Name    | Type    |
| ------- | ------- |
| `error` | `Error` |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetBundle.ts:381](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L381)

***

#### parseBundle

▸ **parseBundle**(`data`): `Promise`<`unknown`>

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `data` | `string` |

**Returns**

`Promise`<`unknown`>

**Defined in**

[framework/asset/a/nassetBundle.ts:94](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L94)

***

#### parseFile

▸ **parseFile**(): `Promise`<`void`>

**Returns**

`Promise`<`void`>

**Defined in**

[framework/asset/a/nassetBundle.ts:279](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L279)

***

#### unload

▸ **unload**(`disposeNow?`): `void`

**Parameters**

| Name         | Type      | Default value |
| ------------ | --------- | ------------- |
| `disposeNow` | `boolean` | `false`       |

**Returns**

`void`

**Defined in**

[framework/asset/a/nassetBundle.ts:357](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L357)

***

#### buildGuid

▸ `Static` **buildGuid**(): `number`

**Returns**

`number`

**Defined in**

[framework/asset/a/nassetBundle.ts:61](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/nassetBundle.ts#L61)
