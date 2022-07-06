# m4m.framework.ParticleSystemScalingMode

[@meta4d/engine](../) / [Exports](../modules/) / [m4m](../modules/m4m.md) / [framework](../modules/m4m.framework.md) / ParticleSystemScalingMode

## Enumeration: ParticleSystemScalingMode

[m4m](../modules/m4m.md).[framework](../modules/m4m.framework.md).ParticleSystemScalingMode

Control how particle systems apply transform scale.

控制粒子系统如何应用变换尺度。

**`author`** feng3d

### Table of contents

#### Enumeration Members

* [Hierarchy](m4m.framework.ParticleSystemScalingMode.md#hierarchy)
* [Local](m4m.framework.ParticleSystemScalingMode.md#local)
* [Shape](m4m.framework.ParticleSystemScalingMode.md#shape)

### Enumeration Members

#### Hierarchy

• **Hierarchy**

Scale the particle system using the entire transform hierarchy.

使用整个转换层次来缩放粒子系统。

**Defined in**

[framework/particlesystem/enums/ParticleSystemScalingMode.ts:17](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/enums/ParticleSystemScalingMode.ts#L17)

***

#### Local

• **Local**

Scale the particle system using only its own transform scale. (Ignores parent scale).

尺度粒子系统只使用自己的变换尺度。(忽略了父母规模)。

**Defined in**

[framework/particlesystem/enums/ParticleSystemScalingMode.ts:24](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/enums/ParticleSystemScalingMode.ts#L24)

***

#### Shape

• **Shape**

Only apply transform scale to the shape component, which controls where particles are spawned, but does not affect their size or movement.

只对形状组件应用变换比例，它控制生成粒子的位置，但不影响粒子的大小或移动。

**Defined in**

[framework/particlesystem/enums/ParticleSystemScalingMode.ts:31](https://github.com/meta4d-me/meta4d-engine/blob/cf6bfe6/src/framework/particlesystem/enums/ParticleSystemScalingMode.ts#L31)
