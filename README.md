# HR-SARBuD
HR-SARBuD (High Resolution SAR Building Dataset) is created based on SpaceNet6 for deep learning(Details are available at https://spacenet.ai/sn6-challenge/). The dataset was originally acquired from Capella SAR satellite data (0.5m). It contains building patches of SAR image and corresponding label images. This repository was derived from co-polarization bands (HH and VV) of the SAR-Intensity folder.
There are about 23000 SAR image patches of building area and corresponding 23000 labels (Where 0 means background and 1 means building) in current version. The size of the images were set to 512×512. More image patches will be added later.

Besides, our dataset is so large that you cannot download it direcly, we start LFS service for it and you need to install lfs for your computer and download the dataset by command like "git lfs clone https://github.com/CAESAR-Radi/HR-SARBuD.git". Maybe sometimes, bandwidth of our lfs runs out in current month and you can't download it, then it will reset in next month.

Please contact us if you have any questions: wufan@aircas.ac.cn(Prof.Wu).
