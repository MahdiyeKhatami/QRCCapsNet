# QRCCapsNet
Fashion Image Retrieval With Quadruplet Capsule Networks

Official Notebook for QRCCapsNet: A Quadruplet version of the RCCapsNet

Based on https://github.com/MahdiyeKhatami/QRCCapsNet/blob/main/Khatami_Fashion_Image_Retrieval_With_Quadruplet_Capsule_Networks.pdf

By Mahdiye Khatami mahdiye_khatami@semnan.ac.ir or m.khatami95@gmail.com


![myimage-alt-tag](https://i.postimg.cc/wM85JMdy/15.png)


# Refrences:

**Quadruplet loss function**

https://openaccess.thecvf.com/content_cvpr_2017/papers/Chen_Beyond_Triplet_Loss_CVPR_2017_paper.pdf

https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9154357

**RCCapsNet**

https://openaccess.thecvf.com/content_ICCVW_2019/papers/CVFAD/Kinli_Fashion_Image_Retrieval_with_Capsule_Networks_ICCVW_2019_paper.pdf

**RCCapsNet official code**

 https://github.com/birdortyedi/image-retrieval-with-capsules


**RCCApsNet unofficial  notebook**

 https://github.com/MahdiyeKhatami/RCCapsNet

**Deep Fashion-inshop Dataset:**

 https://drive.google.com/drive/folders/0B7EVK8r0v71pVDZFQXRsMDZCX1E?resourcekey=0-4R4v6zl4CWhHTsUGOsTstw

## Notice
1.   **Default configs:** **epochs = 1**, **multi_gpu=None**, **model_type='rc'** 
2. Added "eval_partioner_by_group(group)" and you can choose "group" in config.by default group='ALL'.you can ghange it to 'WOMEN' or 'MEN' and then edit the 'num_class' value.

