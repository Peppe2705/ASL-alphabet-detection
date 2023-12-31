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
After the images were collected, an annotation phase was required. A tool called <a href="https://www.cvat.ai/">Computer Vision Annotation</a> was used to draw outlines for object detection. This process facilitated the clear identification and delineation of the signs within the images.

<h3> Export phase </h3>
Finally, the work has been exported in a format compatible with the requirements of our YOLOv8 model. Essentially, our labels are text files containing five values each: the first represents the object class identifier, the second and third represent the x and y coordinates of the object within the image, while the fourth and fifth values represent the width and height of the object in the image.

<h2> Model </h2>

For the development of our final model, <a href="https://github.com/ultralytics/ultralytics">YOLOv8 </a> (You Only Look Once version 8) was utilized, renowned for its exceptional object detection accuracy and computational efficiency. YOLOv8 employs a 'single-stage' approach and provides real-time precision across a range of devices, including those with limited resources. It is widely used in computer vision projects due to its versatility. Specifically, the pre-trained YOLOv8n model proved to be instrumental, enabling us to achieve optimal performance right from the outset.

<h2> Use Case</h2>

https://github.com/Peppe2705/ASL-alphabet-detection/assets/132920381/43c49bb9-d6d1-4ba9-ba3b-86c08391244f

<h2> Contact Information </h2>

In case of further information or questions, please feel free to contact me. You can find my contact details in my profile.
