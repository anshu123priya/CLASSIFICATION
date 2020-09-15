# CLASSIFICATION OF PATHOLOGICAL MYOPIA
classify the fundus photos from PM patients into three labels- Pathological Myopia, High Myopia and Normal labels.

This project we've taken as BTP under Dr. Sandeep Yadav which was a very new grand challenge of 2019. In which we've provided total 400images as our training datasets, 213 for pathological myopia, 161 for normal label and only 26images for high myopia. So, our main task was to deal with very less and unbalanced datasets. We built a modal using ResNet and VGGNet 16 in which we got the maximum accuracy with ResNet model after using data augmentation as we've very unbalanced datasets. To resolve the problem of unbalanced dataset we also try of class weight but we didn't achieve that much accuracy. After that we used categorical cross entropy as our loss function which is nothing but the combination of softmax activation function and cross entropy loss function.
Atlast, we got 94.39% accuracy and 0.9075 F1 score
