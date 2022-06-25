[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / INodeComponent

# Interface: INodeComponent

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).INodeComponent

**`language`** zh_CN

**`classdesc`**
组件实例接口

**`version`** m4m 1.0

## Hierarchy

- **`INodeComponent`**

  ↳ [`IRenderer`](m4m.framework.IRenderer.md)

## Implemented by

- [`AudioListener`](../classes/m4m.framework.AudioListener.md)
- [`AudioPlayer`](../classes/m4m.framework.AudioPlayer.md)
- [`BeBillboard`](../classes/m4m.framework.BeBillboard.md)
- [`aniplayer`](../classes/m4m.framework.aniplayer.md)
- [`asbone`](../classes/m4m.framework.asbone.md)
- [`behaviour`](../classes/m4m.framework.behaviour.md)
- [`bloomctr`](../classes/m4m.framework.bloomctr.md)
- [`boxcollider`](../classes/m4m.framework.boxcollider.md)
- [`camera`](../classes/m4m.framework.camera.md)
- [`canvascontainer`](../classes/m4m.framework.canvascontainer.md)
- [`frustumculling`](../classes/m4m.framework.frustumculling.md)
- [`guidpath`](../classes/m4m.framework.guidpath.md)
- [`keyFrameAniPlayer`](../classes/m4m.framework.keyFrameAniPlayer.md)
- [`light`](../classes/m4m.framework.light.md)
- [`meshFilter`](../classes/m4m.framework.meshFilter.md)
- [`meshcollider`](../classes/m4m.framework.meshcollider.md)
- [`spherecollider`](../classes/m4m.framework.spherecollider.md)
- [`starCamCtr`](../classes/m4m.framework.starCamCtr.md)
- [`vignettingCtr`](../classes/m4m.framework.vignettingCtr.md)

## Table of contents

### Methods

- [clone](m4m.framework.INodeComponent.md#clone)
- [onPlay](m4m.framework.INodeComponent.md#onplay)
- [remove](m4m.framework.INodeComponent.md#remove)
- [start](m4m.framework.INodeComponent.md#start)
- [update](m4m.framework.INodeComponent.md#update)

### Properties

- [gameObject](m4m.framework.INodeComponent.md#gameobject)

## Methods

### clone

▸ **clone**(): `any`

#### Returns

`any`

#### Defined in

[framework/interfaces.ts:20](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L20)

___

### onPlay

▸ **onPlay**(): `any`

#### Returns

`any`

#### Defined in

[framework/interfaces.ts:15](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L15)

___

### remove

▸ **remove**(): `any`

#### Returns

`any`

#### Defined in

[framework/interfaces.ts:19](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L19)

___

### start

▸ **start**(): `any`

#### Returns

`any`

#### Defined in

[framework/interfaces.ts:16](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L16)

___

### update

▸ **update**(`delta`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta` | `number` |

#### Returns

`any`

#### Defined in

[framework/interfaces.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L17)

## Properties

### gameObject

• **gameObject**: [`gameObject`](../classes/m4m.framework.gameObject.md)

#### Defined in

[framework/interfaces.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/interfaces.ts#L18)
