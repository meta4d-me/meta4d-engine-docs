# m4m.framework.bloomctr

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / bloomctr

## Class: bloomctr

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).bloomctr

**`language`** zh\_CN

**`classdesc`** Bloom后期效果 控制器

**`version`** m4m 1.0

### Implements

* [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

### Table of contents

#### Accessors

* [bloomIntensity](m4m.framework.bloomctr.md#bloomintensity)
* [bloomThreshold](m4m.framework.bloomctr.md#bloomthreshold)
* [blurSpread](m4m.framework.bloomctr.md#blurspread)

#### Constructors

* [constructor](m4m.framework.bloomctr.md#constructor)

#### Properties

* [gameObject](m4m.framework.bloomctr.md#gameobject)
* [ClassName](m4m.framework.bloomctr.md#classname)

#### Methods

* [onPlay](m4m.framework.bloomctr.md#onplay)
* [start](m4m.framework.bloomctr.md#start)
* [update](m4m.framework.bloomctr.md#update)

### Accessors

#### bloomIntensity

• `get` **bloomIntensity**(): `number`

**`language`** zh\_CN

**`classdesc`** 强度 - 附加光（影响到该特效的光源）的全局光强

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/component/bloomctr.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L43)

• `set` **bloomIntensity**(`value`): `void`

**`language`** zh\_CN

**`classdesc`** 强度 - 附加光（影响到该特效的光源）的全局光强

**`version`** m4m 1.0

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `value` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/bloomctr.ts:44](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L44)

***

#### bloomThreshold

• `get` **bloomThreshold**(): `number`

**`language`** zh\_CN

**`classdesc`** 发光阈值 - 图像中亮度高于该阈值的区域将产生泛光效果

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/component/bloomctr.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L28)

• `set` **bloomThreshold**(`value`): `void`

**`language`** zh\_CN

**`classdesc`** 发光阈值 - 图像中亮度高于该阈值的区域将产生泛光效果

**`version`** m4m 1.0

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `value` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/bloomctr.ts:29](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L29)

***

#### blurSpread

• `get` **blurSpread**(): `number`

**`language`** zh\_CN

**`classdesc`** 模糊扩散 - Frag down sample 的偏移距离

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/component/bloomctr.ts:58](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L58)

• `set` **blurSpread**(`value`): `void`

**`language`** zh\_CN

**`classdesc`** 模糊扩散 - Frag down sample 的偏移距离

**`version`** m4m 1.0

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `value` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/bloomctr.ts:59](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L59)

### Constructors

#### constructor

• **new bloomctr**()

### Properties

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**`language`** zh\_CN

**`classdesc`** 挂载的gameobject

**`version`** m4m 1.0

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[gameObject](../interfaces/m4m.framework.INodeComponent.md#gameobject)

**Defined in**

[framework/component/bloomctr.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L88)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"bloomctr"`

**Defined in**

[framework/component/bloomctr.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L14)

### Methods

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

**Defined in**

[framework/component/bloomctr.ts:198](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L198)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

**Defined in**

[framework/component/bloomctr.ts:191](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L191)

***

#### update

▸ **update**(`delta`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `delta` | `number` |

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[update](../interfaces/m4m.framework.INodeComponent.md#update)

**Defined in**

[framework/component/bloomctr.ts:203](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/bloomctr.ts#L203)
