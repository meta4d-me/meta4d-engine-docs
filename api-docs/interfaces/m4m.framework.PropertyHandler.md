# m4m.framework.PropertyHandler

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / PropertyHandler

## Interface: PropertyHandler

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).PropertyHandler

### Callable

#### PropertyHandler

▸ **PropertyHandler**(`target`, `source`, `property`, `handlers`, `serialization`): `boolean`

序列化属性函数项

**Parameters**

| Name            | Type                                                         | Description           |
| --------------- | ------------------------------------------------------------ | --------------------- |
| `target`        | `any`                                                        | 序列化后的对象，存放序列化后属性值的对象。 |
| `source`        | `any`                                                        | 被序列化的对象，提供序列化前属性值的对象。 |
| `property`      | `string`                                                     | 序列化属性名称               |
| `handlers`      | [`PropertyHandler`](m4m.framework.PropertyHandler.md)\[]     | 序列化属性函数列表             |
| `serialization` | [`Serialization`](../classes/m4m.framework.Serialization.md) | 序列化工具自身               |

**Returns**

`boolean`

返回true时结束该属性后续处理。

**Defined in**

[framework/util/serialization.ts:68](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/util/serialization.ts#L68)
