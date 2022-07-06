# m4m.io.binTool

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [io](../modules/m4m.io.md) / binTool

## Class: binTool

[m4m](../modules/m4m.md).[io](../modules/m4m.io.md).binTool

### Table of contents

#### Constructors

* [constructor](m4m.io.binTool.md#constructor)

#### Methods

* [dispose](m4m.io.binTool.md#dispose)
* [getBuffer](m4m.io.binTool.md#getbuffer)
* [getBytesAvailable](m4m.io.binTool.md#getbytesavailable)
* [getLength](m4m.io.binTool.md#getlength)
* [getUint8Array](m4m.io.binTool.md#getuint8array)
* [readBoolean](m4m.io.binTool.md#readboolean)
* [readByte](m4m.io.binTool.md#readbyte)
* [readBytes](m4m.io.binTool.md#readbytes)
* [readDouble](m4m.io.binTool.md#readdouble)
* [readFloat](m4m.io.binTool.md#readfloat)
* [readInt](m4m.io.binTool.md#readint)
* [readInt16](m4m.io.binTool.md#readint16)
* [readInt32](m4m.io.binTool.md#readint32)
* [readInt8](m4m.io.binTool.md#readint8)
* [readLong](m4m.io.binTool.md#readlong)
* [readShort](m4m.io.binTool.md#readshort)
* [readSingle](m4m.io.binTool.md#readsingle)
* [readStringAnsi](m4m.io.binTool.md#readstringansi)
* [readStringUtf8](m4m.io.binTool.md#readstringutf8)
* [readStringUtf8FixLength](m4m.io.binTool.md#readstringutf8fixlength)
* [readSymbolByte](m4m.io.binTool.md#readsymbolbyte)
* [readUInt16](m4m.io.binTool.md#readuint16)
* [readUInt32](m4m.io.binTool.md#readuint32)
* [readUInt8](m4m.io.binTool.md#readuint8)
* [readULong](m4m.io.binTool.md#readulong)
* [readUTFByLen](m4m.io.binTool.md#readutfbylen)
* [readUTFBytes](m4m.io.binTool.md#readutfbytes)
* [readUnsignedInt](m4m.io.binTool.md#readunsignedint)
* [readUnsignedShort](m4m.io.binTool.md#readunsignedshort)
* [write](m4m.io.binTool.md#write)
* [writeByte](m4m.io.binTool.md#writebyte)
* [writeBytes](m4m.io.binTool.md#writebytes)
* [writeDouble](m4m.io.binTool.md#writedouble)
* [writeFloat](m4m.io.binTool.md#writefloat)
* [writeInt](m4m.io.binTool.md#writeint)
* [writeInt16](m4m.io.binTool.md#writeint16)
* [writeInt32](m4m.io.binTool.md#writeint32)
* [writeInt8](m4m.io.binTool.md#writeint8)
* [writeLong](m4m.io.binTool.md#writelong)
* [writeShort](m4m.io.binTool.md#writeshort)
* [writeSingle](m4m.io.binTool.md#writesingle)
* [writeStringAnsi](m4m.io.binTool.md#writestringansi)
* [writeStringUtf8](m4m.io.binTool.md#writestringutf8)
* [writeStringUtf8DataOnly](m4m.io.binTool.md#writestringutf8dataonly)
* [writeSymbolByte](m4m.io.binTool.md#writesymbolbyte)
* [writeUInt16](m4m.io.binTool.md#writeuint16)
* [writeUInt32](m4m.io.binTool.md#writeuint32)
* [writeUInt8](m4m.io.binTool.md#writeuint8)
* [writeULong](m4m.io.binTool.md#writeulong)
* [writeUTFBytes](m4m.io.binTool.md#writeutfbytes)
* [writeUint8Array](m4m.io.binTool.md#writeuint8array)
* [writeUnsignedInt](m4m.io.binTool.md#writeunsignedint)
* [writeUnsignedShort](m4m.io.binTool.md#writeunsignedshort)

#### Accessors

* [length](m4m.io.binTool.md#length)

#### Properties

* [r\_offset](m4m.io.binTool.md#r\_offset)
* [w\_offset](m4m.io.binTool.md#w\_offset)

### Constructors

#### constructor

• **new binTool**(`size?`)

**Parameters**

| Name   | Type     | Default value |
| ------ | -------- | ------------- |
| `size` | `number` | `undefined`   |

**Defined in**

[framework/io/binBuffer.ts:199](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L199)

### Methods

#### dispose

▸ **dispose**(): `void`

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:532](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L532)

***

#### getBuffer

▸ **getBuffer**(): `Uint8Array`

**Returns**

`Uint8Array`

**Defined in**

[framework/io/binBuffer.ts:539](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L539)

***

#### getBytesAvailable

▸ **getBytesAvailable**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:379](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L379)

***

#### getLength

▸ **getLength**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:375](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L375)

***

#### getUint8Array

▸ **getUint8Array**(): `Uint8Array`

**Returns**

`Uint8Array`

**Defined in**

[framework/io/binBuffer.ts:546](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L546)

***

#### readBoolean

▸ **readBoolean**(): `boolean`

**Returns**

`boolean`

**Defined in**

[framework/io/binBuffer.ts:284](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L284)

***

#### readByte

▸ **readByte**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:291](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L291)

***

#### readBytes

▸ **readBytes**(`length`): `Uint8Array`

**Parameters**

| Name     | Type     |
| -------- | -------- |
| `length` | `number` |

**Returns**

`Uint8Array`

**Defined in**

[framework/io/binBuffer.ts:325](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L325)

***

#### readDouble

▸ **readDouble**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:235](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L235)

***

#### readFloat

▸ **readFloat**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:306](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L306)

***

#### readInt

▸ **readInt**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:321](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L321)

***

#### readInt16

▸ **readInt16**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:256](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L256)

***

#### readInt32

▸ **readInt32**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:270](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L270)

***

#### readInt8

▸ **readInt8**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:242](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L242)

***

#### readLong

▸ **readLong**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:221](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L221)

***

#### readShort

▸ **readShort**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:317](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L317)

***

#### readSingle

▸ **readSingle**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:214](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L214)

***

#### readStringAnsi

▸ **readStringAnsi**(): `string`

**Returns**

`string`

**Defined in**

[framework/io/binBuffer.ts:363](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L363)

***

#### readStringUtf8

▸ **readStringUtf8**(): `string`

**Returns**

`string`

**Defined in**

[framework/io/binBuffer.ts:332](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L332)

***

#### readStringUtf8FixLength

▸ **readStringUtf8FixLength**(`length`): `string`

**Parameters**

| Name     | Type     |
| -------- | -------- |
| `length` | `number` |

**Returns**

`string`

**Defined in**

[framework/io/binBuffer.ts:356](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L356)

***

#### readSymbolByte

▸ **readSymbolByte**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:313](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L313)

***

#### readUInt16

▸ **readUInt16**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:263](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L263)

***

#### readUInt32

▸ **readUInt32**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:277](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L277)

***

#### readUInt8

▸ **readUInt8**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:249](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L249)

***

#### readULong

▸ **readULong**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:228](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L228)

***

#### readUTFByLen

▸ **readUTFByLen**(`length`): `string`

**Parameters**

| Name     | Type     |
| -------- | -------- |
| `length` | `number` |

**Returns**

`string`

**Defined in**

[framework/io/binBuffer.ts:349](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L349)

***

#### readUTFBytes

▸ **readUTFBytes**(): `string`

**Returns**

`string`

**Defined in**

[framework/io/binBuffer.ts:340](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L340)

***

#### readUnsignedInt

▸ **readUnsignedInt**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:299](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L299)

***

#### readUnsignedShort

▸ **readUnsignedShort**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:295](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L295)

***

#### write

▸ **write**(`array`, `offset?`, `length?`): `void`

**Parameters**

| Name     | Type     | Default value |
| -------- | -------- | ------------- |
| `array`  | `any`    | `undefined`   |
| `offset` | `number` | `0`           |
| `length` | `number` | `-1`          |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:499](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L499)

***

#### writeByte

▸ **writeByte**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:449](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L449)

***

#### writeBytes

▸ **writeBytes**(`array`, `offset?`, `length?`): `void`

**Parameters**

| Name     | Type                                    | Default value |
| -------- | --------------------------------------- | ------------- |
| `array`  | `number` \| `number`\[] \| `Uint8Array` | `undefined`   |
| `offset` | `number`                                | `0`           |
| `length` | `number`                                | `-1`          |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:454](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L454)

***

#### writeDouble

▸ **writeDouble**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:427](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L427)

***

#### writeFloat

▸ **writeFloat**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:474](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L474)

***

#### writeInt

▸ **writeInt**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:494](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L494)

***

#### writeInt16

▸ **writeInt16**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:398](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L398)

***

#### writeInt32

▸ **writeInt32**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:406](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L406)

***

#### writeInt8

▸ **writeInt8**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:388](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L388)

***

#### writeLong

▸ **writeLong**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:419](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L419)

***

#### writeShort

▸ **writeShort**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:489](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L489)

***

#### writeSingle

▸ **writeSingle**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:414](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L414)

***

#### writeStringAnsi

▸ **writeStringAnsi**(`str`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `str` | `string` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:431](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L431)

***

#### writeStringUtf8

▸ **writeStringUtf8**(`str`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `str` | `string` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:438](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L438)

***

#### writeStringUtf8DataOnly

▸ **writeStringUtf8DataOnly**(`str`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `str` | `string` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:444](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L444)

***

#### writeSymbolByte

▸ **writeSymbolByte**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:484](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L484)

***

#### writeUInt16

▸ **writeUInt16**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:402](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L402)

***

#### writeUInt32

▸ **writeUInt32**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:410](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L410)

***

#### writeUInt8

▸ **writeUInt8**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:393](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L393)

***

#### writeULong

▸ **writeULong**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:423](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L423)

***

#### writeUTFBytes

▸ **writeUTFBytes**(`str`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `str` | `string` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:479](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L479)

***

#### writeUint8Array

▸ **writeUint8Array**(`array`, `offset?`, `length?`): `void`

**Parameters**

| Name     | Type                                    | Default value |
| -------- | --------------------------------------- | ------------- |
| `array`  | `number` \| `number`\[] \| `Uint8Array` | `undefined`   |
| `offset` | `number`                                | `0`           |
| `length` | `number`                                | `-1`          |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:459](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L459)

***

#### writeUnsignedInt

▸ **writeUnsignedInt**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:469](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L469)

***

#### writeUnsignedShort

▸ **writeUnsignedShort**(`num`): `void`

**Parameters**

| Name  | Type     |
| ----- | -------- |
| `num` | `number` |

**Returns**

`void`

**Defined in**

[framework/io/binBuffer.ts:464](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L464)

### Accessors

#### length

• `get` **length**(): `number`

**Returns**

`number`

**Defined in**

[framework/io/binBuffer.ts:383](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L383)

### Properties

#### r\_offset

• **r\_offset**: `number` = `0`

**Defined in**

[framework/io/binBuffer.ts:197](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L197)

***

#### w\_offset

• **w\_offset**: `number` = `0`

**Defined in**

[framework/io/binBuffer.ts:198](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L198)
