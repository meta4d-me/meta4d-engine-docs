# m4m.framework.AudioChannel

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AudioChannel

## Class: AudioChannel

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AudioChannel

### Table of contents

#### Constructors

* [constructor](m4m.framework.AudioChannel.md#constructor)

#### Properties

* [gainNode](m4m.framework.AudioChannel.md#gainnode)
* [isplay](m4m.framework.AudioChannel.md#isplay)
* [pannerNode](m4m.framework.AudioChannel.md#pannernode)
* [source](m4m.framework.AudioChannel.md#source)

#### Methods

* [stop](m4m.framework.AudioChannel.md#stop)

#### Accessors

* [volume](m4m.framework.AudioChannel.md#volume)

### Constructors

#### constructor

• **new AudioChannel**()

### Properties

#### gainNode

• **gainNode**: `GainNode`

**Defined in**

[framework/audio/audioex.ts:173](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L173)

***

#### isplay

• **isplay**: `boolean`

**Defined in**

[framework/audio/audioex.ts:200](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L200)

***

#### pannerNode

• **pannerNode**: `PannerNode`

**Defined in**

[framework/audio/audioex.ts:174](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L174)

***

#### source

• **source**: `AudioBufferSourceNode`

**Defined in**

[framework/audio/audioex.ts:172](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L172)

### Methods

#### stop

▸ **stop**(): `void`

**`language`** zh\_CN

**`classdesc`** 停止播放声音

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/audio/audioex.ts:208](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L208)

### Accessors

#### volume

• `get` **volume**(): `number`

**`language`** zh\_CN

**`classdesc`** 获取音量大小

**`version`** m4m 1.0

**Returns**

`number`

**Defined in**

[framework/audio/audioex.ts:182](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L182)

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

[framework/audio/audioex.ts:194](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L194)
