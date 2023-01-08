# Task

## Action Detection 

The objective of this task is to recognise human action in natural dynamic scenes.
Human activities are frequently constrained by the purpose and the physical properties
of locations and demonstrate a high correlation with particular scene classes. For
example, eating often happens in the kitchen, while running is more common outdoors.


## Dataset:

Get the dataset [here](https://drive.google.com/file/d/1hN6iYh06BXLAhOI6twmMntueYqSu6CcI/view?usp=sharing).

## Problem Statement

In this problem I have to classify videos into one of the twelve categories.
The twelve classes/actions are:
1. Hand Shake
2. Run
3. Stand Up
4. Answer Phone
5. Fight Person
6. Hug Person
7. Sit Down
8. Drive Car
9. Get Out Car
10. Kiss
11. Sit Up

Reading the labels:
- In <action>.txt each line if of the format <video_name> <num>. If <num> is 1 then the
<action> which was the name of the .txt file is being performed in the video
<video_name>, similarly if <num> is -1 then the <action> is not being performed in video
<video_name>.

- Labels in the train folder correspond only to the videos in the train folder,
similar goes for the test folder.

# Prerequisites

- Python
- numpy
- pandas
- Convolution Neural Network
- Tensorflow
- Keras
- Computer Vision

# Libraries/Modules imported

- numpy
- pandas
- Tensorflow
- ImageDataGenerator
- keras
- cvzone

# Logic Applied

First I have removed all the files that have -1 in thier naming and created seperate folders for each action containing coresponding videos using python and pandas. Then I have extracted frames from the video using opencv and then applied CNN on the folders that contains videos correspondoing to their names.

###### Observation: In some videos more than one action is performed.


