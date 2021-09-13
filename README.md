# Face-Recognition-and-Identification
The model is be able to recognize the faces most accurately even if the images of the person are blurry, or with extra  filters, or even if the images of the person are little old and even if the images are at different angles. The model is developed using CNN. The image processing technique using keras is performed on a training dataset to process the images and obtain pixel values. Since we are working with coloured images each pixel has three different values called RGB(Red Blue Green) values as a combination RGB can produce all possible colour pallets. Various layers are used as part of the Neural Network to train the model to produce accurate predictions.

# Preprocessing and Training The Model:

Since we are considering different varieties of pictures like, pictures with different lightings, angles, filters and many more, pre-processing really helps to maintain the unity of pictures for the training. The hyper parameters present helps to generate slightly twisted versions of the original image, which leads to a better model, since it learns on the good and bad mix of images. These transformations are only done on a training set and not on a testing dataset.

![image](https://user-images.githubusercontent.com/59678549/132974090-cbdc25cb-6ff7-42d0-8dda-d9c73223294b.png)

We flatten the output of the convolutional layers to create a single long feature vector and then it is connected to the final classification model, which is called a fully-connected layer.

![image](https://user-images.githubusercontent.com/59678549/132974128-1819549b-ee3e-4a74-b645-b10fa53ac99b.png)

# Predictions:

![image](https://user-images.githubusercontent.com/59678549/132974205-20471901-3bcf-4dba-b41f-28028cd521cd.png)

![image](https://user-images.githubusercontent.com/59678549/132974212-29c29a0f-6b08-45a4-9abe-dc0a3efac5bb.png)

# Challenges faced:

![pose_variations](https://user-images.githubusercontent.com/59678549/133034835-6b2dcf79-4aaf-49ca-b4ca-0d1783d18957.PNG)

![expre](https://user-images.githubusercontent.com/59678549/133034867-95579fe7-29d5-45b9-82eb-015768b44480.PNG)







