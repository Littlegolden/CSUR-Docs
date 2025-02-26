# 常见问题
::: tip
以下整理了Steam工坊、B站等社交媒体上玩家关于旧版CSUR的问题来给出答复。其中有一些问题在新版CSUR中已被修复，另一些问题属于CSUR系统本身的特性。
:::

## CSUR的大部分双向主路都只能在一侧放置公交车站，这个怎么解决？
- 问题在新版CSUR中已修复。新版CSUR的所有对称双向路都可以正常放置公交车站。

## 如果删掉桥墩之后再打开游戏，CSUR的路面会发生奇怪的扭曲
- 问题在新版CSUR中已修复。老版CSUR有这个问题是因为部分组件里面有一个只有电线需要用的选项被打开了，导致删掉桥墩后游戏认为是电线缺失了柱子，从而出现的bug。

## 平移模块无法弯曲，连接后中间有空隙，很难调整角度
- 旧版CSUR的平移模块特意设计为不能弯曲，这样可以在几乎不改变模型的情况下调整车辆路径，防止车子飞出去。新版CSUR取消了这个设计，平移模块是平滑的曲线。

## 平移模块车子的路径很奇怪，有时候甚至会飞出去
- 游戏机制使得车辆路径必须平行于道路区段，所以平移模块车子无法沿着标线行驶。新版CSUR的2车道及以上平移模块通过减少一条有效车道解决这一问题，旧版CSUR的解决方法见上条。

## CSUR需要DLC才能用吗？
- 新版CSUR的所有模块不需要任何DLC。

## 两种路之间（如4DR和6DR）有没有转换模块？
- 新版CSUR的接口模块是程序计算出来的。任意两组可以连接的道路之间都会有接口模块。老版CSUR中的双向接口由新版的两个相反的单向接口代替。

## 有没有带BRT专用道的道路模块？
- 新版CSUR带有BRT道路，最中间的两条车道供快速公交行驶。

## 路口能不能设置左转待行区？
- 左转待行区需要额外的Mod支持，目前新版CSUR不能设置左转待行区。

## 为什么我的地面模式上路面长了草？
- CSUR带有偏移的道路不会剪切地形，所以默认地面上的草会直接显示在路面上。可以通过Surface Painter涂刷水泥覆盖，或者使用Remove Decoration Sprites或hide it除去地面的草。

## 如何把CSUR对接原版马路和高速？
- CSUR可以和原版的六车道以下道路直接连接。和原版高速连接时连接处会凹下去一块，建议用Ploppable Asphalt覆盖。

## 怎么用find it找到我需要的模块？
- 新版CSUR的命名是完全标准的。只要搜索你想连接的道路，用空格分开（如4R 2R4P），就可以搜到对应的接口模块。

## 我一定需要用某个模块，但是工坊没有发布怎么办？
- 请在本网站下载CSUR道路生成软件并在工坊订阅道路导入MOD，参照教程页面（施工中）的步骤生成模块。

## 能否发布通过CSUR程序和附带模型自定义的道路模块？
- CSUR发布版本的模型和贴图由AmamIya制作，使用CC-BY-NC-ND许可。这种许可证不允许用户根据该素材制作衍生品公开发布。简单来说，用自带模型制作的CSUR模块可以自己使用与私人分享，但不能发布至Steam工坊。

## 能否发布由自己制作模型和贴图再用CSUR程序生成的道路？
- CSUR是一套开源软件，使用GPL 3.0许可。只要你制作模型和贴图使用的素材允许，你可以自由发布通过CSUR软件制作的道路。CSUR模型单元和贴图的制作标准请参照此页面（施工中）。

