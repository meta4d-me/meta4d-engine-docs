[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / IEngine2DOP

# Interface: IEngine2DOP

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).IEngine2DOP

## Table of contents

### Properties

- [broadphase](m4m.framework.IEngine2DOP.md#broadphase)
- [constraintIterations](m4m.framework.IEngine2DOP.md#constraintiterations)
- [enableSleeping](m4m.framework.IEngine2DOP.md#enablesleeping)
- [positionIterations](m4m.framework.IEngine2DOP.md#positioniterations)
- [runnerFps](m4m.framework.IEngine2DOP.md#runnerfps)
- [runnerIsFixed](m4m.framework.IEngine2DOP.md#runnerisfixed)
- [timing](m4m.framework.IEngine2DOP.md#timing)
- [velocityIterations](m4m.framework.IEngine2DOP.md#velocityiterations)

## Properties

### broadphase

• `Optional` **broadphase**: `Object`

默认值 : {bucketWidth: 48, bucketHeight: 48}

#### Type declaration

| Name | Type |
| :------ | :------ |
| `bucketHeight` | `number` |
| `bucketWidth` | `number` |

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:22](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L22)

___

### constraintIterations

• `Optional` **constraintIterations**: `number`

默认值 ： 2

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L17)

___

### enableSleeping

• `Optional` **enableSleeping**: `boolean`

默认值 : fales

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L19)

___

### positionIterations

• `Optional` **positionIterations**: `number`

默认值 ： 6

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:13](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L13)

___

### runnerFps

• `Optional` **runnerFps**: `any`

循环器的设定帧率 , 默认值 : 60

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L24)

___

### runnerIsFixed

• `Optional` **runnerIsFixed**: `any`

循环器是否应使用固定的timestep（deltaTime），默认值：false

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L26)

___

### timing

• `Optional` **timing**: [`Itiming`](m4m.framework.Itiming.md)

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L20)

___

### velocityIterations

• `Optional` **velocityIterations**: `number`

默认值 ： 4

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L15)
