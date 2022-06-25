[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / guidpath

# Class: guidpath

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).guidpath

**`language`** zh_CN

**`classdesc`**
路径组件

**`version`** m4m 1.0

## Implements

- [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

## Table of contents

### Constructors

- [constructor](m4m.framework.guidpath.md#constructor)

### Properties

- [gameObject](m4m.framework.guidpath.md#gameobject)
- [isloop](m4m.framework.guidpath.md#isloop)
- [lookforward](m4m.framework.guidpath.md#lookforward)
- [speed](m4m.framework.guidpath.md#speed)
- [ClassName](m4m.framework.guidpath.md#classname)

### Methods

- [onPlay](m4m.framework.guidpath.md#onplay)
- [pause](m4m.framework.guidpath.md#pause)
- [play](m4m.framework.guidpath.md#play)
- [replay](m4m.framework.guidpath.md#replay)
- [setpathasset](m4m.framework.guidpath.md#setpathasset)
- [start](m4m.framework.guidpath.md#start)
- [stop](m4m.framework.guidpath.md#stop)
- [update](m4m.framework.guidpath.md#update)

### Accessors

- [pathasset](m4m.framework.guidpath.md#pathasset)

## Constructors

### constructor

• **new guidpath**()

## Properties

### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh_CN

**`classdesc`**
挂载的gameobject

**`version`** m4m 1.0

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[gameObject](../interfaces/m4m.framework.INodeComponent.md#gameobject)

#### Defined in

[framework/component/guidpath.ts:228](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L228)

___

### isloop

• **isloop**: `boolean` = `false`

#### Defined in

[framework/component/guidpath.ts:108](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L108)

___

### lookforward

• **lookforward**: `boolean` = `false`

**`language`** zh_CN

**`classdesc`**
挂载此组件的gameobject是否朝向前方

**`version`** m4m 1.0

#### Defined in

[framework/component/guidpath.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L116)

___

### speed

• **speed**: `number` = `1`

**`language`** zh_CN

**`classdesc`**
移动速度

**`version`** m4m 1.0

#### Defined in

[framework/component/guidpath.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L53)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"guidpath"`

#### Defined in

[framework/component/guidpath.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L13)

## Methods

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

#### Defined in

[framework/component/guidpath.ts:154](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L154)

___

### pause

▸ **pause**(): `void`

**`language`** zh_CN

**`classdesc`**
暂停移动

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/component/guidpath.ts:75](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L75)

___

### play

▸ **play**(`loopCount?`): `void`

**`language`** zh_CN

**`classdesc`**
按照路径开始移动

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `loopCount` | `number` | `1` |

#### Returns

`void`

#### Defined in

[framework/component/guidpath.ts:63](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L63)

___

### replay

▸ **replay**(`loopCount?`): `void`

**`language`** zh_CN

**`classdesc`**
重新按照路径移动

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `loopCount` | `number` | `1` |

#### Returns

`void`

#### Defined in

[framework/component/guidpath.ts:98](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L98)

___

### setpathasset

▸ **setpathasset**(`pathasset`, `speed?`, `oncomplete?`): `void`

**`language`** zh_CN

**`classdesc`**
设置路径组件的需要的参数

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `pathasset` | [`pathasset`](m4m.framework.pathasset.md) | `undefined` | 路径资源 |
| `speed` | `number` | `1` | 移动速度 |
| `oncomplete` | () => `void` | `null` | 按照路径移动结束需要执行的事件 |

#### Returns

`void`

#### Defined in

[framework/component/guidpath.ts:130](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L130)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

#### Defined in

[framework/component/guidpath.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L149)

___

### stop

▸ **stop**(): `void`

**`language`** zh_CN

**`classdesc`**
停止移动

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/component/guidpath.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L86)

___

### update

▸ **update**(`delta`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[update](../interfaces/m4m.framework.INodeComponent.md#update)

#### Defined in

[framework/component/guidpath.ts:159](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L159)

## Accessors

### pathasset

• `get` **pathasset**(): [`pathasset`](m4m.framework.pathasset.md)

**`language`** zh_CN

**`classdesc`**
路径组件的pathasset

**`version`** m4m 1.0

#### Returns

[`pathasset`](m4m.framework.pathasset.md)

#### Defined in

[framework/component/guidpath.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L42)

• `set` **pathasset**(`pathasset`): `void`

**`language`** zh_CN

**`classdesc`**
设置路径组件需要的路径资源

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `pathasset` | [`pathasset`](m4m.framework.pathasset.md) |

#### Returns

`void`

#### Defined in

[framework/component/guidpath.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/guidpath.ts#L24)
