# 2ndCapstoneProject_github
**Crowd counting by convolutional networks**

# Announcement
All of the images used in this project is only for personal study use. Copyright belongs to the resources.

# Problem statement: 
My idea is to count how many people in a picture or a video by a simple convolutional neural network. It is inspired when I watched some political events on the television. Those different channels would show you some videos or pictures with different numbers of people although it is from the same event. TV channels might want to be my clients and provide a more accurate number of people in their stories. They should be willing to show a really confident number especially when they are reporting particular events like the presidential election campaign. It is not only good in convincing their audience, but also in building up their reputation. 

# Datasets 

**Non-facial images:**

* CIFAR10 (C10) 
* CalTech Cars Rear background  (bg) http://www.robots.ox.ac.uk/~vgg/data3.html
* CalTech Cars Rear (car) http://www.robots.ox.ac.uk/~vgg/data3.html 
* Place365 CNNs (ls) http://places2.csail.mit.edu/download.html

**Facial images:**

* MS-Celeb-1M (https://www.msceleb.org/)
    + Sample ImageThumbnails Data (full)
    + Sample FaceCropped Data (crop)
    + Sample FaceAligned Data (align)
* Labeled faces in the wild (lfw) http://vis-www.cs.umass.edu/lfw/
* CalTech Human Face Front (face) http://www.robots.ox.ac.uk/~vgg/data3.html

# iPython notebooks (follow the order as following)
* **Facial recognition classifier derived from convolutional networks.ipynb**: test different dataset combinations based on 32x32 images in Keras's convolutional neural network
* **Facial recognition classifier derived from convolutional networks + augmentation.ipynb**: use Keras's augmentation preprocessing to add more varieties in classifier training
* **Evaluate facial CNN classifiers by other datasets.ipynb**: use different datasets to test my models
* **Facial recognition classifier + sliding windows.ipynb**: model + sliding window + heat map (crowd counting)

# Files
* **2nd CapstoneProject_Milestone part1.docx**: the results of model evaluation
* **2nd CapstoneProject_Milestone part2.pdf**: the results of crowd counting
* **Crowd counting presentation.pdf**: Slides for project's presentation