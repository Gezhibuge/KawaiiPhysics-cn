# KawaiiPhysics 简体中文补丁包
Kawaii Physics：卡哇伊物理的中文补丁包，使 KawaiiPhysics 支持简体中文
[>>>查看视频<<<](https://www.bilibili.com/video/BV1K1pd68EbU/)
---
1. ### 介绍

**卡哇伊物理中文补丁包** 是由 [鸽纸不鸽](https://space.bilibili.com/615931229) 制作的 [Kawaii Physics](https://github.com/pafuhana1213/KawaiiPhysics) 的**中文补丁**，原开源插件 Kawaii Physics 通过 UE 本地化支持英文与日语，基于此，制作了**中文补丁包**

只要是支持通过本地化显示的文本，就均被翻译为了简体中文，包括但不限于 **节点名称**、**可设置项**、**节点描述**

*鸽纸不鸽* 制作，如果您觉得还不错的话，请**点个 Starts** 与**给个三连**吧\~

---
2. ### 安装

由于 Kawaii Physics 目前的 `Releases 版`暂**不支持本地化**，所以您需要**自行下载源码版进行编译**

1. ##### 准备
* Kawaii Physics 插件的源码
* 任意版本的 `UE5 `*（中文补丁使用 UE5.6.1 制作）*
* `Visual Studio 2022`（建议有，蓝图编译插件可能会失败）

2. ##### 编译 Kawaii Physics

###### 1. 从 Github 下载  [Kawaii Physics 的源码](https://github.com/pafuhana1213/KawaiiPhysics)
在 Github 上打开 [Kawaii Physics](https://github.com/pafuhana1213/KawaiiPhysics) ，单击右上角的 `Code > Download ZIP` 下载**源代码的压缩包**，完成后**解压压缩包**，**复制**其中名为 `Plugins` 的**文件夹**

###### 2. 新建一个 C++ 项目
打开 Unreal Engine 启动器，选择 `游戏 > 空白项目`*（启动快）*，`项目默认设置` 为 `C++` ，等项目**完全打开后**关闭即可

###### 3. 编译插件
将**复制**的 `Plugins` 文件夹**粘贴到项目的根目录**，双击 `项目名.uproject` 启动项目，在**出现的弹窗中**点击 `Yes`，项目即会自动开始编译插件

###### 4. 检查插件
新建一个动画蓝图，右键搜索框输入 `kawaii` 检查下插件能否正常使用，确认无误后关闭项目即可

3. ##### 使用汉化补丁

###### 1. 下载补丁包
在夸克网盘或者 `Releases` 中**下载** `卡哇伊物理中文补丁.zip` 文件，之后解压压缩包，之后打开文件夹，复制其中名为 `KawaiiPhysics` 的**整个文件夹**

###### 2. 安装补丁包
回到**项目的根目录** > 打开 Plugins 文件夹 > 粘贴补丁包即可，记得在弹出的窗口中`**选择覆盖文件**`\~

---
3. ### 完成！

双击 `项目名.uproject` 启动项目，此时再打开**动画蓝图**查看，Kawaii Physics 的节点应该会**显示为中文**，**节点的描述**与**设置项**也应变成中文


**大功告成！**如果您觉得还不错的话，请**点个 Starts** 与**给个三连**吧\~



