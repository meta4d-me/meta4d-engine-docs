# m4m.framework.ClassUtils

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ClassUtils

## Class: ClassUtils

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ClassUtils

类工具

**`author`** feng3d

### Table of contents

#### Constructors

* [constructor](m4m.framework.ClassUtils.md#constructor)

#### Methods

* [addClassNameSpace](m4m.framework.ClassUtils.md#addclassnamespace)
* [getDefaultInstanceByName](m4m.framework.ClassUtils.md#getdefaultinstancebyname)
* [getDefinitionByName](m4m.framework.ClassUtils.md#getdefinitionbyname)
* [getInstanceByName](m4m.framework.ClassUtils.md#getinstancebyname)
* [getQualifiedClassName](m4m.framework.ClassUtils.md#getqualifiedclassname)

### Constructors

#### constructor

• **new ClassUtils**()

### Methods

#### addClassNameSpace

▸ `Static` **addClassNameSpace**(`namespace`): `void`

新增反射对象所在的命名空间，使得getQualifiedClassName能够得到正确的结果

**Parameters**

| Name        | Type     |
| ----------- | -------- |
| `namespace` | `string` |

**Returns**

`void`

**Defined in**

[framework/util/classutils.ts:113](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/classutils.ts#L113)

***

#### getDefaultInstanceByName

▸ `Static` **getDefaultInstanceByName**(`name`): `any`

获取默认实例

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `name` | `string` | 类名称         |

**Returns**

`any`

**Defined in**

[framework/util/classutils.ts:82](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/classutils.ts#L82)

***

#### getDefinitionByName

▸ `Static` **getDefinitionByName**(`name`, `readCache?`): `any`

返回 name 参数指定的类的类对象引用。

**Parameters**

| Name        | Type      | Default value | Description |
| ----------- | --------- | ------------- | ----------- |
| `name`      | `string`  | `undefined`   | 类的名称。       |
| `readCache` | `boolean` | `true`        | -           |

**Returns**

`any`

**Defined in**

[framework/util/classutils.ts:48](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/classutils.ts#L48)

***

#### getInstanceByName

▸ `Static` **getInstanceByName**(`name`): `any`

获取实例

**Parameters**

| Name   | Type     | Description |
| ------ | -------- | ----------- |
| `name` | `string` | 类名称         |

**Returns**

`any`

**Defined in**

[framework/util/classutils.ts:103](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/classutils.ts#L103)

***

#### getQualifiedClassName

▸ `Static` **getQualifiedClassName**(`value`): `string`

返回对象的完全限定类名。

**Parameters**

| Name    | Type  | Description                                                                         |
| ------- | ----- | ----------------------------------------------------------------------------------- |
| `value` | `any` | 需要完全限定类名称的对象，可以将任何 JavaScript 值传递给此方法，包括所有可用的 JavaScript 类型、对象实例、原始类型 （如number)和类对象 |

**Returns**

`string`

包含完全限定类名称的字符串。

**Defined in**

[framework/util/classutils.ts:18](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/classutils.ts#L18)
