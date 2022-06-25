[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / prefab

# Class: prefab

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).prefab

**`language`** zh_CN

**`classdesc`**
预设资源

**`version`** m4m 1.0

## Implements

- [`IAsset`](../interfaces/m4m.framework.IAsset.md)

## Table of contents

### Methods

- [Parse](m4m.framework.prefab.md#parse)
- [apply](m4m.framework.prefab.md#apply)
- [cParse](m4m.framework.prefab.md#cparse)
- [caclByteLength](m4m.framework.prefab.md#caclbytelength)
- [dispose](m4m.framework.prefab.md#dispose)
- [getCloneTrans](m4m.framework.prefab.md#getclonetrans)
- [getCloneTrans2D](m4m.framework.prefab.md#getclonetrans2d)
- [getGUID](m4m.framework.prefab.md#getguid)
- [getName](m4m.framework.prefab.md#getname)
- [unuse](m4m.framework.prefab.md#unuse)
- [use](m4m.framework.prefab.md#use)

### Properties

- [assetbundle](m4m.framework.prefab.md#assetbundle)
- [defaultAsset](m4m.framework.prefab.md#defaultasset)
- [isCab](m4m.framework.prefab.md#iscab)
- [ClassName](m4m.framework.prefab.md#classname)

### Constructors

- [constructor](m4m.framework.prefab.md#constructor)

## Methods

### Parse

▸ **Parse**(`jsonStr`, `assetmgr`): `Promise`<`unknown`\>

**`language`** zh_CN

**`classdesc`**
解析资源

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `jsonStr` | `string` | json数据 |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) | 资源管理实例 |

#### Returns

`Promise`<`unknown`\>

#### Defined in

[framework/asset/resource/prefab.ts:184](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L184)

___

### apply

▸ **apply**(`trans`): `void`

**`language`** zh_CN

**`classdesc`**
设置当前指定的transform

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `trans` | [`transform`](m4m.framework.transform.md) | transform实例 |

#### Returns

`void`

#### Defined in

[framework/asset/resource/prefab.ts:163](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L163)

___

### cParse

▸ **cParse**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

`void`

#### Defined in

[framework/asset/resource/prefab.ts:214](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L214)

___

### caclByteLength

▸ **caclByteLength**(): `number`

**`language`** zh_CN

**`classdesc`**
计算资源字节大小

**`version`** m4m 1.0

#### Returns

`number`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[caclByteLength](../interfaces/m4m.framework.IAsset.md#caclbytelength)

#### Defined in

[framework/asset/resource/prefab.ts:108](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L108)

___

### dispose

▸ **dispose**(): `void`

**`language`** zh_CN

**`classdesc`**
释放资源

**`version`** m4m 1.0

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[dispose](../interfaces/m4m.framework.IAsset.md#dispose)

#### Defined in

[framework/asset/resource/prefab.ts:96](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L96)

___

### getCloneTrans

▸ **getCloneTrans**(): [`transform`](m4m.framework.transform.md)

**`language`** zh_CN

**`classdesc`**
获取克隆的transform

**`version`** m4m 1.0

#### Returns

[`transform`](m4m.framework.transform.md)

#### Defined in

[framework/asset/resource/prefab.ts:122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L122)

___

### getCloneTrans2D

▸ **getCloneTrans2D**(): [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh_CN

**`classdesc`**
获取克隆的transform2D

**`version`** m4m 1.0

#### Returns

[`transform2D`](m4m.framework.transform2D.md)

#### Defined in

[framework/asset/resource/prefab.ts:142](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L142)

___

### getGUID

▸ **getGUID**(): `number`

**`language`** zh_CN

**`classdesc`**
获取资源唯一id

**`version`** m4m 1.0

#### Returns

`number`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[getGUID](../interfaces/m4m.framework.IAsset.md#getguid)

#### Defined in

[framework/asset/resource/prefab.ts:55](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L55)

___

### getName

▸ **getName**(): `string`

**`language`** zh_CN

**`classdesc`**
获取资源名称

**`version`** m4m 1.0

#### Returns

`string`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[getName](../interfaces/m4m.framework.IAsset.md#getname)

#### Defined in

[framework/asset/resource/prefab.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L44)

___

### unuse

▸ **unuse**(`disposeNow?`): `void`

**`language`** zh_CN

**`classdesc`**
引用计数减一

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `disposeNow` | `boolean` | `false` |

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[unuse](../interfaces/m4m.framework.IAsset.md#unuse)

#### Defined in

[framework/asset/resource/prefab.ts:85](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L85)

___

### use

▸ **use**(): `void`

**`language`** zh_CN

**`classdesc`**
引用计数加一

**`version`** m4m 1.0

#### Returns

`void`

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[use](../interfaces/m4m.framework.IAsset.md#use)

#### Defined in

[framework/asset/resource/prefab.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L74)

## Properties

### assetbundle

• **assetbundle**: `string` = `null`

**`language`** zh_CN

**`classdesc`**
prefab依赖的AssetBundle

**`version`** m4m 1.0

#### Defined in

[framework/asset/resource/prefab.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L66)

___

### defaultAsset

• **defaultAsset**: `boolean` = `false`

**`language`** zh_CN

**`classdesc`**
是否为默认资源

**`version`** m4m 1.0

#### Implementation of

[IAsset](../interfaces/m4m.framework.IAsset.md).[defaultAsset](../interfaces/m4m.framework.IAsset.md#defaultasset)

#### Defined in

[framework/asset/resource/prefab.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L24)

___

### isCab

• **isCab**: `boolean` = `false`

#### Defined in

[framework/asset/resource/prefab.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L26)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"prefab"`

#### Defined in

[framework/asset/resource/prefab.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L13)

## Constructors

### constructor

• **new prefab**(`assetName?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `assetName` | `string` | `null` |

#### Defined in

[framework/asset/resource/prefab.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/prefab.ts#L27)
