
**Overview**
- Hybrid system employing the use of multilayer Convolutional Neural Network (CNN) to extract feature form the images and a Long Short Term Memory (LSTM) to accurately structure meaningful sentences using the generated keywords
- Decoder compares target image with large dataset and generate accurate description.
- The performance of the proposed model is evaluated using standard evaluation matrices such as BLUE score.

**Data Source**
- Flickr 8K Image captioning dataset is used
- In the Flickr8k dataset, each image is associated with five different captions that describe the entities and events

**Architecture**

**Technical Approach**
- To encode our text sequence, we will map every word to a 200-dimensional vector. For this will use a pre-trained Glove model.
- GloVe is an unsupervised learning algorithm for obtaining vector representations for words
- Training is performed on aggregated global word-word co-occurrence statistics from a corpus, and the resulting representations showcase interesting linear substructures of the word vector space.
- Output is predicted using Beam Search Algorithm and Greedy Search Algorithm

 Word Vectorization uisng Tenserboard
 
**Results**

**Future Scope**
- Results can be improved using Attention based model
