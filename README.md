# ASL-alphabet-detection
This project aims to detect and recognize hand gestures in the American Sign Language (ASL) alphabet. We have created a custom dataset containing images of ASL gestures and trained a YOLOv8 model for object detection.

<h2> What is ASL-alphabet? </h2>

The ASL Alphabet, also known as the American Sign Language alphabet, is nothing but a visual alphabet, a system of representing the letters of the alphabet using hand signs. The distinctive features that make this alphabet so important are:

1. Communication for the Deaf and Hard of Hearing: It is used as a primary or supplementary means of communication by deaf or hard of hearing individuals in the United States. It allows them to communicate effectively and express ideas, names, and other words without the use of hearing or spoken language.

2. Universality and Accessibility: The ASL Alphabet is a form of visual and gestural communication that transcends linguistic barriers and enables anyone to communicate with deaf or hard of hearing people.

3. Inclusion and Early Learning: Learning the ASL Alphabet is often encouraged in schools as part of inclusive education programs. This helps children develop an early understanding of sign language and promotes the inclusion of deaf or hard of hearing children in hearing communities.

<h2> Dataset </h2>
<h3> Dataset Creation </h3>
At the core of the project is the dataset creation, a critically important phase for the effective training of the sign language alphabet recognition model. A total of 1060 images has been meticulously collected, divided into 925 for the training set and 135 for the validation phase.

<h3> Annotation </h3>
After the images were collected, an annotation phase was required. [A tool called "Computer Vision Annotation"](https://www.cvat.ai/) was used to draw outlines for object detection. This process facilitated the clear identification and delineation of the signs within the images.
