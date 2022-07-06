# m4m.framework.F14RefElement

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / F14RefElement

## Class: F14RefElement

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).F14RefElement

### Implements

* [`F14Element`](../interfaces/m4m.framework.F14Element.md)

### Table of contents

#### Methods

* [OnEndOnceLoop](m4m.framework.F14RefElement.md#onendonceloop)
* [changeAlpha](m4m.framework.F14RefElement.md#changealpha)
* [changeColor](m4m.framework.F14RefElement.md#changecolor)
* [dispose](m4m.framework.F14RefElement.md#dispose)
* [reset](m4m.framework.F14RefElement.md#reset)
* [update](m4m.framework.F14RefElement.md#update)

#### Properties

* [RefEffect](m4m.framework.F14RefElement.md#refeffect)
* [baseddata](m4m.framework.F14RefElement.md#baseddata)
* [drawActive](m4m.framework.F14RefElement.md#drawactive)
* [effect](m4m.framework.F14RefElement.md#effect)
* [endFrame](m4m.framework.F14RefElement.md#endframe)
* [layer](m4m.framework.F14RefElement.md#layer)
* [startFrame](m4m.framework.F14RefElement.md#startframe)
* [type](m4m.framework.F14RefElement.md#type)

#### Constructors

* [constructor](m4m.framework.F14RefElement.md#constructor)

### Methods

#### OnEndOnceLoop

▸ **OnEndOnceLoop**(): `void`

**Returns**

`void`

**Implementation of**

[F14Element](../interfaces/m4m.framework.F14Element.md).[OnEndOnceLoop](../interfaces/m4m.framework.F14Element.md#onendonceloop)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:104](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L104)

***

#### changeAlpha

▸ **changeAlpha**(`value`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `value` | `number` |

**Returns**

`void`

**Implementation of**

[F14Element](../interfaces/m4m.framework.F14Element.md).[changeAlpha](../interfaces/m4m.framework.F14Element.md#changealpha)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L112)

***

#### changeColor

▸ **changeColor**(`value`): `void`

**Parameters**

| Name    | Type    |
| ------- | ------- |
| `value` | `color` |

**Returns**

`void`

**Implementation of**

[F14Element](../interfaces/m4m.framework.F14Element.md).[changeColor](../interfaces/m4m.framework.F14Element.md#changecolor)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:108](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L108)

***

#### dispose

▸ **dispose**(): `void`

**Returns**

`void`

**Implementation of**

[F14Element](../interfaces/m4m.framework.F14Element.md).[dispose](../interfaces/m4m.framework.F14Element.md#dispose)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L116)

***

#### reset

▸ **reset**(): `void`

**Returns**

`void`

**Implementation of**

[F14Element](../interfaces/m4m.framework.F14Element.md).[reset](../interfaces/m4m.framework.F14Element.md#reset)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:46](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L46)

***

#### update

▸ **update**(`deltaTime`, `frame`, `fps`): `void`

**Parameters**

| Name        | Type     |
| ----------- | -------- |
| `deltaTime` | `number` |
| `frame`     | `number` |
| `fps`       | `number` |

**Returns**

`void`

**Implementation of**

[F14Element](../interfaces/m4m.framework.F14Element.md).[update](../interfaces/m4m.framework.F14Element.md#update)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:70](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L70)

### Properties

#### RefEffect

• **RefEffect**: [`f14EffectSystem`](m4m.framework.f14EffectSystem.md)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:43](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L43)

***

#### baseddata

• **baseddata**: [`F14RefBaseData`](m4m.framework.F14RefBaseData.md)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L9)

***

#### drawActive

• **drawActive**: `boolean`

**Implementation of**

[F14Element](../interfaces/m4m.framework.F14Element.md).[drawActive](../interfaces/m4m.framework.F14Element.md#drawactive)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L8)

***

#### effect

• **effect**: [`f14EffectSystem`](m4m.framework.f14EffectSystem.md)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L14)

***

#### endFrame

• **endFrame**: `number`

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L12)

***

#### layer

• **layer**: [`F14Layer`](m4m.framework.F14Layer.md)

**Implementation of**

[F14Element](../interfaces/m4m.framework.F14Element.md).[layer](../interfaces/m4m.framework.F14Element.md#layer)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:7](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L7)

***

#### startFrame

• **startFrame**: `number`

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L11)

***

#### type

• **type**: [`F14TypeEnum`](../enums/m4m.framework.F14TypeEnum.md)

**Implementation of**

[F14Element](../interfaces/m4m.framework.F14Element.md).[type](../interfaces/m4m.framework.F14Element.md#type)

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L6)

### Constructors

#### constructor

• **new F14RefElement**(`effect`, `layer`, `bundleName`)

**Parameters**

| Name         | Type                                                  |
| ------------ | ----------------------------------------------------- |
| `effect`     | [`f14EffectSystem`](m4m.framework.f14EffectSystem.md) |
| `layer`      | [`F14Layer`](m4m.framework.F14Layer.md)               |
| `bundleName` | `string`                                              |

**Defined in**

[framework/component/f14effectsystem/refelement/f14refelement.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/f14effectsystem/refelement/f14refelement.ts#L15)
