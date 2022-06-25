[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / transform

# Class: transform

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).transform

**`language`** zh_CN
transform类 对应unity中transform概念

**`version`** m4m 1.0

## Table of contents

### Properties

- [\_parent](m4m.framework.transform.md#_parent)
- [children](m4m.framework.transform.md#children)
- [dirtiedOfFrustumCulling](m4m.framework.transform.md#dirtiedoffrustumculling)
- [enableCulling](m4m.framework.transform.md#enableculling)
- [firstCalc](m4m.framework.transform.md#firstcalc)
- [gameObject](m4m.framework.transform.md#gameobject)
- [hasInitComp](m4m.framework.transform.md#hasinitcomp)
- [hasInitCompChild](m4m.framework.transform.md#hasinitcompchild)
- [hasOnPlayComp](m4m.framework.transform.md#hasonplaycomp)
- [hasOnPlayCompChild](m4m.framework.transform.md#hasonplaycompchild)
- [hasRendererComp](m4m.framework.transform.md#hasrenderercomp)
- [hasRendererCompChild](m4m.framework.transform.md#hasrenderercompchild)
- [hasUpdateComp](m4m.framework.transform.md#hasupdatecomp)
- [hasUpdateCompChild](m4m.framework.transform.md#hasupdatecompchild)
- [inCameraVisible](m4m.framework.transform.md#incameravisible)
- [insId](m4m.framework.transform.md#insid)
- [name](m4m.framework.transform.md#name)
- [needFillRenderer](m4m.framework.transform.md#needfillrenderer)
- [needGpuInstancBatcher](m4m.framework.transform.md#needgpuinstancbatcher)
- [needUpdate](m4m.framework.transform.md#needupdate)
- [onDispose](m4m.framework.transform.md#ondispose)
- [prefab](m4m.framework.transform.md#prefab)
- [worldTranslate](m4m.framework.transform.md#worldtranslate)
- [ClassName](m4m.framework.transform.md#classname)

### Accessors

- [aabb](m4m.framework.transform.md#aabb)
- [beDispose](m4m.framework.transform.md#bedispose)
- [localEulerAngles](m4m.framework.transform.md#localeulerangles)
- [localPosition](m4m.framework.transform.md#localposition)
- [localRotate](m4m.framework.transform.md#localrotate)
- [localScale](m4m.framework.transform.md#localscale)
- [localTranslate](m4m.framework.transform.md#localtranslate)
- [parent](m4m.framework.transform.md#parent)
- [physicsImpostor](m4m.framework.transform.md#physicsimpostor)
- [scene](m4m.framework.transform.md#scene)

### Methods

- [addChild](m4m.framework.transform.md#addchild)
- [addChildAt](m4m.framework.transform.md#addchildat)
- [checkImpact](m4m.framework.transform.md#checkimpact)
- [checkImpactTran](m4m.framework.transform.md#checkimpacttran)
- [clone](m4m.framework.transform.md#clone)
- [dispose](m4m.framework.transform.md#dispose)
- [find](m4m.framework.transform.md#find)
- [getForwardInWorld](m4m.framework.transform.md#getforwardinworld)
- [getLocalMatrix](m4m.framework.transform.md#getlocalmatrix)
- [getRightInWorld](m4m.framework.transform.md#getrightinworld)
- [getUpInWorld](m4m.framework.transform.md#getupinworld)
- [getWorldMatrix](m4m.framework.transform.md#getworldmatrix)
- [getWorldPosition](m4m.framework.transform.md#getworldposition)
- [getWorldRotate](m4m.framework.transform.md#getworldrotate)
- [getWorldScale](m4m.framework.transform.md#getworldscale)
- [getWorldTranslate](m4m.framework.transform.md#getworldtranslate)
- [lookat](m4m.framework.transform.md#lookat)
- [lookatPoint](m4m.framework.transform.md#lookatpoint)
- [markDirty](m4m.framework.transform.md#markdirty)
- [markHaveInitComp](m4m.framework.transform.md#markhaveinitcomp)
- [markHaveOnplayComp](m4m.framework.transform.md#markhaveonplaycomp)
- [markHaveRendererComp](m4m.framework.transform.md#markhaverenderercomp)
- [markHaveUpdateComp](m4m.framework.transform.md#markhaveupdatecomp)
- [removeAllChild](m4m.framework.transform.md#removeallchild)
- [removeChild](m4m.framework.transform.md#removechild)
- [setWorldMatrix](m4m.framework.transform.md#setworldmatrix)
- [setWorldPosition](m4m.framework.transform.md#setworldposition)
- [setWorldRotate](m4m.framework.transform.md#setworldrotate)
- [setWorldScale](m4m.framework.transform.md#setworldscale)
- [updateTran](m4m.framework.transform.md#updatetran)
- [updateWorldTran](m4m.framework.transform.md#updateworldtran)

### Constructors

- [constructor](m4m.framework.transform.md#constructor)

## Properties

### \_parent

• **\_parent**: [`transform`](m4m.framework.transform.md)

**`language`** zh_CN

**`classdesc`**
父物体实例

**`version`** m4m 1.0

#### Defined in

[framework/transform/transform.ts:459](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L459)

___

### children

• **children**: [`transform`](m4m.framework.transform.md)[] = `[]`

**`language`** zh_CN

**`classdesc`**
子物体列表

**`version`** m4m 1.0

#### Defined in

[framework/transform/transform.ts:425](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L425)

___

### dirtiedOfFrustumCulling

• **dirtiedOfFrustumCulling**: `boolean` = `false`

**`language`** zh_CN

**`classdesc`**
对象RTS有变化了,视锥剔除使用

**`version`** m4m 1.0

#### Defined in

[framework/transform/transform.ts:472](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L472)

___

### enableCulling

• **enableCulling**: `boolean` = `true`

**`language`** zh_CN

**`classdesc`**
当前物体视锥剔除开关

**`version`** m4m 1.0

#### Defined in

[framework/transform/transform.ts:490](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L490)

___

### firstCalc

• **firstCalc**: `boolean` = `true`

#### Defined in

[framework/transform/transform.ts:999](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L999)

___

### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh_CN

**`classdesc`**
获取绑定的gameObject

**`version`** m4m 1.0

#### Defined in

[framework/transform/transform.ts:1304](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1304)

___

### hasInitComp

• **hasInitComp**: `boolean` = `false`

自己是否有需要init方法的组件

#### Defined in

[framework/transform/transform.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L45)

___

### hasInitCompChild

• **hasInitCompChild**: `boolean` = `false`

子对象是否有需要init方法的组件

#### Defined in

[framework/transform/transform.ts:47](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L47)

___

### hasOnPlayComp

• **hasOnPlayComp**: `boolean` = `false`

自己是否有需要OnPlay方法的组件

#### Defined in

[framework/transform/transform.ts:49](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L49)

___

### hasOnPlayCompChild

• **hasOnPlayCompChild**: `boolean` = `false`

子对象是否有需要OnPlay方法的组件

#### Defined in

[framework/transform/transform.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L51)

___

### hasRendererComp

• **hasRendererComp**: `boolean` = `false`

自己是否有渲染器组件

#### Defined in

[framework/transform/transform.ts:37](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L37)

___

### hasRendererCompChild

• **hasRendererCompChild**: `boolean` = `false`

子对象是否有渲染器组件

#### Defined in

[framework/transform/transform.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L39)

___

### hasUpdateComp

• **hasUpdateComp**: `boolean` = `false`

自己是否有需要update方法的组件

#### Defined in

[framework/transform/transform.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L41)

___

### hasUpdateCompChild

• **hasUpdateCompChild**: `boolean` = `false`

子对象是否有需要update方法的组件

#### Defined in

[framework/transform/transform.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L43)

___

### inCameraVisible

• **inCameraVisible**: `boolean` = `false`

**`language`** zh_CN

**`classdesc`**
是否在任意摄像机视野内

**`version`** m4m 1.0

#### Defined in

[framework/transform/transform.ts:481](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L481)

___

### insId

• **insId**: [`insID`](m4m.framework.insID.md)

**`language`** zh_CN

**`classdesc`**
transform唯一的insid

**`version`** m4m 1.0

#### Defined in

[framework/transform/transform.ts:134](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L134)

___

### name

• **name**: `string` = `"noname"`

**`language`** zh_CN

**`classdesc`**
transform名称

**`version`** m4m 1.0

#### Defined in

[framework/transform/transform.ts:125](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L125)

___

### needFillRenderer

• **needFillRenderer**: `boolean` = `true`

需要每帧筛查FillRenderer , 设置为false 该节点以及子节点都会跳过FillRenderer 函数的调用（减少消耗）

#### Defined in

[framework/transform/transform.ts:56](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L56)

___

### needGpuInstancBatcher

• **needGpuInstancBatcher**: `boolean` = `false`

需要gpuInstanceBatcher 模式渲染 (减少渲染消耗 , 仅适合静态物)

#### Defined in

[framework/transform/transform.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L58)

___

### needUpdate

• **needUpdate**: `boolean` = `true`

需要每帧调用组件update , 设置为false 该节点以及子节点都会跳过update 函数的调用（减少消耗）

#### Defined in

[framework/transform/transform.ts:54](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L54)

___

### onDispose

• **onDispose**: () => `void`

#### Type declaration

▸ (): `void`

##### Returns

`void`

#### Defined in

[framework/transform/transform.ts:1340](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1340)

___

### prefab

• **prefab**: `string` = `""`

**`language`** zh_CN

**`classdesc`**
当前节点依赖的prefab路径，如果不依赖，则为空

**`version`** m4m 1.0

#### Defined in

[framework/transform/transform.ts:144](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L144)

___

### worldTranslate

• **worldTranslate**: `vector3`

#### Defined in

[framework/transform/transform.ts:951](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L951)

___

### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"transform"`

#### Defined in

[framework/transform/transform.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L15)

## Accessors

### aabb

• `get` **aabb**(): [`aabb`](m4m.framework.aabb.md)

**`language`** zh_CN

**`classdesc`**
自己的aabb

**`version`** m4m 1.0

#### Returns

[`aabb`](m4m.framework.aabb.md)

#### Defined in

[framework/transform/transform.ts:206](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L206)

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

[framework/transform/transform.ts:1334](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1334)

___

### localEulerAngles

• `get` **localEulerAngles**(): `vector3`

**`language`** zh_CN

**`classdesc`**
本地旋转的欧拉角

**`version`** m4m 1.0

#### Returns

`vector3`

#### Defined in

[framework/transform/transform.ts:934](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L934)

• `set` **localEulerAngles**(`angles`): `void`

**`language`** zh_CN

**`classdesc`**
本地旋转的欧拉角

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `angles` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:939](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L939)

___

### localPosition

• `get` **localPosition**(): `vector3`

**`language`** zh_CN

**`classdesc`**
本地位移

**`version`** m4m 1.0

#### Returns

`vector3`

#### Defined in

[framework/transform/transform.ts:890](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L890)

• `set` **localPosition**(`position`): `void`

**`language`** zh_CN

**`classdesc`**
本地位移

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `position` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:894](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L894)

___

### localRotate

• `get` **localRotate**(): `quaternion`

**`language`** zh_CN

**`classdesc`**
本地旋转四元数

**`version`** m4m 1.0

#### Returns

`quaternion`

#### Defined in

[framework/transform/transform.ts:848](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L848)

• `set` **localRotate**(`rotate`): `void`

**`language`** zh_CN

**`classdesc`**
本地旋转四元数

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `rotate` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:852](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L852)

___

### localScale

• `get` **localScale**(): `vector3`

**`language`** zh_CN

**`classdesc`**
本地缩放

**`version`** m4m 1.0

#### Returns

`vector3`

#### Defined in

[framework/transform/transform.ts:912](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L912)

• `set` **localScale**(`scale`): `void`

**`language`** zh_CN

**`classdesc`**
本地缩放

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `scale` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:916](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L916)

___

### localTranslate

• `get` **localTranslate**(): `vector3`

**`language`** zh_CN

**`classdesc`**
本地位移

**`version`** m4m 1.0

#### Returns

`vector3`

#### Defined in

[framework/transform/transform.ts:870](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L870)

• `set` **localTranslate**(`position`): `void`

**`language`** zh_CN

**`classdesc`**
本地位移

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `position` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:874](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L874)

___

### parent

• `get` **parent**(): [`transform`](m4m.framework.transform.md)

#### Returns

[`transform`](m4m.framework.transform.md)

#### Defined in

[framework/transform/transform.ts:460](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L460)

___

### physicsImpostor

• `get` **physicsImpostor**(): [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

**`language`** zh_CN

**`classdesc`**
物理代理对象

**`version`** m4m 1.0

#### Returns

[`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md)

#### Defined in

[framework/transform/transform.ts:443](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L443)

• `set` **physicsImpostor**(`physicsImp`): `void`

**`language`** zh_CN

**`classdesc`**
物理代理对象

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `physicsImp` | [`PhysicsImpostor`](m4m.framework.PhysicsImpostor.md) |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:447](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L447)

___

### scene

• `get` **scene**(): [`scene`](m4m.framework.scene.md)

**`language`** zh_CN

**`classdesc`**
获取所在场景

**`version`** m4m 1.0

#### Returns

[`scene`](m4m.framework.scene.md)

#### Defined in

[framework/transform/transform.ts:107](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L107)

• `set` **scene**(`value`): `void`

**`language`** zh_CN

**`classdesc`**
设置所在场景实例

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | [`scene`](m4m.framework.scene.md) | 场景实例 |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:95](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L95)

## Methods

### addChild

▸ **addChild**(`node`): `void`

**`language`** zh_CN

**`classdesc`**
添加子物体实例

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `node` | [`transform`](m4m.framework.transform.md) | 子物体实例 |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:501](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L501)

___

### addChildAt

▸ **addChildAt**(`node`, `index`): `void`

**`language`** zh_CN

**`classdesc`**
添加子物体实例到索引位置

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `node` | [`transform`](m4m.framework.transform.md) | 场景实例 |
| `index` | `number` | 索引位置 |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:515](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L515)

___

### checkImpact

▸ **checkImpact**(): [`transform`](m4m.framework.transform.md)[]

**`language`** zh_CN

**`classdesc`**
返回场景中所有与当前tranform碰撞的transform

**`version`** m4m 1.0

#### Returns

[`transform`](m4m.framework.transform.md)[]

#### Defined in

[framework/transform/transform.ts:658](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L658)

___

### checkImpactTran

▸ **checkImpactTran**(`tran`): `boolean`

**`language`** zh_CN

**`classdesc`**
判断是否与给定的transform有碰撞

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `tran` | [`transform`](m4m.framework.transform.md) | 指定的transform |

#### Returns

`boolean`

#### Defined in

[framework/transform/transform.ts:644](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L644)

___

### clone

▸ **clone**(): [`transform`](m4m.framework.transform.md)

**`language`** zh_CN

**`classdesc`**
获取当前transform的克隆

**`version`** m4m 1.0

#### Returns

[`transform`](m4m.framework.transform.md)

#### Defined in

[framework/transform/transform.ts:1322](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1322)

___

### dispose

▸ **dispose**(): `void`

**`language`** zh_CN

**`classdesc`**
释放当前transform

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:1348](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1348)

___

### find

▸ **find**(`name`): [`transform`](m4m.framework.transform.md)

**`language`** zh_CN

**`classdesc`**
查找自己以及子物体中是否有指定名称的transform

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`transform`](m4m.framework.transform.md)

#### Defined in

[framework/transform/transform.ts:613](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L613)

___

### getForwardInWorld

▸ **getForwardInWorld**(`out`): `void`

**`language`** zh_CN

**`classdesc`**
获取世界坐标系下当前z轴的朝向

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:1201](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1201)

___

### getLocalMatrix

▸ **getLocalMatrix**(): `matrix`

**`language`** zh_CN

**`classdesc`**
获取本地矩阵

**`version`** m4m 1.0

#### Returns

`matrix`

#### Defined in

[framework/transform/transform.ts:1122](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1122)

___

### getRightInWorld

▸ **getRightInWorld**(`out`): `void`

**`language`** zh_CN

**`classdesc`**
获取世界坐标系下当前x轴的朝向

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:1214](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1214)

___

### getUpInWorld

▸ **getUpInWorld**(`out`): `void`

**`language`** zh_CN

**`classdesc`**
获取世界坐标系下y轴的朝向

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `out` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:1227](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1227)

___

### getWorldMatrix

▸ **getWorldMatrix**(): `matrix`

**`language`** zh_CN

**`classdesc`**
获取世界矩阵

**`version`** m4m 1.0

#### Returns

`matrix`

#### Defined in

[framework/transform/transform.ts:1141](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1141)

___

### getWorldPosition

▸ **getWorldPosition**(): `vector3`

**`language`** zh_CN

**`classdesc`**
获取世界坐标系下的位移

**`version`** m4m 1.0

#### Returns

`vector3`

#### Defined in

[framework/transform/transform.ts:1031](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1031)

___

### getWorldRotate

▸ **getWorldRotate**(): `quaternion`

**`language`** zh_CN

**`classdesc`**
获取世界坐标系下的旋转

**`version`** m4m 1.0

#### Returns

`quaternion`

#### Defined in

[framework/transform/transform.ts:960](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L960)

___

### getWorldScale

▸ **getWorldScale**(): `vector3`

**`language`** zh_CN

**`classdesc`**
获取世界坐标系下的缩放

**`version`** m4m 1.0

#### Returns

`vector3`

#### Defined in

[framework/transform/transform.ts:1076](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1076)

___

### getWorldTranslate

▸ **getWorldTranslate**(): `vector3`

**`language`** zh_CN

**`classdesc`**
获取世界坐标系下的位移

**`version`** m4m 1.0

#### Returns

`vector3`

#### Defined in

[framework/transform/transform.ts:1007](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1007)

___

### lookat

▸ **lookat**(`trans`): `void`

**`language`** zh_CN

**`classdesc`**
旋转当前transform到z轴指向给定transform

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `trans` | [`transform`](m4m.framework.transform.md) | 给定的transform |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:1268](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1268)

___

### lookatPoint

▸ **lookatPoint**(`point`): `void`

**`language`** zh_CN

**`classdesc`**
旋转当前transform到z轴指向给定坐标

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `point` | `vector3` | 给定的坐标 |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:1280](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1280)

___

### markDirty

▸ **markDirty**(): `void`

**`language`** zh_CN

**`classdesc`**
[ 过时接口,现不需要标记变化]

**`version`** m4m 1.0

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:751](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L751)

___

### markHaveInitComp

▸ **markHaveInitComp**(`selfHas?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `selfHas` | `boolean` | `true` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:793](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L793)

___

### markHaveOnplayComp

▸ **markHaveOnplayComp**(`selfHas?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `selfHas` | `boolean` | `true` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:804](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L804)

___

### markHaveRendererComp

▸ **markHaveRendererComp**(`selfHas?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `selfHas` | `boolean` | `true` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:771](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L771)

___

### markHaveUpdateComp

▸ **markHaveUpdateComp**(`selfHas?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `selfHas` | `boolean` | `true` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:782](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L782)

___

### removeAllChild

▸ **removeAllChild**(`needDispose?`): `void`

**`language`** zh_CN

**`classdesc`**
移除所有子物体

**`version`** m4m 1.0

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `needDispose` | `boolean` | `false` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:562](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L562)

___

### removeChild

▸ **removeChild**(`node`): `void`

**`language`** zh_CN

**`classdesc`**
移除指定子物体

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `node` | [`transform`](m4m.framework.transform.md) | 子物体实例 |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:582](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L582)

___

### setWorldMatrix

▸ **setWorldMatrix**(`mat`): `void`

**`language`** zh_CN

**`classdesc`**
设置transform的世界矩阵 通过计算得到本地矩阵实现

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `mat` | `matrix` | 世界空间下矩阵 |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:1241](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1241)

___

### setWorldPosition

▸ **setWorldPosition**(`pos`): `void`

**`language`** zh_CN

**`classdesc`**
设置transform世界空间下的位移

**`version`** m4m 1.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pos` | `vector3` | 世界空间下的坐标 |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:1051](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1051)

___

### setWorldRotate

▸ **setWorldRotate**(`rotate`): `void`

**`language`** zh_CN

**`classdesc`**
设置transform世界空间下的旋转

#### Parameters

| Name | Type |
| :------ | :------ |
| `rotate` | `quaternion` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:979](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L979)

___

### setWorldScale

▸ **setWorldScale**(`scale`): `void`

**`language`** zh_CN

**`classdesc`**
设置世界坐标系下的缩放

**`version`** m4m 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `scale` | `vector3` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:1095](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1095)

___

### updateTran

▸ **updateTran**(`bool`): `void`

[过时接口,完全弃用]

#### Parameters

| Name | Type |
| :------ | :------ |
| `bool` | `boolean` |

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:157](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L157)

___

### updateWorldTran

▸ **updateWorldTran**(): `void`

[过时接口,完全弃用]

#### Returns

`void`

#### Defined in

[framework/transform/transform.ts:149](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L149)

## Constructors

### constructor

• **new transform**()

#### Defined in

[framework/transform/transform.ts:1290](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/transform/transform.ts#L1290)
