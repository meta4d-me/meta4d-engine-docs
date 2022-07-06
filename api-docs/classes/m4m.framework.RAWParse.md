# m4m.framework.RAWParse

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / RAWParse

## Class: RAWParse

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).RAWParse

### Table of contents

#### Constructors

* [constructor](m4m.framework.RAWParse.md#constructor)

#### Methods

* [parse](m4m.framework.RAWParse.md#parse)
* [parseByAtt](m4m.framework.RAWParse.md#parsebyatt)

### Constructors

#### constructor

• **new RAWParse**()

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

[framework/asset/raw.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/raw.ts#L18)

***

#### parseByAtt

▸ `Static` **parseByAtt**(`gl`, `arrayBuffer`, `_mipmap?`, `_linear?`, `_premultiplyAlpha?`, `_repeat?`): `glTexture2D`

解析纹理 通过参数

**Parameters**

| Name                | Type                    | Default value |
| ------------------- | ----------------------- | ------------- |
| `gl`                | `WebGLRenderingContext` | `undefined`   |
| `arrayBuffer`       | `ArrayBuffer`           | `undefined`   |
| `_mipmap`           | `boolean`               | `true`        |
| `_linear`           | `boolean`               | `true`        |
| `_premultiplyAlpha` | `boolean`               | `false`       |
| `_repeat`           | `boolean`               | `false`       |

**Returns**

`glTexture2D`

**Defined in**

[framework/asset/raw.ts:32](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/raw.ts#L32)
