# Introduction to FastAI

Preliminary learning steps into FastAI have provided foundational understanding in the development of deep learning techniques. 
Progressing through snippets of the provided course learning, the ease of utility without requiring significant mathematical concepts or algorithm techniques is most noticeable. 

Additionally, without having heard or used FastAI before, I was unaware that it was built upon PyTorch. Hence, FastAI provides strong integration to the additional functionality already supplied by PyTorch.

## Preprocessing Techniques
To process the data samples obtained in Question 2 from Duck Duck Go, the dataset was decoupled into two data primitives, the Dataloader and Dataset. 
- Utilising this PyTorch functionality, the modularity of information is signiifcantly increased. 
- This allows the samples and classes to be stored in the dataset and easily accessed by the Dataloader which is iterable. 

Using these techniques, large structures of data can be easily accessed and specifically the corresponding classification of the data is aligned.
Specifically, this allows the obtained data to be structured and allow easy training and modifications using FastAI.

