# m4m.framework.WebGLDebugUtils

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / WebGLDebugUtils

## Class: WebGLDebugUtils

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).WebGLDebugUtils

### Table of contents

#### Constructors

* [constructor](m4m.framework.WebGLDebugUtils.md#constructor)

#### Methods

* [makeDebugContext](m4m.framework.WebGLDebugUtils.md#makedebugcontext)

#### Properties

* [glValidEnumContexts](m4m.framework.WebGLDebugUtils.md#glvalidenumcontexts)

### Constructors

#### constructor

• **new WebGLDebugUtils**()

### Methods

#### makeDebugContext

▸ **makeDebugContext**(`ctx`, `opt_onErrorFunc?`): `WebGLRenderingContext`

Given a WebGL context returns a wrapped context that calls gl.getError after every command and calls a function if the result is not gl.NO\_ERROR.

**Parameters**

| Name              | Type                                                       | Default value | Description                                                                                                                     |
| ----------------- | ---------------------------------------------------------- | ------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| `ctx`             | `WebGLRenderingContext`                                    | `undefined`   | The webgl context to wrap.                                                                                                      |
| `opt_onErrorFunc` | (`err`: `any`, `funcName`: `any`, `args`: `any`) => `void` | `null`        | The function to call when gl.getError returns an error. If not specified the default function calls console.log with a message. |

**Returns**

`WebGLRenderingContext`

**Defined in**

[framework/util/webgl-debug.ts:184](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/webgl-debug.ts#L184)

### Properties

#### glValidEnumContexts

▪ `Static` `Readonly` **glValidEnumContexts**: `Object`

Which arguements are enums.

**Type declaration**

| Name                                  | Type                                                                                           |
| ------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `activeTexture`                       | { `0`: `boolean` = true }                                                                      |
| `activeTexture.0`                     | `boolean`                                                                                      |
| `bindBuffer`                          | { `0`: `boolean` = true }                                                                      |
| `bindBuffer.0`                        | `boolean`                                                                                      |
| `bindFramebuffer`                     | { `0`: `boolean` = true }                                                                      |
| `bindFramebuffer.0`                   | `boolean`                                                                                      |
| `bindRenderbuffer`                    | { `0`: `boolean` = true }                                                                      |
| `bindRenderbuffer.0`                  | `boolean`                                                                                      |
| `bindTexture`                         | { `0`: `boolean` = true }                                                                      |
| `bindTexture.0`                       | `boolean`                                                                                      |
| `blendEquation`                       | { `0`: `boolean` = true }                                                                      |
| `blendEquation.0`                     | `boolean`                                                                                      |
| `blendEquationSeparate`               | { `0`: `boolean` = true; `1`: `boolean` = true }                                               |
| `blendEquationSeparate.0`             | `boolean`                                                                                      |
| `blendEquationSeparate.1`             | `boolean`                                                                                      |
| `blendFunc`                           | { `0`: `boolean` = true; `1`: `boolean` = true }                                               |
| `blendFunc.0`                         | `boolean`                                                                                      |
| `blendFunc.1`                         | `boolean`                                                                                      |
| `blendFuncSeparate`                   | { `0`: `boolean` = true; `1`: `boolean` = true; `2`: `boolean` = true; `3`: `boolean` = true } |
| `blendFuncSeparate.0`                 | `boolean`                                                                                      |
| `blendFuncSeparate.1`                 | `boolean`                                                                                      |
| `blendFuncSeparate.2`                 | `boolean`                                                                                      |
| `blendFuncSeparate.3`                 | `boolean`                                                                                      |
| `bufferData`                          | { `0`: `boolean` = true; `2`: `boolean` = true }                                               |
| `bufferData.0`                        | `boolean`                                                                                      |
| `bufferData.2`                        | `boolean`                                                                                      |
| `bufferSubData`                       | { `0`: `boolean` = true }                                                                      |
| `bufferSubData.0`                     | `boolean`                                                                                      |
| `checkFramebufferStatus`              | { `0`: `boolean` = true }                                                                      |
| `checkFramebufferStatus.0`            | `boolean`                                                                                      |
| `clear`                               | { `0`: `boolean` = true }                                                                      |
| `clear.0`                             | `boolean`                                                                                      |
| `copyTexImage2D`                      | { `0`: `boolean` = true; `2`: `boolean` = true }                                               |
| `copyTexImage2D.0`                    | `boolean`                                                                                      |
| `copyTexImage2D.2`                    | `boolean`                                                                                      |
| `copyTexSubImage2D`                   | { `0`: `boolean` = true }                                                                      |
| `copyTexSubImage2D.0`                 | `boolean`                                                                                      |
| `createShader`                        | { `0`: `boolean` = true }                                                                      |
| `createShader.0`                      | `boolean`                                                                                      |
| `cullFace`                            | { `0`: `boolean` = true }                                                                      |
| `cullFace.0`                          | `boolean`                                                                                      |
| `depthFunc`                           | { `0`: `boolean` = true }                                                                      |
| `depthFunc.0`                         | `boolean`                                                                                      |
| `disable`                             | { `0`: `boolean` = true }                                                                      |
| `disable.0`                           | `boolean`                                                                                      |
| `drawArrays`                          | { `0`: `boolean` = true }                                                                      |
| `drawArrays.0`                        | `boolean`                                                                                      |
| `drawElements`                        | { `0`: `boolean` = true; `2`: `boolean` = true }                                               |
| `drawElements.0`                      | `boolean`                                                                                      |
| `drawElements.2`                      | `boolean`                                                                                      |
| `enable`                              | { `0`: `boolean` = true }                                                                      |
| `enable.0`                            | `boolean`                                                                                      |
| `framebufferRenderbuffer`             | { `0`: `boolean` = true; `1`: `boolean` = true; `2`: `boolean` = true }                        |
| `framebufferRenderbuffer.0`           | `boolean`                                                                                      |
| `framebufferRenderbuffer.1`           | `boolean`                                                                                      |
| `framebufferRenderbuffer.2`           | `boolean`                                                                                      |
| `framebufferTexture2D`                | { `0`: `boolean` = true; `1`: `boolean` = true; `2`: `boolean` = true }                        |
| `framebufferTexture2D.0`              | `boolean`                                                                                      |
| `framebufferTexture2D.1`              | `boolean`                                                                                      |
| `framebufferTexture2D.2`              | `boolean`                                                                                      |
| `frontFace`                           | { `0`: `boolean` = true }                                                                      |
| `frontFace.0`                         | `boolean`                                                                                      |
| `generateMipmap`                      | { `0`: `boolean` = true }                                                                      |
| `generateMipmap.0`                    | `boolean`                                                                                      |
| `getBufferParameter`                  | { `0`: `boolean` = true; `1`: `boolean` = true }                                               |
| `getBufferParameter.0`                | `boolean`                                                                                      |
| `getBufferParameter.1`                | `boolean`                                                                                      |
| `getFramebufferAttachmentParameter`   | { `0`: `boolean` = true; `1`: `boolean` = true; `2`: `boolean` = true }                        |
| `getFramebufferAttachmentParameter.0` | `boolean`                                                                                      |
| `getFramebufferAttachmentParameter.1` | `boolean`                                                                                      |
| `getFramebufferAttachmentParameter.2` | `boolean`                                                                                      |
| `getParameter`                        | { `0`: `boolean` = true }                                                                      |
| `getParameter.0`                      | `boolean`                                                                                      |
| `getProgramParameter`                 | { `1`: `boolean` = true }                                                                      |
| `getProgramParameter.1`               | `boolean`                                                                                      |
| `getRenderbufferParameter`            | { `0`: `boolean` = true; `1`: `boolean` = true }                                               |
| `getRenderbufferParameter.0`          | `boolean`                                                                                      |
| `getRenderbufferParameter.1`          | `boolean`                                                                                      |
| `getShaderParameter`                  | { `1`: `boolean` = true }                                                                      |
| `getShaderParameter.1`                | `boolean`                                                                                      |
| `getTexParameter`                     | { `0`: `boolean` = true; `1`: `boolean` = true }                                               |
| `getTexParameter.0`                   | `boolean`                                                                                      |
| `getTexParameter.1`                   | `boolean`                                                                                      |
| `getVertexAttrib`                     | { `1`: `boolean` = true }                                                                      |
| `getVertexAttrib.1`                   | `boolean`                                                                                      |
| `pixelStorei`                         | { `0`: `boolean` = true; `1`: `boolean` = true }                                               |
| `pixelStorei.0`                       | `boolean`                                                                                      |
| `pixelStorei.1`                       | `boolean`                                                                                      |
| `readPixels`                          | { `4`: `boolean` = true; `5`: `boolean` = true }                                               |
| `readPixels.4`                        | `boolean`                                                                                      |
| `readPixels.5`                        | `boolean`                                                                                      |
| `renderbufferStorage`                 | { `0`: `boolean` = true; `1`: `boolean` = true }                                               |
| `renderbufferStorage.0`               | `boolean`                                                                                      |
| `renderbufferStorage.1`               | `boolean`                                                                                      |
| `stencilFunc`                         | { `0`: `boolean` = true }                                                                      |
| `stencilFunc.0`                       | `boolean`                                                                                      |
| `stencilFuncSeparate`                 | { `0`: `boolean` = true; `1`: `boolean` = true }                                               |
| `stencilFuncSeparate.0`               | `boolean`                                                                                      |
| `stencilFuncSeparate.1`               | `boolean`                                                                                      |
| `stencilMaskSeparate`                 | { `0`: `boolean` = true }                                                                      |
| `stencilMaskSeparate.0`               | `boolean`                                                                                      |
| `stencilOp`                           | { `0`: `boolean` = true; `1`: `boolean` = true; `2`: `boolean` = true }                        |
| `stencilOp.0`                         | `boolean`                                                                                      |
| `stencilOp.1`                         | `boolean`                                                                                      |
| `stencilOp.2`                         | `boolean`                                                                                      |
| `stencilOpSeparate`                   | { `0`: `boolean` = true; `1`: `boolean` = true; `2`: `boolean` = true; `3`: `boolean` = true } |
| `stencilOpSeparate.0`                 | `boolean`                                                                                      |
| `stencilOpSeparate.1`                 | `boolean`                                                                                      |
| `stencilOpSeparate.2`                 | `boolean`                                                                                      |
| `stencilOpSeparate.3`                 | `boolean`                                                                                      |
| `texImage2D`                          | { `0`: `boolean` = true; `2`: `boolean` = true; `6`: `boolean` = true; `7`: `boolean` = true } |
| `texImage2D.0`                        | `boolean`                                                                                      |
| `texImage2D.2`                        | `boolean`                                                                                      |
| `texImage2D.6`                        | `boolean`                                                                                      |
| `texImage2D.7`                        | `boolean`                                                                                      |
| `texParameterf`                       | { `0`: `boolean` = true; `1`: `boolean` = true }                                               |
| `texParameterf.0`                     | `boolean`                                                                                      |
| `texParameterf.1`                     | `boolean`                                                                                      |
| `texParameteri`                       | { `0`: `boolean` = true; `1`: `boolean` = true; `2`: `boolean` = true }                        |
| `texParameteri.0`                     | `boolean`                                                                                      |
| `texParameteri.1`                     | `boolean`                                                                                      |
| `texParameteri.2`                     | `boolean`                                                                                      |
| `texSubImage2D`                       | { `0`: `boolean` = true; `6`: `boolean` = true; `7`: `boolean` = true }                        |
| `texSubImage2D.0`                     | `boolean`                                                                                      |
| `texSubImage2D.6`                     | `boolean`                                                                                      |
| `texSubImage2D.7`                     | `boolean`                                                                                      |
| `vertexAttribPointer`                 | { `2`: `boolean` = true }                                                                      |
| `vertexAttribPointer.2`               | `boolean`                                                                                      |

**Defined in**

[framework/util/webgl-debug.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/webgl-debug.ts#L18)
