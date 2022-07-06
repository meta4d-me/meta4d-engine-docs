# m4m.framework.RVOManager

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / RVOManager

## Class: RVOManager

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).RVOManager

### Table of contents

#### Methods

* [addAgent](m4m.framework.RVOManager.md#addagent)
* [disable](m4m.framework.RVOManager.md#disable)
* [enable](m4m.framework.RVOManager.md#enable)
* [getTransformByKey](m4m.framework.RVOManager.md#gettransformbykey)
* [removeAgent](m4m.framework.RVOManager.md#removeagent)
* [setAttackRange](m4m.framework.RVOManager.md#setattackrange)
* [setRadius](m4m.framework.RVOManager.md#setradius)
* [setRoadPoints](m4m.framework.RVOManager.md#setroadpoints)
* [setSpeed](m4m.framework.RVOManager.md#setspeed)
* [update](m4m.framework.RVOManager.md#update)

#### Properties

* [attackRanges](m4m.framework.RVOManager.md#attackranges)
* [goals](m4m.framework.RVOManager.md#goals)
* [radius](m4m.framework.RVOManager.md#radius)
* [sim](m4m.framework.RVOManager.md#sim)
* [speeds](m4m.framework.RVOManager.md#speeds)
* [transforms](m4m.framework.RVOManager.md#transforms)

#### Constructors

* [constructor](m4m.framework.RVOManager.md#constructor)

### Methods

#### addAgent

▸ **addAgent**(`key`, `transform`, `radius`, `attackRanges`, `speed`): `void`

**Parameters**

| Name           | Type                                      |
| -------------- | ----------------------------------------- |
| `key`          | `number`                                  |
| `transform`    | [`transform`](m4m.framework.transform.md) |
| `radius`       | `number`                                  |
| `attackRanges` | `number`                                  |
| `speed`        | `number`                                  |

**Returns**

`void`

**Defined in**

[framework/navmesh/RVOManager.ts:40](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L40)

***

#### disable

▸ **disable**(): `void`

**Returns**

`void`

**Defined in**

[framework/navmesh/RVOManager.ts:105](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L105)

***

#### enable

▸ **enable**(): `void`

**Returns**

`void`

**Defined in**

[framework/navmesh/RVOManager.ts:109](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L109)

***

#### getTransformByKey

▸ **getTransformByKey**(`key`): [`transform`](m4m.framework.transform.md)

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `key` | `number` |

**Returns**

[`transform`](m4m.framework.transform.md)

**Defined in**

[framework/navmesh/RVOManager.ts:87](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L87)

***

#### removeAgent

▸ **removeAgent**(`key`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `key` | `number` |

**Returns**

`void`

**Defined in**

[framework/navmesh/RVOManager.ts:64](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L64)

***

#### setAttackRange

▸ **setAttackRange**(`id`, `value`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `id`    | `number` |
| `value` | `number` |

**Returns**

`void`

**Defined in**

[framework/navmesh/RVOManager.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L100)

***

#### setRadius

▸ **setRadius**(`id`, `value`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `id`    | `number` |
| `value` | `number` |

**Returns**

`void`

**Defined in**

[framework/navmesh/RVOManager.ts:92](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L92)

***

#### setRoadPoints

▸ **setRoadPoints**(`goalQueue`): `void`

**Parameters**

| Name        | Type         |
| ----------- | ------------ |
| `goalQueue` | `vector3`\[] |

**Returns**

`void`

**Defined in**

[framework/navmesh/RVOManager.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L22)

***

#### setSpeed

▸ **setSpeed**(`id`, `value`): `void`

**Parameters**

| Name    | Type     |
| ------- | -------- |
| `id`    | `number` |
| `value` | `number` |

**Returns**

`void`

**Defined in**

[framework/navmesh/RVOManager.ts:96](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L96)

***

#### update

▸ **update**(): `void`

**Returns**

`void`

**Defined in**

[framework/navmesh/RVOManager.ts:117](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L117)

### Properties

#### attackRanges

• **attackRanges**: `number`\[] = `[]`

**Defined in**

[framework/navmesh/RVOManager.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L11)

***

#### goals

• **goals**: `any`\[] = `[]`

**Defined in**

[framework/navmesh/RVOManager.ts:9](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L9)

***

#### radius

• **radius**: `number`\[] = `[]`

**Defined in**

[framework/navmesh/RVOManager.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L10)

***

#### sim

• **sim**: `any`

**Defined in**

[framework/navmesh/RVOManager.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L6)

***

#### speeds

• **speeds**: `number`\[] = `[]`

**Defined in**

[framework/navmesh/RVOManager.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L12)

***

#### transforms

• **transforms**: [`transform`](m4m.framework.transform.md)\[] = `[]`

**Defined in**

[framework/navmesh/RVOManager.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/navmesh/RVOManager.ts#L8)

### Constructors

#### constructor

• **new RVOManager**()
