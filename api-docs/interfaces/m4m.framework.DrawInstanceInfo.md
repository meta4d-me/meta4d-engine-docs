# m4m.framework.DrawInstanceInfo

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / DrawInstanceInfo

## Interface: DrawInstanceInfo

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).DrawInstanceInfo

批量渲染相关接口

### Implemented by

* [`meshGpuInstanceDrawInfo`](../classes/m4m.framework.meshGpuInstanceDrawInfo.md)

### Table of contents

#### Methods

* [activeAttributes](m4m.framework.DrawInstanceInfo.md#activeattributes)
* [disableAttributes](m4m.framework.DrawInstanceInfo.md#disableattributes)
* [initBuffer](m4m.framework.DrawInstanceInfo.md#initbuffer)

#### Properties

* [instanceCount](m4m.framework.DrawInstanceInfo.md#instancecount)

### Methods

#### activeAttributes

▸ **activeAttributes**(`gl`, `pass`): `void`

启用批量渲染相关顶点属性

**Parameters**

| Name   | Type                    |
| ------ | ----------------------- |
| `gl`   | `WebGLRenderingContext` |
| `pass` | `glDrawPass`            |

**Returns**

`void`

**Defined in**

[framework/asset/resource/material.ts:42](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L42)

***

#### disableAttributes

▸ **disableAttributes**(`gl`, `pass`): `void`

禁用批量渲染相关顶点属性

**Parameters**

| Name   | Type                    |
| ------ | ----------------------- |
| `gl`   | `WebGLRenderingContext` |
| `pass` | `glDrawPass`            |

**Returns**

`void`

**Defined in**

[framework/asset/resource/material.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L46)

***

#### initBuffer

▸ **initBuffer**(`gl`): `void`

初始化Buffer

**Parameters**

| Name | Type                    |
| ---- | ----------------------- |
| `gl` | `WebGLRenderingContext` |

**Returns**

`void`

**Defined in**

[framework/asset/resource/material.ts:38](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L38)

### Properties

#### instanceCount

• **instanceCount**: `number`

渲染数量

**Defined in**

[framework/asset/resource/material.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/resource/material.ts#L32)
