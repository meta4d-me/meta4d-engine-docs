[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IMotorEnabledJoint

# Interface: IMotorEnabledJoint

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IMotorEnabledJoint

Interface for a motor enabled joint

## Implemented by

- [`MotorEnabledJoint`](../classes/m4m.framework.MotorEnabledJoint.md)

## Table of contents

### Properties

- [physicsJoint](m4m.framework.IMotorEnabledJoint.md#physicsjoint)

### Methods

- [setLimit](m4m.framework.IMotorEnabledJoint.md#setlimit)
- [setMotor](m4m.framework.IMotorEnabledJoint.md#setmotor)

## Properties

### physicsJoint

• **physicsJoint**: `any`

#### Defined in

[framework/physics3d/physicJoint.ts:232](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L232)

## Methods

### setLimit

▸ **setLimit**(`upperLimit`, `lowerLimit?`, `motorIndex?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `upperLimit` | `number` |
| `lowerLimit?` | `number` |
| `motorIndex?` | `number` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicJoint.ts:234](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L234)

___

### setMotor

▸ **setMotor**(`force?`, `maxForce?`, `motorIndex?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `force?` | `number` |
| `maxForce?` | `number` |
| `motorIndex?` | `number` |

#### Returns

`void`

#### Defined in

[framework/physics3d/physicJoint.ts:233](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L233)
