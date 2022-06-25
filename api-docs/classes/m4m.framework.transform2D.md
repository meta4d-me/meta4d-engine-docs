[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / transform2D

# Class: transform2D

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).transform2D

**`language`** zh_CN

**`classdesc`**
2d的节点类<p/>
相当于3d的tranform和gameobject的合集<p/>
自身包含父子关系和组件

**`version`** m4m 1.0

## Table of contents

### Methods

- [ContainsCanvasPoint](m4m.framework.transform2D.md#containscanvaspoint)
- [addChild](m4m.framework.transform2D.md#addchild)
- [addChildAt](m4m.framework.transform2D.md#addchildat)
- [addComponent](m4m.framework.transform2D.md#addcomponent)
- [addComponentDirect](m4m.framework.transform2D.md#addcomponentdirect)
- [clone](m4m.framework.transform2D.md#clone)
- [dispose](m4m.framework.transform2D.md#dispose)
- [getCanvasWorldMatrix](m4m.framework.transform2D.md#getcanvasworldmatrix)
- [getComponent](m4m.framework.transform2D.md#getcomponent)
- [getComponents](m4m.framework.transform2D.md#getcomponents)
- [getComponentsInChildren](m4m.framework.transform2D.md#getcomponentsinchildren)
- [getFirstComponentInChildren](m4m.framework.transform2D.md#getfirstcomponentinchildren)
- [getLayoutValue](m4m.framework.transform2D.md#getlayoutvalue)
- [getLocalMatrix](m4m.framework.transform2D.md#getlocalmatrix)
- [getSiblingIndex](m4m.framework.transform2D.md#getsiblingindex)
- [getWorldMatrix](m4m.framework.transform2D.md#getworldmatrix)
- [getWorldRotate](m4m.framework.transform2D.md#getworldrotate)
- [getWorldScale](m4m.framework.transform2D.md#getworldscale)
- [getWorldTranslate](m4m.framework.transform2D.md#getworldtranslate)
- [init](m4m.framework.transform2D.md#init)
- [markDirty](m4m.framework.transform2D.md#markdirty)
- [removeAllChild](m4m.framework.transform2D.md#removeallchild)
- [removeAllComponents](m4m.framework.transform2D.md#removeallcomponents)
- [removeChild](m4m.framework.transform2D.md#removechild)
- [removeComponent](m4m.framework.transform2D.md#removecomponent)
- [removeComponentByTypeName](m4m.framework.transform2D.md#removecomponentbytypename)
- [setLayoutValue](m4m.framework.transform2D.md#setlayoutvalue)
- [setLocalPosition](m4m.framework.transform2D.md#setlocalposition)
- [setSiblingIndex](m4m.framework.transform2D.md#setsiblingindex)
- [setWorldPosition](m4m.framework.transform2D.md#setworldposition)
- [updateTran](m4m.framework.transform2D.md#updatetran)
- [updateWorldTran](m4m.framework.transform2D.md#updateworldtran)
- [getTransInfoInCanvas](m4m.framework.transform2D.md#gettransinfoincanvas)
- [getTransform2DById](m4m.framework.transform2D.md#gettransform2dbyid)

### Properties

- [\_parent](m4m.framework.transform2D.md#_parent)
- [collider](m4m.framework.transform2D.md#collider)
- [componentTypes](m4m.framework.transform2D.md#componenttypes)
- [components](m4m.framework.transform2D.md#components)
- [enableUILayout](m4m.framework.transform2D.md#enableuilayout)
- [enableUIMaskRect](m4m.framework.transform2D.md#enableuimaskrect)
- [height](m4m.framework.transform2D.md#height)
- [hideFlags](m4m.framework.transform2D.md#hideflags)
- [insId](m4m.framework.transform2D.md#insid)
- [isStatic](m4m.framework.transform2D.md#isstatic)
- [layer](m4m.framework.transform2D.md#layer)
- [localRotate](m4m.framework.transform2D.md#localrotate)
- [localScale](m4m.framework.transform2D.md#localscale)
- [localTranslate](m4m.framework.transform2D.md#localtranslate)
- [name](m4m.framework.transform2D.md#name)
- [onDispose](m4m.framework.transform2D.md#ondispose)
- [physicsBody](m4m.framework.transform2D.md#physicsbody)
- [pivot](m4m.framework.transform2D.md#pivot)
- [prefab](m4m.framework.transform2D.md#prefab)
- [renderer](m4m.framework.transform2D.md#renderer)
- [tag](m4m.framework.transform2D.md#tag)
- [width](m4m.framework.transform2D.md#width)
- [ClassName](m4m.framework.transform2D.md#classname)

### Accessors

- [aabbRect](m4m.framework.transform2D.md#aabbrect)
- [beDispose](m4m.framework.transform2D.md#bedispose)
- [canvas](m4m.framework.transform2D.md#canvas)
- [children](m4m.framework.transform2D.md#children)
- [isMask](m4m.framework.transform2D.md#ismask)
- [layoutPercentState](m4m.framework.transform2D.md#layoutpercentstate)
- [layoutState](m4m.framework.transform2D.md#layoutstate)
- [maskRect](m4m.framework.transform2D.md#maskrect)
- [maskRectId](m4m.framework.transform2D.md#maskrectid)
- [parent](m4m.framework.transform2D.md#parent)
- [parentIsMask](m4m.framework.transform2D.md#parentismask)
- [visible](m4m.framework.transform2D.md#visible)
- [visibleInScene](m4m.framework.transform2D.md#visibleinscene)

### Constructors

- [constructor](m4m.framework.transform2D.md#constructor)

## Methods

### ContainsCanvasPoint

▸ **ContainsCanvasPoint**(`ModelPos`, `tolerance?`): `boolean`

**`language`** zh_CN

**`classdesc`**
检测以canvas为参考的位置，是否在节点的范围内

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `ModelPos` | `vector2` | `undefined` | 模型空间位置 |
| `tolerance` | `number` | `0` | - |

#### Returns

`boolean`

#### Defined in

[framework/2d/transform2d.ts:1460](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1460)

___

### addChild

▸ **addChild**(`node`): `void`

**`language`** zh_CN

**`classdesc`**
为当前2d节点添加子节点

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `node` | [`transform2D`](m4m.framework.transform2D.md) | 要添加的子节点 |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:550](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L550)

___

### addChildAt

▸ **addChildAt**(`node`, `index`): `void`

**`language`** zh_CN

**`classdesc`**
为当前2d节点添加子节点,并插入到指定位置

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `node` | [`transform2D`](m4m.framework.transform2D.md) | 要添加的子节点 |
| `index` | `number` | 要插入到的位置 |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:574](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L574)

___

### addComponent

▸ **addComponent**(`type`): [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)

**`language`** zh_CN

**`classdesc`**
为当前节点添加一个组件

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `type` | `string` | 组件名称 |

#### Returns

[`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)

#### Defined in

[framework/2d/transform2d.ts:1102](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1102)

___

### addComponentDirect

▸ **addComponentDirect**(`comp`): [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)

**`language`** zh_CN

**`classdesc`**
为当前节点添加组件

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `comp` | [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md) | 2d组件实例 |

#### Returns

[`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)

#### Defined in

[framework/2d/transform2d.ts:1118](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1118)

___

### clone

▸ **clone**(): [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh_CN

**`classdesc`**
获取当前transform2D的克隆

**`version`** m4m 1.0

#### Returns

[`transform2D`](m4m.framework.transform2D.md)

#### Defined in

[framework/2d/transform2d.ts:1767](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1767)

___

### dispose

▸ **dispose**(): `void`

**`language`** zh_CN

**`classdesc`**
释放当前节点，包括其子节点

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:1002](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1002)

___

### getCanvasWorldMatrix

▸ **getCanvasWorldMatrix**(): `matrix3x2`

**`language`** zh_CN

**`classdesc`**
获取当前节点的Canvas_世界_变换矩阵

**`version`** m4m 1.0

#### Returns

`matrix3x2`

#### Defined in

[framework/2d/transform2d.ts:899](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L899)

___

### getComponent

▸ **getComponent**(`type`): [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)

**`language`** zh_CN

**`classdesc`**
获取当前节点的指定组件实例

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `type` | `string` | 2d组件的名字 |

#### Returns

[`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)

#### Defined in

[framework/2d/transform2d.ts:1295](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1295)

___

### getComponents

▸ **getComponents**(): [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)[]

**`language`** zh_CN

**`classdesc`**
获取当前节点身上所有的组件

**`version`** m4m 1.0

#### Returns

[`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)[]

#### Defined in

[framework/2d/transform2d.ts:1317](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1317)

___

### getComponentsInChildren

▸ **getComponentsInChildren**(`type`): [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)[]

**`language`** zh_CN

**`classdesc`**
获取当前节点下所有的特定组件

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `type` | `string` | 组件名称 |

#### Returns

[`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)[]

#### Defined in

[framework/2d/transform2d.ts:1335](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1335)

___

### getFirstComponentInChildren

▸ **getFirstComponentInChildren**(`type`): [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)

获取当前节点下及子节点第一个能找到的组件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `type` | `string` | 组件名称 |

#### Returns

[`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md)

#### Defined in

[framework/2d/transform2d.ts:1377](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1377)

___

### getLayoutValue

▸ **getLayoutValue**(`option`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `option` | [`layoutOption`](../enums/m4m.framework.layoutOption.md) |

#### Returns

`number`

#### Defined in

[framework/2d/transform2d.ts:1561](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1561)

___

### getLocalMatrix

▸ **getLocalMatrix**(): `matrix3x2`

**`language`** zh_CN

**`classdesc`**
获取当前节点的本地变换矩阵

**`version`** m4m 1.0

#### Returns

`matrix3x2`

#### Defined in

[framework/2d/transform2d.ts:875](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L875)

___

### getSiblingIndex

▸ **getSiblingIndex**(): `number`

**`language`** zh_CN

**`classdesc`**
获取兄弟姐妹序列索引

**`version`** m4m 1.0

#### Returns

`number`

#### Defined in

[framework/2d/transform2d.ts:1752](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1752)

___

### getWorldMatrix

▸ **getWorldMatrix**(): `matrix3x2`

**`language`** zh_CN

**`classdesc`**
获取当前节点的世界变换矩阵

**`version`** m4m 1.0

#### Returns

`matrix3x2`

#### Defined in

[framework/2d/transform2d.ts:887](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L887)

___

### getWorldRotate

▸ **getWorldRotate**(): [`angelref`](m4m.math.angelref.md)

**`language`** zh_CN

**`classdesc`**
获取当前节点的相对于canvas的旋转

**`version`** m4m 1.0

#### Returns

[`angelref`](m4m.math.angelref.md)

#### Defined in

[framework/2d/transform2d.ts:862](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L862)

___

### getWorldScale

▸ **getWorldScale**(): `vector2`

**`language`** zh_CN

**`classdesc`**
获取当前节点的相对于canvas的缩放

**`version`** m4m 1.0

#### Returns

`vector2`

#### Defined in

[framework/2d/transform2d.ts:849](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L849)

___

### getWorldTranslate

▸ **getWorldTranslate**(): `vector2`

**`language`** zh_CN

**`classdesc`**
获取当前节点的相对于canvas的位置

**`version`** m4m 1.0

#### Returns

`vector2`

#### Defined in

[framework/2d/transform2d.ts:836](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L836)

___

### init

▸ **init**(`bePlay?`): `void`

**`language`** zh_CN

**`classdesc`**
组件的初始化

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `bePlay` | `boolean` | `false` |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:1074](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1074)

___

### markDirty

▸ **markDirty**(): `void`

**`language`** zh_CN

**`classdesc`**
标记自身脏了

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:649](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L649)

___

### removeAllChild

▸ **removeAllChild**(`needDispose?`): `void`

**`language`** zh_CN

**`classdesc`**
为当前2d节点移除所有子节点

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `needDispose` | `boolean` | `false` |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:631](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L631)

___

### removeAllComponents

▸ **removeAllComponents**(): `void`

**`language`** zh_CN

**`classdesc`**
移除当前节点下的所有组件

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:1271](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1271)

___

### removeChild

▸ **removeChild**(`node`): `void`

**`language`** zh_CN

**`classdesc`**
为当前2d节点移除子节点

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`transform2D`](m4m.framework.transform2D.md) |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:604](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L604)

___

### removeComponent

▸ **removeComponent**(`comp`): `void`

**`language`** zh_CN

**`classdesc`**
移除当前节点下的组件

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `comp` | [`I2DComponent`](../interfaces/m4m.framework.I2DComponent.md) | 2d组件实例 |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:1198](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1198)

___

### removeComponentByTypeName

▸ **removeComponentByTypeName**(`type`): [`C2DComponent`](m4m.framework.C2DComponent.md)

**`language`** zh_CN

**`classdesc`**
移除当前节点下的组件

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `type` | `string` | 2d组件名称 |

#### Returns

[`C2DComponent`](m4m.framework.C2DComponent.md)

#### Defined in

[framework/2d/transform2d.ts:1244](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1244)

___

### setLayoutValue

▸ **setLayoutValue**(`option`, `value`): `void`

**`language`** zh_CN

**`classdesc`**
布局设定值

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `option` | [`layoutOption`](../enums/m4m.framework.layoutOption.md) |
| `value` | `number` |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:1551](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1551)

___

### setLocalPosition

▸ **setLocalPosition**(`pos`): `void`

设置 节点的本地位置（会处理layout选项）

#### Parameters

| Name | Type |
| :------ | :------ |
| `pos` | `vector2` |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:1776](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1776)

___

### setSiblingIndex

▸ **setSiblingIndex**(`siblingIndex`): `void`

**`language`** zh_CN

**`classdesc`**
设置兄弟姐妹序列索引

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `siblingIndex` | `number` |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:1734](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1734)

___

### setWorldPosition

▸ **setWorldPosition**(`pos`): `void`

**`language`** zh_CN

**`classdesc`**
设置当前节点的相对于canvas的位置

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pos` | `vector2` | 相对于canvas的位置 |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:943](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L943)

___

### updateTran

▸ **updateTran**(`parentChange`): `void`

**`language`** zh_CN

**`classdesc`**
用脏机制来检查自身和子节点。更新位置、缩放、旋转等信息

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `parentChange` | `boolean` | 父节点是否发生变化 |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:668](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L668)

___

### updateWorldTran

▸ **updateWorldTran**(): `void`

**`language`** zh_CN

**`classdesc`**
更新整个节点结构

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:725](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L725)

___

### getTransInfoInCanvas

▸ `Static` **getTransInfoInCanvas**(`trans`, `out`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `trans` | [`transform2D`](m4m.framework.transform2D.md) |
| `out` | [`t2dInfo`](m4m.framework.t2dInfo.md) |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:905](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L905)

___

### getTransform2DById

▸ `Static` **getTransform2DById**(`insID`): [`transform2D`](m4m.framework.transform2D.md)

获取transform2D 通过 insID

#### Parameters

| Name | Type |
| :------ | :------ |
| `insID` | `number` |

#### Returns

[`transform2D`](m4m.framework.transform2D.md)

#### Defined in

[framework/2d/transform2d.ts:143](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L143)

## Properties

### \_parent

• **\_parent**: [`transform2D`](m4m.framework.transform2D.md)

**`language`** zh_CN

**`classdesc`**
当前2d节点的父亲节点

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:239](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L239)

___

### collider

• **collider**: [`ICollider2d`](../interfaces/m4m.framework.ICollider2d.md)

**`language`** zh_CN

**`classdesc`**
碰撞盒组件 可为空

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:1043](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1043)

___

### componentTypes

• **componentTypes**: `Object` = `{}`

#### Index signature

▪ [key: `string`]: `boolean`

#### Defined in

[framework/2d/transform2d.ts:1063](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1063)

___

### components

• **components**: [`C2DComponent`](m4m.framework.C2DComponent.md)[] = `[]`

**`language`** zh_CN

**`classdesc`**
当前节点的所有组件

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:1062](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1062)

___

### enableUILayout

• **enableUILayout**: `boolean` = `true`

启用 UI 布局功能

#### Defined in

[framework/2d/transform2d.ts:185](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L185)

___

### enableUIMaskRect

• **enableUIMaskRect**: `boolean` = `true`

启用 UI 矩形遮罩裁剪显示 功能

#### Defined in

[framework/2d/transform2d.ts:190](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L190)

___

### height

• **height**: `number` = `0`

**`language`** zh_CN

**`classdesc`**
当前2d节点的高

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:291](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L291)

___

### hideFlags

• **hideFlags**: [`HideFlags`](../enums/m4m.framework.HideFlags.md) = `HideFlags.None`

**`language`** zh_CN

**`classdesc`**
当前2d节点的hideFlag，用来控制2d节点各种形态下的显示隐藏

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:310](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L310)

___

### insId

• **insId**: [`insID`](m4m.framework.insID.md)

**`language`** zh_CN

**`classdesc`**
当前节点的唯一id

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:372](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L372)

___

### isStatic

• **isStatic**: `boolean` = `false`

**`language`** zh_CN

**`classdesc`**
对象是静态

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:230](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L230)

___

### layer

• **layer**: `number`

**`language`** zh_CN

**`classdesc`**
对象layer (取值范围0~31)

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:201](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L201)

___

### localRotate

• **localRotate**: `number` = `0`

**`language`** zh_CN

**`classdesc`**
当前2d节点的旋转

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:406](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L406)

___

### localScale

• **localScale**: `vector2`

**`language`** zh_CN

**`classdesc`**
当前2d节点的缩放

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:396](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L396)

___

### localTranslate

• **localTranslate**: `vector2`

**`language`** zh_CN

**`classdesc`**
当前2d节点的位置

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:386](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L386)

___

### name

• **name**: `string` = `"noname"`

**`language`** zh_CN

**`classdesc`**
当前2d节点的名字

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:220](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L220)

___

### onDispose

• **onDispose**: () => `void`

#### Type declaration

▸ (): `void`

##### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:993](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L993)

___

### physicsBody

• **physicsBody**: [`I2DPhysicsBody`](../interfaces/m4m.framework.I2DPhysicsBody.md)

**`language`** zh_CN

**`classdesc`**
碰撞盒组件 可为空

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:1052](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1052)

___

### pivot

• **pivot**: `vector2`

**`language`** zh_CN

**`classdesc`**
当前2d节点的中心点位置

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:301](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L301)

___

### prefab

• **prefab**: `string` = `""`

**`language`** zh_CN

**`classdesc`**
当前节点依赖的prefab路径，如果不依赖，则为空

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:157](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L157)

___

### renderer

• **renderer**: [`IRectRenderer`](../interfaces/m4m.framework.IRectRenderer.md)

**`language`** zh_CN

**`classdesc`**
当前节点的渲染组件，一个节点同时只能存在一个渲染组件

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:1034](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1034)

___

### tag

• **tag**: `string` = `StringUtil.builtinTag_Untagged`

**`language`** zh_CN

**`classdesc`**
对象字符标签

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:210](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L210)

___

### width

• **width**: `number` = `0`

**`language`** zh_CN

**`classdesc`**
当前2d节点的宽

**`version`** m4m 1.0

#### Defined in

[framework/2d/transform2d.ts:281](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L281)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"transform2D"`

#### Defined in

[framework/2d/transform2d.ts:124](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L124)

## Accessors

### aabbRect

• `get` **aabbRect**(): `rect`

aabb 矩形

#### Returns

`rect`

#### Defined in

[framework/2d/transform2d.ts:452](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L452)

___

### beDispose

• `get` **beDispose**(): `boolean`

**`language`** zh_CN

**`classdesc`**
获取当前transform是否被释放掉了

**`version`** m4m 1.0

#### Returns

`boolean`

#### Defined in

[framework/2d/transform2d.ts:987](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L987)

___

### canvas

• `get` **canvas**(): [`canvas`](m4m.framework.canvas.md)

**`language`** zh_CN

**`classdesc`**
当前2d节点所属的canvas

**`version`** m4m 1.0

#### Returns

[`canvas`](m4m.framework.canvas.md)

#### Defined in

[framework/2d/transform2d.ts:171](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L171)

• `set` **canvas**(`val`): `void`

**`language`** zh_CN

**`classdesc`**
当前2d节点所属的canvas

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | [`canvas`](m4m.framework.canvas.md) |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:166](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L166)

___

### children

• `get` **children**(): [`transform2D`](m4m.framework.transform2D.md)[]

**`language`** zh_CN

**`classdesc`**
当前2d节点的孩子节点

**`version`** m4m 1.0

#### Returns

[`transform2D`](m4m.framework.transform2D.md)[]

#### Defined in

[framework/2d/transform2d.ts:253](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L253)

• `set` **children**(`children`): `void`

**`language`** zh_CN

**`classdesc`**
当前2d节点的孩子节点

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `children` | [`transform2D`](m4m.framework.transform2D.md)[] |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:257](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L257)

___

### isMask

• `get` **isMask**(): `boolean`

**`language`** zh_CN

**`classdesc`**
当前节点是否是mask

**`version`** m4m 1.0

#### Returns

`boolean`

#### Defined in

[framework/2d/transform2d.ts:437](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L437)

• `set` **isMask**(`b`): `void`

**`language`** zh_CN

**`classdesc`**
当前节点是否是mask

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `b` | `boolean` |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:441](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L441)

___

### layoutPercentState

• `get` **layoutPercentState**(): `number`

**`language`** zh_CN

**`classdesc`**
布局百分比模式状态

**`version`** m4m 1.0

#### Returns

`number`

#### Defined in

[framework/2d/transform2d.ts:1587](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1587)

• `set` **layoutPercentState**(`state`): `void`

**`language`** zh_CN

**`classdesc`**
布局百分比模式状态

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `state` | `number` |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:1577](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1577)

___

### layoutState

• `get` **layoutState**(): `number`

**`language`** zh_CN

**`classdesc`**
布局状态

**`version`** m4m 1.0

#### Returns

`number`

#### Defined in

[framework/2d/transform2d.ts:1536](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1536)

• `set` **layoutState**(`state`): `void`

**`language`** zh_CN

**`classdesc`**
布局状态

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `state` | `number` |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:1526](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L1526)

___

### maskRect

• `get` **maskRect**(): `rect`

裁剪遮罩矩形

#### Returns

`rect`

#### Defined in

[framework/2d/transform2d.ts:416](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L416)

___

### maskRectId

• `get` **maskRectId**(): `string`

裁剪遮罩矩形 ID

#### Returns

`string`

#### Defined in

[framework/2d/transform2d.ts:410](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L410)

___

### parent

• `get` **parent**(): [`transform2D`](m4m.framework.transform2D.md)

#### Returns

[`transform2D`](m4m.framework.transform2D.md)

#### Defined in

[framework/2d/transform2d.ts:240](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L240)

___

### parentIsMask

• `get` **parentIsMask**(): `boolean`

#### Returns

`boolean`

#### Defined in

[framework/2d/transform2d.ts:528](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L528)

___

### visible

• `get` **visible**(): `boolean`

**`language`** zh_CN

**`classdesc`**
当前2d节点的隐藏状态

**`version`** m4m 1.0

#### Returns

`boolean`

#### Defined in

[framework/2d/transform2d.ts:340](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L340)

• `set` **visible**(`val`): `void`

**`language`** zh_CN

**`classdesc`**
当前2d节点的隐藏状态

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `boolean` |

#### Returns

`void`

#### Defined in

[framework/2d/transform2d.ts:344](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L344)

___

### visibleInScene

• `get` **visibleInScene**(): `boolean`

**`language`** zh_CN

**`classdesc`**
当前2d节点在场景中是否可见</p>
如果其父节点不可见，其同样不可见

**`version`** m4m 1.0

#### Returns

`boolean`

#### Defined in

[framework/2d/transform2d.ts:323](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/transform2d.ts#L323)

## Constructors

### constructor

• **new transform2D**()
