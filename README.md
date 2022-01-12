# PyTorch Implementation of PaletteNet

This GitHub repository contains the PyTorch implementation of [PaletteNet: Image Recolorization with Given Color Palette](https://openaccess.thecvf.com/content_cvpr_2017_workshops/w12/papers/Cho_PaletteNet_Image_Recolorization_CVPR_2017_paper.pdf) (Cho et al., 2017). 

I used a Jupyter Notebook to demonstrate the implementation for the following two reasons:
1. The authors did not provide the dataset for their experiments, so my team crawled images and their palettes from Dribbble. My intention here is not to create a data pipeline here; instead, I want to showcase the models quickly. The example dataset is [here](https://github.com/yongzx/PaletteNet-PyTorch/blob/master/example_dribbble_designs.tsv), and we cannot share the full dataset that we used.
2. There are many helper functions needed for successful training of the models, such as extracting the luminance of an image. I believe putting all the helper functions in one place with the model training process (instead of compartmentalizing the utility functions) makes reading my codes simpler. 

I have commented on the codes inside the notebook, so it's easy to follow my implementation.
