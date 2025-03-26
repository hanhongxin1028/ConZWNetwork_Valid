<div align="center">

[![CN](https://img.shields.io/badge/🇨🇳_中文-FF0000?style=flat-square)](README.zh-CN.md)
[![EN](https://img.shields.io/badge/🇺🇸_English-007ACC?style=flat-square)](README.md)

# ConZWNetwork 研究🔬
<!-- 校徽图片，调整大小并居中 -->
<img src="https://github.com/user-attachments/assets/b68351e5-2dfc-49f5-b8fb-14ad5970e119" width="150" alt="nufe">

</div>


> ​**❗ 重要通知**  
> 本工具为论文《ConZWNet: A Contrastive Learning-based Zero-Watermark Network for High Robustness and Distinguishability》的官方实现。
> 源码将在论文正式接收后全部公开，敬请期待！

## 🚀 如何使用

1. ​**📥 下载工具**  
   点击此链接直接下载最新的 `zip` 文件：  
   [📦 ConZWNetwork_Valid.zip](https://github.com/hanhongxin1028/ConZWNetwork_Valid/releases/download/v1.0/ConZWNet_valid.zip)

2. ​**📂 文件说明**  
   - `zeroWatermarkTest.exe`: 主程序文件，用于运行工具。  
   - `test_images/`: 测试图像文件夹，包含工具运行所需的测试用例。  
   - `README.md`: 使用说明文档，包含详细的使用指南和注意事项。  
   - `weights/`: 预训练权重文件夹，包含模型所需的权重文件。

3. ​**🛠️ 使用步骤**  
   - ​**步骤 1**: 解压下载的 `zip` 文件。  
   - ​**步骤 2**: 双击打开 `zeroWatermarkTest.exe`。  
   - ​**步骤 3**: 根据提示上传对应的三张图片（在 `test_images` 文件夹下提供了一组测试用例）。  
   - ​**步骤 4**: 点击 `Run Robustness Test` 开始测试网络的表现。  
   - ​**步骤 5**: 查看结果：  
     - `Pred Copyright Label` 表示上传的版权图标签。  
     - `NC` 表示两个零水印之间的相似度。


![robust_test_example](https://github.com/user-attachments/assets/e99fa319-7992-4630-b618-611b79d47702)

