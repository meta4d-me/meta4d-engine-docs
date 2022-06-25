[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / defShader

# Class: defShader

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).defShader

## Table of contents

### Constructors

- [constructor](m4m.framework.defShader.md#constructor)

### Properties

- [diffuseShader](m4m.framework.defShader.md#diffuseshader)
- [fscode](m4m.framework.defShader.md#fscode)
- [fscode2](m4m.framework.defShader.md#fscode2)
- [fscodeMaskUI](m4m.framework.defShader.md#fscodemaskui)
- [fscodeUI](m4m.framework.defShader.md#fscodeui)
- [fscodefontUI](m4m.framework.defShader.md#fscodefontui)
- [fscodeuifontmask](m4m.framework.defShader.md#fscodeuifontmask)
- [fsdiffuse](m4m.framework.defShader.md#fsdiffuse)
- [fsline](m4m.framework.defShader.md#fsline)
- [fslinetrail](m4m.framework.defShader.md#fslinetrail)
- [linetrailShader](m4m.framework.defShader.md#linetrailshader)
- [materialShader](m4m.framework.defShader.md#materialshader)
- [shader0](m4m.framework.defShader.md#shader0)
- [shaderuifront](m4m.framework.defShader.md#shaderuifront)
- [uishader](m4m.framework.defShader.md#uishader)
- [vscode](m4m.framework.defShader.md#vscode)
- [vscodeMaskUI](m4m.framework.defShader.md#vscodemaskui)
- [vscodeUI](m4m.framework.defShader.md#vscodeui)
- [vscodefontUI](m4m.framework.defShader.md#vscodefontui)
- [vscodeuifontmask](m4m.framework.defShader.md#vscodeuifontmask)
- [vsdiffuse](m4m.framework.defShader.md#vsdiffuse)
- [vsline](m4m.framework.defShader.md#vsline)
- [vslinetrail](m4m.framework.defShader.md#vslinetrail)
- [vsmaterialcolor](m4m.framework.defShader.md#vsmaterialcolor)

### Methods

- [initDefaultShader](m4m.framework.defShader.md#initdefaultshader)

## Constructors

### constructor

• **new defShader**()

## Properties

### diffuseShader

▪ `Static` **diffuseShader**: `string` = `"{\ \"properties\": [\ \"_MainTex('MainTex',Texture)='white'{}\",\ \"_AlphaCut('AlphaCut',Range(0.0,1.0)) = 0.5\"\ ]\ }"`

#### Defined in

[framework/asset/default/defshader.ts:343](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L343)

___

### fscode

▪ `Static` **fscode**: `string` = `" \ uniform sampler2D _MainTex; \ varying lowp vec4 xlv_COLOR; \ varying highp vec2 xlv_TEXCOORD0; \ void main() \ {\ lowp vec4 col_1; \ mediump vec4 prev_2;\ lowp vec4 tmpvar_3;\ tmpvar_3 = (xlv_COLOR * texture2D(_MainTex, xlv_TEXCOORD0));\ prev_2 = tmpvar_3;\ mediump vec4 tmpvar_4;\ tmpvar_4 = mix(vec4(1.0, 1.0, 1.0, 1.0), prev_2, prev_2.wwww);\ col_1 = tmpvar_4;\ col_1.x =xlv_TEXCOORD0.x;\ col_1.y =xlv_TEXCOORD0.y;\ gl_FragData[0] = col_1;\ }\ "`

#### Defined in

[framework/asset/default/defshader.ts:52](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L52)

___

### fscode2

▪ `Static` **fscode2**: `string` = `" \ void main() \ {\ gl_FragData[0] = vec4(1.0, 1.0, 1.0, 1.0);\ }\ "`

#### Defined in

[framework/asset/default/defshader.ts:72](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L72)

___

### fscodeMaskUI

▪ `Static` **fscodeMaskUI**: `string`

#### Defined in

[framework/asset/default/defshader.ts:133](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L133)

___

### fscodeUI

▪ `Static` **fscodeUI**: `string`

#### Defined in

[framework/asset/default/defshader.ts:86](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L86)

___

### fscodefontUI

▪ `Static` **fscodefontUI**: `string`

#### Defined in

[framework/asset/default/defshader.ts:229](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L229)

___

### fscodeuifontmask

▪ `Static` **fscodeuifontmask**: `string`

#### Defined in

[framework/asset/default/defshader.ts:301](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L301)

___

### fsdiffuse

▪ `Static` **fsdiffuse**: `string` = `"\ uniform sampler2D _MainTex;\ uniform lowp float _AlphaCut;\ varying highp vec2 xlv_TEXCOORD0;\ void main() \ {\ lowp vec4 tmpvar_3 = texture2D(_MainTex, xlv_TEXCOORD0);\ if(tmpvar_3.a < _AlphaCut)\ discard;\ gl_FragData[0] = tmpvar_3;\ }"`

#### Defined in

[framework/asset/default/defshader.ts:364](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L364)

___

### fsline

▪ `Static` **fsline**: `string` = `"\ varying lowp vec4 xlv_COLOR;\ void main()\ {\ gl_FragData[0] = xlv_COLOR;\ }"`

#### Defined in

[framework/asset/default/defshader.ts:392](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L392)

___

### fslinetrail

▪ `Static` **fslinetrail**: `string`

#### Defined in

[framework/asset/default/defshader.ts:446](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L446)

___

### linetrailShader

▪ `Static` **linetrailShader**: `string` = `"{\ \"properties\": [\ \"_MainTex('MainTex',Texture)='white'{}\"\ ]\ }"`

#### Defined in

[framework/asset/default/defshader.ts:440](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L440)

___

### materialShader

▪ `Static` **materialShader**: `string` = `"{\ \"properties\": [\ \"_Color('Color',Vector) = (1,1,1,1)\",\ \"_Alpha('Alpha', Range(0.0, 1.0)) = 1.0\"\ ]\ }"`

#### Defined in

[framework/asset/default/defshader.ts:400](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L400)

___

### shader0

▪ `Static` **shader0**: `string` = `"{\ \"properties\": [\ \"_MainTex('MainTex',Texture)='white'{}\"\ ]\ }"`

#### Defined in

[framework/asset/default/defshader.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L31)

___

### shaderuifront

▪ `Static` **shaderuifront**: `string` = `"{\ \"properties\": [\ \"_MainTex('MainTex',Texture)='white'{}\"\ ]\ }"`

#### Defined in

[framework/asset/default/defshader.ts:167](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L167)

___

### uishader

▪ `Static` **uishader**: `string` = `"{\ \"properties\": [\ \"_MainTex('MainTex',Texture)='white'{}\",\ \"_MaskTex('MaskTex',Texture)='white'{}\"\ ]\ }"`

#### Defined in

[framework/asset/default/defshader.ts:79](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L79)

___

### vscode

▪ `Static` **vscode**: `string` = `"\ attribute vec4 _glesVertex; \ attribute vec4 _glesColor; \ attribute vec4 _glesMultiTexCoord0; \ uniform highp mat4 glstate_matrix_mvp; \ varying lowp vec4 xlv_COLOR; \ varying highp vec2 xlv_TEXCOORD0; \ void main() \ { \ highp vec4 tmpvar_1; \ tmpvar_1.w = 1.0; \ tmpvar_1.xyz = _glesVertex.xyz; \ xlv_COLOR = _glesColor; \ xlv_TEXCOORD0 = _glesMultiTexCoord0.xy; \ gl_Position = (glstate_matrix_mvp * tmpvar_1); \ }"`

#### Defined in

[framework/asset/default/defshader.ts:36](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L36)

___

### vscodeMaskUI

▪ `Static` **vscodeMaskUI**: `string`

#### Defined in

[framework/asset/default/defshader.ts:113](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L113)

___

### vscodeUI

▪ `Static` **vscodeUI**: `string`

#### Defined in

[framework/asset/default/defshader.ts:96](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L96)

___

### vscodefontUI

▪ `Static` **vscodefontUI**: `string`

#### Defined in

[framework/asset/default/defshader.ts:173](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L173)

___

### vscodeuifontmask

▪ `Static` **vscodeuifontmask**: `string`

#### Defined in

[framework/asset/default/defshader.ts:278](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L278)

___

### vsdiffuse

▪ `Static` **vsdiffuse**: `string` = `"\ attribute vec4 _glesVertex;\ attribute vec4 _glesMultiTexCoord0;\ uniform highp mat4 glstate_matrix_mvp;\ varying highp vec2 xlv_TEXCOORD0;\ void main()\ {\ highp vec4 tmpvar_1;\ tmpvar_1.w = 1.0;\ tmpvar_1.xyz = _glesVertex.xyz;\ xlv_TEXCOORD0 = _glesMultiTexCoord0.xy;\ gl_Position = (glstate_matrix_mvp * tmpvar_1);\ }"`

#### Defined in

[framework/asset/default/defshader.ts:350](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L350)

___

### vsline

▪ `Static` **vsline**: `string` = `"\ attribute vec4 _glesVertex;\ attribute vec4 _glesColor;\ uniform highp mat4 glstate_matrix_mvp;\ varying lowp vec4 xlv_COLOR;\ void main()\ {\ highp vec4 tmpvar_1;\ tmpvar_1.w = 1.0;\ tmpvar_1.xyz = _glesVertex.xyz;\ xlv_COLOR = _glesColor;\ gl_Position = (glstate_matrix_mvp * tmpvar_1);\ }"`

#### Defined in

[framework/asset/default/defshader.ts:378](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L378)

___

### vslinetrail

▪ `Static` **vslinetrail**: `string`

#### Defined in

[framework/asset/default/defshader.ts:422](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L422)

___

### vsmaterialcolor

▪ `Static` **vsmaterialcolor**: `string` = `"\ attribute vec4 _glesVertex;\ uniform vec4 _Color;\ uniform float _Alpha;\ uniform highp mat4 glstate_matrix_mvp;\ varying lowp vec4 xlv_COLOR;\ void main()\ {\ highp vec4 tmpvar_1;\ tmpvar_1.w = 1.0;\ tmpvar_1.xyz = _glesVertex.xyz;\ xlv_COLOR = _Color;\ xlv_COLOR.a = xlv_COLOR.a * _Alpha;\ gl_Position = (glstate_matrix_mvp * tmpvar_1);\ }"`

#### Defined in

[framework/asset/default/defshader.ts:406](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L406)

## Methods

### initDefaultShader

▸ `Static` **initDefaultShader**(`assetmgr`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `assetmgr` | [`assetMgr`](m4m.framework.assetMgr.md) |

#### Returns

`void`

#### Defined in

[framework/asset/default/defshader.ts:461](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/asset/default/defshader.ts#L461)
