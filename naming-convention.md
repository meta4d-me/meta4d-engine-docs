# Naming convention



1. 文件名和路径名必须全小写
2. 命名空间的名字必须全小写，全以m4m.xx 开头，xx 必须是经过确定的模块
   * 如m4m.io
3. 类名采用驼峰法命名，首单词小写，就算是首单词是简写，也小写
   * 如class jsLoader
   * 如class meshData
4. 函数命名法同上，可以酌情使用下划线分割
5. 变量命名法同上，可以酌情使用下划线分割，const 或者稳定不变的除外。
6. 接口名采用驼峰法命名，首字为大写的I
   * 如interface ITexture
7. 枚举名采用驼峰法命名，首单词大写，如果枚举是单选使用，使用Enum结尾，如果枚举是多选使用，使用Mask结尾
   * 如enum VertexFormatMask
   * 如enum enum MeshTypeEnum
   * 枚举中的值，首字大写，其他随意，比如可以全体大写，可以使用下划线分割或者驼峰法
8. 其他const值或者稳定不变的变量采用全大写和下划线分割
   * 如 static ONE:number;
   * 如 static SRC\_ALPHA:number;

以上命名规范仅针对公开成员，私有成员可酌情命名。
