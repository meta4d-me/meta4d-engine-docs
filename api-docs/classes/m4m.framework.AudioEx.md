# m4m.framework.AudioEx

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / AudioEx

## Class: AudioEx

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).AudioEx

### Table of contents

#### Properties

* [audioContext](m4m.framework.AudioEx.md#audiocontext)

#### Methods

* [clickInit](m4m.framework.AudioEx.md#clickinit)
* [createAudioChannel](m4m.framework.AudioEx.md#createaudiochannel)
* [isAvailable](m4m.framework.AudioEx.md#isavailable)
* [loadAudioBuffer](m4m.framework.AudioEx.md#loadaudiobuffer)
* [loadAudioBufferFromArrayBuffer](m4m.framework.AudioEx.md#loadaudiobufferfromarraybuffer)
* [instance](m4m.framework.AudioEx.md#instance)

### Properties

#### audioContext

• **audioContext**: `AudioContext`

**Defined in**

[framework/audio/audioex.ts:14](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L14)

### Methods

#### clickInit

▸ **clickInit**(): `void`

**`language`** zh\_CN

**`classdesc`** 初始化声音api，注意：在ios上面必须手动点击某个按钮来调用初始化，否则无法播放声音

**`version`** m4m 1.0

**Returns**

`void`

**Defined in**

[framework/audio/audioex.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L36)

***

#### createAudioChannel

▸ **createAudioChannel**(`be3DSound`): [`AudioChannel`](m4m.framework.AudioChannel.md)

**Parameters**

| Name        | Type      |
| ----------- | --------- |
| `be3DSound` | `boolean` |

**Returns**

[`AudioChannel`](m4m.framework.AudioChannel.md)

**Defined in**

[framework/audio/audioex.ts:113](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L113)

***

#### isAvailable

▸ **isAvailable**(): `boolean`

**`language`** zh\_CN

**`classdesc`** 初始化声音api，注意：在ios上面必须手动点击某个按钮来调用初始化，否则无法播放声音

**`version`** m4m 1.0

**Returns**

`boolean`

**Defined in**

[framework/audio/audioex.ts:107](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L107)

***

#### loadAudioBuffer

▸ **loadAudioBuffer**(`url`, `fun`): `void`

**`language`** zh\_CN

**`classdesc`** 从本地文件加载音频数据，返回audiobuffer

**`version`** m4m 1.0

**Parameters**

| Name  | Type                                              | Description |
| ----- | ------------------------------------------------- | ----------- |
| `url` | `string`                                          | 文件地址        |
| `fun` | (`buf`: `AudioBuffer`, `_err`: `Error`) => `void` |             |

**Returns**

`void`

**Defined in**

[framework/audio/audioex.ts:83](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L83)

***

#### loadAudioBufferFromArrayBuffer

▸ **loadAudioBufferFromArrayBuffer**(`ab`, `fun`): `void`

**`language`** zh\_CN

**`classdesc`** 从arraybuffer转成audiobuffer

**`version`** m4m 1.0

**Parameters**

| Name  | Type                                              | Description |
| ----- | ------------------------------------------------- | ----------- |
| `ab`  | `ArrayBuffer`                                     | 二进制声音数据     |
| `fun` | (`buf`: `AudioBuffer`, `_err`: `Error`) => `void` |             |

**Returns**

`void`

**Defined in**

[framework/audio/audioex.ts:66](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L66)

***

#### instance

▸ `Static` **instance**(): [`AudioEx`](m4m.framework.AudioEx.md)

**Returns**

[`AudioEx`](m4m.framework.AudioEx.md)

**Defined in**

[framework/audio/audioex.ts:6](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/audio/audioex.ts#L6)
