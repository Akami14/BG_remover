Human segmentation, i.e. high resolution extraction of humans from images, is a fascinating application with many uses. However, the problem is significantly under-constrained, making it an active area of research for developing more advanced methods. This dataset, developed by AISegment aims to help by providing a solid quality dataset of images and masks.

Quoting from the dataset author's GitHub (translated via Google Translate):

This dataset is currently the largest portrait matting dataset, containing 34,427 images and corresponding matting results.
The data set was marked by the high quality of Beijing Play Star Convergence Technology Co., Ltd., and the portrait soft segmentation model trained using this data set has been commercialized.
The original images in the dataset are from Flickr, Baidu, and Taobao. After face detection and area cropping, a half-length portrait of 600*800 was generated.
The clip_img directory is a half-length portrait image in the format jpg; the matting directory is the corresponding matting file (convenient to confirm the matting quality), the format is png, you should first extract the alpha map from the png image before training. For example, using opencv you can get an alpha map like this:

https://www.kaggle.com/code/utkarshsaxenadn/human-body-seperation-bg-removal-unet-keras

In the 1st part we solve hole problems
In the 2ed part we build up Datagenerator with solving holes problem
In the 3ed tuner for model choseng 
4 - education part
