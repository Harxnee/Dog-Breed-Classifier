# Dog-Breed-Classifier
A dog breed classifier project as a part of the Udacity Nanodegree Program

#Project Goal:
In this project you will use a created image classifier to identify dog breeds using the three types of CNNs: VGG, Resnet and Alexnet. The main focus is to code using Python and the actual classifier was given (We will focus on building a classifier ourselves later in the program).

#Description:
Your city is hosting a citywide dog show and you have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. The registration system tags the images based upon the biographical information.

Some people are planning on registering pets that aren’t actual dogs.

You need to use an already developed Python classifier to make sure the participants are dogs.

Note, you DO NOT need to create the classifier. It will be provided to you. You will need to apply the Python tools you just learned to USE the classifier.


#Your Tasks:
1. Using your Python skills, you will determine which image classification algorithm works the "best" on classifying images as "dogs" or "not dogs".
2. Determine how well the "best" classification algorithm works on correctly identifying a dog's breed.
3. If you are confused by the term image classifier look at it simply as a tool that has an input and an output. The Input is an image. The output determines what the image depicts. (for example: a dog). Be mindful of the fact that image classifiers do not always categorize the images correctly. (We will get to all those details much later on the program).
4. Time how long each algorithm takes to solve the classification problem. With computational tasks, there is often a trade-off between accuracy and runtime. The more accurate an algorithm, the higher the likelihood that it will take more time to run and use more computational resources to run.


#Answers to questions regarding the project:
1. Did the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed? If not, report the differences in the classifications.

Answer: Yes, the three model architectures correctly classified Dog_01.jpg as 'pug'.


2. Did each of the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed of dog as that model architecture classified Dog_02.jpg? If not, report the differences in the classifications.

Answer: All three models have rightly identified the picture as dog as the file name is "dog" and the breed hasn't been identified by all the three

3. Did the three model architectures correctly classify Animal_Name_01.jpg and Object_Name_01.jpg to not be dogs? If not, report the misclassifications.

Answer: The three model architectures identified the object picture as a non-dog, and correctly classified it as a 'coffee'. 

4. Based upon your answers for questions 1. - 3. above, select the model architecture that you feel did the best at classifying the four uploaded images. Describe why you selected that model architecture as the best on uploaded image classification.

Answer: VGG and ResNet identified correctly 75% of images. Overall, the best-performing model architecture for this task was ResNet, because of its less runtime as compared to VGG.


#Final Results:
![image](https://github.com/Harxnee/Dog-Breed-Classifier/assets/91590046/0e3c1d1b-2ea2-491d-b6d6-b5286c654387)

