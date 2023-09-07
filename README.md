# DL-Face-Recognition
This repository is based on a project completed as part of the Deep Learning Specialization on Coursera by DeepLearning.AI. 

## Introduction
The objective of this project is to construct a facial recognition system inspired by [FaceNet](https://arxiv.org/pdf/1503.03832.pdf).

Facial recognition tasks are typically categorized into two main types:

- **Face Verification** - This involves confirming if the presented individual matches the claimed identity, a one-to-one (1:1) matching problem.

- **Face Recognition** - In this scenario, the objective is to identify the person in the image, a one-to-many (1:K) matching problem.

FaceNet utilizes a neural network to encode a facial image into a 128-dimensional vector. By comparing two such vectors, it becomes possible to determine whether two images depict the same individual.
    
**In this assignment, the following items were explored:**
- Implement the triplet loss function
- Use a pretrained model to map face images into 128-dimensional encodings
- Use these encodings to perform face verification and face recognition

## Credits and References
- [Deep Learning Specialization, Coursera](https://www.coursera.org/specializations/deep-learning?utm_medium=sem&utm_source=gg&utm_campaign=B2C_NAMER_deep-learning_deeplearning-ai_FTCOF_specializations_country-US-country-CA&campaignid=904733485&adgroupid=46370300620&device=c&keyword=coursera%20ai&matchtype=b&network=g&devicemodel=&adposition=&creativeid=415429098219&hide_mobile_promo&gclid=CjwKCAjw6eWnBhAKEiwADpnw9hljnzqyV-ElnDB_Tzr6cgek7YH6P3dWuoU2oR8EV71I6KW6XwS1PBoCokEQAvD_BwE)
- [pytorch version of the original implementation](https://github.com/furkanu/deeplearning.ai-pytorch)



