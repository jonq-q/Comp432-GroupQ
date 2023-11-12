# Comp432-GroupQ
Comp 432 Machine learning Group Q repo

Our project's main objective revolves around utilizing convolutional neural networks (CNNs) to detect very subtle differences in various datasets. We expect to demonstrate the adaptability of our model across different datasets. Ultimately, our goal is to highlight the versatility of CNNs.

For this project, we have two tasks to complete. For both tasks, the data preprocessing techniques used will be normalization, and data augmentation, and we will split the data 80/20 for training and testing. The first task asks us to train a CNN model to classify colorectal cancer images. We will choose ResNet-18 as our CNN architecture since it offers skip connections. T-SNE will be applied to the encoder output to help us visualize the output.

The second task will be to analyze the output of our previously trained model and a pre-trained one on datasets 2 and 3 using t-SNE visualization. For our comparative study, we will use VGG-16 from the Pytorch library to classify datasets 2 and 3. We will also conduct KNN and SVM training, and testing and measure the difference in performance between them.

By using our trained model to predict datasets 2 and 3, we expect to have better performance for the 2nd dataset since the data is still related to the medical field. The performance for both tasks will be measured by visualizing the different feature matrices, calculating the loss and accuracy, F1, and plotting the classification of different data points. These metrics will allow scientists to gain a more comprehensive insight into how trained computer vision models react to various datasets.


