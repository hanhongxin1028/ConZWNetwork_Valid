<div align="center">

[![CN](https://img.shields.io/badge/🇨🇳_中文-FF0000?style=flat-square)](README.zh-CN.md)
[![EN](https://img.shields.io/badge/🇺🇸_English-007ACC?style=flat-square)](README.md)

# ConZWNetwork 研究🔬

</div>


<div style="background-color: #f0f8ff; padding: 15px; border-left: 5px solid #8A2BE2; border-radius: 5px; margin: 20px 0;">
  <strong style="color: #8A2BE2;">❗ 重要通知</strong><br>
  本工具为论文《ConZWNet: A Contrastive Learning-based Zero-Watermark Network for High Robustness and Distinguishability》的官方实现。源码和权重将在论文正式接收后全部公开，敬请期待！
</div>

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

   ![🖼️ 示例图片](https://github.com/user-attachments/assets/d3750887-5593-471e-9292-c417fc805a3f)

