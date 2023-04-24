# Liver_tumor_segmentation_W_Net
#Intuition behind the architecture
![image](https://user-images.githubusercontent.com/89221563/234088096-1e45f2da-7d8e-4983-8eb8-54e6d35bae03.png)
# Model architecture
![Weight Layer - 1 (2)](https://user-images.githubusercontent.com/89221563/229314613-89f2c7c5-1659-42cd-8245-8ee6e9864c1e.png)

# Training-Validation curves for the evaluation metrics
![image](https://user-images.githubusercontent.com/89221563/229313676-b1fcad65-c9ba-4a35-8e15-ac121819aa87.png)
# Feature-map Analysis:
It can clearly be seen that encoder_1 focuses more on the local specifics wheres encoder_2 has a more spread-out attention map. The feature maps from the last encoder block clearly show that the first encoder has learnt to discard refions of the vertebral column and has a attention spread across very small logal targets. On the contrary the attention map of the pretrained encoder is still more evenly spreadout. This enables the model to combine local as well as global specifics from the feature maps leading to superior segmentation performance.
![image](https://user-images.githubusercontent.com/89221563/234089598-c08b690a-bff0-42f5-9137-88cab445bb58.png)
# Comparison of segmented output with ground-truth
sequence: Processed 2D CT slice, GT, Segmented Mask

![Screenshot 2023-03-23 132357](https://user-images.githubusercontent.com/89221563/227143886-1e937076-a97e-445f-8fbc-3da4a8066446.jpg)

# Comparison with the state-of-the-art:
![image](https://user-images.githubusercontent.com/89221563/234089822-99f9a808-50f0-4489-975e-52829f627aee.png)


link to the paper will be added shortly
