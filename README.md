# Person Re-Identification

### This repository is inspired by the paper [Spatial-Temporal Reidentification (ST-ReID)](https://arxiv.org/abs/1812.03282v1).

Person re-identification is a computer vision task that involves identifying a person across different camera views, based on their appearance or features. The goal is to match the same individual across different camera views, even if their appearance may have changed (e.g., due to different clothing or different lighting conditions).

Person re-identification is an important task in video surveillance, where it is often necessary to track individuals across multiple cameras in order to monitor their movements and behavior. For example, in a shopping mall, a person may be captured by one camera in the parking lot, and then later be captured by another camera inside the mall. Person re-identification can be used to match these two camera views and track the person's movements.

Person re-identification can be a challenging task, as it requires dealing with variations in appearance (e.g., due to different clothing, accessories, or lighting conditions) and handling occlusions (e.g., when a person is partially obscured by an object or another person). To address these challenges, machine learning techniques, such as deep learning, are often used to extract features from images that can be used to match individuals across different camera views.

## Dataset Description: 

Dataset Name: Market-1501
It contains 1501 identities which are captured by six different cameras, and 32,668 pedestrian 
image bounding boxes obtained using the Deformable Part Models pedestrian detector. 
Each person has 3.6 images on average at each viewpoint. 
The dataset is split into two parts: 750 identities are utilized for training and the remaining 751 
identities are used for testing.
The training set consists of 12936 images and the testing set consists of 19732 images.

## Sample Images from Training set:

![image](https://user-images.githubusercontent.com/20626950/231385006-9a110ae6-0f1e-4106-b0ab-fe0a8502651d.png)

## Sample Images from Testing set:

![image](https://user-images.githubusercontent.com/20626950/231385202-c83b1424-88e9-4e94-9c20-2369da874a76.png)

## Architecture proposed in the paper

![image](https://user-images.githubusercontent.com/20626950/231385441-6c5885eb-15ec-43e0-b0da-dcc0a1ab80b2.png)

## Below graph shows the training accuracy and training loss

![image](https://user-images.githubusercontent.com/20626950/231385661-029e0796-0ade-48f3-a1e8-5fc1de0e1503.png)

![image](https://user-images.githubusercontent.com/20626950/231385738-04667807-e20e-4e0e-bbc8-6294a84abf20.png)



