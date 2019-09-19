In order to evaluate face alignment on five facial landmarks: left eye center, right eye center, nose tip, left mouth corner and right mouth corner, I use 2995 images of AFLW dataset for testing as same as TCDCN [1]. Although TCDCN publishes the 2995 images, face bounding boxes are not provided.

I use "code face" face detection tool provided by cascaded CNN [2] to detect the faces. There are maybe some faces fail to be detected or more than one face is detected for one image, and I process these cases.

The file "AFLW_image_list.txt" shows the list of corresponding images.

References:

[1] Zhanpeng Zhang, Ping Luo, Chen Change Loy, and Xiaoou Tang, “Facial landmark detection by deep multitask learning,” in Computer Vision–ECCV 2014, pp. 94–108. Springer, 2014.

[2] Yi Sun, Xiaogang Wang, and Xiaoou Tang, “Deep convolutional network cascade for facial point detection,” in Computer Vision and Pattern Recognition (CVPR), 2013 IEEE Conference on. IEEE, 2013, pp. 3476–3483.
