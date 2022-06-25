[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [io](../modules/m4m.io.md) / binTool

# Class: binTool

[m4m](../modules/m4m.md).[io](../modules/m4m.io.md).binTool

## Table of contents

### Constructors

- [constructor](m4m.io.binTool.md#constructor)

### Methods

- [dispose](m4m.io.binTool.md#dispose)
- [getBuffer](m4m.io.binTool.md#getbuffer)
- [getBytesAvailable](m4m.io.binTool.md#getbytesavailable)
- [getLength](m4m.io.binTool.md#getlength)
- [getUint8Array](m4m.io.binTool.md#getuint8array)
- [readBoolean](m4m.io.binTool.md#readboolean)
- [readByte](m4m.io.binTool.md#readbyte)
- [readBytes](m4m.io.binTool.md#readbytes)
- [readDouble](m4m.io.binTool.md#readdouble)
- [readFloat](m4m.io.binTool.md#readfloat)
- [readInt](m4m.io.binTool.md#readint)
- [readInt16](m4m.io.binTool.md#readint16)
- [readInt32](m4m.io.binTool.md#readint32)
- [readInt8](m4m.io.binTool.md#readint8)
- [readLong](m4m.io.binTool.md#readlong)
- [readShort](m4m.io.binTool.md#readshort)
- [readSingle](m4m.io.binTool.md#readsingle)
- [readStringAnsi](m4m.io.binTool.md#readstringansi)
- [readStringUtf8](m4m.io.binTool.md#readstringutf8)
- [readStringUtf8FixLength](m4m.io.binTool.md#readstringutf8fixlength)
- [readSymbolByte](m4m.io.binTool.md#readsymbolbyte)
- [readUInt16](m4m.io.binTool.md#readuint16)
- [readUInt32](m4m.io.binTool.md#readuint32)
- [readUInt8](m4m.io.binTool.md#readuint8)
- [readULong](m4m.io.binTool.md#readulong)
- [readUTFByLen](m4m.io.binTool.md#readutfbylen)
- [readUTFBytes](m4m.io.binTool.md#readutfbytes)
- [readUnsignedInt](m4m.io.binTool.md#readunsignedint)
- [readUnsignedShort](m4m.io.binTool.md#readunsignedshort)
- [write](m4m.io.binTool.md#write)
- [writeByte](m4m.io.binTool.md#writebyte)
- [writeBytes](m4m.io.binTool.md#writebytes)
- [writeDouble](m4m.io.binTool.md#writedouble)
- [writeFloat](m4m.io.binTool.md#writefloat)
- [writeInt](m4m.io.binTool.md#writeint)
- [writeInt16](m4m.io.binTool.md#writeint16)
- [writeInt32](m4m.io.binTool.md#writeint32)
- [writeInt8](m4m.io.binTool.md#writeint8)
- [writeLong](m4m.io.binTool.md#writelong)
- [writeShort](m4m.io.binTool.md#writeshort)
- [writeSingle](m4m.io.binTool.md#writesingle)
- [writeStringAnsi](m4m.io.binTool.md#writestringansi)
- [writeStringUtf8](m4m.io.binTool.md#writestringutf8)
- [writeStringUtf8DataOnly](m4m.io.binTool.md#writestringutf8dataonly)
- [writeSymbolByte](m4m.io.binTool.md#writesymbolbyte)
- [writeUInt16](m4m.io.binTool.md#writeuint16)
- [writeUInt32](m4m.io.binTool.md#writeuint32)
- [writeUInt8](m4m.io.binTool.md#writeuint8)
- [writeULong](m4m.io.binTool.md#writeulong)
- [writeUTFBytes](m4m.io.binTool.md#writeutfbytes)
- [writeUint8Array](m4m.io.binTool.md#writeuint8array)
- [writeUnsignedInt](m4m.io.binTool.md#writeunsignedint)
- [writeUnsignedShort](m4m.io.binTool.md#writeunsignedshort)

### Accessors

- [length](m4m.io.binTool.md#length)

### Properties

- [r\_offset](m4m.io.binTool.md#r_offset)
- [w\_offset](m4m.io.binTool.md#w_offset)

## Constructors

### constructor

• **new binTool**(`size?`)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `size` | `number` | `undefined` |

#### Defined in

[framework/io/binBuffer.ts:199](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L199)

## Methods

### dispose

▸ **dispose**(): `void`

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:532](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L532)

___

### getBuffer

▸ **getBuffer**(): `Uint8Array`

#### Returns

`Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:539](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L539)

___

### getBytesAvailable

▸ **getBytesAvailable**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:379](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L379)

___

### getLength

▸ **getLength**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:375](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L375)

___

### getUint8Array

▸ **getUint8Array**(): `Uint8Array`

#### Returns

`Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:546](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L546)

___

### readBoolean

▸ **readBoolean**(): `boolean`

#### Returns

`boolean`

#### Defined in

[framework/io/binBuffer.ts:284](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L284)

___

### readByte

▸ **readByte**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:291](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L291)

___

### readBytes

▸ **readBytes**(`length`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `length` | `number` |

#### Returns

`Uint8Array`

#### Defined in

[framework/io/binBuffer.ts:325](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L325)

___

### readDouble

▸ **readDouble**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:235](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L235)

___

### readFloat

▸ **readFloat**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:306](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L306)

___

### readInt

▸ **readInt**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:321](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L321)

___

### readInt16

▸ **readInt16**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:256](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L256)

___

### readInt32

▸ **readInt32**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:270](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L270)

___

### readInt8

▸ **readInt8**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:242](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L242)

___

### readLong

▸ **readLong**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:221](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L221)

___

### readShort

▸ **readShort**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:317](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L317)

___

### readSingle

▸ **readSingle**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:214](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L214)

___

### readStringAnsi

▸ **readStringAnsi**(): `string`

#### Returns

`string`

#### Defined in

[framework/io/binBuffer.ts:363](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L363)

___

### readStringUtf8

▸ **readStringUtf8**(): `string`

#### Returns

`string`

#### Defined in

[framework/io/binBuffer.ts:332](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L332)

___

### readStringUtf8FixLength

▸ **readStringUtf8FixLength**(`length`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `length` | `number` |

#### Returns

`string`

#### Defined in

[framework/io/binBuffer.ts:356](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L356)

___

### readSymbolByte

▸ **readSymbolByte**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:313](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L313)

___

### readUInt16

▸ **readUInt16**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:263](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L263)

___

### readUInt32

▸ **readUInt32**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:277](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L277)

___

### readUInt8

▸ **readUInt8**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:249](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L249)

___

### readULong

▸ **readULong**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:228](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L228)

___

### readUTFByLen

▸ **readUTFByLen**(`length`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `length` | `number` |

#### Returns

`string`

#### Defined in

[framework/io/binBuffer.ts:349](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L349)

___

### readUTFBytes

▸ **readUTFBytes**(): `string`

#### Returns

`string`

#### Defined in

[framework/io/binBuffer.ts:340](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L340)

___

### readUnsignedInt

▸ **readUnsignedInt**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:299](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L299)

___

### readUnsignedShort

▸ **readUnsignedShort**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:295](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L295)

___

### write

▸ **write**(`array`, `offset?`, `length?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `array` | `any` | `undefined` |
| `offset` | `number` | `0` |
| `length` | `number` | `-1` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:499](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L499)

___

### writeByte

▸ **writeByte**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:449](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L449)

___

### writeBytes

▸ **writeBytes**(`array`, `offset?`, `length?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `array` | `number` \| `number`[] \| `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |
| `length` | `number` | `-1` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:454](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L454)

___

### writeDouble

▸ **writeDouble**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:427](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L427)

___

### writeFloat

▸ **writeFloat**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:474](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L474)

___

### writeInt

▸ **writeInt**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:494](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L494)

___

### writeInt16

▸ **writeInt16**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:398](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L398)

___

### writeInt32

▸ **writeInt32**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:406](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L406)

___

### writeInt8

▸ **writeInt8**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:388](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L388)

___

### writeLong

▸ **writeLong**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:419](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L419)

___

### writeShort

▸ **writeShort**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:489](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L489)

___

### writeSingle

▸ **writeSingle**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:414](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L414)

___

### writeStringAnsi

▸ **writeStringAnsi**(`str`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `str` | `string` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:431](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L431)

___

### writeStringUtf8

▸ **writeStringUtf8**(`str`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `str` | `string` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:438](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L438)

___

### writeStringUtf8DataOnly

▸ **writeStringUtf8DataOnly**(`str`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `str` | `string` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:444](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L444)

___

### writeSymbolByte

▸ **writeSymbolByte**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:484](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L484)

___

### writeUInt16

▸ **writeUInt16**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:402](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L402)

___

### writeUInt32

▸ **writeUInt32**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:410](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L410)

___

### writeUInt8

▸ **writeUInt8**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:393](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L393)

___

### writeULong

▸ **writeULong**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:423](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L423)

___

### writeUTFBytes

▸ **writeUTFBytes**(`str`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `str` | `string` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:479](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L479)

___

### writeUint8Array

▸ **writeUint8Array**(`array`, `offset?`, `length?`): `void`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `array` | `number` \| `number`[] \| `Uint8Array` | `undefined` |
| `offset` | `number` | `0` |
| `length` | `number` | `-1` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:459](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L459)

___

### writeUnsignedInt

▸ **writeUnsignedInt**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:469](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L469)

___

### writeUnsignedShort

▸ **writeUnsignedShort**(`num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `number` |

#### Returns

`void`

#### Defined in

[framework/io/binBuffer.ts:464](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L464)

## Accessors

### length

• `get` **length**(): `number`

#### Returns

`number`

#### Defined in

[framework/io/binBuffer.ts:383](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L383)

## Properties

### r\_offset

• **r\_offset**: `number` = `0`

#### Defined in

[framework/io/binBuffer.ts:197](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L197)

___

### w\_offset

• **w\_offset**: `number` = `0`

#### Defined in

[framework/io/binBuffer.ts:198](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/io/binBuffer.ts#L198)
