# Talk2Mute
## Abstract
Sign language is an incredible advancement that has grown over the
years. Unfortunately, there are some drawbacks that have come along
with this language. Not everyone knows how to interpret a sign
language when having a conversation with a deaf and dumb person.
There is always a need to communicate using sign language. One
finds it hard to communicate without an interpreter. To solve this, we
need a product that is versatile and robust. We need to convert the
sign language so that it is understood by common people and will
help them to communicate without any barriers.
The main objective of this project is to recognize the gestures and
display the corresponding word. The first phase involves capturing
the gesture using a webcam along with pose estimation library. The
webcam captures the image and image is processed with pose
estimation algorithm in tensor-flow utility. The webcam reads the
image and the skeleton mapped on the image is the result of the pose
estimation library. The skeleton obtained provides the values for
creating the data set; the data set is a collection of the values of the
coordinates of the end points of the skeleton. These values are
labelled accordingly and are appended to the machine for predicting
when the input is taken. The data set created is taken up in the training
platform and machine learning algorithm is used to train the machine.
The set of values stored for a specific gesture is referred by the
machine in its training and makes it possible to predict the gesture
when the input is taken. Therefore, the system, when provided with
the proper gestures, gives out the corresponding words.

### Group Members

Vincy Anto

Sreehari

Neethuu N

Sidharth U

### Project Guide

Sajitha I
