# m4m.framework.F14Element

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14Element

## Interface: F14Element

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14Element

### Implemented by

* [`F14Emission`](../classes/m4m.framework.F14Emission.md)
* [`F14RefElement`](../classes/m4m.framework.F14RefElement.md)
* [`F14SingleMesh`](../classes/m4m.framework.F14SingleMesh.md)

### Table of contents

#### Methods

* [OnEndOnceLoop](m4m.framework.F14Element.md#onendonceloop)
* [changeAlpha](m4m.framework.F14Element.md#changealpha)
* [changeColor](m4m.framework.F14Element.md#changecolor)
* [dispose](m4m.framework.F14Element.md#dispose)
* [reset](m4m.framework.F14Element.md#reset)
* [update](m4m.framework.F14Element.md#update)

#### Properties

* [drawActive](m4m.framework.F14Element.md#drawactive)
* [layer](m4m.framework.F14Element.md#layer)
* [type](m4m.framework.F14Element.md#type)

### Methods

#### OnEndOnceLoop

▸ **OnEndOnceLoop**(): `any`

**Returns**

`any`

**Defined in**

[framework/component/f14effectsystem/f14element.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14element.ts#L15)

***

#### changeAlpha

▸ **changeAlpha**(`value`): `any`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `value` | `number` |

**Returns**

`any`

**Defined in**

[framework/component/f14effectsystem/f14element.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14element.ts#L17)

***

#### changeColor

▸ **changeColor**(`value`): `any`

**Parameters**

| Name    | Type    |
| ------- | ------- |
| `value` | `color` |

**Returns**

`any`

**Defined in**

[framework/component/f14effectsystem/f14element.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14element.ts#L16)

***

#### dispose

▸ **dispose**(): `any`

**Returns**

`any`

**Defined in**

[framework/component/f14effectsystem/f14element.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14element.ts#L13)

***

#### reset

▸ **reset**(): `any`

**Returns**

`any`

**Defined in**

[framework/component/f14effectsystem/f14element.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14element.ts#L14)

***

#### update

▸ **update**(`deltaTime`, `frame`, `fps`): `any`

**Parameters**

| Name        | Type     |
| ----------- | -------- |
| `deltaTime` | `number` |
| `frame`     | `number` |
| `fps`       | `number` |

**Returns**

`any`

**Defined in**

[framework/component/f14effectsystem/f14element.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14element.ts#L12)

### Properties

#### drawActive

• **drawActive**: `boolean`

**Defined in**

[framework/component/f14effectsystem/f14element.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14element.ts#L19)

***

#### layer

• **layer**: [`F14Layer`](../classes/m4m.framework.F14Layer.md)

**Defined in**

[framework/component/f14effectsystem/f14element.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14element.ts#L18)

***

#### type

• **type**: [`F14TypeEnum`](../enums/m4m.framework.F14TypeEnum.md)

**Defined in**

[framework/component/f14effectsystem/f14element.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/f14element.ts#L11)
