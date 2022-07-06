# m4m.render.glTextureCube

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [render](../modules/m4m.render.md) / glTextureCube

## Class: glTextureCube

[m4m](../modules/m4m.md).[render](../modules/m4m.render.md).glTextureCube

### Implements

* `ITexture`

### Table of contents

#### Methods

* [caclByteLength](m4m.render.glTextureCube.md#caclbytelength)
* [dispose](m4m.render.glTextureCube.md#dispose)
* [isFrameBuffer](m4m.render.glTextureCube.md#isframebuffer)
* [uploadImages](m4m.render.glTextureCube.md#uploadimages)

#### Constructors

* [constructor](m4m.render.glTextureCube.md#constructor)

#### Properties

* [format](m4m.render.glTextureCube.md#format)
* [height](m4m.render.glTextureCube.md#height)
* [linear](m4m.render.glTextureCube.md#linear)
* [loaded](m4m.render.glTextureCube.md#loaded)
* [mipmap](m4m.render.glTextureCube.md#mipmap)
* [texture](m4m.render.glTextureCube.md#texture)
* [webgl](m4m.render.glTextureCube.md#webgl)
* [width](m4m.render.glTextureCube.md#width)

### Methods

#### caclByteLength

▸ **caclByteLength**(): `number`

**Returns**

`number`

**Implementation of**

ITexture.caclByteLength

**Defined in**

[render/resource/texture.ts:769](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L769)

***

#### dispose

▸ **dispose**(`webgl`): `void`

**Parameters**

| Name    | Type                    |
| ------- | ----------------------- |
| `webgl` | `WebGLRenderingContext` |

**Returns**

`void`

**Implementation of**

ITexture.dispose

**Defined in**

[render/resource/texture.ts:784](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L784)

***

#### isFrameBuffer

▸ **isFrameBuffer**(): `boolean`

**Returns**

`boolean`

**Implementation of**

ITexture.isFrameBuffer

**Defined in**

[render/resource/texture.ts:790](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L790)

***

#### uploadImages

▸ **uploadImages**(`Texture_NEGATIVE_X`, `Texture_NEGATIVE_Y`, `Texture_NEGATIVE_Z`, `Texture_POSITIVE_X`, `Texture_POSITIVE_Y`, `Texture_POSITIVE_Z`, `min?`, `max?`, `mipmap?`): `void`

**Parameters**

| Name                 | Type                                  | Default value                   |
| -------------------- | ------------------------------------- | ------------------------------- |
| `Texture_NEGATIVE_X` | [`texture`](m4m.framework.texture.md) | `undefined`                     |
| `Texture_NEGATIVE_Y` | [`texture`](m4m.framework.texture.md) | `undefined`                     |
| `Texture_NEGATIVE_Z` | [`texture`](m4m.framework.texture.md) | `undefined`                     |
| `Texture_POSITIVE_X` | [`texture`](m4m.framework.texture.md) | `undefined`                     |
| `Texture_POSITIVE_Y` | [`texture`](m4m.framework.texture.md) | `undefined`                     |
| `Texture_POSITIVE_Z` | [`texture`](m4m.framework.texture.md) | `undefined`                     |
| `min`                | `number`                              | `WebGLRenderingContext.NEAREST` |
| `max`                | `number`                              | `WebGLRenderingContext.NEAREST` |
| `mipmap`             | `number`                              | `null`                          |

**Returns**

`void`

**Defined in**

[render/resource/texture.ts:618](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L618)

### Constructors

#### constructor

• **new glTextureCube**(`webgl`, `format?`, `mipmap?`, `linear?`)

**Parameters**

| Name     | Type                    | Default value            |
| -------- | ----------------------- | ------------------------ |
| `webgl`  | `WebGLRenderingContext` | `undefined`              |
| `format` | `TextureFormatEnum`     | `TextureFormatEnum.RGBA` |
| `mipmap` | `boolean`               | `false`                  |
| `linear` | `boolean`               | `true`                   |

**Defined in**

[render/resource/texture.ts:607](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L607)

### Properties

#### format

• **format**: `TextureFormatEnum`

**Defined in**

[render/resource/texture.ts:764](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L764)

***

#### height

• **height**: `number` = `0`

**Implementation of**

ITexture.height

**Defined in**

[render/resource/texture.ts:766](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L766)

***

#### linear

• **linear**: `boolean` = `false`

**Defined in**

[render/resource/texture.ts:768](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L768)

***

#### loaded

• **loaded**: `boolean` = `false`

**Defined in**

[render/resource/texture.ts:762](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L762)

***

#### mipmap

• **mipmap**: `boolean` = `false`

**Defined in**

[render/resource/texture.ts:767](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L767)

***

#### texture

• **texture**: `WebGLTexture`

**Implementation of**

ITexture.texture

**Defined in**

[render/resource/texture.ts:763](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L763)

***

#### webgl

• **webgl**: `WebGLRenderingContext`

**Defined in**

[render/resource/texture.ts:760](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L760)

***

#### width

• **width**: `number` = `0`

**Implementation of**

ITexture.width

**Defined in**

[render/resource/texture.ts:765](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/render/resource/texture.ts#L765)
