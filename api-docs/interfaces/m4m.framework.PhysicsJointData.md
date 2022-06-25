[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / PhysicsJointData

# Interface: PhysicsJointData

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).PhysicsJointData

## Hierarchy

- **`PhysicsJointData`**

  ↳ [`DistanceJointData`](m4m.framework.DistanceJointData.md)

  ↳ [`SpringJointData`](m4m.framework.SpringJointData.md)

## Table of contents

### Properties

- [collision](m4m.framework.PhysicsJointData.md#collision)
- [connectedAxis](m4m.framework.PhysicsJointData.md#connectedaxis)
- [connectedPivot](m4m.framework.PhysicsJointData.md#connectedpivot)
- [mainAxis](m4m.framework.PhysicsJointData.md#mainaxis)
- [mainPivot](m4m.framework.PhysicsJointData.md#mainpivot)
- [nativeParams](m4m.framework.PhysicsJointData.md#nativeparams)

## Properties

### collision

• `Optional` **collision**: `boolean`

The collision of the joint

#### Defined in

[framework/physics3d/physicJoint.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L24)

___

### connectedAxis

• `Optional` **connectedAxis**: `vector3`

The connected axis of the joint

#### Defined in

[framework/physics3d/physicJoint.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L20)

___

### connectedPivot

• `Optional` **connectedPivot**: `vector3`

The connected pivot of the joint

#### Defined in

[framework/physics3d/physicJoint.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L12)

___

### mainAxis

• `Optional` **mainAxis**: `vector3`

The main axis of the joint

#### Defined in

[framework/physics3d/physicJoint.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L16)

___

### mainPivot

• `Optional` **mainPivot**: `vector3`

The main pivot of the joint

#### Defined in

[framework/physics3d/physicJoint.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L8)

___

### nativeParams

• `Optional` **nativeParams**: `any`

Native Oimo/Cannon/Energy data

#### Defined in

[framework/physics3d/physicJoint.ts:28](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/physics3d/physicJoint.ts#L28)
