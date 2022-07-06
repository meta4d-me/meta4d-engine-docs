# m4m.framework.ASTCParse

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ASTCParse

## Class: ASTCParse

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ASTCParse

astc 格式概述 https://github.com/ARM-software/astc-encoder/blob/main/Docs/FormatOverview.md Khronos Group astc格式规范 https://www.khronos.org/registry/DataFormat/specs/1.3/dataformat.1.3.html#ASTC

### Table of contents

#### Constructors

* [constructor](m4m.framework.ASTCParse.md#constructor)

#### Methods

* [parse](m4m.framework.ASTCParse.md#parse)

### Constructors

#### constructor

• **new ASTCParse**()

### Methods

#### parse

▸ `Static` **parse**(`gl`, `arrayBuffer`): `glTexture2D`

**Parameters**

| Name          | Type                    | Description                         |
| ------------- | ----------------------- | ----------------------------------- |
| `gl`          | `WebGLRenderingContext` | WebGLRenderingContext               |
| `arrayBuffer` | `ArrayBuffer`           | contents of the ASTC container file |

**Returns**

`glTexture2D`

**Defined in**

[framework/asset/astc.ts:25](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/astc.ts#L25)
