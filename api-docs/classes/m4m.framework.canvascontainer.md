[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / canvascontainer

# Class: canvascontainer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).canvascontainer

**`language`** zh_CN

**`classdesc`**
UI画布容器组件

**`version`** m4m 1.0

## Implements

- [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

## Table of contents

### Accessors

- [canvas](m4m.framework.canvascontainer.md#canvas)
- [renderMode](m4m.framework.canvascontainer.md#rendermode)
- [sortOrder](m4m.framework.canvascontainer.md#sortorder)

### Constructors

- [constructor](m4m.framework.canvascontainer.md#constructor)

### Properties

- [gameObject](m4m.framework.canvascontainer.md#gameobject)
- [ClassName](m4m.framework.canvascontainer.md#classname)

### Methods

- [getOverLay](m4m.framework.canvascontainer.md#getoverlay)
- [onPlay](m4m.framework.canvascontainer.md#onplay)
- [setOverLay](m4m.framework.canvascontainer.md#setoverlay)
- [start](m4m.framework.canvascontainer.md#start)
- [update](m4m.framework.canvascontainer.md#update)

## Accessors

### canvas

• `get` **canvas**(): [`canvas`](m4m.framework.canvas.md)

**`language`** zh_CN

**`classdesc`**
UI canvas

**`version`** m4m 1.0

#### Returns

[`canvas`](m4m.framework.canvas.md)

#### Defined in

[framework/component/canvascontainer.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L34)

___

### renderMode

• `get` **renderMode**(): [`canvasRenderMode`](../enums/m4m.framework.canvasRenderMode.md)

**`language`** zh_CN

**`classdesc`**
renderMode UI render模式

**`version`** m4m 1.0

#### Returns

[`canvasRenderMode`](../enums/m4m.framework.canvasRenderMode.md)

#### Defined in

[framework/component/canvascontainer.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L79)

• `set` **renderMode**(`mode`): `void`

**`language`** zh_CN

**`classdesc`**
renderMode UI render模式

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `mode` | [`canvasRenderMode`](../enums/m4m.framework.canvasRenderMode.md) |

#### Returns

`void`

#### Defined in

[framework/component/canvascontainer.ts:80](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L80)

___

### sortOrder

• `get` **sortOrder**(): `number`

#### Returns

`number`

#### Defined in

[framework/component/canvascontainer.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L52)

• `set` **sortOrder**(`order`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `order` | `number` |

#### Returns

`void`

#### Defined in

[framework/component/canvascontainer.ts:55](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L55)

## Constructors

### constructor

• **new canvascontainer**()

#### Defined in

[framework/component/canvascontainer.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L15)

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

[framework/component/canvascontainer.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L25)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"canvascontainer"`

#### Defined in

[framework/component/canvascontainer.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L13)

## Methods

### getOverLay

▸ **getOverLay**(): [`overlay2D`](m4m.framework.overlay2D.md)

#### Returns

[`overlay2D`](m4m.framework.overlay2D.md)

#### Defined in

[framework/component/canvascontainer.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L47)

___

### onPlay

▸ **onPlay**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

#### Defined in

[framework/component/canvascontainer.ts:109](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L109)

___

### setOverLay

▸ **setOverLay**(`lay`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `lay` | [`overlay2D`](m4m.framework.overlay2D.md) |

#### Returns

`void`

#### Defined in

[framework/component/canvascontainer.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L42)

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Implementation of

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

#### Defined in

[framework/component/canvascontainer.ts:104](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L104)

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

[framework/component/canvascontainer.ts:114](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/canvascontainer.ts#L114)
