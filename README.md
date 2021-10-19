# EDSR in Tensorflow

TensorFlow implementation of [Enhanced Deep Residual Networks for Single Image Super-Resolution](https://openaccess.thecvf.com/content_cvpr_2017_workshops/w12/papers/Lim_Enhanced_Deep_Residual_CVPR_2017_paper.pdf)

It was trained on the [Div2K dataset](https://data.vision.ee.ethz.ch/cvl/DIV2K/) - Train Data (HR images).

## Requirements
- tensorflow
- numpy
- cv2

## EDSR 
This is the EDSR model, which has a different model for each scale. Architecture shown below. Go to branch 'mdsr' for the MDSR model.
![Alt text](images/EDSR.png?raw=true "EDSR architecture")
