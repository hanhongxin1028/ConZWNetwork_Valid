> ConZWNet: A Contrastive Learning-based Zero-Watermark Network for High Robustness and Distinguishability

# 1. introduction

`zeroWatermarkTest.exe` is one of ConZWNet's tools for testing robustness and copyright discrimination.



# 2. test dataset

We have prepared a set of test data under the folder `test_images` .  

The attacked_host_images subfolder stores various attack versions of the original host image, and the copyright subfolder stores 200 copyrighted images.



# 3. how to use?

Just upload the corresponding pictures according to the prompts on the interface. 

After the three pictures are uploaded, click `Run Robustness Test`to test it.

After calculation, the `Pred Copyright Label` shows the identifier of the copyright image you uploaded, while the `NC` shows the similarity between the two zero-watermarks.


![exe_ui](https://github.com/user-attachments/assets/36897946-ba4f-481c-bb13-f9ac1a3e7c47)
