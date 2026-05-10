# 熊出没之熊大快跑2018 - 初音未来Mod版

## 项目简介

本项目是对已停运游戏「熊出没之熊大快跑2018」的Mod修改版，将游戏中的「功夫熊猫」角色替换为初音未来。

## 修改内容

| 修改项 | 原版 | Mod版 |
|--------|------|-------|
| 角色名称 | 功夫熊猫 | 初音未来 |
| 角色贴图 | 熊猫造型 | 初音未来VRM模型纹理 |
| 角色描述 | 传说中拯救世界的大侠 | 来自未来的虚拟歌姬 |

### 纹理替换详情

使用 GitHub 开源项目 [outrine/HatsuneMiku_VRM_Model](https://github.com/outrine/HatsuneMiku_VRM_Model) 提供的初音未来VRM模型，提取以下纹理并合成到游戏角色贴图中：

- `body00.png` - 身体贴图
- `face1.png` - 脸部贴图
- `hair.png` - 头发贴图
- `eye1.png` - 眼睛贴图

替换了以下游戏内纹理文件：

- `xiongmaozhuang` (功夫熊猫装)
- `xiongda2017` (熊大2017)
- `Tex_juese_dongganxiongda` (动感熊大)
- `Tex_juese_meixiongwang` (美熊王)
- 以及9个配饰/鞋子纹理

## 技术细节

- 游戏引擎：Unity 4.3.1f1
- 工具：UnityPy (Python) 用于纹理替换
- 签名：V1/V2/V3 签名方案
- APK大小：约82MB

## 安装说明

1. 卸载原版游戏
2. 下载Release中的APK文件
3. 允许未知来源安装
4. 安装Mod版APK

## 免责声明

本项目仅供学习研究用途，初音未来模型版权归原作者所有。
