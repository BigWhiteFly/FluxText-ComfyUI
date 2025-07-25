# FluText-ComfyUI
a ComfyUI custom node for FluxText,VARM >= 4GB

## how to use
1.把FluxText-ComfyUI文件夹放入ComfyUI/custom_nodes目录下
（如果你之前下载过FluxText-ComfyUI，请删掉旧版本）

2.下载flux1-fill-dev-mmgp放到ComfyUI/models/AIFSH文件夹
下载链接：https://pan.quark.cn/s/178624ad07ae

3.下载flux1_fill_dev_transformer_mmgp.safetensors把它放到ComfyUI/models/diffusion_models的文件夹
下载链接：https://pan.quark.cn/s/021778bc5373

4.下载flux1_fill_dev_text_encoder_2_mmgp.safetensors把它放到ComfyUI/models/text_encoders
下载链接：https://pan.quark.cn/s/7677715a9fcf

5.下载fluxtext把它放到ComfyUI/models/loras的文件夹
下载链接：https://huggingface.co/GD-ML/FLUX-Text/resolve/main/model_multisize/pytorch_lora_weights.safetensors

6.请安装最新的mmgp

7.启动ComfyUI开始使用
## Demo
原图

![](https://github.com/user-attachments/assets/a000c2fb-e344-4a84-a979-202e65a1872d)

编辑后
![](https://github.com/user-attachments/assets/ba49b8dd-5bf4-4a94-b738-005542e98347)
