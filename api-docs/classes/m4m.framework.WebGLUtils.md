# m4m.framework.WebGLUtils

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / WebGLUtils

## Class: WebGLUtils

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).WebGLUtils

### Table of contents

#### Constructors

* [constructor](m4m.framework.WebGLUtils.md#constructor)

#### Methods

* [create3DContext](m4m.framework.WebGLUtils.md#create3dcontext)
* [setupWebGL](m4m.framework.WebGLUtils.md#setupwebgl)

### Constructors

#### constructor

• **new WebGLUtils**()

**Defined in**

[framework/util/webgl-utils.ts:104](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/webgl-utils.ts#L104)

### Methods

#### create3DContext

▸ **create3DContext**(`canvas`, `opt_attribs`): `any`

Creates a webgl context.

**Parameters**

| Name          | Type  | Description                                                                      |
| ------------- | ----- | -------------------------------------------------------------------------------- |
| `canvas`      | `any` | The canvas tag to get context from. If one is not passed in one will be created. |
| `opt_attribs` | `any` | -                                                                                |

**Returns**

`any`

The created context.

**Defined in**

[framework/util/webgl-utils.ts:90](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/webgl-utils.ts#L90)

***

#### setupWebGL

▸ **setupWebGL**(`canvas`, `opt_attribs?`, `opt_onError?`): `any`

Creates a webgl context. If creation fails it will change the contents of the container of the tag to an error message with the correct links for WebGL.

**Parameters**

| Name          | Type                        | Default value | Description                                               |
| ------------- | --------------------------- | ------------- | --------------------------------------------------------- |
| `canvas`      | `Element`                   | `undefined`   | -                                                         |
| `opt_attribs` | `WebGLContextAttributes`    | `null`        | Any creation attributes you want to pass in.              |
| `opt_onError` | (`msg`: `string`) => `void` | `null`        | An function to call if there is an error during creation. |

**Returns**

`any`

The created context.

**Defined in**

[framework/util/webgl-utils.ts:51](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/webgl-utils.ts#L51)
