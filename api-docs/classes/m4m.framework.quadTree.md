[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / quadTree

# Class: quadTree

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).quadTree

**`language`** zh_CN

**`classdesc`**
四叉树

**`version`** m4m 1.0

## Table of contents

### Methods

- [clear](m4m.framework.quadTree.md#clear)
- [insert](m4m.framework.quadTree.md#insert)
- [retrieve](m4m.framework.quadTree.md#retrieve)

### Constructors

- [constructor](m4m.framework.quadTree.md#constructor)

## Methods

### clear

▸ **clear**(): `void`

**`language`** zh_CN
清理所有节点

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/tool/quadTree.ts:283](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/quadTree.ts#L283)

___

### insert

▸ **insert**(`rect`): `void`

**`language`** zh_CN
插入节点

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `rect` | `rect` | 矩形区域 |

#### Returns

`void`

#### Defined in

[framework/tool/quadTree.ts:257](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/quadTree.ts#L257)

___

### retrieve

▸ **retrieve**(`bounds`, `outRects`): `void`

**`language`** zh_CN
检索结果

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `bounds` | `rect` | 检测矩形 |
| `outRects` | `rect`[] | 返回结果矩形数组 |

#### Returns

`void`

#### Defined in

[framework/tool/quadTree.ts:271](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/quadTree.ts#L271)

## Constructors

### constructor

• **new quadTree**(`bounds`, `maxObjNum?`, `maxLevel?`)

**`language`** zh_CN
四叉树

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `bounds` | `rect` | `undefined` | 全局的矩形范围 |
| `maxObjNum` | `number` | `5` | 每个节点(象限) 能包含的最大物体数量 |
| `maxLevel` | `number` | `5` | 树的最大深度 |

#### Defined in

[framework/tool/quadTree.ts:244](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/tool/quadTree.ts#L244)
