# m4m.reflect

[@meta4d/engine](../) / [Exports](./) / [m4m](m4m.md) / reflect

## Namespace: reflect

[m4m](m4m.md).reflect

### Table of contents

#### Functions

* [Field](m4m.reflect.md#field)
* [FieldRef](m4m.reflect.md#fieldref)
* [UIComment](m4m.reflect.md#uicomment)
* [UIStyle](m4m.reflect.md#uistyle)
* [isComp](m4m.reflect.md#iscomp)

### Functions

#### Field

▸ **Field**(`valueType`, `defaultValue?`, `referenceType?`): (`target`: `Object`, `propertyKey`: `string`) => `void`

**`language`** zh\_CN

**`classdesc`** Field

**`version`** m4m 1.0

**Parameters**

| Name            | Type     | Default value | Description                    |
| --------------- | -------- | ------------- | ------------------------------ |
| `valueType`     | `string` | `undefined`   | 值类型                            |
| `defaultValue`  | `any`    | `undefined`   | 默认值                            |
| `referenceType` | `string` | `undefined`   | valueType 为 reference类型时 的具体类型 |

**Returns**

`fn`

▸ (`target`, `propertyKey`): `void`

**Parameters**

| Name          | Type     |
| ------------- | -------- |
| `target`      | `Object` |
| `propertyKey` | `string` |

**Returns**

`void`

**Defined in**

[io/reflect.ts:354](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/reflect.ts#L354)

***

#### FieldRef

▸ **FieldRef**(`referenceType`, `defaultValue?`): (`target`: `Object`, `propertyKey`: `string`) => `void`

Field的引用类型(修饰后，改字段将在 Inspector 中暴露 , 该函数是Field() 的封装 )

**Parameters**

| Name            | Type     | Default value | Description                                                                                |
| --------------- | -------- | ------------- | ------------------------------------------------------------------------------------------ |
| `referenceType` | `string` | `undefined`   | reference指定类型 支持:"transform"、"transform2D"、@reflect.node2DComponent、@reflect.nodeComponent |
| `defaultValue`  | `any`    | `undefined`   | 默认值                                                                                        |

**Returns**

`fn`

▸ (`target`, `propertyKey`): `void`

**Parameters**

| Name          | Type     |
| ------------- | -------- |
| `target`      | `Object` |
| `propertyKey` | `string` |

**Returns**

`void`

**Defined in**

[io/reflect.ts:380](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/reflect.ts#L380)

***

#### UIComment

▸ **UIComment**(`comment`): (`target`: `Object`, `propertyKey`: `string`) => `void`

**`language`** zh\_CN

**`classdesc`** 属性面板提示修饰

**`version`** m4m 1.0

**Parameters**

| Name      | Type     |
| --------- | -------- |
| `comment` | `string` |

**Returns**

`fn`

▸ (`target`, `propertyKey`): `void`

**Parameters**

| Name          | Type     |
| ------------- | -------- |
| `target`      | `Object` |
| `propertyKey` | `string` |

**Returns**

`void`

**Defined in**

[io/reflect.ts:403](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/reflect.ts#L403)

***

#### UIStyle

▸ **UIStyle**(`style`, `min?`, `max?`, `defvalue?`): (`target`: `Object`, `propertyKey`: `string`) => `void`

**`language`** zh\_CN

**`classdesc`** 属性面板显示方式修饰

**`version`** m4m 1.0

**Parameters**

| Name        | Type     |
| ----------- | -------- |
| `style`     | `string` |
| `min?`      | `number` |
| `max?`      | `number` |
| `defvalue?` | `any`    |

**Returns**

`fn`

▸ (`target`, `propertyKey`): `void`

**Parameters**

| Name          | Type     |
| ------------- | -------- |
| `target`      | `Object` |
| `propertyKey` | `string` |

**Returns**

`void`

**Defined in**

[io/reflect.ts:428](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/reflect.ts#L428)

***

#### isComp

▸ **isComp**(`type`): `any`

**Parameters**

| Name   | Type     |
| ------ | -------- |
| `type` | `string` |

**Returns**

`any`

**Defined in**

[io/reflect.ts:10](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/io/reflect.ts#L10)
