# Emotion-Detector-with-CNN
Cole Sevier 			  						          sevier@usc.edu \
I chose the FER-2013 (facial expression) dataset and I did not have to do any preprocessing but the images were centered and occupy the same amount of space in the frame in order to take out any external factors besides a difference in emotion that would show variance. For my code I had 3 Conv2D layers and then 3 dense layers to improve the accuracy and overtime I kept decreasing the number of nodes and epochs while increasing the batch size to expedite the testing process. In the end I got an accuracy of .52, which I was happy with. In the future I’d like to add more epochs to improve the accuracy. I believe that this could be used to monitor patients in medical settings to check for mood and emotions through cameras. To continue this project I would like to have data from a wider range of ages to see if that impacts the accuracy of the model and honestly I would need to practice more through GitHub because I did all the code in kaggle and then had to transfer to CoLab and then GitHub.\
Dataset: \
https://www.kaggle.com/datasets/msambare/fer2013 \
Resources: \
https://pytorch.org/docs/stable/generated/torch.nn.Sequential.html \
https://www.tensorflow.org/tutorials/images/cnn \
https://matplotlib.org/stable/gallery/subplots_axes_and_figures/subplots_demo.html \
https://matplotlib.org/stable/tutorials/pyplot.html \
![image](https://github.com/user-attachments/assets/a211e834-c27c-47be-a67d-20530a9f58e0)
