[@meta4d/engine](../README.md) / [Exports](../modules.md) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / collisionFilter

# Interface: collisionFilter

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).collisionFilter

碰撞筛选属性对象
两个物体之间的碰撞将遵守以下规则：
1.两个物体的group相同且大于0时会执行碰撞，如果负数将永远不会碰撞。
2.当两个物体group不相同或等于0时将执行 类别/位掩码 的规则。

## Table of contents

### Properties

- [category](m4m.framework.collisionFilter.md#category)
- [group](m4m.framework.collisionFilter.md#group)
- [mask](m4m.framework.collisionFilter.md#mask)

## Properties

### category

• `Optional` **category**: `number`

类别 (32位 , 范围[1,2^31])

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:702](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L702)

___

### group

• `Optional` **group**: `number`

组号

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:700](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L700)

___

### mask

• `Optional` **mask**: `number`

位掩码（指定此主体可能碰撞的碰撞类别）

#### Defined in

[framework/2d/physicEngine/physicEngine2d.ts:704](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L704)
