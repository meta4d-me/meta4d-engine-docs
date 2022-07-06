# m4m.framework.AudioPlayer

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AudioPlayer

## Class: AudioPlayer

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AudioPlayer

### Implements

* [`INodeComponent`](../interfaces/m4m.framework.INodeComponent.md)

### Table of contents

#### Properties

* [be3DSound](m4m.framework.AudioPlayer.md#be3dsound)
* [beLoop](m4m.framework.AudioPlayer.md#beloop)
* [buffer](m4m.framework.AudioPlayer.md#buffer)
* [gameObject](m4m.framework.AudioPlayer.md#gameobject)
* [ClassName](m4m.framework.AudioPlayer.md#classname)

#### Methods

* [clone](m4m.framework.AudioPlayer.md#clone)
* [isPlaying](m4m.framework.AudioPlayer.md#isplaying)
* [onPlay](m4m.framework.AudioPlayer.md#onplay)
* [play](m4m.framework.AudioPlayer.md#play)
* [remove](m4m.framework.AudioPlayer.md#remove)
* [start](m4m.framework.AudioPlayer.md#start)
* [stop](m4m.framework.AudioPlayer.md#stop)
* [update](m4m.framework.AudioPlayer.md#update)

#### Constructors

* [constructor](m4m.framework.AudioPlayer.md#constructor)

#### Accessors

* [volume](m4m.framework.AudioPlayer.md#volume)

### Properties

#### be3DSound

• **be3DSound**: `boolean` = `true`

**Defined in**

[framework/component/audioplayer.ts:12](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L12)

***

#### beLoop

• **beLoop**: `boolean`

**Defined in**

[framework/component/audioplayer.ts:11](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L11)

***

#### buffer

• **buffer**: `AudioBuffer`

**Defined in**

[framework/component/audioplayer.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L10)

***

#### gameObject

• **gameObject**: [`gameObject`](m4m.framework.gameObject.md)

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[gameObject](../interfaces/m4m.framework.INodeComponent.md#gameobject)

**Defined in**

[framework/component/audioplayer.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L14)

***

#### ClassName

▪ `Static` `Readonly` **ClassName**: `string` = `"AudioPlayer"`

**Defined in**

[framework/component/audioplayer.ts:8](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L8)

### Methods

#### clone

▸ **clone**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[clone](../interfaces/m4m.framework.INodeComponent.md#clone)

**Defined in**

[framework/component/audioplayer.ts:145](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L145)

***

#### isPlaying

▸ **isPlaying**(): `boolean`

**`language`** zh\_CN

**`classdesc`** 获得当前音频播放器是否在播放

**`version`** m4m 1.0

**Returns**

`boolean`

**Defined in**

[framework/component/audioplayer.ts:112](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L112)

***

#### onPlay

▸ **onPlay**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[onPlay](../interfaces/m4m.framework.INodeComponent.md#onplay)

**Defined in**

[framework/component/audioplayer.ts:121](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L121)

***

#### play

▸ **play**(`buffer`, `beLoop?`, `volume?`, `onended?`): `void`

**`language`** zh\_CN

**`classdesc`** 播放声音

**Parameters**

| Name       | Type          | Default value | Description |
| ---------- | ------------- | ------------- | ----------- |
| `buffer`   | `AudioBuffer` | `undefined`   | 音源缓冲对象      |
| `beLoop`   | `boolean`     | `false`       | 是循环播放       |
| `volume`   | `number`      | `0`           | 音量 0-1      |
| `onended?` | `Function`    | `undefined`   | 音源播放结束回调    |

**Returns**

`void`

**Defined in**

[framework/component/audioplayer.ts:26](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L26)

***

#### remove

▸ **remove**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[remove](../interfaces/m4m.framework.INodeComponent.md#remove)

**Defined in**

[framework/component/audioplayer.ts:141](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L141)

***

#### start

▸ **start**(): `void`

**Returns**

`void`

**Implementation of**

[INodeComponent](../interfaces/m4m.framework.INodeComponent.md).[start](../interfaces/m4m.framework.INodeComponent.md#start)

**Defined in**

[framework/component/audioplayer.ts:116](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L116)

***

#### stop

▸ **stop**(): `void`

**`language`** zh\_CN

**`classdesc`** 停止播放

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/component/audioplayer.ts:74](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L74)

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

[framework/component/audioplayer.ts:130](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L130)

### Constructors

#### constructor

• **new AudioPlayer**()

### Accessors

#### volume

• `get` **volume**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取音量大小

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/component/audioplayer.ts:88](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L88)

• `set` **volume**(`val`): `void`

**`language`** zh\_CN

**`classdesc`** 设置音量大小

**`version`** m4m 1.0

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `val` | `number` |

**Returns**

`void`

**Defined in**

[framework/component/audioplayer.ts:100](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/component/audioplayer.ts#L100)
