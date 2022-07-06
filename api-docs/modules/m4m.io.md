# m4m.io

[@meta4d/engine](../) / [Exports](./) / [m4m](m4m.md) / io

## Namespace: io

[m4m](m4m.md).io

### Table of contents

#### Functions

* [JSONParse](m4m.io.md#jsonparse)
* [cloneObj](m4m.io.md#cloneobj)
* [loadArrayBuffer](m4m.io.md#loadarraybuffer)
* [loadBlob](m4m.io.md#loadblob)
* [loadImg](m4m.io.md#loadimg)
* [loadJSON](m4m.io.md#loadjson)
* [loadText](m4m.io.md#loadtext)
* [ndeSerialize](m4m.io.md#ndeserialize)
* [stringToBlob](m4m.io.md#stringtoblob)
* [stringToUtf8Array](m4m.io.md#stringtoutf8array)
* [xhrLoad](m4m.io.md#xhrload)

#### Enumerations

* [SaveAssetType](../enums/m4m.io.SaveAssetType.md)

#### Classes

* [binTool](../classes/m4m.io.binTool.md)
* [binWriter](../classes/m4m.io.binWriter.md)
* [converter](../classes/m4m.io.converter.md)

### Functions

#### JSONParse

▸ **JSONParse**(`text`): `Promise`<`any`>

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `text` | `string` |

**Returns**

`Promise`<`any`>

**Defined in**

[io/loadtool.ts:142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/loadtool.ts#L142)

***

#### cloneObj

▸ **cloneObj**(`instanceObj`, `clonedObj?`): `any`

**`language`** zh\_CN

**`classdesc`** 对可序列化实例的克隆

**`version`** m4m 1.0

**Parameters**

| Name          | Type  | Default value | Description |
| ------------- | ----- | ------------- | ----------- |
| `instanceObj` | `any` | `undefined`   | 被克隆实例       |
| `clonedObj`   | `any` | `undefined`   | 克隆实例引用      |

**Returns**

`any`

**Defined in**

[framework/io/clone.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/clone.ts#L15)

***

#### loadArrayBuffer

▸ **loadArrayBuffer**(`url`, `fun`, `onprocess?`): `void`

**`language`** zh\_CN

**`classdesc`** 加载arraybuffer资源

**`version`** m4m 1.0

**Parameters**

| Name        | Type                                                                         | Default value | Description |
| ----------- | ---------------------------------------------------------------------------- | ------------- | ----------- |
| `url`       | `string`                                                                     | `undefined`   | 加载路径        |
| `fun`       | (`_bin`: `ArrayBuffer`, `_err`: `Error`, `isloadFail?`: `boolean`) => `void` | `undefined`   | 加载结果回调函数    |
| `onprocess` | (`curLength`: `number`, `totalLength`: `number`) => `void`                   | `null`        | 加载进度        |

**Returns**

`void`

**Defined in**

[io/loadtool.ts:248](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/loadtool.ts#L248)

***

#### loadBlob

▸ **loadBlob**(`url`, `fun`, `onprocess?`): `void`

**`language`** zh\_CN

**`classdesc`** 加载二进制资源

**`version`** m4m 1.0

**Parameters**

| Name        | Type                                                                   | Default value | Description |
| ----------- | ---------------------------------------------------------------------- | ------------- | ----------- |
| `url`       | `string`                                                               | `undefined`   | 加载路径        |
| `fun`       | (`_blob`: `Blob`, `_err`: `Error`, `isloadFail?`: `boolean`) => `void` | `undefined`   | 加载结果回调函数    |
| `onprocess` | (`curLength`: `number`, `totalLength`: `number`) => `void`             | `null`        | 加载进度        |

**Returns**

`void`

**Defined in**

[io/loadtool.ts:271](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/loadtool.ts#L271)

***

#### loadImg

▸ **loadImg**(`url`, `fun`, `onprocess?`): `void`

**`language`** zh\_CN

**`classdesc`** 加载图片资源

**`version`** m4m 1.0

**Parameters**

| Name        | Type                                                                             | Default value | Description |
| ----------- | -------------------------------------------------------------------------------- | ------------- | ----------- |
| `url`       | `string`                                                                         | `undefined`   | 加载路径        |
| `fun`       | (`_tex`: `HTMLImageElement`, `_err?`: `Error`, `loadFail?`: `boolean`) => `void` | `undefined`   | 加载结果回调函数    |
| `onprocess` | (`curLength`: `number`, `totalLength`: `number`) => `void`                       | `null`        | -           |

**Returns**

`void`

**Defined in**

[io/loadtool.ts:289](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/loadtool.ts#L289)

***

#### loadJSON

▸ **loadJSON**(`url`, `fun`, `onprocess?`): `Promise`<`unknown`>

**Parameters**

| Name        | Type                                                                 | Default value |
| ----------- | -------------------------------------------------------------------- | ------------- |
| `url`       | `string`                                                             | `undefined`   |
| `fun`       | (`_txt`: `any`, `_err`: `Error`, `isloadFail?`: `boolean`) => `void` | `undefined`   |
| `onprocess` | (`curLength`: `number`, `totalLength`: `number`) => `void`           | `null`        |

**Returns**

`Promise`<`unknown`>

**Defined in**

[io/loadtool.ts:157](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/loadtool.ts#L157)

***

#### loadText

▸ **loadText**(`url`, `fun`, `onprocess?`): `void`

**`language`** zh\_CN

**`classdesc`** 加载text资源

**`version`** m4m 1.0

**Parameters**

| Name        | Type                                                                    | Default value | Description |
| ----------- | ----------------------------------------------------------------------- | ------------- | ----------- |
| `url`       | `string`                                                                | `undefined`   | 加载路径        |
| `fun`       | (`_txt`: `string`, `_err`: `Error`, `isloadFail?`: `boolean`) => `void` | `undefined`   | 加载结果回调函数    |
| `onprocess` | (`curLength`: `number`, `totalLength`: `number`) => `void`              | `null`        | 加载进度        |

**Returns**

`void`

**Defined in**

[io/loadtool.ts:106](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/loadtool.ts#L106)

***

#### ndeSerialize

▸ **ndeSerialize**<`T`>(`json`, `assetbundle`, `useAsset?`): `T`

**Type parameters**

| Name | Type                                                                                                                     |
| ---- | ------------------------------------------------------------------------------------------------------------------------ |
| `T`  | extends [`transform`](../classes/m4m.framework.transform.md) \| [`transform2D`](../classes/m4m.framework.transform2D.md) |

**Parameters**

| Name          | Type      |
| ------------- | --------- |
| `json`        | `any`     |
| `assetbundle` | `string`  |
| `useAsset?`   | `boolean` |

**Returns**

`T`

**Defined in**

[framework/io/nserialize.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/nserialize.ts#L6)

***

#### stringToBlob

▸ **stringToBlob**(`content`): `Blob`

**`language`** zh\_CN

**`classdesc`** string转换为blob

**`version`** m4m 1.0

**Parameters**

| Name      | Type     |
| --------- | -------- |
| `content` | `string` |

**Returns**

`Blob`

**Defined in**

[framework/io/iointerface.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/iointerface.ts#L17)

***

#### stringToUtf8Array

▸ **stringToUtf8Array**(`str`): `number`\[]

**`language`** zh\_CN

**`classdesc`** string转换为utf8数组

**`version`** m4m 1.0

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `str` | `string` |

**Returns**

`number`\[]

**Defined in**

[framework/io/iointerface.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/iointerface.ts#L31)

***

#### xhrLoad

▸ **xhrLoad**(`url`, `fun`, `onprocess?`, `responseType`, `loadedFun`): `void`

**Parameters**

| Name           | Type                                                                        | Default value | Description |
| -------------- | --------------------------------------------------------------------------- | ------------- | ----------- |
| `url`          | `string`                                                                    | `undefined`   | 加载路径        |
| `fun`          | (`ContentData`: `any`, `_err`: `Error`, `isloadFail?`: `boolean`) => `void` | `undefined`   | 加载结果回调函数    |
| `onprocess`    | (`curLength`: `number`, `totalLength`: `number`) => `void`                  | `null`        | 加载进度        |
| `responseType` | `XMLHttpRequestResponseType`                                                | `undefined`   | -           |
| `loadedFun`    | (`req`: `XMLHttpRequest`) => `void`                                         | `undefined`   | 正常加载完成后回调   |

**Returns**

`void`

**Defined in**

[io/loadtool.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/loadtool.ts#L18)
