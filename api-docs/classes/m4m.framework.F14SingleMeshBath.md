# m4m.framework.F14SingleMeshBath

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14SingleMeshBath

## Class: F14SingleMeshBath

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14SingleMeshBath

### Implements

* [`F14Basebatch`](../interfaces/m4m.framework.F14Basebatch.md)

### Table of contents

#### Properties

* [ElementMat](m4m.framework.F14SingleMeshBath.md#elementmat)
* [colors](m4m.framework.F14SingleMeshBath.md#colors)
* [curIndexCount](m4m.framework.F14SingleMeshBath.md#curindexcount)
* [curRealVboCount](m4m.framework.F14SingleMeshBath.md#currealvbocount)
* [curVertexcount](m4m.framework.F14SingleMeshBath.md#curvertexcount)
* [dataForEbo](m4m.framework.F14SingleMeshBath.md#dataforebo)
* [dataForVbo](m4m.framework.F14SingleMeshBath.md#dataforvbo)
* [effect](m4m.framework.F14SingleMeshBath.md#effect)
* [indices](m4m.framework.F14SingleMeshBath.md#indices)
* [meshlist](m4m.framework.F14SingleMeshBath.md#meshlist)
* [type](m4m.framework.F14SingleMeshBath.md#type)
* [uv](m4m.framework.F14SingleMeshBath.md#uv)
* [vertexLength](m4m.framework.F14SingleMeshBath.md#vertexlength)
* [vertices](m4m.framework.F14SingleMeshBath.md#vertices)

#### Methods

* [OnEndCollectElement](m4m.framework.F14SingleMeshBath.md#onendcollectelement)
* [addElement](m4m.framework.F14SingleMeshBath.md#addelement)
* [canBatch](m4m.framework.F14SingleMeshBath.md#canbatch)
* [dispose](m4m.framework.F14SingleMeshBath.md#dispose)
* [getElementCount](m4m.framework.F14SingleMeshBath.md#getelementcount)
* [reInit](m4m.framework.F14SingleMeshBath.md#reinit)
* [render](m4m.framework.F14SingleMeshBath.md#render)
* [unRender](m4m.framework.F14SingleMeshBath.md#unrender)

#### Constructors

* [constructor](m4m.framework.F14SingleMeshBath.md#constructor)

### Properties

#### ElementMat

• **ElementMat**: [`material`](m4m.framework.material.md)

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L21)

***

#### colors

• **colors**: `color`\[] = `[]`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L29)

***

#### curIndexCount

• **curIndexCount**: `number` = `0`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:41](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L41)

***

#### curRealVboCount

• **curRealVboCount**: `number` = `0`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:39](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L39)

***

#### curVertexcount

• **curVertexcount**: `number` = `0`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L40)

***

#### dataForEbo

• **dataForEbo**: `Uint16Array`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:35](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L35)

***

#### dataForVbo

• **dataForVbo**: `Float32Array`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:34](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L34)

***

#### effect

• **effect**: [`f14EffectSystem`](m4m.framework.f14EffectSystem.md)

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[effect](../interfaces/m4m.framework.F14Basebatch.md#effect)

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L19)

***

#### indices

• **indices**: `number`\[] = `[]`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:27](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L27)

***

#### meshlist

• **meshlist**: [`F14SingleMesh`](m4m.framework.F14SingleMesh.md)\[] = `[]`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:23](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L23)

***

#### type

• **type**: [`F14TypeEnum`](../enums/m4m.framework.F14TypeEnum.md)

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[type](../interfaces/m4m.framework.F14Basebatch.md#type)

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L18)

***

#### uv

• **uv**: `vector2`\[] = `[]`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:30](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L30)

***

#### vertexLength

• **vertexLength**: `number` = `0`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L43)

***

#### vertices

• **vertices**: `vector3`\[] = `[]`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L28)

### Methods

#### OnEndCollectElement

▸ **OnEndCollectElement**(): `void`

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:53](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L53)

***

#### addElement

▸ **addElement**(`mesh`, `insert?`): `void`

**Parameters**

| Name     | Type                                              | Default value |
| -------- | ------------------------------------------------- | ------------- |
| `mesh`   | [`F14SingleMesh`](m4m.framework.F14SingleMesh.md) | `undefined`   |
| `insert` | `boolean`                                         | `false`       |

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L121)

***

#### canBatch

▸ **canBatch**(`mesh`): `boolean`

**Parameters**

| Name   | Type                                              |
| ------ | ------------------------------------------------- |
| `mesh` | [`F14SingleMesh`](m4m.framework.F14SingleMesh.md) |

**Returns**

`boolean`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:126](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L126)

***

#### dispose

▸ **dispose**(): `void`

**Returns**

`void`

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[dispose](../interfaces/m4m.framework.F14Basebatch.md#dispose)

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:266](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L266)

***

#### getElementCount

▸ **getElementCount**(): `number`

**Returns**

`number`

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[getElementCount](../interfaces/m4m.framework.F14Basebatch.md#getelementcount)

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:138](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L138)

***

#### reInit

▸ **reInit**(`mat`, `effect`): `void`

**Parameters**

| Name     | Type                                                  |
| -------- | ----------------------------------------------------- |
| `mat`    | [`material`](m4m.framework.material.md)               |
| `effect` | [`f14EffectSystem`](m4m.framework.f14EffectSystem.md) |

**Returns**

`void`

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:114](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L114)

***

#### render

▸ **render**(`context`, `assetmgr`, `camera`, `Effqueue`): `void`

**Parameters**

| Name       | Type                                    |
| ---------- | --------------------------------------- |
| `context`  | `renderContext`                         |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |
| `camera`   | [`camera`](m4m.framework.camera.md)     |
| `Effqueue` | `number`                                |

**Returns**

`void`

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[render](../interfaces/m4m.framework.F14Basebatch.md#render)

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:147](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L147)

***

#### unRender

▸ **unRender**(): `void`

**Returns**

`void`

**Implementation of**

[F14Basebatch](../interfaces/m4m.framework.F14Basebatch.md).[unRender](../interfaces/m4m.framework.F14Basebatch.md#unrender)

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:263](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L263)

### Constructors

#### constructor

• **new F14SingleMeshBath**(`mat`, `effect`)

**Parameters**

| Name     | Type                                                  |
| -------- | ----------------------------------------------------- |
| `mat`    | [`material`](m4m.framework.material.md)               |
| `effect` | [`f14EffectSystem`](m4m.framework.f14EffectSystem.md) |

**Defined in**

[framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts:45](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/singlemesh/f14singlemeshbatch.ts#L45)
