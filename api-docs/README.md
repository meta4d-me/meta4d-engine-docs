@meta4d/engine / [Exports](modules.md)

# M4M
M4M 是一个基于HTML5 技术栈的，多平台3D 游戏引擎库。

### 特性
- unity场景模型资源导出
- 资源 unity场景模型导出
- 资源 gltf 模型
- 资源 基本纹理 ".png" ".jpg"
- 资源 压缩纹理 "ASTC" "ETC" "PVR" 
- 资源 hdr纹理 ".hdr" ".raw"
- 资源 图集
- 3D 骨骼动画
- 3D 节点关键帧动画
- 3D 特效系统
- 3D 物理系统（oimo.js、cannon.js）
- 3D 空间UI容器
- 场景 环境 灯光、雾效
- 场景 pick功能 
- 场景 gameObject + component 管理模式
- 场景 相机功能
- 场景 导航寻路网格
- 自定义游戏组件脚本 behavior
- 自定义编辑shader
- 渲染 静态模型
- 渲染 动态蒙皮模型
- 渲染 模型Lightmap
- 渲染 全屏后处理
- 渲染 PBR材质
- 渲染 Instance绘制
- 渲染 UI图片
- 渲染 UI SDF模式字体绘制
- 渲染 UI绘制矩形区域裁剪
- 键盘鼠标input
- 2D UI组件 "图片" "按钮" "文本框" "滑动框" "文本输入框"
- 2D UI事件系统
- 2D spine骨骼动画
- 2D 物理系统（matter.js）
- 音频系统
- 完善的数学库
- 二进制读写工具
### 目录结构
* enginesource
* &emsp;|---src&emsp;//引擎源码
* &emsp;|---lib&emsp;//引擎编译发布
* &emsp;|---examples&emsp;//样例
* &emsp;&emsp;|---engineExample&emsp;(git submodule)&emsp;//引擎样例
* &emsp;&emsp;&emsp;|---code&emsp;//引擎样例源码
* &emsp;&emsp;&emsp;|---exampleResource&emsp;(git submodule)&emsp;//样例资源
* &emsp;&emsp;&emsp;|---lib&emsp;//样例lib
* &emsp;&emsp;|---wasmBoy&emsp;(git submodule)&emsp;//gameboy pbr渲染 + GB模拟器
* &emsp;|---docs&emsp;(git submodule)&emsp;//引擎文档
* &emsp;&emsp;|---APIDoc&emsp;//引擎API文档
* &emsp;&emsp;|---tools&emsp;//引擎文档工具
* &emsp;&emsp;&emsp;|---typeDoc&emsp;//API文档生成工具typedoc
