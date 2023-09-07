# DL-Face-Recognition
This repository is based on a project completed as part of the Deep Learning Specialization on Coursera by DeepLearning.AI. 

## Introduction
The goal of this repository is to build a face recognition system with ideas from [FaceNet](https://arxiv.org/pdf/1503.03832.pdf). 

Face recognition problems commonly fall into two categories: 

- **Face Verification** - "is this the claimed person?". For example, at some airports, you can pass through customs by letting a system scan your passport and then verifying that you (the person carrying the passport) are the correct person. A mobile phone that unlocks using your face is also using face verification. This is a 1:1 matching problem. 
- **Face Recognition** - "who is this person?". For example, the video lecture showed a face recognition video (https://www.youtube.com/watch?v=wr4rx0Spihs) of Baidu employees entering the office without needing to otherwise identify themselves. This is a 1:K matching problem. 

FaceNet learns a neural network that encodes a face image into a vector of 128 numbers. By comparing two such vectors, you can then determine if two pictures are of the same person.
    
**In this assignment, the following items were explored:**
- Implement the triplet loss function
- Use a pretrained model to map face images into 128-dimensional encodings
- Use these encodings to perform face verification and face recognition

## Credits and References
- [Deep Learning Specialization, Coursera](https://www.coursera.org/specializations/deep-learning?utm_medium=sem&utm_source=gg&utm_campaign=B2C_NAMER_deep-learning_deeplearning-ai_FTCOF_specializations_country-US-country-CA&campaignid=904733485&adgroupid=46370300620&device=c&keyword=coursera%20ai&matchtype=b&network=g&devicemodel=&adposition=&creativeid=415429098219&hide_mobile_promo&gclid=CjwKCAjw6eWnBhAKEiwADpnw9hljnzqyV-ElnDB_Tzr6cgek7YH6P3dWuoU2oR8EV71I6KW6XwS1PBoCokEQAvD_BwE)
- [pytorch version of the original implementation](https://github.com/furkanu/deeplearning.ai-pytorch)



