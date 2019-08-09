## -# HandWriting - AI, Machine learning

-English Deep Writer
-In this notebook I have built a deep neural network that can successfully identify writers based on their writing style. The data used to build the model was collected from IAM Handwriting database. This model is built on handwriting from 50 different writers. Each writer has written multiple paragraphs and sentences have been extracted from those paragraphs.
-Model
-I have built a multi layer CNN in Tensorflow to classify writers. The inspiration for this work comes from a paper written by Linjie Xing, Yu Qiao referenced below. They were able to successfully classify English and Chinese test. I have taken some key concepts from their paper and modified the neural network tfor this task
-Results
-Model's performance has been calculated based on a test set which has writings from among 50 writers. The model was not exposed to this data during training and validation Classification accuracy on Test Set : 94.1%
-Resources
-IAM handwriting database -[Deep Writer Paper](https://arxiv.org/abs/1606.06472) -
-\*Based on Tensorflow and JS tutorial for handwritten classification
