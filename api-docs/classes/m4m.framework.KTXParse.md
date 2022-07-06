# m4m.framework.KTXParse

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / KTXParse

## Class: KTXParse

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).KTXParse

for description see https://www.khronos.org/opengles/sdk/tools/KTX/ for file layout see https://www.khronos.org/opengles/sdk/tools/KTX/file\_format\_spec/

ported from https://github.com/BabylonJS/Babylon.js/blob/master/src/Misc/khronosTextureContainer.ts

### Table of contents

#### Constructors

* [constructor](m4m.framework.KTXParse.md#constructor)

#### Methods

* [parse](m4m.framework.KTXParse.md#parse)

### Constructors

#### constructor

• **new KTXParse**()

### Methods

#### parse

▸ `Static` **parse**(`gl`, `arrayBuffer`, `facesExpected?`, `loadMipmaps?`): `glTexture2D`

**Parameters**

| Name            | Type                    | Default value | Description                                                 |
| --------------- | ----------------------- | ------------- | ----------------------------------------------------------- |
| `gl`            | `WebGLRenderingContext` | `undefined`   |                                                             |
| `arrayBuffer`   | `ArrayBuffer`           | `undefined`   | contents of the KTX container file                          |
| `facesExpected` | `number`                | `1`           | should be either 1 or 6, based whether a cube texture or or |
| `loadMipmaps`   | `boolean`               | `true`        | -                                                           |

**Returns**

`glTexture2D`

**Defined in**

[framework/asset/ktx.ts:21](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/ktx.ts#L21)
