# HR-SARBuD
## Introduction
HR-SARBuD (High Resolution SAR Building Dataset) is created based on SpaceNet6 for deep learning(Details are available at https://spacenet.ai/sn6-challenge/). The dataset was originally acquired from Capella SAR satellite data (0.5m). It contains building patches of SAR image and corresponding label images. This repository was derived from co-polarization bands (HH and VV) of the SAR-Intensity folder.
There are about 22000 SAR image patches of building area and corresponding 22000 labels (Where 0 means background and 1 means building) in current version. The size of the images were set to 512×512. The dataset is compressed into zip format, with a total of 3 files.

## Getting Started
Our dataset is so large that you cannot download it direcly, You can download it in two ways.<br>
You can download the dataset and checkpoint weight from [Google Drive](https://drive.google.com/drive/folders/1C2DZg1Ofz4wlgHqEceYZtxBKkC8FkzxS?usp=drive_link)<br>
You can download the dataset and checkpoint weight from [Baidu Netdisk](https://pan.baidu.com/s/1bmiebsMatTCP31CKdEQ8gA?pwd=qnhj).

## Reference
Shermeyer, J., Hogan, D., Brown, J., Etten, A.V., Weir, N., Pacifici, F., Hänsch, R., Bastidas, A., Soenen, S., Bacastow, T.M., & Lewis, R. (2020). SpaceNet 6: Multi-Sensor All Weather Mapping Dataset. 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 768-777.
