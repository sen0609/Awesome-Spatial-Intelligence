# 空间智能研究图谱 / Topic Map

本页按当前研究图谱的六个主分支展开：空间感知、空间表征、空间理解、空间推理、空间生成与评测框架。包括根主题在内共 **114 个非空主题**。图谱的主题层次和作品名称保持原有内容，换行合并为顿号。

为避免图稿与文献清单版本变化造成编号错连，本页省略图谱中的引用数字。查找作品请使用名称检索 [参考文献清单](REFERENCES.md)；以该清单的当前文末编号为准。

## 空间感知

### 空间感知信号及其获取

- 二维观测信号
  - RGB/灰度图像、热红外图像、事件流
- 深度与表面几何信号
  - SGM、MVSNet、FoundationStereo、DEFOM-Stereo、Stereo Anywhere、SMFormer、Depth Anything V2、Marigold、UniDepthV2、Depth Any Camera、UniDAC、Depth Anything with Any Prior、Any to Full、Large Depth Completion Model、Need for Speed、AnchorD、DSINE
- 三维坐标信号
  - DUSt3R、VGGT、UniK3D

### 多视角空间整合

- 经典重建流程
  - MVSNet、Structure-from-Motion Revisited、Pixelwise View Selection for Unstructured Multi-View Stereo
- 三维匹配与共同坐标预测
  - DUSt3R、MASt3R
- 多视图统一几何预测
  - VGGT、Fast3R、MUSt3R
- 多视角一致性建模
  - π³、Depth Anything 3
- 连续序列空间更新
  - S-MUSt3R、CUT3R

### 主动感知与视角选择

- ActiveGAMER、POp-GS

## 空间表征

### 显式几何与基元表征

- 点云
  - LaS-Comp
- 体素与占用预测
  - KinectFusion、SSCNet、VoxFormer、SurroundOcc、UniOcc、ForecastOcc
- 网格
  - Marching Cubes、BuildAnyPoint、TopoMesh、PixARMesh
- 三维高斯泼溅
  - 3D Gaussian Splatting、PixelSplat、MVSplat

### 隐式几何与辐射场表征

- 占据场
  - Occupancy Networks、Convolutional Occupancy Networks
- 距离场与神经隐式表面
  - DeepSDF、NeuS、NeuralUDF、SparseRecon、DebSDF、Geometric Prior Uncertainty
- 神经辐射场
  - NeRF、Mip-NeRF、Instant-NGP、MU-GeNeRF、Generalizable NGP-SR

### 结构化语义表征

- 3D Scene Graph、Learning 3D Semantic Scene Graphs、ConceptGraphs、Open-Vocabulary Functional 3D Scene Graphs、Open3DSG、FunFact、Hierarchical Open-Vocabulary 3D Scene Graphs、SceneGraphFusion、RelationField、Motion-Aware Contrastive Learning

### 空间表征学习

- 几何编码
  - PointNet、PointNet++、MinkowskiNet、Geometry Awakening
- 跨模态对齐
  - ULIP、OpenShape、Uni3D、LERF、LangSplat、LangSplatV2、GALA
- 模型接口
  - PointLLM、3D-LLM、SpatialLLM、3DGraphLLM、SSR3D-LLM、Point Cloud as a Foreign Language

## 空间理解

### 三维目标检测与视觉定位

- 封闭集检测
  - VoteNet、3DETR、PointPillars、AS-Det
- 开放词汇检测
  - OpenScene、ConceptFusion、LERF、Feature 3DGS、LangSplat
- 视觉定位
  - ScanRefer、ReferIt3D、3D-LLM

### 三维语义分割与实例分割

- 封闭集分割
  - PointNet++、MinkowskiNet、Semantic-NeRF、Mask3D
- 开放词汇分割
  - LERF、Feature 3DGS、LangSplat、OpenScene、OpenMask3D、Open3DIS

### 三维场景图构建

- 封闭集场景图
  - 3D Dynamic Scene Graphs、3DSSG
- 层级场景图
  - Open3DSG、ConceptGraphs、OGScene3D、ReLaGS、Octree-Graph、Hierarchical 3D Scene Graphs

## 空间推理

### 度量类能力

- SpatialVLM、GASP、Euclid's Gift、SpatialBot、GeoWeaver、ViCA2、Perceptio、GeoSR、SpatialRGPT、VG-LLM、Spatial-MLLM、SpatialPIN、EASE

### 关系类能力

- SpatialLadder、EASE、SpatialVLM、SpatialRGPT、VG-LLM、ViCA2、Spatial-MLLM、3D-LLM、LL3DA、ChatScene、3D-LLaVA、G²VLM、QuatRoPE、Video-3D LLM、SOMA

### 视角类能力

- 3D-LLM、LL3DA、ChatScene、3D-LLaVA、G²VLM、QuatRoPE、3DThinker、GASP

### 动力学类能力

- R4、STORM、SOMA、OnlineSI、Video-3D LLM、LLaVA-OneVision-2

### 组合类能力

- ProSR、STORM、R4、SpatialLadder、3DThinker

## 空间生成

### 静态空间生成

- 三维物体生成
  - LRM、TRELLIS、Hunyuan3D 2.5、HY3D-Bench、SparseGen、Omni123、DreamFusion、ProlificDreamer、Zero-1-to-3、Wonder3D、SViM3D、PartCrafter
- 三维场景生成
  - WorldCraft、PAT3D、HOG-Layout、SplatFlow、SpatialGen、WorldGrow、HunyuanWorld 1.0、One2Scene、Gen3R、WorldAct

### 动态空间生成

- 基础视频扩散
  - Video Diffusion Models、Genie、Sora、Wan、Sora 2
- 多模态与结构化控制
  - VACE、CameraCtrl、MagicDrive、AICL
- 动作条件与可交互生成
  - Vid2World、Interactive World Simulator、RealWonder、Generated Reality、DAWN、RoVid-X

### 世界模型

- 渲染器世界模型
  - Cosmos、WorldModelBench
- 模拟器世界模型
  - World Models、DreamerV3、V-JEPA 2
- 规划器世界模型
  - OpenVLA、GR00T N1、Gemini Robotics 1.5、WorldVLA、DreamZero

## 评测框架

### 空间理解

- ScanNet、ScanNet++、EmbodiedScan、3EED、Anywhere3D、NuGrounding、OpenLex3D、ScanNet200、ScanQA、SQA3D、EASG-Bench

### 空间推理

- 单图或静态视觉输入
  - SpatiaLQA、OmniSpatial、11PLUS-Bench、IR3D-Bench、GIQ
- 多图或多视角输入
  - MMSI-Bench、SpaCE-10、MindCube、Ego3D-Bench、ReMindView-Bench、ViewSpatial-Bench、SpinBench
- 视频、三维和具身输入
  - SIBench、EASG-Bench、ScanQA、SQA3D、NuScenes-SpatialQA、Embodied3DBench、NaviTrace、Embodied4C、ESI-Bench、ESPIRE、SpatialWorld

### 空间生成

- 静态三维内容
  - 3DGen-Bench、3D Arena、T23D-CompBench、P3D-Bench、3D-FRONT、SceneEval、Multi-dimensional QA for Text-to-3D Assets
- 动态三维或四维世界
  - 4DWorldBench、LoViF、WorldScore
- 世界模型
  - WorldCoder-Bench、IR3D-Bench

