# ComfyUI_JoyAI_Image

[JoyAI-Image](https://github.com/jd-opensource/JoyAI-Image):Awakening Spatial Intelligence in Unified Multimodal Understanding and Generation



Update
-----
* support te use gguf, use less memory(all need 40G RAM ) / te支持gguf，内存占用更少(共占用40G左右，压缩了24G)，模型在hg或者夸克云
* Support gguf now, use less memory / 支持gguf，内存占用更少，模型在hg或者夸克云


1.Installation  
-----

* In the ./ComfyUI/custom_nodes directory, run the following:   

```
git clone https://github.com/smthemex/ComfyUI_JoyAI_Image
```

2.requirements  
----

```
pip install -r requirements.txt

```

3.checkpoints 
----

* transformers/gguf/vae/clip  [links](https://huggingface.co/jdopensource/JoyAI-Image-Edit) 
* or [夸克云](https://pan.quark.cn/s/e20f511c921c)
* or [hg](https://huggingface.co/smthem/JoyAI-Image-Edit-merge-dit-gguf)

```
├── ComfyUI/models/
|     ├── diffusion_models/
|        ├──joy_image_transformer.safetensors # optional
|     ├── gguf/
|        ├──joy_image_transformer-Q8_0.gguf # optional
|        ├──JoyAI-Image-Und-merger-Q6_K.gguf # optional te
|     ├── vae/
|        ├──Wan2.1_VAE.pth
|     ├── clips
|        ├──JoyAI-Image-Und-merger_bf16.safetensors # te optional
```

4.Example
----

![](https://github.com/smthemex/ComfyUI_JoyAI_Image/blob/main/example_workflows/example.png)
![](https://github.com/smthemex/ComfyUI_JoyAI_Image/blob/main/example_workflows/example2.png)
![](https://github.com/smthemex/ComfyUI_JoyAI_Image/blob/main/example_workflows/example3.png)
* dit gguf
![](https://github.com/smthemex/ComfyUI_JoyAI_Image/blob/main/example_workflows/example_q.png)
* TE gguf
![](https://github.com/smthemex/ComfyUI_JoyAI_Image/blob/main/example_workflows/example_te.png)

5.Citation
----

```
@jd-opensource

```



