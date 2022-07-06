# m4m.framework.stateLoad

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / stateLoad

## Class: stateLoad

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).stateLoad

**`language`** zh\_CN

**`classdesc`** 加载状态

**`version`** m4m 1.0

### Table of contents

#### Properties

* [bundle](m4m.framework.stateLoad.md#bundle)
* [compressBinLoaded](m4m.framework.stateLoad.md#compressbinloaded)
* [compressTextLoaded](m4m.framework.stateLoad.md#compresstextloaded)
* [curtask](m4m.framework.stateLoad.md#curtask)
* [errs](m4m.framework.stateLoad.md#errs)
* [iserror](m4m.framework.stateLoad.md#iserror)
* [isfinish](m4m.framework.stateLoad.md#isfinish)
* [isloadFail](m4m.framework.stateLoad.md#isloadfail)
* [logs](m4m.framework.stateLoad.md#logs)
* [progressCall](m4m.framework.stateLoad.md#progresscall)
* [resstate](m4m.framework.stateLoad.md#resstate)
* [resstateFirst](m4m.framework.stateLoad.md#resstatefirst)
* [totalByteLength](m4m.framework.stateLoad.md#totalbytelength)
* [totaltask](m4m.framework.stateLoad.md#totaltask)
* [url](m4m.framework.stateLoad.md#url)

#### Constructors

* [constructor](m4m.framework.stateLoad.md#constructor)

#### Accessors

* [curByteLength](m4m.framework.stateLoad.md#curbytelength)
* [fileProgress](m4m.framework.stateLoad.md#fileprogress)
* [progress](m4m.framework.stateLoad.md#progress)

### Properties

#### bundle

• `Optional` **bundle**: [`assetBundle`](m4m.framework.assetBundle.md)

**Defined in**

[framework/asset/a/define.ts:234](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L234)

***

#### compressBinLoaded

• **compressBinLoaded**: `number` = `0`

**Defined in**

[framework/asset/a/define.ts:344](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L344)

***

#### compressTextLoaded

• **compressTextLoaded**: `number` = `0`

**Defined in**

[framework/asset/a/define.ts:342](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L342)

***

#### curtask

• **curtask**: `number` = `0`

**`language`** zh\_CN 当前的文件数进度

**`version`** m4m 1.0

**Defined in**

[framework/asset/a/define.ts:279](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L279)

***

#### errs

• **errs**: `Error`\[] = `[]`

**`language`** zh\_CN 加载过程中记录的错误信息

**`version`** m4m 1.0

**Defined in**

[framework/asset/a/define.ts:359](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L359)

***

#### iserror

• **iserror**: `boolean` = `false`

**`language`** zh\_CN 加载是否遇到错误

**`version`** m4m 1.0

**Defined in**

[framework/asset/a/define.ts:249](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L249)

***

#### isfinish

• **isfinish**: `boolean` = `false`

**`language`** zh\_CN 加载是否完成

**`version`** m4m 1.0

**Defined in**

[framework/asset/a/define.ts:256](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L256)

***

#### isloadFail

• **isloadFail**: `boolean` = `false`

**`language`** zh\_CN 加载是否失败

**`version`** m4m 1.0

**Defined in**

[framework/asset/a/define.ts:241](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L241)

***

#### logs

• **logs**: `string`\[] = `[]`

**`language`** zh\_CN 加载过程中记录的log

**`version`** m4m 1.0

**Defined in**

[framework/asset/a/define.ts:352](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L352)

***

#### progressCall

• **progressCall**: `boolean` = `false`

**Defined in**

[framework/asset/a/define.ts:340](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L340)

***

#### resstate

• **resstate**: `Object` = `{}`

**`language`** zh\_CN 记录需要加载的每一个的状态和资源引用

**`version`** m4m 1.0

**Index signature**

▪ \[id: `string`]: [`ResourceState`](m4m.framework.ResourceState.md)

**Defined in**

[framework/asset/a/define.ts:264](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L264)

***

#### resstateFirst

• **resstateFirst**: [`ResourceState`](m4m.framework.ResourceState.md) = `null`

**`language`** zh\_CN 记录加载的第一个的状态和资源引用

**`version`** m4m 1.0

**Defined in**

[framework/asset/a/define.ts:272](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L272)

***

#### totalByteLength

• **totalByteLength**: `number` = `0`

**`language`** zh\_CN 总字节长度

**`version`** m4m 1.0

**Defined in**

[framework/asset/a/define.ts:327](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L327)

***

#### totaltask

• **totaltask**: `number` = `0`

**`language`** zh\_CN 文件数的总进度

**`version`** m4m 1.0

**Defined in**

[framework/asset/a/define.ts:286](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L286)

***

#### url

• **url**: `string`

**`language`** zh\_CN 源url地址

**`version`** m4m 1.0

**Defined in**

[framework/asset/a/define.ts:366](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L366)

### Constructors

#### constructor

• **new stateLoad**()

### Accessors

#### curByteLength

• `get` **curByteLength**(): `number`

**`language`** zh\_CN 已加载的字节长度

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/asset/a/define.ts:305](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L305)

***

#### fileProgress

• `get` **fileProgress**(): `number`

**`language`** zh\_CN 获取文件数加载进度

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/asset/a/define.ts:294](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L294)

***

#### progress

• `get` **progress**(): `number`

**`language`** zh\_CN 获取文件真实加载进度

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/asset/a/define.ts:335](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/a/define.ts#L335)
