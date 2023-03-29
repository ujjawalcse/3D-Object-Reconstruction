# 3D-Object/Human-Reconstruction
*Reconstruct 3D Object/Human from single/multiple images*

1. 3D Human Body Reconstruction without Clothes and Texture

+ Tried **SMPL**,**SMPLX**,**SMPLify-X** parametric body to reconstruct 3D body using a single image

References:
+ https://github.com/CalciferZh/SMPL
+ https://github.com/vchoutas/smplify-x
+ https://github.com/vchoutas/smplx

2. Semantic Texture Stitching for Texture Mapping

+ Tried **Semantic Texture Stitching** using images from 8 viewpoints to map texture for human body

References:
+ https://github.com/thmoa/semantic_human_texture_stitching

3. UV-GAN for Face UV Reconstruction

+ Tried **UV-GAN** to reconstruct facial UV texture

References:
+ https://arxiv.org/abs/1712.04695

4. 3D Human Body Reconstruction in Clothes with Texture

+ Tried **MGN (Multi Garment Network)** to reconstrcut human body with clothes and textures
+ Tried **PIFU**(Pixel-Aligned Implicit Function for High-Resolution 3D Human Digitization) to reconstruct 3D human body in clothes
+ Tried **PIFUHD** (Multi-Level Pixel-Aligned Implicit Function for High-Resolution 3D Human Digitization) to reconstruct 3D human body in clothes
+ Tried **Pix2Surf** for 3D clothes reconstruction and mapping to 3D body using Blender python script

References:

+ https://github.com/facebookresearch/pifuhd
+ https://github.com/shunsukesaito/PIFu
+ https://github.com/facebookresearch/pifuhd
+ https://github.com/aymenmir1/pix2surf


5. 3D Human Body Shape Measurement

+ Tried **STRAPS** deep learning model for accurate 3D human body shape and pose estimation
+ Trained **STRAPS** model on female pose and shape datasets
+ Used **body_measurement python package** to measure 3D cross sections(like Hip,Chest,Thigh,Neck,Bust etc) and 
  length (like Leg length,Hand length,Neck to Hip length etc)

References:

+ https://github.com/akashsengupta1997/STRAPS-3DHumanShapePose


6. 3D Object Reconstruction

+ Created cap and shoe synthetic data using Blender
+ Trained and Tested **PIFU** for cap and shoe reconstruction from single view image
+ Trained and Tested **Differentiable Volumetric Rendering** for cap and shoe 
  reconstruction from single and multiple view images

References:

+ https://github.com/shunsukesaito/PIFu
+ https://github.com/autonomousvision/differentiable_volumetric_rendering
