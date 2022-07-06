# m4m.framework.Ibody

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / Ibody

## Interface: Ibody

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).Ibody

### Table of contents

#### Properties

* [angle](m4m.framework.Ibody.md#angle)
* [angularSpeed](m4m.framework.Ibody.md#angularspeed)
* [angularVelocity](m4m.framework.Ibody.md#angularvelocity)
* [bounds](m4m.framework.Ibody.md#bounds)
* [collisionFilter](m4m.framework.Ibody.md#collisionfilter)
* [density](m4m.framework.Ibody.md#density)
* [force](m4m.framework.Ibody.md#force)
* [friction](m4m.framework.Ibody.md#friction)
* [frictionAir](m4m.framework.Ibody.md#frictionair)
* [frictionStatic](m4m.framework.Ibody.md#frictionstatic)
* [id](m4m.framework.Ibody.md#id)
* [inertia](m4m.framework.Ibody.md#inertia)
* [inverseInertia](m4m.framework.Ibody.md#inverseinertia)
* [inverseMass](m4m.framework.Ibody.md#inversemass)
* [isSensor](m4m.framework.Ibody.md#issensor)
* [isSleeping](m4m.framework.Ibody.md#issleeping)
* [isStatic](m4m.framework.Ibody.md#isstatic)
* [mass](m4m.framework.Ibody.md#mass)
* [motion](m4m.framework.Ibody.md#motion)
* [name](m4m.framework.Ibody.md#name)
* [parts](m4m.framework.Ibody.md#parts)
* [position](m4m.framework.Ibody.md#position)
* [restitution](m4m.framework.Ibody.md#restitution)
* [sleepThreshold](m4m.framework.Ibody.md#sleepthreshold)
* [slop](m4m.framework.Ibody.md#slop)
* [speed](m4m.framework.Ibody.md#speed)
* [tag](m4m.framework.Ibody.md#tag)
* [timeScale](m4m.framework.Ibody.md#timescale)
* [torque](m4m.framework.Ibody.md#torque)
* [type](m4m.framework.Ibody.md#type)
* [velocity](m4m.framework.Ibody.md#velocity)
* [vertices](m4m.framework.Ibody.md#vertices)

### Properties

#### angle

• **angle**: `number`

旋转角度

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:657](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L657)

***

#### angularSpeed

• **angularSpeed**: `number`

角速度值

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:661](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L661)

***

#### angularVelocity

• **angularVelocity**: `number`

角速度向量

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:671](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L671)

***

#### bounds

• **bounds**: `Object`

**Type declaration**

| Name    | Type                              |
| ------- | --------------------------------- |
| `max`   | { `x`: `number` ; `y`: `number` } |
| `max.x` | `number`                          |
| `max.y` | `number`                          |
| `min`   | { `x`: `number` ; `y`: `number` } |
| `min.x` | `number`                          |
| `min.y` | `number`                          |

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:634](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L634)

***

#### collisionFilter

• **collisionFilter**: [`collisionFilter`](m4m.framework.collisionFilter.md)

碰撞筛选属性对象

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:652](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L652)

***

#### density

• **density**: `number`

密度

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:680](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L680)

***

#### force

• **force**: [`Ivec2`](m4m.math.Ivec2.md)

力

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:650](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L650)

***

#### friction

• **friction**: `number`

摩擦力

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:665](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L665)

***

#### frictionAir

• **frictionAir**: `number`

空气摩擦力

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:663](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L663)

***

#### frictionStatic

• **frictionStatic**: `number`

静态摩擦力

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:667](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L667)

***

#### id

• **id**: `number`

身份ID

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:673](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L673)

***

#### inertia

• **inertia**: `number`

惯性值

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:685](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L685)

***

#### inverseInertia

• **inverseInertia**: `number`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:686](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L686)

***

#### inverseMass

• **inverseMass**: `number`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:683](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L683)

***

#### isSensor

• **isSensor**: `boolean`

传感器的标志 , 开启时触发碰撞事件

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:642](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L642)

***

#### isSleeping

• **isSleeping**: `boolean`

睡眠状态

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:640](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L640)

***

#### isStatic

• **isStatic**: `boolean`

静态

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:644](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L644)

***

#### mass

• **mass**: `number`

质量

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:682](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L682)

***

#### motion

• **motion**: `number`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:674](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L674)

***

#### name

• **name**: `string`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:655](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L655)

***

#### parts

• **parts**: [`Ibody`](m4m.framework.Ibody.md)\[]

成员

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:636](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L636)

***

#### position

• **position**: [`Ivec2`](m4m.math.Ivec2.md)

重心点位置

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:646](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L646)

***

#### restitution

• **restitution**: `number`

弹性值

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:669](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L669)

***

#### sleepThreshold

• **sleepThreshold**: `number`

睡眠阈值

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:678](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L678)

***

#### slop

• **slop**: `number`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:687](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L687)

***

#### speed

• **speed**: `number`

位移速度值

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:659](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L659)

***

#### tag

• **tag**: `string`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:654](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L654)

***

#### timeScale

• **timeScale**: `number`

时间缩放

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:689](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L689)

***

#### torque

• **torque**: `number`

扭矩

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:676](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L676)

***

#### type

• **type**: `string`

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:653](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L653)

***

#### velocity

• **velocity**: [`Ivec2`](m4m.math.Ivec2.md)

速率向量 , 想要改变它 需要通过给它施加力

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:648](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L648)

***

#### vertices

• **vertices**: [`Ivec2`](m4m.math.Ivec2.md)\[]

顶点集合

**Defined in**

[framework/2d/physicEngine/physicEngine2d.ts:638](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/2d/physicEngine/physicEngine2d.ts#L638)
